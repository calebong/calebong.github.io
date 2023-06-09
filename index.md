---
output:
  html_document:
    keep_md: true
---

# Financial Data Analytics Portfolio

This section highlights my experience in workflow conceptualization, idea implementation, and deployment of financial and risk management analytical tools, which are used in everyday work.

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

#### Gradient boosting frameworks for probabilistic assessments of market sectors performance and risk expectations. Implementable and scalable across industries and sub sectors of many countries. The preview document highlights the workflow and analysis, as applied to the 11 main USA GIC sectors.

[Preview Document](/pdf/Preview-Monthly-Country-Industry-Forecast-Model.pdf)

<img src="images/demoRmdUsa.png?raw=true"/>

### Daily Country Industry Risk Monitoring and Forecast Model

#### Markov-switching GARCH models for market sectors risk monitoring and risk expectations assessment. Implementable and scalable across industries and sub sectors of many countries. The preview document highlights the workflow and analysis, as applied to the 11 main USA GIC sectors.


[Preview Document](/pdf/Preview-Daily-Country-Industry-Risk-Forecast-Model.pdf)

<img src="images/demoRmdUsaGarch.png?raw=true"/>

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



Last Updated: 2023-06-09 21:01:16 UTC +8

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
   <td style="text-align:left;"> https://tradingeconomics.com/canada/capacity-utilization </td>
   <td style="text-align:left;"> 2023-06-09 20:38:00 </td>
   <td style="text-align:left;"> Canada Capacity Utilization Rate Ticks Up to 81.9% in Q1 </td>
   <td style="text-align:left;"> Canadian industries operated at 81.9% of their production capacity in the first quarter of 2023, slightly higher than the upwardly revised 81.8% in the fourth quarter of 2022, largely attributed to an uptick in the manufacturing capacity utilization rate (78.1% vs 77.1% in Q4). Capacity utilization increased in 13 of the 21 major manufacturing industry groups, representing approximately 75% of the gross domestic product in the manufacturing sector, notably the manufacture of transportation equipment (80.7% vs 77%), petroleum and coal products (86.8% vs 83.8%) and fabricated metal products (78.3% vs 76.3%).  Meanwhile, capacity utilization fell in the mining, quarrying, and oil and gas extraction sector (79.5% from 80.4%) and construction (90.2% vs 90.5%). </td>
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
   <td style="text-align:left;"> Bloomberg Surveillance with Tom Keene, Jonathan Ferro &amp; Lisa Abramowicz live from New York, bringing insight on global markets and the top business stories of the day.                                                      , The economy and markets are "under surveillance". Bloomberg Surveillance, covering the latest news in finance, economics and investments.                                                                                    , If a green pivot is to happen, power grids must become “supergrids,” continent-spanning networks that can move green energy thousands of miles. The technology is here, but politics may stand in the way.                   , Citi to Cut 50 London Jobs in Investment and Corporate Banking                                                                                                                                                               , The More Inflation the Better: This Little-Discussed Insurance Broker Is Having a Moment                                                                                                                                     , Canada Sheds 17,300 Jobs in First Decline in Nine Months                                                                                                                                                                     , Fed Seen Ending Its 15-Month Hiking Campaign in Economist Survey                                                                                                                                                             , China Central Bank Governor Reiterates Stable Policy Stance                                                                                                                                                                  , Transcript: How Wildfire Smoke and Air Pollution Affect Your Health                                                                                                                                                          , Rowdy Tourists Spark Partial Airbnb Ban on Malaysian Island                                                                                                                                                                  , A Cheat Sheet to AI Buzzwords and Their Meanings                                                                                                                                                                             , UAE Fintech Optasia Hires Moelis for Potential Sale, IPO                                                                                                                                                                     , TikTok-Owner Tests ChatGPT-Style Bot After Joining China AI Race                                                                                                                                                             , Spanish Left Unites to Face Conservatives in Snap Election                                                                                                                                                                   , Labour Caves on £140 Billion Green Energy Plan Over Cost Fear                                                                                                                                                                , Tiger Global Among Hedge Funds Riding AI Mania to May Gains                                                                                                                                                                  , Bank of America Reworks Leadership in Investment Bank Unit                                                                                                                                                                   , Craft Beer’s Hottest Trend Is a Style That’s as Mass as Can Be                                                                                                                                                               , The Best Luxury Father’s Day Gifts for Dads Who Love Design                                                                                                                                                                  , This Week’s Wildfire Smoke Disaster Won’t Be the Last                                                                                                                                                                        , What’s the Best Use for Crypto? Let AI Figure It Out                                                                                                                                                                         , Musk Promised Transparency, Then Hid Twitter Data                                                                                                                                                                            , The Netflix Effect Chills Foreign Content Creators                                                                                                                                                                           , Payrolls, Prices, Productivity and Profits Hold the Answer to the Puzzling US Economy                                                                                                                                        , Will Argentina Ditch the Peso for the Dollar?                                                                                                                                                                                , Support for ESG Shareholder Proposals Plummets Amid GOP Backlash                                                                                                                                                             , Deutsche Bank Gender Gap Shows Europe Is Failing Diversity Test                                                                                                                                                              , What America Learned From the Demise of its EV Battery Pioneer                                                                                                                                                               , Transcript: How Wildfire Smoke and Air Pollution Affect Your Health                                                                                                                                                          , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                               , Connecticut May Ban Collection Tactic Used in Cash-Advance Loans                                                                                                                                                             , Deep Drought Punishes Latin American Clean Water Pioneer                                                                                                                                                                     , Binance.US Set to Be Cut Off From Banking System After SEC Lawsuit                                                                                                                                                           , FTX’s US Judge Vows to Keep Control of Crypto in Blow to Bahamas                                                                                                                                                             , SEC Seeks ‘Alternative Means’ to Serve Papers to Binance’s Zhao                                                                                                                                                              , Citigroup’s offices in Canary Wharf, London.                                                                                                                                                                                 , William Shaw                                                                                                                                                                                                                 , Subscriber Benefit                                                                                                                                                                                                           , Subscribe                                                                                                                                                                                                                    , Citigroup Inc. is planning to cut 30 investment banking jobs and 20 more in its corporate banking unit in London in its latest wave of redundancies.                                                                         , The cuts are necessary for the bank to reduce its cost base because of adverse market conditions, according to a person within the bank, who isn’t authorized to speak publicly. Financial News reported the layoffs earlier. </td>
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
   <td style="text-align:left;"> Bloomberg Surveillance with Tom Keene, Jonathan Ferro &amp; Lisa Abramowicz live from New York, bringing insight on global markets and the top business stories of the day.                                     , The economy and markets are "under surveillance". Bloomberg Surveillance, covering the latest news in finance, economics and investments.                                                                   , If a green pivot is to happen, power grids must become “supergrids,” continent-spanning networks that can move green energy thousands of miles. The technology is here, but politics may stand in the way.  , Citi to Cut 50 London Jobs in Investment and Corporate Banking                                                                                                                                              , The More Inflation the Better: This Little-Discussed Insurance Broker Is Having a Moment                                                                                                                    , Canada Sheds 17,300 Jobs in First Decline in Nine Months                                                                                                                                                    , Fed Seen Ending Its 15-Month Hiking Campaign in Economist Survey                                                                                                                                            , China Central Bank Governor Reiterates Stable Policy Stance                                                                                                                                                 , Transcript: How Wildfire Smoke and Air Pollution Affect Your Health                                                                                                                                         , Rowdy Tourists Spark Partial Airbnb Ban on Malaysian Island                                                                                                                                                 , A Cheat Sheet to AI Buzzwords and Their Meanings                                                                                                                                                            , UAE Fintech Optasia Hires Moelis for Potential Sale, IPO                                                                                                                                                    , TikTok-Owner Tests ChatGPT-Style Bot After Joining China AI Race                                                                                                                                            , Spanish Left Unites to Face Conservatives in Snap Election                                                                                                                                                  , Labour Caves on £140 Billion Green Energy Plan Over Cost Fear                                                                                                                                               , Tiger Global Among Hedge Funds Riding AI Mania to May Gains                                                                                                                                                 , Bank of America Reworks Leadership in Investment Bank Unit                                                                                                                                                  , Craft Beer’s Hottest Trend Is a Style That’s as Mass as Can Be                                                                                                                                              , The Best Luxury Father’s Day Gifts for Dads Who Love Design                                                                                                                                                 , This Week’s Wildfire Smoke Disaster Won’t Be the Last                                                                                                                                                       , What’s the Best Use for Crypto? Let AI Figure It Out                                                                                                                                                        , Musk Promised Transparency, Then Hid Twitter Data                                                                                                                                                           , The Netflix Effect Chills Foreign Content Creators                                                                                                                                                          , Payrolls, Prices, Productivity and Profits Hold the Answer to the Puzzling US Economy                                                                                                                       , Will Argentina Ditch the Peso for the Dollar?                                                                                                                                                               , Support for ESG Shareholder Proposals Plummets Amid GOP Backlash                                                                                                                                            , Deutsche Bank Gender Gap Shows Europe Is Failing Diversity Test                                                                                                                                             , What America Learned From the Demise of its EV Battery Pioneer                                                                                                                                              , Transcript: How Wildfire Smoke and Air Pollution Affect Your Health                                                                                                                                         , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                              , Connecticut May Ban Collection Tactic Used in Cash-Advance Loans                                                                                                                                            , Deep Drought Punishes Latin American Clean Water Pioneer                                                                                                                                                    , Binance.US Set to Be Cut Off From Banking System After SEC Lawsuit                                                                                                                                          , FTX’s US Judge Vows to Keep Control of Crypto in Blow to Bahamas                                                                                                                                            , SEC Seeks ‘Alternative Means’ to Serve Papers to Binance’s Zhao                                                                                                                                             , Arthur J. Gallagher &amp; Co. CEO J. Patrick Gallagher Jr.                                                                                                                                                      , Source: PRNewswire                                                                                                                                                                                          , Breanna Bradham                                                                                                                                                                                             , Subscriber Benefit                                                                                                                                                                                          , Subscribe                                                                                                                                                                                                   , It’s enemy No. 1 inside the halls of the Federal Reserve, dreaded in cash-strapped households across America and a headache for CFOs at countless companies, big and small.                                 , But bring up inflation with executives at Arthur J. Gallagher &amp; Co., an insurance broker outside Chicago, and you’ll get a very different reaction. “We win,” says J. Patrick Gallagher Jr., the firm’s CEO. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2023/06/09/business/dealbook/trump-indictment-2024.html </td>
   <td style="text-align:left;"> 2023-06-09 19:55:59 </td>
   <td style="text-align:left;"> Donald Trump’s Latest Indictment May Reshape the 2024 Race - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , DealBook Newsletter                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , The former president, who faces seven criminal charges for mishandling classified documents, is expected to surrender to authorities next week.                                                                                                                                                                                                                                                                                                                                         , By Andrew Ross Sorkin, Ravi Mattu, Bernhard Warner, Sarah Kessler, Michael J. de la Merced, Lauren Hirsch and Ephrat Livni                                                                                                                                                                                                                                                                                                                                                              , For the second time in two months, Donald Trump will surrender to the authorities to face legal charges, dropping another bomb into the 2024 presidential race. Within minutes, he was fund-raising on the back of the news.                                                                                                                                                                                                                                                            , The indictment won’t be unsealed until next week, but some details are known. The former president and front-runner for the Republican nomination faces seven criminal charges that he mishandled classified documents from his time in the White House and obstructed the government’s efforts to reclaim them. He is expected to turn himself in to the authorities on Tuesday.                                                                                                       , Mr. Trump himself broke the news last night, a sign his inner circle had been bracing for the indictment for weeks.                                                                                                                                                                                                                                                                                                                                                                     , On his Truth Social platform, Mr. Trump called the charges “election interference at the highest level,” adding, “I’m an innocent man.”                                                                                                                                                                                                                                                                                                                                                 , Mr. Trump’s legal troubles keep piling up. But this indictment holds greater “legal gravity and political peril,” writes The Times’s Peter Baker. It’s not just a first in American history for a former president, but also involves the nation’s secrets.                                                                                                                                                                                                                             , Here’s a recap of the other legal matters he faces:                                                                                                                                                                                                                                                                                                                                                                                                                                     , A federal grand jury last month ordered Mr. Trump to pay $5 million to the journalist E. Jean Carroll in a civil case that he sexually abused and then defamed her; Carroll’s legal team has sued Mr. Trump again over subsequent comments he made about her.                                                                                                                                                                                                                           , In April, the New York authorities charged Mr. Trump with falsifying business documents in connection with hush-money payments to the porn star Stormy Daniels in the run-up to the 2016 presidential election.                                                                                                                                                                                                                                                                         , Mr. Trump is also under investigation in Georgia for possible election tampering in the state; a decision is expected later this summer.                                                                                                                                                                                                                                                                                                                                                , Mr. Trump’s Republican challengers came to his defense. Gov. Ron DeSantis of Florida, his nearest rival in the polls, accused the Biden administration of weaponizing the Justice Department to take on a political rival. And Vivek Ramaswamy, the anti-woke financier, said he would pardon Mr. Trump if elected president.                                                                                                                                                           , Mr. Trump gained in the polls the last time he was charged. It is unclear if the public will be so supportive this time. A Yahoo-YouGov poll showed nearly two-thirds of Americans view the charges of removing classified documents and obstructing the investigation as a serious criminal matter; a similar percentage feel that he should not serve as president if convicted.                                                                                                      , So far, big-money conservative donors have stayed mum on the latest charges. Many have deserted Mr. Trump after backing him in previous election cycles.                                                                                                                                                                                                                                                                                                                                , The wildfire haze is moving on from the Northeast. Cities including New York and Philadelphia have seen air conditions improve, though the noxious smoke is spreading south and west; the F.A.A. has lifted ground stops at LaGuardia and Newark airports. But scientists confirmed that the El Niño weather phenomenon has started, portending hotter temperatures through next year.                                                                                                  , China suffers from a lack of inflation. New monthly data shows that producer prices fell 4.6 percent in May, the sharpest year-on-year drop in seven years, while consumer prices rose just 0.2 percent. Though a contrast from Western countries grappling with rapid inflation, the trend suggests China’s faltering economy may soon suffer from deflation.                                                                                                                          , The White House reportedly braces for the death of its student loan forgiveness program. Biden administration officials are privately worrying that the Supreme Court may strike down its proposal, which would eliminate up to $20,000 in education debt per person for millions of Americans, according to The Wall Street Journal. The White House is preparing less legally risky alternatives to help borrowers.                                                                   , G.M. electric vehicles will gain access to Tesla’s charging network. The move, which follows a similar announcement by Ford, will vastly expand charger accessibility for G.M. But some in the industry fear that wider adoption of Tesla’s plugs, which are now likely to become the industry standard, will give Elon Musk’s company even greater power over the E.V. market.                                                                                                         , Investors shrugged off lousy labor market data and a new round of inflation warnings to push the S&amp;P 500 into bull market territory on Thursday. But that enthusiasm seems to be waning on Friday morning as stock futures suggest markets will open lower.                                                                                                                                                                                                                             , The bear market lasted 248 trading days, the longest such run since 1948. Since its October low, the S&amp;P 500 has gained 20.04 percent, just enough to tip into a bull market. The benchmark index is still roughly 10 percent away from a record high; some market observers say, therefore, that it’s premature to call this a true bull market.                                                                                                                                       , Investor enthusiasm for artificial intelligence has underpinned this rally. According to Deutsche Bank analysts, the FANG+ Index — a collection of big cap tech stocks, many of which are expanding into A.I. — is up nearly 80 percent since ChatGPT debuted in November.                                                                                                                                                                                                              , Now to the bad news … A growing number of economists believe that next week’s Consumer Price Index report will show an uptick in core inflation. That could pressure the Fed to raise interest rates further — if not next week, in July.                                                                                                                                                                                                                                               , And there are signs of economic weakness. The Labor Department on Thursday reported 261,000 new jobless claims, the highest number since October 2021.                                                                                                                                                                                                                                                                                                                                  , Expect a prolonged period of economic uncertainty. That was the message from Mario Draghi, the former Italian prime minister and president of the E.C.B., in a speech on Thursday at M.I.T.                                                                                                                                                                                                                                                                                             , The economist, who once famously vowed to do “whatever it takes” to save the euro, has a bearish view of the future. He warned that industrialized economies face a “volatile cocktail” of persistent inflation, high budget deficits, high interest rates and low potential growth as central banks grapple with a climate crisis, the reshoring of supply chains and the impact of Russia’s war in Ukraine.                                                                           , Regulators and crypto executives are making their cases in the court of public opinion after the S.E.C. sued Binance and Coinbase, two of the sector’s biggest exchanges, this week in an intensifying crackdown on the industry.                                                                                                                                                                                                                                                       , “We’ve seen this story before,” the S.E.C. chairman Gary Gensler said on Thursday at a fintech conference, likening widespread noncompliance in crypto to the era of “hucksters” and fraud a century ago. He rejected claims that digital asset businesses cannot comply with the existing rules or do not realize that they apply: “When crypto asset market participants go on Twitter or TV and say they lacked ‘fair notice’ that their conduct could be illegal, don’t believe it.”, Coinbase’s boss says that new regulations are needed. Its C.E.O., Brian Armstrong, addressed the event on Wednesday, saying the rules are opaque and need to be updated. The S.E.C. case is certainly a drag on his company: Moody’s, the ratings agency, downgraded Coinbase on Thursday to negative from stable because of the charges.                                                                                                                                               , Binance is regrouping. The company’s American division said on Thursday that it would no longer allow customers to trade in U.S. dollars, after banks stopped working with it. At the same time, the S.E.C. says it is trying to find “alternative means” to serve legal papers to Binance and Changpeng Zhao, the company’s C.E.O., telling a federal court that it was difficult to determine where he was.                                                                           , Who’s judging? The S.E.C.’s case against Coinbase in New York was assigned to District Judge Jennifer Rearden. Her nomination last year angered some Democratic lawmakers because she represented Chevron as a lawyer at Gibson, Dunn &amp; Crutcher. She’s also handling the government’s appeal of the sale of the failed crypto broker Voyager to Binance’s U.S. arm and put the deal on hold in March.                                                                                  , Judge Amy Berman Jackson of the Federal District Court for D.C. is presiding over the Binance case, and is best known for overseeing the criminal proceedings against two Mr. Trump advisers, Paul Manafort and Roger Stone. Next week, she will hold a hearing on an S.E.C. request to freeze Binance’s assets.                                                                                                                                                                        , — Steven Schwartz, a lawyer who has practiced in New York for 30 years. He told a federal judge that he regrets using the chatbot to write a legal brief that was found to be filled with fake judicial opinions and legal citations.                                                                                                                                                                                                                                                   , Apple unveiled its first headset for augmented/virtual/mixed reality this week, but none of those words appears in a nine-minute video on its website about the $3,500 Vision Pro goggles. Instead, the company preferred a more obscure term: “spatial computing.”                                                                                                                                                                                                                     , Apple is trying to put its own stamp on the category. When it comes to spatial computing, “no one knows what that is — and that provides Apple the opportunity to define it,” Marcus Collins, the author of “For the Culture: The Power Behind What We Buy, What We Do and Who We Want to Be,” told DealBook.                                                                                                                                                                           , Apple has successfully done this in the past. Before the App Store, people didn’t talk about apps; they talked about “software programs.”                                                                                                                                                                                                                                                                                                                                               , And the iPhone and AirPods were neither the first mobile phone nor the first earbuds, but they became runaway hits (despite being priced at a premium to the competition).                                                                                                                                                                                                                                                                                                              , Jim Posner, a communications consultant who has led teams at Twitter and Google, said that the intended audience may be investors and the media rather than consumers. “They are pitching a product to people,” he said. “For the tech press, industry analysts and investors, they’re pitching a concept.”                                                                                                                                                                             , Elsewhere, Mark Zuckerberg gave his thoughts on Apple’s Vision Pro goggles. “I was really curious to see what they’d ship,” the Meta C.E.O. told employees on Thursday, “and it’s a good sign for our own development that they don’t have any magical solutions to the laws of physics that we haven’t already explored.”                                                                                                                                                              , Deals                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , The agricultural commodities giant Bunge is said to be finalizing a deal to buy Viterra, a grain trader, that could value the combined firm at $30 billion. (Reuters)                                                                                                                                                                                                                                                                                                                   , UBS has secured a government backstop for losses tied to its takeover of Credit Suisse, clearing the last hurdle for combining Switzerland’s top two banks. (FT)                                                                                                                                                                                                                                                                                                                        , Permira is reportedly weighing a sale or public listing for Golden Goose, a footwear brand favored by Taylor Swift, at a $2.7 billion valuation. (Bloomberg)                                                                                                                                                                                                                                                                                                                            , Policy                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Louisiana passed a bill that would block online services — including Instagram, TikTok and Fortnite — for children under 18 without their parents’ permission. (NYT)                                                                                                                                                                                                                                                                                                                    , The Supreme Court unanimously ruled against a dog-toy maker whose product closely resembles a bottle of Jack Daniels whiskey. (NYT)                                                                                                                                                                                                                                                                                                                                                     , Best of the rest                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Sam Altman of OpenAI, Bob Iger of Disney, Jay Monahan of the PGA Tour, Rupert Murdoch of Fox and Sundar Pichai of Alphabet are all on the guest list for this year’s Allen &amp; Company gathering in Sun Valley, Idaho. (Variety)                                                                                                                                                                                                                                                          , How Taylor Swift is a godsend for Chicago’s hotel industry. (Bloomberg)                                                                                                                                                                                                                                                                                                                                                                                                                 , “What All the Single Ladies (and Men) Say About the Economy” (NYT)                                                                                                                                                                                                                                                                                                                                                                                                                      , We’d like your feedback! Please email thoughts and suggestions to dealbook@nytimes.com.                                                                                                                                                                                                                                                                                                                                                                                                 , Andrew Ross Sorkin is a columnist and the founder and editor at large of DealBook. He is a co-anchor of CNBC’s "Squawk Box" and the author of “Too Big to Fail.” He is also a co-creator of the Showtime drama series "Billions."  @andrewrsorkin • Facebook                                                                                                                                                                                                                            , Ravi Mattu is the managing editor of DealBook, based in London. He joined The New York Times in 2022 from the Financial Times, where he held a number of senior roles in Hong Kong and London.  @ravmattu                                                                                                                                                                                                                                                                               , Bernhard Warner joined the The Times in 2022 as a senior editor for DealBook. Previously he was a senior writer and editor at Fortune focusing on business, the economy and the markets.  @bernhardwarner                                                                                                                                                                                                                                                                               , Sarah Kessler is a senior staff editor for DealBook and the author of “Gigged,” a book about workers in the gig economy.  @sarahfkessler                                                                                                                                                                                                                                                                                                                                                , Michael de la Merced joined The Times as a reporter in 2006, covering Wall Street and finance. Among his main coverage areas are mergers and acquisitions, bankruptcies and the private equity industry.  @m_delamerced • Facebook                                                                                                                                                                                                                                                      , Lauren Hirsch joined The Times from CNBC in 2020, covering deals and the biggest stories on Wall Street.  @laurenshirsch                                                                                                                                                                                                                                                                                                                                                                , Ephrat Livni reports from Washington on the intersection of business and policy for DealBook. Previously, she was a senior reporter at Quartz, covering law and politics, and has practiced law in the public and private sectors.    @el72champs                                                                                                                                                                                                                                       , Advertisement </td>
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
   <td style="text-align:left;"> Bloomberg Surveillance with Tom Keene, Jonathan Ferro &amp; Lisa Abramowicz live from New York, bringing insight on global markets and the top business stories of the day.                                                         , The economy and markets are "under surveillance". Bloomberg Surveillance, covering the latest news in finance, economics and investments.                                                                                       , If a green pivot is to happen, power grids must become “supergrids,” continent-spanning networks that can move green energy thousands of miles. The technology is here, but politics may stand in the way.                      , Citi to Cut 50 London Jobs in Investment and Corporate Banking                                                                                                                                                                  , The More Inflation the Better: This Little-Discussed Insurance Broker Is Having a Moment                                                                                                                                        , Canada Sheds 17,300 Jobs in First Decline in Nine Months                                                                                                                                                                        , Fed Seen Ending Its 15-Month Hiking Campaign in Economist Survey                                                                                                                                                                , China Central Bank Governor Reiterates Stable Policy Stance                                                                                                                                                                     , Transcript: How Wildfire Smoke and Air Pollution Affect Your Health                                                                                                                                                             , Rowdy Tourists Spark Partial Airbnb Ban on Malaysian Island                                                                                                                                                                     , A Cheat Sheet to AI Buzzwords and Their Meanings                                                                                                                                                                                , UAE Fintech Optasia Hires Moelis for Potential Sale, IPO                                                                                                                                                                        , TikTok-Owner Tests ChatGPT-Style Bot After Joining China AI Race                                                                                                                                                                , Spanish Left Unites to Face Conservatives in Snap Election                                                                                                                                                                      , Labour Caves on £140 Billion Green Energy Plan Over Cost Fear                                                                                                                                                                   , Tiger Global Among Hedge Funds Riding AI Mania to May Gains                                                                                                                                                                     , Bank of America Reworks Leadership in Investment Bank Unit                                                                                                                                                                      , Craft Beer’s Hottest Trend Is a Style That’s as Mass as Can Be                                                                                                                                                                  , The Best Luxury Father’s Day Gifts for Dads Who Love Design                                                                                                                                                                     , This Week’s Wildfire Smoke Disaster Won’t Be the Last                                                                                                                                                                           , What’s the Best Use for Crypto? Let AI Figure It Out                                                                                                                                                                            , Musk Promised Transparency, Then Hid Twitter Data                                                                                                                                                                               , The Netflix Effect Chills Foreign Content Creators                                                                                                                                                                              , Payrolls, Prices, Productivity and Profits Hold the Answer to the Puzzling US Economy                                                                                                                                           , Will Argentina Ditch the Peso for the Dollar?                                                                                                                                                                                   , Support for ESG Shareholder Proposals Plummets Amid GOP Backlash                                                                                                                                                                , Deutsche Bank Gender Gap Shows Europe Is Failing Diversity Test                                                                                                                                                                 , What America Learned From the Demise of its EV Battery Pioneer                                                                                                                                                                  , Transcript: How Wildfire Smoke and Air Pollution Affect Your Health                                                                                                                                                             , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                  , Connecticut May Ban Collection Tactic Used in Cash-Advance Loans                                                                                                                                                                , Deep Drought Punishes Latin American Clean Water Pioneer                                                                                                                                                                        , Binance.US Set to Be Cut Off From Banking System After SEC Lawsuit                                                                                                                                                              , FTX’s US Judge Vows to Keep Control of Crypto in Blow to Bahamas                                                                                                                                                                , SEC Seeks ‘Alternative Means’ to Serve Papers to Binance’s Zhao                                                                                                                                                                 , Romanian teachers protest in front of the Romanian Government headquarters in Bucharest, on May 25                                                                                                                              , Photographer: Daniel Michaelscu/AFP/Getty Images                                                                                                                                                                                , Andra Timu and                                                                                                                                                                                                                  , Irina Vilcu                                                                                                                                                                                                                     , Subscriber Benefit                                                                                                                                                                                                              , Subscribe                                                                                                                                                                                                                       , Thousands of teachers took to the streets of Romania’s capital as the biggest education strike in almost two decades approached its third week and the government struggled to reach a deal with union negotiators.             , Some 10,000 people joined the demonstration in central Bucharest Friday to demand a pay hike and better working conditions, according to local media. It was the third such gathering since the teachers’ strike began May 22.   </td>
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
   <td style="text-align:left;"> Bloomberg Surveillance with Tom Keene, Jonathan Ferro &amp; Lisa Abramowicz live from New York, bringing insight on global markets and the top business stories of the day.                                                               , The economy and markets are "under surveillance". Bloomberg Surveillance, covering the latest news in finance, economics and investments.                                                                                             , If a green pivot is to happen, power grids must become “supergrids,” continent-spanning networks that can move green energy thousands of miles. The technology is here, but politics may stand in the way.                            , Citi to Cut 50 London Jobs in Investment and Corporate Banking                                                                                                                                                                        , The More Inflation the Better: This Little-Discussed Insurance Broker Is Having a Moment                                                                                                                                              , Canada Sheds 17,300 Jobs in First Decline in Nine Months                                                                                                                                                                              , Fed Seen Ending Its 15-Month Hiking Campaign in Economist Survey                                                                                                                                                                      , China Central Bank Governor Reiterates Stable Policy Stance                                                                                                                                                                           , Transcript: How Wildfire Smoke and Air Pollution Affect Your Health                                                                                                                                                                   , Rowdy Tourists Spark Partial Airbnb Ban on Malaysian Island                                                                                                                                                                           , A Cheat Sheet to AI Buzzwords and Their Meanings                                                                                                                                                                                      , UAE Fintech Optasia Hires Moelis for Potential Sale, IPO                                                                                                                                                                              , TikTok-Owner Tests ChatGPT-Style Bot After Joining China AI Race                                                                                                                                                                      , Spanish Left Unites to Face Conservatives in Snap Election                                                                                                                                                                            , Labour Caves on £140 Billion Green Energy Plan Over Cost Fear                                                                                                                                                                         , Tiger Global Among Hedge Funds Riding AI Mania to May Gains                                                                                                                                                                           , Bank of America Reworks Leadership in Investment Bank Unit                                                                                                                                                                            , Craft Beer’s Hottest Trend Is a Style That’s as Mass as Can Be                                                                                                                                                                        , The Best Luxury Father’s Day Gifts for Dads Who Love Design                                                                                                                                                                           , This Week’s Wildfire Smoke Disaster Won’t Be the Last                                                                                                                                                                                 , What’s the Best Use for Crypto? Let AI Figure It Out                                                                                                                                                                                  , Musk Promised Transparency, Then Hid Twitter Data                                                                                                                                                                                     , The Netflix Effect Chills Foreign Content Creators                                                                                                                                                                                    , Payrolls, Prices, Productivity and Profits Hold the Answer to the Puzzling US Economy                                                                                                                                                 , Will Argentina Ditch the Peso for the Dollar?                                                                                                                                                                                         , Support for ESG Shareholder Proposals Plummets Amid GOP Backlash                                                                                                                                                                      , Deutsche Bank Gender Gap Shows Europe Is Failing Diversity Test                                                                                                                                                                       , What America Learned From the Demise of its EV Battery Pioneer                                                                                                                                                                        , Transcript: How Wildfire Smoke and Air Pollution Affect Your Health                                                                                                                                                                   , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                        , Connecticut May Ban Collection Tactic Used in Cash-Advance Loans                                                                                                                                                                      , Deep Drought Punishes Latin American Clean Water Pioneer                                                                                                                                                                              , Binance.US Set to Be Cut Off From Banking System After SEC Lawsuit                                                                                                                                                                    , FTX’s US Judge Vows to Keep Control of Crypto in Blow to Bahamas                                                                                                                                                                      , SEC Seeks ‘Alternative Means’ to Serve Papers to Binance’s Zhao                                                                                                                                                                       , Shaik Abdul Rasheed Abdul Ghaffour                                                                                                                                                                                                    , Anisah Shukry                                                                                                                                                                                                                         , Subscriber Benefit                                                                                                                                                                                                                    , Subscribe                                                                                                                                                                                                                             , Malaysia named Shaik Abdul Rasheed Abdul Ghaffour as its new central bank governor, tasked with fostering stability and confidence in an economy under pressure from slowing global demand, volatile inflation and a weakened ringgit., Malaysia’s king approved Abdul Rasheed as the governor from July 1 for a period of five years, Bank Negara Malaysia said Friday. He will replace Nor Shamsiah Mohd Yunus, whose term ends June 30, according to the statement. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2023-06-09/zimbabwe-share-prices-daily-limit-raised-after-760-jump </td>
   <td style="text-align:left;"> 2023-06-09 18:27:11 </td>
   <td style="text-align:left;"> Zimbabwe Lifts Daily Share-Move Limit to Cope With Price Surges </td>
   <td style="text-align:left;"> Bloomberg Surveillance with Tom Keene, Jonathan Ferro &amp; Lisa Abramowicz live from New York, bringing insight on global markets and the top business stories of the day.                                                                                                                                                                               , The economy and markets are "under surveillance". Bloomberg Surveillance, covering the latest news in finance, economics and investments.                                                                                                                                                                                                             , If a green pivot is to happen, power grids must become “supergrids,” continent-spanning networks that can move green energy thousands of miles. The technology is here, but politics may stand in the way.                                                                                                                                            , Citi to Cut 50 London Jobs in Investment and Corporate Banking                                                                                                                                                                                                                                                                                        , The More Inflation the Better: This Little-Discussed Insurance Broker Is Having a Moment                                                                                                                                                                                                                                                              , Canada Sheds 17,300 Jobs in First Decline in Nine Months                                                                                                                                                                                                                                                                                              , Fed Seen Ending Its 15-Month Hiking Campaign in Economist Survey                                                                                                                                                                                                                                                                                      , China Central Bank Governor Reiterates Stable Policy Stance                                                                                                                                                                                                                                                                                           , Transcript: How Wildfire Smoke and Air Pollution Affect Your Health                                                                                                                                                                                                                                                                                   , Rowdy Tourists Spark Partial Airbnb Ban on Malaysian Island                                                                                                                                                                                                                                                                                           , A Cheat Sheet to AI Buzzwords and Their Meanings                                                                                                                                                                                                                                                                                                      , UAE Fintech Optasia Hires Moelis for Potential Sale, IPO                                                                                                                                                                                                                                                                                              , TikTok-Owner Tests ChatGPT-Style Bot After Joining China AI Race                                                                                                                                                                                                                                                                                      , Spanish Left Unites to Face Conservatives in Snap Election                                                                                                                                                                                                                                                                                            , Labour Caves on £140 Billion Green Energy Plan Over Cost Fear                                                                                                                                                                                                                                                                                         , Tiger Global Among Hedge Funds Riding AI Mania to May Gains                                                                                                                                                                                                                                                                                           , Bank of America Reworks Leadership in Investment Bank Unit                                                                                                                                                                                                                                                                                            , Craft Beer’s Hottest Trend Is a Style That’s as Mass as Can Be                                                                                                                                                                                                                                                                                        , The Best Luxury Father’s Day Gifts for Dads Who Love Design                                                                                                                                                                                                                                                                                           , This Week’s Wildfire Smoke Disaster Won’t Be the Last                                                                                                                                                                                                                                                                                                 , What’s the Best Use for Crypto? Let AI Figure It Out                                                                                                                                                                                                                                                                                                  , Musk Promised Transparency, Then Hid Twitter Data                                                                                                                                                                                                                                                                                                     , The Netflix Effect Chills Foreign Content Creators                                                                                                                                                                                                                                                                                                    , Payrolls, Prices, Productivity and Profits Hold the Answer to the Puzzling US Economy                                                                                                                                                                                                                                                                 , Will Argentina Ditch the Peso for the Dollar?                                                                                                                                                                                                                                                                                                         , Support for ESG Shareholder Proposals Plummets Amid GOP Backlash                                                                                                                                                                                                                                                                                      , Deutsche Bank Gender Gap Shows Europe Is Failing Diversity Test                                                                                                                                                                                                                                                                                       , What America Learned From the Demise of its EV Battery Pioneer                                                                                                                                                                                                                                                                                        , Transcript: How Wildfire Smoke and Air Pollution Affect Your Health                                                                                                                                                                                                                                                                                   , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                                                                                                                                        , Connecticut May Ban Collection Tactic Used in Cash-Advance Loans                                                                                                                                                                                                                                                                                      , Deep Drought Punishes Latin American Clean Water Pioneer                                                                                                                                                                                                                                                                                              , Binance.US Set to Be Cut Off From Banking System After SEC Lawsuit                                                                                                                                                                                                                                                                                    , FTX’s US Judge Vows to Keep Control of Crypto in Blow to Bahamas                                                                                                                                                                                                                                                                                      , SEC Seeks ‘Alternative Means’ to Serve Papers to Binance’s Zhao                                                                                                                                                                                                                                                                                       , Ray Ndlovu                                                                                                                                                                                                                                                                                                                                            , Subscriber Benefit                                                                                                                                                                                                                                                                                                                                    , Subscribe                                                                                                                                                                                                                                                                                                                                             , Share prices are rising so rapidly on Zimbabwe’s main stock exchange that the bourse is increasing the maximum move allowed in a single day.                                                                                                                                                                                                          , A new daily limit of a 15% move in the all-share index — up from 10% — will be implemented from Monday, Justin Bgoni, chief executive officer of the Zimbabwe Stock Exchange in Harare, said by phone Friday. Circuit breakers halted trading on the bourse on three consecutive days this week. “It’s in response to the recent activity,” he said.   </td>
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
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2023-06-09/japan-watchdog-seeks-penalty-on-regional-banks-over-bond-sales </td>
   <td style="text-align:left;"> 2023-06-09 18:00:21 </td>
   <td style="text-align:left;"> Japan Watchdog Seeks Penalty On Regional Banks Over Bond Sales </td>
   <td style="text-align:left;"> Bloomberg Surveillance with Tom Keene, Jonathan Ferro &amp; Lisa Abramowicz live from New York, bringing insight on global markets and the top business stories of the day.                                                                                                                                                                        , The economy and markets are "under surveillance". Bloomberg Surveillance, covering the latest news in finance, economics and investments.                                                                                                                                                                                                      , If a green pivot is to happen, power grids must become “supergrids,” continent-spanning networks that can move green energy thousands of miles. The technology is here, but politics may stand in the way.                                                                                                                                     , Citi to Cut 50 London Jobs in Investment and Corporate Banking                                                                                                                                                                                                                                                                                 , The More Inflation the Better: This Little-Discussed Insurance Broker Is Having a Moment                                                                                                                                                                                                                                                       , Canada Sheds 17,300 Jobs in First Decline in Nine Months                                                                                                                                                                                                                                                                                       , Fed Seen Ending Its 15-Month Hiking Campaign in Economist Survey                                                                                                                                                                                                                                                                               , China Central Bank Governor Reiterates Stable Policy Stance                                                                                                                                                                                                                                                                                    , Transcript: How Wildfire Smoke and Air Pollution Affect Your Health                                                                                                                                                                                                                                                                            , Rowdy Tourists Spark Partial Airbnb Ban on Malaysian Island                                                                                                                                                                                                                                                                                    , A Cheat Sheet to AI Buzzwords and Their Meanings                                                                                                                                                                                                                                                                                               , UAE Fintech Optasia Hires Moelis for Potential Sale, IPO                                                                                                                                                                                                                                                                                       , TikTok-Owner Tests ChatGPT-Style Bot After Joining China AI Race                                                                                                                                                                                                                                                                               , Spanish Left Unites to Face Conservatives in Snap Election                                                                                                                                                                                                                                                                                     , Labour Caves on £140 Billion Green Energy Plan Over Cost Fear                                                                                                                                                                                                                                                                                  , Tiger Global Among Hedge Funds Riding AI Mania to May Gains                                                                                                                                                                                                                                                                                    , Bank of America Reworks Leadership in Investment Bank Unit                                                                                                                                                                                                                                                                                     , Craft Beer’s Hottest Trend Is a Style That’s as Mass as Can Be                                                                                                                                                                                                                                                                                 , The Best Luxury Father’s Day Gifts for Dads Who Love Design                                                                                                                                                                                                                                                                                    , This Week’s Wildfire Smoke Disaster Won’t Be the Last                                                                                                                                                                                                                                                                                          , What’s the Best Use for Crypto? Let AI Figure It Out                                                                                                                                                                                                                                                                                           , Musk Promised Transparency, Then Hid Twitter Data                                                                                                                                                                                                                                                                                              , The Netflix Effect Chills Foreign Content Creators                                                                                                                                                                                                                                                                                             , Payrolls, Prices, Productivity and Profits Hold the Answer to the Puzzling US Economy                                                                                                                                                                                                                                                          , Will Argentina Ditch the Peso for the Dollar?                                                                                                                                                                                                                                                                                                  , Support for ESG Shareholder Proposals Plummets Amid GOP Backlash                                                                                                                                                                                                                                                                               , Deutsche Bank Gender Gap Shows Europe Is Failing Diversity Test                                                                                                                                                                                                                                                                                , What America Learned From the Demise of its EV Battery Pioneer                                                                                                                                                                                                                                                                                 , Transcript: How Wildfire Smoke and Air Pollution Affect Your Health                                                                                                                                                                                                                                                                            , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                                                                                                                                 , Connecticut May Ban Collection Tactic Used in Cash-Advance Loans                                                                                                                                                                                                                                                                               , Deep Drought Punishes Latin American Clean Water Pioneer                                                                                                                                                                                                                                                                                       , Binance.US Set to Be Cut Off From Banking System After SEC Lawsuit                                                                                                                                                                                                                                                                             , FTX’s US Judge Vows to Keep Control of Crypto in Blow to Bahamas                                                                                                                                                                                                                                                                               , SEC Seeks ‘Alternative Means’ to Serve Papers to Binance’s Zhao                                                                                                                                                                                                                                                                                , Fumio Kishida                                                                                                                                                                                                                                                                                                                                  , Photographer: Kimimasa Mayama/EPA/Bloomberg                                                                                                                                                                                                                                                                                                    , Takashi Nakamichi                                                                                                                                                                                                                                                                                                                              , Subscriber Benefit                                                                                                                                                                                                                                                                                                                             , Subscribe                                                                                                                                                                                                                                                                                                                                      , Japan’s securities watchdog is seeking penalties on two regional banks for improperly selling structured bonds, a rare move that could send a signal to the broader industry about its sales practices.                                                                                                                                        , The Securities and Exchange Surveillance Commission on Friday asked the Financial Services Agency to punish Chiba Bank Ltd. and its brokerage subsidiary, as well as Musashino Bank Ltd. The agency said they sold these products without properly checking customers’ investment preference and experience, or explaining the risks involved.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2023-06-09/hsbc-among-uk-banks-pulling-mortgage-deals-from-the-market-again </td>
   <td style="text-align:left;"> 2023-06-09 17:57:04 </td>
   <td style="text-align:left;"> HSBC Among UK Banks Pulling Mortgage Deals From the Market Again </td>
   <td style="text-align:left;"> Bloomberg Surveillance with Tom Keene, Jonathan Ferro &amp; Lisa Abramowicz live from New York, bringing insight on global markets and the top business stories of the day.                                                                                                                                                                       , The economy and markets are "under surveillance". Bloomberg Surveillance, covering the latest news in finance, economics and investments.                                                                                                                                                                                                     , If a green pivot is to happen, power grids must become “supergrids,” continent-spanning networks that can move green energy thousands of miles. The technology is here, but politics may stand in the way.                                                                                                                                    , Citi to Cut 50 London Jobs in Investment and Corporate Banking                                                                                                                                                                                                                                                                                , The More Inflation the Better: This Little-Discussed Insurance Broker Is Having a Moment                                                                                                                                                                                                                                                      , Canada Sheds 17,300 Jobs in First Decline in Nine Months                                                                                                                                                                                                                                                                                      , Fed Seen Ending Its 15-Month Hiking Campaign in Economist Survey                                                                                                                                                                                                                                                                              , China Central Bank Governor Reiterates Stable Policy Stance                                                                                                                                                                                                                                                                                   , Transcript: How Wildfire Smoke and Air Pollution Affect Your Health                                                                                                                                                                                                                                                                           , Rowdy Tourists Spark Partial Airbnb Ban on Malaysian Island                                                                                                                                                                                                                                                                                   , A Cheat Sheet to AI Buzzwords and Their Meanings                                                                                                                                                                                                                                                                                              , UAE Fintech Optasia Hires Moelis for Potential Sale, IPO                                                                                                                                                                                                                                                                                      , TikTok-Owner Tests ChatGPT-Style Bot After Joining China AI Race                                                                                                                                                                                                                                                                              , Spanish Left Unites to Face Conservatives in Snap Election                                                                                                                                                                                                                                                                                    , Labour Caves on £140 Billion Green Energy Plan Over Cost Fear                                                                                                                                                                                                                                                                                 , Tiger Global Among Hedge Funds Riding AI Mania to May Gains                                                                                                                                                                                                                                                                                   , Bank of America Reworks Leadership in Investment Bank Unit                                                                                                                                                                                                                                                                                    , Craft Beer’s Hottest Trend Is a Style That’s as Mass as Can Be                                                                                                                                                                                                                                                                                , The Best Luxury Father’s Day Gifts for Dads Who Love Design                                                                                                                                                                                                                                                                                   , This Week’s Wildfire Smoke Disaster Won’t Be the Last                                                                                                                                                                                                                                                                                         , What’s the Best Use for Crypto? Let AI Figure It Out                                                                                                                                                                                                                                                                                          , Musk Promised Transparency, Then Hid Twitter Data                                                                                                                                                                                                                                                                                             , The Netflix Effect Chills Foreign Content Creators                                                                                                                                                                                                                                                                                            , Payrolls, Prices, Productivity and Profits Hold the Answer to the Puzzling US Economy                                                                                                                                                                                                                                                         , Will Argentina Ditch the Peso for the Dollar?                                                                                                                                                                                                                                                                                                 , Support for ESG Shareholder Proposals Plummets Amid GOP Backlash                                                                                                                                                                                                                                                                              , Deutsche Bank Gender Gap Shows Europe Is Failing Diversity Test                                                                                                                                                                                                                                                                               , What America Learned From the Demise of its EV Battery Pioneer                                                                                                                                                                                                                                                                                , Transcript: How Wildfire Smoke and Air Pollution Affect Your Health                                                                                                                                                                                                                                                                           , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                                                                                                                                , Connecticut May Ban Collection Tactic Used in Cash-Advance Loans                                                                                                                                                                                                                                                                              , Deep Drought Punishes Latin American Clean Water Pioneer                                                                                                                                                                                                                                                                                      , Binance.US Set to Be Cut Off From Banking System After SEC Lawsuit                                                                                                                                                                                                                                                                            , FTX’s US Judge Vows to Keep Control of Crypto in Blow to Bahamas                                                                                                                                                                                                                                                                              , SEC Seeks ‘Alternative Means’ to Serve Papers to Binance’s Zhao                                                                                                                                                                                                                                                                               , Estate agents boards outside a block of flats in the Slade Green district of Greater London.                                                                                                                                                                                                                                                  , Damian Shepherd and                                                                                                                                                                                                                                                                                                                           , William Shaw                                                                                                                                                                                                                                                                                                                                  , Subscriber Benefit                                                                                                                                                                                                                                                                                                                            , Subscribe                                                                                                                                                                                                                                                                                                                                     , UK lenders, led by HSBC Holdings Plc, are removing mortgage deals from the market again as they prepare to reprice home loans to account for inflation.                                                                                                                                                                                       , Giving only hours’ notice, HSBC said on Thursday that it would remove all its current new business residential and buy-to-let products via broker services the same evening. It said the offerings will be back Monday at increased rates. That triggered a surge in demand, prompting the lender to withdraw them before the scheduled time.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/greece/inflation-cpi </td>
   <td style="text-align:left;"> 2023-06-09 17:44:52 </td>
   <td style="text-align:left;"> Greece Inflation Continues Downward Trend </td>
   <td style="text-align:left;"> Greece annual consumer inflation eased for an eighth straight month to 2.8% in May 2023 from 3% in April, marking the lowest reading since September 2021. The cost rose softer for hotels, cafés &amp; restaurants (7.4% vs 8.5% in the previous period) and household equipment (9.9% vs 10.9%). It also declined for housing (-12.9% vs -13.4%), transport (-3.1% vs 1.4%), and communication (-2.3% vs -1.8%). On the other hand, inflation accelerated for food &amp; non-alcoholic beverages (11.6% vs 11.4%); health (7.8% vs 6.5%); miscellaneous goods &amp; services (6.8% vs 6.4%); and clothing &amp; footwear (11.8% vs 5.6%). On a monthly basis, consumer prices grew by 0.4%, slowing from a 0.6% gain in April. Additionally, harmonized inflation rate decelerated to a 1-1/2 year low of 4.1%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2023-06-09/amd-gets-chance-to-show-ai-roadmap-after-87-rally-tech-watch </td>
   <td style="text-align:left;"> 2023-06-09 17:39:32 </td>
   <td style="text-align:left;"> AMD Tracks Nvidia Gains in Wall Street’s AI Frenzy </td>
   <td style="text-align:left;"> Bloomberg Surveillance with Tom Keene, Jonathan Ferro &amp; Lisa Abramowicz live from New York, bringing insight on global markets and the top business stories of the day.                                                                                                                                                                                                                    , The economy and markets are "under surveillance". Bloomberg Surveillance, covering the latest news in finance, economics and investments.                                                                                                                                                                                                                                                  , If a green pivot is to happen, power grids must become “supergrids,” continent-spanning networks that can move green energy thousands of miles. The technology is here, but politics may stand in the way.                                                                                                                                                                                 , Citi to Cut 50 London Jobs in Investment and Corporate Banking                                                                                                                                                                                                                                                                                                                             , The More Inflation the Better: This Little-Discussed Insurance Broker Is Having a Moment                                                                                                                                                                                                                                                                                                   , Canada Sheds 17,300 Jobs in First Decline in Nine Months                                                                                                                                                                                                                                                                                                                                   , Fed Seen Ending Its 15-Month Hiking Campaign in Economist Survey                                                                                                                                                                                                                                                                                                                           , China Central Bank Governor Reiterates Stable Policy Stance                                                                                                                                                                                                                                                                                                                                , Transcript: How Wildfire Smoke and Air Pollution Affect Your Health                                                                                                                                                                                                                                                                                                                        , Rowdy Tourists Spark Partial Airbnb Ban on Malaysian Island                                                                                                                                                                                                                                                                                                                                , A Cheat Sheet to AI Buzzwords and Their Meanings                                                                                                                                                                                                                                                                                                                                           , UAE Fintech Optasia Hires Moelis for Potential Sale, IPO                                                                                                                                                                                                                                                                                                                                   , TikTok-Owner Tests ChatGPT-Style Bot After Joining China AI Race                                                                                                                                                                                                                                                                                                                           , Spanish Left Unites to Face Conservatives in Snap Election                                                                                                                                                                                                                                                                                                                                 , Labour Caves on £140 Billion Green Energy Plan Over Cost Fear                                                                                                                                                                                                                                                                                                                              , Tiger Global Among Hedge Funds Riding AI Mania to May Gains                                                                                                                                                                                                                                                                                                                                , Bank of America Reworks Leadership in Investment Bank Unit                                                                                                                                                                                                                                                                                                                                 , Craft Beer’s Hottest Trend Is a Style That’s as Mass as Can Be                                                                                                                                                                                                                                                                                                                             , The Best Luxury Father’s Day Gifts for Dads Who Love Design                                                                                                                                                                                                                                                                                                                                , This Week’s Wildfire Smoke Disaster Won’t Be the Last                                                                                                                                                                                                                                                                                                                                      , What’s the Best Use for Crypto? Let AI Figure It Out                                                                                                                                                                                                                                                                                                                                       , Musk Promised Transparency, Then Hid Twitter Data                                                                                                                                                                                                                                                                                                                                          , The Netflix Effect Chills Foreign Content Creators                                                                                                                                                                                                                                                                                                                                         , Payrolls, Prices, Productivity and Profits Hold the Answer to the Puzzling US Economy                                                                                                                                                                                                                                                                                                      , Will Argentina Ditch the Peso for the Dollar?                                                                                                                                                                                                                                                                                                                                              , Support for ESG Shareholder Proposals Plummets Amid GOP Backlash                                                                                                                                                                                                                                                                                                                           , Deutsche Bank Gender Gap Shows Europe Is Failing Diversity Test                                                                                                                                                                                                                                                                                                                            , What America Learned From the Demise of its EV Battery Pioneer                                                                                                                                                                                                                                                                                                                             , Transcript: How Wildfire Smoke and Air Pollution Affect Your Health                                                                                                                                                                                                                                                                                                                        , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                                                                                                                                                                             , Connecticut May Ban Collection Tactic Used in Cash-Advance Loans                                                                                                                                                                                                                                                                                                                           , Deep Drought Punishes Latin American Clean Water Pioneer                                                                                                                                                                                                                                                                                                                                   , Binance.US Set to Be Cut Off From Banking System After SEC Lawsuit                                                                                                                                                                                                                                                                                                                         , FTX’s US Judge Vows to Keep Control of Crypto in Blow to Bahamas                                                                                                                                                                                                                                                                                                                           , SEC Seeks ‘Alternative Means’ to Serve Papers to Binance’s Zhao                                                                                                                                                                                                                                                                                                                            , AMD will introduce new data center chips next week.                                                                                                                                                                                                                                                                                                                                        , Ian King and                                                                                                                                                                                                                                                                                                                                                                               , Subrat Patnaik                                                                                                                                                                                                                                                                                                                                                                             , Subscriber Benefit                                                                                                                                                                                                                                                                                                                                                                         , Subscribe                                                                                                                                                                                                                                                                                                                                                                                  , Advanced Micro Devices Inc.’s stellar share-price performance this year reflects its place in the eyes of investors looking to make an artificial intelligence trade: the best backup plan.                                                                                                                                                                                                , The stock’s 87% surge would make it the top performer on the Philadelphia Stock Exchange Semiconductor Index if it wasn’t for the stratospheric gain of rival Nvidia Corp. Nvidia briefly became the first chipmaker to have a trillion-dollar market value after delivering concrete evidence that the rush to develop new AI services is translating into a surge in orders for hardware. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2023-06-09/japan-sushi-chain-sues-teen-480-000-for-soy-sauce-licking-prank </td>
   <td style="text-align:left;"> 2023-06-09 17:37:18 </td>
   <td style="text-align:left;"> Japan Sushi Chain Sues Teen $480,000 For Soy-Sauce Licking Prank </td>
   <td style="text-align:left;"> Bloomberg Surveillance with Tom Keene, Jonathan Ferro &amp; Lisa Abramowicz live from New York, bringing insight on global markets and the top business stories of the day.                                                                                    , The economy and markets are "under surveillance". Bloomberg Surveillance, covering the latest news in finance, economics and investments.                                                                                                                  , If a green pivot is to happen, power grids must become “supergrids,” continent-spanning networks that can move green energy thousands of miles. The technology is here, but politics may stand in the way.                                                 , Citi to Cut 50 London Jobs in Investment and Corporate Banking                                                                                                                                                                                             , The More Inflation the Better: This Little-Discussed Insurance Broker Is Having a Moment                                                                                                                                                                   , Canada Sheds 17,300 Jobs in First Decline in Nine Months                                                                                                                                                                                                   , Fed Seen Ending Its 15-Month Hiking Campaign in Economist Survey                                                                                                                                                                                           , China Central Bank Governor Reiterates Stable Policy Stance                                                                                                                                                                                                , Transcript: How Wildfire Smoke and Air Pollution Affect Your Health                                                                                                                                                                                        , Rowdy Tourists Spark Partial Airbnb Ban on Malaysian Island                                                                                                                                                                                                , A Cheat Sheet to AI Buzzwords and Their Meanings                                                                                                                                                                                                           , UAE Fintech Optasia Hires Moelis for Potential Sale, IPO                                                                                                                                                                                                   , TikTok-Owner Tests ChatGPT-Style Bot After Joining China AI Race                                                                                                                                                                                           , Spanish Left Unites to Face Conservatives in Snap Election                                                                                                                                                                                                 , Labour Caves on £140 Billion Green Energy Plan Over Cost Fear                                                                                                                                                                                              , Tiger Global Among Hedge Funds Riding AI Mania to May Gains                                                                                                                                                                                                , Bank of America Reworks Leadership in Investment Bank Unit                                                                                                                                                                                                 , Craft Beer’s Hottest Trend Is a Style That’s as Mass as Can Be                                                                                                                                                                                             , The Best Luxury Father’s Day Gifts for Dads Who Love Design                                                                                                                                                                                                , This Week’s Wildfire Smoke Disaster Won’t Be the Last                                                                                                                                                                                                      , What’s the Best Use for Crypto? Let AI Figure It Out                                                                                                                                                                                                       , Musk Promised Transparency, Then Hid Twitter Data                                                                                                                                                                                                          , The Netflix Effect Chills Foreign Content Creators                                                                                                                                                                                                         , Payrolls, Prices, Productivity and Profits Hold the Answer to the Puzzling US Economy                                                                                                                                                                      , Will Argentina Ditch the Peso for the Dollar?                                                                                                                                                                                                              , Support for ESG Shareholder Proposals Plummets Amid GOP Backlash                                                                                                                                                                                           , Deutsche Bank Gender Gap Shows Europe Is Failing Diversity Test                                                                                                                                                                                            , What America Learned From the Demise of its EV Battery Pioneer                                                                                                                                                                                             , Transcript: How Wildfire Smoke and Air Pollution Affect Your Health                                                                                                                                                                                        , NYC Pays Over $300 a Night for Budget Hotel Rooms for Migrants                                                                                                                                                                                             , Connecticut May Ban Collection Tactic Used in Cash-Advance Loans                                                                                                                                                                                           , Deep Drought Punishes Latin American Clean Water Pioneer                                                                                                                                                                                                   , Binance.US Set to Be Cut Off From Banking System After SEC Lawsuit                                                                                                                                                                                         , FTX’s US Judge Vows to Keep Control of Crypto in Blow to Bahamas                                                                                                                                                                                           , SEC Seeks ‘Alternative Means’ to Serve Papers to Binance’s Zhao                                                                                                                                                                                            , Grace Huang                                                                                                                                                                                                                                                , Subscriber Benefit                                                                                                                                                                                                                                         , Subscribe                                                                                                                                                                                                                                                  , A sushi restaurant chain is suing a customer for ¥67 million ($480,000), saying that a viral online video of the teen licking communal bottles and plates caused a drop in sales, foot traffic and the company’s shares, according to Japanese media.      , Food &amp; Life Cos., which owns Akindo Sushiro, the outlet where the incident occurred, had filed a police report and received an apology from the perpetrator. In the clip, he also touched the sushi as it rolled past with fingers he had put in his mouth. </td>
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
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/currency </td>
   <td style="text-align:left;"> 2023-06-09 10:58:49 </td>
   <td style="text-align:left;"> Dollar Set for Second Weekly Fall </td>
   <td style="text-align:left;"> The dollar index held below 103.5 on Friday after losing 0.8% in the previous session, tracking weakness in Treasury yields as a surge in weekly jobless claims reinforced expectations that the Federal Reserve will pause its interest rate hikes next week. The greenback was also down 0.6% so far this week, on track to decline for the second consecutive week. The number of Americans filing new claims for unemployment benefits jumped to 261K last week, posting the highest reading since October 2021 and exceeding forecasts of 235K. Markets now anticipate the Fed to hold rates steady at next week’s policy meeting, before resuming the tightening cycle in July. Investor also look ahead to US inflation data on Tuesday, as well as interest rate decisions from the European Central Bank and the Bank of Japan next week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/hong-kong/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 10:55:00 </td>
   <td style="text-align:left;"> Hong Kong Stocks Down But Point to Gains Weekly </td>
   <td style="text-align:left;"> The Hang Seng fell 64 points or 0.33% to 19,235 in early deals on Friday after gaining in the prior two sessions, dragged by losses from tech shares, property, and financials. Market participants were cautious as deflation risk in China grew following weaker-than-expected inflation data for May.  Official figures showed that the country's annual inflation rate edged up to 0.2% from April's 26-month low of 0.1%, below market consensus of 0.3%, while producer prices fell by 4.6%, the most since 2016. Locally, recent readings pointed that Hong Kong's forex reserves dropped to a 7-month low in May, while factory activity grew the least in five months amid slowing orders and rising cost burdens. JD Health Intl. shed by 3.3%, followed by Alibaba Health Intl. (-2.5%), Haier Smart Home (-1.7%), Xiaomi Corp. (-1.5%), and AIA Group (-1.2%). Still, the index for the week is set to book a 1.5% rise, encouraged by optimism that Beijing will deliver more stimulus to spur economic recovery in China. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/stock-market </td>
   <td style="text-align:left;"> 2023-06-09 10:35:00 </td>
   <td style="text-align:left;"> China Stocks Rise After Inflation Data </td>
   <td style="text-align:left;"> The Shanghai Composite rose 0.55% to close at 3,231 while the Shenzhen Component gained 0.66% to 10,794 on Friday, extending gains from the previous session as investors reacted to softer-than-expected Chinese inflation data. China’s consumer price index rose 0.2% year-on-year in May, lower than the 0.3% forecast, while producer deflation continued last month. Weakening economic data in China fueled speculations that authorities could introduce more fiscal and monetary stimulus this year, including a possible cut to banks' reserve requirement ratio. High-growth technology stocks led the advance, with strong gains from iFLYTEK (3.3%), Zhongji Innolight (8%), Inspur Electronic (6.1%), Dawning Information (4.5%) and Foxconn Industrial (10%). The Shanghai index inched up 0.04% this week, while the Shenzhen index dropped 1.86%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2023-06-09 10:00:00 </td>
   <td style="text-align:left;"> Oil Heads for Second Weekly Decline </td>
   <td style="text-align:left;"> WTI crude futures traded around $71 per barrel on Friday and were on track to decline for the second straight week, as investors remained concerned about demand. The prospect of further interest rate hikes from major central banks and economic uncertainties in top crude importer China could negatively impact overall demand. The US oil benchmark tumbled as much as 4.8% on Thursday following news that the US and Iran reached a temporary nuclear agreement that would allow Iran to resume oil exports of around 1 million barrels per day. However, both countries denied the report, causing oil prices to recoup most of Thursday's losses. Meanwhile, Saudi Arabia announced over the weekend its intention to reduce output by 1 million barrels per day to 9 million bpd in July, the lowest level in years amid an effort to support crude prices. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/food-inflation </td>
   <td style="text-align:left;"> 2023-06-09 09:51:00 </td>
   <td style="text-align:left;"> China Food Prices Accelerate </td>
   <td style="text-align:left;"> Food prices in China increased by 1.0% year-on-year in May 2023, accelerating sharply from a 0.4% rise a month earlier which was the softest pace since March 2022. This was the 14th straight month of food inflation,  with upward price pressures coming from cooking oils (3.6% vs 4.8%in April), fresh fruit (3.4% vs 5.3%). and milk (0.6% vs 1.1%). At the same time, cost of fresh vegetables declined much softer (-1.7% vs -13.5%). Prices of pork fell by 3.2% after rising 4.0% previously, amid continued efforts from authorities to closely monitor supply and demand in the hog market. Meantime, cost of eggs declined by 1.5% after rising 1.2% in April. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/inflation-cpi </td>
   <td style="text-align:left;"> 2023-06-09 09:35:00 </td>
   <td style="text-align:left;"> China Inflation Rate Below Forecasts </td>
   <td style="text-align:left;"> China's annual inflation rate edged up to 0.2% in May 2023 from April's 26-month low of 0.1% but below market estimates of 0.3%. Food inflation picked up from a 13-month low in the prior month (1.0% vs 0.4%) on the back of further rises in prices of both fruit and cooking oil and a softer fall in cost of fresh vegetables. Meanwhile, non-food inflation was flat (at 0.1%), as further falls in prices of both transport (-3.9% vs -3.3%) and housing (-0.2% vs -0.3%) offset rises in cost of health (1.1% vs 1.0%) and education (1.7% vs 1.9%). Core consumer prices, excluding the volatile prices of food and energy, went up 0.6% yoy, after a 0.7% gain in April.  On a monthly basis, consumer prices dropped by 0.2%, the fourth straight month of fall, compared with estimates of a 0.1% decline. </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2023-06-09 21:01:40 UTC +8

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
   <td style="text-align:left;"> 2023-06-09 21:01:16 </td>
   <td style="text-align:left;"> $SPY . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:01:04 </td>
   <td style="text-align:left;"> $SPY futes ripping $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:00:58 </td>
   <td style="text-align:left;"> $DJIA $QQQ $SPY $TSLA who&amp;#39;s ready for another day of crooked Wall Street trading? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:00:44 </td>
   <td style="text-align:left;"> $SPY same play every Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:00:43 </td>
   <td style="text-align:left;"> $SPY shit is so god damn rigged ffs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:00:21 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA has joined the fun… now every Nasdaq stock has a parabolic chart. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 21:00:20 </td>
   <td style="text-align:left;"> $SPY $QQQ The communist traitor is indicted, time to rally! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:59:50 </td>
   <td style="text-align:left;"> $QQQ $SPY Bears your time is approaching shortly. Since last week Calls are about 2/3 over Puts day traders it may be time to just sit out at these levels until we see a confirmation esp in AI/Tech/Growth give it a few days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:59:49 </td>
   <td style="text-align:left;"> $SPY joke market

