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



Last Updated: 2022-02-02 09:01:50 UTC +8

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
   <td style="text-align:left;"> https://tradingeconomics.com/australia/stock-market </td>
   <td style="text-align:left;"> 2022-02-02 08:52:27 </td>
   <td style="text-align:left;"> Australian Shares Jump on Mining, Energy Boost </td>
   <td style="text-align:left;"> The S&amp;P/ASX 200 Index jumped 1.2% to around 7,090 on Wednesday as higher commodity prices lifted resource-related stocks, a day after the Reserve Bank of Australia held interest rates at a record low and pushed back on market bets for an early rate hike. The RBA decided to keep rates at 0.1% and called an end to its bond buying program, as widely expected, but governor Philip Lowe said the end of bond purchases was not a flag for a near-term rise in rates and the Board would stay patient on policy. Heavyweight miners and energy firms led the market higher on stronger iron ore and oil prices, with gains from BHP Group (2.3%), Fortescue Metals (4%), Rio Tinto (2.9%), Woodside Petroleum (2.5%) and Santos Ltd (2%). Gold stocks, lithium explorers, banks and retailers also gained, while technology firms mostly declined. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-02 08:28:36 </td>
   <td style="text-align:left;"> US Futures Extend Gains, Alphabet Jumps </td>
   <td style="text-align:left;"> US stock futures rose on Wednesday after the major averages gained for a third day, while investors mulled a fresh batch of earnings results. Nasdaq and S&amp;P 500 futures gained 0.9% and 0.4%, respectively, while Dow futures were flat. Google parent Alphabet jumped more than 8% in extended trading after the company reported better-than-expected Q4 earnings and revenue. Advanced Micro Devices also soared 10% on strong earnings, while Paypal tanked 17% on weak guidance. In regular trading on Tuesday, the major averages rose for a third day as investors tried to further shake off a tumultuous January driven by the Federal Reserve’s policy shift. The Dow rose 0.78%, the S&amp;P 500 edged up 0.69% and the Nasdaq gained 0.75%. Energy, basic materials and financial stocks led the market higher. Companies slated to report earnings on Wednesday include Meta Platforms, Qualcomm and AbbVie, among others. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60208466?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-02 08:03:21 </td>
   <td style="text-align:left;"> Amazon announces 1,500 new apprenticeships for 2022 </td>
   <td style="text-align:left;"> Tech giant Amazon has announced 1,500 new apprenticeships across the UK.                                                                                                                                                                                                                                                                    , The 40 schemes range from engineering to health and safety and includes more than 200 apprenticeships which are degree level.                                                                                                                                                                                                               , Amazon employs more than 70,000 staff in the UK and said the scheme would help more people get the skills in demand in the job market.                                                                                                                                                                                                      , BT Group recently announced plans to recruit more than 600 apprentices and graduates for September 2022.                                                                                                                                                                                                                                    , The group, one of the UK's largest private sector apprenticeship employers, said it would recruit for posts in its engineering, customer service, applied research, and cyber-security areas.                                                                                                                                               , The latest recruitment drive for both companies comes as firms in the UK and the US report growing problems filling skilled roles. Amazon has also previously offered a signing-on bonus of £1,000 to fill some roles.                                                                                                                      , Amazon's apprenticeships programme covers a wide range of areas including publishing, retailing, marketing, and a programme focused on environmental, social and corporate governance.                                                                                                                                                      , The firm's UK country manager John Boumphrey, said Amazon was "proud" to have created the 1,500 apprenticeships which would "help even more people get the skills that are in demand in today's labour market."                                                                                                                             , He added: "We want to be the employer that helps people take their careers to the next level, whether you're just starting your first job or making a career change, in every community that we serve across the UK."                                                                                                                       , Business Secretary Kwasi Kwarteng, said the announcement is "testament to the strength of the British economy, with GDP back at pre-pandemic levels, employee numbers at record highs and unemployment falling".                                                                                                                            , He added: "With the vast majority of Amazon's workforce located outside of London and the South East, these additional 25,000 jobs highlight the success of our Plan for Jobs in helping to ensure greater opportunities across the country."                                                                                               , Stephen Isherwood, chief executive of the Institute of Student Employers, told the BBC the move "reflects what we hear from many employers, that apprentice training routes deliver an increasingly important source of talent."                                                                                                            , However, Mr Isherwood said the government needed to make "significant improvements" to the "patchy careers provision in schools so that students and their parents are more aware of the alternatives to university".                                                                                                                       , Julian David, chief executive of industry group techUK said that increasing numbers of its members were now offering apprenticeships, but added that the plans the government had set out so far were "still leaving people behind as technology innovation is accelerating faster than the pipeline of people available to fill the gaps". , The BBC has contacted the Department for Education for a response.                                                                                                                                                                                                                                                                          , "While the pandemic and remote working have unfortunately slowed down apprenticeship adoption for some companies, it is clear that the sector is aware alternative routes to careers are an answer to today's digital skills crisis," Mr David added.                                                                                       , For employers who hire apprentices under 20 years old, Mr Isherwood said firms need to increase the "financial incentive to recruit".                                                                                                                                                                                                       , Another option, he said, would be for the government to allow employers "greater flexibility in how they spend their levy pot."                                                                                                                                                                                                             , Last year, business group the Chartered Institute of Personnel and Development said that UK employers had lost £2bn over the previous two years in apprenticeship levy funds that they were unable to spend.                                                                                                                                , Last September, Amazon announced it was looking to hire 55,000 staff globally for corporate jobs and roles in robotics, research and engineering.                                                                                                                                                                                           , About 40,000 jobs will be in the US, with 2,500 in the UK and the remainder mostly in India, Germany and Japan.                                                                                                                                                                                                                             , Prof. Steven Pinker tries to make sense of the situation...                                                                                                                                                                                                                                                                                 , Go behind the scenes at London's Corinthia Hotel                                                                                                                                                                                                                                                                                            , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60216076?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-02 08:01:09 </td>
   <td style="text-align:left;"> Fraud: MPs seek overhaul to tackle financial scammers </td>
   <td style="text-align:left;"> The strategy to tackle fraud and other economic crime should be overhauled to prevent scammers acting with "impunity", according to MPs.                                                                                                                                                  , Ministers should consider creating a new government department and a new law enforcement agency to get to grips with the issue, the Treasury Committee said.                                                                                                                              , The committee called for mandatory refunds in push-payment fraud cases.                                                                                                                                                                                                                   , This is when victims transfer money to fraudsters, thinking they are from official organisations.                                                                                                                                                                                         , Among a string of recommendations, MPs also said the government should consider whether to make big technology companies liable to pay compensation when people are tricked by con-artists using their platforms. Ministers should also legislate against online fraud adverts, they said., "For too long, pernicious scammers have acted with impunity, ripping off innocent consumers with fraudulent online adverts, impersonation scams and dodgy crypto investments," said Mel Stride, who chairs the committee.                                                                 , "Unfortunately, fraud has soared during the pandemic and, as MPs, we've heard heart-breaking stories of individuals who have fallen victim to these criminals and lost large sums of money.                                                                                               , "While the government have made some progress in this area, we're today calling on them to push harder and act faster on the growing fraud epidemic."                                                                                                                                     , The committee said there was a "bewildering" number of agencies responsible for fighting economic crime and fraud.                                                                                                                                                                        , "The government must consider why economic crime seems not to be a priority for law enforcement, and how it can ensure it becomes one," its report said.                                                                                                                                  , After having £25,000 stolen by fraudsters when she was recovering from a stroke, 74-year-old Janet from Essex was told the police would not investigate her case.                                                                                                                         , "It just seems like you're put in a heap, you're just one of a number," she told BBC Radio 4's Money Box programme last month.                                                                                                                                                            , "I had sleepless nights thinking about it. It was always on my mind."                                                                                                                                                                                                                     , More than £4m on average is stolen by fraudsters every day in the UK.                                                                                                                                                                                                                     , In total, £754m was stolen through fraud in the first half of last year, an increase of 30% compared with the same period last year, figures from banking trade body UK Finance show.                                                                                                     , Among a string of other reforms suggested by the Treasury Committee are longer term proposals to tackle financial crime and the emerging issues over cryptoassets.                                                                                                                        , It called for an overhaul of Companies House - where directors register companies - and to increase the cost to register a business from £12 or £13 currently to £100 in an attempt to deter criminals from setting up hundreds of shell firms.                                           , On crypto, it welcomed government plans to legislate to bring advertising of cryptoassets into line with that of other financial services and products, but said there should be "proper consumer protection regulation across the whole cryptoasset industry".                           , Prof. Steven Pinker tries to make sense of the situation...                                                                                                                                                                                                                               , Go behind the scenes at London's Corinthia Hotel                                                                                                                                                                                                                                          , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-02/u-k-retailers-raise-prices-at-fastest-pace-since-2012-brc-says?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-02 08:01:00 </td>
   <td style="text-align:left;"> U.K. Retailers Raise Prices at Fastest Pace Since 2012, BRC Says </td>
   <td style="text-align:left;"> Andrew Atkinson                                                                                                                                                                                                      , U.K. retailers raised their prices at the fastest pace in more than nine years in January as firms across the sector sought to pass on soaring food, fuel and transportation costs, a survey showed.                 , The report by the British Retail Consortium suggests inflation is becoming generalized, with goods from food to furniture seeing prices driven higher in a month when stores traditionally offer new year discounts.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-02/facebook-google-should-refund-scam-victims-u-k-lawmakers-say?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-02 08:01:00 </td>
   <td style="text-align:left;"> Facebook, Google Should Refund Scam Victims, U.K. Lawmakers Say </td>
   <td style="text-align:left;"> Tom Metcalf                                                                                                                                                                                                                                                                                                                                                           , A group of U.K. lawmakers is urging the government to “seriously consider” forcing technology companies including Facebook’s owner Meta Platforms Inc. and Google’s parent Alphabet Inc. to refund victims of fraud on their sites.                                                                                                                                   , “Placing a responsibility on online companies to reimburse consumers who are victims of online fraud could rapidly transform their approach,” the Treasury Committee’s report on economic crime said. “The government should seriously consider whether online companies should be required to contribute compensation when fraud is conducted using their platforms.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/01/business/starbucks-prices.html </td>
   <td style="text-align:left;"> 2022-02-02 07:45:14 </td>
   <td style="text-align:left;"> Starbucks Raising Prices as Inflation and Labor Costs Bite - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                     , The company’s profit soared 31 percent, to $816 million, in the last three months of 2021.                                                                                                                                                                                                                        , By Coral Murphy Marcos                                                                                                                                                                                                                                                                                            , Starbucks will increase prices this year, the coffee giant said on Tuesday, blaming supply chain disruptions and a sharp rise in labor costs.                                                                                                                                                                     , For the last three months of last year, the company’s profit soared 31 percent, to $816 million, Starbucks said in reporting its quarterly earnings on Tuesday. Revenue grew to $8.1 billion, a 19 percent jump compared with the same quarter a year ago.                                                        , The company raised prices in October 2021 and again in January 2022, executives said on Tuesday, and more increases are coming.                                                                                                                                                                                   , “We anticipate supply chain disruptions will continue for the foreseeable future,” said Kevin Johnson, the president and chief executive of Starbucks. “We have additional pricing actions planned through the balance of this year, which play an important role to mitigate cost pressures including inflation.”, The price of menu items at fast-food restaurants rose 8 percent in 2021, the biggest jump in more than 20 years, according to government data, with the chains citing higher costs for food, transportation and workers.                                                                                          , Starbucks also said it had increased spending on Covid-19 pay, including paid time off for employees to receive vaccinations or to those who contracted the virus. It also said it was spending more on training “to address labor market conditions.”                                                            , “Although demand was strong, this pandemic has not been linear,” Mr. Johnson said in a statement, adding that the company had “experienced higher-than-expected inflationary pressures.”                                                                                                                          , John Culver, the chief operating officer, said the price increases had not made “any meaningful impact to customer demand.”                                                                                                                                                                                       , Starbucks shares fell as much as 5 percent in after-hours trading after it announced its results for its fiscal first quarter, before recovering some of those losses.                                                                                                                                            , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/01/stock-market-futures-open-to-close-news.html </td>
   <td style="text-align:left;"> 2022-02-02 07:06:59 </td>
   <td style="text-align:left;"> Nasdaq futures rise after its third day of gains, Alphabet pops on strong earnings </td>
   <td style="text-align:left;"> , Nasdaq futures rose in overnight trading on Tuesday, after the technology-focused average gained for the third day in the regular session.                                                                                                                                                                         , Dow futures fell 40 points. S&amp;P 500 futures gained 0.25% and Nasdaq 100 futures rose 0.75%.                                                                                                                                                                                                                        , Google-parent Alphabet rose more than 7% in extended trading after the company beat on the top and bottom lines for its quarterly results. Alphabet also announced a 20-for-1 stock split.                                                                                                                         , Chip stock Advanced Micro Devices also gained on strong earnings, while Starbucks and General Motors dipped following their results. PayPal tanked 11% after hours after issuing disappointing guidance.                                                                                                           , On Tuesday, the major average rose for the third day as stocks attempted a comeback from their tumultuous January where the S&amp;P 500 has its worst month since March 2020.                                                                                                                                          , The Dow Jones Industrial Average added more than 270 points, helped by a 4.1% gain in Boeing. The S&amp;P 500 also registered a gain, climbing 0.7%. Bank stocks were some of the best performers on Tuesday.                                                                                                          , The Nasdaq Composite rose 0.75% as investors await key technology earnings after the bell and throughout the week.                                                                                                                                                                                                 , "The market has strung together a few solid up days," said Jim Paulsen, Leuthold Group chief investment strategist. "This strong showing is causing more investors to wonder if the correction is over and raising concerns that they could miss out on a nice post-correction rally"                              , Earnings season continues on Wednesday with key reporting from Meta Platforms, formerly Facebook, and Qualcomm. AbbVie, D.R. Horton and T-Mobile also report earnings on Wednesday.                                                                                                                                , So far this earnings season, more than 36% of the S&amp;P 500 has reported and more than 78% have topped Wall Street's expectations.                                                                                                                                                                                   , "While the earnings season began with some disappointments last week, it has become more solid in recent days," added Paulsen.                                                                                                                                                                                     , On the economic front, private payroll data is set to release at 8:15 a.m. on Wednesday. Economists polled by Dow Jones are expecting 200,000 private jobs were added in January, down from December's growth of 807,000 private payrolls, according to ADP.                                                       , The major averages are coming off of a volatile month, mainly spurred by a pivot in the Federal Reserve. However, some Fed members have have offered reassuring commentary that they do not want their pending rate hikes to disturb the financial markets and that few see any appetite for a 50 basis point hike., Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                             , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                             , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                   , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                   , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                 , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-01/u-s-stock-climb-sets-brighter-tone-for-asia-open-markets-wrap </td>
   <td style="text-align:left;"> 2022-02-02 06:28:38 </td>
   <td style="text-align:left;"> Stocks, Futures Rise on Earnings, Easing Fed Angst: Markets Wrap </td>
   <td style="text-align:left;"> Sunil Jagtiani                                                                                                                                                                                               , Asian stocks rose Wednesday amid a recovery in U.S. shares spurred by the corporate earnings outlook and signs that Federal Reserve officials favor measured monetary-policy tightening.                     , Equities advanced in Japan and Australia, among the few markets open in Asia due to the Lunar New Year holiday. U.S. Treasuries were steady, Australian bond yields jumped and a dollar gauge held a retreat. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-01/goldman-sees-qt-fueling-treasury-volatility-hurting-liquidity?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-02 06:26:13 </td>
   <td style="text-align:left;"> Goldman Sees QT Fueling Treasury Volatility and Hurting Liquidity </td>
   <td style="text-align:left;"> Alex Harris                                                                                                                                                                                                                                                                                                                                                                                                                             ,  and Edward Bolingbroke                                                                                                                                                                                                                                                                                                                                                                                                                 , A reduction in the size of the Federal Reserve’s balance sheet could hurt liquidity within the Treasury market, boost volatility and affect how different parts of the U.S. rates market are valued relative to one another, according to Goldman Sachs Group Inc.                                                                                                                                                                      , The call by Goldman strategists including Praveen Korapaty follows remarks from Citigroup Inc. strategists, who said in a report published late last week that the process of so-called quantitative tightening -- which is widely expected to follow on the heels of the central bank’s first interest rate increases later this year -- could spark a return of arbitrage opportunities for traders within U.S. interest-rate markets. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/unemployment-rate </td>
   <td style="text-align:left;"> 2022-02-02 05:58:09 </td>
   <td style="text-align:left;"> NZ Jobless Rate Renews All-Time Low </td>
   <td style="text-align:left;"> New Zealand's unemployment rate decreased to an all-time low of 3.2 percent in the fourth quarter of 2021, from 3.4 percent in the previous quarter, and below market expectations of 3.4 percent. “The labour market continued to show the tightness we saw in the September 2021 quarter, with both unemployment and underutilisation rates remaining low,” work and wellbeing statistics senior manager Becky Collett said. The seasonally adjusted number of employed people remained relatively steady over the quarter, rising by 3,000 people to 2,831,000. The labor force participation rate edged down to 71.1 percent from 71.2 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/labour-costs </td>
   <td style="text-align:left;"> 2022-02-02 05:53:51 </td>
   <td style="text-align:left;"> New Zealand Labour Costs Rise Further </td>
   <td style="text-align:left;"> New Zealand's annual wage inflation, as measured by the labor cost index, rose by 2.8 percent in the fourth quarter of 2021, accelerating from a 2.4 percent increase in the prior period. Public sector wages advanced 3.1 percent, up from a 2.0 percent gain in the previous quarter while private-sector wages rose 2.5 percent, quickening from 2.2 percent last quarter. On a quarterly basis, wages increased 0.7 percent, following a 0.8 percent rise in the prior period. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-01/barclays-led-bank-group-stuck-with-300-million-of-covis-debt?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-02 05:50:37 </td>
   <td style="text-align:left;"> Barclays-Led Bank Group Stuck With $300 Million of Covis Debt </td>
   <td style="text-align:left;"> Lisa Lee                                                                                                                                                                                                                                                                                                                                                                                                                           ,  and Laura Benitez                                                                                                                                                                                                                                                                                                                                                                                                                 , A group of banks led by Barclays Plc has been stuck with $300 million of loans to Covis Pharmaceuticals Inc. that they can’t readily sell, signaling that even in the relatively strong market for the debt, signs of cooling are emerging.                                                                                                                                                                                        , The loans are part of a $1.2 billion financing package tied to an acquisition that has been struggling for days because of investors’ concerns about future profit at the company owned by private equity firm Apollo Global Management Inc. The group also includes HSBC Holdings Plc, Mizuho Financial Group Inc., Mitsubishi UFJ Financial Group Inc., BNP Paribas SA and Royal Bank of Canada, who are bookrunners on the sale. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/business/2022/02/01/ioc-executive-director-winter-olympics-beijing-qmb.cnnbusiness </td>
   <td style="text-align:left;"> 2022-02-02 05:49:11 </td>
   <td style="text-align:left;"> Beijing Olympics 'feel safe' says IOC director  - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/01/stocks-making-the-biggest-moves-after-hours-alphabet-amd-paypal-and-more.html </td>
   <td style="text-align:left;"> 2022-02-02 05:43:27 </td>
   <td style="text-align:left;"> Stocks making the biggest moves after hours: Alphabet, AMD, PayPal and more </td>
   <td style="text-align:left;"> , Check out the companies making headlines after the bell:                                                                                                                                                                                                                                                                                                                           , Alphabet — Shares of the Google-parent rose more than 7% in extended trading after the company beat on the top and bottom lines for its quarterly results. The technology giant earned $30.69 per share on revenue of $75.33 billion. Wall Street expected earnings of $27.34 on revenue of $72.17 billion, according to Refinitiv. Alphabet also announced a 20-for-1 stock split., Starbucks — Shares of the worldwide coffee chain dipped more than 4% in after-hours trading after Starbucks reported quarterly earnings that came in below Wall Street's forecast, dragged lower by higher costs. Starbucks earned 72 cents per share, while analysts were expecting 80 cents per share, according to Refinitiv. Revenue, however, topped estimates.               , General Motors — The automaker reported mixed quarterly results, earning $1.35 per share on revenue of $33.58 billion. Wall Street expected earnings of $1.19 per share on revenue of $34.01 billion, according to Refinitiv. The company also said it expects to generate a 2022 operating profit of between $13 billion and $15 billion, in line with expectations.              , Advanced Micro Devices — Shares of the chip maker rose 9% after hours on a top- and bottom-line quarterly beat. AMD earned 92 cents per share on revenue of $4.83 billion. Wall Street expected earnings of 76 cents per share on revenue of $4.53 billion, according to Refinitiv. AMD also issued strong first-quarter and full-year revenue guidance.                           , PayPal — Shares of the payments giant tanked 14% after hours following disappointing first-quarter and full-year guidance. PayPal sees first-quarter EPS of 87 cents, compared with Wall Street consensus of $1.16 per share, according to Refinitiv. PayPal reported earnings about in line and revenue above expectations for the fourth quarter.                                , Electronic Arts — Shares of the video game company fell roughly 2.5% after the bell following its quarterly earnings report. Electronic Arts reported GAAP earnings of 23 cents per share, which was not comparable to estimates. Its quarterly revenue of $2.58 billion fell below Wall Street projections.                                                                       , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                             , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                             , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                   , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                   , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                 , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/api-data-reportedly-show-weekly/story.aspx?guid={2F79085B-B327-4B1C-BD37-3435BF974E45}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-02 05:41:57 </td>
   <td style="text-align:left;"> API data reportedly show a weekly U.S. supply fall for crude, sharp rise for gasoline - MarketWatch </td>
   <td style="text-align:left;"> The American Petroleum Institute reported late Tuesday that U.S. crude supplies fell by 1.6 million barrels for the week ended Jan. 28, according to sources. The API, however, also reportedly showed a weekly inventory climb of 5.8 million barrels for gasoline, while distillate supplies decline by 2.5 million barrels. Crude stocks at the Cushing, Okla., delivery hub edged down by 1 million barrels last week, sources said. Inventory data from the Energy Information Administration will be released Wednesday. On average, the EIA is expected to show crude inventories rose by 1.1 million barrels, according to a survey of analysts conducted by S&amp;P Global Platts. The survey also calls for a weekly supply rise of 1.7 million barrels for gasoline and an inventory decrease of 1 million barrels for distillates. Oil prices were little changed in the electronic trading session after the API data. March West Texas Intermediate crude 
        CLH22,
        +0.42%
       was at $88.28 a barrel in electronic trading, after settling Tuesday at $88.20 on the New York Mercantile., The viral word-game sensation is going corporate after it was scooped up by New York Times Co. NYT for an amount "in the low seven figures."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/bipartisan-group-of-senators-send-letter-supporting-bill-cracking-down-on-big-tech-china-control-of-app-marke </td>
   <td style="text-align:left;"> 2022-02-02 05:33:49 </td>
   <td style="text-align:left;"> Chinese human rights activists back bill to crack down on Big Tech, China app market control </td>
   <td style="text-align:left;"> Sen. Marsha Blackburn, R-Tenn., on Instagram implementing new controls ahead of Capitol Hill hearing, cracking down on Big Tech, Biden's meeting with Putin and the Military Defense Authorization Act.                                                                                                                                                                                                                                                                                                             , Chinese human rights groups and activists have sent a letter to the Senate Judiciary Committee announcing support for a bipartisan bill that would rein in the grip that Big Tech and China have on app markets.                                                                                                                                                                                                                                                                                                    , "We write as Chinese human rights activists, pro-democracy movements, national security experts, and members of persecuted religious communities to share our deep concerns with Apple’s use of its monopolistic dominance and its collusion with the Chinese government to stifle freedom of expression in China," the letter, written in support of the bipartisan Open App Markets Act and signed by dozens of human rights activists and organizations, states.                                                 , "As the Committee considers legislation to rein in the abuses of tech firms, we encourage it to help dissenting voices and efforts to offer privacy and security tools in China through protecting the right to sideload, as included in the Open App Markets Act."                                                                                                                                                                                                                                                 , The bill is a relatively rare bipartisan effort introduced by Sens. Richard Blumenthal, D-Conn., Marsha Blackburn, R-Tenn., and Amy Klobuchar, D-Minn.                                                                                                                                                                                                                                                                                                                                                              , This March 19, 2018, file photo shows Apple's App Store app in Baltimore.                                                                                                                                                                                                                                                                                                                                                                                                                                           , CONSERVATIVE GROUPS ASK SENATORS TO KEEP APP MARKET OPEN                                                                                                                                                                                                                                                                                                                                                                                                                                                            , The letter includes examples of Apple cooperating with Chinese censorship, including blocking apps that provide support to Christians, supporters of democracy in Hong Kong, as well as the Uyghur and Tibetan community.                                                                                                                                                                                                                                                                                           , "While our organizations have decades of expertise fight back against China’s repression, Apple’s complete dominance over iOS blocks us from offering tools to bypass censorship, prevent spying, and promote democracy," the letter says.                                                                                                                                                                                                                                                                          , "Our pleas and campaigns for Apple to do the right thing have been ignored by Apple’s leadership. If we were allowed to provide apps outside of the censored App Store, also known as sideloading, we would be able finally offer Chinese communities with tools to defeat the Great Firewall, such as Ultrasurf, Psiphon, and FreeGate. The Open App Markets Act’s protections for sideloading would help us open up the world to hundreds of millions more Chinese people living under repression aided by Apple.", The bill, which its sponsors argue "would set fair, clear, and enforceable rules to protect competition and strengthen consumer protections within the app market," will have a markup hearing on Thursday before being sent to the Senate floor.                                                                                                                                                                                                                                                                   , "Big Tech giants are forcing their own app stores on users at the expense of innovative start-ups," Blackburn said in a press release. "My colleagues and I are committed to ensuring U.S. consumers and small businesses are not punished by Big Tech giants like Apple and Google. American consumers should be able to benefit from a competitive app store marketplace and choose the products that suit their needs."                                                                                          , Google headquarters is seen in Mountain View, California, United States on Oct. 28, 2021. (Tayfun Coskun/Anadolu Agency via Getty Images / Getty Images)                                                                                                                                                                                                                                                                                                                                                            , Blumenthal added in the press release that Apple and Google have "reigned over the multi-billion app market for years, restricting consumer choice and squashing competitors."                                                                                                                                                                                                                                                                                                                                      , SOROS CALLS CHINA'S XI JINPING 'THE GREATEST THREAT THAT OPEN SOCIETIES FACE TODAY’                                                                                                                                                                                                                                                                                                                                                                                                                                 , "There is clear, growing bipartisan momentum for the Open App Markets Act to break their ironclad grip, open the app economy to new competitors, and give users more control over their own devices," the Connecticut Democrat said.                                                                                                                                                                                                                                                                                , The legislation, first introduced in August, also has the support of Sen. Marco Rubio, R-Fla., Sen.  Cynthia Lummis, R-Wyo., Sen. Cory Booker, D-N.J., and Lindsey Graham, R-S.C.                                                                                                                                                                                                                                                                                                                                   , Sen. Marsha Blackburn (R-TN) questions Head of Instagram Adam Mosseri during a Senate Commerce, Science, and Transportation Committee hearing. (Drew Angerer/Getty Images / Getty Images)                                                                                                                                                                                                                                                                                                                           , Conservative policy organizations have urged the Senate to pass the bill and have attempted to make the case that it will allow app developers to tell consumers about lower prices and competitive offers, prevent side loading, open opportunities for startup apps and third-party app stores, and prevent app stores from taking advantage of developers.                                                                                                                                                       , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , "Gatekeeper control over [iOS and Android] operating systems and their app stores allow these two companies, Apple and Alphabet (Google), which have a combined market capitalization of more than $4 trillion, to exclusively dictate — without checks and balances — the rules of the road for app developers," a group of organizations, led by the American Principles Project, said in a letter to the Senate earlier this week.                                                                               , "This monopoly power stifles innovation and competition, hurts consumers and small businesses and creates an unequal playing field where some app developers are required to pay a 30 percent tax."                                                                                                                                                                                                                                                                                                                 , Eight out of ten app developers support the passage of the Open App Markets Act, according to data from the Coalition for App Fairness.                                                                                                                                                                                                                                                                                                                                                                             , Apple and Google did not immediately respond to a request for comment from Fox News </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/gild:us </td>
   <td style="text-align:left;"> 2022-02-02 05:30:16 </td>
   <td style="text-align:left;"> Gilead Sciences earnings below expectations at 0.69 USD </td>
   <td style="text-align:left;"> Gilead Sciences (GILD) released earnings per share at 0.69 USD, compared to market expectations of 1.58 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/democratic-sen-lujan-new-mexico/story.aspx?guid={FF2F9B7D-1146-4B24-B880-CFDD6978B9DA}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-02 05:28:55 </td>
   <td style="text-align:left;"> Democratic Sen. Lujan of New Mexico suffers stroke but expected to make 'full recovery'  - MarketWatch </td>
   <td style="text-align:left;"> Sen. Ben Ray Lujan, a New Mexico Democrat, suffered a stroke Thursday but is expected to make a "full recovery," his office said in a statement. The senator underwent decompressive surgery to ease swelling once the stroke was discovered, the statement said. Lujan's absence from the Senate means there will be only 49 senators in the Democratic caucus. That would make moving any nominees difficult. However, Utah Republican Sen. Mitt Romney is out this week with COVID, noted a Politico reporter, so the party breakdown would remain the same until next week.  , Workers will pay for the Fed's fight against inflation                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Robert Schroeder is the Washington bureau chief for MarketWatch. Follow him on Twitter @mktwrobs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/lifestyle/cedar-fair-seaworld-unsolicited-offer </td>
   <td style="text-align:left;"> 2022-02-02 05:27:30 </td>
   <td style="text-align:left;"> Cedar Fair reviewing SeaWorld's unsolicited offer </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.
                                                                                                                                                                                                                                                                                                                                                            , Sandusky, Ohio-based theme park operator Cedar Fair says it is carefully reviewing and considering an unsolicited, non-binding buyout proposal from SeaWorld Entertainment.                                                                                                                                                                                                                                  , SONY BUYING HALO, DESTINY VIDEO GAME MAKER BUNGIE IN $3.6B DEAL                                                                                                                                                                                                                                                                                                                                              , Cedar Fair noted in a press release on Tuesday that it is consulting with its financial and legal advisers, Perella Weinberg Partners L.P. and Weil, Gotshal &amp; Manges, to determine the best course of action in the interest of its shareholders.                                                                                                                                                           , Bloomberg, the first to report the news, said that SeaWorld made a bid of around $60 per share, citing people familiar with the matter. Representatives for both SeaWorld and Cedar Fair declined to comment.                                                                                                                                                                                                , Shares of Cedar Fair finished Tuesday's trading session at $56.25 apiece, up more than 13%, while SeaWorld shares closed up about 2% at $61.12 apiece.                                                                                                                                                                                                                                                       , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                      , Cedar Fair owns and operates 13 properties, including 11 amusement parks, four separately gated outdoor water parks, resort accommodations totaling more than 2,300 rooms and more than 600 luxury RV sites. The company's parks include Cedar Point, California's Great America, Knotts Berry Farm, Valleyfair, Carowinds, Kings Dominion, Kings Island and Dorney Park.                                    , The company, which has been recovering from coronavirus pandemic-induced theme park closures, recently reported total net income of $148 million for the third quarter of 2021, compared to $190 million during the same period in 2019, and record third quarter net revenue of $753 million. Third quarter attendance levels at its parks reached approximately 82% of 2019 levels during the same period. , Millennium Force, a ride at Cedar Point in Sandusky, Ohio, keeps you screaming after its 200 plus drop at the beginning of the ride.  (Tricia Spaulding/Lexington Herald-Leader/Tribune News Service via Getty Images / Getty Images)                                                                                                                                                                        , Meanwhile, SeaWorld posted third quarter net income of $102.1 million and revenue of $521.2 million, up 4.2% and 10% compared to the same period in 2019, respectively. Though SeaWorld's third quarter park attendance increased by 5.7 million guests year-over-year to 7.2 million, attendance was down 11% compared to the third quarter of 2019.                                                        , Tourists visit SeaWorld San Antonio in Texas, the United States, on June 19, 2020. (Xinhua/Ma Lie via Getty Images)                                                                                                                                                                                                                                                                                          , Tuesday's announcement comes after Cedar Fair previously rejected a $4 billion takeover offer from Six Flags Entertainment Corporation in 2019. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-01/alphabet-declares-20-for-1-stock-split-kz4mpxwm?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-02 05:24:47 </td>
   <td style="text-align:left;"> Alphabet Seeks More Investors in 20-for-1 Stock Split </td>
   <td style="text-align:left;"> Nico Grant                                                                                                                                                                                             ,  and Divya Balji                                                                                                                                                                                       , Alphabet Inc. announced a 20-for-1 stock split in the form of a one-time special stock dividend, aiming to draw a wider audience for its shares.                                                       , “The reason for the split is it makes our shares more accessible,” Ruth Porat, Alphabet’s chief financial officer, said in a conference call with television anchors. “We thought it made sense to do.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/01/politics/olympics-china-burner-phones/index.html </td>
   <td style="text-align:left;"> 2022-02-02 05:23:36 </td>
   <td style="text-align:left;"> FBI urges Olympic athletes to leave personal phones at home ahead of Beijing games - CNNPolitics </td>
   <td style="text-align:left;"> Washington (CNN)The FBI is urging Olympic athletes to leave their personal cell phones at home and instead take burner phones to the Beijing Winter Olympics this month, citing the potential for "malicious cyber activities."                                                                                                                                                          , "The FBI urges all athletes to keep their personal cell phones at home and use a temporary phone while at the games. The National Olympic Committees in some Western countries are also advising their athletes to leave personal devices at home or use temporary phones due to cybersecurity concerns at the Games," the agency said in a notice.                                      , While not aware of "any specific cyber threat against the Olympics" the FBI added that it's important that those at the games be "vigilant and maintain best practices in their network and digital environments."                                                                                                                                                                       , The warning comes amid rising concerns by US national security officials about Chinese espionage and intellectual property theft -- and as intelligence officials have publicly warned that China has created an advanced techno-surveillance state within its borders, blanketed by cameras, facial recognition and other technology.                                                   , Counterintelligence officials have long warned that US state and local officials, as well as members of business and academia, who travel to China face the risk of having their personal devices hacked. The FBI routinely provides so-called defensive briefings to Americans it considers to be at risk of becoming victims of Chinese espionage efforts.                             , The FBI currently has open over 2,000 counterintelligence investigations into alleged efforts by Beijing to steal American information of technology, according to FBI Director Chris Wray.                                                                                                                                                                                              , "When we tally up what we see in our investigations, there is just no country that presents a broader threat to our ideas, our innovation, and our economic security than China," Wray said during public remarks at the Ronald Reagan Presidential Library on Monday.                                                                                                                   , While US athletes are allowed to compete, the Biden administration will not be sending government officials to the games. The same policy applies for the Paralympic Games, which are also taking place in Beijing. The White House is looking to send a "clear message" that the human rights abuses in China mean there cannot be "business as usual," Psaki told reporters last year. , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ea:us </td>
   <td style="text-align:left;"> 2022-02-02 05:20:36 </td>
   <td style="text-align:left;"> Electronic Arts EA earnings below expectations at 0.23 USD </td>
   <td style="text-align:left;"> Electronic Arts EA (EA) released earnings per share at 0.23 USD, compared to market expectations of 3.21 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/gm:us </td>
   <td style="text-align:left;"> 2022-02-02 05:19:59 </td>
   <td style="text-align:left;"> General Motors earnings above expectations at 1.35 USD </td>
   <td style="text-align:left;"> General Motors (GM) released earnings per share at 1.35 USD, compared to market expectations of 1.13 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/cb:us </td>
   <td style="text-align:left;"> 2022-02-02 05:19:21 </td>
   <td style="text-align:left;"> Chubb earnings above expectations at 3.81 USD </td>
   <td style="text-align:left;"> Chubb (CB) released earnings per share at 3.81 USD, compared to market expectations of 3.29 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/sbux:us </td>
   <td style="text-align:left;"> 2022-02-02 05:19:09 </td>
   <td style="text-align:left;"> Starbucks earnings below expectations at 0.72 USD </td>
   <td style="text-align:left;"> Starbucks (SBUX) released earnings per share at 0.72 USD, compared to market expectations of 0.80 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/amd:us </td>
   <td style="text-align:left;"> 2022-02-02 05:18:51 </td>
   <td style="text-align:left;"> Advanced Micro Devices earnings above expectations at 0.92 USD </td>
   <td style="text-align:left;"> Advanced Micro Devices (AMD) released earnings per share at 0.92 USD, compared to market expectations of 0.76 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/pypl:us </td>
   <td style="text-align:left;"> 2022-02-02 05:18:22 </td>
   <td style="text-align:left;"> PayPal earnings below expectations at 1.11 USD </td>
   <td style="text-align:left;"> PayPal (PYPL) released earnings per share at 1.11 USD, compared to market expectations of 1.12 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/goog:us </td>
   <td style="text-align:left;"> 2022-02-02 05:17:57 </td>
   <td style="text-align:left;"> Alphabet earnings above expectations at 30.69 USD </td>
   <td style="text-align:left;"> Alphabet (GOOG) released earnings per share at 30.69 USD, compared to market expectations of 27.80 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/01/americas/quebec-drops-unvaxxed-tax-plan/index.html </td>
   <td style="text-align:left;"> 2022-02-02 05:05:19 </td>
   <td style="text-align:left;"> Quebec drops 'unvaxxed tax' plan - CNN </td>
   <td style="text-align:left;"> (CNN)Quebec's premier said Tuesday his province would scrap any attempt to tax people who haven't gotten their Covid-19 vaccinations, as his government proposed just weeks ago, citing concerns about dividing people and straining their mental health.                     , "I have to make sure that I protect the health of Quebecers, but I have also to protect the peace in our society," said Quebec Premier François Legault during a news conference in Quebec City.                                                                               ,                                                                                                                                                                                                                                                                                , Legault acknowledged that it seemed his government's proposal to charge the unvaccinated a yearly "health contribution" for refusing the get the shots had already increased the number of people booking first-time vaccinations, but he said it was time to abandon the idea., "In the last week or so there's an increase in the reaction of people. They are angry more than ever," he said. "I don't like to see Quebecers divided like we're seeing."                                                                                                     , Legault underscored that Quebecers have generally adhered to public health measures, and the province now has some of the highest vaccination rates in the world.                                                                                                              , He added that balancing mental and physical health was tough and said he is taking people's frustration and anger with health restrictions into consideration.                                                                                                                 , While nearly 90% of eligible Quebecers have received at least one dose of a Covid-19 vaccine, the unvaccinated remain a burden on the province's public health system, the government has said.                                                                                , The majority of patients in Quebec hospitals remain unvaccinated, public health officials said in January.                                                                                                                                                                     , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-01/pummeled-canopy-growth-tilray-rebound-on-renewed-banking-push?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-02 04:37:50 </td>
   <td style="text-align:left;"> Pot Stocks Canopy, Tilray Rebound on Renewed Legislative Push </td>
   <td style="text-align:left;"> Cristin Flanagan                                                                                                                                                                                                                                                                                                                                                                                             , After falling out of favor, pot stocks including Canopy Growth Corp. and Tilray Brands Inc. are rebounding in a risk-on rally, with the renewed push to get cannabis legislation passed further helping fuel the rally.                                                                                                                                                                                      , Canopy, which sells Martha Stewart-branded CBD gummies, has climbed 25% over the past three sessions while Tilray advanced 19%. Investors are weighing prospects for legislation known as the Secure and Fair Enforcement, or SAFE, Banking Act that would make it easier for cannabis companies to do business as a Colorado representative pledged to renew efforts to get approval before his retirement.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-02 04:32:00 </td>
   <td style="text-align:left;"> Wall Street Kicks Off February on the Positive Note </td>
   <td style="text-align:left;"> US stocks extended gains on the first trading day of February as investors continued to digest prospects of a more hawkish monetary policy from the Fed and followed the earnings season. The Dow Jones added more than 250 points, the S&amp;P rose 0.7%, and the Nasdaq Composite gained 0.7%. On the corporate front, bank shares lead the gains with Goldman Sachs 2% higher and Jp Morgan 1.5% up. Also, big tech performed well with Netflix surging almost 6% while Alphabet and GM are due to report today. On the data front, the ISM Manufacturing PMI pointed to a further slowdown in factory activity in January, and JOLTS job openings exceeded market forecasts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-02 04:30:04 </td>
   <td style="text-align:left;"> The Dow Jones Index is up by 0.61% </td>
   <td style="text-align:left;"> United States Stock Market is picking up 215 points. Gains are led by Boeing (9.37%), Salesforce.com (4.12%) and Walt Disney (4.03%). Biggest losers are UnitedHealth (-1.51%), Walgreens Boots Alliance (-1.12%) and Microsoft (-1.09%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-01/cme-will-launch-more-battery-metals-contracts-as-demand-surges?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-02 04:23:50 </td>
   <td style="text-align:left;"> CME to Launch More Battery-Metals Contracts as Demand Surges </td>
   <td style="text-align:left;"> Joe Deaux                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , CME Group Inc., one of the largest commodity exchanges in the world, expects to launch a suite of battery-metal products in the future as it works toward securing its place as the go-to home for trading of key materials needed in the global energy transition.                                                                                                                                                                                                                                                                                                      , The exchange last year saw a surge of interest in contracts of metals like cobalt and lithium that are critical to lithium-ion batteries needed to power electric vehicles and energy grid storage systems, according to CME’s global head of metals products, Young-Jin Chang. The bulk of interest is coming from commercial clients and hedgers who actively buy and sell the physical metals, she said, indicating that the exchange is gaining traction from more and more key players that still largely transact through handshake deals and long-dated contracts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/platinum </td>
   <td style="text-align:left;"> 2022-02-02 04:23:00 </td>
   <td style="text-align:left;"> Platinum Prices Rises to Near 9-Week-High </td>
   <td style="text-align:left;"> Platinum futures rose to $1,030 per troy ounce in the first week of February, getting closer to a 9-weeks-high hit on January 20th as the supply remains tight and demand is set to rise. The car production is set to recover sharply as chips shortage eases and economies recover.  Also, many automakers are switching from palladium to platinum usage in autocatalysts to cut costs. Meanwhile, major producers, Sibanye-Stillwater and Anglo American Platinum, have revised their outlook for their production, their mining supply over the next few years, according to World Platinum Investment Council director of research Trevor Raymond. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/pjt-partners-stock-slides-earnings/story.aspx?guid={A3D99A55-015B-443C-B14A-D9570C36B697}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-02 04:13:56 </td>
   <td style="text-align:left;"> PJT Partners stock slides on earnings miss - MarketWatch </td>
   <td style="text-align:left;"> PJT Partners Inc. 
        PJT,
        -8.02%
       shares fell 9.8% on Tuesday after the advisory firm's fourth-quarter earnings of $1.52 a share fell short of the Wall Street estimate of $1.72 a share in a survey of analysts by FactSet. PJT's revenue of $313.3 million also missed the analyst target of $339 million. PJT said its advisory revenue for restructuring services fell more than expected due to "a challenging market backdrop for restructuring activity following an extraordinary run up in 2020." It's the biggest share drop for PJT since March 18, 2020, when the stock fell 17.4%. On a call with analysts, PJT chairman and CEO Paul Taubman said he remains cautious about the firm's restructuring business going forward. "We certainly are seeing increasing stress building in the system, and we're seeing companies having more difficulty in refinancing," he said. "We're seeing companies more nervous about their business prospects and that to me, is an essential element for a change in restructuring. But I certainly think that the headwinds are behind us. When we get the tailwinds. It will happen. I'm just not yet prepared to say it's going to happen soon." , Here's what you need to know.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Steve Gelsi covers banking and cannabis as a Senior Reporter for MarketWatch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-02-02 04:00:59 </td>
   <td style="text-align:left;"> FTSE 100 above 7550 </td>
   <td style="text-align:left;"> FTSE 100 rose above 7550 points. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-02-01/bridgewater-sees-market-turmoil-on-aggressive-fed-tightening?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-02-02 03:58:20 </td>
   <td style="text-align:left;"> Bridgewater Sees Market Turmoil on ‘Aggressive’ Fed Tightening </td>
   <td style="text-align:left;"> Ye Xie                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Investors may be underestimating the need for “aggressive” monetary tightening from the Federal Reserve and other central banks to combat inflation, resulting in “significant risks” for markets, according to Bridgewater Associates.                                                                                                                                                                                                                                          , Following hawkish comments from the Fed Chair Jerome Powell last week, investors have brought forward expectations of tightening, pricing in five quarter-point rate hikes this year. Further out, however, they’re predicting fewer rate increases, anticipating the Fed will end the cycle with the policy rate at about 1.65% and long-term inflation expectations anchored around 2%. Consumer prices surged 7% in December from a year earlier, the fastest pace since 1982. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/white-house-china-no-mention-bill </td>
   <td style="text-align:left;"> 2022-02-02 03:53:26 </td>
   <td style="text-align:left;"> White House does not mention 'China' in statement supporting Dem's China anti-competition bill </td>
   <td style="text-align:left;"> Mark Clifford, president of the Committee for Freedom in Hong Kong, argues continued threats from China are a 'real, clear and present danger' that won't stop at Hong Kong.                                                                                                                                                                                                                                                                                                                                                                   , The White House released a statement in support of House Speaker Nancy Pelosi's proposed COMPETES legislation, which aims to take a harder line in financial and manufacturing relations between the U.S. and China. However, the White House's two-page statement of support did not once use the word "China" – a concerning oversight for many Republicans who claim the America COMPETES Act of 2022 is all bark and no bite.                                                                                                              , "It's disgraceful the [White House] Statement of Administration Policy on the bill [Pelosi] claims is a counter China bill doesn't even contain the word China. This is proof COMPETES is not a serious effort to combat the generational threat posed by the [Chinese Communist Party]," said Rep. Michael McCaul, R-Texas, the ranking member on the House Foreign Affairs Committee.                                                                                                                                                        , OLYMPIC CORPORATE SPONSORS STICKING TO DEALS DESPITE BOYCOTT CALLS AGAINST CHINA                                                                                                                                                                                                                                                                                                                                                                                                                                                               , The America COMPETES Act of 2022 (America Creating Opportunities for Manufacturing, Pre-Eminence in Technology, and Economic Strength) has been championed by Pelosi, D-Calif., and other Democrats as a bipartisan push for more accountability in U.S.-China relations.                                                                                                                                                                                                                                                                      , However, the White House Office of Management and Budget's (OMB) statement Tuesday made little mention of competition from less-than-friendly nations such as China.                                                                                                                                                                                                                                                                                                                                                                           , "The legislation would complement the President's efforts to strengthen critical domestic supply chains," the statement reads. "It would establish a new office at the Department of Commerce to monitor, analyze, and support the resilience of our supply chains and domestic manufacturing, including through authorization of new grants, loans, and loan guarantees."                                                                                                                                                                     , The Biden administration also praised the bill's contributions to diversity, saying it "would lower barriers to inclusion and broaden opportunities for people and communities who have historically been underserved and underrepresented in science, technology, engineering, and mathematics."                                                                                                                                                                                                                                              , Democrats and the White House have championed the legislation as a bipartisan bill in response to the Senate-passed $250 billion U.S. Innovation and Competition Act (USICA), but House Republicans have claimed it's a stockpile of partisan issues. The House bill substantially cut funding allocated in the Senate USICA bill by dropping the $190 billion allocated for technology and research, as first reported Reuters. The bill instead includes $45 billion to bolster supply chains and the domestic production of critical goods. , Rep. August Pfluger, R-Texas, also criticized OMB's statement Tuesday, saying that the Biden administration and Democrats in Congress are "not serious" about combating threats.                                                                                                                                                                                                                                                                                                                                                               , "We have been in talks with House and Senate committees of jurisdiction for weeks, trying to put together a bipartisan bill that could pass Congress," McCaul told Fox News Digital last week once the bill text was released. "I would strongly urge Speaker Pelosi and other House Democrats to scrap their weak, partisan bill and work with Republicans on comprehensive legislation that will actually counter CCP aggression and that has the ability to pass both Houses of Congress.                                                   , "The Administration supports these steps to strengthen our economic competitiveness, supply chain resilience, equity and inclusivity, and leadership in science and technology," the White House statement concluded – a far cry from the aggressive swipe at Chinese economic misconduct that Republicans had hoped for.                                                                                                                                                                                                                      , House Minority Leader Kevin McCarthy, R-Calif., echoed these sentiments by calling the legislation "toothless" and claimed it would waste "billions of dollars on unrelated matters."                                                                                                                                                                                                                                                                                                                                                          , Chinese staffers adjust U.S. and Chinese flags before the opening session of trade negotiations between U.S. and Chinese trade representatives in Beijing on Feb. 14, 2019. (AP Photo/Mark Schiefelbein, Pool) (Associated Press)                                                                                                                                                                                                                                                                                                              , "The COMPETES Act isn’t serious legislation – it is a facade to cover up the Democrats’ reluctance to actually do anything to hold China accountable and their desperation to do something to distract from their domestic crises," he added.                                                                                                                                                                                                                                                                                                  , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Team USA Olympians and Paralympians will be sporting Nike apparel on the winner’s podium at the Beijing Winter Games this month, but the company is staying tight-lipped on where in the world the uniforms were manufactured.                                                                                                                                                                                                                                                                                                                 , Wang Chen, vice chairman of the standing committee of China's National People's Congress (NPC), speaks at the Great Hall of the People in Beijing, March 8, 2019. (AP Photo/Mark Schiefelbein)                                                                                                                                                                                                                                                                                                                                                 , Team USA and Nike last week unveiled the medal stand uniforms, which include light-blue hooded jackets and dark blue pants. The jackets have a Paralympic or Olympic patch on the left side, a Nike Swoosh on the right, and a vertical American flag and "USA" on the back.                                                                                                                                                                                                                                                                   , "For the official Team USA Medal Stand look in Beijing, we worked closely with the disability community, including current and former winter and summer Paralympians, in our design and testing process, and used inclusive design principles and methods to create gear that ensures every athlete who competes feels support in style from start to finish," Nike said in a press release.                                                                                                                                                   , FOX Business' Jessica Chasmar and Caitlin McFall contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/portugal/industrial-production </td>
   <td style="text-align:left;"> 2022-02-02 03:52:00 </td>
   <td style="text-align:left;"> Portugal Industrial Output Ticks Up in December </td>
   <td style="text-align:left;"> Industrial production in Portugal went up by 0.4 percent over a year earlier in December of 2021, quickening from a 0.2 percent increase in the previous month. Main upward pressure came from a rebound in manufacturing of capital goods (4.3 percent vs -1.1 percent in November); and another sustained increase in production of consumer goods (2.4 percent vs 5.0 percent), exclusive on the back of nondurable goods (2.8 percent vs 4.6 percent), as manufacturing of durables decreased (-0.2 percent vs 8.0 percent). To a lesser extent, growth received support from intermediate goods production (1.2 percent vs 3.4 percent), while the slump in energy output eased (-8.0 percent vs -13.0 percent). On a monthly basis, industrial production grew 1.8 percent, following a 1.2 percent increase in the preceding month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/rice </td>
   <td style="text-align:left;"> 2022-02-02 03:46:00 </td>
   <td style="text-align:left;"> Rice Prices Remain at 17-Month High </td>
   <td style="text-align:left;"> Chicago rough rice traded around $15.12 per hundredweight on the first day of February 2022, close to levels not seen since July of 2020 amid expectations of lower supply. Rising fertilizer costs in previous months limited the planting. Also, It is predicted that farmers will substitute the crops that are less dependent upon fertilizers, such as soybeans, or crops with more favorable financial returns, such as corn. Moreover, prices increased on the back of logistic bottlenecks that are limiting rice exports from India, the world’s biggest rice exporter. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/kazakhstan/monthly-gdp-yoy </td>
   <td style="text-align:left;"> 2022-02-02 03:43:00 </td>
   <td style="text-align:left;"> Kazakhstan GDP Grows the Most in 8-Months </td>
   <td style="text-align:left;"> Kazakhstan’s economy expanded 7.8 percent year-on-year in December of 2021, the most since April and following a 6.5 percent advance in November. Main contributions to growth came from industrial output (8.9 percent vs 6.8 percent in November), and construction works (13.9 percent vs -4.1 percent). Meanwhile, the rate of expansion eased in retail trade (6.4 percent vs 9.7 percent) and communications (11.8 percent vs 13.1 percent). On the other hand, output contracted from agricultural, forestry, and fishing activities (-0.6 percent vs -4.0 percent). On the expenditure side, fixed capital investment rose 8.1 percent, quickening from a 2.9 percent increase in November. Considering 2021 as a whole, the economy advanced 4.5 percent over the same period a year earlier. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/us-oil-futures-settle-modestly/story.aspx?guid={D26C7F94-5041-4132-A721-16046BC019A4}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-02 03:37:12 </td>
   <td style="text-align:left;"> U.S. oil futures settle modestly higher a day ahead of the OPEC+ meeting - MarketWatch </td>
   <td style="text-align:left;"> U.S. oil futures settled slightly higher on Tuesday, as traders await the outcome of Wednesday's meeting of major oil producers. OPEC+, which comprises the Organization of the Petroleum Exporting Countries and their allies, is expected to agree to a 400,000 barrel-per-day production increase for March. "When you factor in that many members are struggling to hit their quotas, oil seems poised to head higher," said Edward Moya, senior market analyst at OANDA. "Fears of disruption to supplies will remain elevated given the winter blast hitting the north and the geopolitical risks abroad," he added. West Texas Intermediate crude for March delivery 
        clh22
       edged up by a nickel, or nearly 0.1%, to settle at $88.20 a barrel on the New York Mercantile Exchange., Diners can be seen throwing punches --- and high chairs --- during the Bensalem, Pa. restaurant riot                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/denmark/manufacturing-pmi </td>
   <td style="text-align:left;"> 2022-02-02 03:22:36 </td>
   <td style="text-align:left;"> Danish Factory Activity Slows to 11-Month Low </td>
   <td style="text-align:left;"> The DILF Manufacturing PMI in Denmark declined to 60.9 in January of 2021, from a downwardly revised 63.9 in December. It was the lowest reading in the current ten-month sequence of expansion, mostly due to a slowdown in new orders (64.5 vs 70.1 in December) and in the workforce expansion pace (57.6 vs 63.3). Meanwhile, output growth was unchanged from the previous month at 60.4, while inflationary pressures persisted, as input costs increased faster (80.9 vs 80.0) although selling charges rose the least since March of last year (63.8 vs 70.9). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/tv/2022/02/01/amanpour-myanmar-sasa.cnn </td>
   <td style="text-align:left;"> 2022-02-02 03:16:36 </td>
   <td style="text-align:left;"> 'We'll never back down': Myanmar's coup, one year later - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/greece/manufacturing-pmi </td>
   <td style="text-align:left;"> 2022-02-02 02:59:01 </td>
   <td style="text-align:left;"> Greece Manufacturing PMI at 6-Month Low </td>
   <td style="text-align:left;"> The IHS Markit Greece Manufacturing PMI decreased to a six-month low of 57.9 in January of 2021, from a four-month high of 59.0 in the previous month. It was the 11th straight month of expansion in the manufacturing sector, as output, employment and new orders continued to grow sharply. A sustained uptick in client demand leading to a historically elevated rise in total sales and the second highest rise in outstanding work influenced firms to step up their hiring activity at the sharpest rate since February 2020. Meanwhile, material shortages and input delivery delays pushed cost burdens up, albeit at the slowest rate in five months, resulting in firms raising selling charges markedly. Looking forward, goods producers were the most optimistic since June of 2021 amid hopes of softer price hikes and sustained client demand in 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/colombia/manufacturing-pmi </td>
   <td style="text-align:left;"> 2022-02-02 02:45:31 </td>
   <td style="text-align:left;"> Colombia Factory Activity Growth Slows in January </td>
   <td style="text-align:left;"> The Davivienda Colombia Manufacturing PMI eased to 52.6 in January of 2021 from 53.1 in the previous month, but remained above its long-run average of 50.9 indicating a solid rate of growth. Output and new orders both increased at the slowest rate in seven months, owing to cooling demand conditions, price pressures, raw material scarcity and staff shortages. On the price front, input prices increased further at the start of 2022. Still, upbeat growth projections and efforts to clear backlogs supported hiring activity among goods producers. Looking ahead, firms forecast output growth in the coming 12 months to be supported by product diversification, marketing efforts and export opportunities. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/gold-futures-settle-back-above/story.aspx?guid={E70964C9-44A0-4992-BC82-1700CAC90B08}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-02 02:37:55 </td>
   <td style="text-align:left;"> Gold futures settle back above $1,800 for first time in nearly a week - MarketWatch </td>
   <td style="text-align:left;"> Gold prices settled higher on Tuesday for a second straight session, above the $1,800 mark for the first time in almost a week. "Gold continues to be pulled back and forth because of the ebb and flow of the U.S. bond market, as well as the strength of the U.S. dollar," said Michael Hewson, chief market analyst at CMC Markets UK. However, weakness in the currency markets Tuesday appeared to help support gold, he said. April gold 
        GCJ22,
        -0.03%
       rose $5.10, or 0.3%, to settle at $1,801.50 an ounce. That was the highest most-active contract finish since Jan. 26, FactSet data show., Here's what you need to know.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/kazakhstan/inflation-cpi </td>
   <td style="text-align:left;"> 2022-02-02 02:27:42 </td>
   <td style="text-align:left;"> Kazakhstan Inflation Rate Inches Up in January </td>
   <td style="text-align:left;"> The annual inflation rate in Kazakhstan inched up to 8.5 percent in January of 2021, from a five-month low of 8.4 percent in the previous month. Prices rose at a faster pace for transports (13.0 percent vs 12.8 percent in December); houseware (6.8 percent vs 6.3 percent); healthcare (5.4 percent vs 5.2 percent); miscellaneous goods &amp; services (6.1 percent vs 5.7 percent); restaurants &amp; hotels (6.1 percent vs 5.8 percent); and education (8.1 percent vs 7.9 percent). On the other hand, prices of food &amp; non-alcoholic beverages increased 9.9 percent, the same as in December, while those of alcoholic beverages &amp; tobacco rose less markedly (9.8 percent vs 10.3 percent). On a monthly basis, consumer prices went up 0.7 percent, slightly faster than the 0.6 percent advance in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/cedar-fairs-stock-soars-toward/story.aspx?guid={E08E06E4-142E-49F4-9540-07B1393C108E}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-02 02:27:33 </td>
   <td style="text-align:left;"> Cedar Fair's stock soars toward more-than 2-year high after confirming SeaWorld's buyout bid - MarketWatch </td>
   <td style="text-align:left;"> Shares of Cedar Fun L.P. 
        FUN,
        +13.11%
       rocketed 14.7% toward a more-than two-year high in afternoon trading Tuesday, after the amusement park operator confirmed that it had received an unsolicited buyout bid from SeaWorld Entertainment Inc. 
        SEAS,
        +2.58%.
       The company did not disclose terms of the bid, but Bloomberg, which first reported the on the bid, indicated it was for around $3.4 billion. Trading volume spiked to 4.3 million shares, compared with the full-day average of around 309,000 shares. At the current stock price, which would mark the highest close since November 2019, Cedar Fair's market capitalization would be $3.24 billion, according to FactSet. SeaWorld's stock rose 4.2% in afternoon trading. "Consistent with its fiduciary duties, and in consultation with its independent legal and financial advisors, the Cedar Fair Board of Directors will carefully review and consider the proposal to determine the course of action that it believes is in the best interest of the Company and its unitholders," the company said in a statement. "Cedar Fair unitholders do not need to take any action at this time." Cedar Fair shares have now run up 21.3% over the past three months and SeaWorld's stock has lost 4.2%, while the S&amp;P 500 
        SPX,
        +0.69%
       has eased 1.9%., Here's what the chief executive of ARK Invest had to say.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/switzerland/manufacturing-pmi </td>
   <td style="text-align:left;"> 2022-02-02 02:23:20 </td>
   <td style="text-align:left;"> Swiss Manufacturing Activity Growth Slows in January </td>
   <td style="text-align:left;"> The procure.ch and Credit Suisse Manufacturing PMI for Switzerland edged down to 63.8 in January of 2022 from the upwardly revised 64.2 in the previous month, slightly below market forecasts of 64. Decreases were seen for backlogs of work (-1.8 to 63), production (-0.1 to 58.6), delivery times (-5.4 to 85.9), stocks sold (-3.8 to 49.6), and purchasing volumes (-0.6 to 58.9). Meanwhile, improvements were recorded for employment (+1.4 to 62.4) and stocks purchased (+0.1 to 60.7). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/soros-china-xi-jinping-greatest-threat-open-societies-face </td>
   <td style="text-align:left;"> 2022-02-02 02:21:27 </td>
   <td style="text-align:left;"> Soros calls China's Xi Jinping 'the greatest threat that open societies face today’ </td>
   <td style="text-align:left;"> 'The Great U.S.-China Tech War' author Gordon Chang says Chinese president Xi Jinping is adopting Maoist ideas on military advances amid U.S.-China tensions.                                                                                                                                                                                                           , Billionaire George Soros on Monday warned that Chinese President Xi Jinping is "the greatest threat that open societies face today," and said the rise of big tech companies have "sharpened the conflict" between China and the United States.                                                                                                                         , Soros, a Hungarian-American mega-donor known for his backing of liberal causes and politicians, made remarks at the opening of a Hoover Institution panel on Monday evening, beginning by dubbing 2022 as a "critical year in the history of the world."                                                                                                                , "In a few days, China – the world’s most powerful authoritarian state – will begin hosting the Winter Olympics, and, like Germany in 1936, it will attempt to use the spectacle to score propaganda victory for its system of strict controls," Soros said. "We are at, or close to, important decisions that will determine the direction in which the world is going.", GEN. KEANE WARNS CHINA, RUSSIA'S BUDDING RELATIONSHIP ‘VERY CONCERNING’                                                                                                                                                                                                                                                                                                 , Soros pointed to elections across Europe, and Russian President Vladimir Putin as he considers whether to invade Ukraine, calling them "developments" that "will help determine the fate of Europe."                                                                                                                                                                    , George Soros speaks at the World Economic Forum annual meeting on Jan. 23, 2020, in Davos, Switzerland.  (Fabrice Coffrini/AFP via Getty Images / Getty Images)                                                                                                                                                                                                         , In October, Soros noted, China will decide whether President Xi Jinping should be given a third term in office as party general secretary, and the United States will hold a "crucial midterm election in November."                                                                                                                                                    , "In an open society, the role of the state is to protect the freedom of the individual," Soros said. "In a closed society the role of the individual is to serve the rulers of the state."                                                                                                                                                                              , "As the founder of the Open Society Foundations, obviously I am on the side of open societies," he continued. "But the most important question now is, which system is going to prevail?"                                                                                                                                                                               , Mark Clifford, president of the Committee for Freedom in Hong Kong, argues continued threats from China are a 'real, clear and present danger' that won't stop at Hong Kong.                                                                                                                                                                                            , Soros said President Biden has "generally adopted the right policies."                                                                                                                                                                                                                                                                                                  , With regard to Taiwan, Soros said Biden has "made it clear" that if Xi uses force against Taiwan, China will have to confront the AUKUS alliance. But Soros said Xi is "determined to assert China’s sovereignty over Taiwan by force if necessary."                                                                                                                    , REPUBLICANS SLAM PELOSI OVER CHINA BILL PROPOSAL: ‘NOT SERIOUS ABOUT CONFRONTING THE CCP’                                                                                                                                                                                                                                                                               , "He is devoting enormous resources to armaments. Recently he surprised the world by demonstrating a hypersonic controllable missile," Soros said, noting that the U.S. "has nothing comparable and doesn’t intend to compete."                                                                                                                                          , "I think that is the right policy because Xi Jinping’s hypersonic achievement doesn’t change the balance of mutually assured destruction that will stop the enemies from attacking each other," he continued. "The missile is merely a propaganda victory."                                                                                                             , President Biden meets virtually with Chinese President Xi Jinping from the Roosevelt Room of the White House on Nov. 15, 2021. (AP Photo/Susan Walsh / AP Newsroom)                                                                                                                                                                                                     , Soros, added, though, that "war between the U.S. and its enemies has become more plausible and that is not a pleasant subject to contemplate."                                                                                                                                                                                                                          , "When I embarked on what I call my political philanthropy in the 1980s, American superiority was not in question. That is no longer the case," Soros said. "Why?"                                                                                                                                                                                                       , Soros pointed to artificial intelligence and the rise of social media and tech platforms, saying they have "produced very profitable companies that have become so powerful that nobody can compete with them, but they can compete with each other."                                                                                                                   , "These companies have come to dominate the global economy," Soros said, adding that "their reach extends to every corner of the world."                                                                                                                                                                                                                                 , Soros said its development has had "far-reaching political consequences," and has "sharpened the conflict between China and the United States and has given it an entirely new dimension."                                                                                                                                                                              , BILLIONAIRE GEORGE SOROS DISHING OUT $125M TO HELP DEMOCRATS IN NOVEMBER'S MIDTERMS                                                                                                                                                                                                                                                                                     , "China has turned its tech platforms into national champions; the U.S. is more hesitant to do so because it worries about their effect on the freedom of the individual," Soros said, adding that the "different attitudes shed new light on the conflict between the two systems of governance that the U.S. and China represent."                                     , As for Xi, Soros slammed his leadership, saying he has reinterpreted the Chinese Communist Party’s history in a way that would "lead to appointing him for at least another term."                                                                                                                                                                                      , "Xi Jinping has many enemies," Soros said, adding that he is "introducing a system of governance that is inherently superior to liberal democracy."                                                                                                                                                                                                                     , "He rules by intimidation and nobody dares to tell him what he doesn’t want to hear," Soros said, noting that makes it "difficult to shake his beliefs even as the gap between his beliefs and reality has grown ever wider."                                                                                                                                           , CLICK HERE TO GET THE FOX NEWS APP                                                                                                                                                                                                                                                                                                                                      , Soros criticized Xi for his leadership, including in China’s real estate market, the Olympics and COVID-19 vaccines.                                                                                                                                                                                                                                                    , "He tried to impose total control, but he failed," Soros said, claiming there is "strong opposition" to him within the CCP.                                                                                                                                                                                                                                             , "It is to be hoped that Xi Jinping may be replaced by someone less repressive at home and more peaceful abroad," Soros said. "This would remove the greatest threat that open societies face today, and they should do everything within their power to encourage China to move in the desired direction."                                                              , Fox News' Adam Shaw contributed to this report.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/home-depot-hiring-labor-shortage </td>
   <td style="text-align:left;"> 2022-02-02 02:11:09 </td>
   <td style="text-align:left;"> Labor shortage has Home Depot pushing 'accelerated hiring process' </td>
   <td style="text-align:left;"> FOX Business’ Madison Alworth discusses red states like Texas, Arizona, Idaho, and Utah recovering all jobs lost during the COVID-19 pandemic.                                                                                                                                                                                   , Home Depot has launched a new "accelerated hiring process" aimed at providing prospective applicants with a job offer at the home improvement retailer within as little as a day in an effort to combat ongoing labor shortages.                                                                                                 , JOB OPENINGS REMAINED ELEVATED IN DECEMBER AS AMERICANS CONTINUED TO QUIT                                                                                                                                                                                                                                                        , The company, which is hosting a virtual Spring Career Day event on Feb. 16, plans to hire more than 100,000 associates ahead of its busy spring season for flexible, full-time and part-time positions in areas including customer service and sales, store support, freight, merchandising and warehouse.                       , "In today’s climate, jobseekers are shopping for the best opportunity," Home Depot vice president of global talent acquisition Eric Schelling said in a statement. "At The Home Depot, they’ll find a company that offers much more than a job and a paycheck."                                                                  , An employee assists customers at a Home Depot Inc. store in Louisville, Kentucky, on Feb. 25, 2019.  (Luke Sharrett/Bloomberg via Getty Images / Getty Images)                                                                                                                                                                   , Home Depot offers a variety of health and personal benefits to employees, including upskilling programs, tuition reimbursement, paid family leave, back-up dependent care, a company performance-based cash bonus program, a 401(k) savings plan with company match, a discounted company stock purchase program and more.       , Over the past three years, Home Depot store associates have received more than $1 billion in Success Sharing awards, according to the company.                                                                                                                                                                                   , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                          , The announcement comes as 4.3 million Americans, or about 2.9% of the workforce, quit their jobs in December, down from a fresh high of 4.5 million in November, but well above the pre-pandemic level of about 3.6 million. Meanwhile, the number of job openings rose to 10.9 million by the end of December.                  , The data precedes the release of the January jobs report on Friday morning, which is expected to show that employers hired just 153,000 new workers last month as the highly contagious omicron variant sidelined millions of Americans from the workforce. The unemployment rate, meanwhile, is expected to hold steady at 3.9%., Fox Business' Megan Henney contributed to this report </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/01/africa/guinea-bissau-coup-attempt-intl/index.html </td>
   <td style="text-align:left;"> 2022-02-02 02:09:39 </td>
   <td style="text-align:left;"> Guinea-Bissau attempted coup: Guinea-Bissau's president says coup attempt has failed, government is in control - CNN </td>
   <td style="text-align:left;"> (CNN)Guinea-Bissau's President Umaro Sissoco Embaló said an attempted military coup to overthrow him had failed on Tuesday, and called for calm across the country during a national address broadcast on Radio TV Bantaba.                                                                                                                                                    , "I have never imagined that we would arrive to this type of situation," Embaló said. "I never thought that Bissau-Guineans could practice another act of violence."                                                                                                                                                                                                             , Defense forces engaged in crossfire with the alleged perpetrators for five hours before averting the coup, Embaló said.                                                                                                                                                                                                                                                         , He added that "many" members of security forces were killed in the failed attempt, but did not confirm the number of casualties. Several arrests have also been made, the president said.                                                                                                                                                                                       , Embaló also said that he believes the perpetrators of the coup intended to kill him and members of his cabinet, who were gathered for a weekly meeting in the palace. He added that drug traffickers and corrupt agents were also involved in the "very well planned" coup attempt.                                                                                             , "Power is something you get from the people -- through ballots," Embaló said, adding: "Guinea-Bissau is mourning today."                                                                                                                                                                                                                                                        , Earlier in the day, the Economic Community of West African States (ECOWAS) called for peace in Guinea-Bissau, as gunfire was heard around the government palace in the capital Bissau.                                                                                                                                                                                          , The unrest in Guinea-Bissau came after a military coup rocked Burkina Faso on January 24.                                                                                                                                                                                                                                                                                       ,                                                                                                                                                                                                                                                                                                                                                                                 , Prior to Embaló's address, Mamadou Jao, an academic in Guinea Bissau, told CNN that the streets were quiet across the capital, as worried residents stayed inside awaiting more information.                                                                                                                                                                                    , "Bissau is quiet but we don't know what is happening near the government place... We are waiting to know more about what is happening," Jao said earlier on Tuesday. Jao added that the power was off in homes saying: "The place is in darkness for about three or four hours. It is not something that happens normally."                                                     , David Glovsky, assistant professor in Africana Studies at the University of Albany, told CNN that since taking office in early 2020, Embaló "has faced many challenges to his legitimacy, including disputes over his election itself."                                                                                                                                         , "I doubt many Guineans are surprised by another coup attempt, and yet this is still so disappointing," Glovsky said, adding: "Regardless of anyone's feelings on President Embaló -- and there is a real range --  Guineans have too often been at the mercy of the military, and elite conflicts that do not necessarily focus on the concerns of Guineans across the country.", Guinea-Bissau's history has been marked by several military coups since the country gained independence from Portugal in 1974.                                                                                                                                                                                                                                                  , These conflicts have ravaged the country's infrastructure and economy, leaving it among the poorest in the world.                                                                                                                                                                                                                                                               , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/balance-of-trade </td>
   <td style="text-align:left;"> 2022-02-02 02:08:22 </td>
   <td style="text-align:left;"> Brazil Trade Deficit Roughly Unchanged As Expected </td>
   <td style="text-align:left;"> Brazil recorded a trade deficit of $0.176 billion in January of 2022 from a $0.205 billion deficit in the corresponding month of the previous. Exports jumped 25.3 percent to $19.67 billion amid higher sales of manufactured products (+35.1 percent) and agricultural products (97.5 percent), while mining goods exports plunged 18.6 percent. At the same time, imports rose 24.6 percent to $19.85 billion as the purchase surged for manufactured products (+14.9 percent) and mining goods (+325.8 percent), while agricultural products imports dropped 15.7 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/peru/inflation-cpi </td>
   <td style="text-align:left;"> 2022-02-02 02:03:42 </td>
   <td style="text-align:left;"> Peru Inflation Rate Eases from 13-Year High </td>
   <td style="text-align:left;"> The annual inflation rate in Peru eased to 5.7 percent in January of 2022 from the 13-year high of 6.4 percent in the previous month. Consumer prices rose at a slower rate for housing and utilities (11.8 percent vs 13.3 percent in December 2021), and food and non-alcoholic beverages (7.9 percent vs 8 percent). On the other hand, prices accelerated for transportation (8.1 percent vs 7.8 percent), while inflation remained constant for furniture and household maintenance (at 3 percent). On a monthly basis, consumer prices remained unchanged from the previous month, compared to a 0.8 percent rise during December of 2021. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/czech-republic/manufacturing-pmi </td>
   <td style="text-align:left;"> 2022-02-02 01:59:45 </td>
   <td style="text-align:left;"> Czech Republic Factory Activity Almost Unchanged </td>
   <td style="text-align:left;"> The IHS Markit Czech Republic Manufacturing PMI was almost unchanged at 59.0 in January of 2022 from a four-month high of 59.1 in the previous month and missed market expectations of 60.3. Output growth and new orders were at 5-month highs, boosted by stronger domestic demand and employment rose further, due to efforts to clear some outstanding work. At the same time, supply chain issues continued to ease, although energy and raw material costs, as well as transport fares, kept inflationary pressures elevated, with input prices rising at near record rates. In response, selling charges soared at an unprecedented pace. Looking ahead, output expectations rose to their highest in 3-1/2-years, reflecting hopes of a further uptick in client demand. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/energy/how-will-los-angeles-ban-on-new-oil-and-gas-wells-impact-drivers-wallets </td>
   <td style="text-align:left;"> 2022-02-02 01:55:53 </td>
   <td style="text-align:left;"> Gas prices in California will soar following LA ban on new oil and gas wells, industry rep warns </td>
   <td style="text-align:left;"> FOX Business' Kelly O'Grady reports on the move's potential impact on gas prices in California.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , California Independent Petroleum Association CEO Rock Zierman warned in an interview that aired on ‘Varney &amp; Co.’ Tuesday that already high gas prices in Los Angeles will be even higher if oil is no longer allowed to be produced in the area.                                                                                                                                                                                                                                                                                                                                                    , Zierman, who heads the group representing nearly 400 oil and gas industry entities, made the comment less than one week after the Los Angeles City Council approved a measure to ban new oil and gas wells and phase out existing ones.                                                                                                                                                                                                                                                                                                                                                              , The move is the latest effort to curb the production and usage of fossil fuels in California as the state has been trying to meet climate goals and improve public health.                                                                                                                                                                                                                                                                                                                                                                                                                           , Zierman stressed that the city council’s measure would not only raise gas prices, but will also eliminate jobs and make the region more dependent on foreign oil at a time when tension are brewing.                                                                                                                                                                                                                                                                                                                                                                                                 , As Russian President Vladimir Putin inches closer to Ukraine, the world energy markets are facing a potentially seismic event threatening a global economic recession.                                                                                                                                                                                                                                                                                                                                                                                                                               , FOX Business host gives his take on the rising tensions between Russia and Ukraine, tax cuts and Biden's energy policies on 'Kudlow.'                                                                                                                                                                                                                                                                                                                                                                                                                                                                , With global oil supplies below normal and the International Energy Agency (IEA) reportedly admitting that it has been overstating global supplies, the loss of Russian oil and gas could be next to impossible to replace. In Europe, natural gas prices have surged to record highs as the continent feels the impact of being over-reliant on Russia for that product. On the petroleum side, Russia is currently the world's second-largest producer, and if it chooses to cut off supply or if supplies were disrupted because of an active war, the void in the global market would be massive. , NORD 2 PIPELINE DEAL WILL HAND RUSSIA’S PUTIN KEYS TO EUROPE                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , "Any of the oil we don’t produce here has to be tankered in from a foreign country and as a result, we already pay the highest oil prices in the United States, which then gets turned into gasoline, and diesel and fuel - which are also the highest price in the entire country - and that is going to be exacerbated if we are no longer producing here," he warned on FOX Business.                                                                                                                                                                                                             , On Tuesday, the national average for gas was $3.38, which is nearly one dollar more than the year before, according to AAA.                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , California’s average on Tuesday was $4.64, which is $1.26 higher than the national average. The average price for gas in Los Angeles was $4.67 on Tuesday.                                                                                                                                                                                                                                                                                                                                                                                                                                           , Patrick De Haan, head of petroleum analysis at GasBuddy, predicts the national average for gasoline could hit $4 a gallon in the spring before peaking in the summer.                                                                                                                                                                                                                                                                                                                                                                                                                                , On Wednesday, the Los Angeles City Council directed the city attorney to draft an ordinance to ban oil and gas drilling in the city, change zoning laws to make drilling illegal and study how to legally phase out existing wells.                                                                                                                                                                                                                                                                                                                                                                  , Zierman argued that the city’s measure is illegal and warned that it will negatively impact the 8,000 jobs associated with oil extraction in Los Angeles, according to Grist.org.CLICK HERE TO GET FOX BUSINESS ON THE GO                                                                                                                                                                                                                                                                                                                                                                            , FOX Business’ Kelly O'Grady reported on Tuesday that critics question whether oil and gas workers in Los Angeles will be able to find new jobs without developing new skill sets. The council said a jobs program will be created in an attempt to help transition those workers to other industries.                                                                                                                                                                                                                                                                                                , The decision came after a decade of complaints from residents about health problems, including coughing and wheezing, which they blamed on air pollution from the sites.                                                                                                                                                                                                                                                                                                                                                                                                                             , California reportedly consumes 1.8 million barrels of oil a day, according to Californians for Energy Independence, which also reported that the state consumes every barrel of oil and gas produced in the state and imports almost three times more.                                                                                                                                                                                                                                                                                                                                               , California is the largest consumer of gas and jet fuel among the 50 states, accounting for 17% of the nation’s jet fuel consumption and 11% of motor gasoline consumption in 2019, according to the U.S. Energy Information Administration, which also noted that the state is the second-largest consumer of all petroleum products combined, accounting for 10% of the U.S. total.                                                                                                                                                                                                                 , READ MORE ON FOX BUSINESS BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , FOX Business’ Phil Flynn and The Associated Press contributed to this report.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mexico/currency </td>
   <td style="text-align:left;"> 2022-02-02 01:42:00 </td>
   <td style="text-align:left;"> Mexican Peso Strengthens From Near 6-Week Low </td>
   <td style="text-align:left;"> The Mexican peso traded below 20.6 per USD, after hitting a near 6-week low of 20.7876 on January 28th, amid a weaker dollar and higher oil prices. Also, domestically, inflation data and the last Central Bank minutes strengthened the case for higher rates, with bets surrounding another 50 bps increase during February’s meeting. Meanwhile, preliminary data showed that the Mexican economy entered a technical recession during the last quarter of 2021 after slipping 0.1% QoQsa, which could weigh on the Central Bank's decision to keep its current pace of policy tightening. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/01/business/supply-chain-disruption.html </td>
   <td style="text-align:left;"> 2022-02-02 01:32:09 </td>
   <td style="text-align:left;"> A Normal Supply Chain? It’s ‘Unlikely’ in 2022. - The New York Times </td>
   <td style="text-align:left;"> , The chaos at ports, warehouses and retailers will probably persist through the year, and perhaps even longer.                                                                                                                                                                                                                                                                                                   , The Port of Los Angeles, one of the busiest ports in the United States, where containers have piled up uncollected.Credit...Erin Schaff/The New York Times                                                                                                                                                                                                                                                      , Supported by                                                                                                                                                                                                                                                                                                                                                                                                    , By Peter S. Goodman                                                                                                                                                                                                                                                                                                                                                                                             , With the havoc at ports showing no signs of abating and prices for a vast array of goods still rising, the world is absorbing a troubling realization: Time alone will not solve the Great Supply Chain Disruption.                                                                                                                                                                                             , It will require investment, technology and a refashioning of the incentives at play across global business. It will take more ships, additional warehouses and an influx of truck drivers, none of which can be conjured quickly or cheaply. Many months, and perhaps years, are likely to transpire before the chaos subsides.                                                                                 , “It’s unlikely to happen in 2022,” said Phil Levy, chief economist at Flexport, a freight forwarding company based in San Francisco. “My crystal ball gets murky further out.”                                                                                                                                                                                                                                  , For those who keep tabs on the global supply chain, the very concept of a return to normalcy has given way to a begrudging acceptance that a new normal may be unfolding.                                                                                                                                                                                                                                       , Cheap and reliable shipping may no longer be taken as a given, forcing manufacturers to move production closer to customers. After decades of reliance on lean warehouses and online systems that monitor inventory and summon goods as needed — a boon to shareholders — manufacturers may revert to a more prudent focus on extra capacity.                                                                   , The deepening understanding that the supply chain crisis has staying power poses a daunting challenge to policymakers.                                                                                                                                                                                                                                                                                          , Mayhem at factories, ports and shipping yards, combined with the market dominance of major companies, is a key driver for rising prices. Spooked by the highest rates of inflation in decades, the Federal Reserve has resolved to tighten credit, while the Bank of England and other central banks have already lifted interest rates, sowing alarm in stock markets from New York to Tokyo.                  , Public anger over rising consumer prices — especially for food and fuel — helps explain why Democrats may be in danger of losing control of Congress.                                                                                                                                                                                                                                                           , Record beef prices, along with rising costs for pork and poultry, have prompted the Biden administration to pursue the prospect of antitrust enforcement against the four companies that dominate the American meat supply.                                                                                                                                                                                     , But whatever the politicians and central bankers unleash in the name of taming inflation, businesses continue to struggle to manufacture and distribute their products.                                                                                                                                                                                                                                         , Whirlpool recently warned that customers who purchased its washing machines, refrigerators and other household appliances would continue to experience delays as the company contended with supply chain problems.                                                                                                                                                                                              , Even as Tesla last week announced record profits amid overwhelming demand for its electric cars, the company said sales would be hurt by difficulties in the supply chain — not least due to continued shortages of computer chips.                                                                                                                                                                             , The chip shortage has limited the production of cars worldwide, while stymying makers of medical devices and a vast range of electronic gadgets. The U.S. commerce secretary, Gina M. Raimondo, recently described persistent chip shortages as an “alarming” threat to American industry.                                                                                                                      , The International Monetary Fund last week cited supply chain woes among other factors as it downgraded its forecast for global economic growth for 2022 to 4.4 percent from 4.9 percent.                                                                                                                                                                                                                        , The breadth and persistence of supply chain troubles in part result from how the coronavirus pandemic has accelerated trends that have been unfolding for decades, especially the growth of e-commerce.                                                                                                                                                                                                         , Whereas major brands traditionally ship goods from factories around the world to central warehouses that supply retail outlets, e-commerce demands a far more complicated endeavor: Retailers must deliver individual orders to homes and businesses.                                                                                                                                                           , As warehouses have been swamped by goods, major retailers have added capacity at a breakneck pace. Amazon spent more than $164 million to construct new warehouse space last year, while Lowe’s, the home improvement retailer, spent more than $17 million, according to Reonomy, a commercial real estate data provider.                                                                                      , Warehouses are stuffed to the rafters in the places with the most demand — those near the largest metropolitan areas.                                                                                                                                                                                                                                                                                           , As of late last year, warehouses in the Inland Empire region of Southern California had vacancy rates of less than 1 percent, according to CBRE Group, a commercial real estate services and investment company. Those in northern New Jersey had vacancy rates of only 2.4 percent.                                                                                                                            , “The basic physics of land scarcity matters quite a bit,” said Chris Caton, managing director of global strategy and analytics at Prologis, a real estate investment trust focused on warehouses. “If you look at Southern California, you look at the greater New York-New Jersey area, there’s just no more land in the most sought-after locations.”                                                         , The tightness in warehouses helps explain why American ports remain seized by dysfunction, especially the busiest one, the complex of terminals at Los Angeles and Long Beach. With limited room to stash goods offloaded from inbound vessels, containers have piled up on docks uncollected. That has prompted port overseers to force ships to float offshore for days and even weeks before they can unload., Over the last three months, container ships unloading goods have remained at American ports for seven days on average, an increase of 4 percent compared with all of 2021 and 21 percent higher than at the start of the pandemic, according to FourKites, a supply chain consultancy based in Chicago.                                                                                                         , As ports work through the backlog, they are contending with structural problems — aging and overtaxed infrastructure, a shortage of chassis used to haul containers with trucks, and not enough drivers, even as trucking companies increase pay.                                                                                                                                                               , Shipping companies are hobbled by outmoded technology that has limited their ability to anticipate and plan around problems.                                                                                                                                                                                                                                                                                    , “Those systemic problems in the supply chains, this has been building for years,” said Steve Dowse, senior vice president and general manager for international solutions at FourKites. “The pandemic has really just highlighted the fragility of our supply chains.”                                                                                                                                          , Even as companies confront the supply chain upheaval, the costs and complexity of solving their troubles may dissuade executives from taking effective action.                                                                                                                                                                                                                                                  , The pandemic sparked the problem. The highly intricate and interconnected global supply chain is in upheaval. Much of the crisis can be traced to the outbreak of Covid-19, which triggered an economic slowdown, mass layoffs and a halt to production. Here’s what happened next:                                                                                                                             , A reduction in shipping. With fewer goods being made and fewer people with paychecks to spend at the start of the pandemic, manufacturers and shipping companies assumed that demand would drop sharply. But that proved to be a mistake, as demand for some items would surge.                                                                                                                                 , Demand for protective gear spiked. In early 2020, the entire planet suddenly needed surgical masks and gowns. Most of these goods were made in China. As Chinese factories ramped up production, cargo vessels began delivering gear around the globe.                                                                                                                                                          , Then, a shipping container shortage. Shipping containers piled up in many parts of the world after they were emptied. The result was a shortage of containers in the one country that needed them the most: China, where factories would begin pumping out goods in record volumes                                                                                                                              , Demand for durable goods increased. The pandemic shifted Americans’ spending from eating out and attending events to office furniture, electronics and kitchen appliances – mostly purchased online. The spending was also encouraged by government stimulus programs.                                                                                                                                          , Strained supply chains. Factory goods swiftly overwhelmed U.S. ports. Swelling orders further outstripped the availability of shipping containers, and the cost of shipping a container from Shanghai to Los Angeles skyrocketed tenfold.                                                                                                                                                                       , Labor shortages. Businesses across the economy, meanwhile, struggled to hire workers, including the truck drivers needed to haul cargo to warehouses. Even as employers resorted to lifting wages, labor shortages persisted, worsening the scarcity of goods.                                                                                                                                                  , Component shortages. Shortages of one thing turned into shortages of others. A dearth of computer chips, for example, forced major automakers to slash production, while even delaying the manufacture of medical devices.                                                                                                                                                                                      , A lasting problem. Businesses and consumers reacted to shortages by ordering earlier and extra, especially ahead of the holidays, but that has placed more strain on the system. These issues are a key factor in rising inflation and are likely to last through 2022 — if not longer.                                                                                                                         , In a recent survey of over 3,000 chief executives conducted by the consulting firm Alix Partners, fewer than half said they were taking longer-term action to alleviate supply chain challenges, while a majority said they were relying on short-term measures. Regardless of their approach, more than three-fourths of chief executives were skeptical that their plans would prove effective.               , The supply chain problems have endured despite much talk that they would prove a largely momentary phenomenon resulting from the pandemic.                                                                                                                                                                                                                                                                      , In the initial months of the spread of Covid-19 — as markets plunged and American businesses laid off workers — manufacturers slashed orders for a vast array of goods on the assumption that health fears, lockdowns and diminished paychecks would limit demand for their wares.                                                                                                                              , Using the same logic, computer chip manufacturers cut production. Global shipping companies reduced service.                                                                                                                                                                                                                                                                                                    , That calculus proved disastrously wrong.                                                                                                                                                                                                                                                                                                                                                                        , The pandemic did not eliminate spending so much as shift it around. People stopped going to restaurants, sporting events and amusement parks, while directing their dollars to outfitting their homes for life under lockdown. They added treadmills to their basements, desk chairs to their bedroom offices and video game consoles to their living rooms.                                                    , Many of these goods were made in China. And the surge of demand swamped the availability of shipping containers at ports in Asia, delaying transport.                                                                                                                                                                                                                                                           , As ships arrived at ports from Los Angeles to Savannah, Ga., they carried more cargo than dockworkers and truck drivers could handle. Stacks of uncollected containers towered like monuments to globalization gone awry.                                                                                                                                                                                       , Shipping companies have expanded their fleets, but the impact has been canceled out by the number of vessels marooned off ports.                                                                                                                                                                                                                                                                                , “A ship that’s queued up is not a ship that’s moving stuff back and forth across the ocean,” Mr. Levy, the Flexport chief economist, said. “It’s a floating warehouse.”                                                                                                                                                                                                                                         , Many economists assumed that after a few months, Americans would exhaust their demand for products, allowing the supply chain to catch up. As vaccines reached the bloodstream and the pandemic loosened its grip on many parts of the world, it was thought that consumers would stop buying stand mixers and return to restaurants.                                                                           , This shift has yet to happen meaningfully — a seeming testament to the economic impact of Covid-19 variants like Delta and Omicron, which have led many to return to social isolation.                                                                                                                                                                                                                          , The biggest uncertainty centers on what happens next.                                                                                                                                                                                                                                                                                                                                                           , Once a household spends several thousand dollars to outfit an exercise room in the basement, its occupants may not return to their old gym after the pandemic ends. Rather than shell out for a gym membership, they may opt to invest in additional gear at home, adding more weights or an elliptical.                                                                                                        , As white-collar professionals begin a third year in their home offices, attending video conferences in sweatpants, how many will jump at the chance to again don business attire? And what does that mean for retailers that sell such clothing?                                                                                                                                                                , These are merely some of the variables at play as businesses try to divine the future. The dearth of solid information may dissuade investments — in trucking, in shipping, in warehouses, in technology — that might ease the supply chain upheaval.                                                                                                                                                           , “All of these head-scratching puzzles, these are really difficult,” Mr. Levy said. “Everybody is wary of getting caught out.”                                                                                                                                                                                                                                                                                   , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spain/stock-market </td>
   <td style="text-align:left;"> 2022-02-02 01:31:13 </td>
   <td style="text-align:left;"> Madrid Stocks Book Gains </td>
   <td style="text-align:left;"> The IBEX 35 Index closed 1.3% higher at 8,727 on Tuesday, in line with its European counterparts, as investors welcomed a series of economic data ahead of the ECB’s meeting on Thursday while closely monitoring geopolitical developments in between Russia and NATO members. The unemployment rate in the eurozone dropped to a record low of 7% for December, while the domestic manufacturing IHS Markit PMI reading was held constant at 56.2 in January, slightly above market expectations. On the corporate front, gains were led by the industrial sector, especially ArcelorMittal (5.5%) and Acerinox (2.9%) due to a rally in steel producing manufacturers, while Ferrovial (2.3%) also booked gains. On the other hand, Acciona fell 3% after a major expressway collapsed over the constructor's tunnel excavation site for the extension of a metro line in Sao Paulo, Brazil. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/01/stocks-making-the-biggest-moves-midday-exxon-mobil-amc-entertainment-ups-and-more.html </td>
   <td style="text-align:left;"> 2022-02-02 01:30:56 </td>
   <td style="text-align:left;"> Stocks making the biggest moves midday: Exxon Mobil, AMC Entertainment, UPS and more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Check out the companies making headlines in midday trading.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Exxon Mobil – Exxon shares advanced 6.5% after the company's fourth-quarter profit topped analysts' estimates. The oil giant earned $2.05 per share on an adjusted basis, which was ahead of the $1.93 analysts surveyed by Refinitiv were expecting. Revenue came in at $84.97 billion, which was below the expected $91.85 billion. The company said it paid down $9 billion in debt during the period, bringing its debt level to prepandemic levels.                                                                                                                                                                                              , UPS – Shares of the delivery company surged 14% following the company's fourth-quarter results and upbeat guidance. The company earned an adjusted $3.59 per share, while analysts surveyed by Refinitiv were expecting $3.10. Revenue also topped expectations, and UPS announced a 49% dividend increase.                                                                                                                                                                                                                                                                                                                                           , AMC Entertainment – Shares of the movie theater chain rose 5% after the company announced fourth-quarter preliminary results that topped expectations. AMC said it was able to cap off 2021 with "the strongest quarter in two years," which was led by movies like "Spider-Man: No Way Home." Sirius XM – Shares of the satellite radio and streaming audio service company jumped 6.3% after a better-than-expected earnings report. Sirius beat estimates by a penny with quarterly earnings of 8 cents per share, according to Refinitiv. Its revenue also surpassed expectations. Sirius also announced a special dividend of 25 cents per share., Carnival Corp. — Shares of the major cruise operators rose in midday trading on Tuesday. Carnival Corp. added 5.7%. Norwegian Cruise Line and Royal Caribbean rose 3.7% and 4.4%, respectively.                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Pitney Bowes — Shares of the mailing company cratered 15.4% in midday trading after missing Wall Street's estimates for its quarterly earnings. Pitney Bowes reported EPS of 6 cents per share, below the 11 cents per share forecasted by analysts, according to Refinitiv.                                                                                                                                                                                                                                                                                                                                                                          , These stocks are oversold into what could be good earnings reports, Barclays says                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Cathie Wood is buying Tesla again after steadily trimming position for months                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Stifel names Snap a top pick in digital advertising, projects stock can rebound 38%                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Piper Sandler says Goldman Sachs, Bank of America are top bank stocks after fourth-quarter earnings                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , AT&amp;T — Shares of AT&amp;T fell 4.3% after the telecom company announced it will spin off WarnerMedia in a $43 billion merger with Discovery. AT&amp;T also said it will cut its dividend by nearly half. Meanwhile, Discovery shares rose 1.7%.                                                                                                                                                                                                                                                                                                                                                                                                               , UBS Group — Shares of UBS Group rallied 9.3% in midday trading after the Zurich-based bank announced plans to increase its dividend as well its boost its share buyback program. UBS also posted net profit attributable to shareholders of $1.35 billion for the fourth quarter, down from $1.64 billion a year prior.                                                                                                                                                                                                                                                                                                                               , Cirrus Logic — Shares of the semiconductor company fell 7.3% despite beating on the top and bottom lines of its quarterly results. The company also gave strong fiscal fourth-quarter revenue guidance.                                                                                                                                                                                                                                                                                                                                                                                                                                               , Stanley Black &amp; Decker — Shares of the toolmaker dropped rose 0.9% after Stanley Black &amp; Decker reported fourth-quarter revenue that was well below expectations. The company said supply chain issues hurt sales volume.                                                                                                                                                                                                                                                                                                                                                                                                                             , — with reporting from CNBC's Yun Li, Pippa Stevens, Jesse Pound and Hannah Miao.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/01/cars/tesla-fsd-stop-sign/index.html </td>
   <td style="text-align:left;"> 2022-02-02 01:29:29 </td>
   <td style="text-align:left;"> Tesla recalls all 53,822 vehicles with its 'full self-driving' feature - CNN </td>
   <td style="text-align:left;"> Washington, DC (CNN Business)Tesla will recall all 53,822 vehicles with its "full self-driving" driver-assist feature after it was intentionally programmed to slowly roll through stop signs in some scenarios.                                                                                                                                                                                                                                                                                    , The recall will impact Model S, X, 3 and Y vehicles that have its beta version of the "full self-driving" software enabled. "Full self-driving" is a controversial driver-assist feature that aims to one day allow cars to drive themselves.                                                                                                                                                                                                                                                       , The technology sometimes steers Tesla vehicles smoothly and obeys traffic rules like stopping for red lights. But in other cases it has proved inconsistent, according to accounts from alarmed drivers using the software. Telsa says that "full self-driving" requires an attentive driver who is ready to take full control of the car at any time.                                                                                                                                              , "Full self-driving" has been capable of rolling through stop signs since the release of the first version in October 2020. Tesla decided to disable the function following meetings this month with the National Highway Traffic Safety Administration, which regulates motor vehicles.                                                                                                                                                                                                             , "The Vehicle Safety Act prohibits manufacturers from selling vehicles with defects posing unreasonable risks to safety, including intentional design choices that are unsafe. If the information shows that a safety risk may exist, NHTSA will act immediately," the administration said in a statement.                                                                                                                                                                                           , Tesla will disable the function as soon as this month in an updated version of "full self-driving" software that's released over the internet, according to a document the automaker filed. Drivers won't need to take their vehicles to be serviced.                                                                                                                                                                                                                                               , Tesla did not immediately respond to a request for comment.                                                                                                                                                                                                                                                                                                                                                                                                                                         , The recalled feature, called "rolling stop," allowed vehicles to travel through all-way stop intersections at up to 5.6 mph under certain conditions. Drivers had to set their vehicle to a "full self-driving" style that included the feature. The vehicle's "chill" setting, the setting a user can select that drives the most conservatively of the options Tesla gives drivers, is not described as including the feature. The other settings, "average" and "assertive," include the feature., The "rolling stop" function also required that no relevant moving cars or pedestrian or bicyclists were detected near the intersection. The function wouldn't activate without sufficient visibility, and all roads entering the intersection need to have a speed limit of no more than 30 mph.                                                                                                                                                                                                    , "If all the above conditions are met, only then will the vehicle travel through the all-way-stop intersection at a speed from 0.1 mph up to 5.6 mph without first coming to a complete stop," the recall document states.                                                                                                                                                                                                                                                                           , Tesla said that it is not aware of any collisions, injuries or fatalities related to the feature.                                                                                                                                                                                                                                                                                                                                                                                                   , The US government has been more proactive of late in taking action on new car features that may introduce safety risks. Tesla said in December that it would no longer allow people to play video games on the touchscreens of its vehicles while they are in motion, following a NHTSA investigation.                                                                                                                                                                                              , The US government does not currently have any performance standards for driver-assist features like Tesla's "full self-driving." It launched an investigation last year into Teslas rear-ending emergency vehicles while using the automaker's more rudimentary driver-assist software, Autopilot.                                                                                                                                                                                                  , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/currency </td>
   <td style="text-align:left;"> 2022-02-02 01:29:00 </td>
   <td style="text-align:left;"> Brazilian Real Over 4-Month High </td>
   <td style="text-align:left;"> The Brazilian Real traded below $5.30, the strongest since the end of September, amid a weaker dollar, higher iron ore prices, and expectations of higher interest rates domestically. Iron ore, a major Brazil’s export, rose to above $140 a tonne, the highest since the beginning of September 2021. Also, domestically, hotter-than-expected mid-month inflation data strengthened the case for a more hawkish policy stance by The Central Bank of Brazil. Mid-month consumer price data showed that the annual inflation rate remained above 10%, above market expectations, and the central bank’s target of 3.5%. Since April last year, COPOM has raised the main Selic rate by 725 bps to 9.25% and is expected to deliver another 150 bps hike during its next monetary policy meeting on February 2nd. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/pitney-bowes-stock-tumbles-lead/story.aspx?guid={CED169EF-4F1B-44CA-9CF6-A3D26E5CAEE1}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-02 01:16:39 </td>
   <td style="text-align:left;"> Pitney Bowes stock tumbles to lead NYSE losers after profit miss, domestic parcel volume disappoints - MarketWatch </td>
   <td style="text-align:left;"> Shares of Pitney Bowes Inc. 
        PBI,
        -15.42%
       tumbled 15.6% in midday trading Tuesday, enough to pace the NYSE's decliners, after the shipping and mailing company reported fourth-quarter profit that fell below expectations, amid disappointing domestic parcel volumes. Net income fell to $1.3 million, or 1 cent a share, from $20.3 million, or 11 cents a share, in the year-ago period. Excluding nonrecurring items, adjusted earnings per share fell to 6 cents from 14 cents, missing the FactSet consensus of 11 cents. Revenue declined 4.3% to $983.7 million, but beat the FactSet consensus of $691.6 million. Global ecommerce revenue fell 8.7% to $473 million, with Chief Financial Officer Ana Maria Chadwick saying the decline was "driven primarily by lower-than-expected domestic parcel volumes," given a move by many customers to shop via brick-and-mortar store, or to buy online for in-store pickup, rather than online for delivery to ensure they got their products in a timely manner as a result of supply-chain concerns. The stock, on track for the lowest close since Nov. 2, 2020, has plunged 29.7% over the past three months while the S&amp;P 500 
        SPX,
        +0.69%
       has slipped 2.0%., The viral word-game sensation is going corporate after it was scooped up by New York Times Co. NYT for an amount "in the low seven figures."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/cyprus/retail-sales-annual </td>
   <td style="text-align:left;"> 2022-02-02 01:00:23 </td>
   <td style="text-align:left;"> Cyprus Retail Sales Growth at 3-Month Low </td>
   <td style="text-align:left;"> Retail sales growth in Cyprus eased to 5.3 percent year-on-year in November of 2021 from 6.2 percent in the previous month. It was the smallest gain in retail trade since August, as sales slowed for food products (0.8 percent vs 4.3 percent in October); textiles and clothing (12 percent vs 21 percent); electrical household appliances, furniture, lighting equipment, and construction equipment (9.3 percent vs 2.2 percent); and computers and telecommunications equipment, curtains, carpets, books, stationery, sporting equipment, toys, flowers, plants, watches, and jewellery (12.6 percent vs 16.6 percent). On the other hand, sales rebounded sharply for automotive fuel (6.5 percent vs -0.4 percent). On a monthly basis, sales growth declined 0.5 percent compared to a downwardly revised 1.6 percent rise in October. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-02-02 00:48:00 </td>
   <td style="text-align:left;"> Italian Shares Extend Gains </td>
   <td style="text-align:left;"> The FTSE MIB Index closed 1.5% higher at 27,225 on Tuesday, lifted by strong sessions for the industrial and banking sectors, as investors weighed on a batch of fresh economic data and continued to monitor the development of geopolitical tensions in between Russia and western states. Unemployment in the Eurozone ticked down to a record low of 7% during December, while domestic unemployment decreased to a 19-month low of 9%. In the corporate front, financial stocks rose 1.5%, led by Bper Banca (3.5%), while industrial shares gained 1.9%, driven by Tenaris (5.9%) amid a global rally in the steel manufacturing sector. On the other hand, Saipem (-1.3%) continued to decline, extending yesterday’s 30.1% plunge that halted its session after the oil field services provider issued a profit warning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-02-02 00:47:00 </td>
   <td style="text-align:left;"> London Shares Jump on Tuesday </td>
   <td style="text-align:left;"> The FTSE 100 jumped 1% to close at 7,539 on the first trading day of February, tracking its European peers higher, and attempting to extend a 1.1% rally in January. Investors focus on prospects of a strong economic recovery, digest fresh economic data and earnings reports, and await the BoE monetary policy decision on Thursday. The Markit Manufacturing PMI was revised higher and mortgage lending and approvals topped forecasts while house prices recorded the strongest start to the year since 2005, according to Nationwide. On the corporate front, shares of clothing retailer Joules sank around 45.2% after the company warned supply constraints and covid-19 infections are hurting earnings. Virgin Money, however, increased guidance on net interest margin for 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-02-02 00:47:00 </td>
   <td style="text-align:left;"> European Stocks Close Higher on Tuesday </td>
   <td style="text-align:left;"> European stocks closed the first session of February on a strong foot, with the Stoxx 600 up 1.1% and the DAX ending 1% higher, after a bleak month of January saw shares erase the most value since October 2020. Investors continued to monitor NATO-Russia tensions over Ukraine and a fresh batch of quarterly earnings, ahead of the ECB monetary policy decision on Thursday. UBS shares jumped more than 8% after quarterly profits beat expectations, while full-year results showed the highest annual profit since 2006. On the data front, Germany’s retail sales unexpectedly sank 5.5% in December, while the annual inflation rate in France quickened to a faster-than-expected 2.9% in January. Markit PMIs continued to point to strong manufacturing growth although there were some downward revisions for Germany and the Euro Area. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-02-02 00:46:00 </td>
   <td style="text-align:left;"> French Stocks Extend Rebound </td>
   <td style="text-align:left;"> The CAC 40 Index jumped 1.4% to close at 7,099 on Tuesday, supported by the industrial and luxury goods sectors, as investors digested a batch of economic data to asses growth while monitoring the development of talks in between Russia and western states. Domestic preliminary inflation for January came at 2.9% on the year, the highest in over 13 years, while the manufacturing PMI was confirmed at a three-month low of 55.5. At the same time, the unemployment rate in the Eurozone ticked down to a record low of 7%. On the corporate front, industrial shares jumped 2.1%, carried by ArcelorMittal (5%) and Safran (4.1%) after Deutche Bank changed its recommendation of the aircraft manufacturer from “buy” to “hold”. At the same time, Faurecia gained 5.4% after it completed the acquisition of German automotive manufacturer Hella for USD 6 billion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/currency </td>
   <td style="text-align:left;"> 2022-02-02 00:43:51 </td>
   <td style="text-align:left;"> Canadian Dollar Rebounds From 1-Month Low </td>
   <td style="text-align:left;"> The Canadian dollar traded below 1.27 per USD at the beginning of February, after hitting a one-month low of 1.27669 on January 28th, amid a weaker dollar and after monthly GDP data topped forecasts and climbed back to pre-pandemic levels. The Canadian economy expanded 0.6 percent month-over-month in November of 2021, the sixth consecutive month of expansion, following a 0.8 percent increase in October and above market expectations of a 0.3 percent raise. While preliminary estimates show that the Canadian economy rose at an annualized rate of 6.3% during the last quarter of 2021. Also, oil prices – a major Canada’s export – were trading near a 7-year high of $88 per barrel, supporting the loonie's gains. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/02/01/americans-are-ready-to-travel-as-their-omicron-fears-fade.html </td>
   <td style="text-align:left;"> 2022-02-02 00:41:18 </td>
   <td style="text-align:left;"> Americans are ready to travel as their omicron fears fade </td>
   <td style="text-align:left;"> , Americans' enthusiasm for travel has rebounded to levels unseen since the broad rollout of Covid-19 vaccines last year, as their wanderlust eclipses hesitation fueled by the omicron and delta virus variants.                                                                                                                     , Nearly 82% of people are in a "ready to travel" mindset in 2022 — a 5 percentage-point increase in just the last two weeks, according to a survey of 1,200 American travelers published Monday by Destination Analysts, a tourism market research firm.                                                                             , The findings suggest would-be travelers have largely brushed off the shock of the highly contagious omicron variant, which pushed caseloads to record levels and upended travel plans over the winter holiday season.                                                                                                               , More from Personal Finance:Top spots to shop for a dream winter vacation homeHow to insure your trip amid airline cancellationsWhere Americans want to travel abroad                                                                                                                                                                , "Travel sentiment recovered very quickly," said Erin Francis-Cummings, president and CEO of Destination Analysts, which has conducted biweekly polls of U.S. travelers since March 2020. "The ready-to-go mindset is essentially the highest it's been," she added, calling the metric a leading indicator of optimism.             , More than 92% of respondents will take at least one trip in the next 12 months; they expect to take 3.3 leisure trips, on average, the highest share in 14 months, according to the survey, conducted Jan. 26-28. Over three-quarters have dreamed about and planned travel just in the last week — a rate unseen since last summer., Travel enthusiasm had previously begun gaining steam around midyear 2021, when a broad swath of Americans became eligible for a Covid vaccine. But the delta variant dampened that outlook, and again when omicron fears emerged around Thanksgiving.                                                                               , "Early summer 2021 was the prior apex," Francis-Cummings said. "We're starting to see that apex again."                                                                                                                                                                                                                             , "Omicron definitely had an impact: People canceled and postponed trips," she added. "It didn't have as deep or as long of an impact as delta did."                                                                                                                                                                                  , Respondents' optimism about the course of the pandemic over the next month jumped 11 percentage points to about 42% in the last two weeks, exceeding the post-delta variant recovery, Destination Analysts said.                                                                                                                    , About 81% of travelers polled by Destination Analysts are fully vaccinated — well above the 68% of overall Americans age 5 and older, the population currently eligible for a shot, according to the Centers for Disease Control and Prevention.                                                                                    , Travel site Hopper is forecasting prices for domestic airfare will jump 7%, on average, each month until June, "driven by demand recovery following the omicron variant wave."                                                                                                                                                      , That's well above the typical 2% monthly pre-pandemic airfare increases heading into the summer, according to the company's consumer airfare index published Jan. 19. Domestic prices will hit 2019 levels by April 2022, it said.                                                                                                  , Prices for international flights are at record lows for January, averaging $649 round trip, but are expected to rebound by 5%, on average, a month until June, Hopper said. Fares began dropping the last week of November, when the World Health Organization classified omicron as a variant of concern.                          , International travel likely poses some additional hurdles for travelers, with many countries imposing testing and other requirements for entry. (The U.S. also requires a negative test for reentry.) Some countries haven't yet reopened their borders to American travelers.                                                      , Wherever the destination, Americans traveling in 2022 plan to go big. The average traveler plans to spend more than $4,100 on leisure travel this year, up over $200 from early January, according to Destination Analysts.                                                                                                         , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                              , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                              , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                    , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                    , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                  , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-02 00:40:37 </td>
   <td style="text-align:left;"> Australia 10Y Bond Yield Little Changed after RBA Meeting </td>
   <td style="text-align:left;"> The yield on the Australian 10-year government swung between gains and losses around 1.9% on Tuesday, following the Reserve Bank of Australia’s monetary policy meeting, where it pushed back against rate hike talks and announced the end of the QE program. Policymakers will terminate the AUD 275 billion bond-buying program on February 10th but warned that its end wasn’t a signal that interest rates would be raised soon. The central bank also said that it was too early to say if inflation would remain sustainably within target and wage growth remained modest. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/02/01/business/als-synapticure-startup.html </td>
   <td style="text-align:left;"> 2022-02-02 00:33:49 </td>
   <td style="text-align:left;"> Rethinking Care After an A.L.S. Diagnosis - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , With the backing of venture capital and well-known tech investors, Synapticure seeks to fill in the gaps in care and research for those with amyotrophic lateral sclerosis.                                                                                                                                                                                                                                                                                                                                              , By Maureen Farrell                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , In August 2017, Brian Wallach’s notion of time changed forever.                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Mr. Wallach, then 36 and a federal prosecutor in the middle of a firearms trafficking case in Chicago, had spent months trying to ignore persistent muscle spasms and a worsening cough.                                                                                                                                                                                                                                                                                                                                 , When he finally visited a neurologist — just a few days after the birth of his second child — the news was grim: The doctor believed he had amyotrophic lateral sclerosis, or Lou Gehrig’s disease. In a few years, he would most likely be robbed of the ability to walk, speak, eat and ultimately breathe.                                                                                                                                                                                                            , Even so, Mr. Wallach was fortunate: His diagnosis, which took a few months and trips to neurologists all over the country to confirm, came comparatively early. He had time — and a chance to get into clinical trials that have added to doctors’ understanding of the lethal disease.                                                                                                                                                                                                                                  , Today, Mr. Wallach and his wife, Sandra Abrevaya, lead a company that aims to help other A.L.S. patients make the most of their time — and, ideally, give them more of it.                                                                                                                                                                                                                                                                                                                                               , Their company, Synapticure, believes telemedicine and data aggregation will help A.L.S. patients and researchers deal with challenges caused by the disease’s rapid progression. Between 20,000 and 30,000 people in the United States have A.L.S., according to Centers for Disease Control and Prevention estimates, and most are expected to live for just two to five years after diagnosis.                                                                                                                         , While there are multidisciplinary A.L.S. treatment centers in almost every state, patients may have to drive for hours to reach them while travel grows increasingly difficult. And doctors at many clinics say they can serve at most 300 patients a year because of their extensive needs.                                                                                                                                                                                                                             , At the same time, clinical trials that could help slow the disease’s progress are generally open to patients only within 18 months of the onset of symptoms — a brief window if early signs were ignored or missed.                                                                                                                                                                                                                                                                                                      , Navigating it all can get a little harder each day. Mr. Wallach, who ran on Yale University’s track and field team, uses a wheelchair. He cracks jokes and rattles off reams of information about research, genetic sequencing and the business rationale for pharmaceutical companies to work on A.L.S., but he also struggles to pronounce words and often relies on Ms. Abrevaya to repeat them so others can understand.                                                                                             , “We’re stuck in a burning house with the doors locked,” Ms. Abrevaya said. “It’s your responsibility to track all of this and make sure you’re organized and know about everything.”                                                                                                                                                                                                                                                                                                                                     , Chicago-based Synapticure closed a $6 million round of seed funding last fall from GV, formerly known as Google Ventures, and a host of well-known tech investors and founders. They included Ben Silbermann, the chief executive of Pinterest, and Ron Conway, who was among the earliest backers of Facebook, Airbnb and Twitter.                                                                                                                                                                                      , Mr. Wallach, who left his job as an assistant U.S. attorney in 2018, and Ms. Abrevaya, who left her job as president of Thrive Chicago, an education nonprofit, in 2020, want to use the new funding to attract more patients and specialists as well as to build out Synapticure’s technology platform.                                                                                                                                                                                                                 , Mr. Wallach said he and his wife were able to read reams of research papers and consult a number of doctors to sniff out the best treatments and studies, but others are not so fortunate.                                                                                                                                                                                                                                                                                                                               , “If we succeed, it will be because every patient will have the opportunities I’ve had,” he said. “That would be an amazing success both from a human standpoint and from a business standpoint.”                                                                                                                                                                                                                                                                                                                         , Synapticure’s timing is auspicious: Mr. Wallach said that more than 100 A.L.S. clinical trials were in the pipeline, far more than a decade ago, and that the pandemic had accelerated the use of telemedicine. Medicare has expanded the types of remote services it covers, and the Department of Health and Human Services temporarily relaxed enforcement of HIPAA, the federal patient privacy law, when providers use everyday platforms like FaceTime or Skype.                                                   , And a growing group of companies have proved there’s a business model for improving disease-specific care. One of the most successful, the diabetes-treatment company Livongo, went public in 2019 at a roughly $4.4 billion valuation and was sold to a competitor a year later for about $18.5 billion.                                                                                                                                                                                                                , Livongo “unleashed a belief that you could build these kinds of companies,” said Hemant Taneja, a managing partner at the venture capital firm General Catalyst, one of Livongo’s initial investors.                                                                                                                                                                                                                                                                                                                     , Investors have taken note, pouring money into so-called health tech deals. U.S. investors put roughly $32 billion into private health care technology companies last year, a record, and nearly double the amount from 2020, according to PitchBook data.                                                                                                                                                                                                                                                                , Dr. Krishna Yeshwant, a managing partner at GV who is leading its Synapticure investment, learned of the company through a colleague, Graham Spencer, who has A.L.S. Although Dr. Yeshwant, who is a physician, and others at GV have sought ways to help their colleague, he said the firm wouldn’t have invested in Synapticure unless it was a clear opportunity for big returns.                                                                                                                                     , “You can lose a lot of money solving complex issues for friends,” Dr. Yeshwant said.                                                                                                                                                                                                                                                                                                                                                                                                                                     , Synapticure makes money much the way a typical doctor’s office does, billing insurance companies for its services, including neurological consultations and counseling. It does not charge patients any additional fees.                                                                                                                                                                                                                                                                                                 , The company’s nurses, counselors, neurologists and medical assistants help patients sort through their existing care and connect them with providers who can fill any gaps. The company also monitors current and pending clinical trials to see which of its users might qualify. With a database of clients who are eager to share their health records, Synapticure hopes to make it easier for biotech start-ups that conduct these trials to find potential research subjects, a costly and time-consuming endeavor., “That is a clear need,” said Dr. Eva Feldman, the director of the A.L.S. Center of Excellence at the University of Michigan. She and her team spend roughly four hours with each patient at each visit — about the maximum they can handle — leaving no time to talk about outside research.                                                                                                                                                                                                                             , “Right now we only discuss the clinical trials we’re doing, and that’s what every center does,” Dr. Feldman said.                                                                                                                                                                                                                                                                                                                                                                                                        , Mr. Wallach and Ms. Abrevaya — who met while working on Barack Obama’s 2008 presidential campaign and later worked in his administration — began their advocacy by starting a nonprofit, I AM ALS, in 2019 to help advocate for research and government funding. President Biden thanked them in December when he signed a bill known as the ACT for ALS, which expanded federal research and gave patients earlier access to treatments still being reviewed by the Food and Drug Administration.                       , But the nonprofit, even with about roughly 50,000 members, didn’t have the capacity to address the problems that Mr. Wallach and Ms. Abrevaya observed.                                                                                                                                                                                                                                                                                                                                                                  , “We have pieced together for ourselves what we think is the best care,” Ms. Abrevaya said. “We knew we needed to build a systemic platform that’s available for everyone.”                                                                                                                                                                                                                                                                                                                                               , Evan Campa, a 40-year-old mother of two who learned she had A.L.S. three years ago, was part of Synapticure’s pilot program. Ms. Campa, of Nashville, had finished one clinical trial and was enrolling in a second one when a team from Synapticure visited her to take a DNA sample that will be continually crosschecked with coming genetic research around A.L.S.                                                                                                                                                   , Ms. Campa no longer dreads visits with doctors. “They always made it clear there was nothing they could do for you,” she said. “Synapticure represents hope. The conversations are always about the next steps and a continued focus on exploring all options that are on the table.”                                                                                                                                                                                                                                    , Some A.L.S. doctors worry, however, that offering patients too many potential treatments could cause confusion. “A concern of mine is fragmenting patients’ care,” said Dr. Zachary Simmons, director of the A.L.S. Center at Penn State Health. “Ultimately, people will have to decide who is directing their care and whether receiving different types of input is a good thing.”                                                                                                                                    , Mr. Wallach, however, brims with optimism about what Synapticure can do, even as he’s articulating the challenges he faces personally. His Twitter feed, which has more than 100,000 followers, is an endless stream of gratitude, inspiration and hope.                                                                                                                                                                                                                                                                 , “Even after I was diagnosed with a 100% fatal disease I have had high hopes for this life I’ve been given to live,” he wrote on Jan. 8. “That ain’t never gonna change. In fact, every day they get a bit higher.”                                                                                                                                                                                                                                                                                                       , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-02-02 00:29:00 </td>
   <td style="text-align:left;"> South African Stocks Start February on Positive Note </td>
   <td style="text-align:left;"> The FTSE/JSE All Share Index rose 0.79% to close at 74,889 on the first trading day of February, after booking a 0.8% gain in January, mainly supported by commodity-linked sectors and tech stocks. Meanwhile, investors continued to weigh tensions between NATO and Russia over Ukraine, inflationary pressures and the prospect of higher interest rates soon. Domestically, the South African government has relaxed Covid-19 restrictions even further, citing the falling number of cases and the high natural immunity in the South African population. According to new rules, the isolation period for those infected with symptomatic Covid-19 was cut to 7 days from 10 and it was dropped the need for asymptomatic cases and contacts of those infected to isolate. The government also announced that school children can all now return to their educational facilities full time. On the data front, Absa's report showed South African manufacturing activity expanded at a faster pace in January. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-02 00:26:13 </td>
   <td style="text-align:left;"> 10-Year Treasury Rebounds From Near 1-Week Low </td>
   <td style="text-align:left;"> The yield on the benchmark 10-year Treasury note ticked up to above 1.8% on Tuesday, still below 2020-highs of 1.9% hit in mid-January, as investors continued to wonder if the Fed will need to tight monetary policy faster than anticipated to tackle rising inflation. The US central bank indicated last week that it would likely hike interest rates in March, with markets pricing in five quarter-point rate hikes this year. Meanwhile, jobs opening data topped forecasts after rising to 10.925 million in December 2021 from an upwardly revised 10.775 million in the previous month and above market expectations of 10.3 million. The level of openings remained near record highs, as employers were still having a difficult time filling positions. Still, traders will get an update on the strength of the US labor market this week with the payrolls and ADP releases. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/austria/unemployment-rate </td>
   <td style="text-align:left;"> 2022-02-02 00:24:53 </td>
   <td style="text-align:left;"> Austria Jobless Rate Falls to 8.1% in January </td>
   <td style="text-align:left;"> The jobless rate in Austria declined to 8.1 percent in January of 2022 from 11.4 percent in the corresponding month of the previous year,as the labour market continues to recover from the Covid-19 crisis. The number of people registered as unemployed declined by 135,374 to 332,956. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/dow-transports-charges-higher-record/story.aspx?guid={148C2A4A-9B39-4611-9E5E-2766A61BAAC4}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-02-02 00:22:32 </td>
   <td style="text-align:left;"> Dow transports charges higher as record UPS stock surge provides a near 200-point boost - MarketWatch </td>
   <td style="text-align:left;"> The Dow Jones Transportation Average 
        DJT,
        +2.14%
       charged up 281 points, or 1.8%, to outperform the broader stock market by a wide margin, as big surge in United Parcel Service Inc.'s stock 
        UPS,
        +14.08%
       on the back of a blowout fourth-quarter report provided a boost. UPS's stock powered up 15.3% toward a one-day record gain and a record close, with the $30.94 price gain adding about 189 points to the Dow transports' price. Shares of fellow package delivery provider FedEx Corp. 
        FDX,
        +2.50%
       got a reciprocal boost of $7.60, or 3.1%, to add about 46 points to the Dow transports. Meanwhile, the Dow Jones Industrial Average 
        DJIA,
        +0.78%
       rose 52 points, or 0.2%, and the S&amp;P 500 
        SPX,
        +0.69%
       ticked up 0.1%., The viral word-game sensation is going corporate after it was scooped up by New York Times Co. NYT for an amount "in the low seven figures."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/copper </td>
   <td style="text-align:left;"> 2022-02-02 00:17:12 </td>
   <td style="text-align:left;"> Copper Rebounds from 6-Week Low </td>
   <td style="text-align:left;"> Copper futures rebounded to $4.4 per tonne from a six-week low of $ 4.28 touched on January 31st, amid weaker dollar and strong factory activity in Europe, in a week of thin trading in China as the local markets are closed for New Year’s celebrations. The US dollar eased from 19-month highs as other major central banks signaled tighter policy to come, increasing the purchasing power of importing states. At the same time, January PMI data showed that factory activity grew strongly in the Eurozone, the UK, Japan, and Russia as supply-chain bottlenecks eased and production and order book improved. To make things even better, improvements in business confidence across European factories pointed to stronger demand in the coming months. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-02-02 00:16:39 </td>
   <td style="text-align:left;"> Crude Oil Hits 7-year High </td>
   <td style="text-align:left;"> Crude Oil increased to a 7-year high of 88.85 USD/Bbl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/heating-oil </td>
   <td style="text-align:left;"> 2022-02-02 00:13:48 </td>
   <td style="text-align:left;"> Heating Oil Futures at 7-Year Highs </td>
   <td style="text-align:left;"> Heating oil futures traded close to seven-year highs around $2.7 per gallon at the start of February, tracking movements in crude oil futures and robust demand prospects. Oil producing nations have so far failed to meet the planned output increases, as traders prepare for another OPEC+ meeting where the group will decide how much to raise output in March. Meanwhile, domestic distillate inventory levels, where heating oil is included, are projected to shrink by 1.67 million barrels for the week ended January 28th, after a larger-than-expected 2.8 million barrel draw. US heating oil stocks shrank by 607 thousand barrels in the third week of January, the biggest withdrawal since the week before Christmas, and stood 15.9% below last year’s level, according to government figures. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mexico/manufacturing-pmi </td>
   <td style="text-align:left;"> 2022-02-01 23:57:59 </td>
   <td style="text-align:left;"> Mexico Factory Activity Contracts for 23rd Straight Month </td>
   <td style="text-align:left;"> The IHS Markit Mexico Manufacturing PMI fell to 46.1 in January of 2022 from 49.4 in the prior month, signaling deterioration in the health of the sector. The latest reading pointed to the 23rd consecutive month of contraction in factory activity and the steepest since March of 2021, as manufacturers recorded a sharper deterioration in output and new orders, amid lower international demand. At the same time, employment continued to decline, and staff absence furthered the capacity pressures already in place due to raw material scarcity. On the price front, input inflation was broadly similar to December’s five-year high, largely due to a weaker peso, transportation problems, raw material scarcity, and pandemic pressures, while cost burdens continued to be passed to clients. Looking forward, business confidence slipped to a one-year low, as manufacturers became increasingly concerned about the pandemic and supply-chain problems. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2022-02-01 23:57:27 </td>
   <td style="text-align:left;"> Natural Gas Rally Falters in February </td>
   <td style="text-align:left;"> US natural gas futures traded around $4.8 per million British thermal units, close to highs not seen since late November, as investors took a breather and digested weather reports. The next couple of weeks could see milder temperatures across most of the US and undermine heating demand, while news of a cold blast heading to Texas fueled concerns over output, as natural gas wells could freeze again. Elsewhere, traders continued to monitor tensions in Eastern Europe, with Russian officials yet to write back to NATO’s proposals and US Secretary of State to hold a telephone conference with Russia’s Foreign Minister, while Western leaders finalize a package of sanctions against Russia. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60208463?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-01 23:56:09 </td>
   <td style="text-align:left;"> Wordle inventor 'overwhelmed' as New York Times buys game </td>
   <td style="text-align:left;"> The inventor of word game sensation Wordle has spoken of being overwhelmed by its success, following a sale to the New York Times (NYT).                                                                                                                                               , Software engineer Josh Wardle released the free simple online game in October, and has now sold it for an undisclosed seven-figure sum.                                                                                                                                                , He said the game, which has millions of players, "has gotten bigger than I ever imagined. It has been incredible."                                                                                                                                                                     , The NYT wants to use the game to boost its online subscriptions.                                                                                                                                                                                                                       , The media group said it will "initially remain free" to play, raising questions that the intention in the long term is to charge.                                                                                                                                                      , Mr Wardle always wanted the game to remain free, but the unexpected success of something he devised during lockdown for just two people - him and his partner - has come as a shock.                                                                                                   , He took to Twitter to thank users for sharing touching stories about the effect the game has had on their lives and relationships, adding that he was "thrilled" about the takeover.                                                                                                   , He said: "It has been incredible to watch the game bring so much joy to so many and I feel so grateful for the personal stories some of you have shared with me - from Wordle uniting distant family members, to provoking friendly rivalries, to supporting medical recoveries.       , "On the flip side, I'd be lying if I said this hasn't been overwhelming. After all, I am just one person, and it is important to me that, as Wordle grows, it continues to provide a great experience to everyone.                                                                     , "Given this, I am incredibly pleased to announce that I've reached an agreement with The New York Times for them to take over running Wordle going forward."                                                                                                                           , This video can not be played                                                                                                                                                                                                                                                           , The game challenges players to find a five-letter word in six guesses.                                                                                                                                                                                                                 , A new puzzle is published every day and players can post how quickly they solved the colourful grid on social media - but in a way that does not spoil the answer for those still playing - which is why, Mr Wardle said, it managed to capture the imagination of so many users.      , Mr Wardle announced the deal in a statement posted on Twitter, saying he had "long admired the NYT's approach to their games and the respect with which they treat their players".                                                                                                     , The New York Times said it bought the hit word game from its creator for a price "in the low seven figures".                                                                                                                                                                           , "The Times remains focused on becoming the essential subscription for every English-speaking person seeking to understand and engage with the world. New York Times Games are a key part of that strategy," a statement said.                                                          , "Our games already provide original, high-quality content and experiences every single day. Wordle will now play a part in that daily experience, giving millions more people around the world another reason to turn to The Times to meet their daily news and life needs," it added. , The game can be played in just a few minutes. Players begin by guessing any five-letter word.                                                                                                                                                                                          , Wordle fan Matthew Robertson said he only discovered the game a few weeks ago after reading about it in the media.                                                                                                                                                                     , Like most players who discover Wordle, it becomes a bit of an addiction. "I'm not great at it, but it's still fun and gets me thinking," he told the BBC.                                                                                                                              , "I think the set-up and how it works is very clever. It's something to do every day, as well."                                                                                                                                                                                         , Having only just discovered the game, Sheffield-based Mr Robertson is really hoping the New York Times doesn't put Wordle behind a paywall.                                                                                                                                            , He does volunteering, including at his local library. "I hope that the New York Times doesn't charge, as that will make it difficult for me to play," he said. "Apart from that, I see no issue with them taking it over."                                                             , Wales-born Mr Wardle, who graduated from university in London in 2006 and moved to the US for a masters degree in 2008, worked as a software engineer at Reddit.                                                                                                                       , He said he had "really got into" the New York Times crossword and spelling games during the pandemic.                                                                                                                                                                                  , The New York Times Games, Mr Wardle said, played a "big part" in Wordle's origins, "so this step feels very natural".                                                                                                                                                                  , In January, Mr Wardle told the BBC's Today programme he had come up with a prototype for the game in 2013 but his friends had not been keen on it.                                                                                                                                     , "Last year, my partner and I got really into crosswords and word games and I wanted a game for us to play each morning as part of our routine," he said.                                                                                                                               , He then shared it with his family on WhatsApp before opening it up to the public.                                                                                                                                                                                                      , Asked whether he planned to make money from it, he said: "I don't understand why something can't just be fun. I don't have to charge people money for this and ideally would like to keep it that way."                                                                                , Prof. Steven Pinker tries to make sense of the situation...                                                                                                                                                                                                                            , Go behind the scenes at London's Corinthia Hotel                                                                                                                                                                                                                                       , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/01/31/russia-ukraine-military-comparison-lon-orig-ll.cnn </td>
   <td style="text-align:left;"> 2022-02-01 23:54:14 </td>
   <td style="text-align:left;"> Videos show striking difference between Russia and Ukraine militaries - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/denmark/government-bond-yield </td>
   <td style="text-align:left;"> 2022-02-01 23:42:33 </td>
   <td style="text-align:left;"> Denmark 10Y Bond Yield Hits 34-month High </td>
   <td style="text-align:left;"> Denmark 10 Year Government Bond Yeld increased to a 34-month high of 0.258% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/cocoa </td>
   <td style="text-align:left;"> 2022-02-01 23:38:08 </td>
   <td style="text-align:left;"> Cocoa Hits 1-Week High on Supply Worries </td>
   <td style="text-align:left;"> Cocoa futures rose to a 1-week high of around $2600 a tonne at the start of February on expectations of lower supplies amid dry conditions in top producer Ivory Coast. Farmers warned that lack of rains for the second straight week in top growing regions of Ivory Coast coupled with periods of heat could reduce the quality of cocoa beans for the last stage of the main crop and shrink the April-September mid crop. At the same time, demand remained firm as both Asian and European Q4 cocoa grindings, a measure of demand, rose 6.3% year-on year. Meanwhile, North American Q4 cocoa grindings fell 1.2% on an annual basis and exporters estimated that cocoa port arrivals in Ivory Coast rose 1.5% between Oct. 1 and Jan. 30 period compared to the same period a year ago. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/baltic </td>
   <td style="text-align:left;"> 2022-02-01 23:29:00 </td>
   <td style="text-align:left;"> Baltic Exchange Dry Index Rises for 4th Day </td>
   <td style="text-align:left;"> The Baltic Exchange Dry Index rose 1.6% to 1,440 on Tuesday, its highest since January 20th, extending gains for a fourth straight session, as the capesize index, which tracks iron ore and coal cargos of 150,000-tonnes, surged 7.4% to 1,297, its highest level in two weeks. Meanwhile, the panamax index which tracks cargoes of about 60,000 to 70,000 tonnes of coal and grains, eased 17 points to 1,811, its lowest since April; and the supramax index fell 9 points to its lowest since February 2021 at 1,578. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-02-01 23:21:45 </td>
   <td style="text-align:left;"> Canada Stocks Flat on Tuesday </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, traded flat on Tuesday, shy of the 21,200 level touched for the last time on January 20th, as concerns over the interest rate outlook globally offset gains in the energy sector. On the data front, the Canadian economy rose 0.6% y-o-y in November, more than market forecasts of a 0.3% expansion, with 17 out of 20 industrial sectors in positive territory. Meanwhile, factory activity growth slowed in January, although firms reported higher levels of new orders. On the earnings front, Imperial Oil narrowly missed Q4 profit forecasts, as higher commodity prices and motor fuel demand were partly offset by lower oil sand extraction levels amid icy temperatures. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/uk-60218573?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-01 23:09:25 </td>
   <td style="text-align:left;"> Royal souvenirs have 'Platinum Jubbly' misprint </td>
   <td style="text-align:left;"> A spelling mistake on thousands of pieces of Platinum Jubilee merchandising, calling it the "Platinum Jubbly", is proving a challenge for souvenir sellers.                                                   , The cups and plates were meant to mark the Queen's 70-year reign.                                                                                                                                             , Clearance website boss Karl Baxter said - "in classic Del Boy-style" - he will pitch them as collectors' items.                                                                                               , "What could be more unique than our limited-edition misprinted crockery?" he said.                                                                                                                            , More than 10,000 pieces of the jubilee memorabilia were produced in China and sent to be sold in the UK - except for the slight problem of a misprint, which says "the Platinum Jubbly of Queen Elizabeth II"., Wholesale Clearance, which deals in bankrupt stock and discontinued lines, has stepped in to sell the commemorative items - with the products advertised as "Souvenir Stock with Slight Typo Mistake".        , "This could be your chance to get your hands on a novelty souvenir for a fraction of the price," said Mr Baxter, with a 90% discount on offer.                                                                , Invoking the spirit of market traders from the TV comedy, the website promises: "Become an Only Fools and Horses fan and wow your friends with your Lovely Jubbly set!"                                       , The wholesale firm will try to sell the misprinted cups, mugs and commemorative plates as a single lot to retailers - with a spokesman saying: "There's a market for everything".                             , The Platinum Jubilee will be marked with a four-day holiday in June, with concerts, parties, pageants - and maybe some jubilee bubbly.                                                                        , Prof. Steven Pinker tries to make sense of the situation...                                                                                                                                                   , Go behind the scenes at London's Corinthia Hotel                                                                                                                                                              , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/business-confidence </td>
   <td style="text-align:left;"> 2022-02-01 23:05:00 </td>
   <td style="text-align:left;"> US Factory Growth Slows Again in January: ISM </td>
   <td style="text-align:left;"> The ISM Manufacturing PMI for the US fell for a second straight month to 57.6 in January of 2022 from 58.8 in December, and compared to market forecasts of 57.5. The reading pointed to the weakest growth in factory activity since September of 2020. "The US manufacturing sector remains in a demand-driven, supply chain-constrained environment, but January was the third straight month with indications of improvements in labor resources and supplier delivery performance. Still, there were shortages of critical intermediate materials, difficulties in transporting products and lack of direct labor on factory floors due to the COVID-19 omicron variant. Quits rate and early retirements hinder reliable consumption. Panel sentiment remains strongly optimistic", Timothy Fiore, Chair of the ISM said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/job-offers </td>
   <td style="text-align:left;"> 2022-02-01 23:04:00 </td>
   <td style="text-align:left;"> US Job Openings Top Forecasts </td>
   <td style="text-align:left;"> The number of job openings in the United States rose to 10.925 million in December 2021 from an upwardly revised 10.775 million in the previous month and above market expectations of 10.3 million. The level of openings remained near record highs, as employers were still having a difficult time filling positions. Job openings increased in several industries with the largest increases in accommodation and food services (+133,000), information (+40,000), and nondurable goods manufacturing and state and local government education (+31,000 each). Job openings decreased in finance and insurance (-89,000) and in wholesale trade (-48,000). The number of  job openings was little changed in all four regions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/construction-spending </td>
   <td style="text-align:left;"> 2022-02-01 23:02:00 </td>
   <td style="text-align:left;"> US December Construction Spending Misses Forecasts </td>
   <td style="text-align:left;"> Construction spending in the US inched up 0.2 percent from the previous month to a seasonally adjusted annual rate of USD 1.640 trillion in December of 2021, following an upwardly revised 0.6 percent advance in December and missing market expectations of a 0.6 percent gain. Spending on private construction rose 0.7 percent, mostly new single family residential construction (2.1 percent), amusement and recreation (3.3 percent) and lodging (2.1 percent). On the other hand, public construction outlays fell 1.6 percent, weighed down by transportation (-3.0 percent), educational (-1.4 percent), and sewage and waste disposal (-3.9 percent). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/02/01/politics/republicans-january-6-committee-miscalculations/index.html </td>
   <td style="text-align:left;"> 2022-02-01 22:56:52 </td>
   <td style="text-align:left;"> The massive miscalculation Republicans made on the January 6 committee - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)Last spring, congressional Republicans made two fateful decisions.                                                                                                                                                                                                                                                                                                                                                                                                                      , First, in May, Senate Minority Leader Mitch McConnell decided to come out forcefully against an independent commission to study the January 6, 2021 riot at the US Capitol, despite the fact that its creation had been part of a bipartisan deal in the House -- and 35 House Republicans had voted for it.                                                                                                                                                                                  , Second, in July, House Minority Leader Kevin McCarthy decided to pull all Republican members he had nominated for the House committee investigating January 6, following House Speaker Nancy Pelosi's rejection of the presence of GOP Reps. Jim Jordan of Ohio and Jim Banks of Indiana on the panel. (Two Republicans -- Reps. Liz Cheney of Wyoming and Adam Kinzinger of Illinois -- are on the panel but were put there by Pelosi.)                                                      , Both moves were motivated by the same belief: That by opposing an independent commission and by refusing to keep any of their choices on the House committee, Republicans would successfully short-circuit the effectiveness and impact of the investigation before it got started. The idea being that without Republican participation the whole thing would look like a partisan witch hunt, with little practical damage, politically speaking, to the GOP.                               , "Republicans will not be party to their sham process and will instead pursue our own investigation of the facts," McCarthy said at the time.                                                                                                                                                                                                                                                                                                                                                  , With each passing week. however, those twin decisions look worse and worse for Republicans. Consider what we've learned about the January 6 committee's work in just the last few months:                                                                                                                                                                                                                                                                                                     , 1. Marc Short, former Vice President Mike Pence's chief of staff, recently testified before the committee, CNN exclusively reported.                                                                                                                                                                                                                                                                                                                                                          , 2. Former President Donald Trump lost his attempt to keep more than 700 White House documents pertaining to January 6 from the committee. The committee now has all of those documents.                                                                                                                                                                                                                                                                                                       , 3. Former Trump adviser Steve Bannon, who refused a subpoena by the committee, was charged with criminal contempt by the Justice Department.                                                                                                                                                                                                                                                                                                                                                  , What these series of developments mean is that the committee has already made more headway than Republican leaders believed they would when they made the decision to walk away from the panel.                                                                                                                                                                                                                                                                                               , And what's worse for GOP leaders is that they have little visibility into the inner workings of the committee. (While both Cheney and Kinzinger are Republicans, they have been largely ostracized from their party because of their willingness to speak out against Trump's actions on January 6, 2021. That means they have little incentive to keep their fellow Republicans apprised of the goings-on inside the committee.)                                                             , The more people -- especially those at a senior level like Short -- who cooperate with the committee, the more difficult it will be Republicans to dismiss the findings of the report. This won't be about what some Democratic members say happened on January 6 and what role (if any) Trump played in it. Instead, it will be Republicans at highest levels of the Trump administration telling the story of that day. That's far more politically problematic for Republicans in Congress., Notably, McConnell has also struck a different tone on the House committee recently. In a December TV interview, McConnell said the committee is seeking to uncover "something the public needs to know."                                                                                                                                                                                                                                                                                     , Put simply: Republican leaders made a big bet that they could paint the committee as nothing more than a group of disgruntled Democrats using what happened on January 6 to further their own partisan agenda. That bet looks like a loser as of today, with the committee seemingly poised to deliver a far more definitive -- and impactful -- review of that fateful day than many expected.                                                                                               , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/manufacturing-pmi </td>
   <td style="text-align:left;"> 2022-02-01 22:49:36 </td>
   <td style="text-align:left;"> US Markit Manufacturing PMI Revised Higher </td>
   <td style="text-align:left;"> The IHS Markit US Manufacturing PMI was revised higher to 55.5 in January of 2022 from a preliminary of 55, but continued to point to the weakest rise in factory activity since October of 2020, as output growth was muted. Demand conditions also softened further, with new orders rising at the slowest pace since September 2020. Muted client demand was reflected in only a fractional increase in employment. The softer rise in new orders allowed firms to partially work through backlogs of work, which expanded at the slowest pace for 11 months. Nonetheless, firms were at their most upbeat regarding the outlook for output since November 2020. Meanwhile, inflationary pressures remained marked. The rate of cost inflation eased to the softest for eight months, however, as firms also moderated the pace at which selling prices increased. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/balance-of-trade </td>
   <td style="text-align:left;"> 2022-02-01 22:47:00 </td>
   <td style="text-align:left;"> India January Trade Gap Widens </td>
   <td style="text-align:left;"> India's trade deficit widened to USD 17.95 billion in January of 2022, from USD 14.49 billion in the same period last year, a preliminary estimate showed. Imports soared 23.74 percent to USD 52.01 billion on higher purchases of electronic goods (56.31%); coal, coke and briquettes (39.71%); and petroleum and crude products (21.3%) but still is down from a record high of USD 59.48 billion hit last month. At the same time, exports rose by 23.67 percent to USD 34.06 billion amid higher sales of gems and jewellery (74.73%) and engineering goods (24.13%) but fell from an all-time high of USD 37.81 billion hit last month. Non-petroleum imports increased 24.44 percent to USD 40.57 billion, while non-petroleum exports rose 19.4 percent to USD 30.33 billion. Considering the April-January period of 2021, the trade deficit stood at USD 160.4 billion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/technology-60156682?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-02-01 22:45:52 </td>
   <td style="text-align:left;"> Facebook-funded cryptocurrency Diem winds down </td>
   <td style="text-align:left;"> Meta's experiment with cryptocurrency, Diem, is shutting down.                                                                                                                                                                                                                           , The Diem Association, which runs the project, announced the sale of assets of the cryptocurrency venture to Slivergate Capital Corporation for $182million.                                                                                                                              , Launched as Libra in 2019, the project quickly ran into opposition from policy-makers.                                                                                                                                                                                                   , The association said it became clear from "dialogue with federal regulators" that the project could not move ahead.                                                                                                                                                                      , "As a result, the best path forward was to sell the Diem Group's assets, as we have done today to Silvergate," Diem chief executive Stuart Levey wrote.                                                                                                                                  , The Diem Association is a separate organisation from Facebook, although its funding came from the firm.                                                                                                                                                                                  , Facebook intended Diem to be a stablecoin which, as the name implies, is a type of cryptocurrency designed to be less of a financial rollercoaster, its value linked to less volatile assets such as national currencies or commodities.                                                 , But that did not stop the venture causing concern.                                                                                                                                                                                                                                       , "This is an alternative money," Prof Ross Buckley at the University of New South Wales told the BBC in 2019, warning that it was unlikely to get the kind of easy treatment from regulators that an in-game currency might,                                                              , In a research paper, Prof Buckley and colleagues argued the currency was "the ultimate example of something that is highly likely to move from 'too small to care' to 'too big to fail' in a very short period of time".                                                                 , Regulators and politicians did indeed put Diem under the microscope.                                                                                                                                                                                                                     , Facebook's former crypto head and Diem co-creator David Marcus said on Twitter the idea might fare better with a more "acceptable" promoter.                                                                                                                                             , The Financial Times wrote that "regulator hostility put a stop to the Diem experiment".                                                                                                                                                                                                  , Facebook's size, the newspaper argued, meant that Diem was a "challenge to the status quo" and it was surprising the firm had not foreseen the problems ahead.                                                                                                                           , But for Diem's Stuart Levey, the technology it developed addressed many key concerns that have emerged as cryptocurrencies have taken off: "One of our highest priorities in designing the Diem Payment Network was building in controls to protect it against misuse by illicit actors. , "Among these controls was a prohibition on anonymous transactions, which pose both a sanctions and money-laundering risk".                                                                                                                                                               , Mr Levey added: "We look forward to seeing the design choices - and the ideals - of Diem thrive."                                                                                                                                                                                        , Stephane Kasriel, head of Novi - Meta's digital wallet project - tweeted that the company "would continue to execute on our existing fintech plans to create economic opportunities and champion greater financial inclusion today, and as we look ahead to the metaverse".              , Prof. Steven Pinker tries to make sense of the situation...                                                                                                                                                                                                                              , Go behind the scenes at London's Corinthia Hotel                                                                                                                                                                                                                                         , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-02-01 22:39:00 </td>
   <td style="text-align:left;"> Brazilian Equities Lack Direction </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Bovespa, swung between small losses and gains on the first trading day of February, after booking a 7% gain in January. Investors continued to digest prospects of a more hawkish monetary policy from the Federal Reserve, while shifting their attention on corporate results
as the earnings season kicks off with Industrias Romi, releasing its numbers later. Domestically, traders cautiously await the central bank monetary policy decision on Wednesday, anticipating a 150bps hike in the key Selic rate to 10.75%. On the data front, producer prices dropped 0.12% from a month earlier in December, but the decrease was not enough to avoid the annual variation of 28.39% in 2021, the highest level on record. A separate report from Markit Economics showed Brazil's factory contracted for a third straight month in January and to the greatest extent since May of 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-02-01 22:35:00 </td>
   <td style="text-align:left;"> US Stocks Waver to Kick Off February </td>
   <td style="text-align:left;"> US stocks swung between gains and losses on the first trading day of February, pausing after a big rally the day before and following a volatile January month that ended with big losses for the 3 key benchmarks, with the S&amp;P and the Nasdaq recording their worst month since March 2020. Investors continue to digest prospects of a more hawkish monetary policy from the Fed and follow the earnings season. Of the 172 companies in the S&amp;P 500 that have reported earnings to date, 78.5% topped analysts’ estimates, according to Refinitiv. On the corporate front, shares of United Parcel Services were up almost 10% amid strong corporate results and guidance and stocks of Exxon Mobil added 1% after upbeat earnings. Alphabet and GM are also due to report today. Meanwhile, the ISM Manufacturing PMI pointed to a further slowdown in factory activity in January and JOLTS job openings exceeded market forecasts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/manufacturing-pmi </td>
   <td style="text-align:left;"> 2022-02-01 22:35:00 </td>
   <td style="text-align:left;"> Canada Factory Activity Growth at 6-Month Low </td>
   <td style="text-align:left;"> The IHS Markit Canada Manufacturing PMI edged down to 56.2 in January of 2022, from a 56.5 in December, pointing to the lowest reading since July of 2021. Nonetheless, January marked the 19th consecutive expansion in the sector, underpinned by rising levels of new work. Output rose less significantly, despite strong domestic demand, in line with foreign sales. Outstanding business grew at one of the fastest rates in the survey’s history due to lengthened lead times, raw material scarcity, poor weather conditions, and truck shortages due to COVID-19 border restrictions. Both input and output price inflation rates eased, with the former at an 11-month low. Looking forward, hopes of a return to normality, more availability of materials, and prospects of robust demand all contributed to a brighter outlook. </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2022-02-02 09:02:03 UTC +8

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
   <td style="text-align:left;"> 2022-02-02 09:01:39 </td>
   <td style="text-align:left;"> $SPY Now we just need Amazon to do a stock split. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 09:01:09 </td>
   <td style="text-align:left;"> $SPY 3-4 months. 556 pivot point is gonna get touched. Bull rally cometh. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 09:01:08 </td>
   <td style="text-align:left;"> $SPY yeah I know. Same money and the algos just rolling, how boring😂😂computer where a blessing but a curse at the same time.. MFs trapped them selfs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 09:01:07 </td>
   <td style="text-align:left;"> $SPY PAMP DAT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 09:01:04 </td>
   <td style="text-align:left;"> Can you say ALL TIME HIGHS because I have been TELLING YOU 
 
$googl $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 09:00:59 </td>
   <td style="text-align:left;"> $QQQ $SPY These index funds are trading like UVXY right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 09:00:38 </td>
   <td style="text-align:left;"> $SPY ER stocks are still pumping to the very end. They could send spy to 465 tomorrow. Wtff!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 09:00:09 </td>
   <td style="text-align:left;"> $SPY just get done with it tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 09:00:05 </td>
   <td style="text-align:left;"> $BA  #inthecrosshairs  From box bottom support back to box top resistance?  #stocks #stockmarket #stocktrading #options #optionstrading $SPY $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 09:00:02 </td>
   <td style="text-align:left;"> $SPY Federal Reserve Chairman Jerome Powell recently acknowledged the fiscal situation can&amp;#39;t continue on the current trajectory. 
&amp;quot;We&amp;#39;re on an unsustainable path,&amp;quot; Powell told lawmakers last month. &amp;quot;Debt is not at an unsustainable level, but the path is unsustainable -- meaning it&amp;#39;s growing faster than the economy, meaningfully faster than the economy. We have to address that over time. We will address it over time. And the better way to do it is soon.&amp;quot; 
But that won&amp;#39;t be easy -- or politically popular. And it will be complicated by the Fed&amp;#39;s planned interest rate hikes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:59:31 </td>
   <td style="text-align:left;"> $SPY soft </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:59:10 </td>
   <td style="text-align:left;"> $SPY https://www.youtube.com/watch?v=P5sgmuS06qQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:59:00 </td>
   <td style="text-align:left;"> $SPY Looks like we going full penny stock on this one. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:58:55 </td>
   <td style="text-align:left;"> $SPY how do you think we open? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:58:45 </td>
   <td style="text-align:left;"> $SPY rainbow 🌈 🏀shot!! 😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:58:42 </td>
   <td style="text-align:left;"> $SPY big ole green open gap up. Idk where after could rip and dip. But I think the reversal is on. Thank god earnings came to save last weeks shit show </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:58:26 </td>
   <td style="text-align:left;"> $SPY I loaded puts right at eod I’m looking for a drop to $448 to cover. This market is so weak </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:58:16 </td>
   <td style="text-align:left;"> $SPY like a king stands, no body challenge </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:58:14 </td>
   <td style="text-align:left;"> $SPY Bearish tags nonexistent 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:58:12 </td>
   <td style="text-align:left;"> $SPY 2022 FOMC Meetings 
https://www.federalreserve.gov/monetarypolicy/fomccalendars.htm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:58:12 </td>
   <td style="text-align:left;"> $SPY robbinghood introduced options watchlist. Getting more bearish 😅😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:58:01 </td>
   <td style="text-align:left;"> $SPY   i&amp;#39;m gonna hold long on futures here - tight stop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:57:53 </td>
   <td style="text-align:left;"> $SPY paypal got absolutely murdered </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:57:42 </td>
   <td style="text-align:left;"> $spy made 2 g&amp;#39;s this week. ahead of my 1k weekly goal. can take off next week or go for a side hustle goal of 100k annually. we will see </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:57:33 </td>
   <td style="text-align:left;"> $SPY 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:57:29 </td>
   <td style="text-align:left;"> $SPY but way their more.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:57:28 </td>
   <td style="text-align:left;"> $SPY  
 
Welp.  That -12% correction had me thinking that the bullshit was finally over with.  Guess not. 
 
Took profit and back in the dugout, waiting again.  Might even wait for another break of the daily 200 as a prerequisite this time.  Dunno. We&amp;#39;ll see. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:57:20 </td>
   <td style="text-align:left;"> $SPY Tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:57:16 </td>
   <td style="text-align:left;"> $SPY flutes!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:57:12 </td>
   <td style="text-align:left;"> $SPY just wait more towards the 2nd half of feb where we get more telling earnings reports. First half leans more bullish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:57:00 </td>
   <td style="text-align:left;"> $SPY Interest costs alone are projected to surpass $5 trillion over the next 10 years and will amount to nearly half of all federal revenue by 2051, according to the Peter G. Peterson Foundation, an organization focused on raising awareness to the fiscal challenge. 
Kelly pointed out that rising borrowing costs will limit how much money Washington can spend on other priorities like climate change. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:56:51 </td>
   <td style="text-align:left;"> $SPY 433 calls bouts to print </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:56:43 </td>
   <td style="text-align:left;"> $SPY futes ripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:56:36 </td>
   <td style="text-align:left;"> $SPY where’s @tanercapital i miss him </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:56:29 </td>
   <td style="text-align:left;"> $SPY cool down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:56:28 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:56:02 </td>
   <td style="text-align:left;"> $SPY $DWAC It shouldn’t just be truckers everyone should be protesting  other jobs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:56:00 </td>
   <td style="text-align:left;"> $SPY the dow should get delisted </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:55:59 </td>
   <td style="text-align:left;"> $SPY Bridgewater Capital is racist. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:55:46 </td>
   <td style="text-align:left;"> $SPY $DWAC 

https://mobile.twitter.com/TPostMillennial/status/1488323594023223301?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1488323594023223301%7Ctwgr%5E%7Ctwcon%5Es1_&amp;amp;ref_url=https%3A%2F%2Fwww.infowars.com%2Fbreaking-news%2F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:55:37 </td>
   <td style="text-align:left;"> $spy Next leg down coming....Tmrw..... You&amp;#39;re calls.... Worthless.... you think we are rocketing back to new all time highs? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:55:33 </td>
   <td style="text-align:left;"> Nasdaq stats $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:55:28 </td>
   <td style="text-align:left;"> $SPY it’s 4:54 and fools are talking about futures 😂🤷‍♂️🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:55:10 </td>
   <td style="text-align:left;"> $SPY Bears today: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:55:02 </td>
   <td style="text-align:left;"> $SPY If this rip $10 it wouldn&amp;#39;t surprise me one bit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:55:02 </td>
   <td style="text-align:left;"> $SPY 84 ships inport... this is after they began the practice of forcing ships to loiter miles out at sea so they wouldn&amp;#39;t be counted. 
 
Before they played games with ships inport, the records were being broken around 160 ships inport. 
https://twitter.com/MXSOCAL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:54:50 </td>
   <td style="text-align:left;"> $SPY if you&amp;#39;re STILL a bear right now, I think you&amp;#39;re really better off just sitting on the sidelines, as opposed to trying to trade </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:54:41 </td>
   <td style="text-align:left;"> $SPY REKT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:54:31 </td>
   <td style="text-align:left;"> $SPY do people actually pay to join Cramer&amp;#39;s investing club 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:54:16 </td>
   <td style="text-align:left;"> $SPY Reverse Repo Operations 
(fm https://www.newyorkfed.org/markets/desk-operations/reverse-repo#search-operations) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:54:07 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $AAPL $TSLA  
. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:54:04 </td>
   <td style="text-align:left;"> $SPY Delusional Bulls Bought calls end of day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:53:57 </td>
   <td style="text-align:left;"> $SPY Futures are ripping 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:53:49 </td>
   <td style="text-align:left;"> $SPY I king has no friends, only followers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:53:48 </td>
   <td style="text-align:left;"> $PIXY added another run 2/3 On this one so let’s see
$amd $goog $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:53:43 </td>
   <td style="text-align:left;"> $SPY 🅿️🅿️🅿️💯💯💯🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:53:26 </td>
   <td style="text-align:left;"> $SPY Futes look a little…limp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:53:20 </td>
   <td style="text-align:left;"> $SPY  I planned to go to Peru and try some Ayahuasca medicinal tea but after hearing Alex Jones friend tried it and tripped his balls off hallucinating that he was trapped in a giant room with a preying mantis the size of a house plotting his death for what seemed like an eternity, I&amp;#39;m not sure I&amp;#39;m man&amp;#39;s enough🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:53:01 </td>
   <td style="text-align:left;"> $SPY $QQQ the fact that $AAPL and $MSFT didnt make a move after hours gotta tell something! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:52:51 </td>
   <td style="text-align:left;"> $SPY GET REKT Bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:52:43 </td>
   <td style="text-align:left;"> $SPY 
my short portfolio reaction...
let me see Paul.Allen&amp;#39;s card </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:52:43 </td>
   <td style="text-align:left;"> $SPY omg my first big trade ever and its changed my life 🤗🤗🤗🤗 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:52:34 </td>
   <td style="text-align:left;"> $SPY floating on ….. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:52:30 </td>
   <td style="text-align:left;"> $SPY 457 gap up tomorrow. Thanks to Google 🙏🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:52:11 </td>
   <td style="text-align:left;"> $SPY They are going to short tf outta this… I would. Look at the range. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:51:42 </td>
   <td style="text-align:left;"> $SPY Bears are totalky fcked, and knowing them they will not cover at the open waiting for the fairy tale crash.  This is done selling kids, better take your losses tomorrow.  YOU HAVE BEEN WARNED! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:51:28 </td>
   <td style="text-align:left;"> $SPY Bearish! The put/call vol ratio for Friday&amp;#39;s SPY contracts is 0.79, and the market doesn&amp;#39;t wanna pay out all that moolah!🙊 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:51:17 </td>
   <td style="text-align:left;"> $SPY Doesn’t mean it won’t derail tho… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:51:12 </td>
   <td style="text-align:left;"> UPS CEO: US economy could handle higher interest rates

https://www.google.com/amp/s/finance.yahoo.com/amphtml/news/ups-ceo-us-economy-could-handle-higher-interest-rates-192308025.html

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:50:59 </td>
   <td style="text-align:left;"> $SPY Don’t stand in front a freight train going full throttle. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:50:54 </td>
   <td style="text-align:left;"> $SPY downgrades abundant. Flood to meme Stonks or simpcoins as a hedge </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:50:52 </td>
   <td style="text-align:left;"> $SPY   Still think its ABC and one gap up with complete the wave. 
Hourly chart 
 
Since its second wave based on my count it will retrace to 61.8 % ( most common) 
 
Strength of next down will give a clue. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:50:36 </td>
   <td style="text-align:left;"> $SPY just went grocery shopping and sprite is $7.29 plus deposit for a 12 pack. Thanks powell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:50:33 </td>
   <td style="text-align:left;"> $SPY remember bears 🐻 shorting isn’t a long position </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:50:26 </td>
   <td style="text-align:left;"> $SPY the strength </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:50:21 </td>
   <td style="text-align:left;"> $SPY What correction? 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:50:16 </td>
   <td style="text-align:left;"> $SPY $DWAC  😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:50:14 </td>
   <td style="text-align:left;"> U.S. National Debt Tops $30 Trillion as Borrowing Surged Amid Pandemic

https://www.google.com/amp/s/www.nytimes.com/2022/02/01/us/politics/national-debt-30-trillion.amp.html

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:50:03 </td>
   <td style="text-align:left;"> $SPY push it bulls, do it for my gf OF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:49:52 </td>
   <td style="text-align:left;"> $SPY Please take a look at the open interest for $425 2/18 Puts 

😳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:49:48 </td>
   <td style="text-align:left;"> $SPY Bulls and Bears... none of us benefit from inflation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:49:21 </td>
   <td style="text-align:left;"> $SPY Holy crap 455…they couldn’t give those calls away today. Lol 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:49:07 </td>
   <td style="text-align:left;"> $spy $btc.x 😂😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:48:46 </td>
   <td style="text-align:left;"> $SPY  BAG SECURED </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:48:39 </td>
   <td style="text-align:left;"> $SPY Politics and Medicine need to be disentangled to solve the worldwide inflation problem. 
https://www.youtube.com/watch?v=bnMMYJKZvnU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:48:31 </td>
   <td style="text-align:left;"> $SPY gr8. Only $45 away from $500. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:48:12 </td>
   <td style="text-align:left;"> $SPY daddy fell in love with a stripper named Libby but never for a BULL TRAP!! 🌈🐻🥺 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:48:06 </td>
   <td style="text-align:left;"> $SPY after looking at charts and verifying comments it’s clear there is a sizable gap at $400. With 90% of gaps filled historically is this something we see gets filled in short term? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:48:06 </td>
   <td style="text-align:left;"> $SPY 460 tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:47:55 </td>
   <td style="text-align:left;"> $SPY guys... Cramer is bullish on $ARKK now...you know what that means. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:47:43 </td>
   <td style="text-align:left;"> $SPY jk guys idk just like everyone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:46:41 </td>
   <td style="text-align:left;"> $SPY  seems the squeeze is continuing tonight 
4555&amp;#39;s already </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:46:37 </td>
   <td style="text-align:left;"> $SPY never gonna go away HONK HONK $DWAC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:46:21 </td>
   <td style="text-align:left;"> $SPY if u remember those 2 legends u r a real spy og </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:45:59 </td>
   <td style="text-align:left;"> $SPY we can do karaoke tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:45:58 </td>
   <td style="text-align:left;"> $SPY i kinda need another @Blehhhhhh or @Ironbro personalities on here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:45:48 </td>
   <td style="text-align:left;"> $SPY market makers knows everything before goes at wire..how come spy took of before $GOOG split stock..hmm interesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:45:31 </td>
   <td style="text-align:left;"> $SPY stairs down elevator up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:45:07 </td>
   <td style="text-align:left;"> $SPY fundstrat: get ready for a violent rally in 22022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:45:06 </td>
   <td style="text-align:left;"> $SPY money up the ass </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:44:59 </td>
   <td style="text-align:left;"> $SPY The Vix: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:44:58 </td>
   <td style="text-align:left;"> $AMZN Amazon is going to split I am 100% confident it will, they have to, retail are also investors and can boost the stock to new highs. No split since 1998!

Let’s go Jeff Bezos time to pump Amazon to new highs

$GOOGL $AAPL $TSLA $SPY

Never forget Apple and Tesla split

Google will run above EMA9 all day tomorrow algos will trigger it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:44:31 </td>
   <td style="text-align:left;"> $SPY Western Australia. Parents are not allowed to visit their children in the hospital if the parents aren&amp;#39;t vaccinated. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:44:29 </td>
   <td style="text-align:left;"> $SPY $QQQ Mega big tech companies are gonna do well even with higher interest rates and higher inflation, the earnings confirmed it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:44:10 </td>
   <td style="text-align:left;"> $SPY where are these bears the bulls are owning i don&amp;#39;t see them. guessing they took profits after a 10% correction because they learned how trade. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:44:08 </td>
   <td style="text-align:left;"> $SPY Dix printed 51% and Vix flat lining… clear skies. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:44:03 </td>
   <td style="text-align:left;"> $SPY I’m down 6% this week. Damn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:43:47 </td>
   <td style="text-align:left;"> $SPY +10% tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:43:44 </td>
   <td style="text-align:left;"> $SPY Facebook earnings tomorrow and Amazon Thursday. .enough said </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:43:22 </td>
   <td style="text-align:left;"> $SPY nobody care bear </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:43:05 </td>
   <td style="text-align:left;"> $SPY is it even possible for the market to be red with google going up? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:42:36 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA 

J Powell + stock market = ⬆️ 😁

https://www.instagram.com/reel/CZdHv9bhJbC/?utm_medium=copy_link </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:42:29 </td>
   <td style="text-align:left;"> $SPY apple and microsoft is getting on my nerves like why do y’all want to be so different like go green already </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:41:56 </td>
   <td style="text-align:left;"> $SPY 600 tonight?? lol my lawrt </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:41:32 </td>
   <td style="text-align:left;"> $SPY $AMD $GOOG 

One last look before after hours closes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:41:06 </td>
   <td style="text-align:left;"> $SPY bulls what are you playing tomorrow for FB ER? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:41:01 </td>
   <td style="text-align:left;"> $spy $btc.x , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:41:00 </td>
   <td style="text-align:left;"> $SPY undelay!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:40:59 </td>
   <td style="text-align:left;"> $SPY 20 min alert </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:40:39 </td>
   <td style="text-align:left;"> $SPY $5+ premarket open or what?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:40:00 </td>
   <td style="text-align:left;"> $SPY has a poor technical rating and the quality of the setup is also only medium at the moment. https://www.chartmill.com/stock/quote/SPY/technical-analysis?key=84303b30-e7bc-44d7-b0b1-1493858db9a2&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=SPY&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:39:31 </td>
   <td style="text-align:left;"> $SPY I came home nice but I&amp;#39;m going back mean </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:39:17 </td>
   <td style="text-align:left;"> $SPY fuck no.. keep it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:38:30 </td>
   <td style="text-align:left;"> $SPY bears will be buying after spy hits 500$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:38:20 </td>
   <td style="text-align:left;"> $SPY my take here is that we test over the 460 call wall near 461 (1 day chart 200SMA) and then sell off from there. Not as badly as January though. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:37:42 </td>
   <td style="text-align:left;"> $SPY when does January CPI get priced in? Or was that last drop just a preview of what’s to come? (Feb 10th) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:37:36 </td>
   <td style="text-align:left;"> $SPY this looks like it want to head higher, No making sense of this market. It’s a casino! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:37:16 </td>
   <td style="text-align:left;"> $SPY when corporations get to big they are sliced because they take an entire share of the whole market leaving small business like mine with no where to hide, its just a matter of time till the Silicon Valley honey moon is over, the Military made Silicon Valley and at this rate I think its going to be the same Military who’s going to have to bring it down, if they look the other way. Asta la vista baby… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:37:12 </td>
   <td style="text-align:left;"> $SPY does the bear say ouch? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:37:06 </td>
   <td style="text-align:left;"> $SPY sorry bulls punch bowl is empty this quarters numbers are the best you will ever see. Government money is gone. Fed is not your friend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:36:51 </td>
   <td style="text-align:left;"> $SPY paypal holy shit, can&amp;#39;t believe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:36:36 </td>
   <td style="text-align:left;"> $ABML $BTC.X $ADA.X $SPY  
My home tour, circa 2025.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:36:27 </td>
   <td style="text-align:left;"> $SPY dam glad didn’t enter a trade </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:36:05 </td>
   <td style="text-align:left;"> $SPY So everyone ignores PayPal earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:36:02 </td>
   <td style="text-align:left;"> $spy I could not imagine this if I had bought this at 300,  No position myself. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:36:01 </td>
   <td style="text-align:left;"> New Analysis: How smart money knew this bounce was coming. Plus, why tail-chasing in $TSLA makes sense: https://cracked.market/2022/02/how-smart-money-knew-this-bounce-was-coming-plus-while-tail-chasing-in-tsla-makes-sense/ $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:35:56 </td>
   <td style="text-align:left;"> $AMD Let $SPY be green tomorrow and we’re def seeing $137 👀🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:35:49 </td>
   <td style="text-align:left;"> $SPY In all of Europe, only two countries have removed covid restrictions. UK and Denmark. Europe is the 2nd largest economy in the world. 
 
China. Do you know how many of the 1.3 billion people are in hard lockdown? I don&amp;#39;t. The most recent province I heard shut down was Shandong.  101 million population southwest of Beijing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:35:41 </td>
   <td style="text-align:left;"> Be more like Buffet $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:35:37 </td>
   <td style="text-align:left;"> $SPY don’t forget to open a position in Marijuana 💰📈😎🎶💯⏰  Chucky boy is really trying not to screw it up , he’s rapidly pushing legislation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:35:26 </td>
   <td style="text-align:left;"> $SPY my 460c overnight doesnt look too retarded rn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:35:21 </td>
   <td style="text-align:left;"> $SPY $QQQ latexbeed6ebf2bc7ae3914411c8d6f3721e9RBLX 160%
$AAPL 60% 

What was your favorite play today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:34:50 </td>
   <td style="text-align:left;"> $SPY lest go 260 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:34:24 </td>
   <td style="text-align:left;"> $QQQ $SPY bears today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:34:17 </td>
   <td style="text-align:left;"> $SPY Huh, 20 pts? That’s it? Come on bulls those are rookie numbers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:34:16 </td>
   <td style="text-align:left;"> $SPY Only Valdimir Stupidtin  holding this market now. He cant even piss to fill an  egg shell .  Next week moon party </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:33:57 </td>
   <td style="text-align:left;"> $SPY $QQQ Well earnings from $AMZN and $FB coming up, the nightmare could continue for the bears lol 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:33:00 </td>
   <td style="text-align:left;"> $SPY World&amp;#39;s largest ETF sees most significant monthly outflows in its nearly 30-year history </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:32:32 </td>
   <td style="text-align:left;"> $SPY $AMZN earnings ready to piss your pants Bro bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:32:24 </td>
   <td style="text-align:left;"> $SPY But Duhhh Drone Duhhh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:32:11 </td>
   <td style="text-align:left;"> $SPY this should surprise no one who had half an eye on VIX breaking down out of its </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:31:58 </td>
   <td style="text-align:left;"> $SPY big money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:31:46 </td>
   <td style="text-align:left;"> $spy unless Russia spoils the party we are going much much higher tomorrow.. the squeeze would be too much </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:31:35 </td>
   <td style="text-align:left;"> $SPY much easier short at $460. I’ll double down there.  This thing is priming for major dump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:31:31 </td>
   <td style="text-align:left;"> $SPY been here for years - the bulls are all the same accounts... New bears show up every dip, get wiped out and you never see them again 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:31:30 </td>
   <td style="text-align:left;"> $SPY Try ordering a product on Amazon today in Canada. &amp;quot;Undeliverable&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:31:06 </td>
   <td style="text-align:left;"> $QQQ $SPY once Qs get though $370 layer this week.  💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:30:56 </td>
   <td style="text-align:left;"> $SPY didn&amp;#39;t think this would get over 455 in ah. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:30:54 </td>
   <td style="text-align:left;"> $AMD Just wait til Lisa and Jim flatter each other on CNBC at 9:50 tomorrow morning. Gonna be a schmooz fest about the blowout QT and the $XLNX deal. This new run has just started. If I were short, I’d be covering at open. The SMH is gonna moon (except Intel). $QQQ $SPY $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:30:54 </td>
   <td style="text-align:left;"> $SPY like you can tell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:30:22 </td>
   <td style="text-align:left;"> $SPY Bears just giving back the money they took from you, love it!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:30:07 </td>
   <td style="text-align:left;"> $SPY who is your favorite federal reserve board member...mine was Kaplan; but unfortunately, he was removed : ( </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:29:53 </td>
   <td style="text-align:left;"> $SPY so we are just leaving it like that? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:29:45 </td>
   <td style="text-align:left;"> $SPY  Guess we goin to 4560 or 4570 after hours. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:29:44 </td>
   <td style="text-align:left;"> $SPY lol 3 weekends in a row I’ve had a girl ask me my zodiac sign and I always act like I don’t know it so they can tell me and feel smart . Worked every fckin time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:29:36 </td>
   <td style="text-align:left;"> $SPY remember clowns don’t troll with ur real name and photo on  ur account 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:29:27 </td>
   <td style="text-align:left;"> @2kaykim Summed it up pretty well in his last video $SPY $QQQ $TQQQ $SQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:29:25 </td>
   <td style="text-align:left;"> $SPY Bears crashed instead of market 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:29:25 </td>
   <td style="text-align:left;"> $SPY $MSFT $AAPL $GOOG $GOOGL 😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:29:09 </td>
   <td style="text-align:left;"> $SPY I conservatively say $500 by May

But the way this is going we might get there by end of month 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:29:06 </td>
   <td style="text-align:left;"> $SPY pretty incredible what a week can do. We went from end of world to hardly off all time
Highs basically overnight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:28:55 </td>
   <td style="text-align:left;"> $SPY waking up to 460😌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:28:52 </td>
   <td style="text-align:left;"> $SPY take your charts and throw it out the window. TA means shit. Makes no sense. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:28:29 </td>
   <td style="text-align:left;"> $SPY golden. 1hr 458 target. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:28:28 </td>
   <td style="text-align:left;"> $SPY $QQQ Chinese people might use their red envelope money from their new year to buy US stocks tomorrow, might actually be positive for the market lol 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:28:15 </td>
   <td style="text-align:left;"> $BTC.X $MARA $RIOT $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:28:14 </td>
   <td style="text-align:left;"> $SPY  
 
What if I told you that I called the bottom last week? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:28:00 </td>
   <td style="text-align:left;"> $SPY https://www.youtube.com/watch?v=9_VeHW6vPoU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:27:59 </td>
   <td style="text-align:left;"> $SPY   I recently had an experience when talking about my Jewish history somebody told me they were offended by me talking about how my relatives having  been burned and gassed.  When people find history too  offensive and ugly to remember it they&amp;#39;re doomed to repeat it. The world saw 6.5 million Jews murdered during World War II.   Why do I get the feeling the next war we&amp;#39;ll see a few million gone in a Flash. It bothers me deeply that somebody found my own history to be offensive. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:27:33 </td>
   <td style="text-align:left;"> $SPY we were at 430 just 3 trading days ago insane </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:27:08 </td>
   <td style="text-align:left;"> I will keep adding to my holdings every month will keep doing this over the long haul $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:26:55 </td>
   <td style="text-align:left;"> $SPY sharing what we have and a weird scenario which looks legit though </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:26:46 </td>
   <td style="text-align:left;"> $SPY rip to me sold calls too early at 442 and sheesh if anyone lost money w puts feel free to reply or like </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:26:19 </td>
   <td style="text-align:left;"> $SPY sad seeing many bears make the same mistake here that I made in late 2018 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:25:46 </td>
   <td style="text-align:left;"> These are my current open positions. You can track it all at https://spxyer.com/portfolio/ All alerts are posted FREE and no need to signup. Cheers $AAPL $SPY $GOOGL $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:25:43 </td>
   <td style="text-align:left;"> $SPY 460 then back down following big red trend line. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:25:37 </td>
   <td style="text-align:left;"> $SPY good job guys ,my puts are F’d </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:25:33 </td>
   <td style="text-align:left;"> $SPY $QQQ $FB $GOOGL $AMD 

HEY BEARS,  WHAT HAPPENED TO THE CRASH ???!? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:25:20 </td>
   <td style="text-align:left;"> $SPY sad rape for the bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:25:19 </td>
   <td style="text-align:left;"> $SPY dont worry the crash is transitory </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:25:16 </td>
   <td style="text-align:left;"> Turned $1,171 Into Over $5,000,000 In 256 Business Days 
 
is what his stocktwits profile states 
 
My opinion, one massive fake marketing job in an attempt to entice you to fork over your money to their pay service . Why does the thread beg you to join their pay service on an ongoing basis?   
 
$study $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:24:29 </td>
   <td style="text-align:left;"> $SPY Oh but posting old songs is so much more fun. 
https://www.thedrive.com/the-war-zone/44117/another-flotilla-of-russian-warships-is-about-to-enter-the-english-channel </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:24:25 </td>
   <td style="text-align:left;"> $SPY google broke 3k Lolol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:24:10 </td>
   <td style="text-align:left;"> $SPY Dem putz iz toast! 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:24:05 </td>
   <td style="text-align:left;"> $SPY and just like that we gapped over resistance after hours. 460 tomorrow is the next stop up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:23:43 </td>
   <td style="text-align:left;"> Stay humble keep learning 🙂 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:23:36 </td>
   <td style="text-align:left;"> $SPY they may have to rafters down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:23:22 </td>
   <td style="text-align:left;"> $SPY truckers gonna save this country and my puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:23:15 </td>
   <td style="text-align:left;"> $SPY $QQQ Strong earnings along with strong economic data and signs of easing inflation are gonna send this market to the moon lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:23:01 </td>
   <td style="text-align:left;"> $SPY did 455 just break in AH? Lol nice </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:22:48 </td>
   <td style="text-align:left;"> $GOOGL $SPY $QQQ 
Hurry everyone. Buy those Google calls asap!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:22:44 </td>
   <td style="text-align:left;"> $SPY The market isn&amp;#39;t in a bubble.  It&amp;#39;s a super bubble.  Mr Workmans still not convinced correction is over. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:22:38 </td>
   <td style="text-align:left;"> $SPY so goated </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:22:35 </td>
   <td style="text-align:left;"> $SAND.X over 4.23 it’s game over for the teddies 460sh $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:22:11 </td>
   <td style="text-align:left;"> $SPY prolly wake up to this being 460 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:22:11 </td>
   <td style="text-align:left;"> Biden getting ready to hide like TRUDEAU $SPY $DWAC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:22:10 </td>
   <td style="text-align:left;"> Moving higher on futures $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:21:16 </td>
   <td style="text-align:left;"> $SPY I feel like tom </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:21:00 </td>
   <td style="text-align:left;"> $SPY damn sum angry folks up in here. I&amp;#39;ve lost 158k last two days but up twice that in last 6 weeks. I&amp;#39;m pissed at myself for getting complacent. But that&amp;#39;s &amp;quot;transitory&amp;quot; happens to us all. What determines our anger lol is our ability/inability to adjust n adapt. Anyways anger is an emotion. Emotions lead to losses....gl peeps </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:20:30 </td>
   <td style="text-align:left;"> $SPY We are here EZ money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:20:25 </td>
   <td style="text-align:left;"> $SPY everyone buy Google tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:20:06 </td>
   <td style="text-align:left;"> $SPY Everyone.  There&amp;#39;s no Need. To. Be. Unhappy. 
https://www.youtube.com/watch?v=CS9OO0S5w2k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:20:05 </td>
   <td style="text-align:left;"> $SPY futures rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:19:53 </td>
   <td style="text-align:left;"> $SPY Futes don’t matter right?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:19:52 </td>
   <td style="text-align:left;"> $AMC 200 more watchers daily $SPY $NYA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:19:40 </td>
   <td style="text-align:left;"> $SPY MOAR debt....but MOAR importantly.....MOOOAAAAAR inflation.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:19:31 </td>
   <td style="text-align:left;"> $SPY volatility will be high. Bulls will have rude awakening </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:19:30 </td>
   <td style="text-align:left;"> $spy $ndx $spx $qqq https://www.youtube.com/watch?v=37aoAp8sALU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:19:29 </td>
   <td style="text-align:left;"> $SPY It&amp;#39;s like magic how bears vanish after their money disappears. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:19:10 </td>
   <td style="text-align:left;"> $SPY FJB $DWAC USA truckers heading to BIDENS house … 50,000 heading there 

https://mobile.twitter.com/IvoryHecker/status/1488328627414519808?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1488328627414519808%7Ctwgr%5E%7Ctwcon%5Es1_&amp;amp;ref_url=https%3A%2F%2Fwww.infowars.com%2Fbreaking-news%2F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:19:05 </td>
   <td style="text-align:left;"> $SPY spy just crossed over 455 in ah trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:18:53 </td>
   <td style="text-align:left;"> $SPY I’m really shocked this recovered like this. This whole month has to be historical in some way. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:18:51 </td>
   <td style="text-align:left;"> $SPY 
Welps. I give up being bearish for now. Imma wait till March is over. Going to buy those $GOOGL  calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:18:39 </td>
   <td style="text-align:left;"> $dis $dia $spy $crm https://www.youtube.com/watch?v=4TqM0peojuk&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:18:21 </td>
   <td style="text-align:left;"> $SPY damn bought puts and just saw this dude at my Wendy’s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:18:03 </td>
   <td style="text-align:left;"> $SPY the after hours movement is from meet Kevin frantically buying in 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:18:03 </td>
   <td style="text-align:left;"> $SPY there better be an epic meltdown before Friday… the last 3 days were too much and every logical investor should recognize that </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:17:58 </td>
   <td style="text-align:left;"> $SPY I play both teams. Never loyal to the red or green team. I always play the winning team. Right now I&amp;#39;m playing the green team. So let&amp;#39;s go. Pump it one last time. Short-term bullish, long term extremely bearish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:17:54 </td>
   <td style="text-align:left;"> Tomorrow $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:17:53 </td>
   <td style="text-align:left;"> $SPY if bears gonna let the news media cram that big fear dick down their throats all day, they might as well get an only fans account and actually profit from it…🤷🏻‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:17:51 </td>
   <td style="text-align:left;"> $SPY if this forms a h&amp;amp;s pattern, I will downgrade my PT to 370, will be nasty to bulls oh my god 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:17:46 </td>
   <td style="text-align:left;"> $SPY tomorrow is gonna be Festival with $GOOG and $AMD contributions 🚀🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:17:44 </td>
   <td style="text-align:left;"> $SPY yeah to the moon!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:17:42 </td>
   <td style="text-align:left;"> $BTC.X $SPY last week the narrative was nuclear war imminent, this week is diplomacy bringing peace. Enjoy the tendies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:17:37 </td>
   <td style="text-align:left;"> $SPY Saved from a recession by the PPT again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:17:36 </td>
   <td style="text-align:left;"> $SPY how bout the ol pump and dump tomorrow morning? That’d be fun right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:17:12 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY $SQQQ The U.S. set a new record today, revealing 4.6 million more jobs than unemployed workers in December. And some 4.3 million people quit their job in December, the third highest print in series history. That&amp;#39;s only going to drive wages higher, most likely, which won&amp;#39;t help the inflation story much. Bumpy roads still ahead.

https://www.cnbc.com/2022/02/01/there-were-4point6-million-more-job-openings-than-unemployed-workers-in-december.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:17:03 </td>
   <td style="text-align:left;"> $SPY Mfs want to censor people and intrude in their personal life like it’s some fucking luxury..take your foreign views the fuck out here. Specially Texas!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:16:45 </td>
   <td style="text-align:left;"> $SPY convoy to DC let’s go $TSLA 

https://youtu.be/518Ekf5zeQU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:16:40 </td>
   <td style="text-align:left;"> $SPY SUKAS WILL BE PUNCHED OUT SOON  https://www.usatoday.com/story/news/politics/2022/02/01/national-debt-covid-government-spending/9239402002/?gnt-cfr=1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:16:21 </td>
   <td style="text-align:left;"> $SPY full ported calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:16:15 </td>
   <td style="text-align:left;"> $SPY Slow grinding to $460.00😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:15:54 </td>
   <td style="text-align:left;"> $SPY smells like market crash tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:15:47 </td>
   <td style="text-align:left;"> $SPY Tomorrow $goog will push the $QQQ over the SMA200 and let&amp;#39;s keep this pump going. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:15:47 </td>
   <td style="text-align:left;"> $SPY yah we be ripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:15:15 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA THEY ARE THE IOWA STATE CYCLONES? WHY NOT TORNADOES? I GUESS THAT…HITS…A LITTLE TOO CLOSE TO HOME 🌪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:14:55 </td>
   <td style="text-align:left;"> $GOOG sub $200 for shares? Im all in for real. This alone will bust $SPY 600 easily </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:14:46 </td>
   <td style="text-align:left;"> $SPY SUPPLY CRUNCH coming 

https://youtu.be/NUlucYAhS04 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:14:33 </td>
   <td style="text-align:left;"> $SPY 
I pulled all the short es orders, not a fan of overnights when I have complete control of trades, gonna check tomorrow and take it from there, we are almost at an inflection point. Feels super bully, so I gotta think bout some things and maybe some homework. ☮️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:14:16 </td>
   <td style="text-align:left;"> $GOOGL new highs tomorrows..the  $3019 52wks  highs is only 20$ is nothing with the stock split news ! Everyone will Fomo in tomrrow $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:14:08 </td>
   <td style="text-align:left;"> $SPY have a  napkin for that finger full of shit!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:14:06 </td>
   <td style="text-align:left;"> $SPY 

LOTS of mon&amp;#39; rollin in dad

@TSB11 

😎😎📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:13:38 </td>
   <td style="text-align:left;"> $SPY how are your puts doing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:13:35 </td>
   <td style="text-align:left;"> $SPY not going to lie I ate shit yesterday and today! Good shit for the bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:13:29 </td>
   <td style="text-align:left;"> $SPY $QQQ Market gonna up massively on $GOOGL earnings tomorrow and possibly on the jobs report this Friday too, looks like it will be a great week for the bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:13:19 </td>
   <td style="text-align:left;"> $SPY uhhhhh

OMG

is @Call_Me_Put banned !???

😭😭📈👎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:13:03 </td>
   <td style="text-align:left;"> $SPY me to my puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:12:57 </td>
   <td style="text-align:left;"> $SPY YALL thought CANADA had protests …. USA truckers next $TSLA 

https://m.facebook.com/groups/428429165022269 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:12:51 </td>
   <td style="text-align:left;"> $SPY but it’s okay, it’s clear, it the same bread rolling in circles with no where to escape. someone is holding a hot key, that eventually it’s going to get so hot their not going to be able to open shit… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:12:31 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;m just gonna pretend I&amp;#39;m a normie bull so they tank this. IM BUYING SO MUCH TOMORROW OMG AND BEARS DUMB YEAH HAHA BEARS GET PWNED </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:12:07 </td>
   <td style="text-align:left;"> $SPY and they keep on buying this dio holy shit I’d assume they slow down but last 3 days dark pools been buying heavy. GEX still accelerating </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:12:02 </td>
   <td style="text-align:left;"> DJIA -2.6% YTD 
S&amp;amp;P 500 -4.6% YTD 
NAS Comp -8.3% YTD 
Russell 2000 -8.7% YTD 
 
$DIA $SPY $QQQ $RUT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:11:51 </td>
   <td style="text-align:left;"> $SPY $QQQ Why do some Asian markets closed for multiple days for Chinese New Year lol, should just like us, one day is more than enough </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:11:49 </td>
   <td style="text-align:left;"> $SPY seeing some really strange prints today on the 2/2 puts today. Like 20k volume on the $370p’s? If it was buying to cover he threw away 40 grand instead of waiting a day? I need not mention the 448 and 450s. Just food for thought. Stay nimble out there. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:11:35 </td>
   <td style="text-align:left;"> $Spy $btc.x 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:11:08 </td>
   <td style="text-align:left;"> $SPY Gap to fill on the hourly around 462-464 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:11:02 </td>
   <td style="text-align:left;"> $PYPL $SPY $SOFI $AAPL $FB  200k in 200$ PYPL weekly Calls. Looking juicy for tomorrow 🙏🏻🙏🏻. PYPL will bounce and hit 250 by morning 🙏🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:10:56 </td>
   <td style="text-align:left;"> $SPY imagine not buying the dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:10:50 </td>
   <td style="text-align:left;"> $SPY  
 
I can&amp;#39;t believe not a single person has found the hidden message in the chart </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:10:44 </td>
   <td style="text-align:left;"> $SPY my favorite drink 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:10:26 </td>
   <td style="text-align:left;"> $SPY 467 perhaps before taking a hit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:10:15 </td>
   <td style="text-align:left;"> $SPY Just buy and hold long term...markets will continue to grind higher...sure they may come down...10... 20 percent but if you are in for the long haul what does it matter as you will just add to your position....the fortune 500 companies will continue to do what they do best...create fortunes.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:10:13 </td>
   <td style="text-align:left;"> $SPY It&amp;#39;s good to be alive. 
https://www.youtube.com/watch?v=fNFzfwLM72c </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:09:57 </td>
   <td style="text-align:left;"> $SPY no stopping, let’s rock on until 470 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:09:55 </td>
   <td style="text-align:left;"> $SPY tomorrow another 2% up day reachin for those ath&amp;#39;s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:09:47 </td>
   <td style="text-align:left;"> $SPY 460 tmr and i post my gf onlyfans with free sub for 1 week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:09:46 </td>
   <td style="text-align:left;"> $SPY 🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:09:44 </td>
   <td style="text-align:left;"> $SPY bought my puts weeks away, #iykyk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:09:36 </td>
   <td style="text-align:left;"> Large caps $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:09:26 </td>
   <td style="text-align:left;"> $SPY idk.... looks more like the anticipation of a right shoulder to me. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:09:23 </td>
   <td style="text-align:left;"> $SPY bears learn trading from Krusty the clown </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:09:22 </td>
   <td style="text-align:left;"> Stocks closed higher on Wall Street Tuesday, getting February off to a strong start after the January consolidation 
 
The S&amp;amp;P 500 added 0.7%, as did the NAS Comp. The DJIA added 0.8%. 
 
$SPY $QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:09:20 </td>
   <td style="text-align:left;"> $SPX $SPY $ES_F $VIX - The markets are between a rock and a hard place. 
 
The moment they start going up...interest rates go up as well, and the market comes down. It doesn&amp;#39;t crash...but it can&amp;#39;t go up too much either. Why? 
 
Multiples compression. Earnings do NOT matter. It&amp;#39;s the multiples that matter. All of the mega caps are trading at ~30 times earnings. Historically, that&amp;#39;s high. Very high. Typical is ~10. Let that sink in. 
 
Again, actual earnings do NOT matter. 
 
And then...the Fed. The (almost) free money spigot will be turned off shortly. And then the draining begins. And it&amp;#39;ll keep draining until something breaks. 
 
You literally cannot have a market less than 10% off it&amp;#39;s ATH, which is wildly out of line of fundamentals and trendlines and a rising interest rate environment, and expect...WHAT? More ATHs?? The market to go up somewhat? Stay stagnant? Go down (gasp)? 
 
Strap your seatbelts on...&amp;#39;cause...Kansas is goin bye bye. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:09:17 </td>
   <td style="text-align:left;"> Simple yet affective $BRK.B $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:09:16 </td>
   <td style="text-align:left;"> $SPY we can read the chart perfect!! There’s just reason and logic to this shit!! Should it be this extended when all my neighbors around all contractors, tell me the same shit!! People don’t have money to pay for the service they want and the ones that do want a discount… and we all think the same think. Fuck you!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:09:11 </td>
   <td style="text-align:left;"> $SPY personally I want this to bounce off $450 2-3 times. Then go ALL IN. On calls 2-3 weeks out for 470. What do you all think? 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:08:37 </td>
   <td style="text-align:left;"> $SPY only loser gamblers hoping on crashes every other day. Buy dips and wait patiently stop hoping for negativity to feed you gains you cocroaches. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:08:17 </td>
   <td style="text-align:left;"> $SPY permabulls will still make a ton of money in the market because long term it trends up. Permabears will just honestly lose all their money long term. You can be a bear with good timing and make good bank. but know when the dip has reversed you cant hold puts forever. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:08:13 </td>
   <td style="text-align:left;"> $SPY FOMO buying and short covering = epic bounce… now waiting for crash 2.0.. don’t make me wait forever SPY😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:07:34 </td>
   <td style="text-align:left;"> $spy ah trading in the later hours was really sloppy.  Lots of .10 cent spreads. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:07:21 </td>
   <td style="text-align:left;"> $SPY LOL BEAR

Earnings beats EVERYWHERE I LOOK and EVERYTHING is MASSIVELY ROCKETING HIGHER !!!!!!

OKAY !!

🙂🙂📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:07:03 </td>
   <td style="text-align:left;"> $SPY keep buying calls. If everyone does this will drop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:06:56 </td>
   <td style="text-align:left;"> $SPY yeah we good we&amp;#39;re  transitory now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:06:54 </td>
   <td style="text-align:left;"> $SPY id rather pay 50 bucks a month to an ugly ass girls OF before i buy this overinflated POS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:06:51 </td>
   <td style="text-align:left;"> $SPY BULL TRAP MEGA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:06:49 </td>
   <td style="text-align:left;"> $SPY who bought puts this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:06:48 </td>
   <td style="text-align:left;"> $GOOGL as tempting as it is I can’t let fomo take over …I’ll be catching the dip at $2850 going balls deep then should see $4500 before split in July but it’s running way too hot on technicals atm $TSLA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-02-02 08:06:44 </td>
   <td style="text-align:left;"> $SPY 
BEARS STILL WAITING FOR 420 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 09:01:04 </td>
   <td style="text-align:left;"> Can you say ALL TIME HIGHS because I have been TELLING YOU 
 
$googl $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 09:00:59 </td>
   <td style="text-align:left;"> $QQQ $SPY These index funds are trading like UVXY right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 09:00:23 </td>
   <td style="text-align:left;"> $QQQ From down ~1% to Up 1.61% today. QQQ up over 10% in three days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:58:12 </td>
   <td style="text-align:left;"> $QQQ futes ripping. Green Day tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:55:58 </td>
   <td style="text-align:left;"> $QQQ anyone buying puts tomorrow at 370? resistance </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:54:07 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $AAPL $TSLA  
. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:53:01 </td>
   <td style="text-align:left;"> $SPY $QQQ the fact that $AAPL and $MSFT didnt make a move after hours gotta tell something! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:51:12 </td>
   <td style="text-align:left;"> UPS CEO: US economy could handle higher interest rates

https://www.google.com/amp/s/finance.yahoo.com/amphtml/news/ups-ceo-us-economy-could-handle-higher-interest-rates-192308025.html

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:51:07 </td>
   <td style="text-align:left;"> $QQQ YTD 2022 has an uncanny resemblence to YTD 2008, if it follows short term will see the rally we are seeing now followed by a decline thru Feb to mid march then rallies back up until June where up on it went into free fall </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:50:14 </td>
   <td style="text-align:left;"> U.S. National Debt Tops $30 Trillion as Borrowing Surged Amid Pandemic

https://www.google.com/amp/s/www.nytimes.com/2022/02/01/us/politics/national-debt-30-trillion.amp.html

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:50:02 </td>
   <td style="text-align:left;"> $QQQ did anyone else added $370 last minute calls  after the news on $GOOGL 👀? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:48:46 </td>
   <td style="text-align:left;"> $QQQ Pump-p-p-pump it up! So I can sh-sh-sh-short again! 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:48:33 </td>
   <td style="text-align:left;"> $QQQ  over 7 milly just casually on the L2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:44:29 </td>
   <td style="text-align:left;"> $SPY $QQQ Mega big tech companies are gonna do well even with higher interest rates and higher inflation, the earnings confirmed it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:43:43 </td>
   <td style="text-align:left;"> $QQQ US House Majority Leader Hoyer tested positive for COVID-19, according to Fox&amp;#39; Pergram 
Via Twitter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:43:31 </td>
   <td style="text-align:left;"> $QQQ Tomorrow QQQs should cross comfortably above 200 SMA. A Good sign for bulls and for bears to be nervous to close shorts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:42:36 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA 

J Powell + stock market = ⬆️ 😁

https://www.instagram.com/reel/CZdHv9bhJbC/?utm_medium=copy_link </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:40:47 </td>
   <td style="text-align:left;"> $QQQ it amazes me the attitude in stocks. You people don’t give a rats ass about the companies your investing in. Only about tomorrow’s gains   These companies breaking record profits can not sustain the earnings once the fed has started raising rates. I’m sure it will go up but your gonna see an explosion down.  You can can’t add in rate increase until you know what they are!!  

You think Jan was bad it’s nothing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:39:57 </td>
   <td style="text-align:left;"> $AMZN I’m willing to bet Amazon will be the only FAA(N)G to disappoint. Will drop 10% to be further negative YoY, while all the others are up 50-100%. $QQQ Feel bad for the holders, not only did you make nothing, but you missed out on epic gains in all the other names. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:39:50 </td>
   <td style="text-align:left;"> $QQQ Un-fudging believable...  Did these companies not take a hit, or what?  What&amp;#39;s going on, they were already propped up...  How are they still going up?@! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:38:21 </td>
   <td style="text-align:left;"> $QQQ Bears have no choice but to sell and buy in now, unless they like eating cat food. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:36:01 </td>
   <td style="text-align:left;"> New Analysis: How smart money knew this bounce was coming. Plus, why tail-chasing in $TSLA makes sense: https://cracked.market/2022/02/how-smart-money-knew-this-bounce-was-coming-plus-while-tail-chasing-in-tsla-makes-sense/ $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:35:21 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:34:24 </td>
   <td style="text-align:left;"> $QQQ $SPY bears today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:33:57 </td>
   <td style="text-align:left;"> $SPY $QQQ Well earnings from $AMZN and $FB coming up, the nightmare could continue for the bears lol 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:32:14 </td>
   <td style="text-align:left;"> $QQQ so 370 is the number… interesting.. puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:31:06 </td>
   <td style="text-align:left;"> $QQQ $SPY once Qs get though $370 layer this week.  💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:30:54 </td>
   <td style="text-align:left;"> $AMD Just wait til Lisa and Jim flatter each other on CNBC at 9:50 tomorrow morning. Gonna be a schmooz fest about the blowout QT and the $XLNX deal. This new run has just started. If I were short, I’d be covering at open. The SMH is gonna moon (except Intel). $QQQ $SPY $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:29:27 </td>
   <td style="text-align:left;"> @2kaykim Summed it up pretty well in his last video $SPY $QQQ $TQQQ $SQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:28:28 </td>
   <td style="text-align:left;"> $SPY $QQQ Chinese people might use their red envelope money from their new year to buy US stocks tomorrow, might actually be positive for the market lol 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:26:22 </td>
   <td style="text-align:left;"> $TSLA $VOO $QQQ Groundhog day tomorrow.   Will this year be a repeat of 2020? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:25:33 </td>
   <td style="text-align:left;"> $SPY $QQQ $FB $GOOGL $AMD 

HEY BEARS,  WHAT HAPPENED TO THE CRASH ???!? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:24:13 </td>
   <td style="text-align:left;"> $QQQ just need to be up 3% (unlikely) tmr and then amzn beat and split for another 3% up to absolutely squeeze the bears and burn all puts. This market is so wow everyday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:23:30 </td>
   <td style="text-align:left;"> $AMD $NVDA $QQQ  They always rotate back to tech. Always. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:23:15 </td>
   <td style="text-align:left;"> $SPY $QQQ Strong earnings along with strong economic data and signs of easing inflation are gonna send this market to the moon lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:22:48 </td>
   <td style="text-align:left;"> $GOOGL $SPY $QQQ 
Hurry everyone. Buy those Google calls asap!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:20:49 </td>
   <td style="text-align:left;"> $btc.x $tsla $qqq $aapl $msft https://www.youtube.com/watch?v=JnaAE_VcHqs&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:20:33 </td>
   <td style="text-align:left;"> $QQQ THESE PONZI ARTISTS WILL FALL UNLESS MORE FIAT PRINTED. Earnings wont matter either </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:19:56 </td>
   <td style="text-align:left;"> $aapl $qqq $ndx https://www.youtube.com/watch?v=KnhPvpaJEeo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:19:30 </td>
   <td style="text-align:left;"> $spy $ndx $spx $qqq https://www.youtube.com/watch?v=37aoAp8sALU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:18:50 </td>
   <td style="text-align:left;"> $QQQ I play both ways but it never pays to be bearish for very long… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:17:12 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY $SQQQ The U.S. set a new record today, revealing 4.6 million more jobs than unemployed workers in December. And some 4.3 million people quit their job in December, the third highest print in series history. That&amp;#39;s only going to drive wages higher, most likely, which won&amp;#39;t help the inflation story much. Bumpy roads still ahead.

https://www.cnbc.com/2022/02/01/there-were-4point6-million-more-job-openings-than-unemployed-workers-in-december.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:15:47 </td>
   <td style="text-align:left;"> $SPY Tomorrow $goog will push the $QQQ over the SMA200 and let&amp;#39;s keep this pump going. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:15:46 </td>
   <td style="text-align:left;"> $QQQ Closed back above the 200 day moving average </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:15:15 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA THEY ARE THE IOWA STATE CYCLONES? WHY NOT TORNADOES? I GUESS THAT…HITS…A LITTLE TOO CLOSE TO HOME 🌪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:13:29 </td>
   <td style="text-align:left;"> $SPY $QQQ Market gonna up massively on $GOOGL earnings tomorrow and possibly on the jobs report this Friday too, looks like it will be a great week for the bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:12:02 </td>
   <td style="text-align:left;"> DJIA -2.6% YTD 
S&amp;amp;P 500 -4.6% YTD 
NAS Comp -8.3% YTD 
Russell 2000 -8.7% YTD 
 
$DIA $SPY $QQQ $RUT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:11:51 </td>
   <td style="text-align:left;"> $SPY $QQQ Why do some Asian markets closed for multiple days for Chinese New Year lol, should just like us, one day is more than enough </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:11:47 </td>
   <td style="text-align:left;"> $QQQ MM and cnbc gonna need some new FUD asap. Earnings from big tech showing that interest rate hikes won’t mean sh**.  Maybe they gonna start a forest fire or purposely crash a Tesla to start new FUD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:09:22 </td>
   <td style="text-align:left;"> Stocks closed higher on Wall Street Tuesday, getting February off to a strong start after the January consolidation 
 
The S&amp;amp;P 500 added 0.7%, as did the NAS Comp. The DJIA added 0.8%. 
 
$SPY $QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:07:12 </td>
   <td style="text-align:left;"> $QQQ 370 could face resistance </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:03:53 </td>
   <td style="text-align:left;"> $SPY  $DIA $QQQ $IWM $SOX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:01:54 </td>
   <td style="text-align:left;"> Seems EVERYONE now knows what PAJAMA knew last week: That this market is going to V RALLY INSANE back to all time highs as we are FREE AND CLEAR to do so thank you Jerome Powell free money and QE bananas 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:01:11 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ :&amp;quot;:&amp;quot;: 
 
 
Account Challenge Update:-  
Start Date: Jan 3, 2022  
Starting Balance: $1,700  
Current Balance: $79,584 
Goal: $100,000 by end of February.  
Strategy: Swing Trade Options, Stocks  
  
Watch out for next play👓 amazing-chat-room.stocksboss.xyz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 08:01:05 </td>
   <td style="text-align:left;"> $QQQ 

6% of total retail trading volume today was in a QQQ related fund. 

That’s simply outrageous. 

Y’all are going to get burned real hard on the way down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:57:55 </td>
   <td style="text-align:left;"> $QQQ my portfolio still down 25% from day trading over past year or two. Y’all recommend holding this for a year to make my money back? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:54:10 </td>
   <td style="text-align:left;"> $QQQ weekly 
https://www.tradingview.com/x/fDcOPHqz/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:53:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $IWM Buy signal for TNA, stop loss @ 54.93. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:53:21 </td>
   <td style="text-align:left;"> Futures literally PINNED to session highs they aren’t allowing a DIME of selling LETS FKN GO tomorrow BIGGEST rally of the year!!! 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:51:09 </td>
   <td style="text-align:left;"> $SPY $QQQ but who cares make it 60 trillion how long is the Chinese will pay it

https://www.washingtonexaminer.com/policy/economy/us-debt-exceeds-30-trillion-for-first-time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:50:10 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA @PurpleReign8 is the biggest bear on ST I can’t hang 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:47:17 </td>
   <td style="text-align:left;"> $DIA $Spy $qqq $btc-x $MRNA
Covid will end because the politicians cant keep you locked up, restricted and mad ,when they need your &amp;quot;vote&amp;quot; for midterms. Soros dumped 125 million into Dems superpac..Hes done playing for now... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:46:59 </td>
   <td style="text-align:left;"> $UVXY $SPY $QQQ $IWM $DIA 
🚨 for fun 🚨 NFA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:44:49 </td>
   <td style="text-align:left;"> $QQQ wow nice </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:43:29 </td>
   <td style="text-align:left;"> DID. YOU. LISTEN. 
 
ARE. YOU. SMILING. 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:43:19 </td>
   <td style="text-align:left;"> $DIA $IWM $QQQ $SPY I was wrong here,  the sell off  was actually -100%-done, my bad. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:40:02 </td>
   <td style="text-align:left;"> $AMD $QQQ Bull Market is over 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:39:50 </td>
   <td style="text-align:left;"> $GOOGL is going to lift $QQQ to the fucking moon on this split news and It won&amp;#39;t need any help. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:39:23 </td>
   <td style="text-align:left;"> $QQQ watch for the bounce on the vix to know when to short and when premiums are likely discounted </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:37:04 </td>
   <td style="text-align:left;"> $PYPL further downside is that $QQQ drops them from their basket. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:34:19 </td>
   <td style="text-align:left;"> $QQQ all we need is one miss in a big name  or some fake news eg about Ukraine- to take the entire market down 5%. It’s all teed up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:31:56 </td>
   <td style="text-align:left;"> $SPY $QQQ $GOOG $AMD  you can never win against the casino. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:29:58 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA NASDAQ IS STILL UNDER 200 DAY MOVING AVERAGE BULLS YOU ARENT OUT OF THE WOODS YET I WOULD KNOW BECAUSE IM A BEAR 🥤🐻🍿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:29:24 </td>
   <td style="text-align:left;"> $SPY $QQQ With the market whipping up and down like this I&amp;#39;ll bet it&amp;#39;s zero-summing everybody&amp;#39;s account </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:28:40 </td>
   <td style="text-align:left;"> $QQQ $GOOGL and $AMD monster beats... tech rally tomorrow... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:28:20 </td>
   <td style="text-align:left;"> $QQQ 
Selling premium tomorrow —— F you bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:26:44 </td>
   <td style="text-align:left;"> $QQQ Perfect setup up for and major dip. Big money took a breather from selling as prices were getting back to where they bought in

Retail ran it up so smart money could take more profits🤣….. Good job! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:25:52 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:25:24 </td>
   <td style="text-align:left;"> VIDEO: Broad Market Technical Analysis Chart 1/31/2022 $SPY $XLF $QQQ $GOOGL $VRNOF https://www.chartguys.com/daily-market-videos/4122/huge-earnings-reaction </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:24:01 </td>
   <td style="text-align:left;"> $QQQ $SPY does this even matter anymore..?
https://www.foxbusiness.com/politics/national-debt-tops-30-trillion </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:23:55 </td>
   <td style="text-align:left;"> $QQQ  opens under the 200 day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:21:42 </td>
   <td style="text-align:left;"> $QQQ surely the big stocks can’t carry this forever…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:16:23 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA $GOOG CARRYING THE NASDAQ AS USUAL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:16:10 </td>
   <td style="text-align:left;"> $QQQ $SPY Looks like NQ futures just bounced from the daily low for today, if you&amp;#39;re buying here, you&amp;#39;re most likely buying at the bottom for the day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:14:46 </td>
   <td style="text-align:left;"> $QQQ well im pretty sure they are paying out all theese calls. 🙂🙃 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:14:24 </td>
   <td style="text-align:left;"> $QQQ stay 2-3 days over 200Ma on daily chart I’m bullish. We go below not so much. Someone look at the past and tell me why I’m wrong </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:13:36 </td>
   <td style="text-align:left;"> $QQQ up! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:12:09 </td>
   <td style="text-align:left;"> $QQQ Tomorrow opening will be very tricky. We&amp;#39;re going to open either right above the 200 day or right below it. It&amp;#39;s going to be a morning full of traps be careful </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:11:51 </td>
   <td style="text-align:left;"> $SPY $QQQ 

They sold techs like there is no tomorrow and now they will be buying them back at higher prices. 
Idiots. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:09:36 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-02-01 Daily Forecast Video: 
https://www.youtube.com/watch?v=evqJhb1Nj-M </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:09:35 </td>
   <td style="text-align:left;"> $QQQ why is “US 100” futures 15,136 when the Nasdaq is 14,346? But $SPY matched up with “US 500”? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:09:00 </td>
   <td style="text-align:left;"> $QQQ has an average volume of 71331700. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:07:43 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $GOOG $TSLA  
 
Everyone get a &amp;quot;participation trophy&amp;quot; in JPOW FREE MONEY PARTY!... except bear :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:06:32 </td>
   <td style="text-align:left;"> $QQQ mm&amp;#39;s are f***ed they will pay calls tomorrow big time they cant take it down with these numbers This is comical as in be careful what you wish for. We could even do a 380 tomorrow  and they did not hedge their bets for this increase. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:02:23 </td>
   <td style="text-align:left;"> $SPY today’s haul...3 day total = $15,172.43 $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:00:23 </td>
   <td style="text-align:left;"> $SPY $QQQ $XBI $IWM Today is probably the most positive day of the previous days. Now we are due for a pullback to $SPX 4450, yesterday&amp;#39;s low should hold. $SPX almost always goes back to retest the 200MA.  
The way it acted today tells me that &amp;quot;they&amp;quot; are preparing what I would call, in Doozio&amp;#39;s terms, &amp;quot;sheep Thursday&amp;quot; followed by a &amp;quot;smart Friday&amp;quot; (or in less politically correct terms &amp;quot;f*ck the sheep Friday). I wouldn&amp;#39;t exclude a big down day Thursday followed by a big up day Friday.  
$XBI is likely to go down to retest the lows, then zoom up.  
This can go a lot higher, the end of the week and next week will tell a lot about the nature of this rally.  
GL. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:00:15 </td>
   <td style="text-align:left;"> $QQQ wow futures </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 07:00:07 </td>
   <td style="text-align:left;"> $QQQ technical analysis for tomorrow. 
 
https://youtu.be/40_0nnOSJCs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:59:31 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA FUTES RIPPIN PROBABLY STILL A BEAR THOUGH 🥤🐻🍿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:59:08 </td>
   <td style="text-align:left;"> $TSLA $QQQ $SPY $ARKK $NVDA futures limit up ??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:58:35 </td>
   <td style="text-align:left;"> $PYPL here are tgts .maybe Thursday bounce at 136... worst case 120 to 122.50. Starts all over..$QQQ $SPY $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:54:45 </td>
   <td style="text-align:left;"> $SPY $QQQ anyone else feel like they will squeeze this move out of the futes session? That would gap QQQ above the 200dma </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:54:16 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
still printing.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:53:58 </td>
   <td style="text-align:left;"> $QQQ Raining iguanas in Florida causing market crash overnight, sorry bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:53:48 </td>
   <td style="text-align:left;"> $QQQ The trend is your friend. Don&amp;#39;t fight it, profit from it. That could easily be a 35% gain tomorrow, maybe 50% 🤔 😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:53:05 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $GLD $TLT  
 
still printing... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:50:58 </td>
   <td style="text-align:left;"> $TSLA $QQQ $SPY Options trading frenzy https://www.ft.com/content/b3db7eca-8bee-4178-91cb-f6e20da9e242 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:48:23 </td>
   <td style="text-align:left;"> $SPY $QQQ bears when they realize market is still below 50 RSI.. 😵‍💫😵‍💫😵‍💫😵‍💫😵‍💫😵‍💫😵‍💫😵‍💫😵‍💫😵‍💫 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:47:36 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $GOOG $AMD  
 
JPOW say...&amp;quot;I will raise rates, sometime&amp;quot; 
 
Market say...&amp;quot;I don&amp;#39;t believe you&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:46:19 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:46:06 </td>
   <td style="text-align:left;"> $QQQ it was difficult to push away all noise.  I had to ask myself “what is more scary right now puts or calls?”  Calls seemed like the “braver” option.  Sometimes you have to just get out the pepto and buy when it looks impossible </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:45:21 </td>
   <td style="text-align:left;"> $QQQ 367C 371C should pay 💰 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:44:06 </td>
   <td style="text-align:left;"> $QQQ hey bears !!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:43:11 </td>
   <td style="text-align:left;"> $QQQ FED has created the mess before earning. FEDs and friends would have bought Feb calls for earning.  
 
the would have made billions by now.  
 
 This is how they play games. Retails are getting poor. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:43:10 </td>
   <td style="text-align:left;"> $QQQ one hell of a way to kick off black history month </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:43:06 </td>
   <td style="text-align:left;"> $QQQ FB ER tomorrow, AMZN after tomorrow, they should be good so I bought QQQ calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:41:57 </td>
   <td style="text-align:left;"> $QQQ 
Yeah the reckoning comes on Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:41:09 </td>
   <td style="text-align:left;"> $SPY $QQQ $UVXY &amp;quot;black swan&amp;quot; on deck..   
 
Of course there&amp;#39;s really no such thing (well...maybe 0.01% of black swans are actual black swans), but hey -- it&amp;#39;ll be fun to watch CNBC sell us the idea that &amp;quot;markets in turmoil&amp;quot; is due to &amp;quot;blah blah blah.&amp;quot;   
 
Remember...  Markets move news...news DOES NOT move markets 🤷‍♂️ 
 
Anyways...  No idea what to expect (okay, I&amp;#39;m lying...I have a few ideas), so I guess it&amp;#39;s good that I&amp;#39;m an INTRA-day trader, and leave the stressful overnight shenanigans to the rest of you 👀😉 
 
Never forget:  Traders make money BOTH ways...  Stop marrying stocks/tickers, and trade whatever they give us </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:41:03 </td>
   <td style="text-align:left;"> $SPY $QQQ ADP report tomorrow, it is basically a preview of the jobs report on Friday. With the US economy doing great, I expect the report tomorrow to show massive jobs growth once again just like we did in the recent months. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:40:40 </td>
   <td style="text-align:left;"> $QQQ i did say i miss the bulls, man, took y’all long enough! how are ya? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:38:29 </td>
   <td style="text-align:left;"> $SPY $QQQ bears are fook </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:38:27 </td>
   <td style="text-align:left;"> $QQQ $380? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:38:01 </td>
   <td style="text-align:left;"> $QQQ SUBRAMANIAN shut the fuck up bitch cunt you getting fuck hard and you dont like it lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:38:01 </td>
   <td style="text-align:left;"> $QQQ easy money has been made.  Well have to see what Meta does but take the money and run this Friday.  Ukraine is not going away. Neither is inflation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:37:34 </td>
   <td style="text-align:left;"> $SPY $GOOG $QQQ $VGT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:37:18 </td>
   <td style="text-align:left;"> $QQQ new highs soon 

Googl amd killing it

Tech is the future, covid proved it further

Bears will be haters always 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:36:40 </td>
   <td style="text-align:left;"> $QQQ Up 3 days in a row 341.1 | 351.8 | 363.05 | 364.42 |  https://www.sleekoptions.com/sleekscan.aspx?sub1=dscan </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:35:43 </td>
   <td style="text-align:left;"> $SPY $QQQ if you think there is no inflation and stocks will go up forever,  go to the supermarket and pay attention to prices (or your credit card interest rate). 
 
Higher rates from the Fed means credit will be more expensive limiting the ability to raise debt and hence restrict debt-fuelled spending for companies and individuals outside of the actual real income they generate (goodbye negative cash flow  zombie companies). 
 
And it means that equities markets will need to justify a higher risk adjusted return than risk free bonds to remain an attractive investment option (except for gamblers). 
 
If the Fed leaves the inflation runs free without controlling it (maintain low rates) and crash the dollar there will be a lot of unhappy people in the street, social unrest happens when people can&amp;#39;t meet their basic needs and that&amp;#39;s not good for any government. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:35:12 </td>
   <td style="text-align:left;"> $SHOP Anyone else holding calls?
Trading is easy 👌

$SPY $PYPL $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:34:59 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Bank of America and Goldman Sachs making extra efforts in media to scare people because they are short and have been caught by turnaround in markets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:34:56 </td>
   <td style="text-align:left;"> $SPY $QQQ Strong earnings from Google bodes well for $AMZN and $FB too I guess </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:34:05 </td>
   <td style="text-align:left;"> $SPY They were confused between bull market rally and bear market rally.. 😅 $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:33:51 </td>
   <td style="text-align:left;"> $SPY $QQQ

how high will this be trading at in 10 yes from now?... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:30:27 </td>
   <td style="text-align:left;"> $SPY $QQQ Some turned into alot </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:30:11 </td>
   <td style="text-align:left;"> $QQQ techs earnings will hold things up this week , but post earnings … we will have to see. These earnings are in general showing great strength. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:29:28 </td>
   <td style="text-align:left;"> How do you buy Call Options on the U.S National Debt? $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:29:13 </td>
   <td style="text-align:left;"> $QQQ Never doubt me again @venture77 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:29:04 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:29:02 </td>
   <td style="text-align:left;"> $QQQ MARRRRRRRRRRRYYYYYYYYYYYYYYYYYYYY MEEEEEEEEEE MISS LU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:28:05 </td>
   <td style="text-align:left;"> $AMD $QQQ 
🐻🥊😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:25:46 </td>
   <td style="text-align:left;"> $QQQ Wen crash </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:24:56 </td>
   <td style="text-align:left;"> $SPY $QQQ $SBUX In this video they talk about Starbucks earnings miss 
 
https://www.youtube.com/watch?v=Q6SfeiR19WA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:24:29 </td>
   <td style="text-align:left;"> $QQQ $SPY Can&amp;#39;t bet against big cap tech earnings this week. Maybe in a week or two but on the same week hahahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:23:58 </td>
   <td style="text-align:left;"> $QQQ Pretty sure there are short hedge funds who could have covered at the bottom and chose not to thinking it would take a leg lower or at least re-test the low. Not so sure about that at this point. Could still happen but looking less and less likely it will get that low again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:23:43 </td>
   <td style="text-align:left;"> $SPY $QQQ

bears no shit tried to short the bottom wtf savages 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:22:48 </td>
   <td style="text-align:left;"> $BENE this is going to get very expensive very soon. and i wont be the only one posting here. New year’s prediction. Confucius says. $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:21:33 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Bears are dumb as shit, change my mind... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:19:40 </td>
   <td style="text-align:left;"> $SPY $QQQ you should all be a bit suspicious that $MSFT is not joining this rally… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:19:07 </td>
   <td style="text-align:left;"> $HOOD Moving up nicely: 
 
Follow for more trade ideas, alerts, technical charts. $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:18:21 </td>
   <td style="text-align:left;"> $SPY $QQQ Lot of Diamond handers with Puts, but they have paper hands when holding stocks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:17:35 </td>
   <td style="text-align:left;"> $BTC.X Going to shock the technical traders and follow $qqq out of correction. Easy money. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:16:51 </td>
   <td style="text-align:left;"> $SPY $QQQ Yes… Let’s keep the surprises coming. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:16:41 </td>
   <td style="text-align:left;"> $QQQ Let’s open at $370 and slow ride up please and thank you 🙏🏾 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:16:35 </td>
   <td style="text-align:left;"> $QQQ sick of this shit being held up by 3 companies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:14:55 </td>
   <td style="text-align:left;"> $QQQ good sport bulls

music still on </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:14:41 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:14:36 </td>
   <td style="text-align:left;"> $QQQ bear market rallies are the most brutal. So are the corrections. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:13:46 </td>
   <td style="text-align:left;"> $SPY $QQQ since when do indexes fly 6 to 7% in 3 days… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:12:47 </td>
   <td style="text-align:left;"> $QQQ bears extinct </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:12:30 </td>
   <td style="text-align:left;"> https://armrreport.com/ Risk Monitor still RED but we are 70% invested. How can that be? I will explain during the Morning Meeting tomorrow 8:30 sharpish $SPY $DIA $QQQ $IWM $VXX  
#investing #stocks #stockmarkets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:12:15 </td>
   <td style="text-align:left;"> $QQQ this should be the last death throw before this turd gets flushed. Only morons are buying the dead cat bounce. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:11:56 </td>
   <td style="text-align:left;"> $QQQ Test of the 200 day SMA resistance  in progress as we speak.  Let&amp;#39;s go Brandon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:11:38 </td>
   <td style="text-align:left;"> $SPY $QQQ $TLT $UUP

Daily Market Recap for Tuesday 2/1/2022 for #Stocks #Bitcoin #Gold and #Silver
https://youtu.be/wZP8R5R_hqU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:08:16 </td>
   <td style="text-align:left;"> $GOOG $GOOGL $QQQ $SPY $NASDAQ 
Recession Priced in Yet? 🤣😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:07:17 </td>
   <td style="text-align:left;"> $QQQ grabbed 370 calls AH - Tech is back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:06:38 </td>
   <td style="text-align:left;"> $QQQ $AMD I had an AMD laptop and then I bought an Intel laptop and the AMD one was better, for real 💻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:06:00 </td>
   <td style="text-align:left;"> $QQQ Monster earnings, no recession, $trillions in puts.  Are you sure you want to draw the right shoulder? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:05:14 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMD $GOOGL wish me luck boys and girls 
results come in april :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:04:59 </td>
   <td style="text-align:left;"> $SOFI I will short the hell out of paypal if this drop below $13 tomorrow! Who else shorting that pos stock? $SPY $QQQ $AAPL $PYPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:04:48 </td>
   <td style="text-align:left;"> $PYPL added here $amd $GOOG $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:04:38 </td>
   <td style="text-align:left;"> $QQQ The googl stock split news just started another bull rally for tech. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:04:32 </td>
   <td style="text-align:left;"> $SPY $QQQ when crash?... 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:03:08 </td>
   <td style="text-align:left;"> $SLS Sure was lol $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:02:43 </td>
   <td style="text-align:left;"> $SOFI sofi is taking PayPal business which is why their earning suck and sofi won’t. Super Bowl is played in sofi stadium . The hype alone will get this to $20! Last word, sofi is not PayPal ! $TQQQ $QQQ $SPY $PYPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:02:27 </td>
   <td style="text-align:left;"> $SPY $QQQ I don&amp;#39;t know if you guys know this but $GOOG is still going with their conference call, it&amp;#39;s a full hour 🕔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:01:53 </td>
   <td style="text-align:left;"> $QQQ $GOOG $SPY Google to the rescue. Wow tomorrow should be a glorious day in tech. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:01:50 </td>
   <td style="text-align:left;"> $SPY $QQQ 

2020-2022 have been some rough years for bulls, I think it’s time we see a pump straight to $550 to reward all dip buyers for their bravery. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:00:49 </td>
   <td style="text-align:left;"> $QQQ when you see $2T companies making 8% moves you should be concerne $GOOG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 06:00:06 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Shortest bear market ever 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:59:34 </td>
   <td style="text-align:left;"> $QQQ it just keeps going! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:58:19 </td>
   <td style="text-align:left;"> $SPY $QQQ amazon is next </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:57:57 </td>
   <td style="text-align:left;"> $QQQ was hoping it would go down more before running up like this… looks like I’ve missed the boat </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:57:23 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL 

Tonight I say a prayer to thank &amp;amp; bless

Jerome Powell for this fed sponsored 

bull market. 🙏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:56:58 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA It’s not about the fake economic numbers, or the fake ER numbers. It’s always been about the Fed and much money they choose to pump into the system. Remember that. There is an expiration date on this market. It just isn’t now. That doesn’t mean we belong at these levels. Be careful. Buy the dips, not the rips. People too confident with this “all’s clear” earnings season. Just too simple. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:56:36 </td>
   <td style="text-align:left;"> $QQQ Does anyone think we will see $372 tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:56:14 </td>
   <td style="text-align:left;"> $SPY Gonna be fun day tomorrow! $QQQ $GOOG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:56:08 </td>
   <td style="text-align:left;"> All Dark Pool Models flipped long $SPY $IWM $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:55:55 </td>
   <td style="text-align:left;"> $QQQ 1st day of Feb.  Tech Futures: V is for Valentines $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:55:04 </td>
   <td style="text-align:left;"> $QQQ think of this bears, can you handle pain 
 
GOOG up 200 
AMZN up 50 
FB up 8 
NVDA up 11 
AMD up 12 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:55:02 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $GOOG $AMD  
 
FED-sponsored bull market firing on all cylinders...lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:54:54 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ $IWM indices closed at their daily highs for 3 straight sessions.   
Loving it, as I&amp;#39;m still long since 1/25 (moving stop-loss to breakeven). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:54:41 </td>
   <td style="text-align:left;"> 5-Day ETF Sentiment Recap: $QQQ is the #3 ETF that institutions are trading over rolling 5 day window with 655.3K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:53:28 </td>
   <td style="text-align:left;"> $NVDA GOES INSANE $XLNX GOES INSANE $AMD GOES INSANE 
 
CAN YOU SAY ALL TIME HIGHS $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:52:57 </td>
   <td style="text-align:left;"> Google adds $150B to its valuation just for stock split news. This euphoric tech bubble burst will be epic 
$QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:51:49 </td>
   <td style="text-align:left;"> $SQQQ Keep waiting. $QQQ needs to re-rest Jan. 20 highs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:51:44 </td>
   <td style="text-align:left;"> $QQQ $PYPL Paypal&amp;#39;s a favorite of the people who are always talking about stocks on CNBC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:51:07 </td>
   <td style="text-align:left;"> $QQQ This strong bounce and price action suggest that institutions are stepping up and buying here. I hope that by now the bears have realized that this is not a dead cat bounce as they thought it would be. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:50:52 </td>
   <td style="text-align:left;"> $QQQ 10% since Friday afternoon- it’s freaking Tuesday! Holy bubble! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:50:26 </td>
   <td style="text-align:left;"> $BTC.X $ETH.X $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:50:24 </td>
   <td style="text-align:left;"> If you didn’t get a 7% wage increase this year, you got a 7% wage cut. 

Think about that when you hear all of these earnings beats. 

$NASDAQ $DJIA $SPY $SPX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:49:51 </td>
   <td style="text-align:left;"> $GOOGL $AMD $QQQ Google and AMD is what we needed to press past the 200 SMA. Looks like we may be getting more of a V shape soon. I still don&amp;#39;t trust it long term, may watch ATH here for a place to build some cash. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:49:44 </td>
   <td style="text-align:left;"> $QQQ $SPY last time NQ had this neg a macd and then crossed after the covid crash.   Just saying…💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:49:42 </td>
   <td style="text-align:left;"> $qqq agree that the rise in goog is probably because of the july split, there&amp;#39;s no forecast but the the release did say the split would be in jul if approved.  thoughts? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:49:23 </td>
   <td style="text-align:left;"> $QQQ almost 10% move from Fridays low 🤪 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:47:57 </td>
   <td style="text-align:left;"> $QQQ It&amp;#39;s pretty shocking that $GOOG and $AMD are gapping up big after their earnings and $PYPL&amp;#39;s getting crushed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:47:28 </td>
   <td style="text-align:left;"> $QQQ pump it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:47:11 </td>
   <td style="text-align:left;"> $QQQ i love the market more when we on 15% down 🍾 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:46:48 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA I MIGHT BE A BIG BEAR BUT I STILL HAVE A 401k CONGRATULATIONS TO THE GOOGLE 🥤🐻🍿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:46:29 </td>
   <td style="text-align:left;"> $QQQ why would you keep buy puts on tech when  earnings are at all time highs and we have just had a 20% correction? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:45:51 </td>
   <td style="text-align:left;"> $SPY $QQQ earnings were pretty solid overall and covid is ending. Inflation was already expected. Things are looking good in the future. Good to stay in the bull zone! OHHHHHHHH!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:45:38 </td>
   <td style="text-align:left;"> $QQQ big boys in the after hours pumping and dumping. Gonna open back up at 360 tomorrow so major retail doesn’t get any ez money. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:45:35 </td>
   <td style="text-align:left;"> $QQQ F*** bears. never play this short game again  
 
this is your lesson. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:45:07 </td>
   <td style="text-align:left;"> $GOOGL sit on it and spin bears. 
 $AAPL $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:45:06 </td>
   <td style="text-align:left;"> $QQQ $AMZN If this continues into tomorrow, let&amp;#39;s just say my net worth is gonna be a &amp;quot;few&amp;quot; thousands higher 😁. Accumulated OTM calls expiring Friday on both during the last 2 hours today. L F G </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:44:44 </td>
   <td style="text-align:left;"> My $GOOGL is getting real close on overtaking my $QQQ position

4. QQQ
5. GOOGL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:44:44 </td>
   <td style="text-align:left;"> $QQQ Bears holding on to those weekly puts like….. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:44:33 </td>
   <td style="text-align:left;"> $QQQ closed my calls at the end of day today to take profits. Oops😂 looks like I could have made a killing holding them overnight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:44:20 </td>
   <td style="text-align:left;"> $SPY $QQQ you ought to be retarded yo buy puts this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:44:09 </td>
   <td style="text-align:left;"> $QQQ broke 360ish resistance. That is a good sign if you are bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:44:03 </td>
   <td style="text-align:left;"> $QQQ $SPY rate hike cancel, back to ATH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:43:55 </td>
   <td style="text-align:left;"> $AMZN $QQQ Yahoo Finance is buggin, who&amp;#39;s getting accurate off market quotes? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:43:46 </td>
   <td style="text-align:left;"> $SBUX will my Puts print tomorrow? 🤔 
 
$GOOG $SPY $PYPL $QQQ  
 
🎰💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:43:35 </td>
   <td style="text-align:left;"> $QQQ feel like so long bears are in denial and people are buying up puts in anticipation of a second leg down, we are not stop melting up.  Similar thing happened on March 2020 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:43:24 </td>
   <td style="text-align:left;"> $QQQ can this get to 375 or close or above tomorrow on such news momentum ? hmmmmm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:43:18 </td>
   <td style="text-align:left;"> $SPY $QQQ mooon tmw baby </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:43:11 </td>
   <td style="text-align:left;"> $QQQ we are at the turning point. 369 now. Turn within a couple of points - it will drop and drop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:43:07 </td>
   <td style="text-align:left;"> $SQQQ hedging overnight every night until the nonsense with Russia is hashed out...

$QQQ $TQQQ $UVXY $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:42:21 </td>
   <td style="text-align:left;"> BEARS STARING IN DISBELIEF AT HOW THEY COULD HAVE GOTTEN IT JUST SO SO WRONG - THE PRICES LAST WEEK WERE GENERATIONAL 
 
THE EARNINGS ARE BLOWOUT - THE LIQUIDITY IS NEVERENDING - THE MONEY IS FREE 
 
WHAT ARE YOU NOT UNDERSTANDING? 
 
If you are SCARED to buy stocks - TURN OFF THE CNBC and start listening to CONFERENCE CALLS and reading EARNINGS REPORTS 
 
$spy $qqq $googl $amd </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:41:55 </td>
   <td style="text-align:left;"> Sorry, she only parties with $AMD bulls. Bears are poor and trash. $QQQ $SPY $XLNX $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:41:41 </td>
   <td style="text-align:left;"> $AMD $GOOGL $QQQ 
Congrats Bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:41:36 </td>
   <td style="text-align:left;"> $SPY $QQQ 

It’s nonstop sensational v’s, the little money (bears) just can’t bring this market down $$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:41:34 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Full on Ponzi …..

Very fishy….

Next 3 days down ?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:41:21 </td>
   <td style="text-align:left;"> $QQQ $SPY $AMD AMD just delivered one of the best earnings reports I have see.   Gross margins at 50%, 50% yoy growth.   Trading at only 8x sales. Been long and not selling. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:40:56 </td>
   <td style="text-align:left;"> $QQQ back to burger flipping for the bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:40:15 </td>
   <td style="text-align:left;"> $QQQ bears are dead. Feb going to be
one of the best months ever. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:39:53 </td>
   <td style="text-align:left;"> $QQQ lets go green, 4x day in a row </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:39:40 </td>
   <td style="text-align:left;"> $SPY $QQQ How are u bears feeling now. LMAO... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:39:35 </td>
   <td style="text-align:left;"> $SPY $QQQ $PFE starts seeking FDA emergency approval of Covid vaccine for kids under 5 .. that should help the bottom line said CEO Bourla as he laughed maniacally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:39:08 </td>
   <td style="text-align:left;"> $QQQ i guess tech gonna be good tomorrow thanks to $GOOG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:38:54 </td>
   <td style="text-align:left;"> $SOFI Sofi is not PayPal! We beat our forecast estimate here at sofi! $PYPL $LC $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:38:45 </td>
   <td style="text-align:left;"> $AMD $NVDA $GOOG non stop in after hours on their earnings. Very strong for $QQQ into tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:38:27 </td>
   <td style="text-align:left;"> $QQQ We could see $AMD +15% tomorrow. CONGRATS to retail shorts … poor house tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:37:06 </td>
   <td style="text-align:left;"> $SPY $QQQ Bipolar market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:36:46 </td>
   <td style="text-align:left;"> $QQQ 375 open? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:36:37 </td>
   <td style="text-align:left;"> $QQQ 9% in 3 days $SPY smh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:36:06 </td>
   <td style="text-align:left;"> $QQQ when ATH? 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:36:02 </td>
   <td style="text-align:left;"> $SPY $QQQ The lesson for the bears to learn is that you don&amp;#39;t ever bet against the US mega big tech stocks lol $GOOGL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:35:50 </td>
   <td style="text-align:left;"> $QQQ puts at close crew sweating a bit $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:35:48 </td>
   <td style="text-align:left;"> $QQQ kiss of the 200sma.  Not OB by any means, but a gap and crap day tomorrow is a real possibility. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:35:37 </td>
   <td style="text-align:left;"> $QQQ resistance just got trampled </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:35:35 </td>
   <td style="text-align:left;"> $TQQQ stoked on this avg price $QQQ 
🚀🥳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:35:31 </td>
   <td style="text-align:left;"> $QQQ textbook buy the dip at support today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:34:40 </td>
   <td style="text-align:left;"> $QQQ The gap tomorrow is going to be insane! 1% plus </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:34:35 </td>
   <td style="text-align:left;"> $QQQ $GOOGL oh how quickly the sell tech narrative changes. Funds were loading up on your cheap shares all last month if you were selling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:33:45 </td>
   <td style="text-align:left;"> $googl FIRST TERA CAP TO RIP FACES BACK TO ALL TIME HIGHS - REST OF MARKET TO FOLLOW THE LEADER 
 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:33:30 </td>
   <td style="text-align:left;"> $QQQ Guess I gotta own that horrible call. Thought for sure google would send this market dumping. 20-1 split. FML </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:33:11 </td>
   <td style="text-align:left;"> TELL ME which idiot sold $amd at 98 last week now 127 $googl 2290 now 2936 I mean just LUNACY omg tomorrow is going to be INCREDIBLE 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:32:56 </td>
   <td style="text-align:left;"> $QQQ https://m.youtube.com/watch?v=29veHfOMD40

Let’s Go Brandon!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:32:49 </td>
   <td style="text-align:left;"> $SPY after hours is popping!!! $qqq gonna pop 2morrow 🤑🤑🤑 !! @mbellizz 
$dia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:32:42 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMD 

HEY  BEARS 👇👇👇👇👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:32:37 </td>
   <td style="text-align:left;"> $QQQ EARNINGS SZN IS RIPPPPPPING </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:32:35 </td>
   <td style="text-align:left;"> $QQQ how bout we go for one more run at ATHs before the crash </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:32:29 </td>
   <td style="text-align:left;"> $AMD 126 AH .

Bravo. Bravo.

How many bagholders still from 150+?

and why guide so high in a coming ultra inflationary environment? 🥶 

Chip shortages, supply chains, more and more folks vying for their chips fabbed, guidance sounds like more $NXPI hopium to me. 

$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:32:27 </td>
   <td style="text-align:left;"> $QQQ tech doesn&amp;#39;t do well with rising rates... that&amp;#39;s bullshit.  $GOOGL $AMD $MSFT $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:31:49 </td>
   <td style="text-align:left;"> GOOD. GOD. ALMIGHTY&amp;gt; ARE YOU GUYS SEEING THE ABSOLUTE FACE RIPPERS AFTER HOURS WE GAP N GO HARD THERE CAN BE ZERO DOUBT THIS DOESNT GO TO ALL TIME HIGHS WITHIN THE NEXT 2 WEEKS  
 
CONGRATS EVERYONE !!!! 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:30:27 </td>
   <td style="text-align:left;"> $AMD $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:30:01 </td>
   <td style="text-align:left;"> $googl and $amd proved that we can overcome supply chain issues and inflation 

$iwm $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:30:00 </td>
   <td style="text-align:left;"> $QQQ 

Fear to Fomo in 3 days lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:29:52 </td>
   <td style="text-align:left;"> $SPY $QQQ $NQ_F the blow off top pattern. get out the champagne. algos going for the kill </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:29:30 </td>
   <td style="text-align:left;"> $QQQ feb 11 375 calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:29:21 </td>
   <td style="text-align:left;"> $QQQ bought calls earlier today…Can’t wait to see those print in the morning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:29:05 </td>
   <td style="text-align:left;"> $QQQ Stocktwits your s mega bullish. This week is a red bar with a massive topping tail. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:29:05 </td>
   <td style="text-align:left;"> $QQQ haha I’m intrigued. Is the whole market fixed now? No rate rises or inflation? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:28:35 </td>
   <td style="text-align:left;"> $QQQ 5% up day tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:27:39 </td>
   <td style="text-align:left;"> $QQQ so all the market problems are sold or they just trapping more retailers? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:27:26 </td>
   <td style="text-align:left;"> $QQQ Accumulating shorts. Yes im stupid. Dax 17k nasdaq 20k I know I know. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:27:23 </td>
   <td style="text-align:left;"> ICYMI - 20 STOCKS TO CONSIDER IN FEBRUARY    
All charts covered in detail.      
$IWM $QQQ $SPY $SPX $DIA all fully assessed plus many more charts and ideas.      
https://www.honeystocks.com/analysis </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:26:34 </td>
   <td style="text-align:left;"> $QQQ bears and Putin stand no chance folks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:26:33 </td>
   <td style="text-align:left;"> $SPY $QQQ Well $GOOGL is just a monster lol, the bears are in big time trouble tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:25:09 </td>
   <td style="text-align:left;"> $QQQ Tom Lee called this RALLY!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:25:02 </td>
   <td style="text-align:left;"> $QQQ damn feel like if fb beat and amzn beat and split, we could fly back to ath. This is so unreal that we were in so panic mode a week ago </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:24:55 </td>
   <td style="text-align:left;"> $QQQ - Perfect set up, fake green until extended hours closes….. Then the shit show and it’s down we go tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:24:41 </td>
   <td style="text-align:left;"> $QQQ Russia already backing down&amp;gt;&amp;gt;&amp;gt; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:24:40 </td>
   <td style="text-align:left;"> $GOOGL markets gonna pump tomorrow on this news alone. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:23:53 </td>
   <td style="text-align:left;"> $QQQ bears get slaughtered </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:23:48 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA National Debt hits $30 Trillion. 

When this blows up its gonna be worse than 1929 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:23:37 </td>
   <td style="text-align:left;"> $GOOGL 🤩 No one saw that coming stock split are crazy catalysts $AMZN $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:23:36 </td>
   <td style="text-align:left;"> $QQQ $SPY Largest unloading of the indexes after hours I have seen this far </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:23:18 </td>
   <td style="text-align:left;"> $GOOGL $GOOG $SPY $QQQ Alphabet dividend coming soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:23:10 </td>
   <td style="text-align:left;"> Google parent Alphabet announces 20-for-1 stock split $GOOG $GOOGL $SPY $QQQ https://cnb.cx/3rit5dO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:23:00 </td>
   <td style="text-align:left;"> $AAPL $AMZN $GOOG $QQQ $SPY  goog is the only company out of 5 that had okay earnings. The rest going down the shitter. Market will be lower tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:22:38 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $AAPL $TSLA  
 
If this keeps up PIGGIE gonna be 100% cash in his retirement accounts in a week or two! 
 
He is now 65% cash as of today and will move 15% more to cash at 4600 and 10% at 4700 and 4800. 
 
Then Piggie done for year!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:22:24 </td>
   <td style="text-align:left;"> $QQQ yolo calls&amp;gt; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:21:42 </td>
   <td style="text-align:left;"> CHIPS!!!! $amd goes insane watch pin action tomorrow from the rest of tech OMG party like its 1999 REMINDER: Money is still free and Fed is STILL printing and buying assets  
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:21:37 </td>
   <td style="text-align:left;"> $QQQ sea of green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:20:36 </td>
   <td style="text-align:left;"> $GOOGL i definitely expect that multi year horizontal resistance will give bulls hell but if we get thru that man look out. $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:20:18 </td>
   <td style="text-align:left;"> $SPY $QQQ Mega cap are all gonna listen to Burry and split shares
protects interest of earlier investors 
increased market participation 
relative easy lending 
accessibility 
marketability 
idk man this bubble can still run 
fuck it 
Im riding this bitch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:19:56 </td>
   <td style="text-align:left;"> $QQQ honest question for the techy guys and more experience traders. after AMD &amp;amp; GOOGLE violated ER what PT you expect QQQ tomorrow ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:19:49 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMD $GOOGL exactly why we need to raise rates </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-02-02 05:19:28 </td>
   <td style="text-align:left;"> $SPY $QQQ  Denver Broncos is going up for sale… any high rollers here? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:58:16 </td>
   <td style="text-align:left;"> $AAPL anyone care to enlighten me as to what the fuck happened to Yahoo Finance message boards? What in the holy hell. Go Bulls! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:56:17 </td>
   <td style="text-align:left;"> $AAPL inside bar today on low volume..lets break 145 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:55:34 </td>
   <td style="text-align:left;"> $AAPL Our puts placed 2 days ago T over 55% on sale will pay out late summer. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:55:17 </td>
   <td style="text-align:left;"> $AAPL bloodbath will happen tomorrow, I’m ready. 🕳👨🏽‍🦯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:54:07 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $AAPL $TSLA  
. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:53:01 </td>
   <td style="text-align:left;"> $SPY $QQQ the fact that $AAPL and $MSFT didnt make a move after hours gotta tell something! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:48:57 </td>
   <td style="text-align:left;"> $SPX Critical to get back above 4600 and into the channel else we will be seeing these volatility with higher highs and lower lows $MSFT $AAPL... good for day traders! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:46:21 </td>
   <td style="text-align:left;"> 3/3

$AMD absolutely blisters Q4:
-Record revenue, NI and EPS
-Top &amp;amp; bottom beat
-50% GM that we haven&amp;#39;t seen for a while (2006)
-Ryzen &amp;amp; GPU ASP up
-7th record Epyc qtr
-Strong Q1 guide (45% rev/50.5% GM) w/o Xilinx
-Killer &amp;#39;22 guide: $21.5B rev +31%; 51% GM w/o Xilinx / $XLNX 

$AAPL $TSLA $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:46:10 </td>
   <td style="text-align:left;"> $BA $AAPL $AMZN &amp;#39;;&amp;#39;; 
 
Account Challenge Update:-  
Start Date: Jan 3, 2022  
Starting Balance: $1,700  
Current Balance: $79,589 
Goal: $100,000 by end of February.  
Strategy: Swing Trade Options, Stocks  
  
Watch out for next play👓 amazing-chat-room.stocksboss.xyz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:46:06 </td>
   <td style="text-align:left;"> 2/3

$AMD absolutely blisters Q4:
-Record revenue, NI and EPS
-Top &amp;amp; bottom beat
-50% GM that we haven&amp;#39;t seen for a while (2006)
-Ryzen &amp;amp; GPU ASP up
-7th record Epyc qtr
-Strong Q1 guide (45% rev/50.5% GM) w/o Xilinx
-Killer &amp;#39;22 guide: $21.5B rev +31%; 51% GM w/o Xilinx / $XLNX 

$AAPL $TSLA $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:45:47 </td>
   <td style="text-align:left;"> 1/3

$AMD absolutely blisters Q4:
-Record revenue, NI and EPS
-Top &amp;amp; bottom beat
-50% GM that we haven&amp;#39;t seen for a while (2006)
-Ryzen &amp;amp; GPU ASP up
-7th record Epyc qtr
-Strong Q1 guide (45% rev/50.5% GM) w/o Xilinx
-Killer &amp;#39;22 guide: $21.5B rev +31%; 51% GM w/o Xilinx / $XLNX 

$AAPL $TSLA $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:44:58 </td>
   <td style="text-align:left;"> $AMZN Amazon is going to split I am 100% confident it will, they have to, retail are also investors and can boost the stock to new highs. No split since 1998!

Let’s go Jeff Bezos time to pump Amazon to new highs

$GOOGL $AAPL $TSLA $SPY

Never forget Apple and Tesla split

Google will run above EMA9 all day tomorrow algos will trigger it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:40:34 </td>
   <td style="text-align:left;"> 1 year of $GEVO latex07a9b014ead38d4b2a08c1540e2193daRBLX 160%
$AAPL 60% 

What was your favorite play today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:34:09 </td>
   <td style="text-align:left;"> $ERBB $AAPL $OZSC $GOOGL  
There are 100,000,000 pennies in one million dollars. You must find the next thing, not the now thing $ERBB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:33:01 </td>
   <td style="text-align:left;"> $AAPL Charts looks very strong for a breakout and test ATHs. MACD curling up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:31:38 </td>
   <td style="text-align:left;"> $GOOG fucking dummies never learn.

They short apple, Microsoft and now, Amd and Google before earning $AAPL $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:31:25 </td>
   <td style="text-align:left;"> $AAPL google aths!
Apple next 🍏🚀 amd too ;) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:30:46 </td>
   <td style="text-align:left;"> Ticker: $AAPL 
Buy: February 04, 2022 $175.00 Calls 
Entry Price: $1.52 - $1.54 
Exit Price: $1.96 
Stop Loss: $1.34 
Potential ROI: 29% 
Estimated Hold Time: 38 Minutes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:29:25 </td>
   <td style="text-align:left;"> $SPY $MSFT $AAPL $GOOG $GOOGL 😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:27:22 </td>
   <td style="text-align:left;"> $AAPL Question for the more experienced than me (most of y’all lol). Is this a good hold for 3 years. And what’s a good place to read up on upcoming products/ earning reports? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:26:37 </td>
   <td style="text-align:left;"> $AMD revenue graph📈

➕ $XLNX 🤑

$AAPL | $TSLA | $MSFT N </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:25:46 </td>
   <td style="text-align:left;"> These are my current open positions. You can track it all at https://spxyer.com/portfolio/ All alerts are posted FREE and no need to signup. Cheers $AAPL $SPY $GOOGL $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:25:40 </td>
   <td style="text-align:left;"> $AAPL https://music.apple.com/us/album/we-the-people/1606514858?i=1606514859 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:25:25 </td>
   <td style="text-align:left;"> $AAPL * IPhone Revenues For Full Year Is $140 billion to $210 billion x 36% GM = $75,600,000,000

Earning EPS: $16 to $19 x 36 x PE = $684 without Apple Car + Glasses + Metaverse 

Autonomous: Will Be Services + Low Margin Business, Unless The Battery Business is a Success To Have With Lower Margin Cost &amp;amp; Higher Mileage.

Autonomy Level 4 &amp;amp; 5 - Full Autonomous Driverless Vehicle: 

Possible We Can see: $1,000 to $3,500 Per Share if PE multiple is $18 Earnings &amp;amp; 145x or 185x Forward Multiple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:25:18 </td>
   <td style="text-align:left;"> $AMD $NVDA $MSFT $AAPL if you got scared and didn’t buy the dip on big tech then you shouldn’t be investing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:25:13 </td>
   <td style="text-align:left;"> $AAPL had 34.6 Billion in profit &amp;amp; $123.9 Billion in Revenue; yet $GOOG did much worse than them… still gains 10% lol wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:25:10 </td>
   <td style="text-align:left;"> $AAPL 6) Apple Car - Project Titan 

7) Metaverse - In works 

8) Mac Hardware Extended Business Users With The New Silicon M silicon group that is coming to more advance into Mac Air and More Advance Pro &amp;amp; iMac - potential 350 million or more customers to target for business users  

350,000,000 x $2,189 = $766,150,000,000 x 34% GM = $260,491,000,000

9) Other wearables, iPad, iPad Pro etc - 

$178,000,000,000 x (38% + 74% GM)/2 *56% = $99,680,000,000 

Based on all products minus &amp;quot;Project Titan&amp;quot; + &amp;quot;Metaverse&amp;quot; ~ Total Addressable Revenues Can Be $388,877,000,000 for Gross Margin Revenue without any iPhone Sales Units Included In The Gross Margin Totals And Thus Apple Can&amp;#39;t Built 590 million Watch In Year 2022/2023, If They Include the Diabetic Non-Needle Watch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:24:36 </td>
   <td style="text-align:left;"> $AAPL  🍏 AfterHours Volume Heavy, 7.1 Million. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:24:30 </td>
   <td style="text-align:left;"> $AAPL 2) Apple Search Ads - $4 billion today heading to $18 to 24 billion for consumer/business ads

$24 billon x 78% GM = $18,720,000,000

3)AR/AI: Headset

$1,000 to $3,000 price range: $1,500 x 22 million = $16,500,000,000 x 36% GM = $5,940,000,000

Note: AR Headset will sell like Apple Watch after Year 1 or Will Take Off At The Introduction In 2022, Q2 Apple Watch In 2021 = 100 million Units

4) AR/AI: Glasses - Year Introduced Either 4th Qtr 2022 or 2023

Price and Units Sold - 50 million x $ ? 

5) Apple TV: No subscription numbers out from apple, heavily invested in 12 new movies per year and extended TV series 

89,000,000 subscriber x $49.99 = $4,500,000,000 x 67% GM = $3,026,000,000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:23:51 </td>
   <td style="text-align:left;"> $AAPL Apple Future Business 2022/2023

Exclusive: This below is my theory calculation based on what May or May not happen - depending on, if these products come into the real world or numbers shared by Apple, like the Tv subscription, Watch doing more FDA approved health care monitoring and so forth - 

••••••••••••••••••••••••••••••••••••••••••••••••••
Sum-Of-Parts Business:
-------------------------

AAPL the sum of parts for Apple&amp;#39;s Future Business Isn&amp;#39;t Known Yet By WallStreet:

1) Apple Watch Extended to Many More Health Care including diabetic, temperature, sleep apnea and much more are in works, 590 million first time users if the diabetic sensor works in the coming months (Tim Cook has been wearing this secret sensor watch inside the campus, walking around for exercise:

590,000,000 x $429 = $255 billion + Add On&amp;#39;s $10 billion = $265 billion x 38% GM = $100,700,000,000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:21:43 </td>
   <td style="text-align:left;"> $AAPL    🍏Futures:  Wayyyy early, but…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:20:49 </td>
   <td style="text-align:left;"> $btc.x $tsla $qqq $aapl $msft https://www.youtube.com/watch?v=JnaAE_VcHqs&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:19:56 </td>
   <td style="text-align:left;"> $aapl $qqq $ndx https://www.youtube.com/watch?v=KnhPvpaJEeo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:14:42 </td>
   <td style="text-align:left;"> $AAPL Don&amp;#39;t know if Apple will get a PE forward multiple like Google and others 

Like 35x or 45x 

New product categories 

Services business is $100 billion + for apple 

What about the apple ride share - what will be that multiple 

155x or 185x like Amazon or Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:13:56 </td>
   <td style="text-align:left;"> $AAPL Typical garbage poster 
And StockTwits allows all garbage like this... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:11:02 </td>
   <td style="text-align:left;"> latex21c39b00f3b096bf1ea93116d5d28586NVDA - 78% call flow 
$AAPL - 56% call flow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:08:18 </td>
   <td style="text-align:left;"> $AAPL should at the very least approach $180 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:07:20 </td>
   <td style="text-align:left;"> $AAPL did better than $GOOG right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:04:47 </td>
   <td style="text-align:left;"> $AAPL $V $WEN $MA $SBUX this is why you buy the best of the best! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:04:04 </td>
   <td style="text-align:left;"> $AAPL oh HELLL NO!!! 
https://m.worldstar.com/web/video.php?v=wshhK52y260E9a2KXM9G </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:03:50 </td>
   <td style="text-align:left;"> $AAPL Buying more at 139. Holding all my shares I bought between 145 and 172. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 08:00:26 </td>
   <td style="text-align:left;"> $AAPL well well well what’s that we’re seeing, buy action.  Hmm think the MM’s held her back long enough… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 07:59:13 </td>
   <td style="text-align:left;"> $AAPL hitting $185+ would yield $50k in gain </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 07:59:05 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #3 ticker with sweep activity where institutions are trading options urgently with 38.9K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 07:58:03 </td>
   <td style="text-align:left;"> $AAPL what was that AH drop at 5:09pm to 163ish? 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 07:56:04 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 07:45:16 </td>
   <td style="text-align:left;"> $TSLA tech sector pumping and $TSLA and $AAPL  holding down, expecting some upside movements EOW…👀👀👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 07:40:13 </td>
   <td style="text-align:left;"> $GOOG $AMD should inspire 5-10% uptick on $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 07:38:49 </td>
   <td style="text-align:left;"> $AAPL $200 February 18. Pass it on </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 07:36:43 </td>
   <td style="text-align:left;"> $AAPL  🍏 In the “final second of the Close, 7.4 Million AAPL Shares traded to the “Buy Side”.  “Accumulation”, all afternoon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 07:32:31 </td>
   <td style="text-align:left;"> $AAPL https://youtu.be/UU_4xfd0Xh0 legs gooo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 07:30:57 </td>
   <td style="text-align:left;"> $AAPL this is going to blast off tomorrow. Seems the whole market is. How odd. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 07:26:51 </td>
   <td style="text-align:left;"> $AAPL anyone know why apple didn’t move? While every big tech shot up today. Could it already be priced in with its own earnings and everyone else trying to catch up? Google is insane btw. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 07:26:12 </td>
   <td style="text-align:left;"> $AAPL 176 tomorrow 🤞🏾 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 07:17:33 </td>
   <td style="text-align:left;"> $AAPL why this tech share alone red ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 07:17:18 </td>
   <td style="text-align:left;"> $SPY So Markets didn&amp;#39;t see Pro&amp;#39;s sell into the Pop today so I was looking for the Wed&amp;#39;s dip but now w/ that $googl &amp;amp; $amd crush it 
we&amp;#39;re in a quandary after todays chasing. 
 
Keeping the Bears off balanced, what do the Quants have in store for the Markets tomorrow? hmmm :o) 
 
$aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 07:17:14 </td>
   <td style="text-align:left;"> $AAPL 

LETS GOOOOO!!!! 
#RELI #STRR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 07:14:26 </td>
   <td style="text-align:left;"> $SPY Looks like $GOOGL $GOOG  will suck away capital from $AAPL and $MSFT tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 07:11:00 </td>
   <td style="text-align:left;"> $AAPL is one of the better performing stocks in the Technology Hardware, Storage &amp;amp; Peripherals industry. https://www.chartmill.com/stock/quote/AAPL/technical-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 07:09:10 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-02-01 Daily Forecast Video: 
https://www.youtube.com/watch?v=-bWxDBPxCRs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 07:08:54 </td>
   <td style="text-align:left;"> $AAPL this is deflating fast ah </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 07:08:15 </td>
   <td style="text-align:left;"> $AAPL you do be breaking my heart rn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 07:05:57 </td>
   <td style="text-align:left;"> $SPY if you don’t know.. now you do.
1st $AAPL , now $GOOGL , next $FB , then to finish the week $AMZN. 🚀 I just hope we don’t hit ATH this week so you shorts can cover. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 07:04:55 </td>
   <td style="text-align:left;"> $GOOG Google market cap 2 Trillion dollars.  That represents 10% of US GDP last year.  GOOG is Too Big To Fail.   Feds need to break up the company for national economic security.  $SPY  $AMZN $AAPL $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 07:01:09 </td>
   <td style="text-align:left;"> $AAPL technical analysis for tomorrow. 
 
https://youtu.be/cy11BmFEyFY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:59:01 </td>
   <td style="text-align:left;"> $AAPL $AAL Here’s What We Know About ‘Stealth’ Omicron BA.2 — The More Infectious Subvariant Better Able To Infect Vaccinated People https://www.forbes.com/sites/roberthart/2022/02/01/heres-what-we-know-about-stealth-omicron-ba2---the-more-infectious-subvariant-better-able-to-infect-vaccinated-people/?utm_campaign=forbes&amp;amp;utm_source=facebook&amp;amp;utm_medium=social&amp;amp;utm_term=Gordie&amp;amp;fbclid=IwAR3fRueAZGXnwTYU_bCoYVOgYemCOmQT3KGKMXzQptQXObSnmtaxrvmvWws </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:58:05 </td>
   <td style="text-align:left;"> $AAPL anyone else still holding on to 2/4 puts? Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:57:24 </td>
   <td style="text-align:left;"> Bears are having hard to hide now :) 
 
$AAPL $TSLA $SPY $AMD $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:56:54 </td>
   <td style="text-align:left;"> $AAPL should just buy $PYPL to save them some of this humiliation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:56:03 </td>
   <td style="text-align:left;"> $AAPL $AMZN $MSFT $GOOG make up 37% of my net worth...am I worried about that concentration?  NOPE! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:55:19 </td>
   <td style="text-align:left;"> drag $EA close to 100 and have $AAPL buy this ish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:52:33 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:52:07 </td>
   <td style="text-align:left;"> $AAPL keep-shorting it Bears, you’re gonna wake up tomorrow after she gaps and go what the F was I thinking!!!  Hehe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:49:32 </td>
   <td style="text-align:left;"> $AMD $nvda $intc $tsla $AAPL 

AMD Gross Margin: from 27% (2016) to 48% (2021)
Intel Gross Margin: from 63% (2016) to 53% (2021)

from the above numbers, you will know which to buy. 

amd margin will grow further as more CPUs and GPUs are to be sold to Tesla and Apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:49:19 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:49:17 </td>
   <td style="text-align:left;"> $AAPL ... fu &amp;quot;BEARS&amp;quot;! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:47:30 </td>
   <td style="text-align:left;"> Alphabet Stock Split Could Permit Tech Giant to Join Dow Industrials  $UNH $AAPL $MSFT $AMZN $FB 

https://newsfilter.io/a/8ca5bd29bd007c31876b660d73083572 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:47:16 </td>
   <td style="text-align:left;"> $PYPL They’re not $GOOG $AAPL or $OSTK. Outdated tech like $BB @TrollingBaggiesOriginal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:34:57 </td>
   <td style="text-align:left;"> $AAPL Stocks were ripping today. Simulated Weekly $175.0 CALLS for Wednesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:34:45 </td>
   <td style="text-align:left;"> $AAPL oh look we’re slightly red and the bears woke up out of hibernation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:31:26 </td>
   <td style="text-align:left;"> $SPY $AMD $AAPL  lying about the supply chain and inflation gonna back fire in the end. At least UPS wasnt scared to tell the truth  https://youtu.be/Eh_bLL17LjM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:30:25 </td>
   <td style="text-align:left;"> $AAPL sold 2 CS 11/18 200 puts today. I’ll take profits at +$5k. How long do you think it takes?? I think I buy these back before May 1st.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:29:29 </td>
   <td style="text-align:left;"> last week $aapl calls were 120-300% overnight depending on your cost avg/time of selling them

 and now $PYPL puts are currently somewhere around 650-1000% right now depending on cost avg at this very moment. Obv will depend also when you sell tmrw 

Solid closes on core swing $nine $mdia $bbig as well. Let’s see what tmrw brings to the table for us </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:26:01 </td>
   <td style="text-align:left;"> $AAPL MMs may dump small positions to get in on Google stock split hype.  Not expecting a big downside move, but daily candle is either the start of consolidation or slowdown in ER hype. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:25:46 </td>
   <td style="text-align:left;"> Tech oversold bounce in play. $AMD $AAPL $GOOG $AMD 
Daily Market Recap for Tuesday 2/1/2022 for #Stocks #Bitcoin #Gold and #Silver
https://youtu.be/wZP8R5R_hqU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:23:26 </td>
   <td style="text-align:left;"> $MVIS I think $AAPL or $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:23:24 </td>
   <td style="text-align:left;"> $AAPL  why did faang stocks shoot up together after earnings today but apple stayed flat? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:21:27 </td>
   <td style="text-align:left;"> $EA Well I hope $GOOGL or $AAPL or even $DIS buys out EA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:20:27 </td>
   <td style="text-align:left;"> $AMD  All of the hedge funds cannot be wrong  
  
Ignore the BS of Robinhood, these stocks are NOT a meme stocks 
 
This actually flew over Robinhood&amp;#39;s headquarters in Menlo Park  California, it was hilarious and Robinhood&amp;#39;s CEO couldn&amp;#39;t do anything about it, nothing was illegal :) 
 
https://www.youtube.com/watch?v=WFie1ep9xk0 
 
$AAPL $TSLA $SPY $AMD $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:20:05 </td>
   <td style="text-align:left;"> $VIAC

 $GOOGL stock split shouldn’t be bullish for the stock momentum, but it will be. Just like it was for $AAPL and $TSLA last year.

The question becomes, are they smart enough to also have a stock offering to raise cash, and aquire $VIAC?

Would $GOOGL and it’s YouTube TV platform benefit from acquiring $VIAC? 

After tense negotiations with ESPN ($DIS) in December, I think Google would love to own its own sports right. And thats just one piece of the puzzle. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:16:28 </td>
   <td style="text-align:left;"> Notice of exempt solicitation submitted by non-management https://www.conferencecalltranscripts.com/summary/?id=10382646 $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:15:23 </td>
   <td style="text-align:left;"> $AAPL when the Bears come out in force they are still scared!!! LMAO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:14:02 </td>
   <td style="text-align:left;"> $AAPL this is going to fill the $160 gap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:13:21 </td>
   <td style="text-align:left;"> $AAPL by how im buying 175 Puts here,. Apple is way extended. Hasn&amp;#39;t pulled back far enough to break through 180here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:12:49 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:10:28 </td>
   <td style="text-align:left;"> $AAPL no one’s concerned apple isn’t getting any love after hours.  Red in a green market.  That’s odd. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:10:05 </td>
   <td style="text-align:left;"> $AAPL Absolute garbage. Severely underperforming the market. Dead money. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:08:01 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $GOOGL stock split 20-1 Google is a monster </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:05:37 </td>
   <td style="text-align:left;"> $GOOGL who makes more money...this or $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:04:59 </td>
   <td style="text-align:left;"> $SOFI I will short the hell out of paypal if this drop below $13 tomorrow! Who else shorting that pos stock? $SPY $QQQ $AAPL $PYPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 06:01:54 </td>
   <td style="text-align:left;"> $AAPL if semiconductors are doing well! It only confirms that $AAPL spoke the truth with their supply chain dynamic easing for QTR1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:59:30 </td>
   <td style="text-align:left;"> $AAPL $MSFT should’ve put all my money into my GOOG or FB play 🤦🏽‍♀️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:57:35 </td>
   <td style="text-align:left;"> $AAPL eating all of payment processors revenue </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:57:23 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL 

Tonight I say a prayer to thank &amp;amp; bless

Jerome Powell for this fed sponsored 

bull market. 🙏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:56:46 </td>
   <td style="text-align:left;"> Chart here $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:55:33 </td>
   <td style="text-align:left;"> $AMD $AAPL 200 soon
Both baby </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:54:01 </td>
   <td style="text-align:left;"> $SOFI PayPal is  not a bank! We don’t know PayPal! He was just an intern that got us coffee! Buy sofi because unlike PayPal, we actually beat our earning forecast here! $PYPL $SPY $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:49:40 </td>
   <td style="text-align:left;"> $AAPL mf cover tomorrow $180.00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:45:35 </td>
   <td style="text-align:left;"> $AAPL will uptick over $182 b/c $AMD CRUSHED IT? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:45:07 </td>
   <td style="text-align:left;"> $GOOGL sit on it and spin bears. 
 $AAPL $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:44:48 </td>
   <td style="text-align:left;"> $PYPL $SQ hit because $AAPL Apple challenges Both by transforming iPhones into POS terminals - Bloomberg.  
So Point of Sale or Piece of Poop? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:44:47 </td>
   <td style="text-align:left;"> $AAPL should see 185 by eow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:44:46 </td>
   <td style="text-align:left;"> $SPY $GOOG $$AMD $AAPL $MSFT come on tech is kicking butt </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:41:58 </td>
   <td style="text-align:left;"> $SPY With earnings like this $GOOGL $AMD $AAPL $TSLA Who needs the FED. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:41:30 </td>
   <td style="text-align:left;"> $AAPL bear burgers for breakfast tomorrow morning! Medium rare? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:40:31 </td>
   <td style="text-align:left;"> $XELA $AAPL $SSNLF please don&amp;#39;t tease me with those deals 💯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:39:32 </td>
   <td style="text-align:left;"> $AAPL bears are fucked tomorrow’s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:38:38 </td>
   <td style="text-align:left;"> $AAPL  2% AH…..🚀🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:38:25 </td>
   <td style="text-align:left;"> $AMC A LOT OF FAILURE TO DELIVERS FOR A $20 MOVIE THEATER STOCK THATS SUPPOSEDLY DeAd 💀 
Why are there so many more ftds then $AMZN or $AAPL ? Anyone ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:38:18 </td>
   <td style="text-align:left;"> $AAPL Form PX14A6G (notice of exempt solicitation submitted by non-management) filed with the SEC https://newsfilter.io/a/2c51453dc941dfa8c6a667b9bb224c24 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:38:08 </td>
   <td style="text-align:left;"> Options: 
BTO $NFLX Calls 440 Feb 04 at 9.55 
BTO $SPY Calls 456 Feb 02 at .54 
BTO $MVIS Calls 3.50 Feb 04 at .14 
BTO $NVDA Calls 255 Feb 04 at 2.01 
BTO $AAPL Calls 177.50 Feb 04 at .48 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:37:59 </td>
   <td style="text-align:left;"> $AAPL That’s the Confirmation I wanted GAP~N~GO Tomorrow!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:37:55 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $AAPL is the #1 stock that institutions are trading over rolling 5 day window with 541.4K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:36:10 </td>
   <td style="text-align:left;"> $RBLX $GOOG $AAPL liking these earnings reports </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:36:04 </td>
   <td style="text-align:left;"> $AAPL  . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:35:26 </td>
   <td style="text-align:left;"> last week called the $AAPL gap up right on the money

now played the $PYPL puts right on the money.. 

Both strike prices were on the spot as well lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:35:21 </td>
   <td style="text-align:left;"> $AAPL $Spy on the rise AH, Apple will follow, don’t see a real drop until maybe Monday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:34:18 </td>
   <td style="text-align:left;"> $AAPL here comes the run </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:32:27 </td>
   <td style="text-align:left;"> $QQQ tech doesn&amp;#39;t do well with rising rates... that&amp;#39;s bullshit.  $GOOGL $AMD $MSFT $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:32:08 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-02-01 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=F5Kcx8X63YA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:31:19 </td>
   <td style="text-align:left;"> $PYPL that woke CEO Dan S** needs to be fired.. glad i took loss and moved to $AAPL last year.. feel bad for shareholders </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:31:12 </td>
   <td style="text-align:left;"> $AAPL We have been forecasting AAPL to decline into the blue box and bounce higher in mid January.  The bounce now is strong enough where either a new cycle higher has started, or the instrument will decide to do the double.  We are looking for further extension higher as the preferred scenario at this point.  Members who bought the blue box have already taken partial profits..   #Elliottwave #Trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:31:09 </td>
   <td style="text-align:left;"> $AAPL  Money running to the prima donnas AH…they’ll take profits and we’ll see a pop….the mkt will fly tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:30:52 </td>
   <td style="text-align:left;"> $AAPL $GOOG $AMD inflation killer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:30:46 </td>
   <td style="text-align:left;"> $AAPL well look at that </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:30:05 </td>
   <td style="text-align:left;"> $AAPL we take off tomorrow don’t worry </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:29:08 </td>
   <td style="text-align:left;"> $AAPL And while everybody moons this shit decides to burn with theta now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:26:37 </td>
   <td style="text-align:left;"> $AAPL dividends on Friday, hold the line </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:26:33 </td>
   <td style="text-align:left;"> $AAPL somehow, Netflix is having better recovery from dismal earnings while apple should have been back to 180 from its earnings as it’ll be hard to be beat for the next few quarters </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:26:20 </td>
   <td style="text-align:left;"> $PYPL $AAPL already going to disrupt this market, it has no where to go except back to $100 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:26:05 </td>
   <td style="text-align:left;"> ICYMI - 20 STOCKS TO CONSIDER IN FEBRUARY    
All charts covered in detail.      
$AAPL $MSFT $NFLX $NVDA and is $AMZN getting ready to rip higher?    
All fully assessed plus many more charts and ideas.      
https://www.honeystocks.com/analysis </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:25:53 </td>
   <td style="text-align:left;"> $AMD $AAPL $GOOG  $GOOGL 
Apple came to rescue last week.  AMD and Google this week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:25:35 </td>
   <td style="text-align:left;"> $GOOGL $GOOG see example of what happened to $TSLA and $AAPL after split announcement. This old bitch is about to run!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:24:37 </td>
   <td style="text-align:left;"> $AAPL 

Since you heard AMD and GOOG just beat expectation..

This is very good and it will push AAPL to ATH and past 3T this month!

It’s very encouraging !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:24:13 </td>
   <td style="text-align:left;"> $AAPL total MM manipulation here, hold strong! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:24:13 </td>
   <td style="text-align:left;"> What we are seeing this past week are the true leaders like $GOOG $MSFT and $AAPL distinguish themselves from the hype companies like $TSLA. People nowadays want real earnings, clear guidance, responsible leadership. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:23:00 </td>
   <td style="text-align:left;"> $AAPL $AMZN $GOOG $QQQ $SPY  goog is the only company out of 5 that had okay earnings. The rest going down the shitter. Market will be lower tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:22:38 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $AAPL $TSLA  
 
If this keeps up PIGGIE gonna be 100% cash in his retirement accounts in a week or two! 
 
He is now 65% cash as of today and will move 15% more to cash at 4600 and 10% at 4700 and 4800. 
 
Then Piggie done for year!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:21:57 </td>
   <td style="text-align:left;"> $AAPL 20:1 stock split JULY... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:21:35 </td>
   <td style="text-align:left;"> $PYPL told you … its a dead money… people were offensive on my post! $AAPL pay will take offer! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:21:04 </td>
   <td style="text-align:left;"> $AAPL steady and solid. 200$ soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:20:51 </td>
   <td style="text-align:left;"> $AAPL all money flowing into google and amazon 😂 rotten apple getting left behind  lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:19:07 </td>
   <td style="text-align:left;"> $SPY is ready to round the bases now. $AAPL threw the pitch and $GOOG knocked it out of the park. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:18:25 </td>
   <td style="text-align:left;"> $MSFT $AAPL these two better be up tomorrow by at least 1% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:18:11 </td>
   <td style="text-align:left;"> $AAPL For the 🐻 they can blow on a soft one </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:17:06 </td>
   <td style="text-align:left;"> $AAPL couldn’t even end green and missed getting out of these calls. Likely it opens red it seems </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:16:37 </td>
   <td style="text-align:left;"> $AAPL market is pumping up and this is getting shorted back down to 170. Can’t hold 174 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:16:11 </td>
   <td style="text-align:left;"> $GOOG  Plans a 20 to 1 stock split. Will it have the same effect as it did for $TSLA and $AAPL ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:15:39 </td>
   <td style="text-align:left;"> $AAPL going back up!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:15:25 </td>
   <td style="text-align:left;"> $SPY  next to split in the mid term  is $AAPL $GOOG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:15:24 </td>
   <td style="text-align:left;"> $XELA Best penny stock
way to go XELA.
Not even 1 dollar yet. 
$aapl $tsla $AMZN  $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:14:37 </td>
   <td style="text-align:left;"> $DIS still cheap and long way to catchup while earnings blowout $GOOGL $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:14:22 </td>
   <td style="text-align:left;"> $AAPL $176 open tomorrow $180 end of week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:14:08 </td>
   <td style="text-align:left;"> $AAPL why is this down after $GOOG beat? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:13:43 </td>
   <td style="text-align:left;"> $AAPL keeps dumping while market moves up. Seems to be that this is getting shorted as a hedge </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:13:42 </td>
   <td style="text-align:left;"> $SPY $GOOG $AAPL $ARKK $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:13:41 </td>
   <td style="text-align:left;"> $AAPL - Apple&amp;#39;s Cash-Based Sources Of Intrinsic Value Are Amazing!. https://t.co/2MVgcR7UTY #economy #finance #trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:13:18 </td>
   <td style="text-align:left;"> $AAPL I though Google going up would help other tech stocks go up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:13:05 </td>
   <td style="text-align:left;"> $GOOGL Damn, moving like $AAPL on those nice earnings. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:12:41 </td>
   <td style="text-align:left;"> $NFLX  positions that i added last week $RH $AMD $NFLX  still $BAC and $AAPL my biggest one 💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:12:13 </td>
   <td style="text-align:left;"> $AAPL Google and AMD mooning while I decided to keep holding these APPL calls...shit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:11:49 </td>
   <td style="text-align:left;"> $GOOGL $AAPL $QQQ $TSLA $SPY 

BOOM 💥 

TECH IS BACK!!!!!

$GOOGL Q4 Earnings

Revenue: $69.2B v $59.3B Expected 
EPS: $30.69 v $26.69 Expected </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:10:08 </td>
   <td style="text-align:left;"> Goodman Financial Corp,has filed Form 13F for Q4 2021.Opened NEW positions in $AAPL $ALB $BRK/B $EUSA $IXUS $SNDR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:10:08 </td>
   <td style="text-align:left;"> $AAPL 🍏 ❗️No Company has come close, to AAPL’s Earnings.  Apple, is the standout in the World. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:09:49 </td>
   <td style="text-align:left;"> $GOOGL they seen how much it helped $AAPL and $TSLA for to long they had to join the party. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:09:27 </td>
   <td style="text-align:left;"> $AAPL No chips. Bad delivery. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:09:01 </td>
   <td style="text-align:left;"> $AAPL bulltrap  its bad report 100 % </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:08:01 </td>
   <td style="text-align:left;"> $GOOGL wow.     Jeeeeeezzzz

Yes.   I own the hell out of this.   

$amzn $fb $nflx $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:07:14 </td>
   <td style="text-align:left;"> $SOFI pelosi bought sofi shares today! $SPY $AAPL $TSLA $UPST </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:07:06 </td>
   <td style="text-align:left;"> $AAPL   🍏Google, big beat! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:06:44 </td>
   <td style="text-align:left;"> $AAPL Bull Trap here huh........LMAO from $60s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:06:14 </td>
   <td style="text-align:left;"> $AAPL   🍏👍    Strong Mkt Recovery into the Close! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:05:00 </td>
   <td style="text-align:left;"> $AAPL: The short term is neutral, but the long term trend is still positive. Not much to worry about for now. https://www.chartmill.com/stock/analyzer/stock/AAPL?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:04:01 </td>
   <td style="text-align:left;"> $SPY i just like seeing degenerate retail bears lose. nothing is sweeter $TSLA $AAPL $MSFT $NDX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:03:28 </td>
   <td style="text-align:left;"> $AAPL Closed Red what a bummer.. what going on here? Its trading 28X the earnings. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:03:19 </td>
   <td style="text-align:left;"> $AAPL barely missed my sell price. Thing struggled all day and this ah price action may mean even more decay for these calls I wanted to get out of. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:02:58 </td>
   <td style="text-align:left;"> $AAPL Hahaha that was a fun day. Not sure why anyone would want to create stress owning this stock... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:02:48 </td>
   <td style="text-align:left;"> Top Bearish Flow Today : 

$TSLA $HYG $VIX $AAPL $AMD

🤖📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:01:36 </td>
   <td style="text-align:left;"> $SOFI we are going to hit $20 before
The Super Bowl at sofi stadium! NFL
Fans united and buy this stock to support your team!!!! $SPY $QQQ $AMC $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:01:35 </td>
   <td style="text-align:left;"> $AAPL alphabet earning will raise the whole sector </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:01:31 </td>
   <td style="text-align:left;"> $AAPL  🍏 Close, 174.61. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:01:00 </td>
   <td style="text-align:left;"> $AAPL Mr PUTZ.............tomorrow morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:00:16 </td>
   <td style="text-align:left;"> $AAPL we where so closeeeeeee </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 05:00:15 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple News launches its first daily local newsletter, targeting Bay Area readers https://www.stck.pro/news/AAPL/22346628 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:59:42 </td>
   <td style="text-align:left;"> $AAPL enjoy these levels for now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:58:55 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL Snopes confirmed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:58:53 </td>
   <td style="text-align:left;"> $SPY Ha ha &amp;quot;ALL CLEAR WHISTLE BLOWN..&amp;quot; 
btfd! BARCELONA BULLS ARE BACK RUNNING! $DIA $QQQ $UVXY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:58:13 </td>
   <td style="text-align:left;"> $QQQ $SPY $VIX $SPX $AAPL  
 
i have to say, today is probably the most angry i&amp;#39;ve seen retail bears since last week. You covering will only facilitate the inevitable which is SPX 4700 in Feb 
 
All of your January profit gone by 2/4 
 
retail never learns </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:57:49 </td>
   <td style="text-align:left;"> $AAPL 
+$175 BREAKOUT 🍏🔜🆙🔝 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:57:12 </td>
   <td style="text-align:left;"> $AAPL going green +2c </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:56:50 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $AAPL $TSLA  
 
keep printing money and pumping asset prices when the average American is struggling with 7% inflation.  
 
You show &amp;#39;em your true colors JDADDY! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:56:50 </td>
   <td style="text-align:left;"> $AAPL clowns bears what’s the difference? 🤷‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:56:50 </td>
   <td style="text-align:left;"> $AAPL COME ONNNNNNNN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:56:38 </td>
   <td style="text-align:left;"> $AAPL bought some 2/11 $170 Puts, this bounce feels way too forced. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:56:31 </td>
   <td style="text-align:left;"> $AAPL holding us from green. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:56:19 </td>
   <td style="text-align:left;"> $AAPL gotta love that it reach for the high to yesterdays close. Right to the penny!  Come on now! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:56:14 </td>
   <td style="text-align:left;"> $AAPL FINISH GREEN PLEASE AND THANKS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:56:11 </td>
   <td style="text-align:left;"> $AAPL bears got played here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:55:46 </td>
   <td style="text-align:left;"> $AAPL 5 MINUTES TO 175 eod lets go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:55:42 </td>
   <td style="text-align:left;"> $AAPL may actually finish green? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:55:30 </td>
   <td style="text-align:left;"> $AAPL Buy every dip $$$$$$$$$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:55:16 </td>
   <td style="text-align:left;"> $AAPL Bears laughed at me when I bought shares for $158 during the JPow presser... 
 
P.S.: Not selling... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:55:01 </td>
   <td style="text-align:left;"> $AAPL everything else pumping up with ease and this is struggling like no other to break into the green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:55:00 </td>
   <td style="text-align:left;"> $AAPL no more shorts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:53:58 </td>
   <td style="text-align:left;"> $SOS Biggest  blessing of your life to sell now. Enjoy profits and buy $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:53:57 </td>
   <td style="text-align:left;"> $AAPL Does anyone know what motley is pushing concerning Project Garta with apple phones? The next great stock? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:53:53 </td>
   <td style="text-align:left;"> $AAPL That Hoya whatever guy blocked me. He&amp;#39;s a super fan boy for Apple. Watch out. I stick my what I say and know. Under 150 eom </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:53:15 </td>
   <td style="text-align:left;"> $AAPL you can do it Apple let’s close this Green and then soar AH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:53:11 </td>
   <td style="text-align:left;"> $AAPL Closing Green??? Will upset the bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:53:03 </td>
   <td style="text-align:left;"> $AAPL short sellers gotta cover before ex dividends day on Feb. 04 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:53:00 </td>
   <td style="text-align:left;"> $AAPL We are going Green 🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:52:17 </td>
   <td style="text-align:left;"> $AAPL 

There is no more shorts here..
They already covered at huge loss so it’s MM will set to 175 today! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:51:54 </td>
   <td style="text-align:left;"> $AAPL under 150 eom mark it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:51:32 </td>
   <td style="text-align:left;"> $AAPL strong close...as long as GOOG doesn&amp;#39;t blow it..Feb should be good. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:51:25 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:51:22 </td>
   <td style="text-align:left;"> $AAPL You might want to step out of the way here........Mr PUTZ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:51:10 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:51:09 </td>
   <td style="text-align:left;"> $AAPL Big rally towards the close $GOOG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:51:04 </td>
   <td style="text-align:left;"> $AAPL Funny how the doomsday prophets never show up at the end of the day to admit that they were wrong, er, TOTALLY FUCKING WRONG ($170, $165, $150, $135, $118, etc., etc.) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:50:37 </td>
   <td style="text-align:left;"> Past 3rd Qtr #’s 
&amp;gt; https://d1io3yog0oux5.cloudfront.net/_29cde4c8283359ae156ea75577e27551/amd/db/778/6672/file/AMD+Q3%2721+Financial+Results+Slides.pdf

$AMD ↗️➕ $XLNX 

$TSLA  | $AAPL | $INTC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:50:07 </td>
   <td style="text-align:left;"> $AAPL come on 175 close! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:49:58 </td>
   <td style="text-align:left;"> $AAPL 178 Eod tmw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:48:48 </td>
   <td style="text-align:left;"> $AAPL if $GOOG hits their numbers today, Apple going up too! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:48:42 </td>
   <td style="text-align:left;"> $AAPL 4hr view from 1/27 update. Found buyers at the blue box area &amp;amp; showing reaction higher taking place from the blue box area. Longs should be risk free by now #elliottwave #trading #stocks #Apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:48:35 </td>
   <td style="text-align:left;"> $AAPL no 175 at close😭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:48:08 </td>
   <td style="text-align:left;"> $AAPL $178 Tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:47:46 </td>
   <td style="text-align:left;"> Swing: $AAPL 180c @.15 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:46:17 </td>
   <td style="text-align:left;"> $AMD $NVDA $GOOG $AAPL $TSLA 
We still down this much last 30 days. We got more space to go up isn’t it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:45:34 </td>
   <td style="text-align:left;"> $MSFT $AAPL $SPY I can hold longer than your poots can have value </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:44:38 </td>
   <td style="text-align:left;"> latex4c027482e21de1072a82a0faebad6b53$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:37:28 </td>
   <td style="text-align:left;"> $AAPL after Google/Alphabet blows it out of the park later today.  Apple will move very quickly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:36:30 </td>
   <td style="text-align:left;"> $AAPL is going kill it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:35:46 </td>
   <td style="text-align:left;"> $AAPL     🍏👍: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:34:38 </td>
   <td style="text-align:left;"> $AAPL still can’t run without constant dips </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:33:47 </td>
   <td style="text-align:left;"> $AAPL Bears today bwahahahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:33:07 </td>
   <td style="text-align:left;"> $AAPL probably green Eod </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:32:22 </td>
   <td style="text-align:left;"> “Even after raising guidance multiple times through 2021 from 37% to 50% to 60% to now 65%, we believe AMD has the capacity to deliver upside, which would have been higher with better supply,” Ramsay, who has an outperform rating and a $150 price target on $AMD, wrote.

➕ $XLNX 🛎 🗣🦁

$TSLA | $AAPL | $INTC  https://www.marketwatch.com/story/amd-is-about-to-wander-into-a-minefield-11643413893 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:31:52 </td>
   <td style="text-align:left;"> $AAPL 1hr view from 1/14 Pre-Market update presented to members at elliottwave-forecast.com/ #elliottwave #trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:31:43 </td>
   <td style="text-align:left;"> $AAPL Lets do this WS! $$$$$$$$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:31:30 </td>
   <td style="text-align:left;"> $NFLX $AAPL $WISH Low float IPOs getting run all over. Check $BTBD 💲 Run over 800% in AH last week 🚀💰💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:31:23 </td>
   <td style="text-align:left;"> $AMD  you have amd too; i bought some for earning call.. usually hate it but i regretted about $aapl earning about not to play; what u think about amd earning? i think $goog safer but somehow my hand went to amd  .. @Kornie7 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:31:00 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $UVXY

3 straight green day’s after the SPY bottomed means the correction is over. Congrats bulls you survived a fud driven bear market now let’s see if the bears can survive a fed driven bull market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:30:48 </td>
   <td style="text-align:left;"> $AAPL run far away.  
 
https://www.tradingview.com/chart/AAPL/gg8hZ1Y6-AAPL-P-Modeling-Pt-X1-The-Blank-Canvas-of-Cajun/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:30:30 </td>
   <td style="text-align:left;"> $AAPL $MSFT Alphabet&amp;#39;s Earnings Are About to Land. Watch for News on the Ad Market. 

https://newsfilter.io/a/29489bdb837aba361100ad9869388f5a </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:29:46 </td>
   <td style="text-align:left;"> $SPY $QQQ $VIX $SPX $AAPL  
 
what do degenerate gamblers do when they win $500 on a scratch ticket? 
 
they spend $500 buying more scratch tickets + cigarettes and alcohol. 
 
in the end you only have yourselves to blame. 
 
Enjoy bankruptcy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:29:34 </td>
   <td style="text-align:left;"> Options just seem so easy for companys that start with 1 penny options out of the money. 100 bucks with 100 options is pretty legendary. If that penny becomes .50 cents. Yo. You did it. You can do that with $BRK.B and $AAPL  what else? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:28:08 </td>
   <td style="text-align:left;"> $SPY $QQQ $VIX $AAPL $TSLA  
 
i shouldn&amp;#39;t enjoy watching all of you clueless fuckwit bears who made money that didn&amp;#39;t belong to you in January, lose it all this week...  
 
But i can&amp;#39;t help myself...  
 
Seeing retail become bankrupt buying puts warms my heart. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:27:55 </td>
   <td style="text-align:left;"> $AAPL AKIC$ THE NEXT PIXAR IS GOING PUBLIC!!!!
https://www.stocktitan.net/news/AKIC/dneg-to-become-the-only-pure-play-publicly-traded-visual-effects-and-v7fwlzs7l9z3.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:27:11 </td>
   <td style="text-align:left;"> $AAPL #Apple $AAPL video from 12 January looking at the #Elliottwave path https://www.youtube.com/watch?v=q1xLRP7d8LA  #trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:26:37 </td>
   <td style="text-align:left;"> $AAPL 175 EOD Lets go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:26:18 </td>
   <td style="text-align:left;"> $AAPL let’s go!!! 174 hold for EOD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:26:06 </td>
   <td style="text-align:left;"> $SPY $UPS earnings report told the real truth on the supply chain and inflation unlike lying Cook over at $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:22:45 </td>
   <td style="text-align:left;"> $AAPL perhaps could buy $TTWO or $RBLX to make a play on the gaming space with $MSFT buying $ATVI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:22:32 </td>
   <td style="text-align:left;"> $AAPL looking at the chart this looks like the next top could be somewhere around $184.50(ish) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:22:26 </td>
   <td style="text-align:left;"> $AAPL puts still printing huh? BaHahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:22:05 </td>
   <td style="text-align:left;"> $AAPL okay Apple let’s do this!!  Up up and Away!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:20:24 </td>
   <td style="text-align:left;"> $AAPL Chart of The Day 12 January: #Apple can see further downside https://elliottwave-forecast.com/stock-market/elliott-wave-view-apple/  #elliottwave #trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:19:35 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple&amp;amp;#8217;s Stellar Earnings Will Make Its Recent Drop a Distant Memory https://www.stck.pro/news/AAPL/22345348 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:18:54 </td>
   <td style="text-align:left;"> Unusual Option Alert on $AAPL $1,232,412 call sweep traded with $130.0 strike expiring on 2022-06-17. Via: https://www.stockgrid.io/optionsflowcumulativestats/AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:16:01 </td>
   <td style="text-align:left;"> $AAPL I meant Stephanie Link buying Apple sorry for typo  earlier </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:15:03 </td>
   <td style="text-align:left;"> $BKKT   It wasn&amp;#39;t like this before, but it is now.  Way faster upside, a stupidly positioned 10m shares sold short, ultra-low float, and look at the chart this week.  It&amp;#39;s a dream position right here.  Move a position from $TSLA or $AAPL into Bakkt. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:15:02 </td>
   <td style="text-align:left;"> $AAPL if y’all can’t look at this chart and see a correction coming there’s no hope for you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:15:01 </td>
   <td style="text-align:left;"> $AAPL let’s take this positive! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:14:25 </td>
   <td style="text-align:left;"> $AAPL    🍏👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:13:53 </td>
   <td style="text-align:left;"> $aapl $btc.x $qqq $spy https://www.youtube.com/watch?v=KnhPvpaJEeo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:13:26 </td>
   <td style="text-align:left;"> $tsla $btc.x $qqq $aapl https://www.youtube.com/watch?v=JnaAE_VcHqs&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:13:23 </td>
   <td style="text-align:left;"> $SPY todays power hour brought to you by $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:12:52 </td>
   <td style="text-align:left;"> $AAPL struggling with 174 again today. Been having issues breaking through these walls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:11:49 </td>
   <td style="text-align:left;"> $AAPL let close 175 today! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:10:18 </td>
   <td style="text-align:left;"> $AAPL let’s go green. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:10:08 </td>
   <td style="text-align:left;"> GARRISON BRADFORD &amp;amp; ASSOCIATES INC,has filed Form 13F for Q4 2021.Opened NEW positions in $AAPL $ARGX $BAM $WMT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:09:51 </td>
   <td style="text-align:left;"> $AAPL Might see the Day highs in power hour, then a swing to 180- for the week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:08:37 </td>
   <td style="text-align:left;"> $AAPL just won’t drop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:08:08 </td>
   <td style="text-align:left;"> $AAPL    🍏 Updated daily.  Not reliable…just to cancel the “Bear Children’s toxic laughter”.  Going Higher: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-02-02 04:07:27 </td>
   <td style="text-align:left;"> $AAPL Never short apple. I did and lost more than 50%. Trying to short this is like trying to fight head on with a Bison 🦬. Survival chances are 0.005 in 100. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 09:01:44 </td>
   <td style="text-align:left;"> $TSLA Elon a stupid prick. Get use to it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 09:00:56 </td>
   <td style="text-align:left;"> $TSLA still overvalued. People who made money should be glad they jumped in early and acknowledge what an anomaly Tesla was with it P/E remaining so high for so long. 
 
Do you really think these historic levels of valuations are going to continue for much longer? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 09:00:42 </td>
   <td style="text-align:left;"> $TSLA MIND BLOWING POTENTIAL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 09:00:33 </td>
   <td style="text-align:left;"> $LKNCY I respect what $SBUX has done in China. I really do. They dominated the above-average coffee market for 10-15 years, and blanketed the country in stores. Way ahead of other coffee companies.  They managed to convince many people to pay $6 for a latte when the average income was $500 a month. But there comes a time in every foreign entity’s experience in China when they realize their window of opportunity is closing. They’ve been allowed remarkable freedom to penetrate the market, to invest huge amounts of money, to undergo much trial-and-error. But when a local company rises up to compete, the writing is on the wall. Either change your corporate structure to allow for local ownership (Yum brands), sell everything (Uber), or get squashed. You will not be allowed to continue to succeed at the expense of local companies. I’m also looking at you, $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:59:59 </td>
   <td style="text-align:left;"> $TSLA THAT&amp;#39;S IT.....BEARS ARE SMOKED! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:59:48 </td>
   <td style="text-align:left;"> $TSLA He doesn&amp;#39;t even have a family. What a prick of a human being. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:59:47 </td>
   <td style="text-align:left;"> $TSLA wow nice jump wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:59:10 </td>
   <td style="text-align:left;"> $TSLA who’s wet about tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:59:00 </td>
   <td style="text-align:left;"> $TSLA I&amp;#39;ll be conservative $988 Tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:58:53 </td>
   <td style="text-align:left;"> $TSLA 
WTF? 
What is this crap 💩?
Where is my +-50 point daily move.
#scam </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:58:06 </td>
   <td style="text-align:left;"> $TSLA i know where’s its going to bounce .. 👁⏰ do you? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:56:36 </td>
   <td style="text-align:left;"> $TSLA Can&amp;#39;t fix stupid. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:56:22 </td>
   <td style="text-align:left;"> $TSLA 

Looking like chips shortage may be easing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:55:21 </td>
   <td style="text-align:left;"> $TSLA my knowledge of TA is very basic and I am trying to find something bullish on the current tesla chart.

Any input would be appreciated 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:55:13 </td>
   <td style="text-align:left;"> $TSLA Does anybody have a favorite level two software program? And how does it compare to streetsmart edge through Schwab? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:54:28 </td>
   <td style="text-align:left;"> $TSLA Going to fly tomorrow. $1000 incoming by Friday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:54:07 </td>
   <td style="text-align:left;"> $SPY $DJIA latex3bc412ec80a0ff995584bcf6c75c3ffbNIO
$GM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:49:45 </td>
   <td style="text-align:left;"> $GOOGL 

And ya telling me newbies buy CEI/ SNDL/ PROG crap? Man! How do they ignore stocks like $AMZN $TSLA $MSFT 

GOOGLE🔥🔥🔥
🤑💰💰💰💸💸💸💥💥💥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:48:49 </td>
   <td style="text-align:left;"> $TSLA when tesla reached their peak earnings, it will make google earnings look like nothing when we overtake the oil giants of the world </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:48:44 </td>
   <td style="text-align:left;"> ***NEW VIDEO****  
$TSLA Analysis that has turned out to be correct for the bull case 
Youtube- https://www.youtube.com/watch?v=1j3-fRIs-5Q </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:47:13 </td>
   <td style="text-align:left;"> $TSLA Google to split 20:1 to 150.00 (3000/20) 
Futures will be green on Google beat, along with Tesla!! 
 
Austin/Berlin factory opens up soon; and possibility of Tesla robots in 2022! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:46:37 </td>
   <td style="text-align:left;"> $TSLA 

We will fly from here. 
All good news ahead. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:46:21 </td>
   <td style="text-align:left;"> 3/3

$AMD absolutely blisters Q4:
-Record revenue, NI and EPS
-Top &amp;amp; bottom beat
-50% GM that we haven&amp;#39;t seen for a while (2006)
-Ryzen &amp;amp; GPU ASP up
-7th record Epyc qtr
-Strong Q1 guide (45% rev/50.5% GM) w/o Xilinx
-Killer &amp;#39;22 guide: $21.5B rev +31%; 51% GM w/o Xilinx / $XLNX 

$AAPL $TSLA $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:46:06 </td>
   <td style="text-align:left;"> 2/3

$AMD absolutely blisters Q4:
-Record revenue, NI and EPS
-Top &amp;amp; bottom beat
-50% GM that we haven&amp;#39;t seen for a while (2006)
-Ryzen &amp;amp; GPU ASP up
-7th record Epyc qtr
-Strong Q1 guide (45% rev/50.5% GM) w/o Xilinx
-Killer &amp;#39;22 guide: $21.5B rev +31%; 51% GM w/o Xilinx / $XLNX 

$AAPL $TSLA $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:45:47 </td>
   <td style="text-align:left;"> 1/3

$AMD absolutely blisters Q4:
-Record revenue, NI and EPS
-Top &amp;amp; bottom beat
-50% GM that we haven&amp;#39;t seen for a while (2006)
-Ryzen &amp;amp; GPU ASP up
-7th record Epyc qtr
-Strong Q1 guide (45% rev/50.5% GM) w/o Xilinx
-Killer &amp;#39;22 guide: $21.5B rev +31%; 51% GM w/o Xilinx / $XLNX 

$AAPL $TSLA $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:44:58 </td>
   <td style="text-align:left;"> $AMZN Amazon is going to split I am 100% confident it will, they have to, retail are also investors and can boost the stock to new highs. No split since 1998!

Let’s go Jeff Bezos time to pump Amazon to new highs

$GOOGL $AAPL $TSLA $SPY

Never forget Apple and Tesla split

Google will run above EMA9 all day tomorrow algos will trigger it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:43:02 </td>
   <td style="text-align:left;"> $PLUG $FCEL $TSLA 

Great video to open our eyes to what our great leaders 👏 are doing and did with our tax money.

They spent 125 Trillions dollars vs 3.5 T is what they told us 😡😡😡 big fat liars,,,our dollar is worthless . 

Thank you Govt for bailing out banks and many countries with our $$.

This why Jerome Powell would respond to difficult questions &amp;quot;I don&amp;#39;t I have an answer&amp;quot;. Of course not, USA is deep trouble,,,inflation through the roof because of your bad decisions 😀👏👏

https://youtu.be/awG_-9aDpUg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:42:23 </td>
   <td style="text-align:left;"> $TSLA anyone know anything about this 

https://www.reuters.com/business/autos-transportation/tesla-recalls-nearly-54000-us-vehicles-rolling-stop-software-feature-2022-02-01/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:41:27 </td>
   <td style="text-align:left;"> $tsla 1010 open 👍🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:40:35 </td>
   <td style="text-align:left;"> Ticker: $TSLA 
Buy: February 04, 2022 $935.00 Calls 
Entry Price: $20.76 - $21.00 
Exit Price: $26.78 
Stop Loss: $18.27 
Potential ROI: 29% 
Estimated Hold Time: 64 Minutes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:40:25 </td>
   <td style="text-align:left;"> $TSLA some google powered rocket fuel tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:39:56 </td>
   <td style="text-align:left;"> $TSLA wen moon? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:39:46 </td>
   <td style="text-align:left;"> $TSLA $GOOG has good earning, so did $FB the market should look good tomorrow, bears will get roasted </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:39:12 </td>
   <td style="text-align:left;"> $TSLA https://www.investors.com/news/tsla-stock-recalls-nhtsa-probe-self-driving/?src=A00220 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:37:41 </td>
   <td style="text-align:left;"> $TSLA I think we break that 50 ma in 180 day tommorow should see $970 minimum </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:36:01 </td>
   <td style="text-align:left;"> New Analysis: How smart money knew this bounce was coming. Plus, why tail-chasing in $TSLA makes sense: https://cracked.market/2022/02/how-smart-money-knew-this-bounce-was-coming-plus-while-tail-chasing-in-tsla-makes-sense/ $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:36:00 </td>
   <td style="text-align:left;"> $TSLA has a Profit Margin of 10.25%. This is amongst the best returns in the industry. https://www.chartmill.com/stock/quote/TSLA/fundamental-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:35:58 </td>
   <td style="text-align:left;"> $TSLA 🤔 inverse head and shoulder </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:35:32 </td>
   <td style="text-align:left;"> $TSLA Google’s massive beat &amp;amp; 20:1 split is going to send tech stocks, including Tesla, surging again as all that cash flows back into tech. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:35:32 </td>
   <td style="text-align:left;"> $TSLA tomorrow we ride 💰💰💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:35:11 </td>
   <td style="text-align:left;"> $TSLA can’t even rise above green on a green nasdaq day. pathetic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:34:49 </td>
   <td style="text-align:left;"> $TSLA 

Split then trade it at $150-$170 n enjoy 😉 the gold rush back to $370 then breakout all over again (10X psychological satisfaction) 

That’s how we get to 46k over the next 5yrs — Retails are on standby to take dirtbags HFs to laundry cleaner…  @elonmusk !! 

🙏🏻🐉🦅👀⬆️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:34:30 </td>
   <td style="text-align:left;"> $TSLA $GOOGL  20-1 split , remember when Tesla did it , it went up crazy. Google will be $4000 a share than split $200 a share. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:32:47 </td>
   <td style="text-align:left;"> $TSLA Sub 1100 after recalling yesterday…🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:32:22 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-01 Technical Analysis Video: 
https://www.youtube.com/watch?v=cTY7eiTJeZs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:31:15 </td>
   <td style="text-align:left;"> $TSLA 🤔🤔🤔 Thought we would get a bigger bump in the afterhours.   
Not much happening with Aapl or Microsoft either??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:30:55 </td>
   <td style="text-align:left;"> $TSLA sub 900 tomorrow, more recall news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:29:57 </td>
   <td style="text-align:left;"> $TSLA https://chng.it/h9C7Dk8Kzh
Please share. The Ignorant and sell out Biden needs to know. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:29:13 </td>
   <td style="text-align:left;"> $TSLA 1000+ tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:28:14 </td>
   <td style="text-align:left;"> $TSLA 950+ ??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:28:01 </td>
   <td style="text-align:left;"> $tsla cnbc will talk about Canada fsd rollout all day tomorrow 🚀🚀

🔥🔥🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:27:55 </td>
   <td style="text-align:left;"> $TSLA your real President is on NewsMax tonight $dwac </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:27:42 </td>
   <td style="text-align:left;"> $TSLA anybody holding weekly puts rip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:27:37 </td>
   <td style="text-align:left;"> $CLSK $GOOGL $TSLA growing more than we do being trillion(s) worth 😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:26:39 </td>
   <td style="text-align:left;"> $TSLA futures are ripping… tomorrow 🔥🔥💎💎💎💎💎💐💐💐💐💎💎💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:26:37 </td>
   <td style="text-align:left;"> $AMD revenue graph📈

➕ $XLNX 🤑

$AAPL | $TSLA | $MSFT N </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:26:22 </td>
   <td style="text-align:left;"> $TSLA $VOO $QQQ Groundhog day tomorrow.   Will this year be a repeat of 2020? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:24:38 </td>
   <td style="text-align:left;"> $TSLA not sure what I think here for rest of week. That top trendline is giving us hell. Recall news didn’t help. Not that it matters but big money use it to play with price action. Seems like traders left today when it touched 944 area and then algos took over rest of day. I like that it held where it did and and market is still bullish but gonna need some real volume tomorrow or it’ll likely start making its way to bottom of trend channel. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:20:49 </td>
   <td style="text-align:left;"> $btc.x $tsla $qqq $aapl $msft https://www.youtube.com/watch?v=JnaAE_VcHqs&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:20:03 </td>
   <td style="text-align:left;"> $TSLA  Cramer said to buy tesla on his show tonight. We&amp;#39;re fucked now and going to drop immediately. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:19:01 </td>
   <td style="text-align:left;"> $tsla rest day today after massive rally y’day.  Rally resumes tomorrow 🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:18:21 </td>
   <td style="text-align:left;"> $tsla $lcid $rivn https://www.youtube.com/watch?v=utVr6bkZmIA&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:17:44 </td>
   <td style="text-align:left;"> Sweep Options Activity: $TSLA is the #8 ticker with sweep activity where institutions are trading options urgently with 18.9K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:16:45 </td>
   <td style="text-align:left;"> $SPY convoy to DC let’s go $TSLA 

https://youtu.be/518Ekf5zeQU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:15:30 </td>
   <td style="text-align:left;"> $TSLA $1000 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:15:01 </td>
   <td style="text-align:left;"> $TSLA scary bears will hide tomorrow they have only one night to scrap🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:13:42 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:12:57 </td>
   <td style="text-align:left;"> $SPY YALL thought CANADA had protests …. USA truckers next latexa374e3b18388ff973068291614b901b5NVDA - 78% call flow 
$AAPL - 56% call flow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:10:15 </td>
   <td style="text-align:left;"> $TSLA this is going to try 970 $ tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:10:11 </td>
   <td style="text-align:left;"> $TSLA $GM the leading EV make according to Biden  
GM Q4 2021 sold 440,745 vehicles, down 43%. Of those 440,745 vehicles, only 26 were EVs sold 
https://www.reuters.com/markets/us/general-motors-fourth-quarter-us-auto-sales-drop-43-2022-01-04/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:09:17 </td>
   <td style="text-align:left;"> $TSLA looks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:08:54 </td>
   <td style="text-align:left;"> $TSLA this is just straight manipulation $AMC apes 🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:07:36 </td>
   <td style="text-align:left;"> My first bad Tesla experience - 

A Tesla dealership swapped out my summer tires for winter tires and ended up scratching all 4 rims. 

A quick complaint through the app and now I have an appointment to get them corrected. Still sucks but at least its getting fixed.

$TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:07:35 </td>
   <td style="text-align:left;"> $TSLA So nobody take a win or lost today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:06:48 </td>
   <td style="text-align:left;"> $GOOGL as tempting as it is I can’t let fomo take over …I’ll be catching the dip at $2850 going balls deep then should see $4500 before split in July but it’s running way too hot on technicals atm $TSLA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:06:47 </td>
   <td style="text-align:left;"> $tsla don’t underestimate this news that came late. Very very big deal.  🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:06:29 </td>
   <td style="text-align:left;"> $SPY yikes $TSLA 

https://www.zerohedge.com/markets/tesla-accused-inflating-sales-australia-after-company-sales-data-fails-reconcile-official </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:02:26 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-01 Trade Analysis Video: 
https://www.youtube.com/watch?v=6oauuZoF2tM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:01:11 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ :&amp;quot;:&amp;quot;: 
 
 
Account Challenge Update:-  
Start Date: Jan 3, 2022  
Starting Balance: $1,700  
Current Balance: $79,584 
Goal: $100,000 by end of February.  
Strategy: Swing Trade Options, Stocks  
  
Watch out for next play👓 amazing-chat-room.stocksboss.xyz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 08:00:48 </td>
   <td style="text-align:left;"> $TSLA expecting a nice gap up after $GOOGL blew it out of the water sell your puts asap $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:58:11 </td>
   <td style="text-align:left;"> $TSLA stock sank on great earnings report. Wallstreet indeed cannot stand this company and his leader. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:57:57 </td>
   <td style="text-align:left;"> $TSLA People jumping up and down in jubilation about Google missed all the excitement tonight with Paypal. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:55:40 </td>
   <td style="text-align:left;"> $TSLA $1200 by end of the week. Wahoo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:54:54 </td>
   <td style="text-align:left;"> $TSLA $940.00+6%=996.40=$1k Thanks Google! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:54:28 </td>
   <td style="text-align:left;"> $TSLA lithium- metal backed batteries IPO / SES - Level A 3rd party audited for 1st step in production capability. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:52:32 </td>
   <td style="text-align:left;"> $TSLA is this bullish or bearish? 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:52:25 </td>
   <td style="text-align:left;"> $TSLA 3 days to reach 1200$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:50:56 </td>
   <td style="text-align:left;"> Tesla: Still Attractive Even without New Vehicle Models -- my article for @TipRanks https://tipranks.com/news/article/tesla-still-attractive-even-without-new-vehicle-models/ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:48:40 </td>
   <td style="text-align:left;"> $TSLA imaging where are we if Tesla had a focused earning conference call </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:48:03 </td>
   <td style="text-align:left;"> $TSLA while entire tech sector is up this turd is still sitting at 930s lol 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:45:16 </td>
   <td style="text-align:left;"> $TSLA tech sector pumping and $TSLA and $AAPL  holding down, expecting some upside movements EOW…👀👀👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:44:57 </td>
   <td style="text-align:left;"> $TSLA trash </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:42:49 </td>
   <td style="text-align:left;"> $TSLA this better do better in the morning with  tech up like crazy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:41:48 </td>
   <td style="text-align:left;"> $TSLA when roadster? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:41:27 </td>
   <td style="text-align:left;"> $GOOGL $TSLA 2.0 LOL!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:40:33 </td>
   <td style="text-align:left;"> $GOOG $GOOGL Remember when $TSLA did their 5:1 stock split and it nearly doubled within a month. Don’t miss this opportunity folks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:37:17 </td>
   <td style="text-align:left;"> $TSLA Meet kevin sold his google shares along with Tesla. Now google splits. Wow. That’s what happens to a guy a like that. $GOOGL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:34:43 </td>
   <td style="text-align:left;"> $GM $F $TSLA  Interesting Take 
 
https://www.benzinga.com/news/earnings/22/02/25348278/josh-brown-says-the-general-motors-story-entirely-hinges-on-this-single-ev-rollout </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:34:30 </td>
   <td style="text-align:left;"> $GOOGL way overbought on 180 day waiting on a dip to $2900 before going all in $TSLA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:34:26 </td>
   <td style="text-align:left;"> $GM missing sales while $TSLA clobbers expectations quarter after quarter. Yet Brandon got the nerve to ignore this incredible company. F U Brandon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:33:34 </td>
   <td style="text-align:left;"> $TSLA $880 soon… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:33:09 </td>
   <td style="text-align:left;"> Tesla Model 3 Police Car Hits Hampshire, UK This Wee 
 
Tesla’s Model 3 Performance can reach 0-60mph in 3.1 seconds, offering supercar speeds to police forces 
 
$TSLA 
 
https://teslanorth.com/2022/02/01/tesla-model-3-police-car-hits-hampshire-uk-this-week/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:32:40 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/UU_4xfd0Xh0 evs lets gooo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:32:01 </td>
   <td style="text-align:left;"> Tesla Gigafactory Texas catalyzes $500M, 2,500 home development project 
 
Gigafactory Texas most recent estimates have projected at least 15,000 new jobs both directly &amp;amp; indirectly at the plant  
 
Tesla has created 5,000 new jobs in Austin as of Oct. 
 
$TSLA 
 
https://www.teslarati.com/tesla-gigafactory-texas-housing-development-500-million-mirador/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:30:41 </td>
   <td style="text-align:left;"> $TSLA Analysis that has turned out to be correct for the bull case 
Youtube- https://www.youtube.com/watch?v=qNHsRE_D8CI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:29:28 </td>
   <td style="text-align:left;"> $TSLA 

Biden is Di**k head 

https://www.businessinsider.com/tesla-biden-elon-musk-petition-electric-cars-2022-2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:29:16 </td>
   <td style="text-align:left;"> Unusual Options Activity: $TSLA is the #24 ticker with unusual activity from institutional traders with an average of 15% out of the money, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:27:23 </td>
   <td style="text-align:left;"> $TSLA https://l.facebook.com/l.php?u=https%3A%2F%2Fwww.instagram.com%2Freel%2FCYkNLxkhzhb%2F&amp;amp;h=AT2yyoBSXj4ucTztDJv3PK0DMvswgCki_iEwbUESGROAYf4AIEAydj6hwNjwRg597se3M5oRJAcVDc4RxkvMpTpNBQKVegVQ4zZFjz-QwPIB_u8nEqWoQbzSgnXfvpJO-pfO5szuQAh7t092xQ&amp;amp;s=1&amp;amp;fs=e&amp;amp;s=cl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:26:40 </td>
   <td style="text-align:left;"> $TSLA Anything Cathy Wood buys, I short. 👋🏼👋🏼👋🏼🔻🔻🔻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:25:26 </td>
   <td style="text-align:left;"> $TSLA GOOGLE JUST ANNOUNCED 20:1 stock split 🚀🚀🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:23:45 </td>
   <td style="text-align:left;"> $TSLA still think this rips to $5000 by Friday. today was just a dip before the rip.

 Unferperforming the indices is bullish as fuck.   

🚀 🚀 🚀  to the moooon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:22:38 </td>
   <td style="text-align:left;"> $TSLA will Joe Byron ever say Telsa? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:20:14 </td>
   <td style="text-align:left;"> $TSLA i have met with my counsel and it is agreed, she breaks $960 by 10am and $1000 by noon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:19:51 </td>
   <td style="text-align:left;"> $TSLA fuck so tempted to get onto $GOOGL any other tesla bros get in it ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:19:44 </td>
   <td style="text-align:left;"> $TSLA Andrew D Baglino sold 3,500 shares [Very Low Conviction] https://www.insider-analysis.com/search_transactions.php?ticker=TABLE_TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:15:24 </td>
   <td style="text-align:left;"> $tsla 173,000 likes and you think this guy doesn&amp;#39;t post for a living? hahahahah  mass report the trolls with no trading accounts $GOOG 
 
@blancobull </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:13:09 </td>
   <td style="text-align:left;"> $TSLA still think this rips to $1100 by Friday. Today was just a dip before the rip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:12:55 </td>
   <td style="text-align:left;"> $TSLA 175,000 likes hahahahahaha $goog </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:11:43 </td>
   <td style="text-align:left;"> $TSLA 

Only Tesla goes down 11% after impressive earning .. huh?! 

Scumbags HFs in bed with Scumbags SEC !!! 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:11:07 </td>
   <td style="text-align:left;"> $SPY forget about EV’s look at these autonomous futes 🥂 $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:09:14 </td>
   <td style="text-align:left;"> $TSLA Larry Ellison needs to coach Elon to do something now for shareholders </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:09:00 </td>
   <td style="text-align:left;"> $TSLA what the target here by end of February </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:08:47 </td>
   <td style="text-align:left;"> $TSLA looks like FSD will finally happen next year!
https://www.thestreet.com/investing/teslas-full-self-driving-feature-dealt-a-big-blow-puts-musks-promises-at-risk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:08:28 </td>
   <td style="text-align:left;"> $TSLA When split?🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:07:43 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $GOOG $TSLA  
 
Everyone get a &amp;quot;participation trophy&amp;quot; in JPOW FREE MONEY PARTY!... except bear :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:06:03 </td>
   <td style="text-align:left;"> $TSLA let&amp;#39;s recap... 1. no new vehicle models this entire year, 2. Musk will instead focus on building an autobot, Optimus Prime, 3. Recall of FSD despite Musk claim lv 5 autonomy will be reached this year, 4. No Semi delivered to Pepsi despite Pepsi claiming it would receive Semis by end of January,  5. Delivery numbers maybe exaggerated as inferred by the report out of Australia, 6. Legacy Automakers have begun production and sale of popular evs this year, 7. Giga Berlin still not  open, 8. Musk and Tesla being investigated by the DOJ and SEC.  With all the above, how is the share price above $200? The current price is a gift for longs so that they can exit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:05:52 </td>
   <td style="text-align:left;"> $TSLA should drop tomorrow another $50 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:05:48 </td>
   <td style="text-align:left;"> $GOOGL on second though gonna wait for a dip split ain’t till 6 months sticking with latexae78df39af276c2fc340bf125764231dPYPL
$TSLA
 https://www.cnbc.com/2022/02/01/after-a-huge-year-for-growth-the-us-economy-is-about-to-slam-into-a-wall.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:03:47 </td>
   <td style="text-align:left;"> $TSLA these bears lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:02:24 </td>
   <td style="text-align:left;"> $TSLA possible inverse H &amp;amp; S on goin 2nd shoulder down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:01:23 </td>
   <td style="text-align:left;"> $TSLA technical analysis for tomorrow. 
 
https://youtu.be/9LHzAEjEBzI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:01:19 </td>
   <td style="text-align:left;"> $TSLA Anyone wanna take bets when it&amp;#39;s found out that Elon is found out to be a frequent flyer of Epstein Island? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 07:00:12 </td>
   <td style="text-align:left;"> $TSLA this will crash hard tomorrow ppl will be leavin this going to $GOOGL , one of the few red stocks today, support at 850ish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:59:29 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:59:08 </td>
   <td style="text-align:left;"> $TSLA $QQQ $SPY $ARKK $NVDA futures limit up ??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:57:24 </td>
   <td style="text-align:left;"> Bears are having hard to hide now :) 
 
$AAPL $TSLA $SPY $AMD $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:56:48 </td>
   <td style="text-align:left;"> $TSLA even goog and amd glitter can’t stick to auto companies. overpriced fanboys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:54:55 </td>
   <td style="text-align:left;"> $NVDA $TSLA back to eating SPAM  for the bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:53:29 </td>
   <td style="text-align:left;"> $GOOGL thinking of exiting my $TSLA position for this 🤔 decisions </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:50:58 </td>
   <td style="text-align:left;"> $TSLA $QQQ $SPY Options trading frenzy https://www.ft.com/content/b3db7eca-8bee-4178-91cb-f6e20da9e242 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:50:16 </td>
   <td style="text-align:left;"> $TSLA 90% of the posts here are trolls with no trading accounts it&amp;#39;s sad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:49:32 </td>
   <td style="text-align:left;"> $AMD $nvda $intc $tsla $AAPL 

AMD Gross Margin: from 27% (2016) to 48% (2021)
Intel Gross Margin: from 63% (2016) to 53% (2021)

from the above numbers, you will know which to buy. 

amd margin will grow further as more CPUs and GPUs are to be sold to Tesla and Apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:49:20 </td>
   <td style="text-align:left;"> $TSLA Tomorrow $TSLA will split, then the next day each share will be $5,000 and will promptly split again. Every day will be thus. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:49:03 </td>
   <td style="text-align:left;"> $TSLA  reverse the last split, $5000 a share would get rid of the RifRaf. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:47:01 </td>
   <td style="text-align:left;"> $TSLA wasn&amp;#39;t PayPal Musk&amp;#39;s company? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:45:37 </td>
   <td style="text-align:left;"> $GOOGL the last time $tsla 5:1 split it went extra $1000+? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:43:41 </td>
   <td style="text-align:left;"> $BTC.X $TSLA why are there so few Bitcoin and Tesla millionaires here? Because they retired and are now enjoying the rest of their lives. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:43:35 </td>
   <td style="text-align:left;"> $TSLA I’m wearing green shorts tomorrow 🤩🤩🤑🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:42:28 </td>
   <td style="text-align:left;"> $TSLA STOP TALKONG ABOUT A SPLIT!!!  THIS DIDNT SPLIT TILL $2400 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:41:49 </td>
   <td style="text-align:left;"> $TSLA tomorrow $999🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀🙏🏼🙏🏼🙏🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:41:35 </td>
   <td style="text-align:left;"> $BTC.X in the long run non panicking bulls always win. Friend of mine went through it with $TSLA. She retired early and has an amazing life! Know what you own!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:41:27 </td>
   <td style="text-align:left;"> $TSLA 💎💎💎👍👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:40:32 </td>
   <td style="text-align:left;"> $TSLA When will Tesla announce split like Google. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:40:19 </td>
   <td style="text-align:left;"> $TSLA Elon ready with Twitt… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:40:06 </td>
   <td style="text-align:left;"> New report on chargers has Electrify America and $TSLA at the top, followed by $CHPT and $EVGO. Near the bottom is $BLNK. Say it over and over, blink is an overvalued 💩💩💩. Still not worth buying imo.
https://www.prnewswire.com/news-releases/electrify-america-positioned-first-in-2021-electric-vehicle-charging-infrastructure-benchmark-by-umlaut-and-charged-301471594.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:39:39 </td>
   <td style="text-align:left;"> $TSLA will everyone take profits from tech tmrw ??? Thus driving down market??? ;o </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:39:36 </td>
   <td style="text-align:left;"> $TSLA in for a squeeze tomorrow … </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:38:33 </td>
   <td style="text-align:left;"> $PYPL has overtaken $TSLA as the second most mentioned ticker on WSB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:37:39 </td>
   <td style="text-align:left;"> Tesla: Still Attractive Even without New Vehicle Models -- my article for @TipRanks https://www.tipranks.com/news/article/tesla-still-attractive-even-without-new-vehicle-models/ $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:37:26 </td>
   <td style="text-align:left;"> $TSLA Lol Squeeze the Shorts tomorrow ;) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:36:40 </td>
   <td style="text-align:left;"> $TSLA Pool at Circa and i come across this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:35:36 </td>
   <td style="text-align:left;"> $TSLA Stocks were ripping today. Simulated Weekly $935.0 CALLS for Wednesday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:34:00 </td>
   <td style="text-align:left;"> $TSLA shows a strong growth in EPS: 204.86%. https://www.chartmill.com/stock/analyzer/stock/TSLA?view=fundamental-analysis&amp;amp;key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:32:23 </td>
   <td style="text-align:left;"> $GM   GM&amp;#39;s Low cost EV pickup truck is gonna do well.  The $80-100k pickup truck fad will fade fast

$f $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:32:16 </td>
   <td style="text-align:left;"> $TSLA 

Go Tesla!!! 
🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:31:19 </td>
   <td style="text-align:left;"> $TSLA guys, be patient! Easy. Stop haste… give some time to the stock! We are just went through a rough correction. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:30:45 </td>
   <td style="text-align:left;"> $TSLA wake up mr sock puppet 

https://www.businessinsider.com/tesla-biden-elon-musk-petition-electric-cars-2022-2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:30:40 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-01 Largest Trades Data: 
https://www.youtube.com/watch?v=fHhlcxVUyvc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:29:17 </td>
   <td style="text-align:left;"> $GOOG The 20 for 1 split is awesome news.  Now time for $AMZN &amp;amp; $TSLA to do the same. 😍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:28:20 </td>
   <td style="text-align:left;"> $AMD $NVDA $AMZN $TSLA 
Bought the (near term) bottom playas and put ya money to work? Thats how u make money while sleeping baby!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:27:45 </td>
   <td style="text-align:left;"> $TSLA Look at the bright side!!  
 
Futures will be green (and Tesla will be green!) after Google/AMD earnings beats!! 
 
We also got Austin/Berlin  factory openings this year and possibly Tesla robots!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:27:39 </td>
   <td style="text-align:left;"> $TSLA Once they stop black balling TSLA it will fly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:27:33 </td>
   <td style="text-align:left;"> $TSLA 50% growth on $75Billion revenue with 40% gross margins!!! 

I can see this $2k by end of the year unless socialists somehow poop on Tesla. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:27:26 </td>
   <td style="text-align:left;"> $TSLA the tech is goin insane now. Stunning ERs after on another </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:25:55 </td>
   <td style="text-align:left;"> $TSLA this should be trading at $1250 right now with huge beats across the board. 

Probably the only mega company with no real competition even close. . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:25:51 </td>
   <td style="text-align:left;"> $TSLA Asking a bull, what&amp;#39;s tomorrow&amp;#39;s catalyst the sunrise?😏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:23:26 </td>
   <td style="text-align:left;"> $MVIS I think $AAPL or $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:23:24 </td>
   <td style="text-align:left;"> $TSLA big tech running with earnings beat but this stock got robbed with their earnings last week 😤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:23:14 </td>
   <td style="text-align:left;"> $TSLA this recall thing is such a scam there’s updates on Tesla every few weeks just media trying to overhype a technical error still the safest car on road </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:22:50 </td>
   <td style="text-align:left;"> $RIDE $TSLA Called Tesla retracing to $800 in November, was called stupid by you pumpers, and just so you know the trend is still intact to go even lower! Sorry to all those meet Kevin pumpers,  and musk fans, you all ignored 1) clear signs of a double top, 2) repeated recalls and 3) cybertruck delays . The first pump and dump was hertz, the next was a Tesla phone, and now Mr. musk is pushing a robot to keep the attention on him. Laughable!!!!! Great company, but a con of a ceo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:22:46 </td>
   <td style="text-align:left;"> $TSLA did you all forget we had a 10% move up yesterday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:21:36 </td>
   <td style="text-align:left;"> $TSLA if google missed we would be down big but when it’s up big we don’t follow market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:21:18 </td>
   <td style="text-align:left;"> $TSLA  
 
TSLA Key Levels Grid For Feb 2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:21:03 </td>
   <td style="text-align:left;"> $TSLA stupid algos </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:20:44 </td>
   <td style="text-align:left;"> $TSLA Lol Biden’s hypocrisy and social injustice against Tesla is repulsive ;) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:20:42 </td>
   <td style="text-align:left;"> $GOOG $AMD $NVDA $NFLX $TSLA  how to bet on earning with very high win rate! https://youtu.be/NJLJ-BXvUJw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:20:40 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:20:27 </td>
   <td style="text-align:left;"> $AMD  All of the hedge funds cannot be wrong  
  
Ignore the BS of Robinhood, these stocks are NOT a meme stocks 
 
This actually flew over Robinhood&amp;#39;s headquarters in Menlo Park  California, it was hilarious and Robinhood&amp;#39;s CEO couldn&amp;#39;t do anything about it, nothing was illegal :) 
 
https://www.youtube.com/watch?v=WFie1ep9xk0 
 
$AAPL $TSLA $SPY $AMD $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:20:05 </td>
   <td style="text-align:left;"> $VIAC

 $GOOGL stock split shouldn’t be bullish for the stock momentum, but it will be. Just like it was for $AAPL and $TSLA last year.

The question becomes, are they smart enough to also have a stock offering to raise cash, and aquire $VIAC?

Would $GOOGL and it’s YouTube TV platform benefit from acquiring $VIAC? 

After tense negotiations with ESPN ($DIS) in December, I think Google would love to own its own sports right. And thats just one piece of the puzzle. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:19:54 </td>
   <td style="text-align:left;"> $TSLA 950-960 am </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:19:40 </td>
   <td style="text-align:left;"> $TSLA back under resistance. will it drag spy down tmrw?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:19:32 </td>
   <td style="text-align:left;"> $TSLA anyone using this broker https://alpaca.markets ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:18:03 </td>
   <td style="text-align:left;"> $TSLA will open 980 at 4AM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:16:51 </td>
   <td style="text-align:left;"> $RIDE $TSLA Called Tesla retracing to $800 in November, was called stupid by you pumpers, and just so you know the trend is still intact! Sorry to all those meet Kevin pumpers,  and musk fans, you all ignored 1) clear signs of a double top, 2) repeated recalls and 3) cybertruck delays . The latest pump and dump was hertz, now Mr. musk is pushing a robot to keep the attention on him. Laughable!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:16:33 </td>
   <td style="text-align:left;"> $AMD $NVDA $AMZN $RBLX $TSLA 
Yes we having the nice run!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:16:06 </td>
   <td style="text-align:left;"> $TSLA lmao that AH price action was so sad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:16:06 </td>
   <td style="text-align:left;"> $TSLA if this isn&amp;#39;t flying in AH now after those ERs, then what will it do tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:15:04 </td>
   <td style="text-align:left;"> $TSLA can we touch $987 tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:13:58 </td>
   <td style="text-align:left;"> $TSLA With Tom Lee’s V shape perspective, this thing can run up to $1243 in February! Go! Elon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:13:32 </td>
   <td style="text-align:left;"> $TSLA is my favorite index </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:13:22 </td>
   <td style="text-align:left;"> $TSLA long term investing idea: look at $GOOG . Just buy Tesla now. Don’t look at your account until split is announced… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:13:09 </td>
   <td style="text-align:left;"> $TSLA Tesla will split next and the same thing will happen! I’ve been waiting for this for a while now and here we go! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:11:11 </td>
   <td style="text-align:left;"> $TSLA been a while since I was bullish this stock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:11:04 </td>
   <td style="text-align:left;"> $TSLA if we break 969, which is the 100 day MA, and close above it. We will get more investors to jump in. Next stop will be the 50 day MA which is 1028! Overall looks good, hopefully we can continue to trend upwards. The chart looks like it’s ready to break the down trend, but needs to break 969… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:09:36 </td>
   <td style="text-align:left;"> $TSLA 

Delivery numbers tomorrow right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:09:15 </td>
   <td style="text-align:left;"> $AMC elon, either we fill AMC parking lots up with lambos or we can charge our $TSLA while we watch a movie, the choice is yours... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:08:01 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $GOOGL stock split 20-1 Google is a monster </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:07:39 </td>
   <td style="text-align:left;"> $TSLA Google +up 200+ points (OPption -+7%  straddle spread was correct)  
 
Google about $150.00 (3000/20) in a few days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:06:00 </td>
   <td style="text-align:left;"> $TSLA flat day tomorrow all the cash will be piling into $GOOGL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:05:42 </td>
   <td style="text-align:left;"> $TSLA after a closer look at the weekly chart I believe Tesla will trade sideways tomorrow and squeeze Thursday. Hopefully squeeze tomorrow but I doubt it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:05:40 </td>
   <td style="text-align:left;"> $TSLA Im curious about $F  earnings! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:04:02 </td>
   <td style="text-align:left;"> $TSLA  hold. $SPY going for a short bullish run. Surpassed resistance $450. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:03:50 </td>
   <td style="text-align:left;"> $TSLA 1100$ in the next 2 weeks. 1200 around may after a backtest </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:02:38 </td>
   <td style="text-align:left;"> $PYPL it’s gonna do a $TSLA $MSFT $AMD and  $NFLX move </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:02:33 </td>
   <td style="text-align:left;"> $TSLA With all these massive tech earnings beats, tomorrow could be interesting... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:02:14 </td>
   <td style="text-align:left;"> $AMC $GME  $TSLA $NFX $AMD 

🚨UPDATE🚨

With Pelosi announcing she is running again, reminder I made the Pelosi ETF.

It tracks her &amp;amp; husband&amp;#39;s real time performance, and posts active positions.

She is currently up 32% on her stock positions &amp;amp; 12% on options, beating the indices.

unusualwhales.com/i_am_the_senat… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:00:30 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-02-01 Options Analysis Video: 
https://www.youtube.com/watch?v=0tnQnz5O8Bk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 06:00:28 </td>
   <td style="text-align:left;"> $TSLA when is the car numbers coming out? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:59:36 </td>
   <td style="text-align:left;"> $GM Earnings look good. Not sure why people would pay hefty valuations to buy $TSLA shares when $GM is getting into EV too and trades at a much cheaper valuation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:59:15 </td>
   <td style="text-align:left;"> $TSLA when delivery numbers Elon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:57:49 </td>
   <td style="text-align:left;"> $TSLA Bollinger band looks like it’s laying back in missionary. That means we’re about to get fucked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:57:14 </td>
   <td style="text-align:left;"> $TSLA realistically I see this testing 980 if the trend holds this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:56:02 </td>
   <td style="text-align:left;"> $TSLA this will go to 1k+ tomorrow due to google earnings, amd earnings, and spy recovering. easy 1k tomorrow. options will print. then i will move on to amazon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:55:37 </td>
   <td style="text-align:left;"> $TSLA sheeeesh $1k tomorrow or the next day 100% mark my words </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:55:12 </td>
   <td style="text-align:left;"> $TSLA Every index rallying and growth stocks released great earnings, but Tesla algos lagging </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:54:26 </td>
   <td style="text-align:left;"> $TSLA we gonna have a really bullish February. Market has had a good correction. Time to fly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:54:01 </td>
   <td style="text-align:left;"> $SOFI PayPal is  not a bank! We don’t know PayPal! He was just an intern that got us coffee! Buy sofi because unlike PayPal, we actually beat our earning forecast here! $PYPL $SPY $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:53:05 </td>
   <td style="text-align:left;"> $AMD I think Nasdaq 100 future will be back 16000 soon since major companies release strong ER report. Tech group is back!!!🚀🚀🚀🚀🚀 $TSLA, $LCID, $NVDA 🚀🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:52:56 </td>
   <td style="text-align:left;"> $TSLA lol. Just stops at 934. Fucking algos </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:52:23 </td>
   <td style="text-align:left;"> $TSLA so keyword in the ER for $goog was &amp;quot;AI&amp;quot; i wonder who is the leader in AI who has the #1 luxury vehicle on the planet that literally drives itself and who can land rockets on a floating barge and send humans and cargo to space and back at will??? hmmmm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:51:08 </td>
   <td style="text-align:left;"> $XOM $TSLA $SPY  
 
2022 
 
XOM +29% 
Tesla -19% 
 
delta 48% 
 
my god!...lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:50:52 </td>
   <td style="text-align:left;"> $TSLA  
 
Mostly reliable insider below showing large dip of M3 in China compared to last month.  
 
Bears - puts might be in play.  
 
Bulls - prepare your ass for FUD.  
 
https://twitter.com/teslashanghai/status/1488561361911431168 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:49:28 </td>
   <td style="text-align:left;"> $TSLA lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:49:25 </td>
   <td style="text-align:left;"> $TSLA Damm GM missed on sales....... who would of thought </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:48:58 </td>
   <td style="text-align:left;"> $TSLA going parabolic tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:48:40 </td>
   <td style="text-align:left;"> $TSLA Welp, there goes the AH push </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:48:18 </td>
   <td style="text-align:left;"> $TSLA can elonmusk give me job in Texas? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:47:58 </td>
   <td style="text-align:left;"> $TSLA Best App to track your Portfolio (Asset allocation etc.) and to discuss with the Community🚀🦍 And i will Get 3$ per Download 😂🙏 https://getquin.onelink.me/IQfD/trautisten be my Hero so i can Buy more tesla😇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:47:36 </td>
   <td style="text-align:left;"> $TSLA Oops! That tweet was a year old ;) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:47:26 </td>
   <td style="text-align:left;"> $TSLA 4 HOUR TIMEFRAME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:47:19 </td>
   <td style="text-align:left;"> $TSLA she breaks 1K manana by 10am </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:47:09 </td>
   <td style="text-align:left;"> $GM  maybe $TSLA fans can ride the robot around town </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:47:04 </td>
   <td style="text-align:left;"> $TSLA Soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:45:52 </td>
   <td style="text-align:left;"> $TSLA Good God it can’t even hold a small gain in AH either with $GOOG boosting the whole tech sector </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:44:12 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $TSLA is the #4 stock that institutions are trading over rolling 5 day window with 198.5K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:43:20 </td>
   <td style="text-align:left;"> $AMD 50% gross margin 😱 amazing..

Y/Y 68% revenue growth- this is $TSLA level growth. 

It’s bad for $INTC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:43:15 </td>
   <td style="text-align:left;"> $BTC.X $ETH.X $SPY $TSLA $DWAC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:42:45 </td>
   <td style="text-align:left;"> $TSLA So many corrupt journalists. So many want to damage Tesla. Filter the noise. 

https://twitter.com/elonmusk/status/1488615123946246151?s=20&amp;amp;t=RNOyr1vc0YyyWXvxmIipDg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:42:37 </td>
   <td style="text-align:left;"> ride captain ride aboard your $tsla calls!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:42:35 </td>
   <td style="text-align:left;"> $GOOGL $GOOG missed $TSLA ss not this one. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:42:18 </td>
   <td style="text-align:left;"> $AMD Can&amp;#39;t wait for my $TSLA Model Y with AMD Ryzen inside to arrive next month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:42:08 </td>
   <td style="text-align:left;"> $TSLA at some point this will retrace back to $850 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:42:01 </td>
   <td style="text-align:left;"> $TSLA 

Tesla 10:1 Split should not be far out IMO 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:41:58 </td>
   <td style="text-align:left;"> $SPY With earnings like this $GOOGL $AMD $AAPL $TSLA Who needs the FED. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:41:47 </td>
   <td style="text-align:left;"> $TSLA Sorry to the guy who had $1000 calls 01/28 worth $422k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:41:13 </td>
   <td style="text-align:left;"> $TSLA FYI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:41:08 </td>
   <td style="text-align:left;"> $TSLA “You’re leading Mary and it matters” 🤡🤣🤣🤣🤣🤣
https://www.marketwatch.com/story/gm-stock-falls-after-q4-sales-fall-short-11643750957 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:40:56 </td>
   <td style="text-align:left;"> $TSLA here we go! this all confirms it, bears got trapped </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:40:44 </td>
   <td style="text-align:left;"> $TSLA bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:40:23 </td>
   <td style="text-align:left;"> $GTEC $CENN $TSLA 🤣🧙🏼‍♂️🐂💩 NFA glta https://youtu.be/-WQsAYmwbC0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:40:17 </td>
   <td style="text-align:left;"> $SPY $GOOGL $GOOG $TSLA
GOOGLE will trade like Tesla Now…. Huge volatility incoming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:39:55 </td>
   <td style="text-align:left;"> $TSLA ty Elon, so many free $dwac calls, again man i love Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:39:55 </td>
   <td style="text-align:left;"> $TSLA $NIO 
EV stocks will continue down.
$TMC will continue up.
Check back in 3 years. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:39:49 </td>
   <td style="text-align:left;"> $TSLA 🤝 $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:39:39 </td>
   <td style="text-align:left;"> $TSLA not taking anything under 1200$ by EOW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:39:24 </td>
   <td style="text-align:left;"> $TSLA 1k tomorrow. glad i bought calls before close. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:39:22 </td>
   <td style="text-align:left;"> $TSLA   I can&amp;#39;t wait for the GM 4Q21 Losses Call!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:38:42 </td>
   <td style="text-align:left;"> $TSLA $GOOG 

https://www.cnbc.com/2022/02/01/google-parent-alphabet-announces-20-for-1-stock-split.html

Tesla is Next 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:38:38 </td>
   <td style="text-align:left;"> $TSLA $GM bulls thinking you can easily convert ICE factories to EV. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:38:28 </td>
   <td style="text-align:left;"> $TSLA I think tech group  is coming back since major companies release great ER!! Nasdaq 100 future would return $16000 soon!!!🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:37:58 </td>
   <td style="text-align:left;"> $tsla $amzn  will also shock the street on earnings, can&amp;#39;t wait </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:37:55 </td>
   <td style="text-align:left;"> $TSLA today was an opportunity to get long. The price action at support was a big tell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:37:32 </td>
   <td style="text-align:left;"> $TSLA we need a split too </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:36:51 </td>
   <td style="text-align:left;"> $F there is obviously some correlation between $GM earnings/forcasts and $F, but remember that most analysts out there believe that $F is well ahead of $GM in the EV race. The delivery numbers bear that out. It would have been nice if $GM crushed it&amp;#39;s numbers and forcast, but that doesn&amp;#39;t have any impact on what $F is going to report.  $F is presently number 2 in EV production and sales. 2nd only to $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:36:50 </td>
   <td style="text-align:left;"> $TSLA bears got trapped again smh. Ride the wave up, surf up damnit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:36:14 </td>
   <td style="text-align:left;"> $TSLA discretionary income spending falling. 
 
https://www.cnbc.com/2022/02/01/paypal-pypl-q4-2021-earnings.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:36:10 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:36:07 </td>
   <td style="text-align:left;"> $TSLA L F G </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:35:38 </td>
   <td style="text-align:left;"> $TSLA I want $1000 tonight! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:35:28 </td>
   <td style="text-align:left;"> $TSLA LFG $950-80 tomorrow 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:35:17 </td>
   <td style="text-align:left;"> $TSLA it&amp;#39;s happening now 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:34:49 </td>
   <td style="text-align:left;"> $TSLA we beat and dump $200, AMD and Google beat and skyrocket! FJB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:34:42 </td>
   <td style="text-align:left;"> $TSLA go up you stupid pooch! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:34:28 </td>
   <td style="text-align:left;"> Eat ass, save a life $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:34:27 </td>
   <td style="text-align:left;"> $TSLA $AMD $GOOG put the market on high green rest of the week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:34:25 </td>
   <td style="text-align:left;"> $TSLA pump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:34:24 </td>
   <td style="text-align:left;"> $TSLA SPILL THE NEWS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:34:11 </td>
   <td style="text-align:left;"> $TSLA Would like to see 995 tomorrow out of sheer curiosity..no strike. Got what I came for Friday ;) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:34:10 </td>
   <td style="text-align:left;"> $TSLA lmao bull flag breaking up in AH. Rip bears that were shorting all 933-934 zone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:34:05 </td>
   <td style="text-align:left;"> $TSLA why would Tesla even matter with Amazon??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:33:50 </td>
   <td style="text-align:left;"> $TSLA did Elon twitted? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:33:28 </td>
   <td style="text-align:left;"> $TSLA finally this bitch is going up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-02-02 05:33:13 </td>
   <td style="text-align:left;"> $TSLA With this Google HUGE BEAT and SPLIT..I see $1k by Friday. Its only tuesday...plenty of time to move up 50 bucks. we did that twice today with the daily action </td>
  </tr>
</tbody>
</table></div>

---