Tesla soaring. Doge soaring. Carvana soaring </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:59:45 </td>
   <td style="text-align:left;"> latexf1a6ced35f45f9fb6bc1fa1e7277a115TSLA - 6/16 on watch for a roll up
$NVDA - 6/16 400c over 395 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:59:25 </td>
   <td style="text-align:left;"> $SPY it’s that time of month for my account to bleed a little red - catch me at the expiry ;)

Play smart my Gs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:59:09 </td>
   <td style="text-align:left;"> @KnightKing they just cornered the charging market.  That’s like someone cornering the gas station market 50  years ago.  Insane! $tsla $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:59:02 </td>
   <td style="text-align:left;"> $SPY looks like it wants to blast off. I think there’s probably too much buying pressure to keep it down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:58:42 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $VOO $VTI Bye-bye bear... New S&amp;amp;P 500 bull market has legs - BofA

https://www.investing.com/news/stock-market-news/byebye-bear-new-sp-500-bull-market-has-legs--bofa-432SI-3102066 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:58:35 </td>
   <td style="text-align:left;"> $SPY definitely Red day. Cool off then march forward 😉🍷 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:58:33 </td>
   <td style="text-align:left;"> $SPY we all know this is moving above JPM ‘s collar at 430. These guys want their bonuses ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:58:31 </td>
   <td style="text-align:left;"> $SPY Wild game last night. 🪓Braves with the sweep! 🧹 
 
Markets to new highs... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:57:40 </td>
   <td style="text-align:left;"> $SPY $QQQ 
CNBC has former Fed equating getting vaccines to raising rates </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:57:33 </td>
   <td style="text-align:left;"> $SPY this is way to easy for bulls.. yet another bull Friday🤬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:57:32 </td>
   <td style="text-align:left;"> $SNDL &amp;lt;3 SNDL &amp;gt; A BULLS DREAM ENTRY POINT RSI AT 50 4 HR &amp;amp; DAILY. &amp;gt; SPY 4 HOUR RSI. &amp;lt;3 
 
Today, a Possible Major Break Out to the upside and another break out Monday &amp;amp; Tuesday Next Week! 
 
If you HAVEN&amp;#39;T listened to yesterday&amp;#39;s Cannabis Conference with Zach George, I highly recommend you do ASAP!! 
 
Big Things are happening. Just Saying! 
 
Squeezy! Squeezy!! &amp;lt;3 GL 
 
$SPY $NASDAQ $DJIA All Markets Trending Bullish! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:57:14 </td>
   <td style="text-align:left;"> $SPY HOW MANY TIMES WE GOING TO REJECT THIS AREA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:57:13 </td>
   <td style="text-align:left;"> $SPY $430 coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:57:11 </td>
   <td style="text-align:left;"> $SPY Bear market over? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:57:07 </td>
   <td style="text-align:left;"> HAMMMMMEEER GOLD 💰❗❗❗
CANADA LOSES 17.3K JOBS IN MAY; UNEMPLOYMENT RISES TO 5.2% FROM 5.0%
$QQQ $SPY $DJIA $ARKK $NASDAQ  jdjs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:56:42 </td>
   <td style="text-align:left;"> $SPY does this idiot know that MLinv is a bogus trader selling trading shit like wychoff??? In fact that moron is spreading negative shit about SPY every day. 
 
HINT: those who are patting you on the back while they sell you fear are not your friends. 
 
The BRUTAL TRUTH is fun </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:56:38 </td>
   <td style="text-align:left;"> $SPY $ES_F you can&amp;#39;t make that up, well you can. Short 4300 quick scalp. Long 4296 again looking for 4301. Ding ding ding. Another 5 PT locked. And we are done with this area until we see 4310 and retrace to 4300 for potential long entry. Or over 4305, reject to 4290, climb back 4300 one last time and short entry there. Thoughts to think, always always ALWAYS, money to be made. No need to stress. A Rational Thought~ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:56:36 </td>
   <td style="text-align:left;"> $SPY $QQQ im I the only one thinking this is a fake out? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:56:23 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA 

Too many calls - OI at the close yesterday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:56:21 </td>
   <td style="text-align:left;"> $SPY real hero are bulletproof/laserproof and it just a movie </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:56:09 </td>
   <td style="text-align:left;"> $SPY wall of fury! Denied! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:56:01 </td>
   <td style="text-align:left;"> $RGTI 300k pre market volume. Looking good to breakout over 1.50.
AI needs Quantum computing!!

 $TSLA $NVDA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:55:40 </td>
   <td style="text-align:left;"> $SPY $QQQ $ADBE Will be at least a 500% winner. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:55:24 </td>
   <td style="text-align:left;"> $MSFT $QQQ $SPY Time to go up! 🚀🚀🚀🚀 

Microsoft : BMO raises target price to $385 from $347 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:54:17 </td>
   <td style="text-align:left;"> @PELK @Bears_Stuckinthewasher VIX collapse is simply due to 0DTE taking over. 
 
option hedging $ moved from 30 DTE and greater days out too 0 DTE. This means there is far less $$$ hedging/fear 30 days out and 100x more $$ fear hedging in 0 DTE. 
 
VIX has to collapse because its not measuring the fear in SPX any more. 
 
$SPY $SPX $UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:54:15 </td>
   <td style="text-align:left;"> $SPY Breaking news: Trump on audio talks about not declassifying information - https://abcnews.go.com/Politics/live-updates/trump-indictment/?id=99913217 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:54:01 </td>
   <td style="text-align:left;"> $SIEN chk this fda clearance 
$QQQ $SPY $UDOW $KOLD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:53:59 </td>
   <td style="text-align:left;"> $SPY yall really wanna pretend covid was our all time low and nothing previously mattered....morons </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:53:56 </td>
   <td style="text-align:left;"> $QQQ $SPY $VIX at $13.6 😳😳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:53:47 </td>
   <td style="text-align:left;"> $SPY some resistance around 430.55 ...we shall see from there </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:53:43 </td>
   <td style="text-align:left;"> $SPY Nobody wants to short when central banks are injecting liquidity. You&amp;#39;d be crazy to do so unless it&amp;#39;s a small hedge position. Bull market returns until Fed stops injecting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:53:23 </td>
   <td style="text-align:left;"> DIA $F $SPY $TSLA $GM $QQQ  #todamoon  #carsonmars </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:53:00 </td>
   <td style="text-align:left;"> $SPY break 430 or back to 422? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:53:00 </td>
   <td style="text-align:left;"> $SPY 845 pop that is a new one $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:52:35 </td>
   <td style="text-align:left;"> $SPY I know y’all see that flag on the daily frame. 431/433 targets if we hold above 429.60s 👀 hmmmm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:52:34 </td>
   <td style="text-align:left;"> $SPY will end red/green = ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:52:29 </td>
   <td style="text-align:left;"> $APE day 60 the market is obviously fake and manipulated 🍿 naked shorts $AMC $SPY $JPM price doesn’t reflect fundamentals </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:52:08 </td>
   <td style="text-align:left;"> $SPY &amp;quot;The charges also include willfully retaining documents in violation of the Espionage Act, he said.&amp;quot; hmmm.... what about all those documents they found at Biden&amp;#39;s summer home or wherever he keeps that sweet corvette.  
 
Timing is sus. Seems like preparation, we&amp;#39;re going to hit Trump with this indictment, but let&amp;#39;s first check if we have... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:51:59 </td>
   <td style="text-align:left;"> $SPY SELL THE TOP! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:51:57 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA The market looks like it&amp;#39;s going up 2.75% across the board today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:51:20 </td>
   <td style="text-align:left;"> $CVNA was beautiful yesterday but it looks like it still has legs left. Shirts be careful, this can go pretty good for you or really bad. $SPY still having a battle under that $430. If it breaks it has to hold. Nothing is given. $TSLA has been wild for the past month leading up to this deal with $GM. Definitely some insider trading. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:51:07 </td>
   <td style="text-align:left;"> $CVNA  $SPY $QQQ $GME $SOFI .... also rolling 2-month t-bills.  weeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeeee </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:50:46 </td>
   <td style="text-align:left;"> $SPY so many flipped bullish, at just the right time 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:50:40 </td>
   <td style="text-align:left;"> $SPY this is shitting the bed st openm so obvious </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:50:32 </td>
   <td style="text-align:left;"> $SPY break the pivot high and measured move takes you to 433 and some change. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:50:18 </td>
   <td style="text-align:left;"> $SPY hell they won’t let it do anything else </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:50:04 </td>
   <td style="text-align:left;"> $SPY Pump it up!! I want to see a super bubble in tech!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:49:44 </td>
   <td style="text-align:left;"> The FBI has a server. Somewhere. Set up in a room running futures $SPY $QQQ 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:49:33 </td>
   <td style="text-align:left;"> $SPY sell! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:49:32 </td>
   <td style="text-align:left;"> $SPY market has given easy path to Fed to hike one more time. Economy is booming and it can absorb high interest rates very well </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:49:23 </td>
   <td style="text-align:left;"> $SPY R3ddit is down so I have no choice but to read you stupid fucks comments </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:49:01 </td>
   <td style="text-align:left;"> $SPY bull market baby $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:48:36 </td>
   <td style="text-align:left;"> $SPY alot of rebuilding U.S. taxpayers have to pay in Ukraine 🇺🇦 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:48:35 </td>
   <td style="text-align:left;"> $TSLA $spy $qqq $lcid go

https://www.twitch.tv/tramplewun/v/1841749838?sr=a&amp;amp;t=2s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:48:20 </td>
   <td style="text-align:left;"> $SPY They’re going after Trump because he took those classified documents that proves the deep state alphabet gang have been reverse engineering alien spacecraft and have been in contact with non-human intelligence. Democrats are probably smelly alien mutant shapeshifters. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:48:17 </td>
   <td style="text-align:left;"> $SPY what entities are sophisticated enough to manipulate Futures? $QQQ  CIA, FBI maybe DOJ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:48:13 </td>
   <td style="text-align:left;"> $SPY $QQQ $NASDAQ $RUT $DJIA 

I&amp;#39;m stunned at how meny people are oblivious of the rise in BRICS economy.

Be educated people.  This will affect the USD.

https://www.newsweek.com/how-brics-evolving-china-russia-dream-us-defying-reality-1804844 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:47:50 </td>
   <td style="text-align:left;"> $TSLA Joe&amp;#39;s at the Helm.... Oops and you&amp;#39;re buying Calls? $spy This idiot thinks it&amp;#39;s his birthday this morning  GL $KRE $KSS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:47:43 </td>
   <td style="text-align:left;"> $SPY All Time Highs, Coming to a wallet near you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:47:37 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:47:24 </td>
   <td style="text-align:left;"> $SPY retail is still shorting, silly bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:47:18 </td>
   <td style="text-align:left;"> $SPY $QQQ $SOFI Remember when people said inflation would be at 2% by summer 2023, and that the fed would be preparing for cuts. 
 
Lol. Most over-front runned pivot in history. So crowded. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:46:58 </td>
   <td style="text-align:left;"> $SPY Next week we fly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:46:54 </td>
   <td style="text-align:left;"> $SPY Energy is finished.. LO L </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:46:48 </td>
   <td style="text-align:left;"> $SPY Can we break 430-432 today o_O? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:46:43 </td>
   <td style="text-align:left;"> $SPY that all time chart though. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:46:25 </td>
   <td style="text-align:left;"> $SOFI we know CPI will be down. Fed pause oe no pause dpnt care we still doing very well $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:46:23 </td>
   <td style="text-align:left;"> $SPY   sell the open??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:46:23 </td>
   <td style="text-align:left;"> $SPY think you short this mkt. Way too many bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:46:18 </td>
   <td style="text-align:left;"> $spy $qqq $ndx $NQ_F $nasdaq AI breached </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:46:15 </td>
   <td style="text-align:left;"> $SPY I cant believe that students actually voted for this guy whom only looks out for the rich ppl.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:46:07 </td>
   <td style="text-align:left;"> $SPY    
Calls:   
📈  1st at $428.22 - $427.70 
📈  2nd at $426.70 - $426 
Puts:   
📉 below $425.99  
   
Let the setup come to you!  
Manage risk properly! cut losses quickly! And always take profits. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:45:57 </td>
   <td style="text-align:left;"> Or maybe it’s the CIA manipulating the futures $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:45:49 </td>
   <td style="text-align:left;"> $CVNA $TSLA $ADBE $SPY $QQQ my bags pre market 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:45:43 </td>
   <td style="text-align:left;"> $DOCU $SPY $SOFI $COST </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:45:31 </td>
   <td style="text-align:left;"> $WLDS  $AAPL $MSFT $SPY 
It&amp;#39;s getting hot..jump in before it&amp;#39;s to late </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:45:30 </td>
   <td style="text-align:left;"> $SPY Biden is having fun destroying the country. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:45:26 </td>
   <td style="text-align:left;"> $SPY 

This loser on CNBC saying Fed should keep raising.  

Inflation takes time to drop, dummies!   Let it be and watch for a while. Geez. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:45:13 </td>
   <td style="text-align:left;"> $JNJ vs. $SPY vs. $XLP: what is the best stock to add to your portfolio? #JohnsonJohnson https://srnk.us/go/4714048 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:44:44 </td>
   <td style="text-align:left;"> $SPY nothing like waking up in the morning and the market is already getting a head start on a beautifully green day! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:44:39 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $QQQ $META the result of April? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:44:24 </td>
   <td style="text-align:left;"> The FBI probably manipulating futures too $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:44:19 </td>
   <td style="text-align:left;"> $SPY nyc is boarded up and is losing storefronts like Russia is losing young men.  Yet, mega monopolies continue to thrive. Welcome to the new age. It’s more dystopian than we realize. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
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
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:43:38 </td>
   <td style="text-align:left;"> $SPY if your CHILD as in 17 or younger is trans gender you failed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:43:31 </td>
   <td style="text-align:left;"> $COIN DOWNGRADED to NEGATIVE by Moody&amp;#39;s might have an impact to bring it to the DOWNSIDE.  What is interesting that $SPY $QQQ $BTC.X DIA are all over the place in the last few hours. Let&amp;#39;s see the direction after the open as it could go either way. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:43:19 </td>
   <td style="text-align:left;"> $SPY 🤣🤡🧂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:42:47 </td>
   <td style="text-align:left;"> $SPY fun fact old fucking guy is a 40 yr old dude that lives in his moms basement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:42:41 </td>
   <td style="text-align:left;"> Let&amp;#39;s play a game. Guess which ticker this is.

This is the play from yesterday. Alerted the near perfect level for a reversal trade. Just $0.03c from its absolute bottom of the day.
All possible from ONLY buying when H% is low. Look at the each steps shown.

$SPY $TSLA $AAPL $MSFT $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:42:31 </td>
   <td style="text-align:left;"> $SPY apparently trump must be back in office with all this bull pumping? Jk cold reality is we have morons at the helm. Can’t wait for the 🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:42:29 </td>
   <td style="text-align:left;"> $SPY 

Geez. Biden is making normal people sound evil.  Strange 🤔

&amp;quot;Biden went on to say that &amp;quot;extreme officials are pushing hateful bills targeting transgender children, terrifying families and criminalizing doctors.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:42:27 </td>
   <td style="text-align:left;"> $SPY happy money Friday!!! 💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:42:21 </td>
   <td style="text-align:left;"> $SPY S&amp;amp;P futures rollover from June contract to September in effect.   June expires in 7 days, things get choppy during the transition as traders sell June and buy September. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:42:13 </td>
   <td style="text-align:left;"> $SPY we need $META, $MSFT and $AMZN to get with the program lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:42:11 </td>
   <td style="text-align:left;"> $SPY in the last month the top 30 stocks in the SP500 have moved 20% or more up

So how in the hell you still say the word bearish or anything even related with bearish 

Is  FUCKING BULL RUN  stop watching whatever you watching and fallowing whatever you fallow 
Erase everything in you fucking head and start from scratch because you definitely way off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:41:48 </td>
   <td style="text-align:left;"> $SPY  $QQQ  -   Remember Kids, we don&amp;#39;t talk to strangers or get in vans with people who claim &amp;quot;we&amp;#39;re in a new bull market&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:41:41 </td>
   <td style="text-align:left;"> $SPY Low income bears very angry this morning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:41:11 </td>
   <td style="text-align:left;"> $SPY nothing can stop the dancing man....not even the quantum world.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:41:10 </td>
   <td style="text-align:left;"> DIA $F $SPY $TSLA $GM $QQQ   CARS ON MARS ... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:41:09 </td>
   <td style="text-align:left;"> $SPY Baggy pumpers. Keep pumping money but never sell. It only goes up if you don’t sell. maintain the broke-rage account like a trophy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:40:42 </td>
   <td style="text-align:left;"> $SPY  Poke yourself in the eye you lazy bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:40:41 </td>
   <td style="text-align:left;"> $SPY This person gets it! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:40:34 </td>
   <td style="text-align:left;"> $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:39:41 </td>
   <td style="text-align:left;"> $SPY I DONT KNOW WHAT IM DOING BUT I WANT THE MONIES!🤠☘️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:39:06 </td>
   <td style="text-align:left;"> $SPY  $QQQ   Happy Proud of Yahweh Month ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:38:59 </td>
   <td style="text-align:left;"> $SPY futures choppy but so many things getting massive pumps pre market $TSLA $ADBE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:38:24 </td>
   <td style="text-align:left;"> $SPY PAMP DAT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:38:08 </td>
   <td style="text-align:left;"> $SPY looks weak bulls can&amp;#39;t crack it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:37:54 </td>
   <td style="text-align:left;"> $TSLA back to 1k end of year $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:37:48 </td>
   <td style="text-align:left;"> $SPY i am seeing quadriple tops at 430 lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:37:37 </td>
   <td style="text-align:left;"> $QQQ $SPY isn’t this what the Fed (central banks) want in their fight against inflation?  🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:37:20 </td>
   <td style="text-align:left;"> Bye bye bear... New S&amp;amp;P 500 bull market has legs - BofA $SPY $SPX 
 
https://www.streetinsider.com/Analyst+Comments/Bye+bye+bear...New+S%26P+500+bull+market+has+legs+-+BofA/21781706.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:37:18 </td>
   <td style="text-align:left;"> $SPY finally switching to bullish on this for the first time officially! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:37:11 </td>
   <td style="text-align:left;"> $SPY so how is the majority bearish when the fear and greed index is at 77? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:37:01 </td>
   <td style="text-align:left;"> $SPY $GLD negative correlation yet both going up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:37:00 </td>
   <td style="text-align:left;"> $SPY Start using AI now while others panic https://youtu.be/9wFufMFG5fE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:36:56 </td>
   <td style="text-align:left;"> $SPY soooooooooooo............ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:36:51 </td>
   <td style="text-align:left;"> Give it to Mike z Wilson today $450 $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:36:44 </td>
   <td style="text-align:left;"> Which stock is the best to invest? Compare $GDX vs. $SPY vs. $VTI. https://srnk.us/go/4714010 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:36:41 </td>
   <td style="text-align:left;"> $SPY if fed wants to really control the inflation, they need to go .50 .75 this time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:36:30 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:36:14 </td>
   <td style="text-align:left;"> $SPY Jimmy Carter 2.0 ✔️✔️✔️✔️⤵️⤵️🤫🤫🤫🤫🤫🤫 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:36:14 </td>
   <td style="text-align:left;"> $SPY Only up forever. Unlimited money supply. Election cycle 401 pump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:36:03 </td>
   <td style="text-align:left;"> $SPY Morgan Stanly being the biggest joke of them all $QQQ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:36:02 </td>
   <td style="text-align:left;"> $SPY $ES_F gorgeous. The amount of free money they are printing to the unbias traders right now between 4270 and 4300 is outrageous. GET YOURS!!!! A Rational Thought~ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:35:55 </td>
   <td style="text-align:left;"> $SPY One line to rule them all! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:35:54 </td>
   <td style="text-align:left;"> $TSLA pump to 300 with your fake upgrade so massive dump happens. The wait for many shareholders tired of Felon Muskarat, thanks to GM and Ford takeover, is over! $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:35:50 </td>
   <td style="text-align:left;"> $TSLA $SPY EZ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:35:42 </td>
   <td style="text-align:left;"> $SPY CNBC drunk or something why is NIO a popular quote ahahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:35:41 </td>
   <td style="text-align:left;"> $SPY its canadian recession. NOT U.S .buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:35:31 </td>
   <td style="text-align:left;"> In Group 3 Live Session today, we will also explain that the #Dollar has ended the bounce and will get sideways to lower in a Negative USD Dynamic. #Equities and #commodities should rally.  #Elliottwave #Stocks #Trading $SPY $SPX $AAPL $TSLA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:35:20 </td>
   <td style="text-align:left;"> Disgrace to the Stock Race  the bears 🐻 
$SPY $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:35:17 </td>
   <td style="text-align:left;"> $SPY the local $TSLA charging station is already packed. Need more stations. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:35:13 </td>
   <td style="text-align:left;"> $SPY Most retarted market I have ever seen. Embrace being retarted and its easy money tbh. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:35:12 </td>
   <td style="text-align:left;"> $NFLX BOOM 💥 Told you all yesterday 📈

$SPY $TSLA $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:35:09 </td>
   <td style="text-align:left;"> $SPY 

&amp;quot;EXCLUSIVE: Former President Trump said his federal indictment is &amp;quot;election interference at the highest level,&amp;quot; telling Fox News Digital that the Biden administration is &amp;quot;the most corrupt&amp;quot; in history.&amp;quot;

Ok I agree Biden is totally corrupt.

BUT, is Trump saying that this indictment will cause a voter who WAS going to vote for him to NOT vote for him ?   🤔 Hmmm 

I doubt it. I think folks have made up their mind on Trump. I&amp;#39;d be curious to hear from a voter who was leaning Trump and now won&amp;#39;t just because of this. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:34:51 </td>
   <td style="text-align:left;"> $SPY $QQQ  
 
LMAO 
Meme stocks are back! I guess Fed&amp;#39;s rate hikes did shit for anything. Inflation is naturally subsiding. However, it will spike back with vengeance, if Fed keeps adding secret liquidity because it is scared shitless with banking crisis. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:34:48 </td>
   <td style="text-align:left;"> $SPY when break 430 bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:34:38 </td>
   <td style="text-align:left;"> $SPY nothing crazy, just MAs…new quarter rollover and running into 200 MA rejection…pretty clear where we go for the summer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:34:12 </td>
   <td style="text-align:left;"> $SPY oops fake news lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:34:07 </td>
   <td style="text-align:left;"> Big Bears 🐻 are a disgrace to Humanity $SPY $QQQ $SPX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:34:05 </td>
   <td style="text-align:left;"> $SPY $QQQ  with dxy about to tumble, the market is about to take off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:34:02 </td>
   <td style="text-align:left;"> $SPY $QQQ a preview of what’s coming globally. RISING UNEMPLOYMENT. ☠️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:33:53 </td>
   <td style="text-align:left;"> $QQQ $SPY one more hour until bulls get rugged </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:33:23 </td>
   <td style="text-align:left;"> $SPY Who bought POS $MSFT instead of pumping $TSLA $CVNA ? 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:32:58 </td>
   <td style="text-align:left;"> $SPY $QQQ zero sells, only buys since Oct-Dec 2022... 
 
- Hedged when things looked rough. 
- Cashed those in when things looked better. 
- Trolled the dooomers on ST. 
 
That was the way. 
 
No need to change it, *even* if we get further pullbacks/consolidations... even corrections. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:32:54 </td>
   <td style="text-align:left;"> $SPY evere day for last 3 month I was reading &amp;quot;tomorrow blood bath&amp;quot;, so when? 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:32:52 </td>
   <td style="text-align:left;"> You Bears 🐻 are a disgrace to the Stock Race $SPY $QQQ $NDX   a disgrace! Flat out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:32:45 </td>
   <td style="text-align:left;"> $SPY $QQQ WSJ - The S&amp;amp;P 500 starts a new bull market. Outsize gains from a handful of companies, including Amazon, Tesla and Nvidia, helped power the S&amp;amp;P 500 higher over the past few months. Many of those same stocks led Thursday’s market advance, propelling the broad index up 0.6% and ending its longest bear market since the 1940s. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:32:19 </td>
   <td style="text-align:left;"> $SPY As this US moves further towards a liberal dictatorship what will the effects be on the markets? Tough one to figure out. I think it will be very negative looking at other countries under one government. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:32:18 </td>
   <td style="text-align:left;"> $SPY this market is a joke. Can&amp;#39;t wait for jpow to slap us down next week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:31:24 </td>
   <td style="text-align:left;"> Group 3 Live Session will start at 9AM. Tune in @ https://elliottwave-forecast.com/amember/go.php?r=34991&amp;amp;i=l1 where we will explain all the instruments and what should be happening next. #Elliottwave #Stocks #Trading $SPY $QQQ $TSLA $AAPL $SPX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:31:18 </td>
   <td style="text-align:left;"> $SPY Higher for longer✔️⤵️🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:31:08 </td>
   <td style="text-align:left;"> $SPY Strongest economy in recorded history.  Everyone I know is still spending like normal, but I don’t hang out with broke people so not sure what broke people are doing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:31:04 </td>
   <td style="text-align:left;"> $DIA $QQQ $SPY is now 429.3s. it so strong. AI Tech Rally and Banks Come Back help it a lot. SPY will drop 2-4 $ After the Open. $SOXL is now 22.75. I Shorts it for 22.5s avg and I have take +0.5 +1.2 in two days. I will have another +0.5-1. 1-2 Trading days. I had +0.4 yesterday and I did not Take  it bc I want at least +0.5. 
 
$SPY was 373.s 13 July at CPI I have Calls for 410+ for FOMC ER rally. SPY 410 FOMC and 431 at ER mid August. I calls later 400 in 1-3 weeks. 1st week 410 2nd week 400 3rd week 390. 13 oct 350 -1.5%. at 10h19 am I calls for a Close Green and 410+ in 4-6 weeks. SPY Close 365 +2.6% 13 dec CPI SPY 411.s. Icalls for Taxes Losses Selling 390-380. a week later 378 and I Calls for FOMC 400-405 etc.. Msgs Posted and Saves. 
 
Soon or Later SPY will Crash FED Rates  5.25%+  Always make market  Crash. AI Stocks have drop as I Predicted and Banks will be next aGain as I Predicted. 13 march Banks Crash and SPY 380. GLTA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:30:58 </td>
   <td style="text-align:left;"> $SPY no one is blaming Biden now. All time high soon. No recession </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:30:56 </td>
   <td style="text-align:left;"> $SPY I believe the worst is over, but a pullback to 417-420 is necessary. Markets are churning and need a small 2-5 day organized pull back. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
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
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:30:40 </td>
   <td style="text-align:left;"> $SPY for those who weren’t old enough to see how people lost everything during the dot-com bubble, now you know </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:30:38 </td>
   <td style="text-align:left;"> $SPY omg bears are raped again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:30:31 </td>
   <td style="text-align:left;"> $SPY sup lil bro? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:30:30 </td>
   <td style="text-align:left;"> $SPY too is in ? They’re are hiking next week so next week will be red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:30:17 </td>
   <td style="text-align:left;"> $SPY tiktok on the count. guess who won? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:30:12 </td>
   <td style="text-align:left;"> $SPY Calls be preenteng </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:29:58 </td>
   <td style="text-align:left;"> These bears turned into complete losers $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:29:02 </td>
   <td style="text-align:left;"> I didn’t sell only added when it dipped to the 100s and Bears think i’ll sell now 😂😂😂😂

$TSLA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:28:56 </td>
   <td style="text-align:left;"> $SPY this is what i can’t understand!! Strong economy? Really lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:28:23 </td>
   <td style="text-align:left;"> $GM the stock has done basically nothing for the last 10 years with the same person in charge.. that you “trust” 🤣🤣 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:28:22 </td>
   <td style="text-align:left;"> $SPY I want that mythical 2% day lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:28:18 </td>
   <td style="text-align:left;"> $SPY Bears rn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:28:18 </td>
   <td style="text-align:left;"> $BTC.X $ETH.X $SPY I mean who won? mask singer. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:27:54 </td>
   <td style="text-align:left;"> $ES_F $SPY we lied. Took it short 8 for 8 shorting 4300. Only 2 point 2 ES a piece. Simple morning. While retailers blab about bulls and bears. The smart ones just take the low hanging fruit and enjoy our day. A Rational Thought~ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:27:40 </td>
   <td style="text-align:left;"> $SHOP $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:27:33 </td>
   <td style="text-align:left;"> $SPY $QQQ smart money is going to cash out soon. Today could be a good day to do so before next weeks Fed meeting and CPI.  They used 7 big companies to take the markets out of the bear market.  Is it sustainable?. We will see.  See you at open. GLTA. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:27:08 </td>
   <td style="text-align:left;"> $SPY $430 breaks the run begins </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:26:59 </td>
   <td style="text-align:left;"> $SPY Same low volume, pre-market prop job. lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:26:45 </td>
   <td style="text-align:left;"> $SPY 🐸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:26:36 </td>
   <td style="text-align:left;"> latexb3c6b8ea8c852354aad7a34c125cf8b9SPY ...$IWM next let&amp;#39;s go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:26:21 </td>
   <td style="text-align:left;"> $SPY it’s a scam fed ponzi </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:26:14 </td>
   <td style="text-align:left;"> $SPY We rally on Trump indictment, 435+ possible today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:26:12 </td>
   <td style="text-align:left;"> $SPY Bears are low testosterone individuals. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:26:11 </td>
   <td style="text-align:left;"> $TSLA $QQQ $SPY $NVDA 

I am posting less on Stocktwits! 

If u want to follow me I’m on Twitter @Banana3Stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:25:56 </td>
   <td style="text-align:left;"> $SPY will open red! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:25:31 </td>
   <td style="text-align:left;"> $SPY went up on strong payrolls, went up on bad jobless claims. WTF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:25:16 </td>
   <td style="text-align:left;"> $SPY sometimes it feels like all the leverage is in downside protection so every move lower means that protection gets monetized and the market stays up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:25:04 </td>
   <td style="text-align:left;"> $SPY $SPX play for today is buy the ATM 0dte straddle, scalp the quick move on open, if we don&amp;#39;t move hard within like 30 minutes, just sell it back. worth the risk when we&amp;#39;re around yearly highs and there&amp;#39;s gonna be a fight on open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:25:04 </td>
   <td style="text-align:left;"> $SPY not looking good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:24:25 </td>
   <td style="text-align:left;"> $SPY same bogus daily lol ofc this is green. Can’t make this up.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:24:21 </td>
   <td style="text-align:left;"> $SPY $DWAC

THE OLD BURISMA BOYS!

IMPEACHMENT THEN INDICTMENT!

NO MALARKEY! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:24:18 </td>
   <td style="text-align:left;"> $SPY VIX penny stock soon.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:24:13 </td>
   <td style="text-align:left;"> $SPY pumping it up for Bidens election. Lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:24:11 </td>
   <td style="text-align:left;"> What is the difference between $ETN and $SPY? Learn it. #Eaton https://srnk.us/go/4713956 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:22:57 </td>
   <td style="text-align:left;"> $SPY wen CP-Lie </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:22:44 </td>
   <td style="text-align:left;"> $VOR LFGO NOW!!!!

OVERLOOKED BIOTECH BEAUTY 

THE CURED CANCER!!!!!

Wowowowowowowo

 $CYCC does cancer $MOBQ nice moves $SPY bullish $TSLA wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:22:26 </td>
   <td style="text-align:left;"> $SPY pretty much Bears summed up $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:22:21 </td>
   <td style="text-align:left;"> $SPY just liquidated my 401k into money market. Don’t care if I miss another 5% rally when the downside is 40%+ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:22:19 </td>
   <td style="text-align:left;"> $SPY assets soaring. Jpow gonna look like an idiot for the 2nd time when inflation  comes back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:22:13 </td>
   <td style="text-align:left;"> $SQQQ You know we are gonna nuke your rotation to safety right! $XLY $SPY $XLU $XLF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:22:06 </td>
   <td style="text-align:left;"> $SPY Market will stay irrational longer than you can stay solvent. 

Practically this in play now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:21:50 </td>
   <td style="text-align:left;"> $DIA $SPY $IWM Macro focus next week will be on the US CPI (Tues morning), the FOMC decision (Wed afternoon), China’s May economic data (Wed night), the ECB decision (Thurs morning), and the BOJ decision (Fri morning). Regarding earnings, the big names to watch include: Mon night (ORCL), Wed night (LEN), Thurs morning (JBL, KR), and Thurs night (ABDE). There are a few analyst meetings that will be in focus, including: Mon (CRM, ILMN); Tues (HD); and Wed (BLK). It will also be another busy week of sell-side conferences, but investors will pay particular attention to the Morgan Stanley financials event (if the pro-cyclical/small-cap rotation is going to continue, it will require participation from the financials). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:21:47 </td>
   <td style="text-align:left;"> $SPY very rare meme template hunted down in clown museum in Nebraska. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:21:34 </td>
   <td style="text-align:left;"> $SPY 

Just went short, let’s see how much more they pump it. Maybe a couple more weeks but if it is gonna go higher we have to reset some rsi burn. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:21:28 </td>
   <td style="text-align:left;"> $SPY if you lotto played $NQ_F you already banking on calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:21:21 </td>
   <td style="text-align:left;"> Game Plan, Levels and Chart: 
(Note that I will trade the June contract today and I will switch to the September contract on Monday) 
 
https://palmafutures.substack.com/p/s-and-p500-e-mini-levels-for-692023 
 
$SPX $ES_F $SPY $VIX  
#DayTrading #investing #StockMarket #FuturesTrading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:21:01 </td>
   <td style="text-align:left;"> $SOXL vs. $SPY vs. $VBR: what is the best stock to add to your portfolio? https://srnk.us/go/4713943 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:20:59 </td>
   <td style="text-align:left;"> $SPY C&amp;#39;mon, 10 year about 165 bps lower than 6 month bill, the hikes aren&amp;#39;t doing anything...Rent still going up, food still going up, car prices still going up.... Fed still printing money so stocks still going up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:20:57 </td>
   <td style="text-align:left;"> $SPY Anyone know what the criminal MMs have planned for us today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:20:57 </td>
   <td style="text-align:left;"> $SPY gdp growth thanks to inflation 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:20:37 </td>
   <td style="text-align:left;"> $SPY wow getting closer to 429.62 😳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:20:35 </td>
   <td style="text-align:left;"> $SPY 430 call at open? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:20:18 </td>
   <td style="text-align:left;"> $QQQ greatest ponzi schemes.  The greater fool is always there to keep buying , nothing will ever be corrected.  $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:20:18 </td>
   <td style="text-align:left;"> The Nasdaq $QQQ broke out several weeks ago. The S&amp;amp;P 500 $SPY broke out two weeks ago. Now it looks like the DJIA $DIA is headed in that direction. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:20:07 </td>
   <td style="text-align:left;"> Could CRISPR Therapeutics Become the Next Vertex Pharmaceuticals? | The Motley Fool 

$spy $xbi $mrk $vrtx  https://www.fool.com/investing/2023/06/08/could-crispr-therapeutics-become-the-next-vertex/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:19:51 </td>
   <td style="text-align:left;"> $SPY pump NVDA , so we can rip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:19:46 </td>
   <td style="text-align:left;"> $SPY $NVDA LOTTO 395C </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:19:24 </td>
   <td style="text-align:left;"> $GM $F $TSLA  Looking Juicy AF
$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:19:00 </td>
   <td style="text-align:left;"> $SPY my hedge is doing so badly its going green on the upside. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:18:44 </td>
   <td style="text-align:left;"> $SPY 

Meanwhile $RSP is rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:18:38 </td>
   <td style="text-align:left;"> $SPY TSLA will sell off at open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:18:21 </td>
   <td style="text-align:left;"> $SPY  Let&amp;#39;s pretend we are on financial position pumper TV (anyone who understands economics asking a legit question to pumper) &amp;quot;So why would anyone want to buy at these levels given the current state of the world and our economy?&amp;quot;. (Pumper). &amp;quot;because brah because&amp;quot;.   Then pumper gets cheers and applause as more sheep race to buy! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:18:14 </td>
   <td style="text-align:left;"> $SPY it is approaching that 429.63 resistance again. 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:18:00 </td>
   <td style="text-align:left;"> $SPY I’m almost positive you should be using the extended hours chart right now, there is for sure some fuckery going on between the two charts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:17:54 </td>
   <td style="text-align:left;"> $SPY 5% up day for NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:17:43 </td>
   <td style="text-align:left;"> $SPY happy Friday kids!!!! Looking like an inside/green day let’s get it!!!!!! :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:17:42 </td>
   <td style="text-align:left;"> $SPY I heard SPY is getting into AI.  SPY 600 coming soon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:17:28 </td>
   <td style="text-align:left;"> $SPY all credit due to Joe .. trumptards </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:17:25 </td>
   <td style="text-align:left;"> $SPY send spy up 1%  and I won’t say anything bad about Biden for the weekend pls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:17:16 </td>
   <td style="text-align:left;"> $SPY there won’t be much movement until 0DTE gamblers jump in. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:17:13 </td>
   <td style="text-align:left;"> $SPY prepping for higher while the  turncoat Red Elephants begin to crush their fearless leader behind closed doors with words that dig a grave. 
 
It is all coming to fruition and it isn&amp;#39;t a political ploy by the asses as some sadly believe. 
 
When most act in a criminal manner, there is usually a price to pay. Let&amp;#39;s see how long the Teflon coating lasts. 
 
Markets will dismiss the news and go on tracking North due to factors beyond its control. 
 
Enjoy! We are witnessing a historical event. An ex- prez with more than 100 indictments coming his way! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:17:08 </td>
   <td style="text-align:left;"> $SPY $ES_F Overnight, $SPX has defended 4286 and broken 4295.  Now a retest of 4295, hold and that sets us up beautifully to target 4302/4306 and new YTD highs. Fail and we fall to 86/80. Trust last night&amp;#39;s levels! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:16:59 </td>
   <td style="text-align:left;"> $SPY how tho </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:16:31 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL  market is going to go parabolic, scary but deserved by the world&amp;#39;s tried and hardened bulls of the globe. Take a bow. You are believers in America. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:16:29 </td>
   <td style="text-align:left;"> $SPY will those $430 calls pay? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:16:26 </td>
   <td style="text-align:left;"> $SPY Black Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:16:14 </td>
   <td style="text-align:left;"> $SPY I don&amp;#39;t even look at the chart anymore. I just buy calls esp on red days. 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:16:12 </td>
   <td style="text-align:left;"> $TSLA $GMC $SPY 

Meanwhile chargepoint….. i can see chevron or exxon adding tesla chargers to their gas stations if they want to stay relevant. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:16:08 </td>
   <td style="text-align:left;"> $SPY forreal havnt seen a red open in a long time and if it is lately it’s like -.001% red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:15:48 </td>
   <td style="text-align:left;"> $SPY $QQQ never been more bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:15:48 </td>
   <td style="text-align:left;"> $SPY $QQQ are they planning to dump the markets today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:15:46 </td>
   <td style="text-align:left;"> $BBAI $SPY  as I said before.  MiP is a rain cloud.   He is nothing but bad luck when it comes to individual stocks (not SPY options). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:15:45 </td>
   <td style="text-align:left;"> $SPY shorted 4300 plz squeeze me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:15:17 </td>
   <td style="text-align:left;"> $SPY 429.62 is the wall to break </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:15:17 </td>
   <td style="text-align:left;"> $SPY never think these thoughts “they cant bring it down any lower” or “they cant push this up any higher”.. because they can and they will 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:15:04 </td>
   <td style="text-align:left;"> $SPY 0dte puts at open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:15:01 </td>
   <td style="text-align:left;"> $ES_F hit 4300 $SPY into Bull Market. It needs to stay above 4300 for a week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:15:00 </td>
   <td style="text-align:left;"> $SPY same thing every morning with this stupid ass market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:14:49 </td>
   <td style="text-align:left;"> $SPY alright screw It ima chase 0DTE calls because it has been pumping every day and I guarantee u today is the day it tanks 2 $ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:14:45 </td>
   <td style="text-align:left;"> $SPY you know what to do, the same 7 stocks! spin that shit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:14:45 </td>
   <td style="text-align:left;"> $SPCE after successful flights , $SPY flying , $TSLA flying , commercial flights coming and yet this is at $4 ?.Use your common sense. At a minimum weak day on the market this will sink. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:14:42 </td>
   <td style="text-align:left;"> $SPY My July $425 Puts will be ok. Even better next week when the fed raises rates. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:14:38 </td>
   <td style="text-align:left;"> $SPY bullish on Ukraine war, higher yields, higher fed fund rates, higher rental cost, higher mortgage, inverted yield curve, higher CPI, bad PPI, unemployment, deficit increase, and money printer.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:14:38 </td>
   <td style="text-align:left;"> $SPY Bears r fuk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:14:19 </td>
   <td style="text-align:left;"> $SPY futes ripping higher again this morning… massive short squeeze today just like last several Fridays </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:13:52 </td>
   <td style="text-align:left;"> 7 Great Dividend Stocks Under $25 for 2023 https://investorplace.com/market360/2023/06/7-great-dividend-stocks-under-25-for-2023/ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:13:51 </td>
   <td style="text-align:left;"> $SPY Strongest economy I’ve ever seen. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:13:48 </td>
   <td style="text-align:left;"> $SPY Powell continues to be the world chump babying the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:13:24 </td>
   <td style="text-align:left;"> $SPY in the best case scenario will go to 435 in the worst to at lest 380. You can decide how to position yourself. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:13:23 </td>
   <td style="text-align:left;"> ETF Sentiment: $SPY is the #1 ETF that institutions are trading with 1.1M options contracts.

Market analysis included in screenshot of dashboard from 🔥 INSIDERFINANCE.IO 🔥 (Link in profile - @InsiderFinance) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:13:21 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $ARKK $META . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:13:13 </td>
   <td style="text-align:left;"> $SPY gonna happen again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:13:04 </td>
   <td style="text-align:left;"> $NFLX $SPY  🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:12:46 </td>
   <td style="text-align:left;"> $SPY $ES_F we&amp;#39;ve minted 4300 short for 7 different scalps for thousands of dollars. Do we believe the short is there again? Well the level is, but eventually they bang the door long enough it gets opened. If it opens, it really opens. I&amp;#39;ll wait and see if number 8 is the opening first. A Rational Thought~ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:12:30 </td>
   <td style="text-align:left;"> $SPY puts at open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:12:21 </td>
   <td style="text-align:left;"> $SPY Bulls think ATHs are deserved when the world is the worst it&amp;#39;s been since the geopolitical and economic tensions of the 1970s 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:12:18 </td>
   <td style="text-align:left;"> $SPY shorts ⬇️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:12:04 </td>
   <td style="text-align:left;"> $spy 4310 and crash </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:11:55 </td>
   <td style="text-align:left;"> $JPM vs. $SPY vs. $TLT: what will be the best investment? #JPMorganChaseCo https://srnk.us/go/4713903 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:11:54 </td>
   <td style="text-align:left;"> $SPY Appreciate the cheaper puts at open bulls. Take it up higher and higher </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:11:16 </td>
   <td style="text-align:left;"> $SPY No pullback expected- blue sky to 435 today, trapping bear after bear above 430 fueling our 0dtes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:11:11 </td>
   <td style="text-align:left;"> $SPY $VIX I think J-Pow might need to raise rates another 3% or 4% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:10:41 </td>
   <td style="text-align:left;"> $SPY every week the markets pump non stop or float at resistance .. wtf happen to red days ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:10:35 </td>
   <td style="text-align:left;"> $QQQ $SPY free money day is here!! No downside risk. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:10:25 </td>
   <td style="text-align:left;"> $NVDA $SPY $QQQ $TSLA  do all  nvidia bulls feel safe relying on TSMC? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:10:06 </td>
   <td style="text-align:left;"> $SPY Dancing man keeps dancing boys...you know what that means....no one can stop the dancing man.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:09:55 </td>
   <td style="text-align:left;"> $SPY not a matter of if but when and how much </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:09:28 </td>
   <td style="text-align:left;"> $SPY Yeah, pull back to 4280 in the morning to make the fake fakeout and then run to 4325 today. 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:09:26 </td>
   <td style="text-align:left;"> $SPY can anything stop this insane melt up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:09:20 </td>
   <td style="text-align:left;"> $SPY Time to panic bears. You know the drill. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:09:10 </td>
   <td style="text-align:left;"> $SPY Weekly chart with machine learning ma&amp;#39;s. Looking interesting $GOLD $SLV </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:09:03 </td>
   <td style="text-align:left;"> $TSLA $SPY 

They wanted him out of twitter and now they created a monster. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:08:43 </td>
   <td style="text-align:left;"> $SPY if u think this going up I’m sorry </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:08:22 </td>
   <td style="text-align:left;"> $NIO $QQQ $SPX $SPY 

And shorts already blasted. They don’t learn 🙂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:08:03 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:07:37 </td>
   <td style="text-align:left;"> Feels like there’s a hedge fund going broke today on a massive short squeeze break out $SPY $QQQ $SPX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:07:23 </td>
   <td style="text-align:left;"> $SPY these guys reading the last 24-hour headlines “new Bull Market”.  let’s see what they do… 🤔

https://www.cnbc.com/2023/06/07/millionaires-hoarding-cash-betting-on-higher-rates-cnbc-survey-says.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:07:07 </td>
   <td style="text-align:left;"> $SPY TRUMP 2024 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:06:29 </td>
   <td style="text-align:left;"> $SPY   Only up, up, up!!!
S&amp;amp;P is in a New Bull Run!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:06:13 </td>
   <td style="text-align:left;"> $SPY SoFi has been killing it 🔥 come join the fun 

https://www.sofi.com/invite/invest?gcp=6a8612e3-a8ae-40a0-a482-279de12ecefa&amp;amp;isAliasGcp=false </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2023-06-09 20:06:01 </td>
   <td style="text-align:left;"> $SPY bulls are delusional..the top is in </td>
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
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:05:17 </td>
   <td style="text-align:left;"> 6/9/2023 
 
I&amp;#39;ve been posting ongoing that we are in a bull market but NOW IT&amp;#39;S OFFICIAL 
 
The benchmark S&amp;amp;P 500 is now UP 20% off it&amp;#39;s October lows. 
 
Market winners, market pros have always said the best time to get into the market is at the beginning of a bull market.   
 
6/9/2023  
 
$spy $spx $study $dia $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:04:04 </td>
   <td style="text-align:left;"> $QQQ help me please 🙏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:03:11 </td>
   <td style="text-align:left;"> Can test $440 enough hedge funds short get caught up on low volume liquidity. More of them then people paying attention to the market daily bases $SPY $QQQ $SPX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:02:31 </td>
   <td style="text-align:left;"> $QQQ at this rate we will have the lower vix in the history of the VIX. So fucking stupid </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:01:07 </td>
   <td style="text-align:left;"> $QQQ QQQ rebounded from the bottom yesterday and entered a relatively indecisive uptrend. On the 4-hour chart, there is a tendency for a head and shoulders pattern, with the neckline around 354, which corresponds to the pink resistance zone in the chart. Today, pay attention to the reaction of the price in this range. It leans towards selling at high levels. If a strong bullish candle breaks above 354.3 and holds steady, it would require following the upward trend and consider going long. Otherwise, 354 could be a medium-term secondary high point. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:00:52 </td>
   <td style="text-align:left;"> 🛑*PUTIN: RUSSIA TO PLACE NUKE WEAPONS IN BELARUS AFTER JULY 7-8❗
https://twitter.com/PaulVikingGlob1/status/1667135168002260992?t=e3fQ2lRL9nuqVgfvBAAb2A&amp;amp;s=19
$QQQ $SPY $DJIA $ARKK $NASDAQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:00:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X $NVDA $MSTR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:00:08 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ ok bulls.
Y’all just need to hold it here for another hour and a half. Hoping to be able to buy puts at this level before the call strikes are printed for today’s expiration. Once that happens  this booger is gonna dip. Just a little longer. Surprise me and run it to $260 so I can add even more. Please.. pretty please. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 20:00:01 </td>
   <td style="text-align:left;"> $SPY $META $SQ $QQQ $SOFI Literal complacency. There is no way to fail. 
 
In game theory, when enough people believe this, is exactly when it cant be true -- otherwise everyone who simply receive free money. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:59:10 </td>
   <td style="text-align:left;"> $SPY  Wen that Lambo?     $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:58:47 </td>
   <td style="text-align:left;"> $SPY $QQQ  Short squeeze to a record high today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:58:40 </td>
   <td style="text-align:left;"> $QQQ find you someone who looks at you the way futures traders look at ndx at 3am </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:57:36 </td>
   <td style="text-align:left;"> $QQQ moon market says adct and good morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:54:49 </td>
   <td style="text-align:left;"> $tsla with cpi on Tuesday… markets may not rush $spy $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:53:41 </td>
   <td style="text-align:left;"> $BODY vs. $QQQ: what will be the best investment? https://srnk.us/go/4713837 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:53:05 </td>
   <td style="text-align:left;"> $PLTR $17 then $10-$7 for gap fill

$SPY $SPX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:51:16 </td>
   <td style="text-align:left;"> $QQQ Fake pump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:50:52 </td>
   <td style="text-align:left;"> $SPY $QQQ san other suspicious pump in PM. Let’s see what WS has in agenda for today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:50:45 </td>
   <td style="text-align:left;"> $NIO 😉

$SPY $SPX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:42:45 </td>
   <td style="text-align:left;"> $SOXS loading with both hands. This Friday feels different from recent past Fridays where $VIX crush program was much stronger. Could indices reverse? $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:42:29 </td>
   <td style="text-align:left;"> $QQQ $SPY  
 
Europe is in STAGFLATION 
US is in STAGFLATION whether you believe or not....once market realise this, its going to rock and roll for everybody.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:40:31 </td>
   <td style="text-align:left;"> $SOFI hitting a 52 week high ere the. 10.25 on deck. This stock will see 15-20$ in the next 12 months as financials are revised to reflect student loans. Noto has been clear that the resumption of student loans is not in their guidance $SPY $QQQ $KRE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:40:02 </td>
   <td style="text-align:left;"> $SPY $QQQ $DWAC Time to rally 5%! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:39:18 </td>
   <td style="text-align:left;"> $SPY $QQQ don&amp;#39;t be afraid to trade on the OTC market becuz you can make lots of money there </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:38:02 </td>
   <td style="text-align:left;"> $QQQ no surprise here. Quietly turn it itself to green over night. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:37:52 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA let it be </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:36:31 </td>
   <td style="text-align:left;"> $WLGS $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:35:27 </td>
   <td style="text-align:left;"> $SPY $QQQ We&amp;#39;re at extreme greed levels (esp. put/call ratio 5 day avg.), but several pundits noting if next week&amp;#39;s CPI has a 3 handle SPX breakout above 4300 likely. Will have the popcorn ready next week CPI, JayDay (78% no hike), PPI on deck. OPEX thereafter and JUL earnings season a month away. 
 
https://www.cnn.com/markets/fear-and-greed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:34:52 </td>
   <td style="text-align:left;"> $DIA $SPY $QQQ What will happen first Trump will be convicted or Trump will default ON ANOTHER LOAN??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:34:40 </td>
   <td style="text-align:left;"> $QQQ https://www.stockilluminati.com/qqq/news.php - May CPI Report Preview: Inflation Is Settling At 5% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:33:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $META $SQ $SOFI money printing machine all warmed up and ready today. We can’t lose in this market. I foresee algos and feds pumping this for months. Makes a bad administration look good. If you’re a bear right now I feel sorry for you. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:33:00 </td>
   <td style="text-align:left;"> In the last month $QQQ has a been trading in the 322.94 - 357.50 range, which is quite wide. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:32:42 </td>
   <td style="text-align:left;"> This may be more bearish than any day in history $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:31:59 </td>
   <td style="text-align:left;"> $QQQ where is the Tebow guy? He has vanished from twitter 🤣🤣🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:31:22 </td>
   <td style="text-align:left;"> @MLinv $SPY $QQQ meanwhile we have million+ puts shorting the market every day. 
 
Complacency??? lmao......why is there so much ignorance. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:31:09 </td>
   <td style="text-align:left;"> $SPY $QQQ $ARKK $TLT $GOLD 

Well, $460 here we come. 
What’s that sideline money going to do now?
Have all the shorts covered yet?
I know bull margin has been steadily increasing each month since January. 
October 2022 was our low. 
It’s time to move and shake again!

https://www.marketwatch.com/story/s-p-500-exits-longest-bear-market-since-1948-what-stock-market-history-says-about-what-happens-next-a336a139 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:30:18 </td>
   <td style="text-align:left;"> $QQQ https://www.stockilluminati.com/qqq/news.php - Big Tech Strikes Back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:30:06 </td>
   <td style="text-align:left;"> $spy Complacency is the greatest enemy of excellence….just wait for it…. if you look closely you can see it coming.. don’t let it happen to you 🆘🚨

$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:29:36 </td>
   <td style="text-align:left;"> $TSLA for planning purposes. 🫦 
 
[weekly candles, MAs]. 
 
🎩 
🙌🏻 
 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:29:22 </td>
   <td style="text-align:left;"> $QQQ losing my god damn mind with this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:29:14 </td>
   <td style="text-align:left;"> $QQQ https://www.stockilluminati.com/qqq/news.php - Bull Market Or Bull Trap? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:29:03 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $DJIA S&amp;amp;P 500 notches highest close for 2023 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:28:43 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA What a corrupt, POS country this has become at the hands of scumbag Democrats, liberals, Deep State rats, and D.C. careerists.  Selective application of the &amp;quot;law&amp;quot; and &amp;quot;unequitable&amp;quot; investigations.  Need a loose cannon of justice. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:27:46 </td>
   <td style="text-align:left;"> Lots and lots of gaps to fill up north.

$TSLA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:25:16 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ $SOXS &amp;quot;JP Morgan&amp;quot; is talking down markets, just as &amp;quot;Morgan Stanley&amp;quot; is. All about the disconnect beween the Bond&amp;amp; Equities. &amp;quot;If stock markets trade, as bond markets, the result will be -20%&amp;quot;. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:24:36 </td>
   <td style="text-align:left;"> This shows the monthly results from only making a trade when H% is low.
Whats the Win/Lose ratio? The result speaks for itself.

May (&amp;#39;23) = 0 loss
April (&amp;#39;23) = 0 loss
March (&amp;#39;23) = 1 loss
February (&amp;#39;23) = 0 loss
January (&amp;#39;23) = 0 loss
December (&amp;#39;22) = 2 losses
November (&amp;#39;22) = 0 loss
October (&amp;#39;22) = 2 losses

Got timestamps for the skeptics
$SPY $QQQ $COST $TGT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:18:21 </td>
   <td style="text-align:left;"> Let’s party 🎊 🎉  I just read the recession is not coming and the bull market just started.  I know a guy who told me that 9 months ago.  Everyone needs that guy in their life. You got a guy? I got a guy.  $QQQ $CVNA $RMBS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:17:28 </td>
   <td style="text-align:left;"> $QQQ cmon Jpowell you rat dog I expect 355 today minimum </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:17:19 </td>
   <td style="text-align:left;"> $SPY $QQQ also low volume Friday.  I guess  it will depend if Tesla keeps pumping or dumps at open. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:17:04 </td>
   <td style="text-align:left;"> $QQQ EVERY FUCKING DAY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:15:34 </td>
   <td style="text-align:left;"> $QQQ so why the pump now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:10:47 </td>
   <td style="text-align:left;"> $QQQ I’m so sick of this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:09:04 </td>
   <td style="text-align:left;"> I have a scary joke about math, but I&amp;#39;m 2² to say it...

$spy $qqq $uvxy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:06:29 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $MSFT 
 
Nasdaq GRINDS HIGHER after HIGHER than expected JOBLESS CLAIMS 
https://youtu.be/AJOkNnfNl-4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:06:20 </td>
   <td style="text-align:left;"> $QQQ  Would like to see the trend continue here and a retest to 356-357 supply. Yesterday we revisited the demand area of 346.5-348 and followed with strong technical bounce. Look for a break above 353.75 for confirmation back into supply area. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:05:11 </td>
   <td style="text-align:left;"> Wall Street economists are increasingly less worried about a 2023 recession

https://finance.yahoo.com/news/wall-street-economists-are-increasingly-less-worried-about-a-2023-recession-093041009.html

$QQQ $TQQQ $SQQQ $NQ_F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:04:09 </td>
   <td style="text-align:left;"> $QQQ real sentiment vs stocktwits </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:03:49 </td>
   <td style="text-align:left;"> @GraffGripANW @Rangebound500 at some point you might want to stop losing $$ and learning the truth. Most of that historical PE shit is zero math stupidity pushed from a world that is outdated. 
 
if you think about compounded assets being exponential why the hell are you using a random linear useless number that doesn&amp;#39;t even reflect cash or asset ratios. 
 
If you use 16 PE then at some point the stock market will be 10% of assets while cash/bonds are 90%. 
 
That statement is something no one wants to explain to you. The stupid world of finance uses outdated text books and still draws linear straight lines which is annoying/stupid to the mathematics world. 
 
simple truth, those who wait for 16 PE fail to compound any wealth, live in a broke world and celebrate market proving them right ONCE every 10 years over all. 
 
 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:02:45 </td>
   <td style="text-align:left;"> $QQQ so many cry baby bitches below , jobs are needed by these people </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 19:02:00 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ  
 
Only one door to escape out of when the alarm goes off. Hope you make it out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:50:27 </td>
   <td style="text-align:left;"> $AMZN MMs crunched the data and found retail holding too many naked calls above 120 $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:48:49 </td>
   <td style="text-align:left;"> $SPY $QQQ no relevant catalyst this morning. It seems that the indexes will be move by Tesla and other tech pumping.  Let’s see what WS has in agenda for today.  Good morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:44:34 </td>
   <td style="text-align:left;"> $AMZN amazon news? $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:39:15 </td>
   <td style="text-align:left;"> $SPY $QQQ not too shabby, son. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:36:51 </td>
   <td style="text-align:left;"> $QQQ After what you guys have spent in Ukraine that place better look like Japan </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:36:07 </td>
   <td style="text-align:left;"> $QQQ gotta tell you during all those presidential rallys those Ukraine cheers were surely the loudest.....Glad we could pull our gov together for the common cause of....focusing on Ukraine forever.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:35:29 </td>
   <td style="text-align:left;"> $QQQ % of Americans concerned with Ukraine......0% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:34:58 </td>
   <td style="text-align:left;"> $QQQ Could you imagine seeing 1 state&amp;#39;s name in the news as much as we&amp;#39;ve seen the word Ukraine? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:33:48 </td>
   <td style="text-align:left;"> $QQQ We are now the United States of Ukraine News. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:30:41 </td>
   <td style="text-align:left;"> $NIO $TSLA $QQQ $SPY  today , my cat Will most likley give birth to small ragdolls. 👍👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:27:52 </td>
   <td style="text-align:left;"> $QQQ : Looks bullish right, down it goes though. Just a temp pullback </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:23:53 </td>
   <td style="text-align:left;"> $QQQ Yesterday I caught on the news that most of you idiots are giving 20k away to nigerian scammers on Grindr....ya thats a common occurrence so says the news yesterday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:19:46 </td>
   <td style="text-align:left;"> Consumer confidence just tanks’ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:18:58 </td>
   <td style="text-align:left;"> $QQQ the way dems blackout the news channels with their daily dribble points is so awful.  Its like instagram news or something. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:14:46 </td>
   <td style="text-align:left;"> Sunday night Futures $3980’ $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:14:12 </td>
   <td style="text-align:left;"> Trade idea --&amp;gt; $LABD 
 
Multiple bottom setup, recently hitting $14+ and then retraced back down to the $12s. 
 
Two levels to watch for buyers to step back in are $12 &amp;amp; $11.60s, ideally, we take a position into the momentum (reversal) 
🎯 - $13+ once in position. 
 
🛑 Stop loss recommendation 5% max  
$SPY $QQQ $TSLA $AI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:14:08 </td>
   <td style="text-align:left;"> $QQQ Funny how crowded the board is with Bears early morning. Life must be too stressful to sleep! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:09:33 </td>
   <td style="text-align:left;"> $QQQ VIX? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:09:13 </td>
   <td style="text-align:left;"> $AGQ $DIA $QQQ $SMH Did you swing trade $AGQ? https://makecashwork.com/trading-leveraged-agq-how-to-lock-in-10-profits-in-just-10-days/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:08:19 </td>
   <td style="text-align:left;"> $SPY $QQQ telling people it’s climate change is getting old especially when you refuse to accept the rise in arson and crime. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 18:02:05 </td>
   <td style="text-align:left;"> $CVNA I have observed this board extensively over the last day and the general consensus of bulls here is that this should hit $50 today.

The delusion of grandeur is unmatched &amp;amp; uncanny. This amount of idiocracy has never been seen before with this many traders agreeing  in harmony on such an outlandish claim.

$QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:56:27 </td>
   <td style="text-align:left;"> $SPY finally a friday with 2% red $QQQ $TSLA $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:54:48 </td>
   <td style="text-align:left;"> Let&amp;#39;s play a game. Guess which ticker this is.

This is the play from yesterday. Alerted the near perfect level for a reversal trade. Just $0.03c from its absolute bottom of the day.
All possible from ONLY buying when H% is low. Look at the each steps shown.

$SPY $TSLA $AAPL $MSFT $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:52:31 </td>
   <td style="text-align:left;"> Dropping levels $SPY $NDX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:43:37 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ  high base </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:41:40 </td>
   <td style="text-align:left;"> Carry  sticking forks in $apple for profits, ditto $dis noise re #APPLEVISIONPRO re due diligence at must read @ https://link.cnbc.com/view/5b19cc6124c17c1ee97e3beeiw9qc.8gs/c938855b $dia $spy $qqq 🐻❤😈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:32:02 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA $IWMm All you need to know FAAANMG saving the markets! STRONG LONG FOMO alert is still elevated...WOW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:29:58 </td>
   <td style="text-align:left;"> Triple top??? $SPY $SPX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:23:22 </td>
   <td style="text-align:left;"> $SPY  $QQQ  if you didn’t start selling yet everything at the top and in middle of this koas your worst manipulating investor ever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:22:02 </td>
   <td style="text-align:left;"> $NVDA $SPY $QQQ $TSLA  I don’t think buy algos can read.  Software tricked into leaking data is bearish. Nvidia software is trashy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:20:56 </td>
   <td style="text-align:left;"> $SPY  can you imagine the whip say on the headlines that hasn’t started test and it’s been hours and there’s billions at stake $QQQ $NDX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:18:55 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA ROMAN REIGNS IS BORING THE BLOODLINE STORY IS DUMB HE NEEDS A STONE COLD STUNNER 🛶🛶🛶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:15:04 </td>
   <td style="text-align:left;"> $QQQ looking good today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:14:55 </td>
   <td style="text-align:left;"> $QQQ please pump into open and 10a come crashing down today... Short the world! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:13:03 </td>
   <td style="text-align:left;"> $SPY  Something manipulated Futures $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:11:27 </td>
   <td style="text-align:left;"> It’s very obvious to us all now the stock market is now manipulated by something. Not it’s clear and obvious $QQQ $SPY $DIA 

This should be down 5% over the day and it hasn’t moved .50’cents.  Pure manipulation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:09:37 </td>
   <td style="text-align:left;"> My provider gave me disney+ for a year for free, that ended a few months ago, rarely used it, not missed, unbelievable share price trades over 70$ 🐻❤😈 https://www.google.com/search?ie=UTF-8&amp;amp;client=tablet-android-samsung-rev2&amp;amp;source=android-browser&amp;amp;q=walt+disney+dis $dis ... $nflx $dia $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:06:42 </td>
   <td style="text-align:left;"> $SPY $QQQ What’s funny to me around this time of day, all the bulls and bears come make their predictions… officially you’ve got a 50/50 chance of being right, a little better if you’re paying attention. 

But somehow a majority are always wrong. 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:04:39 </td>
   <td style="text-align:left;"> limit down drop $SPY  $QQQ   Days on end </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 17:02:46 </td>
   <td style="text-align:left;"> $SPY should have a bullish day as the 430+ crowd grows. 

Meanwhile, back at Whacko Ranch where the guilty continue to get a great spin from Fox Fake News anchors, the Teflon frying pan is getting more pitted by the day and getting quite sticky in FLA.

OMG  had to laugh at Levins outcry last night.  That drama queen gets a 10! LOL You&amp;#39;d think that he lost his bed partner.

Oh the outrage displayed there.  We must respect the criminal actions that Trump owns. He made his bed and now he gets to lay in it peacefully as more details seal his fate. He should have kept his mouth shut.

Patience is so hard for so many. Doesn&amp;#39;t matter the venue. Justice is finally moving into 2nd gear.

Will markets care a wit?

Peace to all and have a great day!

$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:58:41 </td>
   <td style="text-align:left;"> $qqq check out NNOx.  AI company in MedTech.  Outperforming top AI players </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:56:00 </td>
   <td style="text-align:left;"> $QQQ: Both the short term and long term trends are positive. This is a very positive sign. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:54:34 </td>
   <td style="text-align:left;"> $QQQ No reason for this bullshit to be up again today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:47:17 </td>
   <td style="text-align:left;"> $SPY $QQQ a trillion planets and galaxies and we humans think we are the masters...LOL clowns we are just a spec...a tiny piece of molecules ..get ready they are coming.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:46:42 </td>
   <td style="text-align:left;"> This shows VISUALLY how I get a reversal trade 95%+ of the times while 90% of traders lose.
$FSR vs $SPY

This is why I ONLY buy when H% is low instead of buying random levels.
Algos are very complex, learn to buy when H% is low.

$QQQ $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:34:27 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:28:35 </td>
   <td style="text-align:left;"> Market Volume Barometer 6-08-2023 
Sentiment: LIMBO 
Volume: -16% 
Real Feel: CHILLY 
Cycle: BULLISH II 
Portfolio: LONG 
Next Day Move: SIDEWAYS 
&amp;gt;&amp;gt;For the full description, follow this link&amp;gt;&amp;gt;https://mytradinglicks.com/market-volume-barometer/ 
$SPY $SPX $QQQ $DJIA $IWM #MarketVolumeBarometer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:27:08 </td>
   <td style="text-align:left;"> $AAPL $SPYD $QQQ $NVDA $IWM Inspite of the hype and exaggeration, markets are headed lower on &amp;quot;Hard Landing&amp;quot;. Do remember, the &amp;quot;shit hitting the fan&amp;quot; will be sudden and the draw down will be fast. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:22:34 </td>
   <td style="text-align:left;"> $COIN woooooooooooooooow 
RED for the futures $SPY $QQQ. Let&amp;#39;s see $BTC.X in the morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:21:19 </td>
   <td style="text-align:left;"> $QQQ please for the love of god leave all those bulls trapped now and dump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:18:56 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $TSLA

Markets don&amp;#39;t run on technicals.. They run on greed, fear, fomo, algos, and keywords. If you haven&amp;#39;t heard the news lately apparently aliens are coming to Earth for AI 😆 🤖 👽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:16:59 </td>
   <td style="text-align:left;"> $SPY $QQQ Come on! KEEP BUYING!!! 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:14:26 </td>
   <td style="text-align:left;"> $SPY $QQQ to many bears flipping to BULLSIDE FOMO --maybe a big BULLTRAP setup is happening? Markets may flip back to bear side soon LOL ---Market is messed up :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:10:37 </td>
   <td style="text-align:left;"> $SPY $QQQ Lots of positive news today $CS makes a deal, $tsla GM charge deal, NVDA 1000 and still going strong --- FAAANMMG -- severe fomo people missed the bottom LOL --and VIX got destroyed :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:09:49 </td>
   <td style="text-align:left;"> $AZN AstraZeneca signs $2 billion agreement with Quell to develop cell therapies. $SPY $QQQ. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:08:35 </td>
   <td style="text-align:left;"> $VIX $SPY $QQQ $DJIA 

Soon the vix will be at 18-19 and stocks will go much lower. Make sure you’re all vaccinated </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:08:29 </td>
   <td style="text-align:left;"> $SPY $QQQ Seriously I need to take out all of the payday loans and go all in on futes because this 4am pump is as certain as a sunrise. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:06:30 </td>
   <td style="text-align:left;"> $QQQ DisruptiveTechnology just on here talking to themselves hyping themselves up spamming bullish jargin for an hour lol no actual analytics or anything just word vomit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:02:59 </td>
   <td style="text-align:left;"> $SPY $qqqq Shortie massacre Friday --RIP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 16:00:04 </td>
   <td style="text-align:left;"> $SPY $QQQ V shape intact, and severe FOMO from Institutions alert elevated ... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 15:58:16 </td>
   <td style="text-align:left;"> $SPY $QQQ Who held their short position overnight oh boy..its going to be another bloodbath , short squeeze, margin calls..OH NO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 15:55:53 </td>
   <td style="text-align:left;"> $SPY $QQQ Lots of BEAR flipping to BULL Side -- time short soon :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 15:50:51 </td>
   <td style="text-align:left;"> $SPY $VIX $QQQ scam market! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 15:47:44 </td>
   <td style="text-align:left;"> $SPY $QQQ Short to medium BULLISH EVENT too strong ..not many bears left they flipping to FOMO .oh boy .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 15:47:23 </td>
   <td style="text-align:left;"> $SPY $DWAC $QQQ - Q the “that’s not happening” 😵‍💫 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 15:46:29 </td>
   <td style="text-align:left;"> $SPY $QQQ all you need to know been holding V since Oct 2022 bottom..bears look silly ..yes that is how long they been pounding bearish sentiment..EPIC FAIL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 15:44:54 </td>
   <td style="text-align:left;"> $SPY $QQQ Looks like another BEAR TRAP ..LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 15:39:38 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $MSFT 
 
Nasdaq GRINDS HIGHER after HIGHER than expected JOBLESS CLAIMS 
https://youtu.be/AJOkNnfNl-4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 15:33:31 </td>
   <td style="text-align:left;"> $SPY $QQQ Recession, rates hike, still paused...for now..shorten..make money till the drop ..easy peasy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 15:28:09 </td>
   <td style="text-align:left;"> $SPY $QQQ  let&amp;#39;s build some Forrest fire bots ..thanks https://www.youtube.com/watch?v=W5ugoiHDaOA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 15:27:47 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA  $NVDA $AMZN

Stock futures slip Thursday night after S&amp;amp;P 500 notches highest close for 2023 https://www.cnbc.com/2023/06/08/stock-market-today-live-updates.html?__source=iosappshare%7Ccom.apple.UIKit.activity.CopyToPasteboard

Remember, the FEDs not saving the day this time, their objective is lowering inflation. QT continues, and retail pays for the bag. The FED is such a scam. And Joe sucks so bad as president! He can’t even stand or walk!   #America #Crumbling #SAD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 15:22:53 </td>
   <td style="text-align:left;"> $SPY $QQQ ... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 15:20:34 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 15:14:00 </td>
   <td style="text-align:left;"> $AMD $QQQ This a millennial memester stock worse than GME and AMC.  Your uniform is ready for pickup losers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 15:08:07 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA SEE THEM INDICTMENTS 🛶🛶🛶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 15:06:43 </td>
   <td style="text-align:left;"> 20 mins YouTube Stock Market Technical Analysis:                                              
https://youtu.be/R_76OIZzEzU 
Subscribe on YouTube for daily market updates &amp;amp; plays 
 
- Tesla Stock TSLA CLEAR 12 EMA 4 hour time frame support guide 
- Nvidia Stock NVDA falling Wedge Guide 
- google Stock GOOGL Lead Bear of big tech bull break with no follow through on Monday 
- Amazon Stock AMZN potential setting a lower high on daily 
- Apple Stock AAPL stronger big tech 2 day time frame EMA 12 perfect support guide 
$SPY $QQQ $SPX $IWM $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 15:05:13 </td>
   <td style="text-align:left;"> $QQQ Lock up Trump now dirtiest stupid President this country ever had. Only white trash support him </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 14:33:48 </td>
   <td style="text-align:left;"> $AAPL $NVDA $QQQ i&amp;#39;m in tech and don&amp;#39;t believe a word these companies are saying. 
 
Y2K all over again. 
 
RIP Google Glass AI 2.0. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 14:29:25 </td>
   <td style="text-align:left;"> $QQQ great day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 14:19:00 </td>
   <td style="text-align:left;"> $QQQ  hey GO FUCK 🖕🏻🖕🏻🖕🏻🤡🤡🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 14:13:54 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA THE ALIENS STOPPED IN VEGAS BECAUSE THEY WANTED TO GAMBLE DUH WINNING 🛶🛶🛶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 14:08:12 </td>
   <td style="text-align:left;"> $QQQ crazy how the dollar is even holding up even after everybody talking about 3% being the new inflation target, soon itll be 4% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 14:06:35 </td>
   <td style="text-align:left;"> Let&amp;#39;s play a game. Guess which ticker this is.

This is the play from yesterday. Alerted the near perfect level for a reversal trade. Just $0.03c from its absolute bottom of the day.
All possible from ONLY buying when H% is low. Look at the each steps shown.

$SPY $TSLA $AAPL $MSFT $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 14:00:42 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $NVDA $TSLA 

How tf is NQ1 already up 1.20% since last closing?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 13:58:44 </td>
   <td style="text-align:left;"> This shows VISUALLY how I get a reversal trade 95%+ of the times while many traders lose. 
$PARA vs $SPY is one example of many.

This visually shows why I ONLY buy when H% is low instead of buying random levels.
Algos are very complex, learn to buy when H% is low.

$QQQ $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 13:57:24 </td>
   <td style="text-align:left;"> $QQQ $TQQQ $SQQQ I’ve been monitoring the AAII weekly survey for years. Sentiment shifts like this do not occur often.

The narrative that the market is too bearish is behind us for now… which from a positioning standpoint can be contrarian, but also means there is a lot of money that can enter the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 13:51:34 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X mark this post kids 
the yen crashes soon, or we do 🤷‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 13:47:35 </td>
   <td style="text-align:left;"> $SPY $QQQ lolllllllllll 

https://www.espn.com/nfl/story/_/id/37821339/garett-bolles-russell-wilson-critics-eat-crow-2023 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 13:38:39 </td>
   <td style="text-align:left;"> $QQQ https://www.stockilluminati.com/qqq/news.php - U.S. Weekly FundFlows Insight Report: Conventional Investment Grade Funds Attract Largest Weekly Inflow Of 2023 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 13:32:03 </td>
   <td style="text-align:left;"> $SPY $QQQ In retaliation for Jabba indictment Repubes vow to boycott Congressional Softball game?

They should the outraged yet it is crickets from the spineless poofdas </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 13:24:29 </td>
   <td style="text-align:left;"> $QQQ please go 357 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 13:21:48 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $MSFT 
 
Nasdaq GRINDS HIGHER after HIGHER than expected JOBLESS CLAIMS 
https://youtu.be/AJOkNnfNl-4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 13:19:28 </td>
   <td style="text-align:left;"> $SPY $QQQ $TQQQ $IMW Biden found to have accepted over 10m from foreign entities in exchange for policy changes. Time to indict Trump, light the fires, talk about aliens.... Its getting old. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 13:13:05 </td>
   <td style="text-align:left;"> $SPY $DWAC $QQQ - and these low iq chit heads still have the nerve to criticize Trump - talk about being in a GAY cult </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 13:12:39 </td>
   <td style="text-align:left;"> $SPY $QQQ Bear market canceled </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 13:10:07 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ - why ? 🤔🤷‍♂️ I thought they like making loans </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 13:08:01 </td>
   <td style="text-align:left;"> $SPY $QQQ $TLT $TMF $USO 
 
China&amp;#39;s Producer Price index just came in at -4.6% for May, beating -4.3% expectations. This type of price deflation by manufacturers is not what commodity/oil bulls and China reopening bulls want to see. 
 
But it should be good for lower US inflation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:59:28 </td>
   <td style="text-align:left;"> $SPY $QQQ Zimbabwe, NoKorea, and Venezuela look like they have more legitimate/truthful Govts than the Current USSA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:50:00 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X MMs the next few weeks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:47:26 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ 🔴 Market Parties like it&amp;#39;s 2008 |  A little late tonight but I had a friend pop by | That big resistance is in sight... I can&amp;#39;t wait 🤭  
 
https://youtu.be/eedLQwPdRmE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:47:26 </td>
   <td style="text-align:left;"> $QQQ 
 
Interesting selloff with google yesterday. Didn’t break big bear level under 346.7 and now semi bullish over the 200EMA. If 355 breaks tomorrow will long towards 358-360 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:45:45 </td>
   <td style="text-align:left;"> Daily Watchlist!

$SPY $TSLA $QQQ $NVDA $BA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:39:40 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ - a few moments later …. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:37:16 </td>
   <td style="text-align:left;"> $QQQ https://www.stockilluminati.com/qqq/news.php - Anatomy Of A Recession Update: U.S. Labor Market Cracks Emerging? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:36:41 </td>
   <td style="text-align:left;"> $QQQ bye felicia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:31:06 </td>
   <td style="text-align:left;"> $SPY $DWAC $QQQ - I’m fucking dying 😂😂😂 - I identify as trans late ⏰ that is someone who is late but identifies as on time . 

https://twitter.com/cadence4trump/status/1666467526216417280?s=46&amp;amp;t=A6mr-JsI6_Tnk3qqOvXORQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:20:44 </td>
   <td style="text-align:left;"> $AAPL the company that thinks people are going to pay $3500 to walk around town with VR headsets on is carrying the whole market.

They have jumped the shark. Cash out.

$QQQ $NVDA 

Collapse is inevitable. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:19:33 </td>
   <td style="text-align:left;"> $SPY $QQQ futes fuckin rippin. Told you. Did you listen? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:16:16 </td>
   <td style="text-align:left;"> $SPY $QQQ the most prosperous country in the world has not started talking about aliens in the White House and the main stream media. Where did things go wrong? Genz is screwed… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:15:07 </td>
   <td style="text-align:left;"> $NIO $QQQ Pre~market updates. NIO. https://pre-market-updates-analysis.blogspot.com/2023/06/nio-and-qqq-updates.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:13:51 </td>
   <td style="text-align:left;"> $SPY  $qqq  just when were making progress against the trans lgbtq crowd Garth Brooks comes out as pro woke and pro bud light </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:12:29 </td>
   <td style="text-align:left;"> ETF Sentiment: $QQQ is the #2 ETF that institutions are trading with 282.9K options contracts.

Market analysis included in screenshot of dashboard from 🔥 INSIDERFINANCE.IO 🔥 (Link in profile - @InsiderFinance) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:12:14 </td>
   <td style="text-align:left;"> $SPY  $qqq makes me wonder if cramer knows about cash or money markets..  theres such a thing as NOT being in stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:12:11 </td>
   <td style="text-align:left;"> $spy $qqq $tsla

so buffett says there are gonna be amazing investment opportunities due to folks doing stupid things with their money. did he mean because they aren’t buying calls or not holding enough cash / preserving capital? hard to tell haha. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:05:52 </td>
   <td style="text-align:left;"> $TSLA “GM and Ford supercharging network” 🤣 $SPY $QQQ https://twitter.com/squawksquare/status/1666933564263333889?s=12&amp;amp;t=bB0_ZKAEkBmXPJsLYmyBtQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:05:45 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $META $NVDA 

OI at close today - way too many calls 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:04:46 </td>
   <td style="text-align:left;"> $QQQ https://www.stockilluminati.com/qqq/news.php - U.S. Household Wealth Rose $3tn In The First Quarter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 12:03:41 </td>
   <td style="text-align:left;"> $NQ_F $QQQ Ehaustion price pattern (red dot) pre-market yesterday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:58:23 </td>
   <td style="text-align:left;"> $TSLA fought “the left” and lost NPR on Twitter $SPY $QQQ https://twitter.com/npr/status/1646138100035272704?s=12&amp;amp;t=bB0_ZKAEkBmXPJsLYmyBtQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:56:34 </td>
   <td style="text-align:left;"> $QQQ $SPY https://thehill.com/policy/defense/4041030-taiwan-air-defenses-activated-chinese-military-aircraft/amp/ 
 
 
Every day I read articles like this. Something is going on between these 2 countries that can’t be ignored. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:56:20 </td>
   <td style="text-align:left;"> $TSLA desperate call and make Twitter cash flow positive… maybe just thinking to pump and dump more Tesla shares? $SPY $QQQ https://twitter.com/elonmusk/status/1666945495334256642?s=12&amp;amp;t=bB0_ZKAEkBmXPJsLYmyBtQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:55:36 </td>
   <td style="text-align:left;"> Let&amp;#39;s play a game. Guess which ticker this is.

This is the play from today. Alerted the near perfect buys for a reversal trade.
All possible from ONLY buying when H% is low. Look at the each steps shown.

$SPY $TSLA $AAPL $MSFT $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:53:18 </td>
   <td style="text-align:left;"> $SPY $QQQ from ABC news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:53:00 </td>
   <td style="text-align:left;"> $QQQ is currently trading near its 52 week high, which is a good sign. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:52:33 </td>
   <td style="text-align:left;"> $QQQ futes up bigly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:51:53 </td>
   <td style="text-align:left;"> $QQQ yes futes green! Nothing to see here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:47:02 </td>
   <td style="text-align:left;"> $SPY Losten, I just need the $QQQ to hit 359, which is six more than we have now. And if it doesn&amp;#39;t, there&amp;#39;s nothing wrong with recalculating it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:44:40 </td>
   <td style="text-align:left;"> $QQQ There&amp;#39;s still one more leg higher. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:44:18 </td>
   <td style="text-align:left;"> $BTC.X WE ARE ENTERING AN UNPRECEDENTED DEBT CRISIS! | RAY DALIO
https://youtube.com/shorts/L2aHgyw5q78?feature=share
$SPY $QQQ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:42:43 </td>
   <td style="text-align:left;"> $QQQ 359 tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:32:17 </td>
   <td style="text-align:left;"> @mikesmic @sizzlemytits @HugZnotDrugZz not sure about that kind of gorilla math, but $TQQQ puts are going to light up like the 4th. I’m in for Sept and will load on Dec if $QQQ moves up in July. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:27:27 </td>
   <td style="text-align:left;"> $SPY $qqq  coffee means nothing oil and copper say it all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:25:09 </td>
   <td style="text-align:left;"> $SPY  $qqq you would think CNN would try to lie better than calling the start of a new bull market the day before a recession collapse happens .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:20:22 </td>
   <td style="text-align:left;"> $DWAC $QQQ $SPY $TSLA Whoa good one I&amp;#39;m laughing so hard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:17:54 </td>
   <td style="text-align:left;"> $DWAC Obese Orange needs to inquire about toupees available in the slammer $SPY $TSLA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:17:42 </td>
   <td style="text-align:left;"> $SPY  $QQQ   happy YahWeh Month . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:17:00 </td>
   <td style="text-align:left;"> $SPY next week is going to be something else. With a Market overvalued on Hype &amp;amp; now at the top we have the Fed, Treasury &amp;amp; now a bunch of poorly educated cult members looking to act up so,.. Where was the VIX? where was the hedges?,... they&amp;#39;re coming! :o) 
 
$aapl $qqq $tsla $nvda </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:16:25 </td>
   <td style="text-align:left;"> Looks like we want to further squeeze shorts and reach all time highs. We are not out of the woods yet tho! $SPY $QQQ $AAPL  https://www.youtube.com/watch?v=P5mgvlo_Xdc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:15:18 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA 

What the frack, there’s an actual ticker called $MOON 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2023-06-09 11:13:52 </td>
   <td style="text-align:left;"> $SPY $QQQ

change the ticker $TSLA to $MOON </td>
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
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:51:08 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Meta CEO Mark Zuckerberg takes a dig at Apple&amp;#39;s &amp;#39;Vision Pro&amp;#39; https://www.stck.pro/news/AAPL/52527573/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:50:04 </td>
   <td style="text-align:left;"> $AAPL never really caught a perfect trade but manage to buy a few bucks worth at 134 and riding this up feels good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:48:01 </td>
   <td style="text-align:left;"> $NASDAQ $NQ_F $SPY Disgusting Democrats $UVXY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:46:38 </td>
   <td style="text-align:left;"> $PYPL latex46ff6cc93bdb3baac4507bed675b24d8AMZN could be interested in this loser company if their smart management team can tinker with this broken company to merge into Amazon Pay 
 
$JPM could be another potential buyer if they want to speed up fintech business development at a cheap price </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:41:47 </td>
   <td style="text-align:left;"> $AAPL $SPY $TSLA  
👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:40:43 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:38:46 </td>
   <td style="text-align:left;"> $PLTR Keith said he is leaving his Palantir shares to his kids!!!  Growth is never going to stop!  Top right of pic… 
 
excellent vid on life 
 
“$msft $amzn $tsla $aapl of our time!!!!” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:33:15 </td>
   <td style="text-align:left;"> $AAPL apple vision pro is epic!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:24:28 </td>
   <td style="text-align:left;"> “$PLTR is like $msft $amzn $tsla $aapl”  This is the second time he has said this!!  24 minute mark of vid!!! 
 
https://m.youtube.com/watch?v=Sb-OKbOSUNw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:23:44 </td>
   <td style="text-align:left;"> $SPY I don’t know who needs to hear this but the last time SPY was at $429 it sold off to $356  
 
$AAPL $TSLA $GOOGL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:21:55 </td>
   <td style="text-align:left;"> $UPST why people are bullish on any other companies other than $TSLA $AAPL $MSFT is beyond me. Companies like upstart will NOT be around. UPST will likely see sub 30 tomorrow morning. After that, who knows. Long term, it won&amp;#39;t be around. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:20:18 </td>
   <td style="text-align:left;"> $AAPL Stocktwits is one of the great SPAM operations of all time. Ads plastered everywhere, feeds filled with ads, pop up ads on the right, now pop up ads in the center on top of the feeds... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:17:56 </td>
   <td style="text-align:left;"> $AAPL https://appleinsider.com/articles/23/06/08/apple-wants-to-build-324000-square-feet-of-office-space-in-north-carolina </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:17:52 </td>
   <td style="text-align:left;"> $spy $qqq $aapl $tsla 

well said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:15:16 </td>
   <td style="text-align:left;"> $IMMR Pump:  Google Apple $AAPL immersion technology </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:13:46 </td>
   <td style="text-align:left;"> $AHI https://www.ahi.tech/products/facescan prob $AAPL buyout, FaceScan aligns exactly with their new Vision Pro headset, just like a few days ago they purchased Mira which does AR — Apple doesn&amp;#39;t need to hide in the shadows anymore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:13:24 </td>
   <td style="text-align:left;"> $MVIS $MSFT $AAPL 

Hey MicroVision Fams, Good news !!!!

Soon you&amp;#39;ll have an actual excuse instead of fantasies for why Microsoft stopped shipping MicroVision&amp;#39;s ancient tech. After June, it&amp;#39;s only been 12 months 😂

Still waiting for an excuse as to why you bagholders claim MicroVision&amp;#39;s components are so valuable to Microsoft yet you&amp;#39;re praying they have an opportunity to continue their worthless contract with them....

TLDR: If your product is in demand, you charge for it. NOT hope you can continue giving it away for nothing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:13:24 </td>
   <td style="text-align:left;"> @Benzikamg Any guy who spends their time tolling LGBTQ issues is def Gay 
 
$Bud $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:12:53 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:12:31 </td>
   <td style="text-align:left;"> $AAPL $SPY $VIX Don&amp;#39;t get me wrong. I understand why the market is rallying. I also understand why it shouldn&amp;#39;t be rallying. Good portion of liquidity is entering over levered and high risk portions of the market.  
 
Vegas always has its best year, just before and during a crash and as far as I can see, this entire market acting like a slot machine. smh.  
 
We are playing with peoples pensions and people yelling BEAR SUCKS while they cant just walk away. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:11:42 </td>
   <td style="text-align:left;"> $PLTR must see TV!!! ”There is only one $tsla!  There is only one $aapl.  There is only one Palantir!“  The real ai Backbone! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:10:44 </td>
   <td style="text-align:left;"> This shows VISUALLY how I get a reversal trade 95%+ of the times while 90% of traders lose.
$FSR vs $SPY

This is why I ONLY buy when H% is low instead of buying random levels.
Algos are very complex, learn to buy when H% is low.

$QQQ $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:10:04 </td>
   <td style="text-align:left;"> $TSLA ripping 🦬

$AI $PLTR $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:08:41 </td>
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
   <td style="text-align:left;"> 2023-06-09 05:07:13 </td>
   <td style="text-align:left;"> $AAPL  what is a price target to short this stock? , I’m guessing $205 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:06:13 </td>
   <td style="text-align:left;"> $AAPL closing at 180….. 

Tim Cook got them fat nutzzzzzz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:05:29 </td>
   <td style="text-align:left;"> $U $AAPL  What more do you need to know </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:02:59 </td>
   <td style="text-align:left;"> $AAPL this graph show the market for 3500 usd VR goggles </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:02:38 </td>
   <td style="text-align:left;"> $AAPL June 8th 2022, two day period gapped down 11$. Cmon bro, u don&amp;#39;t think im being literally do you.  
 
Look at the number. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 05:01:35 </td>
   <td style="text-align:left;"> $TSLA Zuckerberg scared of $AAPL VisionPro. A Steve Ballmer moment for 
$META </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:57:42 </td>
   <td style="text-align:left;"> $aapl added—200+ by soy https://www.youtube.com/live/IULKDv1IaDY?feature=share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:56:40 </td>
   <td style="text-align:left;"> Let&amp;#39;s play a game. Guess which ticker this is.

This is the play from today. Alerted the near perfect buys for a reversal trade.
All possible from ONLY buying when H% is low. Look at the each steps shown.

$SPY $TSLA $AAPL $MSFT $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:56:16 </td>
   <td style="text-align:left;"> $AAPL 
Year to Date up 38.97%!!!
Why would anybody Short this stock? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:55:46 </td>
   <td style="text-align:left;"> $AAPL . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:55:21 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:52:39 </td>
   <td style="text-align:left;"> $BABA most undervalued stock in the entire market … from all US traded stocks cash balances , this has the 4th highest amount of cash at $75 billion. Only $AAPL $MSFT and $GOOGL have more. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:51:14 </td>
   <td style="text-align:left;"> $AAPL  I dare you to find the last time apple went down $11 in a day...I promise you it will be much much tougher than you think. This stock is not volatile so unless there is something you know is happening tomorrow (which you don&amp;#39;t), it is not dropping that low. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:50:25 </td>
   <td style="text-align:left;"> $AAPL  it dumped on day of WWDC but now it looks like it&amp;#39;s going back to it&amp;#39;s ATH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:50:18 </td>
   <td style="text-align:left;"> latex1a2f5dba1fdbf94ceb21bae9b6d20c54AAPL apple is in that same boat 

$SPY $MSFT $JPM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:35:10 </td>
   <td style="text-align:left;"> $AAPL doesn&amp;#39;t this usually dump after wwdc? Also could AAPL realistically buy out DIS like people have been speculating? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:34:49 </td>
   <td style="text-align:left;"> $AAPL Tesla raising the market tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:32:51 </td>
   <td style="text-align:left;"> $AAPL Friday profit taking sell off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:30:59 </td>
   <td style="text-align:left;"> $AAPL  169 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:30:17 </td>
   <td style="text-align:left;"> $NVDA $AAPL just curious what approximate Year we are expecting these companies to grow to their current valuations? 

2030? 2050? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:29:46 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $MSFT 
 
Stock Market Update: Nasdaq GRINDS HIGHER after HIGHER than expected JOBLESS CLAIMS 
https://youtu.be/AJOkNnfNl-4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:28:06 </td>
   <td style="text-align:left;"> $AAPL bears desperate we talking about 50 cents lol 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:27:20 </td>
   <td style="text-align:left;"> $AAPL over 181 you’re dead if you’re short. 177 held three times means support </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:27:01 </td>
   <td style="text-align:left;"> $LCID Lucid should open factory in China to reduce cost. That’s how $AAPL is making shit load of profit on IPhone. Lucid can succeed just like $tsla if management can execute well. Tesla turned profitable only after they started operating in China. 

Lucid has best EV technology, longest and fastest car in the world. Execute well and you see sky is the limit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:26:16 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $AAPL is the #2 stock that institutions are trading over rolling 5 day window with 588.2K options contracts.

Market analysis included in screenshot of dashboard from 🔥 INSIDERFINANCE.IO 🔥 (Link in profile - @InsiderFinance) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:23:09 </td>
   <td style="text-align:left;"> $AAPL $177 held three times. Will break below tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:22:44 </td>
   <td style="text-align:left;"> This shows VISUALLY how I get a reversal trade 95%+ of the times while many traders lose. 
$PLUG vs $SPY is one example of many.

This visually shows why I ONLY buy when H% is low instead of buying random levels.
Algos are very complex, learn to buy when H% is low.

$QQQ $TSLA latexd486ad33e33c13d4bb3516bfcf8195deAAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:21:47 </td>
   <td style="text-align:left;"> These salty ass MFs are mad. Sound like unhinged little girls. 😂

$TSLA $NVDA $AAPL $SOFI $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:20:55 </td>
   <td style="text-align:left;"> $AAPL $AMZN $NVDA $AMD $TSLA almost time for a new bear market already! 
Wow, time flies  😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:19:58 </td>
   <td style="text-align:left;"> $AAPL Ba Zinggggg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:19:50 </td>
   <td style="text-align:left;"> $AAPL love this stock. Crazy how anyone can bet against it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:18:19 </td>
   <td style="text-align:left;"> $SPY $AAPL hard to believe $3500 for some pair of goggles. Apple running out of ideas? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:17:26 </td>
   <td style="text-align:left;"> THE BEAR MARKET IS OVER ❗❗❗👇
A NEW BULL MARKET HAS STARTED 📈🐃

It&amp;#39;s official.  A new bull market is confirmed.🐃

The S&amp;amp;P 500 is now up 20% from its 10/12/22 closing low.  The prior bear market saw the index fall 25.4% over 282 days.📈

Note that the 2022 bear that lasted 282 days was basically right in-line with the average bear market length of 286 days🏔
$TSLA $AAPL $AMZN $NVDA $AMD  SBBDBDBD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:16:23 </td>
   <td style="text-align:left;"> $AAPL below 180 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:15:42 </td>
   <td style="text-align:left;"> $DOCU be 600 in a few years easy LONG get it while it&amp;#39;s cheap....there SUBs are way more  cheaper then $MSFT and $AAPL  these guys are in a great niche market share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:15:15 </td>
   <td style="text-align:left;"> $AAPL gap up 182 tomorrow 🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:15:15 </td>
   <td style="text-align:left;"> $TSLA RSI over 91, but it could go up to 95 history repeating right now. News about Cybertruck estimates 375k per year.
It&amp;#39;s heading over $255 very soon. I just rolled over my call $235 to latexfcbaba73a5f3cf58ce760b0049257eddAAPL Reclaim ATH tomorrow very good chance if makert help.
$AVGO $ADBE Jump back in with some July Call option on opening. I&amp;#39;m just gonna let it run. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:13:15 </td>
   <td style="text-align:left;"> $AAPL How likely will this gap up tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:13:15 </td>
   <td style="text-align:left;"> $AAPL So many bears making fun of Vision don’t even understand the space

This can be big </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:06:34 </td>
   <td style="text-align:left;"> Love how analyst are speaking market doom and gloom while their hedge funds keep loading. $SPY $TSLA $NVDA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:05:58 </td>
   <td style="text-align:left;"> $AAPL A blood bath sure would be fun tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 04:03:35 </td>
   <td style="text-align:left;"> $MULN i dont think u people appreciate my honesty and predictions for tomorrow.  Eventhough i been 100% right.  So i will refrain. But go ahead and keep buying 100k to 200k shares at $1 . Eventhough i said to you why buy? If you could wait under .50. Oh well. 
$SPY $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:58:17 </td>
   <td style="text-align:left;"> $AAPL everytime this hits 180 kerplunk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:58:01 </td>
   <td style="text-align:left;"> @SamuelB747 $AAPL introduced the same feature on Tuesday, makes $DOCU obsolete. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:57:28 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:55:39 </td>
   <td style="text-align:left;"> $AAPL it has been a wonderful day today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:54:49 </td>
   <td style="text-align:left;"> $AAPL bought June 9 $177.5 put </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:54:21 </td>
   <td style="text-align:left;"> $AAPL Next week I will be telling bears I told you so </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:54:08 </td>
   <td style="text-align:left;"> $SPY this is why they say you can’t time the market . People expected a pullback .. so some probably sold to try and get back n cheaper .. now they will have to buy back higher $TSLA $AMAZ $AAPL or wait for awhile </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:53:56 </td>
   <td style="text-align:left;"> $AAPL lmfao 🤣 🤣🤣🤣🤣🤣‼️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:53:42 </td>
   <td style="text-align:left;"> $AAPL 

Gap up tomorrow… sleep well shorties 😬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:52:21 </td>
   <td style="text-align:left;"> $AAPL Like I said, Apple going to break 6 T in short term. Forget valuation. This is frenzy.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:52:00 </td>
   <td style="text-align:left;"> $AAPL: The long and short term trends are both positive. This is looking good! https://www.chartmill.com/stock/quote/AAPL/technical-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:51:23 </td>
   <td style="text-align:left;"> $AAPL Who’s selling the $182.5 call for tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:50:42 </td>
   <td style="text-align:left;"> Dumbonomists don&amp;#39;t think ... they jawbone  ... https://www.marketwatch.com/story/fed-might-hike-interest-rates-again-in-june-instead-of-a-skip-some-economists-think-a3c230bd  ... rest assured higher interest rates incoming  ... enjoy the Autogeddon Armageddon Recession long lasting  ... $aapl $msft $amzn $meta $dis and more 🐻❤😈🤑💲💰✔ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:50:25 </td>
   <td style="text-align:left;"> $AAPL A welcome relief after yesterday&amp;#39;s nonsense. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:48:34 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Run away from AAPL, NVDA and the entire tech sector as fast as you can and start buying gold - The High-Tech Strategist&amp;#39;s Fred Hickey https://www.stck.pro/news/AAPL/52518652/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:47:42 </td>
   <td style="text-align:left;"> $AAPL $SPY $TSLA $QQQ lets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2023-06-09 03:47:32 </td>
   <td style="text-align:left;"> $SPY Trudeau still president ? 
Biden? 
Oh, wait, let me ask the latter after Tuesday Core CPI.

$QQQ $AMD $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:01:13 </td>
   <td style="text-align:left;"> $TSLA already reaching mars 🚀🚀🚀🚀. Time to take some off the table. Overbought.

Tesla Inc : Wedbush adds stock to its best ideas list 
Wedbush raises target price to $300 from $215 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:01:12 </td>
   <td style="text-align:left;"> $TSLA there cud be an insane gamma squeeze.  Call sellers r screwed up every week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:01:07 </td>
   <td style="text-align:left;"> $TSLA SOLID </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:00:59 </td>
   <td style="text-align:left;"> $TSLA wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:00:58 </td>
   <td style="text-align:left;"> $TSLA Bears waking up to the premarket pump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:00:58 </td>
   <td style="text-align:left;"> $DJIA $QQQ $SPY $TSLA who&amp;#39;s ready for another day of crooked Wall Street trading? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:00:48 </td>
   <td style="text-align:left;"> $HOOD $TGT $BUD $DIS $TSLA 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:00:45 </td>
   <td style="text-align:left;"> Home Advantage: How Domestic REE Supply Is Supercharging North American Companies $UCU.V $UURAF $TSLA $GE $GM $F https://ibn.fm/vgnBq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:00:41 </td>
   <td style="text-align:left;"> $BB $BB.CA : Good morning gang. What if Cathie Wood is right about $TSLA ? And what if JC is right about BB teaming up with Elon? JC has surrounded Tesla with QNX in Elon&amp;#39;s supply chains and IVY could be icing on the cake? Just my morning dream. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:00:39 </td>
   <td style="text-align:left;"> $TSLA LOD is $224 today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:00:37 </td>
   <td style="text-align:left;"> $AAPL $googl $amzn $tsla $bntx 
 
https://www.twitch.tv/videos/1841749838?t=00h00m05s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:00:37 </td>
   <td style="text-align:left;"> @comrade44 @aikitran shorts claimed feverishly $TSLA was heading to $70 not to long ago when it was trading in the lower 100’s. Why should we doubt them when they say $AI is going to $27 and $15? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:00:28 </td>
   <td style="text-align:left;"> $MDGS if the float is locked, next $TOP  or $HKD. In accumulation zone. $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:00:24 </td>
   <td style="text-align:left;"> $TSLA About to clear massive resistance. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:00:21 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA has joined the fun… now every Nasdaq stock has a parabolic chart. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 21:00:15 </td>
   <td style="text-align:left;"> $TSLA 

250C / 260C Lotto - bank off the momentum. 

Follow the flow, trade it and bank. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:59:53 </td>
   <td style="text-align:left;"> $TSLA please bears, please short … its RSI at blablsbla. What if i tell u 255 will be reached today??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:59:42 </td>
   <td style="text-align:left;"> $TSLA SO EXCITING !!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:59:41 </td>
   <td style="text-align:left;"> @Invested4Lyfe @FSRmoonster @Knightmoves2 @GuyLadoosh - I am going to pass on the unblock. He knows why I blocked him. I agree with many of the statements from others but I am not going to bad mouth anyone. I own several hundred thousand shares with a horrible $12.76 average plus the shares in my fund. It was a mistake and I regret it completely and in selling $TSLA because I believed in HF. His enthusiasm and charm is infectious when you meet him in person yet he can also be dangerous when it comes to predictions. A critical investor listens to both the bull and bear case and constantly asks himself “where have I gone wrong and where can I go wrong” with my thesis. I am still praying for a home run, but I can also see the holes in the story. Best of luck to all! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:59:41 </td>
   <td style="text-align:left;"> Pretty clear Institutional players are and have been propping markets with $NVDA, $TSLA, $NFLX, and latex3c01fd68880eaef15ab941304ca01c82TSLA - 6/16 on watch for a roll up
$NVDA - 6/16 400c over 395 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:59:27 </td>
   <td style="text-align:left;"> $TSLA Roasted Bear on the menu bois! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:59:15 </td>
   <td style="text-align:left;"> @LWRTSLA2901 what news source is that? this is from dowjones (a legit news source).

and if u combine marketcap increase on days of $f and $gm news with $tsla, tesla&amp;#39;s marketcap has increased over $70 billion on $1-$3 billion increase in annual revenue🤔🙄. this what I mean by the froth smh. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:59:12 </td>
   <td style="text-align:left;"> $SQQQ $TQQQ $NVDA $AMD $TSLA 

The biggest jump I’ve ever seen in bullish sentiment. 

Major contrarian signal. Bye bye bulls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:59:09 </td>
   <td style="text-align:left;"> @KnightKing they just cornered the charging market.  That’s like someone cornering the gas station market 50  years ago.  Insane! $tsla $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:59:07 </td>
   <td style="text-align:left;"> $TSLA  and 150 after 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:58:59 </td>
   <td style="text-align:left;"> $TSLA be funny if shorts pile in at open and this halts 10 times to 500 🤣🤷‍♂️could happen </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:58:58 </td>
   <td style="text-align:left;"> $TSLA Just like 2021, take advantage of the ridiculously inflated pumps. 2022 will be back around the corner to take all your shit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:58:52 </td>
   <td style="text-align:left;"> $TSLA $300 by earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:58:38 </td>
   <td style="text-align:left;"> Peak profit for the last 6 expired option alerts for $TSLA 214.95| 145.27| 14.41| 80.80| 115.00| 166.43| </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:58:36 </td>
   <td style="text-align:left;"> $TSLA shorts right now 😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:58:35 </td>
   <td style="text-align:left;"> $TSLA $WKHS $SNDL $LCID $ABML   WHAT DID I SAY. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:58:25 </td>
   <td style="text-align:left;"> $TSLA OMG she&amp;#39;s gonna blow. 😆 look at the volume already 😳 poo bears 🐻  lost their house 🏠 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:58:16 </td>
   <td style="text-align:left;"> $TSLA I told you...they left I stayed...who am I? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:58:08 </td>
   <td style="text-align:left;"> $TSLA Going to 300 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:58:01 </td>
   <td style="text-align:left;"> $TSLA  burn the shorts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:57:52 </td>
   <td style="text-align:left;"> $TSLA who else is up a bunch and gonna gamble $300 next weeklies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:57:48 </td>
   <td style="text-align:left;"> $TSLA this one for years has been 5 steps forward, 2 steps back, 5 steps forward, 2 steps back, repeat. And yet, shorts are still confident they have a winner. 🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:57:41 </td>
   <td style="text-align:left;"> HAMMER GOLD ❗❗❗
CANADA LOSES 17.3K JOBS IN MAY; UNEMPLOYMENT RISES TO 5.2% FROM 5.0%
$TSLA $AAPL $AMZN $NVDA $AMD  dbbs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:57:40 </td>
   <td style="text-align:left;"> $TSLA This is better then any MEME stock !! 
 
BUY AND HOLD !!! 
 
NEVER SELL !!! 
 
HIGHER AND HIGHER 
 
PASS IT ON !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:57:33 </td>
   <td style="text-align:left;"> $TSLA no bad news coming so just have at it lads! I wanna see 275 eod </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:57:10 </td>
   <td style="text-align:left;"> $TSLA be careful at these levels. It can easily go to $300 but it can easily go below $200 as well. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:57:01 </td>
   <td style="text-align:left;"> $TSLA great now we gotta watch this go alllll the way back to ATH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:56:52 </td>
   <td style="text-align:left;"> $TSLA $310 gap fill coming next week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:56:49 </td>
   <td style="text-align:left;"> $TSLA we will break 250 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:56:49 </td>
   <td style="text-align:left;"> $TSLA GM, Ford and soon the entire US EV industry will adopt Teslas North American Charging Standard ; this is much bigger than just allowing them to use Tesla Super charging network! Bears just don’t get it. 

https://en.m.wikipedia.org/wiki/North_American_Charging_Standard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:56:48 </td>
   <td style="text-align:left;"> $EPR How are you here? 
Thought we can go to $25+ (Covid&amp;#39;s lvls), and didn&amp;#39;t even try to buy at $33+ (bought $TSLA). I&amp;#39;m ok with that. But Dividends are Dividends. 
Love dividends ❤️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:56:38 </td>
   <td style="text-align:left;"> $TSLA $GM Tesla shares jump on EV charging tie-up with GM

https://www.reuters.com/business/autos-transportation/tesla-shares-jump-ev-charging-tie-up-with-gm-2023-06-09/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:56:36 </td>
   <td style="text-align:left;"> $TSLA Will we break 250 my Tesla kittens? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:56:36 </td>
   <td style="text-align:left;"> $TSLA To sell my $230 call at open or not? 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:56:34 </td>
   <td style="text-align:left;"> $TSLA Goldman Sachs 25 billion in government play money to be accommodating who cares about lines….. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:56:27 </td>
   <td style="text-align:left;"> $TSLA NO BEARS ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:56:23 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA 

Too many calls - OI at the close yesterday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:56:22 </td>
   <td style="text-align:left;"> $TSLA over 100k OTM options came ITM. At $250, 18k more. This is going to hardcore gamma squeeze. 🚀📈🌕💎👍🏽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:56:07 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:56:01 </td>
   <td style="text-align:left;"> $RGTI 300k pre market volume. Looking good to breakout over 1.50.
AI needs Quantum computing!!

 $TSLA $NVDA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:56:00 </td>
   <td style="text-align:left;"> $TSLA Green candles exploding. Bears can’t escape now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:55:56 </td>
   <td style="text-align:left;"> $BBBYQ + 20% premarket $QQQ $MULN $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:55:55 </td>
   <td style="text-align:left;"> $TSLA not likely to go over 250 today.
not a short but I see 240 at close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:55:48 </td>
   <td style="text-align:left;"> More insider activity here in $NXGL 🐳 … CONVICTION !!  CEO giving guidance of 73% increase in revenue next quarter , 6 insiders have loaded the last few weeks. This company is seriously starting to fire up🔥

$SOFI has been running recently with $TSLA and $AI 💯

ONLY 4 MILLION FLOAT here in NXGL 🌊 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:55:44 </td>
   <td style="text-align:left;"> $F $GM $NIO $TSLA Elon doesn’t buy companies with no value or function. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:55:36 </td>
   <td style="text-align:left;"> $TSLA checkmate!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:55:32 </td>
   <td style="text-align:left;"> $TSLA Hey bear, how u guys doing there??? Did u lost ur underwear overnight? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:55:22 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:55:04 </td>
   <td style="text-align:left;"> By the time they start showing up on the relative strength scans, quite often you&amp;#39;ll miss the bulk of the move. 
 
$TSLA Tesla is a goo example of this.  
We got our clients and members in 50% ago. 
https://honeystocks.com/join </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:54:49 </td>
   <td style="text-align:left;"> $TSLA mk this post  shorts r trapped, if we have a 10% day we will see 300+ next week if not ahs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:54:39 </td>
   <td style="text-align:left;"> $TSLA the swings today are going to be epic. This is going to be awash in big money traders today. Big storm watch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:54:22 </td>
   <td style="text-align:left;"> $TSLA up 5% PreMarket on 3M volume 
🧸🐻🐻🧸🐻🧸🐻🧸🐻🧸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:54:21 </td>
   <td style="text-align:left;"> $NXGL Annnnddd JUST LIKE THAT MORE INSIDER BUYS IN NXGL!!! 
 
TOLD YOU!!!!  INSIDERS WON&amp;#39;T STOP LOADING!!!!! 
 
$NFLX $CVNA $TSLA All squeezing higher....NXGL little 4.2 low float with over 150k short will squeeze here!!!  LOAD UP!!! 
 
Latest data once approved here by FDA...NexDerm and NexDrape products right into the ALL HOSPITALS to TAKE MARKET SHARE FROM $MMM &amp;#39;s Tegaderm...which has a monopoly in hospital settings. 
 
NEXGELS&amp;#39;s products NOT HAVE IRRITANTS or ADHESIVES like Tegaderm!!! HUGGGEEEE!!! 
 
Also LOOK BELOW FOR DATA ON DRUG DELIVERY NOW&amp;gt;&amp;gt;&amp;gt;&amp;gt; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:54:18 </td>
   <td style="text-align:left;"> @SchruteFarms technical analysis speaking we are at a triple 
top on the weekly so i actually bought puts aftermarket yesterday. $TSLA and some other tech companies making it look not so promising tho 🧐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:54:05 </td>
   <td style="text-align:left;"> $GM GM’s volume is already over 1million in pre market…She gonna go to $40 today!
$FORD $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:54:04 </td>
   <td style="text-align:left;"> $TSLA Poor poo bears. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:54:02 </td>
   <td style="text-align:left;"> $TSLA SHORTS. GOT LUBE? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:53:53 </td>
   <td style="text-align:left;"> @OldFngGuy Pretty sure you meant $TSLA and not $TLSA ... 
 
Anyhow, yeah. There are a ton of hedge funds and short sellers that got utterly wrecked on Tesla. Man they got hit hard without realizing Tesla is a unicorn. 
 
The people who bought into these meme tickers bought into a get rich quick scheme, and it&amp;#39;s obvious that never works out.  
 
Compound interest in boring old index funds are the ticket to wealth. It&amp;#39;s the most powerful force in the universe next to a bunch of 5 gallon buckets being stuck together. But don&amp;#39;t tell that to the apes who bought these meme tickers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:53:40 </td>
   <td style="text-align:left;"> $META $AAPL $TSLA $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:53:30 </td>
   <td style="text-align:left;"> $TSLA 
Payday today for those 227.5 Calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:53:23 </td>
   <td style="text-align:left;"> DIA $F $SPY $TSLA $GM $QQQ  #todamoon  #carsonmars </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:53:04 </td>
   <td style="text-align:left;"> $TSLA will end up down at the end of the day.major institutions are lining up to sell 100 of millions of shares after 100 dollars run in one </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:52:57 </td>
   <td style="text-align:left;"> $TSLA  also observed that chart history calls for a pullback to $241.5 today after profits takers sell after open.. so will cover short there first..added short 100 shares at $250.06 as well. If I see $241.5 I will buy 0dte $245 calls and wait for $253 to start shorting again into Monday GLTA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:52:56 </td>
   <td style="text-align:left;"> $TSLA For all those saying there will be lines at charging stations, did you ever stop to think Tesla might scale up to meet demand? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:52:41 </td>
   <td style="text-align:left;"> @Formula400 Lol the gift that keeps on giving - will be buying back into $CHPT today in the afternoon if there is continued downtrend from the $TSLA $GM news. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:52:16 </td>
   <td style="text-align:left;"> $TSLA   

🚨🚨🚨‼️

Factors in Shorts getting undone:

1/ Size of short volume and type will (naked synthetic) be a factor ! 
2/ S&amp;amp;P 500 Funds balancing 
3/ Accumulation Funds
4/ Reserve Funds 

This thing could double mathematically—- those are the factors imo 

All you n my posts!!  

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:51:55 </td>
   <td style="text-align:left;"> $TSLA it&amp;#39;s so overbought... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:51:54 </td>
   <td style="text-align:left;"> $TSLA should be looking for more strength towards $268.54- $296.08 area before a pullback takes place. Intraday dips should find buyers in 3, 7 or 11 swings  #Elliottwave #Trading #Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:51:43 </td>
   <td style="text-align:left;"> $TSLA anybody else load calls yesterday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:51:32 </td>
   <td style="text-align:left;"> $TSLA Shorts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:51:28 </td>
   <td style="text-align:left;"> $TSLA About to see a lot of, &amp;quot;why is it going down?&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:51:20 </td>
   <td style="text-align:left;"> $CVNA was beautiful yesterday but it looks like it still has legs left. Shirts be careful, this can go pretty good for you or really bad. $SPY still having a battle under that $430. If it breaks it has to hold. Nothing is given. $TSLA has been wild for the past month leading up to this deal with $GM. Definitely some insider trading. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:51:19 </td>
   <td style="text-align:left;"> $TSLA I’m taking your paper gains when this baby drops. Dip baby dip. Short this baby. (Short term) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:51:18 </td>
   <td style="text-align:left;"> $SBRCY Hello, hello, hello 👋  
 
We are waiting?  (Enjoying my $TSLA $155 average). 
 
What about You? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:50:47 </td>
   <td style="text-align:left;"> $TSLA $REKR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:50:46 </td>
   <td style="text-align:left;"> $TSLA Haven&amp;#39;t seen the &amp;quot;chasing Tulips&amp;quot; argument this morning....lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:50:44 </td>
   <td style="text-align:left;"> $TSLA I’m reversing my sentiment. Can I post this? Up, up, up and away! 🚀 $87 up since. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:50:43 </td>
   <td style="text-align:left;"> GAMEPLAN!    
 
Today already looks insane! $TSLA has now spiked over $100 in the last two months and we are currently sitting at highs! $CVNA is the #1 watched play with the MOST VOLUME and the MOST SHORTED in the Stock Market which traders are trying to squeeze!   Today is a day of Good Entries. We already know $CVNA and $TSLA is where all traders will be focused on. All we need to do is find a great entry and place our stop losses.   So What Are the Great Entries?   $CVNA Strong RES at $26. A break of $26 and we could squeeze to $28.75. My first SHORT will be in the high $25 area, I plan on setting a stop at $26.10. If I lose, I lose small. If $CVNA Reverses, then I am at the top. If it breaks $26, I can also cover my shares and watch for the spike! It is a win win   
 
$TSLA I do think we see $251- $252 today, but after seeing such a large gap up and over extended move, I would not be surprised to see a morning crack about 30 mins in. Everyone needs to bring your A Game here! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:50:43 </td>
   <td style="text-align:left;"> $NIO big sell orders in pre market. This is gonna crash hard. Trash earnings as expected. Save your money and move to $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:50:41 </td>
   <td style="text-align:left;"> $TSLA SHORTS YOU CAN STILL COVER AND GO LONG !!!  
 
300 is going to come even faster now !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:50:30 </td>
   <td style="text-align:left;"> $F $GM $NIO $TSLA wait til Tesla buys nio. Guarantee </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:50:04 </td>
   <td style="text-align:left;"> Top Watches today: Lots of movers today large caps small caps med caps, everything is flying, IMPORTANT to MANAGE RISK well though on a Friday after a long week... Looking for a nice bounce back day.** $MDGS $NFLX $TSLA $QQQ #PLTR #AFRM $WLDS **. Good luck out there! 🙏🍺❤️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:49:59 </td>
   <td style="text-align:left;"> $TSLA this is fear mongering trying to save his short position. It’s possible this could retrace but I wouldn’t put any money on it. I would jump in or
out. Always wait for confirmations on directions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:49:51 </td>
   <td style="text-align:left;"> $TSLA Do we fill that gap today??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:49:42 </td>
   <td style="text-align:left;"> $MDGS some are accumulating for very cheap. Soon $20 $20 $20. One float is locked, $100 is also achievable. $TOI $SNOA $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:49:42 </td>
   <td style="text-align:left;"> $TSLA ....Short $250.16...91 RSI premarket, opening likely gap to 86-88....Highest on record is 91.  Looking for a pullback only. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:49:40 </td>
   <td style="text-align:left;"> $TSLA 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:49:36 </td>
   <td style="text-align:left;"> $TSLA That $250 flag tho. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:49:35 </td>
   <td style="text-align:left;"> $CJET told you EVs are hot today
Ppl are making mad money on $TSLA theyll diversify their gains on other EVs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:49:16 </td>
   <td style="text-align:left;"> $TSLA beast </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:49:01 </td>
   <td style="text-align:left;"> $SPY bull market baby $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:48:56 </td>
   <td style="text-align:left;"> $TSLA those that sold will have to buy back at a higher price. Don’t be dumb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:48:35 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:48:35 </td>
   <td style="text-align:left;"> $TSLA $spy $qqq $lcid go

https://www.twitch.tv/tramplewun/v/1841749838?sr=a&amp;amp;t=2s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:48:34 </td>
   <td style="text-align:left;"> $TSLA Tesla will be the Walmart of energy resources in the near future </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:48:28 </td>
   <td style="text-align:left;"> $TSLA some resistance at $250 but hoping she can bust through that limit today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:48:28 </td>
   <td style="text-align:left;"> $TSLA 275 or 300 today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:48:24 </td>
   <td style="text-align:left;"> $NIO nice that GM n ford are getting in bed with Tesla charging…it will be hilarious watching a lineup of people waiting to charge while Nio owners drive through and swap battery in 5min or less. $F $GM $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:48:19 </td>
   <td style="text-align:left;"> $EVGO What Wall St does not get, so far anyway, is that adoption is key. The more EV&amp;#39;s we get on the road the more chargers we will need. The US needs 100x more chargers at least and EVGO have them in places that Tesla does not. Every EVGO charger can service a $GM, $F, Kia, Hyundai or $TSLA car and EVGO are getting government help to install as many as they can, as quickly as they can. The stock should be higher as this is great news for $EVGO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:48:12 </td>
   <td style="text-align:left;"> $TSLA all the hype means go short. All the whales like to sell into strength. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:48:05 </td>
   <td style="text-align:left;"> $TSLA No chill </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:48:04 </td>
   <td style="text-align:left;"> $TSLA even if it went to 700, I probably won&amp;#39;t sell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:48:03 </td>
   <td style="text-align:left;"> $TSLA I wish I’d have truly YOLO’d every dollar I have into calls yesterday. Unfortunately I only bought a few. Fuq me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:47:52 </td>
   <td style="text-align:left;"> $AI wondering if shorts are scared that the $TSLA just lit the fuse for the market to go bonkers so they closing out their shorts just in case. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:47:50 </td>
   <td style="text-align:left;"> $TSLA Joe&amp;#39;s at the Helm.... Oops and you&amp;#39;re buying Calls? $spy This idiot thinks it&amp;#39;s his birthday this morning  GL $KRE $KSS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:47:49 </td>
   <td style="text-align:left;"> $TSLA 😳👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:47:40 </td>
   <td style="text-align:left;"> $TSLA imagine all the butt hurt Tesla haters. 😆 God is good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:47:27 </td>
   <td style="text-align:left;"> $TSLA Who Said 300? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:47:26 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:47:24 </td>
   <td style="text-align:left;"> $TSLA fk your RSI....😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:47:01 </td>
   <td style="text-align:left;"> $TSLA $IEP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:46:55 </td>
   <td style="text-align:left;"> $TSLA shorts are fu…………..cked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:46:47 </td>
   <td style="text-align:left;"> $TSLA 100 shares extra short for each $1 gain above $250.4 that&amp;#39;s my plan..chart history does not lie and today 11th day in green to complete the record on Jan 8 2021..the 11th day in green was the one with the most daily increase in 8% so from yesterday close..that number gives $253.6 as high for today and on Monday the first red day gets 9% down to $230.. so shorting the heck out of it..but then it will go above latex21a3233ac5fd0681787d9862a7e3428aSGML 

$TGTX 

The 4 🐴 man. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:46:42 </td>
   <td style="text-align:left;"> $TSLA $269 incoming! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:46:37 </td>
   <td style="text-align:left;"> $TSLA 230c 6/30 I picked up yesterday will print !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:46:31 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:46:28 </td>
   <td style="text-align:left;"> $TSLA this will be in the $260’s today.  Short squeeze next.  It’s hard to hold this when it is full of enthusiasm to the positive side </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:46:26 </td>
   <td style="text-align:left;"> $CHPT $tsla delivers death blow to $chpt. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:46:19 </td>
   <td style="text-align:left;"> $TSLA you bears need to stfu with your bear posts do you see the stock? How do you shameless post bearish shit inspite of the stock being up this much for this many days? 🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:46:16 </td>
   <td style="text-align:left;"> $TSLA if 258 resistance doesnt hold it might get even more crazy :/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:45:55 </td>
   <td style="text-align:left;"> $TSLA Tesla gains 6.39% in pre-market trade. General Motors announced on Thursday plans to utilize Tesla’s electric vehicle charging network, and said its vehicles will also utilize Tesla’s North American Charging Standard port in its cars starting in 2025. More trending stocks https://bit.ly/43giYXv </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:45:54 </td>
   <td style="text-align:left;"> $TSLA ride the rsi! Ignore the over bought bull shit, Weekly rsi and monthly rsi just getting started!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:45:49 </td>
   <td style="text-align:left;"> $CVNA $TSLA $ADBE $SPY $QQQ my bags pre market 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:45:49 </td>
   <td style="text-align:left;"> $TSLA    
 Calls:    
📈 at $245 - $243  
Puts:   
📉  below $241 
   
Let the setup come to you!  
Manage risk properly! cut losses quickly! And always take profits. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:45:39 </td>
   <td style="text-align:left;"> $TSLA  Higher gap at 262.47  Just saying. 
 
https://share.trendspider.com/chart/TSLA/6682ok7z8i </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:45:30 </td>
   <td style="text-align:left;"> $TSLA $265 today! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:45:22 </td>
   <td style="text-align:left;"> $TSLA 1hr view from the 6/06/2023 Post-Market update. Showing further reaction higher taking place from the blue box area #Elliottwave #Trading #Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:45:20 </td>
   <td style="text-align:left;"> $TSLA elon musk will file to sell  100 to 200 M shares to fund twitter and other projects. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:45:07 </td>
   <td style="text-align:left;"> $TSLA summer pt 200-150 .. lfg? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:44:39 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $QQQ $META the result of April? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:44:38 </td>
   <td style="text-align:left;"> $TSLA so many bulls with insane PT, getting into the Bulls Trap... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:44:37 </td>
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
   <td style="text-align:left;"> 2023-06-09 20:44:30 </td>
   <td style="text-align:left;"> $TSLA Tesla convenience store sounds good in the future or a partnership with local gas stations to install charging stations to service new Ford and GM electric cars </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:44:15 </td>
   <td style="text-align:left;"> $SOFI do I dump my $TSLA profits here???  Asking for a friend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:44:08 </td>
   <td style="text-align:left;"> @dizzzy yeah you&amp;#39;re right, like investing in $TSLA when it was trading at $110 back in January. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:44:03 </td>
   <td style="text-align:left;"> $TSLA wow missed out on 3k of profit fuck me sideways </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:44:02 </td>
   <td style="text-align:left;"> $TSLA map update: we&amp;#39;re just shy 10 points of my ultimate target on news today.  Only I was way off on the timing.  Wow. 
 
Underlining my thesis that Tesla is now THE market leader, replacing $AAPL. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:43:53 </td>
   <td style="text-align:left;"> $TSLA Elon musk counting money 💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:43:51 </td>
   <td style="text-align:left;"> $TSLA these June 23rd 230 calls makin printer go brrr... 😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
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
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:43:30 </td>
   <td style="text-align:left;"> $TSLA daily RSI will probably open at around 97 lol 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:43:14 </td>
   <td style="text-align:left;"> $TSLA 1hr view from the 6/01/2023 Pre-Market update. Showing a very nice reaction higher from the blue box area. Allowed longs to get into a risk-free position  #Elliottwave #Trading #Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:43:03 </td>
   <td style="text-align:left;"> $TSLA all they need open flat or red then drop to a level where it cannot recover and sell all day to kill calls. They can save tons of money by doing so. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:42:41 </td>
   <td style="text-align:left;"> Let&amp;#39;s play a game. Guess which ticker this is.

This is the play from yesterday. Alerted the near perfect level for a reversal trade. Just $0.03c from its absolute bottom of the day.
All possible from ONLY buying when H% is low. Look at the each steps shown.

$SPY $TSLA $AAPL $MSFT $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:42:31 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:42:07 </td>
   <td style="text-align:left;"> $nvda AI already breached and in trouble. $googl $aapl $tsla $nflx 🫧📌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:42:07 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:42:03 </td>
   <td style="text-align:left;"> $TSLA looks like tippy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:42:02 </td>
   <td style="text-align:left;"> $TSLA gates must not be privy to info unlike Soros? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:42:00 </td>
   <td style="text-align:left;"> $TSLA “Markets can remain irrational longer than you can remain solvent” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:41:58 </td>
   <td style="text-align:left;"> $TSLA new support and still running </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:41:52 </td>
   <td style="text-align:left;"> $TSLA price prediction for today is $253🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:41:41 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:41:14 </td>
   <td style="text-align:left;"> $TSLA 1hr view from the 5/31/2023 Midday update. Provided a buying opportunity at the blue box area last week  #Elliottwave #Trading #Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:41:10 </td>
   <td style="text-align:left;"> DIA $F $SPY $TSLA $GM $QQQ   CARS ON MARS ... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:41:06 </td>
   <td style="text-align:left;"> $TSLA $AIHS $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:41:02 </td>
   <td style="text-align:left;"> $THMO $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:40:52 </td>
   <td style="text-align:left;"> $TSLA which puts will make millions? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:40:47 </td>
   <td style="text-align:left;"> $TSLA I will wait to buy at 300 🙃🙃🙃🤠🤠 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:40:43 </td>
   <td style="text-align:left;"> $TSLA best stock ever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:40:42 </td>
   <td style="text-align:left;"> $TSLA 250 pre hot damn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:40:34 </td>
   <td style="text-align:left;"> $TSLA Friday 0DTE call options may just pump this baby to 300! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:40:32 </td>
   <td style="text-align:left;"> $F $GM $TSLA interesting 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:40:15 </td>
   <td style="text-align:left;"> $TSLA Bears tapping out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:39:55 </td>
   <td style="text-align:left;"> $TSLA The only reason $F and $GM are using Tesla&amp;#39;s charging stations is that they don&amp;#39;t take their own EV manufacturing seriously. It&amp;#39;s just a &amp;quot;yeah, we do that, too&amp;quot; bit of poppycock to appease the green mob. In reality, they&amp;#39;re just biding their time until a Republican takes back the WH, and then you&amp;#39;ll see them rolling back those EV lines. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:39:54 </td>
   <td style="text-align:left;"> $TSLA BOOM bye shorts. Yes I’m laughing at you short sellers. Bunch of losers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:39:46 </td>
   <td style="text-align:left;"> $TSLA 7 million already I think we hit 200 million volume today 😜✌️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:39:44 </td>
   <td style="text-align:left;"> $TSLA GM and Ford finally surrender to Far ahead Technology from Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:39:36 </td>
   <td style="text-align:left;"> $TSLA overreaction? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:39:34 </td>
   <td style="text-align:left;"> $TSLA $AAPL $GOOG Our Long Watchlist of plays we alerted 3/12 is KILLING IT…
It’s what we do 🤷🏼‍♂️😎
Ready for our release? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:39:34 </td>
   <td style="text-align:left;"> $TSLA I like the stonk. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:39:30 </td>
   <td style="text-align:left;"> $TSLA Weekly Puts toasted </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:39:29 </td>
   <td style="text-align:left;"> $CJET EVs hot $NIO $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:39:28 </td>
   <td style="text-align:left;"> $KSS $tsla $spyJoe&amp;#39;s at the Helm.... Oops and you&amp;#39;re buying Calls? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:39:25 </td>
   <td style="text-align:left;"> $TSLA if this green then hedge funds will lose billions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:39:24 </td>
   <td style="text-align:left;"> $TSLA for 1 to 3 billions extra revenue in 2025 for a co has arevenue 127b dollars.the market cap increased by 70b b/w yesterday and today 
That&amp;#39;s ridiculous and </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:39:18 </td>
   <td style="text-align:left;"> $TSLA bears cmon you pussies show us how strong you are. Drop that price </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:39:08 </td>
   <td style="text-align:left;"> $TSLA RSI is no longer a reliable indicator. In additions, candles are not valid. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:39:06 </td>
   <td style="text-align:left;"> $TSLA 

We’re rich. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:39:01 </td>
   <td style="text-align:left;"> Tesla’s charging partnerships with Ford, GM will speed up green energy transition, Cathie Wood says

$TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:38:59 </td>
   <td style="text-align:left;"> $SPY futures choppy but so many things getting massive pumps pre market $TSLA $ADBE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:38:44 </td>
   <td style="text-align:left;"> $TSLA NACS4LYF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:38:38 </td>
   <td style="text-align:left;"> $TSLA beauty of this is we will get a bunch of new shorts and put positions at the bell which will also get squeezed today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:38:32 </td>
   <td style="text-align:left;"> $TSLA someone please tell me how it&amp;#39;s beneficial to allow competitors access to tslas charging station standard. From what I understand tsla makes little to nothing on their charging stations. Now gm and f ev s can use them. Isn&amp;#39;t this going to drive sales away from tsla to f and gm? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:38:30 </td>
   <td style="text-align:left;"> $TSLA we&amp;#39;re so back 📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:38:26 </td>
   <td style="text-align:left;"> $TSLA if thunk keeps going like this, Elon will be soon rich enough to buy the next social media platform </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:38:16 </td>
   <td style="text-align:left;"> $TSLA cash on cash on cash on cash </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:38:13 </td>
   <td style="text-align:left;"> $TSLA where do they let it open today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:38:11 </td>
   <td style="text-align:left;"> $TSLA I’m gettin tippy tippy vibes on this beautiful Friday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:38:08 </td>
   <td style="text-align:left;"> IT IS OFFICIAL! The longest bear market since the 40&amp;#39;s has come to a conclusion for now. Most of the gains have been from big tech like $AAPL $NVDA and $TSLA. 
 
Tesla is going crazy this morning after closing another charging station deal, this time with $GM.  
 
META is trying to make a platform to compete with twitter, saying that creators have asked for a version of twitter that is &amp;quot;sanely run&amp;quot; which is a little ridiculous considering all the Meta employees probably drive teslas. They want to do the platform on instagram and make it just like twitter. I will not be particpating.  
 
CVNA had a big day yesterday, rising 51% after their profit outlook improved. Pretty flat trading premarket, but that could be a fun one to trade today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:38:01 </td>
   <td style="text-align:left;"> $NFLX $TSLA Friends and followers... while my specialty is pennies, I want to give a shout out to one of my  mentors who just launched a discord room for options.  If you have ever wanted to learn options or just want to learn how to trade options better, check him out on twitter  &amp;quot;polarbeartrade&amp;quot;  Below are some of the calls I am holding - two of which I will lock for over 1000% this morning.  While not every call equates to these kinds of gains, I can say with all sincerity  that I have never met another trader who understands large caps and options like he does. Good Luck traders, and congrats TSLA and NFLX bulls! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:37:59 </td>
   <td style="text-align:left;"> $TSLA this is why you don’t trade tesla ; you own it and hold it ; just like apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:37:58 </td>
   <td style="text-align:left;"> $TSLA rip all regarded bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:37:57 </td>
   <td style="text-align:left;"> $TSLA 
Smells like a blowoff Top imo.
🐻 🧸 🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:37:54 </td>
   <td style="text-align:left;"> $TSLA back to 1k end of year $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:37:51 </td>
   <td style="text-align:left;"> $TSLA aaah, tesla doing tesla things. Very nice move </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:37:45 </td>
   <td style="text-align:left;"> $TSLA first short of today at $250.56 GLTA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:37:42 </td>
   <td style="text-align:left;"> $TSLA F with the bull, you get the horns. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:37:35 </td>
   <td style="text-align:left;"> $TSLA congrats to anyone holding calls this week. Wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:37:33 </td>
   <td style="text-align:left;"> $TSLA $300 PT by next Friday!!! Easy Money!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:37:29 </td>
   <td style="text-align:left;"> $TSLA 

https://apextraderfunding.com/member/aff/go/danny715

! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:37:29 </td>
   <td style="text-align:left;"> $TSLA dis sumbich bouta boom! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:37:27 </td>
   <td style="text-align:left;"> $TSLA yesterday i put a call for 250 for july 7th, less than 24 hours we hit the target </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:37:26 </td>
   <td style="text-align:left;"> $tsla Kathie Woods just gave Tesla the kiss of death 💋💀 $COIN $ARKK $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:37:16 </td>
   <td style="text-align:left;"> $TSLA Damn 🙄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:37:16 </td>
   <td style="text-align:left;"> $TSLA pouring one for the bears. My 230c and 235c will be paid. Attacking 275c fir next week… even though it might tag it today. It’s a celebration betches!!! Thanks for the fuel bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:37:00 </td>
   <td style="text-align:left;"> $TSLA Elon right now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:36:56 </td>
   <td style="text-align:left;"> $TSLA $300 PT !  
https://www.investing.com/news/stock-market-news/tesla-now-owns-the-charging-ecosystem-domestically--wedbush-bumps-target-on-gm-deal-432SI-3101946 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:36:25 </td>
   <td style="text-align:left;"> $TSLA Happy for everyone making money. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:36:20 </td>
   <td style="text-align:left;"> $TSLA greatest pump of all time is tesla. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:36:19 </td>
   <td style="text-align:left;"> $TSLA 270ish Y not at this rate.....50pointer for EOW F U candle </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:36:12 </td>
   <td style="text-align:left;"> $TSLA crud…looked back at my last Tesla sell and it was $196. Missed this run majorly. 😳😳 congrats y’all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:36:08 </td>
   <td style="text-align:left;"> $TSLA two easy questions for any real tesla bull. Being asked honestly. What is the max AC charging speed at home and what are DC superchargers maxing out at for the newest models? Im guessing 11kwh for AC and 200kwh for DC. Is that accurate? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:36:03 </td>
   <td style="text-align:left;"> $SPY Morgan Stanly being the biggest joke of them all $QQQ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:36:00 </td>
   <td style="text-align:left;"> $TSLA going for 314 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:35:57 </td>
   <td style="text-align:left;"> $TSLA what is there left to pump? We already up 7% on no volume. Watch market take this to 260 today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:35:56 </td>
   <td style="text-align:left;"> $TSLA there&amp;#39;s a guy on Wallstreet bets who bought 1000 250 calls expiring tomorrow as a mistake. He might make a million if tsla hits 260 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:35:54 </td>
   <td style="text-align:left;"> $TSLA pump to 300 with your fake upgrade so massive dump happens. The wait for many shareholders tired of Felon Muskarat, thanks to GM and Ford takeover, is over! $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:35:52 </td>
   <td style="text-align:left;"> $TSLA I still have 217.5 weekly calls. I think I’ll get out at open. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:35:50 </td>
   <td style="text-align:left;"> $TSLA $SPY EZ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:35:49 </td>
   <td style="text-align:left;"> $TSLA Will watch now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:35:46 </td>
   <td style="text-align:left;"> $TSLA wonder how much Elon made the past 2 days ? 🧐 theoretically, I know he’d have to sell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:35:41 </td>
   <td style="text-align:left;"> $TSLA 110% YTD, load puts like no brainer. Another reason is $WISH pumpers are pumping this. I just need to do the opposite. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:35:40 </td>
   <td style="text-align:left;"> $TSLA damn I said open at 250… could be more than that 🤧🤧🤧 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:35:31 </td>
   <td style="text-align:left;"> In Group 3 Live Session today, we will also explain that the #Dollar has ended the bounce and will get sideways to lower in a Negative USD Dynamic. #Equities and #commodities should rally.  #Elliottwave #Stocks #Trading $SPY $SPX $AAPL $TSLA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:35:31 </td>
   <td style="text-align:left;"> $TSLA So you mean TSLA basically owns the only place to charge an EV in the US?   Hahaha I’m in! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:35:21 </td>
   <td style="text-align:left;"> $TSLA Acquired $250 Pt. On watch now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:35:20 </td>
   <td style="text-align:left;"> Disgrace to the Stock Race  the bears 🐻 
$SPY $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:35:18 </td>
   <td style="text-align:left;"> $TSLA I think I made have made 20k profit on my calls.... 🤤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:35:17 </td>
   <td style="text-align:left;"> $SPY the local $TSLA charging station is already packed. Need more stations. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:35:12 </td>
   <td style="text-align:left;"> $NFLX BOOM 💥 Told you all yesterday 📈

$SPY $TSLA $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:35:10 </td>
   <td style="text-align:left;"> $TSLA $269.69 baby! For 6/9!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:35:01 </td>
   <td style="text-align:left;"> $TSLA I think I’ll sell a little here but hold the rest for $300 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:35:00 </td>
   <td style="text-align:left;"> $TSLA 250 ;-) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:34:58 </td>
   <td style="text-align:left;"> $TSLA we may fill that 280 gap in the next week or two. Load your 300c, boys. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:34:48 </td>
   <td style="text-align:left;"> $TSLA this isn’t a penny stock… gaps don’t have to fill lmao. I can think of 100 examples right now with companies like apple and Amazon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:34:44 </td>
   <td style="text-align:left;"> $TSLA not even sure what we’re pumping about anymore but I’ll like it. A LOT! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:34:41 </td>
   <td style="text-align:left;"> $TSLA
Bears “$260? it’s not possible.”
Bulls “No. it’s necessary.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:34:23 </td>
   <td style="text-align:left;"> $TSLA TESLA WILL BE THE GAS STATIONS OF THE FUTURE..IT WILL BE THE FIRST $10 TRILLION COMPANY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:34:17 </td>
   <td style="text-align:left;"> $TSLA what will hod be? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:34:16 </td>
   <td style="text-align:left;"> $TSLA bears grab your balls and whatever money you have left and drop the price so I can buy more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:34:11 </td>
   <td style="text-align:left;"> $CVNA $TSLA $PLTR  it another wonderful day with you three. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:34:09 </td>
   <td style="text-align:left;"> $TSLA to the moon!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:34:09 </td>
   <td style="text-align:left;"> $TSLA shorts if your still shorting since 200 you have only lost half your investment </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:34:07 </td>
   <td style="text-align:left;"> $TSLA holy F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:34:06 </td>
   <td style="text-align:left;"> $TSLA 3x the normal PM volume.  Pain n more pain for the shorts like Craig and G Johnson. How on earth these 2 still have a job </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:34:05 </td>
   <td style="text-align:left;"> The cash train continues..... $CVNA $TSLA $AFRM $UPST </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:34:05 </td>
   <td style="text-align:left;"> $TSLA Bears are mad in the comment section I wonder why lol 

They must of thought today was going to be a bearish day or was hoping for it to go back to $215 lol

They really about to be mad once opening bell hit and they see a negative balance lol 

$280 by earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:33:51 </td>
   <td style="text-align:left;"> $TSLA no one told me RSI goes plaid at 110? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:33:43 </td>
   <td style="text-align:left;"> $TSLA straight lotto 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:33:43 </td>
   <td style="text-align:left;"> Damn $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:33:33 </td>
   <td style="text-align:left;"> $TSLA 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:33:23 </td>
   <td style="text-align:left;"> $SPY Who bought POS $MSFT instead of pumping $TSLA $CVNA ? 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:33:18 </td>
   <td style="text-align:left;"> $TSLA my 250 contract wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:33:10 </td>
   <td style="text-align:left;"> $TSLA someone said short at open you still wanna short at open 🤡😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:32:40 </td>
   <td style="text-align:left;"> $TSLA yassssssss!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:32:39 </td>
   <td style="text-align:left;"> $TSLA bears I don’t hear or see you what happened? 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:32:34 </td>
   <td style="text-align:left;"> $TSLA Who wants to see my </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:32:22 </td>
   <td style="text-align:left;"> $TSLA get use to these $10 to $15 pops!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:32:20 </td>
   <td style="text-align:left;"> $TSLA  you will sell house ? 

Ok. Go ahead </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:32:08 </td>
   <td style="text-align:left;"> $TSLA holy fucking shit dude I think Tesla is going through price discovery for their charging business </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:32:07 </td>
   <td style="text-align:left;"> $TSLA  
Almost there $$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:32:01 </td>
   <td style="text-align:left;"> $TSLA  going to open new position @ 10.30 AM today 👋👋..

Scalpers get lost </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:31:57 </td>
   <td style="text-align:left;"> $TSLA $225 puts July 28 or Aug 18? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:31:46 </td>
   <td style="text-align:left;"> $TSLA clearly &amp;quot;never bet against Tesla&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:31:34 </td>
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

$TSLA $TQQQ $SPYD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:31:34 </td>
   <td style="text-align:left;"> $TSLA there&amp;#39;s  my 250! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:31:28 </td>
   <td style="text-align:left;"> $TSLA food stamp office opens at 8am . The bears are nowhere to be found here 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:31:24 </td>
   <td style="text-align:left;"> Group 3 Live Session will start at 9AM. Tune in @ https://elliottwave-forecast.com/amember/go.php?r=34991&amp;amp;i=l1 where we will explain all the instruments and what should be happening next. #Elliottwave #Stocks #Trading $SPY $QQQ $TSLA $AAPL $SPX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:31:19 </td>
   <td style="text-align:left;"> $TSLA Will this drop hard at the bell from people taking profits? I hope so, to buy calls lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:31:19 </td>
   <td style="text-align:left;"> $TSLA cmon knock down that 250 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:31:12 </td>
   <td style="text-align:left;"> $TSLA what i learned holding my 16 month 75k Amazon bag is you either lock profit or someone else locks your profit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:31:12 </td>
   <td style="text-align:left;"> $TSLA $1T MC coming soon… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:31:10 </td>
   <td style="text-align:left;"> $TSLA Raise your hands if you bought puts yesterday? 😜 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:31:06 </td>
   <td style="text-align:left;"> $TSLA anyone think I should buy some $300 strike exp in 2 weeks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:31:02 </td>
   <td style="text-align:left;"> $TSLA [15s. delayed]: Issued Press Release on June 09, 08:30:00: Home Advantage: How Domestic REE Supply Is Supercharging North American C https://s.flashalert.me/IozAX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:31:00 </td>
   <td style="text-align:left;"> $TSLA but spy is sus atm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:30:54 </td>
   <td style="text-align:left;"> $TSLA boom that’s the milestone …. Next one 300 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:30:30 </td>
   <td style="text-align:left;"> $TSLA $250 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:30:24 </td>
   <td style="text-align:left;"> $TSLA 300 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2023-06-09 20:30:10 </td>
   <td style="text-align:left;"> $TSLA How High will it go today you asked? The stock will see 153.50&amp;#39;s to 155&amp;#39;s once it gets going after the Bell a roonski. </td>
  </tr>
</tbody>
</table></div>

---
