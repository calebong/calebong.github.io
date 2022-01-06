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



Last Updated: 2022-01-06 10:06:51 UTC +8

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
   <td style="text-align:left;"> https://tradingeconomics.com/china/composite-pmi </td>
   <td style="text-align:left;"> 2022-01-06 09:57:30 </td>
   <td style="text-align:left;"> China Caixin Composite PMI Rises to 5-Month High </td>
   <td style="text-align:left;"> The Caixin China General Composite PMI rose to 53.0 in December 2021 from 51.2 a month earlier. This was the fourth straight month of growth in private sector activity and the strongest pace since July, amid stronger rates of output growth across both manufacturing and service sectors. Output has now risen in each of the past four months, with the latest gain the quickest since July, and new orders also expanded at a faster rate.  However, employment was stagnant as higher staffing levels at services companies were offset by a further fall in manufacturing payrolls. On the cost front, firms registered a further increase in average input costs, despite the rate of inflation weakening to a 15-month low. Looking ahead, sentiment slipped to its lowest since May 2020. “To sum up, the economy recovered in December with improvements in demand and supply of manufacturing and services, " said Wang Zhe, senior economist at Caixin Insight Group. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/colombia/inflation-cpi </td>
   <td style="text-align:left;"> 2022-01-06 09:43:06 </td>
   <td style="text-align:left;"> Colombia Inflation Rises Faster Than Expected </td>
   <td style="text-align:left;"> The annual inflation rate in Colombia rose 5.62% in December 2021, following a 5.26% increase in the previous month and topping market expectations for a 5.33% rise. This was the highest reading in nearly five years driven mainly by further increases in cost of food &amp; non-alcoholic beverages (17.23%) and restaurants &amp; hotels (8.83%). Rising consumer prices were also seen in transportation (5.69%), alcoholic beverages &amp; tobacco (4.6%), furniture &amp; household items (4.34%), miscellaneous goods &amp; services (4.19%), health (3.98%), accommodation, water, electricity, gas &amp; other fuels (3.68%), education (2.76%) and recreation &amp; culture (1.04%). Meanwhile, inflation eased for clothing &amp; footwear (-2.6%) and information &amp; communication (-12.1%). On a monthly basis, consumer prices rose 0.73% in December, accelerating from a 0.5% increase in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/05/business/starbucks-union-walkout-covid.html </td>
   <td style="text-align:left;"> 2022-01-06 09:37:45 </td>
   <td style="text-align:left;"> Starbucks Union Workers in Buffalo Walk Out Over Covid Concerns - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , By Emma Goldberg                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , With coronavirus cases surging across New York State, employees at the only company-owned Starbucks store that is unionized staged a walkout on Wednesday to protest what they say are unsafe working conditions.                                                                                                                                                                                                                                                                      , Kyli Hilaire, a barista at the store, which is in Elmwood in the Buffalo area, said that it was understaffed, that workers were struggling to enforce masking rules and that many of them were anxious about their health as they watched Covid-19 case counts spike in the region.                                                                                                                                                                                                    , “One of our requests was to close the store to let the outbreak of Covid run its course so we can return with a full staff rather than burning out the partners who are able to work,” Ms. Hilaire, 20, said. “They’re refusing to take the necessary precautions so our partners are not coming to work sick.”                                                                                                                                                                        , The walkout, involving about half a dozen employees, will last the rest of the week, she added. The company said it had not determined whether the store would stay open.                                                                                                                                                                                                                                                                                                              , Starbucks regional leaders met with union members on Tuesday night to discuss their safety concerns, which had mounted after an employee at the Elmwood store tested positive for the coronavirus. The company said all employees who had been in close contact with the infected person had been notified and given the option to quarantine themselves for five days with pay while monitoring for symptoms or awaiting Covid test results.                                          , “We have met and exceeded all C.D.C. and expert guidelines for safety,” said Reggie Borges, a Starbucks spokesman, adding that the company was giving store and district managers leeway to adjust their operations in response to the fast-spreading Omicron variant of the virus. “All leaders are empowered to make whatever changes make sense for their neighborhood, which includes shortening store hours or moving to 100 percent takeout only, which is the case in Buffalo.” , Starbucks announced on Monday that it would reduce the number of days that vaccinated, asymptomatic workers who tested positive for the virus must isolate themselves to five days from 10, following a shift in guidance from the Centers for Disease Control and Prevention. The company also said this week that all of its U.S. workers had to be vaccinated by Feb. 9 or submit to weekly testing, in compliance with the Biden administration’s vaccine rule for large employers., When the Starbucks workers in Elmwood voted to form their union last month, in an election recognized by the National Labor Relations Board, the result represented a challenge to the company’s long-running argument that its workers enjoy good wages and do not need a union.                                                                                                                                                                                                      , “It was kind of crazy walking out of work,” Ms. Hilaire added. “It was a first for everyone.”                                                                                                                                                                                                                                                                                                                                                                                          , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-01-06 09:08:24 </td>
   <td style="text-align:left;"> US Futures Steady After Fed-Triggered Rout </td>
   <td style="text-align:left;"> US stock futures were steady on Thursday after the major averages sold off in the previous session following the release of the Federal Reserve’s December meeting minutes. Dow futures rose 0.1%, while S&amp;P 500 and Nasdaq 100 futures were little changed. The latest Fed minutes revealed the central bank discussed reducing its balance sheet in another move to aggressively dial back its pandemic-era easy monetary policy. The Fed’s plan comes as it is already tapering its bond purchases and is set to hike interest rates, with members saying that a reduction in the balance sheet likely will start sometime after the central bank begins raising rates. The Dow and S&amp;P 500 fell 1.07% and 1.94%, respectively, following the release of the minutes, while the tech-heavy Nasdaq saw its biggest one-day decline since February by losing 3.34%. All 11 S&amp;P 500 sectors fell on Wednesday, led by the technology, communication services, real estate and consumer cyclical sectors. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/services-pmi </td>
   <td style="text-align:left;"> 2022-01-06 08:56:00 </td>
   <td style="text-align:left;"> Japan Services PMI Revised Upward </td>
   <td style="text-align:left;"> The au Jibun Bank Japan Services PMI was revised higher to 52.1 in December 2021, from a preliminary reading of 51.1 and following a final 53.0 in November, which was the highest reading in 27 months, as COVID-19 restrictions were eased, while demand continued to improve. The latest reading indicated a moderate expansion in the sector, but the average reading over the final quarter was the strongest quarterly performance since Q3 of 2019. New orders moderating, while new export orders rose to the fastest pace since October 2019, and employment fell slightly. On the cost side, input prices increased for the fourth month running, with the rate of inflation accelerating to the highest since August 2008; while output price inflation rose at the fastest pace since October 2019. Looking ahead, business confidence weakened to a three-month low, due to concerns regarding potential impact of new variants of COVID-19. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/composite-pmi </td>
   <td style="text-align:left;"> 2022-01-06 08:51:00 </td>
   <td style="text-align:left;"> Japan Composite PMI Revised Higher </td>
   <td style="text-align:left;"> The au Jibun Bank Japan Composite PMI was at 52.5 in December 2021, compared with a flash figure of 51.8 and a final 53.3 in November which was the highest reading since October 2017. The upward revision brought the average reading in the final quarter to the strongest quarterly performance since Q4 2018, amid continued rises in both factory activity and the service sector. New orders rose for the third month running, despite growth easing slightly from November. That said, stronger demand placed additional pressure on capacity as outstanding business rose at the fastest rate for 3-1/2-years. Meantime, staffing levels rose for the 11th month, with the rate of job creation being unchanged from November and marginal. On prices, input costs rose at the fastest pace since August 2008, which contributed to the fourth-fastest rise in output charges on record. Lastly, sentiment fell to a four-month low, due to fears over the potential impact of the Omicron strain. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-59887024?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-06 08:00:53 </td>
   <td style="text-align:left;"> Electric car sales soar, but chip shortage hits market </td>
   <td style="text-align:left;"> Sales of electric vehicles soared last year, but the market as a whole failed to recover from the Covid pandemic.                                                                                           , More electric cars were registered in 2021 than in the previous five years combined, according to the Society of Motor Manufacturers and Traders (SMMT).                                                    , Yet the industry body said much more investment is needed in charging infrastructure.                                                                                                                       , Meanwhile an acute shortage of computer chips left dealers struggling to get hold of many new conventional models.                                                                                          , Overall, 2021 was another dismal year for the motor industry. Preliminary figures from the SMMT show that some 1.65m cars new cars were registered.                                                         , That was a small increase over 2020, when the impact of the first Covid-related lockdowns and dealer closures sent sales plummeting.                                                                        , But it was still the second-worst figure recorded in nearly three decades, and 28% down on its pre-pandemic level.                                                                                          , At the beginning of the year, there was a further lockdown, while any hopes of a lasting recovery later on were dashed by a severe shortage of semiconductors - or computer chips.                          , These are critical components in modern cars, being used in areas such as engine management and emissions control, emergency braking, airbags, entertainment systems and navigation.                        , A modern car can use between 1500 and 3000 semiconductors.                                                                                                                                                  , But outbreaks of Covid-19 in regions where the chips are made, particularly in southeast Asia, caused factory closures that restricted supplies.                                                            , The motor industry also faced intense competition for the chips that were available from other sectors, particularly the consumer electronics industry.                                                     , This forced manufacturers to allocate what supplies they had to the most profitable models, as well as to those which helped them meet emissions targets - notably electric and plug-in hybrid cars.        , Despite the problems affecting the market as a whole, registrations of electric cars rose more than 75%, from 108,000 in 2020 to 191,000 last year.                                                         , In December, they accounted for one in every four cars sold, while the second-best selling car in the country during the year was Tesla's electric Model 3.                                                 , This trend will be welcomed by the government, which plans to ban the sale of new petrol and diesel powered cars by 2030, to help meet commitments on climate change.                                       , But the SMMT has warned that reductions in the value of the plug-in car grant could send out mixed messages to consumers.                                                                                   , In December, the maximum value of the grant, which is meant to bring down the cost of an electric car, was reduced from £2,500 to £1,500, and the number of eligible models was also narrowed down.         , "It's a confusing message", said Mike Hawes, chief executive of the SMMT.                                                                                                                                   , "It's a massive ambition to get the entire market to move to meet net zero by 2030/2035. We would argue you need to use every lever at your disposal".                                                      , "Anything that brings into doubt that commitment doesn't help a consumer who might be wavering".                                                                                                            , The industry body said it is also concerned that while electric vehicle sales are rising rapidly, the number of on-street public charging points is not increasing as quickly.                              , "There will be more people competing for a much more slowly increasing number of on street chargers", explained Mr Hawes.                                                                                   , "We want the user experience to be seamless, to be affordable and to be easy. And we just foresee this being one of the barriers to the consumer take-up of these vehicles that we need across the country.", But Melanie Shufflebotham, co-founder of the Zap Map website, which lists charging points across the country, disagreed that the rollout of new infrastructure has been too slow.                           , "Electric vehicles are now the norm", she said.                                                                                                                                                             , "Sales accelerated throughout 2021 and so did the public charging infrastructure. There are nearly 30,000 public chargers in the UK, an increase of more than a third since the end of 2020".               , "But we do need charging to keep growing at pace this year to make sure it is simple for the next generation of EV drivers".                                                                                , Meet the new candidates looking to impress Lord Sugar in The Apprentice                                                                                                                                     , How did Chinese woman Zheng Yi Sao and her army terrorise the seas?                                                                                                                                         , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-59886270?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-06 07:59:37 </td>
   <td style="text-align:left;"> Drivers overcharged by £5m a day for petrol, claims RAC </td>
   <td style="text-align:left;"> The RAC has accused petrol retailers of ripping off motorists by refusing to pass on wholesale price cuts.                                                                                                                                                                                                       , The motoring organisation said unleaded petrol fell by 2p a litre, but should have come down by 12p.                                                                                                                                                                                                             , It estimated drivers were overcharged by £5m a day in December as retailers made an average of 16p a litre on petrol instead of the normal 6p.                                                                                                                                                                   , The Petrol Retailers Association objected, saying drivers were likely to have benefited more than that.                                                                                                                                                                                                          , "December was a rotten month for drivers as they were taken advantage of by retailers," said the RAC's fuel spokesman, Simon Williams.                                                                                                                                                                           , In the past, he said, retailers had always reduced pump prices when wholesale prices dropped.                                                                                                                                                                                                                    , "This time they've stood strong, taking advantage of all the media talk about 'higher energy prices' and banked on the oil price rising again and catching up with their artificially inflated prices, which it has now done," Mr Williams said.                                                                 , But Gordon Balmer, executive director of the Petrol Retailers Association, said: "December's pump price data is less reliable because it is taken from fuel card transactions, and there have been far fewer of these transactions because of the reduction in business activity between Christmas and New Year.", He said the retail fuel market remained "extremely competitive" and said supermarkets did not use artificially low fuel prices to lure shoppers into their stores at Christmas.                                                                                                                                  , "The costs of running petrol stations rose all year, with electricity up 19%, vastly reduced margins from fuel cards, increased national insurance and wage inflation," he added.                                                                                                                                , The RAC said unleaded dropped from 147.47p a litre to 145.48p, when drivers should have seen prices nearer to 135p.                                                                                                                                                                                              , Diesel dropped by just under 2p a litre from 150.80p to 148.92p, when drivers should have been paying about 142p, it said.                                                                                                                                                                                       , The RAC's data suggested that the price of a litre of unleaded on the wholesale market, including delivery, averaged 106p across December.                                                                                                                                                                       , It said that had a 6p margin been taken by retailers, drivers would have seen an average petrol pump price of around 135p after applying VAT at 20%.                                                                                                                                                             , The average wholesale cost of delivered diesel was 112p a litre whicPetrol prices hit record high, says RACh, with the usual 6p retailer margin, would have given a pump price of about 142p.                                                                                                                    , "This means it has cost petrol car drivers £6 more to fill up a typical 55-litre family car than it should have (£80 v £74) and for diesel nearly £4 more, with a tank costing £82 at the end of the month instead of £78," the RAC said..                                                                       , It estimated retailers' refusal to reflect lower wholesale prices at the pumps cost petrol car drivers £156m in December, or the equivalent of £5m a day.                                                                                                                                                        , Howard Cox, founder of campaigning group FairFuelUK, called for the government to create an independent pricing watchdog.                                                                                                                                                                                        , "If gas, electricity, water and telecoms get price protection bodies, why shouldn't motorists have one too?" he said.                                                                                                                                                                                            , He said that if prices at the pumps were "honest and transparent and open to scrutiny", inflation could fall by as much as 1%.                                                                                                                                                                                   , "Pump prices should be 10p lower per litre if the actual wholesale price falls had been passed on honestly."                                                                                                                                                                                                     , "Sadly, the government's efforts to work with the fuel industry so that pump prices are competitive, and market driven, ensuring consumers benefit from lower prices, is not working," said MP Craig Mackinlay, chair of the All-Party Parliamentary Group for Fair Fuel for Motorists and Hauliers.             , Meet the new candidates looking to impress Lord Sugar in The Apprentice                                                                                                                                                                                                                                          , How did Chinese woman Zheng Yi Sao and her army terrorise the seas?                                                                                                                                                                                                                                              , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/mnuchin-current-state-economy-inflation-spending </td>
   <td style="text-align:left;"> 2022-01-06 07:21:02 </td>
   <td style="text-align:left;"> Mnuchin blasts Biden: 'We surely don't need more spending now' </td>
   <td style="text-align:left;"> Former treasury secretary Steven Mnuchin joins ‘Kudlow’ to discuss the current state of economy under the Biden administration.                                                                                                                                                                                                                             , Former Treasury Secretary Steven Mnuchin joined FOX Business' Larry Kudlow on Wednesday to offer his take on the state of the economy right now, and what should be done moving forward as the U.S. faces surging debt and inflation.                                                                                                                       , Former US Secretary of the Treasury Steven Mnuchin speaks during the Milken Institute Global Conference on October 19, 2021 in Beverly Hills, California.  (Photo by Patrick T. FALLON / AFP) (Photo by PATRICK T. FALLON/AFP via Getty Images / Getty Images)                                                                                              , Kudlow began by noting that the mantra of his show, of late, has been, "Save America, kill the bill," referring to the proposed Build Back Better Act being pushed by the Biden administration and congressional Democrats.                                                                                                                                 , While it appears to be dead for now, the passage of the legislation would mean an estimated $5 trillion more in federal spending on top of three prior multi-trillion-dollar emergency spending packages amid the pandemic.                                                                                                                                 , "We spent $4 trillion," Mnuchin said, referring to the stimulus packages spent in 2020 during the Trump administration, noting, "and the first two bills we passed 96-0 and 100-0 – overwhelming support – and I think had we not done that we would've had a global depression."                                                                           , Treasury Secretary Steven Mnuchin speaks with reporters about the coronavirus relief package negotiations, at the White House, Thursday, July 23, 2020, in Washington.  (AP Photo/Evan Vucci / AP Newsroom)                                                                                                                                                 , KUDLOW: WE ARE IN THE ‘GREAT RESIGNATION’                                                                                                                                                                                                                                                                                                                   , "But we should have stopped there," Mnuchin continued. Referencing Democrats' partisan COVID-19 relief bill from the spring, he said, "We didn't need the last $2 trillion, and we surely don't need more spending now."                                                                                                                                    , Mnuchin went on to blast the Build Back Better Act, saying, "When people say ‘Oh, it’s deficit neutral,' it's not deficit neutral. That's silly government math over a ten-year period. The debt would go way up."                                                                                                                                          , Kudlow then asked the former treasury secretary for his views on what will happen with inflation, which the host called "a government spending and [Federal Reserve] money-creation issue."                                                                                                                                                                 , "There's no question we have inflation, we're going to continue to have inflation," Mnuchin said.                                                                                                                                                                                                                                                           , Federal Reserve Chairman Jerome Powell arrives to testify at a House Financial Services Committee hearing on oversight of the Treasury Department and Federal Reserve coronavirus pandemic response on Capitol Hill on September 30, 2021, in Washington,  (Photo by Sarah Silbiger-Pool/Getty Images / Getty Images)                                       , "I think the Fed was slow, and I understand why they were slow because they wanted to be careful…but the minutes came out today," Mnuchin went on the say, referring to Fed officials' meeting last month. "Clearly the Fed is going to raise rates. The Fed is going to normalize the portfolio, it's just [a matter of] how quick or how fast they do it.", GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                 , "I think we're going to slow down inflation, but we definitely have to raise interest rates along the way," Mnuchin said. He went on to add that he feels the Fed was slow to react because Chair Jerome Powell "was concerned about reacting too quickly."                                                                                                 , "Now, I think they get it," Mnuchin told Kudlow. "I think over the next year you're going to see the Fed normalize rates and normalize the portfolio." He added, "The numbers overwhelmingly show we have real, ongoing inflation." </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/05/stock-market-futures-open-to-close-news.html </td>
   <td style="text-align:left;"> 2022-01-06 07:03:08 </td>
   <td style="text-align:left;"> Stock futures are slightly higher after Wednesday's sell-off </td>
   <td style="text-align:left;"> , Stock futures were slightly higher in overnight trading Wednesday after the major U.S. stock averages fell sharply in the first losing regular trading session of the year.                                                                                                                         , Futures on the Dow Jones Industrial Average added about 65 points, or 0.2%. S&amp;P 500 futures ticked up 0.1% and Nasdaq 100 futures rose 0.1%.                                                                                                                                                        , Minutes from the Federal Reserve's December meeting revealed the central bank discussed reducing its balance sheet in another move to aggressively dial back its pandemic-era easy monetary policy.                                                                                                 , The Fed's plan to reduce the number of Treasurys and mortgage-backed securities it holds comes as it is already tapering its bond purchases and is set to hike interest rates after the taper concludes.                                                                                            , "Almost all participants agreed that it would likely be appropriate to initiate balance sheet runoff at some point after the first increase in the target range for the federal funds rate," the minutes stated.                                                                                    , Stocks slid following the release of the minutes. The blue-chip Dow Jones Industrial Average closed 392.54 points, or 1.07%, lower after hitting an intraday record earlier in the session. The S&amp;P 500 fell 1.94%. The tech-heavy Nasdaq saw its biggest one-day loss since February, losing 3.34%., Cathie Wood begins 2022 where she left off last year: Buying the dip in her favorite stocks                                                                                                                                                                                                         , Morgan Stanley names its top chip stocks for 2022                                                                                                                                                                                                                                                   , Income investors are off to a good start in 2022 with dividend ETF hitting all-time high                                                                                                                                                                                                            , These stocks win when rates rip higher like they  are doing so far this year                                                                                                                                                                                                                        , "If you ride a wave of liquidity to the upside and that liquidity starts to go away, I don't think it's terribly surprising that you're going to see a reaction," said Kathy Jones, head of fixed income at Charles Schwab.                                                                         , "This was the year we were going to transition from extremely easy monetary policy and fiscal policy to less easy monetary and less expansive fiscal policy. That has to have some impact on risk assets that have risen because the discount rate was so low," Jones added.                        , All 11 S&amp;P 500 sectors fell in Wednesday's session.                                                                                                                                                                                                                                                 , Investors await quarterly earnings reports from Walgreens Boots Alliance and Bed Bath &amp; Beyond before the bell Thursday.                                                                                                                                                                            , On the data front, the weekly jobless claims report is slated for released Thursday morning.                                                                                                                                                                                                        , —CNBC's Jeff Cox contributed to this report.                                                                                                                                                                                                                                                        , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                              , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                              , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                    , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                    , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                  , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/05/technology/jan-6-anniversary-social-media.html </td>
   <td style="text-align:left;"> 2022-01-06 06:43:22 </td>
   <td style="text-align:left;"> Right-Wing Calls to Celebrate Jan. 6 Anniversary Draw a Muted Response - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Online chatter about holding rallies has grown, but sizable real-world gatherings on Thursday are unlikely to materialize.                                                                                                                                                                                                                                                                                                                                                                                                                                      , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , By Sheera Frenkel and Ryan Mac                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Last month, a onetime campaign aide to former President Donald J. Trump posted on Facebook, Twitter, Gab and other social media sites. For the first anniversary of the Jan. 6 riot at the U.S. Capitol, he wrote, candlelight vigils would be held in 20 cities on Thursday to honor those who stormed the building.                                                                                                                                                                                                                                           , “January 6th was America’s Tiananmen Square,” Matt Braynard, the former Trump campaign aide and founder of Look Ahead America, a right-wing organization, said in a post on Gab. “Join us in marking this lie with #J6vigils from coast to coast.”                                                                                                                                                                                                                                                                                                              , The responses were sparse. Seventy-eight people liked the message, and 21 people shared it.                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , The post was an example of what right-wing groups and supporters of Mr. Trump are discussing to commemorate the Jan. 6 anniversary: scattered, local and most likely small gatherings. According to a review by The New York Times of recent posts from right-wing groups on sites including Facebook, Twitter, Gab and Gettr, online chatter about celebrations and rallies for the anniversary has grown in recent weeks, but the posts have not attracted much buzz and appear unlikely to translate into sizable real-world efforts on Thursday.            , Many of the conversations online have instead centered on gatherings for specific groups in places such as Dallas and Phoenix. In Miami, a local chapter of the far-right Proud Boys said it planned to hold a protest on Thursday to honor those arrested after storming the Capitol, according to a post on the Telegram messaging app. In Beverly Hills, a group dedicated to protesting mask mandates said on Telegram that it planned a rally to rename Jan. 6 after Ashli Babbitt, who was killed by federal officers while storming the Capitol building., In the posts, there has been little talk of violence and guns. The groups have mostly focused on positioning the Jan. 6 rioters as heroes and martyrs and encouraged people to push local political leaders toward a far-right agenda. The language in the posts is also muted, calling on supporters to think of long-term goals such as stopping mask and vaccine mandates.                                                                                                                                                                                   , Efforts to organize an anniversary protest in Washington on Thursday have also appeared to gain little traction online, according to The Times’s review.                                                                                                                                                                                                                                                                                                                                                                                                        , “Stay out of Washington, it is nothing but a setup,” wrote an Ohio member of the Proud Boys on Telegram on Monday. “Federal agents are going to be there in disguise waiting to arrest anyone who shows up.”                                                                                                                                                                                                                                                                                                                                                    , Another member responded, “What is the point of D.C.? Better stay local, make a difference” in your hometown.                                                                                                                                                                                                                                                                                                                                                                                                                                                   , The lackluster and dispersed conversations underline how far-right groups have largely fractured across the internet since President Biden was inaugurated last January. While the groups were once united under the banner of Mr. Trump’s White House and had substantial presences on mainstream platforms like Facebook and Twitter, many have since been booted from the sites and are more active locally rather than nationally.                                                                                                                          , “There’s a broad shift happening right now, and we can see it with how all these different groups are discussing and promoting events around Jan. 6 online,” said Heidi Beirich, a founder of the nonprofit Global Project Against Hate and Extremism. “They are on different platforms, with different messages.”                                                                                                                                                                                                                                              , All of this is a far cry from a year ago, when right-wing groups and Mr. Trump’s supporters fomented the Stop the Steal movement — which falsely suggested that the presidential election had been stolen from Mr. Trump — on Facebook and other mainstream social media sites. Tens of thousands of supporters of Mr. Trump showed up in Washington last Jan. 6 and more than 700 were later arrested in connection with the riot.                                                                                                                             , The Proud Boys and Mr. Braynard did not respond to requests for comment. Telegram did not respond to a request for comment.                                                                                                                                                                                                                                                                                                                                                                                                                                     , Yet while right-wing activity on mainstream social media appears to now be more muted, it has not ceased.                                                                                                                                                                                                                                                                                                                                                                                                                                                       , On Tuesday, the Tech Transparency Project, an industry watchdog group funded by the philanthropic organizations of billionaires including Pierre Omidyar and George Soros, published a report showing that Facebook’s recommendation algorithms continued to push pages related to militia organizations and the Three Percenters, an anti-government movement. The activity was taking place even after Facebook cracked down in 2020 on groups related to QAnon, a wide-ranging conspiracy theory, as well as on U.S.-based militia pages.                    , Katie Paul, a director with the Tech Transparency Project, said she had created a Facebook account in July that exclusively followed militia group pages to track how the social network recommended content to certain users following the events of Jan. 6.                                                                                                                                                                                                                                                                                                   , One page that surfaced in her test account featured a banner image of a snake wrapped around a semiautomatic rifle superimposed on a Three Percenter logo. In other instances, she said, her account encountered Facebook ads that tried to recruit her for local militias.                                                                                                                                                                                                                                                                                     , The House investigation. A select committee is scrutinizing the causes of the Jan. 6 riot at the U.S. Capitol, which occurred as Congress met to formalize Joe Biden’s election victory amid various efforts to overturn the results. Here are some people being examined by the panel:                                                                                                                                                                                                                                                                         , Donald Trump. The former president’s movement and communications on Jan. 6 appear to be a focus of the inquiry. But Mr. Trump has attempted to shield his records, invoking executive privilege. The dispute is making its way through the courts.                                                                                                                                                                                                                                                                                                              , Mark Meadows. Mr. Trump’s chief of staff, who initially provided the panel with a trove of documents that showed the extent of his role in the efforts to overturn the election, is now refusing to cooperate. The House voted to recommend holding Mr. Meadows in criminal contempt of Congress.                                                                                                                                                                                                                                                               , Scott Perry and Jim Jordan. The Republican representatives of Pennsylvania and Ohio are among a group of G.O.P. congressmen who were deeply involved in efforts to overturn the election. Mr. Perry has refused to meet with the panel.                                                                                                                                                                                                                                                                                                                         , Phil Waldron. The retired Army colonel has been under scrutiny since a 38-page PowerPoint document he circulated on Capitol Hill was turned over to the panel by Mr. Meadows. The document contained extreme plans to overturn the election.                                                                                                                                                                                                                                                                                                                    , Fox News anchors. ​​Laura Ingraham, Sean Hannity and Brian Kilmeade texted Mr. Meadows during the Jan. 6 riot urging him to persuade Mr. Trump to make an effort to stop it. The texts were part of the material that Mr. Meadows had turned over to the panel.                                                                                                                                                                                                                                                                                                   , Steve Bannon. The former Trump aide has been charged with contempt of Congress for refusing to comply with a subpoena, claiming protection under executive privilege even though he was an outside adviser. His trial is scheduled for next summer.                                                                                                                                                                                                                                                                                                             , Michael Flynn. Mr. Trump’s former national security adviser attended an Oval Office meeting on Dec. 18 in which participants discussed seizing voting machines and invoking certain national security emergency powers. Mr. Flynn has filed a lawsuit to block the panel’s subpoenas.                                                                                                                                                                                                                                                                           , Jeffrey Clark. The little-known official repeatedly pushed his colleagues at the Justice Department to help Mr. Trump undo his loss. The panel has recommended that Mr. Clark be held in criminal contempt of Congress for refusing to cooperate.                                                                                                                                                                                                                                                                                                               , John Eastman. The lawyer has been the subject of intense scrutiny since writing a memo that laid out how Mr. Trump could stay in power. Mr. Eastman was present at a meeting of Trump allies at the Willard Hotel that has become a prime focus of the panel.                                                                                                                                                                                                                                                                                                   , “Are you ready to train and prepare for whatever may be headed our way in 2022?” read one December ad, which was seen by Facebook users fewer than 1,000 times according to the social network’s measurements. “6th Battalion of the 1st Missouri Volunteer Infantry is actively seeking new members in your area.”                                                                                                                                                                                                                                             , Since the report’s publication, Facebook has taken down some of the militia pages. The company, which has been renamed Meta, said it had “taken steps to address harmful content.”                                                                                                                                                                                                                                                                                                                                                                              , “We have strong policies that we continue to enforce, including a ban on hate organizations and removing content that praises or supports them,” said Kevin McAlister, a Meta spokesman.                                                                                                                                                                                                                                                                                                                                                                        , For the Jan. 6 anniversary, he added, the company was in contact with law enforcement authorities and was “continuing to actively monitor threats on our platform and will respond accordingly.”                                                                                                                                                                                                                                                                                                                                                                , Twitter also said it planned to monitor its service for calls to violence on Thursday and added that it had an internal group prepared to enforce its rules if violent content proliferates.                                                                                                                                                                                                                                                                                                                                                                    , The social media companies may face an easier time on Thursday than a year ago, given that conversations about the Jan. 6 anniversary were muted on Facebook, Telegram and other channels. In some of the posts reviewed by The Times, commenters said they could not attend anniversary rallies but wished others well.                                                                                                                                                                                                                                        , “Honor our brothers, honor our friends,” wrote an Ohio member of the Proud Boys in a Telegram group. “Keep up the fight in their name.”                                                                                                                                                                                                                                                                                                                                                                                                                         , Another member wrote, “I can’t keep track of what is happening where… can we get together a group calendar?”                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Kate Conger contributed reporting.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-59889628?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-06 06:39:12 </td>
   <td style="text-align:left;"> Cost of living: Government discusses fuel bill support </td>
   <td style="text-align:left;"> After a two hour meeting with senior energy industry leaders, the idea of targeted financial support for fuel bills - along the lines of the current Warm Homes Discount scheme - is emerging as a frontrunner to tackle a cost of living squeeze which could see households £1,200 a year worse off as a higher energy cap comes in at the same time as a rise in taxes on workers and employers.                                                                                                                                                                                                                , The current Warm Homes Discount scheme offers those in receipt of certain benefits the option to apply for a one off £140 payment.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , This could be increased and the number of people eligible could be expanded more broadly. Government sources confirmed this was "under discussion with other options" and the prime minister referred to the scheme twice in the last 48 hours.                                                                                                                                                                                                                                                                                                                                                                   , However, some industry sources say the coming increases in bills will affect so many households that narrow targeting may be insufficient.                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Although none of the other options are being ruled out, a blanket cut in the 5% VAT charged on energy bills - called for by Labour -  is considered too blunt as it would also benefit better off households.                                                                                                                                                                                                                                                                                                                                                                                                     , Suspending the additional levies on bills that fund green policies would be a tricky sell in some quarters after the UK hosted COP26, given these levies are designed to reduce dependence on volatile fossil fuels. This option is however gaining support among some Conservative backbench MPs.                                                                                                                                                                                                                                                                                                                , Moving these green levies from energy bills to general taxation is being pushed by some industry voices as it would mean higher earners pay more than those who spend a larger proportion of their income on essentials like heating. They also argue it would lower the measure of inflation, saving the government money on inflation linked borrowing costs. This is not thought to be popular with the Treasury who are reluctant to increase the general tax burden with a £12bn rise in National Insurance contributions starting in April - the same time as the new (higher) energy cap comes into force. , That rise in National Insurance itself is being questioned by MPs, including Jacob Rees-Mogg. However, reversing it would be a dramatic move from a Chancellor keen to keep control over public spending despite his personal misgivings about raising taxes.                                                                                                                                                                                                                                                                                                                                                     , Another option - favoured by the industry - would be to subsidise the energy companies themselves by establishing a fund or facility which would allow them to draw down government cash when wholesale prices were very high and then pay it back when prices dipped again. This would smooth out price spikes and would have the added benefit, energy providers argue, of preventing further providers going bust.                                                                                                                                                                                             , Even those that have survived so far have warned that their ability to insure themselves by buying the gas they need in advance is beginning to unravel as higher prices outlast their advance orders and exhaust their day to day cash.                                                                                                                                                                                                                                                                                                                                                                          , No concrete proposals have yet reached the desk of the chancellor. Industry sources have told the BBC they are hoping a decision will be made next week. Yet, government officials pointed to a date of 7 February, when the new energy cap level is announced, as a guide to their absolute deadline for announcing new support.                                                                                                                                                                                                                                                                                 , Meet the new candidates looking to impress Lord Sugar in The Apprentice                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , How did Chinese woman Zheng Yi Sao and her army terrorise the seas?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/media/kudlow-we-are-in-the-great-resignation </td>
   <td style="text-align:left;"> 2022-01-06 06:36:22 </td>
   <td style="text-align:left;"> Kudlow: We are in the 'great resignation' </td>
   <td style="text-align:left;"> ‘Kudlow’ discusses the number of Americans quitting their jobs hits its highest record.                                                                                                                                                                                                                                                                                                                , So just a couple of quick points: First, there seems to be a big misunderstanding in the media about the record number of Americans leaving their jobs and the so-called "quit rate." I see the term "great resignation" being bandied about in negative ways, sort of like "nobody wants to work."                                                                                                    , And while it is true that a number of Biden proposals to provide welfare-related assistance without any workfare requirements, and I always felt that overly generous and overly lengthy unemployment benefits created incentives not to work, the quit rate is quite a different matter.                                                                                                              , 2022 IS THE YEAR OF THE RAISE AND WORKERS GETTING THE ‘UPPER HAND’, PERSONAL FINANCE EXPERT SAYS                                                                                                                                                                                                                                                                                                       , It's actually a sign of labor market strength, and it's actually a sign of worker power. Why? Because labor markets are tight, and people know that they can leave today's job and get a better paying job tomorrow in another place.                                                                                                                                                                  , 4.5 million people quit their job in November, according to the JOLTS report, and that comes to a 3% quit rate, which measures the number of quits as a percentage of payrolls.                                                                                                                                                                                                                        , ‘How America Works’ narrator Mike Rowe warns a workforce imbalance will impact every American.                                                                                                                                                                                                                                                                                                         , Several decades ago, Alan Greenspan popularized the quit rate as a key labor market indicator. When quits are falling people are afraid to leave their job, and it's usually a sign of high unemployment. But when quits are rising, people are much bolder because they know they can get better-paying work elsewhere, and it's a sign of falling unemployment. This is exactly what's happening now., GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                            , Former fed chair and current treasury secretary Janet Yellen also used the quit rate as a labor market indicator.                                                                                                                                                                                                                                                                                      , So all I’m saying is that quits are a healthy sign for workforce opportunities as long as government stays out of the way.                                                                                                                                                                                                                                                                             , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                , Save America. Kill the bill.                                                                                                                                                                                                                                                                                                                                                                           , This article is adapted from Larry Kudlow's opening commentary on Jan. 5, 2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/01/05/asia/north-korea-missile/index.html </td>
   <td style="text-align:left;"> 2022-01-06 06:36:21 </td>
   <td style="text-align:left;"> North Korea says it test-fired hypersonic missile Wednesday - state media - CNN </td>
   <td style="text-align:left;"> (CNN)North Korea said it successfully test-fired a hypersonic missile on Wednesday, the state-run news agency KCNA reported Thursday.                                                                                                                                                                                                                , According to the report, North Korean leader Kim Jong Un did not attend the launch.                                                                                                                                                                                                                                                                   , "The successive successful test launches in the hypersonic missile sector have a strategic significance of accelerating the task of modernizing the national strategic force suggested by the 8th Party Congress and completing the most important task among the top five tasks in the strategic weapons sector of the five-year plan," KCNA said.   , The missile was separated after launch, maneuvered 120 kilometers (74.5 miles) from the initial launch, and hit the target set at 700 kilometers (435 miles) without an error, KCNA reported.                                                                                                                                                         , The Japan Coast Guard said after reports of the launch Wednesday that the projectile fell into the sea off the east coast of the Korean Peninsula.                                                                                                                                                                                                    , Shortly after the launch Wednesday, South Korea's National Security Council expressed concerns over North Korea's launch of a missile, which it presumed to be a ballistic missile, and called for resumption of dialogue with North Korea to ease tension in inter-Korean relations, according to the Blue House, South Korea's presidential office. , South Korea's Unification Ministry urged North Korea to respond to its efforts to reach peace and cooperation through dialogue.                                                                                                                                                                                                                       , Last September, North Korea said it had tested a new hypersonic missile, Hawasong-8, from Toyang-ri, Ryongrim County of Jagang province.                                                                                                                                                                                                              , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-59876063?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-06 06:28:12 </td>
   <td style="text-align:left;"> Covid: Pre-departure travel tests to be scrapped </td>
   <td style="text-align:left;"> The rules on testing are to be eased for people travelling to England, the government has announced, following calls from the travel industry.                                                                                                                                                                                              , From 04:00 GMT on Friday, fully vaccinated travellers coming to England will no longer have to take a test before they travel.                                                                                                                                                                                                              , And from Sunday, rather than taking a PCR test on day two of arrival, they can take a cheaper lateral flow.                                                                                                                                                                                                                                 , The rules for self-isolating on arrival will also change.                                                                                                                                                                                                                                                                                   , The shake-up was confirmed by Boris Johnson earlier, following calls from travel firms who said the measures were not effective now that Omicron was spreading widely.                                                                                                                                                                      , Under the current rules in force until Friday, all fully-vaccinated travellers over the age of 12 must show proof of a negative test lateral flow or PCR test taken in the two days before coming to the UK. Fully vaccinated people must also pay for a PCR test within two days of arrival and self-isolate while waiting for the result. , People who aren't fully vaccinated must currently take PCR tests on both day two and day eight after arriving, and self-isolate for 10 days.                                                                                                                                                                                                , But under the new rules:                                                                                                                                                                                                                                                                                                                    , Prime Minister Boris Johnson said the pre-departure test "discourages many from travelling for fear of being trapped overseas and incurring significant extra expense".                                                                                                                                                                     , The announcement comes after airlines said passenger testing was making no real impact, with data last week suggesting one in 25 people in England had the virus.                                                                                                                                                                           , They also said compulsory testing had held back the sector's recovery.                                                                                                                                                                                                                                                                      , Mr Johnson met his cabinet earlier and alongside changes to travel tests, the government has said it will ease Covid testing rules for people without symptoms, who will no longer need to confirm a positive lateral flow test with a PCR.                                                                                                 , On Tuesday, Mr Johnson said he hoped the country could "ride out" the current wave, although he acknowledged parts of the NHS would feel temporarily overwhelmed.                                                                                                                                                                           , That rule change will come into force on 11 January and apply to England only for now.                                                                                                                                                                                                                                                      , Following the announcement for England, Health Minister for the Welsh government Eluned Morgan said: "I have today reluctantly agreed to remove the requirements for fully vaccinated travellers and under 18s to take a pre departure test (PDT) and a day 2 PCR test when arriving in the UK."                                            , Currently, all travellers to the UK aged 12 and over have to show proof of a negative test, which can be a PCR or a lateral flow test, and must be taken up to two days before departure for the UK.                                                                                                                                        , They then have to take another test - which this time must be a PCR test - within the first two days after their arrival in the UK.                                                                                                                                                                                                         , But at the time that rule was brought in a month ago, the number of new cases reported in the UK each day was running between 40,000 and 50,000 - and was only rising relatively slowly because it was almost entirely made up of the Delta variant of Covid.                                                                               , But UK cases have now risen sharply and Omicron is the dominant variant - so airlines can argue that there is no longer any hope of relying on testing to "keep out Omicron".                                                                                                                                                               , Read more.                                                                                                                                                                                                                                                                                                                                  , John Wyndham, who is currently planning a third trip to the US for February, said that scrapping pre-departure tests will make him feel unsafe on flights.                                                                                                                                                                                  , "I'm frustrated because pre-departure was the most important as an effective control and also the cheapest test," he told the BBC.                                                                                                                                                                                                          , Mr Wyndham runs a start-up company that is organising marching bands across the world to participate in London Band Week. He went to the US in December along with three colleagues, who paid £212 each for PCR testing.                                                                                                                    , However, he said that the eliminating pre-departure testing will only save him around £30 per person and wasn't worth the added worry about new variants.                                                                                                                                                                                   , "It's bonkers that we could now sit on the plane with someone who has it," he said, adding that it would "worsen what has already been the most stressful travelling of my life".                                                                                                                                                           , However, holidaymaker David Hughes welcomed the scrapping of PCR tests before returning to the UK. Currently on holiday in Dubai, the rule change will save his family of 4 around £400 and another removing the Day 2 PCR will also save the family another £400.                                                                          , "Having returned from a country where there were strict entry requirements and we were tested on arrival I would be very confident that we'll be returning to the UK Covid free," he told the BBC.                                                                                                                                          , Cancellation fees and no longer having to test before returning would mean significantly less hassle and stress, Mr Hughes added.                                                                                                                                                                                                           , In response, Mark Tanzer, Chief Executive of ABTA - The Travel Association, said the two announcements were "potentially very positive" for the travel sector, but that damage had "already been done".                                                                                                                                     , "We now hope to see confidence return as we enter what is usually the peak booking season for summer holidays," he added.                                                                                                                                                                                                                   , Steve Heapy, boss of the airline Jet2 and tour operator Jet2 Holidays, also said the timing of the announcement will make a "huge difference". Numbers of customers on their website, he said, were already increasing "exponentially" after the rule change.                                                                               , Shai Weiss, chief executive of Virgin Atlantic, agreed that the announcement meant customer demand would be boosted in a "critical booking window" for the industry.                                                                                                                                                                        , EasyJet chief executive Johan Lundgren also welcomed the news, saying it would make travel "much simpler and easier", as customers could now book and travel with "confidence".                                                                                                                                                             , The trade body Airlines UK has argued that continuing the current measures would be financially disastrous for the industry.                                                                                                                                                                                                                , Ahead of the test changes, Manchester Airports Group (MAG) sent the government research it commissioned, which it claimed shows that pre-departure testing has had little or no impact on the spread of Omicron.                                                                                                                            , It said that passenger numbers at MAG's airports fell by more than 30% after Omicron measures were introduced.                                                                                                                                                                                                                              , Tim Hawkins, chief of staff at MAG, told the BBC's Today programme the research showed there was a "basis for taking out all tests" related to international travel, due to the high number of Covid cases in the UK.                                                                                                                       , "We are beyond the point where international travel restrictions can play a role in managing that peak and if there is no benefit to it then we shouldn't be doing it and we should take those measures out," he added.                                                                                                                     , Separately, European airline and tour operator stocks rose on Tuesday amid a rise in investor confidence in the sector.                                                                                                                                                                                                                     , Hargreaves Lansdown analyst Susannah Streeter told Reuters: "With so many people in the short-term being forced to isolate at home, it's likely many people will be spending the next few weeks browsing travel blogs for inspiration, given there is so much desperation for a holiday."                                                   , A recent report by aviation analytics firm Cirium found that the Covid pandemic triggered a 71% drop in international flights in and out of the UK in 2021.                                                                                                                                                                                 , Meet the new candidates looking to impress Lord Sugar in The Apprentice                                                                                                                                                                                                                                                                     , How did Chinese woman Zheng Yi Sao and her army terrorise the seas?                                                                                                                                                                                                                                                                         , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/composite-pmi </td>
   <td style="text-align:left;"> 2022-01-06 06:08:47 </td>
   <td style="text-align:left;"> Australia Markit Composite PMI Confirmed at 54.9 </td>
   <td style="text-align:left;"> The IHS Markit Australia Composite PMI was unrevised at 54.9 in December of 2021, pointing to a slower rate of private sector output growth, though high by historical standards. While both manufacturing and service sectors output growth eased, demand for Australian services improved to push the composite New Orders Index higher. Foreign demand for Australian manufactured goods however improved while services exports stayed subdued amid border restrictions and COVID-19 Omicron variant fears. Expansion of workforce numbers continued while instances of labour constraints remained. On prices, input costs across both manufacturing and service sectors rose at record rates. Manufacturers also passed on these costs to their clients at an unprecedented rate. Overall sentiment remained positive across both the manufacturing and service sectors, though the level of optimism eased across both sectors with concerns that growth may slow due to COVID-19 impacts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/uk-politics-59886030?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-06 06:05:21 </td>
   <td style="text-align:left;"> PMQs: Labour's Angela Rayner steps up call for 5% energy bill VAT cut </td>
   <td style="text-align:left;"> This video can not be played                                                                                                                                                                                                                                                                                    , Labour has stepped up its call for the 5% VAT rate on energy bills to be scrapped, demanding "serious solutions" for the rising cost of living.                                                                                                                                                                 , Speaking at Prime Minister's Questions, the party's deputy leader Angela Rayner said working families were "picking up the tab" for Boris Johnson's "incompetence" over the issue.                                                                                                                              , But the PM insisted the government was providing a number of schemes to help.                                                                                                                                                                                                                                   , A spike in wholesale gas prices has led to soaring energy bills in the UK.                                                                                                                                                                                                                                      , A total of 27 energy companies have also gone bust as the energy price cap - limiting how much consumers can be charged - saw some businesses forced to sell energy for less than they bought it for.                                                                                                           , But there are fears an expected rise in the cap, due in April, could see households hit with even higher bills.                                                                                                                                                                                                 , There is growing unrest on the Conservative benches about the rising cost of living, with a group of 20 Conservative MPs and peers - including five ex-ministers - writing to Mr Johnson last week to urge him to cut VAT on energy bills.                                                                      , They also called for him to go further by suspending environmental levies, which fund renewable energy schemes.                                                                                                                                                                                                 , The Financial Times reported on Wednesday that Leader of the House Jacob Rees-Mogg also spoke out during a cabinet meeting about the incoming tax rise to cover NHS and social care, calling instead for savings to be made in government spending.                                                             , Meanwhile, the Liberal Democrats reiterated their own plan to support people with rising costs, calling for a so-called "Robin Hood" tax on oil and gas firm profits.                                                                                                                                           , The party's leader, Sir Ed Davey, said the one-off levy would raise around £5bn from companies making record profits from the wholesale energy price rise, which could be passed on to those in need.                                                                                                           , Labour has been calling for the government to slash the 5% VAT rate on energy bills to zero since October, with shadow chancellor Rachel Reeves calling it a "simple" and "immediate" measure to help people deal with costs over the winter.                                                                   , And writing in the Sun back in 2016, Mr Johnson himself advocated scrapping VAT on energy bills, saying it would be a benefit of Brexit.                                                                                                                                                                        , Backers of the plan said VAT receipts had come in more than £3bn higher than forecast because of rising prices, giving the government extra funds to cover the cost.                                                                                                                                            , But a Treasury source has told the BBC that rising bills overall mean consumers are spending less elsewhere on products with higher VAT, so the overall income to the government has remained flat.                                                                                                             , Standing in for Labour leader Sir Keir Starmer - who has tested positive for Covid - at PMQs, Ms Rayner said "working people across the country are facing rising bills and ballooning prices", due to a mixture of inflation, rising energy costs and an incoming tax rise to pay for the NHS and social care. , She added: "The prime minister has made political choices that have led us into this place."                                                                                                                                                                                                                    , The deputy leader claimed the government had "failed to invest in long term energy security" and "let the energy market run out of control", adding: "Can't the prime minister see what is happening?                                                                                                           , "Yet again working families are picking up tab for his incompetence."                                                                                                                                                                                                                                           , And having quoted his article in the Sun promising the VAT cut, Ms Rayner said "any decent government would find a way to help British families" and asking him to "finally stand up to his chancellor" to secure the move.                                                                                     , But Mr Johnson said a number of government initiatives - including the warm homes discount, winter fuel payments and cold weather payments - were supporting people, especially those on low incomes.                                                                                                           , He also accused Labour of "bare-faced cheek" for calling for the VAT cut, as the party campaigned to stay in the EU - when it would not have been an option.                                                                                                                                                    , "Everybody knows full well it would be absolutely impossible if they were to do what Labour would do and go back into the EU [and] remain aligned with the EU single market," said the PM.                                                                                                                      , "That is the objective of the Labour Party. They can't be trusted on Brexit and they can't be trusted with the economy."                                                                                                                                                                                        , At Prime Minister's Questions, Boris Johnson said - twice - that the Warm Home Discount Scheme was "worth £140 a week".                                                                                                                                                                                         , That's wrong - it's worth £140 for the whole of the winter.                                                                                                                                                                                                                                                     , It's a one-off discount on the electricity bills between October and March of people on low incomes.                                                                                                                                                                                                            , Labour's deputy leader Angela Rayner said: "In October, the prime minister said that fears about inflation were unfounded."                                                                                                                                                                                     , Mr Johnson replied: "Of course, I said no such thing".                                                                                                                                                                                                                                                          , But in October, he told Sky News: "People have been worrying about inflation for a very long time… those fears have been unfounded."                                                                                                                                                                            , And at PMQs, he said that "everybody on the living wage has seen another £1,000 in their income".                                                                                                                                                                                                               , The living wage is going up in April from £8.91 an hour to £9.50, which will be £1,000 for somebody working full-time.                                                                                                                                                                                          , Clearly, people working fewer hours will receive less. Also, these are figures before taxes and benefits are taken into account.                                                                                                                                                                                , Income tax, National Insurance and the loss of Universal Credit as earnings increase all mean that even a full-time worker is likely to end up with significantly less than £1,000.                                                                                                                             , The SNP's leader in Westminster, Ian Blackford, also attacked the prime minister over the rising cost of living, saying: "We've had the year of Tory sleaze, but now we've got the year of Tory squeeze for family budgets".                                                                                    , He quoted research from the Resolution Foundation, saying on average families will be £1,200 worse off from April "as a result of Tory cuts, tax hikes and soaring energy bills".                                                                                                                               , Mr Blackford asked the PM to "commit to an emergency financial package" to help the worst off.                                                                                                                                                                                                                  , But Mr Johnson said the government was "helping families up and down the country", pointing to changes to the Universal Credit taper and increases to the living wage.                                                                                                                                          , He added: "You've now got more people in work than there were before the pandemic began.                                                                                                                                                                                                                        , "That is because of the balanced and proportionate approach that we've been taking."                                                                                                                                                                                                                            , Abolishing VAT of 5% on energy bills would be quick and easy, but is considered a blunt instrument, as it would provide support to well-off customers who don't need it.                                                                                                                                        , And for those that do need it, 5% of a possible £700 price rise is pretty small.                                                                                                                                                                                                                                , The government could temporarily suspend the additional levies on bills that fund green policies.                                                                                                                                                                                                               , But that would be a tricky sell in some quarters, after the UK hosted a major global climate summit, and these levies are designed to reduce dependence on volatile fossil fuels.                                                                                                                               , One other option is to extend and expand the Warm Homes Discount. Currently, customers in receipt of certain benefits can apply for a one-off payment of £140.                                                                                                                                                  , And another option - suggested by the industry - would be to subsidise the energy companies themselves, by establishing a fund or facility which would allow them to draw down government cash when wholesale prices were very high and then pay it back when prices dipped again.                              , Read more from Simon Jack here.                                                                                                                                                                                                                                                                                 , Meet the new candidates looking to impress Lord Sugar in The Apprentice                                                                                                                                                                                                                                         , How did Chinese woman Zheng Yi Sao and her army terrorise the seas?                                                                                                                                                                                                                                             , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/services-sentiment </td>
   <td style="text-align:left;"> 2022-01-06 06:04:18 </td>
   <td style="text-align:left;"> Australia Services Sector Continues to Expand </td>
   <td style="text-align:left;"> The IHS Markit Australia Services PMI was confirmed at 55.1 in December of 2021, pointing to a continued expansion for the services sector. The easing of COVID-19 restrictions enabled overall new orders to rise at a stronger rate in December, driving higher employment levels and contributing to increased backlogged work. Price pressures further accumulated with record input price inflation seen while business confidence slipped in the final month of 2021. Overall sentiment in the service sector remained positive in December, but business confidence fell markedly to below the series average. While survey respondents were generally hopefully that the economic recovery will continue, some were concerned that growth will slow into the new year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-01-06 05:48:02 </td>
   <td style="text-align:left;"> Brazilian Shares Fall for 3rd Day </td>
   <td style="text-align:left;"> The Ibovespa stock index plunged 2.4% to 101006, the lowest in a month and extending losses for a 3rd consecutive session, in line with its American peers, after the FOMC minutes showed the Fed will likely raise rates faster than initially expected. At the same time, concerns over Brazil's fiscal policy, economic growth and inflation continue to weigh on investors' mood. On the data front, a PMI survey showed Brazil's private sector growth stood at a 6-month low in December. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/hasbro-names-chris-cocks-ceo/story.aspx?guid={20C05575-04D4-B545-783C-E069F9B1A918}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-06 05:25:00 </td>
   <td style="text-align:left;"> Hasbro names Chris Cocks as CEO - MarketWatch </td>
   <td style="text-align:left;"> Hasbro Inc. 
        HAS,
        -0.58%
       said late Wednesday its board appointed Chris Cocks as chief executive and named him as a board member effective Feb. 25. Cocks currently serves as president and chief operating officer Hasbro’s Wizards of the Coast and Digital Gaming division, and replaces Brian Goldner, who died in October. Cocks has served in his current position in charge of the division that puts out games such as “Magic: The Gathering” and “Dungeons &amp; Dragons,” since leaving Microsoft Corp. 
        MSFT,
        -3.84%
       Hasbro also appointed Eric Nyman as the company’s president and chief operating officer effective Feb. 25. Hasbro shares slipped 0.3% after hours, following a 0.6% decline to close the regular session at $103.32. Shares are up 11% over the past 12 months, compared with a 26% gain in the S&amp;P 500 index 
        SPX,
        -1.94%.
       , Amazon, Visa, Nordstrom, and AT&amp;T are among the stocks pegged to outperform the S&amp;P 500 next year.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Wallace Witkowski came to MarketWatch from the Associated Press in New York, where he was a business reporter specializing in pharmaceutical companies. He previously reported for trade publications in covering the drug and medical-device industries back to 1998. Based in San Francisco, his focus is on U.S. equities. Follow Wally on Twitter at: @wmwitkowski. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-01-06 05:23:45 </td>
   <td style="text-align:left;"> Canadian Shares Track Wall Street Lower </td>
   <td style="text-align:left;"> The S&amp;P/TSX reversed course to finish 0.9% lower at 21040 on Wednesday, tracking a big fall on Wall Street and soaring bond yields after the latest FOMC statement increased the odds the Fed will faster tighten monetary policy. The IT sector was the biggest laggard (-3.7%), followed by health care (-3.9%) and industrials (-1.5%). On the other hand, the energy sector ended in the green (0.5%) as oil prices increased. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-01-06 05:11:27 </td>
   <td style="text-align:left;"> US Stocks Fall Sharply on Hawkish Fed </td>
   <td style="text-align:left;"> US stocks ended sharply lower on Wednesday after the FOMC minutes showed the Fed will likely raise rates sooner than earlier anticipated and could reduce its balance sheet shortly after it raises rates. The Dow Jones sank 393 points or 1.1% to 36407, after closing at a record level the day before; the S&amp;P 500 lost 1.9% to 4701; and the Nasdaq finished 3.3% lower at 15100. Tech shares resumed the slide, as soaring Treasury yields raised concerns over tech valuation. The real estate sector also tumbled while shares of Merck &amp; Co (2.4%), Intel (1.4%) and Honeywell (1%) booked gains. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/2-year-note-yield </td>
   <td style="text-align:left;"> 2022-01-06 05:06:58 </td>
   <td style="text-align:left;"> Australia 2Y Bond Yield Hits 7-week High </td>
   <td style="text-align:left;"> Australia 2 Year Government Bond Yeld increased to a 7-week high of 0.47% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/dow-sp-500-nasdaq-close/story.aspx?guid={C43884BD-0F79-4794-A062-8183E2DDD353}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-06 05:03:53 </td>
   <td style="text-align:left;"> Dow, S&amp;P 500, Nasdaq close sharply lower as stocks slide after Fed minutes  - MarketWatch </td>
   <td style="text-align:left;"> Major U.S. stock benchmarks ended sharply lower Wednesday, with the tech-heavy Nasdaq Composite index suffering the steepest decline, after the Federal Reserve released minutes of its December meeting that showed officials eyeing potentially faster and earlier rate hikes amid high inflation. The Nasdaq 
        COMP,
        -3.34%
       dropped about 3.3%, the S&amp;P 500 
        SPX,
        -1.94%
       fell about 1.9% and the Dow Jones Industrial Average 
        DJIA,
        -1.07%
       lost about 1.1%, according to preliminary data from FactSet. Fed officials also discussed shrinking the central bank’s balance sheet, another form of tightening monetary policy. Losses for the interest-rate-sensitive Nasdaq Composite came as the yield on the 10-year Treasury note 
        TMUBMUSD10Y,
        1.690%
       climbed to about 1.7% Wednesday, the highest since April based on 3 p.m. levels, according to Dow Jones Market Data., Stocks swoon, ending at session lows, after the release of the Fed's December meeting minutes show discussion around trimming the central bank's balance sheet.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2022-01-06 04:43:32 </td>
   <td style="text-align:left;"> Natural Gas Prices Rise </td>
   <td style="text-align:left;"> US natural gas futures jumped nearly 4% to $3.8 per million British thermal units on Wednesday, amid forecasts of colder weather this month and as low temperatures have caused natural gas wells to freeze in Texas, New Mexico, and North Dakota. Also, demand from Europe and Asia remains historically high and US producers have been boosting LNG exports to Europe. The United States will be the biggest exporter of LNG in the world through 2022 as a whole, according to forecasts from ICIS and the US Energy Information Agency, as the country's production and storage remains elevated. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-01-06 04:25:58 </td>
   <td style="text-align:left;"> Oil Pares Some Early Gains amid OPEC, EIA </td>
   <td style="text-align:left;"> WTI crude futures settled around $77.85 per barrel on Wednesday after rising as much as 2% to a session-high of $78.53, as investors digest the latest OPEC+ decision to raise oil output by 400,000 barrels per day in February, although doubts persist over whether the group will be able to actually increase production as members including Nigeria and Libya struggle to raise it. Also, the EIA report showed US crude oil inventories fell for the sixth consecutive week but gasoline stocks rose the most since April 2020, raising concerns of declining demand in the world’s biggest consumer amid a surge in Covid cases caused by the fast-spreading omicron variant. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/meta-platforms-stops-vrar-software/story.aspx?guid={6F333B6F-F218-4498-BB03-AC77DA0B8D97}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-06 03:59:44 </td>
   <td style="text-align:left;"> Meta Platforms stops VR/AR software operating system project: report - MarketWatch </td>
   <td style="text-align:left;"> Facebook parent Meta Platforms Inc. 
        FB,
        -3.67%
       has ceased development of a new VR/AR software operating system that employed more than 300 after four years, The Information reported Wednesday. The move could greatly impact Meta's ability to pivot to becoming a major metaverse player. Meta quickly issued a statement via Gabriel Aul, its vice president of Reality Labs Engineering. 
"There are several technical directions we're pursuing in our efforts to build @RealityLabs operating systems, we're still working on a highly specialized OS for our devices - we remain very much invested in this work and continue to dedicate the resources necessary to build this," Aul said in a tweet Wednesday.                                                                                                                                                                                                                                                                                                                                                                      , Shares of Ford Motor Co. undefined dropped 2.0% in morning trading Thursday, after the auto maker reported a 17.1% year-over-year decline in total U.S. auto sales in December, to 173,740 vehicles. Truck sales dropped 15.5% to 91,699 and SUV sales fell 11.1% to 77,377 vehicles, while sales of electrified vehicles surged 121.1% to 12,284 EVs. For 2021, Ford said its EV sales grew 36% faster than the segment overall for the year, and its total EV sales was second only to Tesla Inc. undefined. Within trucks, Ford said December F-Series sales fell 15.7% to 62,496, Transit sales slumped 45.3% to 8,521 and Ranger sales fell 29.2% to 6,992. Within SUVs, Explorer sales dropped 20.6% to 20,715, Edge sales slid 8.7% to 11,456 and Escape sales shed 38.4% to 10,704. For cars, Mustang sales declined 7.5% to 4,564. Ford's stock has run up 66.8% over the past three months, as it closed Tuesday at the highest price since Aug. 10, 2001, while shares of rival General Motors Co. undefined have climbed 19.8%, Tesla's stock has hiked up 45.4% and the S&amp;P 500 undefined has advanced 10.0%., Jon Swartz is a senior reporter for MarketWatch in San Francisco, covering many of the biggest players in tech, including Netflix, Facebook and Google. Jon has covered technology for more than 20 years, and previously worked for Barron's and USA Today. Follow him on Twitter @jswartz. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/fuelcell-energy-stock-leads-fuel/story.aspx?guid={CF5C7AEE-7B42-480A-BEA9-88524B5474BF}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-06 03:53:50 </td>
   <td style="text-align:left;"> FuelCell Energy stock leads fuel cell peers in losses, after tepid endorsement from KeyBanc analyst - MarketWatch </td>
   <td style="text-align:left;"> Shares of FuelCell Energy Inc. 
        FCEL,
        -9.52%
       sank 8.8% in afternoon trading Wednesday, to lead its fuel cell peers in losses, after a relatively tepid endorsement of the fuel cell company by KeyBanc Capital analyst Leo Mariani, who cited smaller revenue and less visibility on near-term growth compared with its peers. And while Mariani is positive on fuel cell industry for the long term, he believes it could take years before they become competitive relative to traditional energy sources. Mariani started coverage of FuelCell at sector weight, while initiating Plug Power Inc. 
        PLUG,
        -6.68%
       at overweight and upgrading Bloom Energy Crop. 
        BE,
        -6.22%
       to overweight from sector weight. He also initiated Ballard Power Systems Inc. 
        BLDP,
        -4.46%
       at sector weight. "Fuel cells can't compete today on economics with power generated by fossil fuels, but they will offer much cleaner and more reliable power vs. traditional grid sources," Mariani wrote in a note to clients. "We think fuel cells will become much more competitive later this decade as technological progress and much greater manufacturing scale drives unit costs lower, much like the world saw with progress on [electric vehicles] and solar and wind energy." Shares of Plug Power shed 5.0%, Bloom Energy dropped 6.4% and Ballard Power gave up 3.5%, while the S&amp;P 500 
        SPX,
        -1.94%
       slid 1.1%., Advanced Micro Devices Inc. shares fell Tuesday after the chip maker announced new desktop and laptop chips at CES 2022.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/energy/billionaire-ceo-calls-for-white-house-to-stop-the-war-on-north-america </td>
   <td style="text-align:left;"> 2022-01-06 03:44:14 </td>
   <td style="text-align:left;"> Billionaire Gristedes CEO calls for White House to 'stop the war on North America' </td>
   <td style="text-align:left;"> John Catsimatidis, the billionaire owner and CEO of New York City supermarket chain Gristedes, warns food prices will continue to rise as manufacturers have been raising prices.                                                                                                                                                      , John Catsimatidis, the billionaire owner and CEO of New York City supermarket chain Gristedes, called for the White House to "stop the war on North America" amid rising inflation on food and gas.                                                                                                                                    , Catsimatidis, who is also the CEO of United Refining, made the comment on President Biden’s energy policies on "Cavuto: Coast to Coast" Wednesday.                                                                                                                                                                                     , Biden revoked the permit for the Keystone XL oil pipeline project on his first day in office last year in a series of orders aimed at combating climate change, ending a project that was expected to employ more than 11,000 Americans this year.                                                                                     , The president also temporarily suspended the issuance of oil and gas permits on federal lands and waters.                                                                                                                                                                                                                              , The consumer price index rose 6.8% in November from a year ago, according to a Labor Department report, marking the fastest increase since June 1982, when inflation hit 7.1%. The CPI – which measures a bevy of goods ranging from gasoline and health care to groceries and rent – jumped 0.8% in the one-month period from October., Price increases were widespread, with energy prices jumping 3.5% in November, up 33.3% year over a year. Gasoline is a stunning 58.1% higher than it was a year ago.                                                                                                                                                                   , On Wednesday, oil inched higher by 1% nearing $78 per barrel. The national average for a gallon of gas was $3.29, slightly higher from the day before and $1.03 higher than the same time last year, according to AAA.                                                                                                                 , Dan Eberhart, the CEO of drilling services company Canary, explains why he believes the rising price of oil and gas is something President Biden 'is going to have to worry about.'                                                                                                                                                    , Catsimatidis called on the White House to allow Canada and Alaska "to turn their spigots on," arguing that if that happens "crude oil will go down $20 a barrel, and we can solve most of our inflation problems."                                                                                                                     , CONSUMERS SEEING SOME FOOD PRICES GO ‘THROUGH THE ROOF,' GROCERY STORE CEO SAYS                                                                                                                                                                                                                                                        , He argued that if that doesn’t happen, inflation will continue to rise through the summer.                                                                                                                                                                                                                                             , Catsimatidis predicted oil could hit $90 a barrel in 2022 and warned if the Biden administration’s energy policies don’t change, the price could reach $100 a barrel by the summer.                                                                                                                                                    , The billionaire also weighed in on rising food prices, arguing that prices will continue to rise as manufacturers have been raising prices to account for higher costs.                                                                                                                                                                , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                            , Gristedes and D'agostino Foods President and United Refining Company CEO John Catsimatidis weighs in on the increase of food prices in the U.S.                                                                                                                                                                                        , "We saw our Christmas pricing going up at least 10%," Catsimatidis told host Neil Cavuto.                                                                                                                                                                                                                                              , "We are seeing a lot of manufacturers raising prices for the month of February and March," he noted, warning that "the rise continues."                                                                                                                                                                                                , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                , FOX Business’ Megan Henney contributed to this report.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/oil-prices-settle-higher-us/story.aspx?guid={479224E7-7F5F-4475-BE26-497088BB2CF8}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-06 03:38:22 </td>
   <td style="text-align:left;"> Oil prices settle higher as U.S. crude supplies edge lower, but gasoline stockpiles climb - MarketWatch </td>
   <td style="text-align:left;"> Oil prices finished with a gain on Wednesday after the Energy Information Administration reported a sixth straight weekly decline in U.S. crude inventories. The EIA report, however, highlighted a sharp decline in oil exports and refined product demand in the U.S., "as the normal seasonal decline in demand during the holiday week was exacerbated by the surge in U.S. COVID cases," said Troy Vincent, senior market analyst at DTN. Still, oil largely shrugged off the reported sharp drop in demand and larger-than-expected builds in petroleum product supplies for the week ended Dec. 31 amid a "growing market consensus that the latest wave of COVID and accompanying decline in demand will be short-lived" and growing concerns over OPEC's ability to delivery on their production goals, he said. February West Texas Intermediate crude 
        CLG22,
        -0.92%
       rose 86 cents, or 1.1%, to settle at $77.85 a barrel on the New York Mercantile Exchange.                                                                                                                       , Shares of Ford Motor Co. undefined dropped 2.0% in morning trading Thursday, after the auto maker reported a 17.1% year-over-year decline in total U.S. auto sales in December, to 173,740 vehicles. Truck sales dropped 15.5% to 91,699 and SUV sales fell 11.1% to 77,377 vehicles, while sales of electrified vehicles surged 121.1% to 12,284 EVs. For 2021, Ford said its EV sales grew 36% faster than the segment overall for the year, and its total EV sales was second only to Tesla Inc. undefined. Within trucks, Ford said December F-Series sales fell 15.7% to 62,496, Transit sales slumped 45.3% to 8,521 and Ranger sales fell 29.2% to 6,992. Within SUVs, Explorer sales dropped 20.6% to 20,715, Edge sales slid 8.7% to 11,456 and Escape sales shed 38.4% to 10,704. For cars, Mustang sales declined 7.5% to 4,564. Ford's stock has run up 66.8% over the past three months, as it closed Tuesday at the highest price since Aug. 10, 2001, while shares of rival General Motors Co. undefined have climbed 19.8%, Tesla's stock has hiked up 45.4% and the S&amp;P 500 undefined has advanced 10.0%., Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/del-taco-launches-value-menu/story.aspx?guid={1B4074D7-DC40-4F3B-85B1-58D063ECBBE2}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-06 03:36:32 </td>
   <td style="text-align:left;"> Del Taco launches value menu, "20 Under $2" - MarketWatch </td>
   <td style="text-align:left;"> Del Taco Restaurants Inc. 
        TACO,
        +0.40%
       launched its new value menu of food and beverages, "20 Under $2" on Wednesday. The menu includes new items like the Chipotle Chicken Taco, Snack Queso Quesadilla and Strawberry Sprite. "We know our guests are concerned about rising gasoline prices and overall inflation, and that's why we think this is the right menu at the right time," said Tim Hackbardt, Del Taco's chief marketing officer, in a statement. The quick-service chain has also introduced two breakfast tacos, Hashbrowns, Egg &amp; Cheese Stuffed Quesadilla Breakfast Taco and Hashbrowns &amp; Bacon Stuffed Quesadilla Breakfast Taco along with two new mint shakes. Del Taco stock has run up 33.7% for the past year, outpacing the S&amp;P 500 index 
        SPX,
        -1.94%,
       which is up 27.6% for the period.  , Microsoft, Alphabet, Amazon, and others will continue to have significant influence on indexes. But look elsewhere for outsize tech returns, UBS says.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Tonya Garcia is a MarketWatch reporter covering retail and consumer-oriented companies. You can follow her on Twitter @tgarcianyc. She is based in New York. Tonya joined MarketWatch from Moguldom Media, where she was business editor for MadameNoire, a website targeting African-American women with a range of content from personal finance to economics, politics, education and lifestyle and entertainment.  She also worked at Mediabistro, and previously handled media relations for MSLGroup’s consumer practice. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/silver </td>
   <td style="text-align:left;"> 2022-01-06 03:35:36 </td>
   <td style="text-align:left;"> Silver Remains Close to 1-Month High </td>
   <td style="text-align:left;"> Silver held around $23 per troy ounce, not far from a near one-month high of $23.3 hit at the end of December, amid concerns over rising Omicron cases and expectations of tightening monetary policy in 2022. The Federal Reserve is set to end pandemic-era asset purchases in March 2022 and hike interest rates three times next year to curb rising inflation; while the Bank of England unexpectedly hiked rates in December, following its peers in Norway, Brazil, Mexico, South Korea and New Zealand. Last year, silver booked its first yearly decline since 2018 as the global economic recovery from the 2020 health crisis faced mounting headwinds and factory activity weakened due to global production bottlenecks, energy shortages and the new Omicron variant. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/05/business/economy/federal-reserve-minutes-interest-rates.html </td>
   <td style="text-align:left;"> 2022-01-06 03:34:58 </td>
   <td style="text-align:left;"> Fed Officials Discussed Raising Rates Sooner and Faster, Minutes Show - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , By Jeanna Smialek                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Federal Reserve officials suggested that they might withdraw support for the economy more quickly than policymakers had previously expected, minutes from their December meeting showed, as a moment of uncomfortably high inflation forces them to reorient their policy path.                                                                                                                                                                                                                                                                               , Central bankers projected last month that they would raise interest rates three times in 2022 as the economy healed and inflation remained above the Fed’s target. Economists and investors think that those increases could begin as soon as March, which is when the Fed is now expected to wrap up the large-scale bond buying program it has been using in tandem with low rates to stoke the economy.                                                                                                                                                    , Fed officials pointed to a stronger outlook for economic growth and the labor market as well as continuing inflation, saying that “it may become warranted to increase the federal funds rate sooner or at a faster pace than participants had earlier anticipated,” according to the minutes, which were released Wednesday.                                                                                                                                                                                                                                 , Officials might then move to further cool off the economy by reducing the size of their balance sheet — where the bonds they bought are held. That could help to push up longer-term interest rates, which would make borrowing for many types of purchases more expensive and further weaken demand.                                                                                                                                                                                                                                                         , “Some participants also noted that it could be appropriate to begin to reduce the size of the Federal Reserve’s balance sheet relatively soon after beginning to raise the federal funds rate,” the minutes stated.                                                                                                                                                                                                                                                                                                                                           , Markets reacted swiftly to the news. The major stock benchmarks, which had been slightly lower on Wednesday, dropped sharply after the Fed published the document at 2 p.m. The S&amp;P 500 fell 1.9 percent, its biggest drop in weeks.                                                                                                                                                                                                                                                                                                                          , Government bond yields, a proxy for investor expectations about interest rates, jumped. The yield on 10-year Treasury notes climbed as high as 1.71 percent, its highest since April.                                                                                                                                                                                                                                                                                                                                                                         , The Fed’s big asset purchases had been adding juice to the economy and markets with each passing month, so cutting them off will provide less momentum. Raising interest rates could do even more to slow growth: By making borrowing costs for houses, cars and credit cards more expensive, higher rates should slow spending, weigh on investment and eventually hold back hiring and tamp down prices.                                                                                                                                                    , The Fed faces trade-offs as it contemplates the path ahead. Higher interest rates could weaken a job market that is still pulling people back from the sidelines after 2020 pandemic lockdowns. But if the Fed waits too long or moves too slowly, businesses and consumers could begin to adjust their behavior to the very high inflation that has dogged the economy much of the past year. That could make it harder to bring price gains back under control — forcing more drastic, and potentially even recession-causing, rate increases down the road., The minutes showed that both considerations weighed on policymakers’ minds as they considered their future actions, but as the labor market has healed swiftly, they have begun turning their attention decisively toward the threat of too-high inflation. The Fed is tasked with two main jobs, fostering maximum employment and keeping prices relatively stable.                                                                                                                                                                                          , “Several participants remarked that they viewed labor market conditions as already largely consistent with maximum employment,” the minutes said. At the same time, some officials noted that it might be smart to raise rates even if the job market was not fully recovered if inflation showed signs of jumping out of control.                                                                                                                                                                                                                            , “It does cement that they’re definitely pivoting strongly toward rate hikes,” Michael Feroli, chief U.S. economist at J.P. Morgan, said after the release. Although it’s hard to pin down the timing, he said, “they are moving toward putting policy in a more restrictive setting.”                                                                                                                                                                                                                                                                         , There’s a reason for the Fed’s active stance. Inflation has been alarmingly high for much longer than central bankers expected. Last year, policymakers expected prices to pop temporarily as pandemic-affected sectors like airlines and restaurants recovered, then return to normal.                                                                                                                                                                                                                                                                       , Instead, prices through November climbed the most since 1982, and monthly gains remained brisk. Factory shutdowns and tangled shipping lines have made it hard for suppliers to catch up with booming consumer demand for goods, forcing costs up. Price gains have also begun to spread: Rents are increasing more quickly, which could make high inflation more persistent.                                                                                                                                                                                 , Inflation is broadly expected to fade this spring, as prices are measured against relatively high levels from a year earlier. Prices may also decelerate as producers catch up with demand, officials hope. But policymakers lack certainty about when that will happen.                                                                                                                                                                                                                                                                                      , What is inflation? Inflation is a loss of purchasing power over time, meaning your dollar will not go as far tomorrow as it did today. It is typically expressed as the annual change in prices for everyday goods and services such as food, furniture, apparel, transportation costs and toys.                                                                                                                                                                                                                                                              , What causes inflation? It can be the result of rising consumer demand. But inflation can also rise and fall based on developments that have little to do with economic conditions, such as limited oil production and supply chain problems.                                                                                                                                                                                                                                                                                                                  , Where is inflation headed? Officials say they do not yet see evidence that rapid inflation is turning into a permanent feature of the economic landscape, even as prices rise very quickly. There are plenty of reasons to believe the price burst will fade, but some concerning signs suggest it could last.                                                                                                                                                                                                                                                , Is inflation bad? It depends on the circumstances. Fast price increases spell trouble, but moderate price gains could also lead to higher wages and job growth.                                                                                                                                                                                                                                                                                                                                                                                               , How does inflation affect the poor? Inflation can be especially hard to shoulder for poor households because they spend a bigger chunk of their budgets on necessities — food, housing and especially gas.                                                                                                                                                                                                                                                                                                                                                    , Can inflation affect the stock market? Rapid inflation typically spells trouble for stocks. Financial assets in general have historically fared badly during inflation booms, while tangible assets like houses have held their value better.                                                                                                                                                                                                                                                                                                                 , Officials projected in their December economic estimates that inflation will ease to 2.6 percent by the end of 2022, but estimates ranged from 2 percent to 3.2 percent. To put those numbers into context, the Fed’s preferred price index climbed 5.7 percent through November, and the central bank targets 2 percent annual gains on average over time.                                                                                                                                                                                                   , Explaining their forecasts for more lasting high inflation, “participants pointed to rising housing costs and rents, more widespread wage growth driven by labor shortages and more prolonged global supply-side frictions, which could be exacerbated by the emergence of the Omicron variant,” the minutes said.                                                                                                                                                                                                                                            , Officials have adapted their policy rapidly over the past few months as inflation has stirred unease. They announced that they would slow bond purchases, then promptly doubled the pace of that process. They went from signaling that they might or might not raise interest rates in 2022 to making it clear that they plan to do so.                                                                                                                                                                                                                      , The question is what will come next: Will the central bank need to accelerate its plans to pull back stimulus further? Or will inflation fade enough on its own that an aggressive central bank response will prove unnecessary?                                                                                                                                                                                                                                                                                                                              , Investors will also be closely watching how the Fed’s actions affect stock and other asset prices, which tend to benefit from bond buying and low rates. There’s an adage that the Fed’s job is to take away the punch bowl just as the party gets going — and that is what it is gearing up to do.                                                                                                                                                                                                                                                           , Markets “have gotten used to not just a punch bowl but a spiked punch bowl,” said Nela Richardson, chief economist at ADP.                                                                                                                                                                                                                                                                                                                                                                                                                                    , The new coronavirus variant, which could also slow hiring and growth, is also looming over the outlook.                                                                                                                                                                                                                                                                                                                                                                                                                                                       , “Many participants noted that the emergence of the Omicron variant made the economic outlook more uncertain,” the minutes said.                                                                                                                                                                                                                                                                                                                                                                                                                               , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gold </td>
   <td style="text-align:left;"> 2022-01-06 03:32:00 </td>
   <td style="text-align:left;"> Gold Pares Gains after FOMC </td>
   <td style="text-align:left;"> Gold pared early gains to trade around $1810 an ounce on Wednesday after hitting a session-high of $1829.45, as FOMC minutes raised the odds the Fed will raise rates sooner than initially anticipated. Still, concerns over the spread of the omicron coronavirus variant and persistent inflationary pressure prevented further losses and continued to boost its safe-haven appeal. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/currency </td>
   <td style="text-align:left;"> 2022-01-06 03:25:00 </td>
   <td style="text-align:left;"> Dollar Little-Changed After Fed Minutes </td>
   <td style="text-align:left;"> The dollar index held around 96.1 on Wednesday, after the FOMC meeting minutes showed the US central bank might start raising interest rates from record-low levels sooner than expected and reduce its overall asset holdings to tame high inflation. Policymakers also noted that the outlooks for the economy and the labor market had improved despite the risk of new variants of the virus, while elevated inflation had persisted for longer than they had previously anticipated. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/federal-reserve-interest-rates-balance-sheet-december-minutes </td>
   <td style="text-align:left;"> 2022-01-06 03:19:58 </td>
   <td style="text-align:left;"> Fed eyes faster interest rate liftoff, balance sheet reduction as inflation soars </td>
   <td style="text-align:left;"> Kroll chief strategist Chris Campbell says government spending will force the Federal Reserve to raise interest rates.                                                                                                                                                                                                                                                                                                                                                                       , Most Federal Reserve officials agreed last month that surging inflation and a rapidly recovering labor market could warrant a faster-than-expected interest rate hike as policymakers seek to wind down pandemic-era support for the U.S. economy.                                                                                                                                                                                                                                           , Stocks tumbled in reaction.                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Minutes from the U.S. central bank's Dec. 14-15 meeting show that many policymakers believe they will reach their employment goal soon if economic conditions continue to improve, opening the door to the Fed's first interest rate hike in three years. The Fed slashed rates to near zero in March 2020 as the nation confronted an unprecedented pandemic that froze economic activity and plunged the country into its steepest recession in almost a century.                          , FED DOUBLES TAPER RATE, EYES THREE INTEREST RATE HIKES IN 2022                                                                                                                                                                                                                                                                                                                                                                                                                               , "Participants generally noted that, given their individual outlooks for the economy, the labor market and inflation, it may become warranted to increase the federal funds rate sooner or at a faster pace than participants had earlier anticipated," the minutes, released Wednesday, said. "Some participants also noted that it could be appropriate to begin to reduce the size of the Federal Reserve’s balance sheet relatively soon after beginning to raise the federal funds rate.", In this March 3, 2020 file photo, Federal Reserve Chair Jerome Powell speaks during a news conference to discuss an announcement from the Federal Open Market Committee in Washington.  (AP Photo/Jacquelyn Martin / AP Newsroom)                                                                                                                                                                                                                                                            , At the conclusion of their two-day meeting last month, policymakers announced they would double the tapering of a massive bond-buying program, putting the Fed on pace to end the program by March. In making the decision, they cited improvements in the labor market and the hottest inflation in nearly 40 years.                                                                                                                                                                        , Although officials held rates near zero during the meeting, they were unanimous in forecasting at least one rate hike next year. That marked a considerable shift from September, when half of the central bankers believed interest rate increases were not warranted until at least 2023.                                                                                                                                                                                                  , Officials now project rates to stand at 0.9% at the end of 2022, 1.6% at the end of 2023 and 2.1% at the end of 2024.                                                                                                                                                                                                                                                                                                                                                                        , "We believe the Fed is likely to raise interest rates quicker and potentially shrinking their balance sheet sooner than many expect as they signal fighting inflation is more important than protecting against a drop in economic activity," said Chris Zaccarelli, chief investment officer for Independent Advisor Alliance. "What is harder to forecast is to what level of market selloff they are willing to tolerate before changing course."                                         , A woman walks past the Federal Reserve headquarters in Washington Sept. 16, 2015.  (REUTERS/Kevin Lamarque / Getty Images)                                                                                                                                                                                                                                                                                                                                                                   , Traders expect the Fed to begin raising rates in March, according to the CME's FedWatch tool, which could mean the balance reduction begins in early summer. Policymakers said the appropriate timing of reducing the balance sheet would likely be "closer to that of policy rate liftoff in the committee’s previous experience," the minutes said.                                                                                                                                        , Meeting minutes suggested that once the process begins, the runoff of the $8.8 trillion balance sheet could be "faster than it was during the previous normalization episode" in 2017. Some participants also "judged that a significant amount of balance sheet shrinkage could be appropriate over the normalization process."                                                                                                                                                             , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                      , For months, the Fed has been wrestling with its dual mandate of stable prices and full employment: The nation's jobless rate plunged to 4.2% in November, but there are still about 6.9 million out-of-work Americans. At the same time, consumer prices in November soared 6.8% from a year ago, the fastest pace since June 1982. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/interest-rate </td>
   <td style="text-align:left;"> 2022-01-06 03:16:00 </td>
   <td style="text-align:left;"> Fed Hints It May Remove Stimulus Quicker </td>
   <td style="text-align:left;"> Fed policymakers noted that given the outlook for the economy, labour market and inflation it may become warranted to increase the federal funds rate sooner or at a faster pace than previously anticipated, minutes from the last FOMC meeting of 2021 showed. Some Fed policymakers also noted that it could be appropriate to start reducing the size of the balance sheet soon after the central bank begins raising interest rates. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-01-06 03:15:00 </td>
   <td style="text-align:left;"> Dow Jones Cuts Gains After Fed Minutes </td>
   <td style="text-align:left;"> The Dow Jones surrendered its modest gains to trade in negative territory, while both the S&amp;P 500 and Nasdaq extended losses, as investors digested the latest FOMC meeting minutes and as soaring Treasury yields continued to pressure the tech sector. Fed policymakers widely agreed that it might become warranted to increase interest rates sooner than they had earlier anticipated, given a brighter outlook for the economy and the labor market against the backdrop of rising inflation. In December, the US central bank announced it would end its pandemic-era bond purchases in March, paving the way for three interest rate hikes by the end of 2022. Meanwhile, the ADP report showed private businesses in the US added in December the most jobs in seven months. On the corporate front, shares of Pfizer gained more than 2% after the Bank of America upgrade the stock to “buy” from “neutral” while Microsoft shares (-1.7%) were among the worst performs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/2-year-note-yield </td>
   <td style="text-align:left;"> 2022-01-06 02:59:49 </td>
   <td style="text-align:left;"> US 2Y Bond Yield Hits 22-month High </td>
   <td style="text-align:left;"> US 2 Year Government Bond Yeld increased to a 22-month high of 0.8097% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/wells-fargo-chief-risk-officer/story.aspx?guid={6122B7EB-8D98-484A-90D2-7D1D1BABD40D}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-06 02:58:42 </td>
   <td style="text-align:left;"> Wells Fargo Chief Risk Officer Amanda Norton retiring this year - MarketWatch </td>
   <td style="text-align:left;"> Wells Fargo &amp; Co.
        WFC,
        -0.87%
       Chief Risk Officer Amanda Norton will retire from the bank in June after about four years in the post, a spokesperson for the bank told MarketWatch on Wednesday. Norton, 55, joined Wells Fargo in 2018. Wells Fargo plans to name a replacement in the next few weeks, according to a letter to employees by Wells Fargo CEO Charlie Scharf seen by MarketWatch. "Living through a pandemic teaches you things, and I've realized that now is the time to do some things I want and need to do outside of my career," Norton said in an internal letter. "It is time for me to focus more on my family, get more exercise, pursue interests that have gone dormant, and to finally have the knee surgery I've been putting off for too long." CEO Scharf said Norton has been central to the bank's effort to strengthen its risk control infrastructure. The departure of Norton was initially reported Tuesday by The Wall Street Journal and other publications. Wells Fargo shares are up 72% in the past year., Djokovic attempted to enter Australia on Wednesday after securing a COVID-19 medical exemption to compete in the Australian Open
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Steve Gelsi covers banking and cannabis as a Senior Reporter for MarketWatch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-06 02:55:00 </td>
   <td style="text-align:left;"> US Treasury Yields March Higher after FOMC </td>
   <td style="text-align:left;"> US Treasury yields continued to rise on Wednesday, with the 10-year one hitting an 11-week high of 1.699%, after the FOMC minutes showed the Fed will likely raise rates sooner than expected. Interest rate futures now roughly see an 80% chance of a rate hike in the fed funds rate at the March meeting. Meanwhile, the 2-year yield hit its highest since March 2020 and the 5-year one the highest since mid-February 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/pfizer-upgraded-buy-bofa-paxlovid/story.aspx?guid={BBC5340D-346F-401E-9B75-43D202832D3C}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-06 02:52:02 </td>
   <td style="text-align:left;"> Pfizer upgraded to buy at BofA as Paxlovid likely to offset patent expiration concerns - MarketWatch </td>
   <td style="text-align:left;"> Shares of Pfizer Inc. 
        PFE,
        +2.02%
       rallied 2.5% in afternoon trading Wednesday, after BofA Securities analyst Geoff Meacham turned bullish on the drug maker, saying its COVID-19 pill Paxlovid could alleviate concerns over a "cluster of patent expirations" starting in 2025. Meacham raised his rating to buy, after being at neutral since he started covering Pfizer in October 2020, and raised his stock price target to $70 from $59. He said the Paxlovid rollout "should provide more durable revenues and robust cash flow, the latter of which expands the menu of strategic options around the [loss of exclusivity] period." The upgrade comes a day after Pfizer said the U.S. government doubled its order for treatment courses of Paxlovid to 20 million, which are to be delivered by the end of September. Pfizer's stock has rallied 32.1% over the past three months, while the SPDR Health Care Select Sector ETF 
        XLV,
        -0.71%
       has tacked on 9.7% and the S&amp;P 500 
        SPX,
        -1.94%
       has gained 9.9%., Amazon, Visa, Nordstrom, and AT&amp;T are among the stocks pegged to outperform the S&amp;P 500 next year.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/gold-futures-score-back-to-back-session/story.aspx?guid={7C131DEA-AC59-4C0B-B281-C3B108049163}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-06 02:42:01 </td>
   <td style="text-align:left;"> Gold futures score back-to-back session gains - MarketWatch </td>
   <td style="text-align:left;"> Gold futures rose Wednesday for a second straight session, finding support as U.S. benchmark stock indexes traded mostly lower and the dollar weakened. "Investors seem to be gravitating towards gold as rising omicron variant cases accelerate the flight to safety," said Lukman Otunuga, manager, market analysis, at FXTM. How gold concludes the first trading week of 2022, however, will be influenced by not only the FOMC meeting minutes due out at 2 p.m. Eastern time, but by the key U.S jobs data on Friday, he said. "If these reports reinforce expectations over the Federal Reserve raising interest rates three times this year, this could send zero-yielding gold lower." February gold 
        GCG22,
        -0.77%
       rose $10.50, or 0.6%, to settle at $1,825.10 an ounce., Interest rate hikes are coming. The stock market is taking note.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-06 02:30:01 </td>
   <td style="text-align:left;"> Canada 10Y Bond Yield Hits 5-week High </td>
   <td style="text-align:left;"> Canada 10 Year Government Bond Yeld increased to a 5-week high of 1.625% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/nickel </td>
   <td style="text-align:left;"> 2022-01-06 02:29:50 </td>
   <td style="text-align:left;"> Nickel Climbs to Decade High </td>
   <td style="text-align:left;"> Nickel futures break above $21,200 a tonne in January of 2022 for the first time in a decade supported by low inventories on both the LME and the Shanghai Future Exchange warehouses and expectations that policy easing in China would boost demand for industrial metals. Last year, the price of nickel jumped more than 25%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/congress-exploring-more-covid-relief-small-businesses-omicron </td>
   <td style="text-align:left;"> 2022-01-06 02:15:41 </td>
   <td style="text-align:left;"> Congress exploring more COVID relief for small businesses as omicron surges </td>
   <td style="text-align:left;"> Nello owner Thomas Makkos says people 'are very afraid to come out' of their homes and that the new strain has led to many cancellations with no end in sight.                                                                                                                                                                                                                                                                                            , A bipartisan group of lawmakers has started exploring another round of coronavirus relief funding for small businesses as a surge of the highly contagious omicron variant threatens to unleash more economic havoc.                                                                                                                                                                                                                                      , Sens. Ben Cardin, D-Md., and Roger Wicker, R-Miss., have spearheaded an effort to provide small businesses with additional federal aid, a person familiar with the matter told FOX Business. The news was first reported by The Washington Post.                                                                                                                                                                                                          , A RECORD 4.5M AMERICANS QUIT THEIR JOBS IN NOVEMBER                                                                                                                                                                                                                                                                                                                                                                                                       , The source said the duo is crafting a package based on a bill the pair introduced in August that would replenish the Restaurant Revitalization Fund, a program created by Democrats in March 2021 that gave food and beverage providers grants equal to their pandemic-related revenue loss, with a maximum of $10 million per business and $5 million per location.                                                                                      , The proposed legislation, which failed to pass, would have allocated an additional $48 billion to the fund. The Post reported that Wicker and Cardin put together a $68 billion proposal in mid-December that includes a mix of new spending and reallocation of unused cash authorized under previous packages.                                                                                                                                          , Customers sit outside the Newsbar restaurant in New York Aug. 7, 2021.  (Allison Hess/Bloomberg via Getty Images / Getty Images)                                                                                                                                                                                                                                                                                                                          , The Restaurant Revitalization Fund launched May 3 and paid out approximately $29 billion to eligible applicants, which included restaurants, bars, food trucks and carts, brewpubs, tasting rooms and other food service establishments. Businesses could use the grants to cover expenses, rent and supply costs. The fund ran out of money in less than two months after providing grants to more than 100,000 businesses.                              , Any spending plan faces an uphill battle in the narrowly divided Senate, where Republicans previously sank efforts to provide small businesses with additional aid over concerns about the nation's deficit. But the talks underscore growing unease on Capitol Hill over a stunning rise in cases driven by the highly transmissible omicron variant. The U.S. is now reporting a seven-day moving average of more than 122,000 cases.                   , COVID-19 OMICRON SPREAD PROMPTS TEMPORARY RESTAURANT CLOSURES, VACCINE REQUIREMENTS                                                                                                                                                                                                                                                                                                                                                                       , While it's still unclear what the fast-spreading variant will ultimately mean for the health of the economy, its effects on daily life have already been felt. Thousands of flights have been canceled, Broadway shows are shuttering their doors and a growing number of schools have postponed reopenings.                                                                                                                                              , The U.S. Capitol in Washington, D.C., Wednesday, Jan. 5, 2022.  (Stefani Reynolds/Bloomberg via Getty Images / Getty Images)                                                                                                                                                                                                                                                                                                                              , The White House has maintained that it has the resources needed to respond to any disruptions caused by the omicron spread. Asked Wednesday about the possibility of a relief package that targets restaurants and other small businesses, White House press secretary Jen Psaki pointed to the $1.9 trillion package that Democrats passed nearly a year ago.                                                                                            , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                               , "We did a major relief package that included helping restaurants just last year," she said. "We are in constant discussions with Congress and leadership about the needs of the American people, whether they are small businesses or restaurants or people sitting in their homes as we continue to fight the pandemic, but don't have any new prediction of new pending requests or specific requests and wouldn't predict that at this moment in time.", Only about one-third of restaurants that applied for relief through the fund received a grant, and the Independent Restaurant Coalition, a trade group formed during the pandemic, estimates that nearly 80% of restaurants could close this winter without additional aid. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/uruguay/inflation-cpi </td>
   <td style="text-align:left;"> 2022-01-06 02:14:00 </td>
   <td style="text-align:left;"> Uruguay Inflation Rate Ticks up to 9-Month High </td>
   <td style="text-align:left;"> The annual inflation rate in Uruguay edged up to 7.96 percent in December of 2021 from 7.86 percent in the previous month. It was the highest inflation rate since March, as prices rose at a faster pace for housing and utilities (7.71 percent vs 7.23 percent in November), transport (13.38 percent vs 12.75 percent), restaurants and hotels (8.23 percent vs 7.55 percent) and recreation and culture (7.04 percent vs 6.67 percent). On the other hand, prices eased for food and non-alcoholic beverages (6.5 percent vs 6.77 percent) and health (7.16 percent vs 7.33 percent). On a monthly basis, consumer prices edged down 0.1 percent compared to a 0.25 percent uptick in November. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/brent-crude-oil </td>
   <td style="text-align:left;"> 2022-01-06 02:07:00 </td>
   <td style="text-align:left;"> Brent Hits 7-Week High </td>
   <td style="text-align:left;"> Brent crude futures surged as much as 1.5% to a 7-week high of $81.44 a barrel before paring some of the gains to below $81 on Wednesday, after OPEC+ agreed to increase oil output by 400,000 barrels per day in February although doubts persist over whether the group will be able to actually increase production as members including Nigeria and Libya struggle to raise it. At the same time, EIA data showed US crude inventories declined for a 6th straight week, raising further concerns over supply and constraints. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/heating-oil </td>
   <td style="text-align:left;"> 2022-01-06 01:53:11 </td>
   <td style="text-align:left;"> Heating Oil Hits 7-week High </td>
   <td style="text-align:left;"> Heating Oil increased to a 7-week high of 2.4596 USD/Gal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/01/05/world/russia-rocket-uncontrolled-reentry-scn/index.html </td>
   <td style="text-align:left;"> 2022-01-06 01:44:08 </td>
   <td style="text-align:left;"> Russian rocket stage makes uncontrolled entry into Earth's atmosphere - CNN </td>
   <td style="text-align:left;"> Sign up for CNN's Wonder Theory science newsletter. Explore the universe with news on fascinating discoveries, scientific advancements and more.                                                                                                                                                                ,  (CNN)An out-of-control Russian rocket stage has re-entered the Earth's atmosphere, according to the latest estimate from US Space Command, which has been tracking its descent.                                                                                                                                , The Angara-A5 heavy-lift rocket was launched from the Plesetsk spaceport in Russia's northwestern Arkhangelsk region on Monday, December 27. The launch was testing a new upper rocket stage, known as the Persei booster, according to the state-run TAS news agency.                                          , Most space debris burns up on reentry to Earth's atmosphere and poses an extremely minimal risk to humans, but it's possible that larger parts could cause damage if they landed in inhabited regions.                                                                                                          , But on Wednesday, US Space Command — which had tracked the rocket booster during reentry — said the rocket reentered the Earth's atmosphere at 2:08 pm MST over the Southern Pacific Ocean. That's 4:08 pm ET.                                                                                                  , It may, however, be impossible to determine exactly where the debris landed.                                                                                                                                                                                                                                    ,                                                                                                                                                                                                                                                                                                                 ,                                                                                                                                                                                                                                                                                                                 , Earlier on Wednesday, the head of the European Space Agency's Space Debris Office, Holger Krag, said the Russian rocket part had been traveling at 7.5 kilometers per second (4.7 miles per second), and its reentry latitude was likely to be between 63 degrees north and south of the equator.               , Risk level                                                                                                                                                                                                                                                                                                      , While it was highly unlikely that the rocket would cause damage or hurt anyone, "the risk is real and cannot be ignored," Krag said.                                                                                                                                                                            , In May 2021, NASA lambasted China for its failure to "meet responsible standards" after debris from an out-of-control rocket used to launch China's space station plunged into the Indian Ocean.                                                                                                                , The Russian rocket part is thought to be smaller than the Chinese debris, weighing around 4 tons without fuel, compared to around 20 tons for the Chinese Long March 5B rocket, said Krag.                                                                                                                      , The Chinese Long March rocket was one of the largest objects in recent memory to strike the Earth after falling out of orbit, following a 2018 incident in which a piece of a Chinese space lab broke up over the Pacific Ocean and the 2020 reentry of another Long March 5B rocket.                           , The Persei booster was about 10 meters (33 feet) long compared to 32-meter (105-foot) Chinese Long March 5B rocket, according to Jonathan McDowell, an astronomer at the Center for Astrophysics - Harvard &amp; Smithsonian. While it weighed less, it was carrying about 16 tons of propellant on board, he said. , The "total mass is about the same as the Chinese stage, but most of it is probably liquid and will burn up in the atmosphere, so the risk to the ground is significantly less. I think," said McDowell via email.                                                                                               , Original intentions                                                                                                                                                                                                                                                                                             , He added that the Russian rocket stage was not intended to reenter the Earth's atmosphere in this way.                                                                                                                                                                                                          , "It was meant to end up in an orbit where it would stay for many thousands of years. The rocket failed to restart. The Chinese stage reentry was by DESIGN, they deliberately left it in a low orbit," he said.                                                                                                 , Russia's space agency Roscosmos told CNN the launch was operated by the Russian Ministry of Defence, which did not immediately respond to an emailed request for comment.                                                                                                                                       , Best international practice for spent rocket parts or spacecraft at the end of their life span was typically to make a controlled reentry and fall to Earth in an uninhabited area -- usually a remote part of the Pacific Ocean, Krag said.                                                                    , Krag added that, on average, 100 to 200 tons of space junk reenter the Earth's atmosphere in an uncontrolled way every year. Only one person is known to have been hit by space junk -- a woman named Lottie Williams in Texas in 1997. She was unscathed and lived to tell the tale.                           , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/rhodium </td>
   <td style="text-align:left;"> 2022-01-06 01:40:28 </td>
   <td style="text-align:left;"> Rhodium Climbs to 4-Month High </td>
   <td style="text-align:left;"> Rhodium futures rose to $14,750 per troy ounce in January of 2022, the highest in near four months as automakers are expected to slowly recover from a chip shortage that disrupted production last year. Auto makers consume around 90% of the 1 million ounce rhodium market, making the commodity highly vulnerable to the chip shortage. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/platinum </td>
   <td style="text-align:left;"> 2022-01-06 01:31:01 </td>
   <td style="text-align:left;"> Platinum Hits 6-week High </td>
   <td style="text-align:left;"> Platinum increased to a 6-week high of 1001 USD/t.oz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/technology-59881892?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-06 01:30:59 </td>
   <td style="text-align:left;"> Vodafone and EE delay EU roaming charges return </td>
   <td style="text-align:left;"> Vodafone is delaying the reintroduction of roaming charges in Europe by three weeks.                                                                                                                                                                                            , The phone network had planned to bring in post-Brexit roaming fees on 6 January, matching other networks who plan to do so in 2022.                                                                                                                                             , But it said more time was needed for testing, and the change will now come in at the end of January.                                                                                                                                                                            , EE has also delayed resuming its roaming charges, which were planned for January, until March.                                                                                                                                                                                  , Before the UK left the EU, users were able to use their calls, texts, and data allowance in their mobile plans in any EU country. But the EU trade deal of December 2020 gave mobile operators the option of reintroducing charges.                                             , The Three network has also said it will bring in roaming charges between the UK and Europe, though their change is planned for May 2022.                                                                                                                                        , That means that of the largest mobile networks, only O2 has not announced any plans for the reintroduction of roaming fees.                                                                                                                                                     , Explaining the reason for delaying its planned changes, Vodafone said it was not ready to bring in the new system.                                                                                                                                                              , "We have pushed back the introduction of roaming charges to the end of January, giving time for further testing to ensure the best possible experience for customers purchasing our £1 per day bundles. Until then, customers will continue to be able to roam without charges.", The £1 a day charge is Vodafone's best price, and only applies when bought in an eight or 15-day bundle. The usual planned price is £2 per day in fees, matching EE and Three's planned pricing.                                                                                , EE said the shift in its plans was caused by unspecified technical delays.                                                                                                                                                                                                      , "Making big changes to billing systems in mobile phone networks is always risky," said Ben Wood, chief analyst at CCS Insight and founder of the Mobile Phone Museum.                                                                                                           , "The backlash and negative publicity for any network operator that does not get it right would be immense if a customer ended up with an eye-watering roaming bill.                                                                                                             , "My guess is that rather than rushing out a change, the operators are delaying the introduction to be absolutely sure everything is working.                                                                                                                                    , "Given the current Covid situation it's not like lots of people are travelling, so the operators are not going to be massively exposed on unexpected roaming costs."                                                                                                            , Meet the new candidates looking to impress Lord Sugar in The Apprentice                                                                                                                                                                                                         , How did Chinese woman Zheng Yi Sao and her army terrorise the seas?                                                                                                                                                                                                             , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/3-year-note-yield </td>
   <td style="text-align:left;"> 2022-01-06 01:29:26 </td>
   <td style="text-align:left;"> US 3Y Bond Yield Hits 4-week High </td>
   <td style="text-align:left;"> US 3 Year Government Bond Yeld increased to a 4-week high of 1.0622% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-06 01:26:50 </td>
   <td style="text-align:left;"> UK 10Y Bond Yield Hits 9-week High </td>
   <td style="text-align:left;"> UK 10 Year Government Bond Yeld increased to a 9-week high of 1.096% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/05/stocks-making-the-biggest-moves-midday-microsoft-enphase-energy-salesforce-and-more.html </td>
   <td style="text-align:left;"> 2022-01-06 01:26:02 </td>
   <td style="text-align:left;"> Stocks making the biggest moves midday: Microsoft, Enphase Energy, Salesforce and more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                    , Check out the companies making headlines in midday trading Wednesday:                                                                                                                                                                                                                                              , Salesforce, Adobe — The software stocks fell more than 4% each after UBS downgraded both companies to neutral from buy. UBS said that enterprise tech spending was pulled forward by the pandemic, leading to slower growth for Salesforce and Adobe in 2022.                                                      , Enphase Energy — Shares of Enphase dropped 7.5% after Bank of America downgraded the stock to neutral from buy. The Wall Street firm also slashed its price target to $187 per share from $297 per share.                                                                                                          , Microsoft — Some software, technology and chip stocks continued to fall after Tuesday's sell-off. Okta lost 2.8%, DocuSign fell 2% and Snowflake slipped 3%. Microsoft lost 2.1%.                                                                                                                                  , Alibaba — Shares of the Chinese e-commerce giant jumped almost 5% after Charlie Munger's Daily Journal nearly doubled its stake in the stock. A regulatory filing Tuesday showed that Daily Journal now owns more than 600,000 shares of Alibaba.                                                                  , Beyond Meat — Shares of the alternative meat company jumped 3% after KFC announced it will add Beyond Meat's plant-based chicken to its menus starting Monday. The two companies have been testing the product for years, and the Beyond Meat fried chicken will be available for a limited time, according to KFC., Pinterest– Shares of the image-sharing site rose nearly 2% after Piper Sandler upgraded the stock to overweight from neutral. The Wall Street firm said Pinterest's share price could rebound by 60% after a 50% sell-off over the past year as concerns about user growth appear to be overblown.                 , Pfizer — Shares of the Covid-19 vaccine maker jumped 1.8% following an upgrade to buy from neutral from Bank of America. The firm noted that the financial success of the company's Covid vaccines and oral treatments puts it on strong footing for years ahead.                                                  , Nikola — Shares of the electric truck maker added more than 3% in midday trading after logistics company USA Truck announced a deal to buy 10 electric Nikola trucks.                                                                                                                                              , Garmin — Shares of Garmin rose 3% after Deutsche Bank upgraded the stock to buy from hold. The Wall Street firm said it likes Garmin's "high quality" financials.                                                                                                                                                  , — with reporting from CNBC's Jesse Pound, Hannah Miao, Yun Li and Tanaya Macheel.                                                                                                                                                                                                                                  , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                             , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                             , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                   , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                   , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                 , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/steel </td>
   <td style="text-align:left;"> 2022-01-06 01:22:00 </td>
   <td style="text-align:left;"> Steel Rises to Over 1-Week High </td>
   <td style="text-align:left;"> Steel rebar futures bounced back above CNY 4,600 a tonne, the highest in over a week buoyed by restocking demand and renewed steel production controls in Tangshan city. Industrial companies in China's steel hub were ordered to cut their production after an orange alert for heavy pollution was issued on January 3rd. Top steel producer China is expected to keep output restrictions in place to ensure smog-free skies as it hosts the 2022 Winter Olympic Games in February. On the demand side, low temperatures have been reducing construction activity in many parts of China. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-01-06 01:14:55 </td>
   <td style="text-align:left;"> Dow Jones Hits All-time High </td>
   <td style="text-align:left;"> US30 increased to an all-time high of 36936 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/01/05/sheep-syringe-covid19-vaccination-germany-lon-orig-tp.cnn </td>
   <td style="text-align:left;"> 2022-01-06 01:13:31 </td>
   <td style="text-align:left;"> Sheep form syringe shape in campaign to get vaccinated against Covid-19 - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-01-06 01:08:47 </td>
   <td style="text-align:left;"> London Stocks Close at Near 2-Year Highs </td>
   <td style="text-align:left;"> The FTSE 100 closed up 0.2% at 7,517 on Wednesday, its highest level since February 12th, 2020, led by strong gains in travel stocks, commodity-related firms and auto makers. In addition, Ocado Group jumped more than 3% after Berenberg upgraded its shares to "buy", while London Stock Exchange gained nearly 2% following a similar rating upgrade by Citigroup. Investors were upbeat about the economic outlook after Prime Minister Boris Johnson said on Tuesday there was no need to tighten restrictions in England despite the record surge in coronavirus cases. Meanwhile, prospects for US rate hikes added to concerns ahead of the publication of the Fed's December meeting minutes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/01/05/world/lightning-increased-north-pole-arctic-2021-climate/index.html </td>
   <td style="text-align:left;"> 2022-01-06 01:08:23 </td>
   <td style="text-align:left;"> Lightning in far northern Arctic increased in 2021 - CNN </td>
   <td style="text-align:left;"> (CNN)As extreme weather wreaked havoc across the globe in 2021, a stunning change was happening in the far northern Arctic, largely out of sight but detectable by a network of sensors. Lightning increased significantly in the region around the North Pole, which scientists say is a clear sign of how the climate crisis is altering global weather.                                                                                      , Vaisala, an environmental monitoring company that tracks lightning around the world, reported 7,278 lightning strokes occurred last year north of 80 degrees latitude, nearly twice as many as the previous nine years combined.                                                                                                                                                                                                                 , Arctic lightning is rare -- even more so at such far northern latitudes -- and scientists use it as a key indicator of the climate crisis, since the phenomena signals warming temperatures in the predominantly frozen region. Lightning occurs in energetic storms associated with an unstable atmosphere, requiring relatively warm and moist air, which is why they primarily occur in tropical latitudes and elsewhere during summer months.,                                                                                                                                                                                                                                                                                                                                                                                                                                                  , The annual number of lightning strokes in the Arctic -- the region north of around 65 degrees latitude -- has remained consistent over the past decade, but it is now surging significantly in the extreme north. Chris Vagasky, meteorologist and lightning applications manager at Vaisala, said a warming planet is charging up the Arctic's environment for more lightning to occur.                                                         , "What we've been seeing is that lightning and thunderstorms are developing over Siberia, and then moving out over the Arctic Ocean and continuing very far north," Vagasky told CNN, underscoring "the warm, humid air from all continents are now going out over the Arctic Ocean and they're persisting over the Arctic Ocean, so that you get storms that are developing there."                                                              ,                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Jose Martinez-Claros, a researcher at the University of California, San Diego's Center for Western Weather and Water Extremes, who is not involved with the report, said the findings were "concerning."                                                                                                                                                                                                                                         , "It seems to suggest in the drying and warming climate, these types of storms now reach latitudes that are very much higher than they used to be and closer to the Arctic," he said.                                                                                                                                                                                                                                                             , A 2021 study also found Arctic lightning had increased between 2010 and 2020 and the trend was strongly linked to global warming, which is caused by fossil fuel emissions.                                                                                                                                                                                                                                                                      , "We know that the Arctic is changing faster than the rest of the Earth with respect to its climate," Vagasky said. "And so monitoring these trends in thunderstorms and lightning in this very remote area helps us detect where these warm, moist air intrusions are occurring in this region."                                                                                                                                                 , Lightning in the US also increased in 2021, according to the Vaisala report, where more than 194 million lightning strokes occurred -- 24 million more than what was observed in 2020.                                                                                                                                                                                                                                                           , More than 1 million of those occurred in December, in concert with several unprecedented winter time severe weather outbreaks that ravaged the Central and Southern US. It was the highest number of strokes researchers have seen in December since 2015, Vagasky said, noting now "even the December time period, you might be getting spring- or summer-type conditions," he added.                                                           ,                                                                                                                                                                                                                                                                                                                                                                                                                                                  , In the US, Texas recorded the most lightning last year, primarily due to its large area and warm, storm-prone location, Vaisala reports. Florida saw the highest lightning density than any other state, with 223 lightning events per square mile, followed by Louisiana and Texas.                                                                                                                                                             , Researchers also found lightning-triggered wildfires burned more than two million acres in the US last year. In the drought-stricken West, dry lightning sparked deadly and destructive wildfires, including the Bootleg Fire in Oregon that burned more than 400,000 acres.                                                                                                                                                                     , British Columbia, which typically doesn't experience as much lightning as Canada's central provinces, also saw a particularly rare lightning outbreak as an unprecedented heat wave seared the region. Between June 30 and July 1, more than 700,000 lightning strokes were recorded in the province.                                                                                                                                            , Vaisala has been detecting lightning in the US for nearly 40 years, and around the planet since 2012. The network detects more than two billion lightning events around the world each year, according to Vaisala, including a 2019 lightning event around 32 miles from the North Pole, which set a Guinness World Record for the northernmost lightning stroke ever detected.                                                                  , Vagasky said as the climate crisis advances and the Arctic continues to warm, changes in far remote regions will have a ripple effect on weather across the planet.                                                                                                                                                                                                                                                                              , "All weather is local," Vagasky said. "When you're having these drastic changes, especially in places like the Arctic, those sorts of changes are not just impacting the Arctic. The Earth is totally interconnected."                                                                                                                                                                                                                           , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/solar </td>
   <td style="text-align:left;"> 2022-01-06 01:01:45 </td>
   <td style="text-align:left;"> Solar Energy Index Hits 30-week Low </td>
   <td style="text-align:left;"> Solar Energy Index decreased to a 30-week low of 378.54 USD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-01-06 01:00:00 </td>
   <td style="text-align:left;"> South African Stocks Close Around Record Highs </td>
   <td style="text-align:left;"> The FTSE/JSE All Share Index closed almost muted at 75,061 on Wednesday, after having touched a fresh record high of 75,084 earlier in the session, as strong losses in heavyweights Naspers and its subsidiary Prosus weighed. At the same time, investors weighed the double threat of an unpredictable pandemic and looming interest rates increases ahead of key US Fed minutes from the latest monetary policy decision. Domestically, the focus was on the implications of the first part of the Zondo Commission's report on state capture, which has made damning findings among a number of politicians and politically connected individuals. The report has also recommended the establishment of an independent agency against corruption as part of the measures to restore confidence in the state. On the data front, a PMI survey showed South Africa's private sector activity shrank in December, amid concerns over the Omicron variant and tighter travel restrictions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/lifestyle/hong-kong-disneyland-closure-covid-omicron </td>
   <td style="text-align:left;"> 2022-01-06 00:58:09 </td>
   <td style="text-align:left;"> Hong Kong Disneyland to temporarily close as omicron cases surge </td>
   <td style="text-align:left;"> FOX Business' Ashley Webster speaks with Canaveral Port Authority CEO Captain John Murray regarding the CDC's warning to Americans looking to travel via cruise ship.                                                                                                                                                                                                                                                                                                                                                , The Walt Disney Company will temporarily close its Hong Kong Disneyland theme park as the global spread of the coronavirus's omicron variant has led to a surge of cases in the city.                                                                                                                                                                                                                                                                                                                                , DISNEY WORLD ENDS SERVICE FROM ORLANDO AIRPORT TO RESORT, POSSIBLY CAUSING INCREASE IN RIDE-SHARE PRICES                                                                                                                                                                                                                                                                                                                                                                                                             , "As required by the government and health authorities and in line with prevention efforts taking place across Hong Kong, Hong Kong Disneyland Park will temporarily close from Jan. 7 to 20, 2022," a notice on Hong Kong Disneyland's website reads. "The resort hotels will remain open with adjusted level of services. Service at restaurants and recreation facilities in hotels will be adjusted according to the latest regulations."                                                                         , Disney emphasized the arrangements will be adjusted from time to time based on the latest guidance from government and health officials.                                                                                                                                                                                                                                                                                                                                                                             , A notice of closure stands at the entrance to Walt Disney Co.'s Disneyland Resort, temporarily closed due to the coronavirus, in Hong Kong, China, on Wednesday, July 15, 2020. (Lam Yik/Bloomberg via Getty Images)                                                                                                                                                                                                                                                                                                 , The latest closure for Hong Kong Disneyland comes after the park reopened for the third time in February 2021.                                                                                                                                                                                                                                                                                                                                                                                                       , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , On Wednesday, Hong Kong reported 38 new COVID-19 cases. Among the new cases, 34 are imported, three are epidemiologically linked to previous imported cases and one is local. On Tuesday, the city reported its first untraceable local COVID-19 case, which officials have warned is likely due to the omicron variant, ending a three-month streak without any community cases.                                                                                                                                    , To mitigate the spread of the virus, city officials have banned passenger flights from eight countries for the next two weeks starting Jan. 8. The countries include Australia, Canada, France, India, Pakistan, the Philippines, the UK and the US. Starting Friday, indoor dining after 6 p.m. will be banned, and all gyms, theme parks, pools, party rooms, clubs, museums and other venues will be closed for at least two weeks. Hospital visits will also be halted and "cruises to nowhere" will be canceled., Hong Kong chief executive Carrie Lam encouraged private companies to allow their employees to work from home. Meanwhile, the city's Civil Service bureau is assessing whether it will be possible for civil servants to deliver services without working in the office. Lam added that schools will not suspend face-to-face learning for "the benefit and the interest of the children."                                                                                                                            , The new cases bring Hong Kong's total to 12,799, while the city's death toll stands at 213. Over 10 million COVID-19 vaccine doses have been administered in the city to date, with more than 4.9 million people receiving at least one dose, more than 4.6 million receiving two doses and over 455,000 people receiving a third vaccine dose.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/gm-stock-chevy-silverado-debuts-ceo-mary-barra </td>
   <td style="text-align:left;"> 2022-01-06 00:51:22 </td>
   <td style="text-align:left;"> Bull case for GM stock as Chevy Silverado debuts </td>
   <td style="text-align:left;"> GM CEO Mary Barra reveals the automakers plan to phase out internal combustion vehicles on 'The Claman Countdown.'                                                                                                                           , One day after General Motors was dethroned by Toyota, which outsold the U.S. automaker for the first time since 1931, CEO Mary Barra is undeterred.                                                                                          , She unveiled, at the Consumer Electronics Show, the much-anticipated, all-electric Chevrolet Silverado, also known as the Chevrolet Silverado E, in a move analysts say will cement the automaker’s EV push.                                 , The 2024 Chevrolet Silverado EV RST is shown in Detroit, Wednesday, Jan. 5, 2022. (AP Photo/Paul Sancya) ((AP Photo/Paul Sancya / AP Newsroom)                                                                                               , Barra described the debut as the "tipping point of electrification" for the brand and the automaker.                                                                                                                                         , Wedbush analyst Dan Ives said the vehicle is "kicking off a renaissance of growth for GM with 2022 a pivotal year ahead as this green tidal wave plays out globally." He is forecasting shares can rise to $100 in the next 12 months.       , "This is not your grandfather's GM. We believe the GM EV transformation story heading into 2022 is slowly starting to get recognized by the Street as we believe a EV driven re-rating is now in process."                                   , Of the 24 analysts that cover the stock, 21 rate shares a strong buy or buy, while 3 recommend holding it, as tracked by Refinitiv.                                                                                                          , GM will begin accepting preorders for the vehicle today which runs about $105,000.                                                                                                                                                           , The rollout comes one day after rival Ford said it will double production of its electric Ford 1-50 Lightning and after Tesla reported record fourth-quarter deliveries of 308,600 vehicles, pushing its full-year total to 936,172 globally.,   (REUTERS/Rebecca Cook/File Photo / Reuters Photos)                                                                                                                                                                                         ,   (David Paul Morris/Bloomberg via Getty Images / Getty Images)                                                                                                                                                                              , The automaker's Model 3/Y led the deliveries in the quarter, topping 296,850.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-01-06 00:48:00 </td>
   <td style="text-align:left;"> The FTSE MIB at 13-Year Highs </td>
   <td style="text-align:left;"> The FTSE MIB advanced 0.7% to close at 28,163 on Wednesday, the highest in 13 years, supported by automakers while investors weighed on promising economic data. Domestic consumer inflation was at 3.9% in December, according to preliminary estimates, while Italian IHS Services PMI came below expectations at 53. On the corporate front, Iveco Group extended its rebound to gain 6.2% and surpass its IPO for the first time after falling 10.2% on its first trading day. At the same time, Pirelli (5.3%) booked gains after having its recommendation upgraded by JPMorgan. In the meantime, Telecom Italia rose 2.7% on news that its board of directors is working on a new industrial plan, contemplating on a potential spin-off of its fixed network assets while assessing US private equity firm KKR &amp; Co’s takeover bid of USD 33 billion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-01-06 00:47:00 </td>
   <td style="text-align:left;"> European Stocks Close at Record Levels </td>
   <td style="text-align:left;"> European equity markets closed at a fresh record level on Wednesday, led by gains in automakers such as Renault, Daimler and Stellantis as investors pile into cheaper sectors amid the prospects of higher interest rates. Stellantis received an extra boost after it was revealed it will partner with Amazon to develop cars and trucks. Also, German carmaker BMW announced record sales of over 2.2 million units from its BMW branch last year, despite the effects of the global semiconductor chip shortage. On the data front, services PMI readings in European countries fell in December amid the reintroduction of COVID-19 restrictions, while French consumer morale was at its highest in three months in December. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-01-06 00:46:00 </td>
   <td style="text-align:left;"> The CAC 40 Index Extends Record Close </td>
   <td style="text-align:left;"> The CAC 40 Index closed 0.8% higher at a record-setting 7,376, while reaching the intra-day high of 7,385 on Wednesday, as investors welcomed a batch of promising economic data. French consumer confidence for December came at 100 points, beating market forecasts of 97, while the ADP report pointed to the most jobs being added by US private businesses in seven months during December. On the corporate front, the automotive sector gained the most, led by Renault (5.3%) after the semiconductor giant Qualcomm signed several agreements with the auto-manufacturer over the supply of semiconductor chips, momentarily easing worries of supply shortages. At the same time, Carrefour jumped 5.1% following reports that Auchan is considering another takeover bid over the French rival, after their earlier bid failed in October. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/currency </td>
   <td style="text-align:left;"> 2022-01-06 00:35:28 </td>
   <td style="text-align:left;"> British Pound Hits 8-week High </td>
   <td style="text-align:left;"> GBPUSD increased to a 8-week high of 1.3568 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/sugar </td>
   <td style="text-align:left;"> 2022-01-06 00:31:03 </td>
   <td style="text-align:left;"> Sugar Hits 21-week Low </td>
   <td style="text-align:left;"> Sugar decreased to a 21-week low of 18.36 USd/Lbs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/euro-area/stock-market </td>
   <td style="text-align:left;"> 2022-01-06 00:30:09 </td>
   <td style="text-align:left;"> Euro Stoxx 50 Hits 6-week High </td>
   <td style="text-align:left;"> EU50 increased to a 6-week high of 4395 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mexico/currency </td>
   <td style="text-align:left;"> 2022-01-06 00:29:00 </td>
   <td style="text-align:left;"> Peso Strengthens to Start 2022 </td>
   <td style="text-align:left;"> The Mexican peso strengthened to 20.4 per USD in the first week of January, the strongest since early November, tracking a rise in oil prices and a recovery in risk appetite as traders hope omicron disruptions will not derail growth. Meanwhile, the central bank of Mexico is expected to continue to hike interest rates as inflation shocks persist. The inflation hit a 20-year high of 7.37% in November, well above the Banxico target of 3% plus or minus one percentage point. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/currency </td>
   <td style="text-align:left;"> 2022-01-06 00:25:00 </td>
   <td style="text-align:left;"> South African Rand Strengthens </td>
   <td style="text-align:left;"> The South African rand was trading around 15.8 against USD in early January, its highest since December 28th, as the dollar lost some ground before the release of the Federal Reserve's minutes of its last policy meeting, which could provide clues on the US central bank's plan on interest rate hikes. Meanwhile, concerns over South Africa's economic outlook due to the ongoing uncertainty around the Omicron variant limited further gains. At the same time, persistent electricity supply constraints and the slow implementation of pro-growth and investment structural reforms by the South African government remain the key risks to the country's recovery from a very challenging pandemic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-06 00:23:14 </td>
   <td style="text-align:left;"> Japan 10Y Bond Yield Hits 9-week High </td>
   <td style="text-align:left;"> Japan 10 Year Government Bond Yeld increased to a 9-week high of 0.097% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-01-06 00:23:06 </td>
   <td style="text-align:left;"> WTI Crude Extends Gains to 6-Week High </td>
   <td style="text-align:left;"> WTI crude futures rose to a six-week high above $78 per barrel on Wednesday, extending a 1.2% gain in the previous session as US oil inventories declined for the sixth consecutive week and OPEC+ agreed to maintain a steady pace in raising supply in a sign of optimism for demand in 2022. The EIA Petroleum Status Report showed US crude oil inventories fell by 2.144 million barrels in the last week of 2021, a sixth consecutive period of declines but below market forecasts of a 3.283 million drop. The report also showed gasoline stocks rose by 10.128 million barrels, the most since April 2020 and well above market expectations of a 1.775 million increase, raising concerns of declining demand in the world’s biggest consumer amid a surge in Covid cases caused by the fast-spreading omicron variant. On Tuesday, major oil producers said they would increase oil output by 400,000 barrels per day in February as they see a mild and short-lived impact on fuel demand from the omicron variant. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-06 00:21:13 </td>
   <td style="text-align:left;"> Australia 10Y Bond Yield Hits 5-week High </td>
   <td style="text-align:left;"> Australia 10 Year Government Bond Yeld increased to a 5-week high of 1.808% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-06 00:08:00 </td>
   <td style="text-align:left;"> Brazil 10Y Bond Yield Near 1-Month High </td>
   <td style="text-align:left;"> Brazil's 10-year government bond yield traded above 11% in early January, its highest since December 6th, tracking a rebound in international government bond yields amid looming interest rates increases by the US Federal Reserve to curb strong inflationary pressures. At the same time, investors bet that the Omicron variant will not derail a global economic recovery, despite the massive spike in infections, amid further evidence that is less severe than other strains. Domestically, Brazil's economic outlook remains clouded by high inflation and the prospect of rising interest rates, elevated unemployment, as well as fiscal and political concerns ahead of presidential elections in October. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gasoline </td>
   <td style="text-align:left;"> 2022-01-06 00:06:00 </td>
   <td style="text-align:left;"> Gasoline Firm at 6-Week High </td>
   <td style="text-align:left;"> US gasoline futures climbed to a six-week high near $2.3 per gallon at the beginning of 2022, tracking crude futures higher as investors welcomed the OPEC+ output increase agreement in a sign of optimism for demand in 2022. The oil producing nations agreed to the expected 400,000 bpd output increase in February, as they have done each month since August. Meanwhile, government data showed US gasoline output fell by 1.61 million barrels in the last week of 2021, whilst gasoline stockpiles expanded much more than expected. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/gasoline-stocks-change </td>
   <td style="text-align:left;"> 2022-01-05 23:58:56 </td>
   <td style="text-align:left;"> US Gasoline Stocks Post Biggest Rise in 8 Months </td>
   <td style="text-align:left;"> US gasoline stocks rose by 10.128 million barrels in the week ending December 31st, the most since April 2020 and well above market expectations of a 1.775 million increase raising concerns of declining demand in the world’s biggest consumer amid a surge in Covid cases caused by the fast-spreading omicron variant. Meanwhile, crude oil stocks fell by 2.144 million barrels in the week ending December 31st, a sixth consecutive period of declines and compared with market forecasts of a 3.283 million drop. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/crude-oil-stocks-change </td>
   <td style="text-align:left;"> 2022-01-05 23:52:00 </td>
   <td style="text-align:left;"> US Crude Stocks Fall for 6th Week </td>
   <td style="text-align:left;"> US crude oil inventories fell by 2.144 million barrels in the week ending December 31st, a sixth consecutive period of declines and compared with market forecasts of a 3.283 million drop, data from the EIA Petroleum Status Report showed. Meanwhile, gasoline inventories surged by 10.128 million barrels, the most since April 2020 and much more than market expectations of a 1.775 million increase. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/soybeans </td>
   <td style="text-align:left;"> 2022-01-05 23:37:51 </td>
   <td style="text-align:left;"> Soybeans Hover at 5-Month High </td>
   <td style="text-align:left;"> Soybean futures traded around $13.8 per bushel, the highest in near five months amid supply worries due to forecasts of hot and dry weather in Argentina and southern Brazil. Meanwhile in northern Brazil precipitation slowed down early harvest. Consultancy StoneX forecast Brazil's soybean crop at 134.0 million tonnes, below 145.1 million in December. Elsewhere, investors await a batch of US Department of Agriculture reports due on January 12th, including updated US 2021 crop production figures, as well as December 1st quarterly stocks and updated South American crop estimates. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/currency </td>
   <td style="text-align:left;"> 2022-01-05 23:28:38 </td>
   <td style="text-align:left;"> Russian Ruble at 8-Month Low </td>
   <td style="text-align:left;"> The Russian ruble slipped past the 75.5 mark against the dollar, the lowest in over eight months amid geopolitical concerns. President Joe Biden told Ukraine's President Volodymyr Zelenskiy the US and its allies will "respond decisively" if Russia further invades Ukraine. The ruble is more than 8.5% below its 16-month high of 69.3 touched on October 26th on Western concerns over possible Russian military intervention in Ukraine. On the monetary policy front, officials in Russia raised rates by 100bps during its December meeting to curb inflation and left the door open to further hikes. Trading activity is expected to remain low this week and recover to regular levels after January 10th, the end of Russia's New Year holidays. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/china-mobile-flat-opening-shanghai-market </td>
   <td style="text-align:left;"> 2022-01-05 23:28:36 </td>
   <td style="text-align:left;"> China Mobile records flat opening on Shanghai market after raising China's largest IPO in over a decade </td>
   <td style="text-align:left;"> International Assets Advisory CEO Ed Cofrancesco and host of 'The Bubba Show,' Todd "Bubba" Horwitz discuss their top stock picks to invest in 2022 on 'The Claman Countdown'                                                                                                                                                                                                                                           , China Mobile’s opening day on the Shanghai market saw a strong rise and eventual flat close after raising the largest IPO on the Chinese stock market in over a decade.                                                                                                                                                                                                                                                 , The communications company raised around $8.78 billion, but a quick 10.4% opening rally ended up falling back over the course of the day. The stock ended up close to its opening value by the close of day.                                                                                                                                                                                                            , Supported by the growing economic and business development of China, the Shanghai Stock Exchange has grown to be one of the largest stock exchanges in the world. (iStock / iStock)                                                                                                                                                                                                                                     , The additions of the China Mobile, China Unicom and China Telecom stocks lifted the Shanghai Stock Exchange above Hong Kong as one of the world’s busiest IPO venues, South China Morning Post reported.                                                                                                                                                                                                                , TESLA ACTIVISTS CALL FOR CHINA SHOWROOM CLOSURE                                                                                                                                                                                                                                                                                                                                                                         , China Mobile, which is the largest mobile network operator by total subscribers, sold around 972.6 million new shares, including an over-allotment, at a price of 57.58 yuan a share in late December, making it the second-largest IPO in 2021.                                                                                                                                                                        , The company’s shares on the Hong Kong market also rose after announcing the move to the mainland stock market.                                                                                                                                                                                                                                                                                                          , CHINA ACCUSES WALMART OF ‘STUPIDITY AND SHORTSIGHTEDNESS’ AMID CLAIMS IT PULLED XINJIANG PRODUCTS                                                                                                                                                                                                                                                                                                                       , Beijing needed the stock to perform on its debut as a way to show that China could accommodate its own companies on its own exchanges, author Nina Xiang told the BBC.                                                                                                                                                                                                                                                  , "It's important for Beijing to ensure this listing appears successful and smooth to prove that China has the wherewithal to accommodate its own companies on its own stock exchanges," Xiang" author of US-China Tech War, explained. "But it won't be great for Chinese companies to lose the access to the US capital markets as it will be another step in the downward spiral of deteriorating bilateral relations.", GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                             , China Mobile departed the New York Stock Exchange (NYSE) after it was added to the U.S. investment blacklist, which bans Americans from investing in Chinese companies that allegedly aid Chinese military, intelligence and security services.                                                                                                                                                                         , Other blacklisted companies include SenseTime Group inc. and China Telecom, The Wall Street Journal reported.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/baltic </td>
   <td style="text-align:left;"> 2022-01-05 23:24:00 </td>
   <td style="text-align:left;"> Baltic Exchange Dry Index Edges Up </td>
   <td style="text-align:left;"> The Baltic Exchange Dry Index went up 0.2% to 2,289 on Wednesday, its highest since December 21st and extending gains for a second straight session, as the panamax index which tracks cargoes of about 60,000 to 70,000 tonnes of coal and grains, surged 4.5% to 3,003. Meanwhile, the capesize index, which tracks iron ore and coal cargos of 150,000-tonnes, fell 2.1% to 2,301, its lowest level since late-March, 2021. Also, the supramax index slipped 44 points to its lowest level in over a month at 2,165. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-01-05 23:16:23 </td>
   <td style="text-align:left;"> Toronto Stocks Edge Up, Oil &amp; Miners Lead </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, edged up on Wednesday,as higher oil and gold prices helped lift the heavyweight energy (+2.3%) and material (+0.5%) sectors. On the other hand, tech stocks  (-1.8%) limited overall gains, in line with the US Nasdaq index. Meanwhile, investors wait to gauge the US Fed’s minutes later in the day to look for clues on the interest rate hike outlook of the world’s largest economy for the year ahead. On the data front, the value of building permits in Canada advanced by 6.8% mom to a record C$11.2B in November of 2021, easily beating market forecasts of a 2.3% gain. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/silver </td>
   <td style="text-align:left;"> 2022-01-05 23:16:04 </td>
   <td style="text-align:left;"> Silver Rises for 2nd Session </td>
   <td style="text-align:left;"> Silver rose for the second session to above $23 per troy ounce, in line with gold supported by rising Omicron cases and as the dollar eased ahead of the FOMC minutes. Last year, silver booked its first yearly decline since 2018 amid reduced industrial demand and expectations of higher interest rates. The Federal Reserve is set to end pandemic-era asset purchases in March 2022 and hike interest rates three times next year amid low unemployment and high inflation; while the Bank of England unexpectedly hiked rates citing mounting inflationary pressures, following its peers in Norway, Brazil, Mexico, South Korea and New Zealand. At the same time, the global economic recovery from the 2020 health crisis is facing mounting headwinds and factory activity weakened due to global production bottlenecks, energy shortages and the new Omicron variant. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/bulgaria/stock-market </td>
   <td style="text-align:left;"> 2022-01-05 23:16:02 </td>
   <td style="text-align:left;"> Stocks in Bulgaria Hit 3-year High </td>
   <td style="text-align:left;"> SOFIX increased to a 3-year high of 643.67 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/media/2022-year-of-the-raise-workers-upper-hand-dan-roccato </td>
   <td style="text-align:left;"> 2022-01-05 23:09:10 </td>
   <td style="text-align:left;"> 2022 is the year of the raise and workers getting the ‘upper hand,’ personal finance expert says </td>
   <td style="text-align:left;"> Credible.com personal finance expert Dan Roccato encourages workers to know their market value.                                                                                                                                                                          , 2022 is shaping up to be the year of the raise.                                                                                                                                                                                                                          , Credible.com personal finance expert Dan Roccato said he believes workers have the "upper hand" when asking for a raise this year, on "Mornings with Maria" Wednesday.                                                                                                   , "Maybe some of us haven't looked for a job in a while, so now might be a great time to understand exactly what it is that the market is valuing this job at," Roccato told FOX Business’ Dagen McDowell.                                                                 , American workers are in line to receive one of the biggest pay raises in more than a decade, according to a Conference Board survey released last month.                                                                                                                 , U.S. WORKERS POISED TO GET BIGGEST RAISE IN A DECADE AS INFLATION SOARS                                                                                                                                                                                                  , Companies are reportedly setting aside an average of 3.9% of total payroll for wage increases, which Roccato says is "good news" for the average worker.                                                                                                                 , "Know [your] market value," Roccato said. "Be open to some new responsibilities, maybe a new role in the company."                                                                                                                                                       , Roccato warned against blaming inflation for a pay raise, noting it’s likely a "bad conversation" to have with your boss.                                                                                                                                                , Billboard on the cruelties of inflation in Coon Rapids, Minnesota. (Universal Images Group via Getty Images / Getty Images)                                                                                                                                              , "We want to focus on our contributions to the company," Roccato explained.                                                                                                                                                                                               , Most importantly, he pointed out, workers should have another job opportunity lined up before formally discussing a raise.                                                                                                                                               , "If you're going to have that talk, be prepared to walk, right? So you don't want to just call the bluff," he said. "If you're really going to have that conversation, be prepared to bail."                                                                             , Higher inflation has shown no signs of slowing down, increasing the need for employers to give workers a bigger cost-of-living adjustment.                                                                                                                               , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                              , Credible.com personal finance expert Dan Roccato on readying for a raise this year.                                                                                                                                                                                      , In this scenario of high inflation and a tight labor market, wages are expected to continue rising, with growth remaining well above 4% through 2022. Wages for new hires, and workers in blue-collar and manual services jobs, are expected to grow faster than average., "We're losing ground when it comes to the cost of living," Roccato said. "It may be time to reassess: Am I in the right job? Am I in the right field? Maybe there's something else I can and should be doing to increase my take-home pay."                              , READ MORE FROM FOX BUSINESS                                                                                                                                                                                                                                              , FOX Business’ Megan Henney contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gold </td>
   <td style="text-align:left;"> 2022-01-05 23:08:00 </td>
   <td style="text-align:left;"> Gold Climbs on Omicron Worries </td>
   <td style="text-align:left;"> Gold gained as much as 0.6% to $1,825 an ounce on Wednesday, approaching levels not seen in near seven weeks as investors weighed a rise in treasury yields against surging Covid infections globally. The US set a global record on Monday, reporting almost 1 million new coronavirus infections, according to a Reuters tally. Meanwhile, the benchmark 10-year US yield was around 1.65%, near a 6-week high as markets stepped up bets that the Fed will raise interest rates in March, soon after it completes tapering its asset-buying. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/composite-pmi </td>
   <td style="text-align:left;"> 2022-01-05 22:59:59 </td>
   <td style="text-align:left;"> US Private Sector Activity Expands Solidly in December </td>
   <td style="text-align:left;"> The IHS Markit US Composite PMI came in at 57.0 in December 2021, little-changed from a preliminary estimate of 56.9 and November's final reading of 57.2. The latest data signaled a steep increase in private sector business activity, mainly driven by strong growth in the service sector. New order growth was the quickest for five months, while the pace of job creation slowed to only a marginal rate, amid challenges hiring suitable workers and retaining current staff. Finally, input cost inflation hit a fresh series high in December, boosted by input shortages, transportation delays and upticks in labor costs, while selling prices also rose steeply. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/services-pmi </td>
   <td style="text-align:left;"> 2022-01-05 22:54:00 </td>
   <td style="text-align:left;"> US Service Sector Growth Remains Solid </td>
   <td style="text-align:left;"> The IHS Markit US Services PMI stood at 57.6 in December 2021, little-changed from a preliminary estimate of 57.5 and below November's 58.0. The latest reading signaled a sharp upturn in service sector business activity, despite the pace of growth easing to a three-month low, helped by strong client demand. New order growth quickened to the fastest since July, amid customer acquisitions and contract gains, while the pace of job creation was only marginal and the slowest for three months due to labor shortages and difficulties retaining workers. Meanwhile, backlogs of work continued to rise sharply. On the price front, input cost inflation hit a new all-time high on the back of soaring wage bills and greater supplier prices. The rate of charge inflation eased, but remained close to October's record. Finally, business confidence was the strongest since November 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-01-05 22:43:00 </td>
   <td style="text-align:left;"> Brazilian Equities Fall for 3rd Day </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Bovespa, fell 0.8% to around 102,700 on Wednesday, extending losses for a third straight session to the lowest level since December 1st, amid expectations of rising interest rates ahead of the release of minutes from the Federal Reserve's December meeting. Domestically, former finance minister Guido Mantega was nominated by Lula da Silva, currently in first place in polls on the presidential dispute, to represent him in an article published today in Folha de São Paulo as economic spokesperson. Mantega painted a grim outlook for the Brazilian economy in 2022, blaming years of mismanagement under the governments of Michel Temer and Jair Bolsonaro, which left the country vulnerable to a shock like the Covid-19 pandemic. On the data front, a PMI survey showed Brazil's private sector growth stood at a 6-month low in December. Among single stocks, the retail sector and banks were leading the losses. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-01-05 22:36:26 </td>
   <td style="text-align:left;"> Dow Breaks Another Record, S&amp;P and Nasdaq Fall </td>
   <td style="text-align:left;"> The Dow Jones extended records for a 3rd straight session on Wednesday while both the S&amp;P 500 and the Nasdaq traded in the red, with soaring Treasury yields pressuring the tech sector. All eyes turn to the FOMC minutes release later in the day after the Fed announced it would end its pandemic-era bond purchases in March, paving the way for three interest rate hikes by the end of 2022. Meanwhile, the ADP report showed private businesses in the US added the most jobs in 7 months in December. On the corporate front, shares of Pfizer gained more than 2% after the Bank of America upgrade the stock to “buy” from “neutral” while Microsoft shares (-1.7%) were among the worst performs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/composite-pmi </td>
   <td style="text-align:left;"> 2022-01-05 22:28:46 </td>
   <td style="text-align:left;"> Brazil Private Sector Growth Steady </td>
   <td style="text-align:left;"> The IHS Markit Brazil Composite PMI remained steady from the prior month at 52 in December of 2021, the seventh straight month of expansion in the country’s private sector, albeit the slowest. Growth was supported by the services sector (PMI unchanged from November at 53.6), offsetting the contraction in manufacturing (PMI unchanged at 49.8). Aggregate new orders quickened in Brazil’s private sector, marked by a sharp upturn in work intakes for the services sector while factory orders fell for the third month in a row. At the same time, job creation expanded at a softened pace for both sector levels, with services leading the growth. On the price front, input prices were more pronounced among manufacturers due to higher energy costs and a weaker currency. Lastly, forecasts for both sectors point to increased output in 2022 should the pandemic continue to decrease and vaccine outreach continue to improve in Brazil. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/building-permits </td>
   <td style="text-align:left;"> 2022-01-05 21:39:00 </td>
   <td style="text-align:left;"> Canada Building Permits Rise More than Expected </td>
   <td style="text-align:left;"> The value of building permits in Canada advanced by 6.8 percent month-over-month to CAD 11.2 billion in November of 2021, the highest value ever recorded, following an upwardly revised 2.4 percent increase in October and well above market estimates of a 2.3 percent increase. Construction intentions in the residential sector rose 12 percent to CAD 7.8 billion, the highest increase since the record in March 2021, led by a 20.2 percent jump in multiple-family units to CAD 4.3 billion and a 3.3 percent rise in single-family units to CAD 3.5 billion. Meanwhile, permits in the non-residential sector declined 3.2 percent to CAD 3.4 billion, as a 49.2 percent decline in institutional units to CAD 0.61 billion offset a 45.1 percent jump in industrial units to CAD 0.69 billion. Among Canada’s major provinces, Alberta (20.6 percent to CAD 1.32 billion) contributed the most to the overall increase. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/services-pmi </td>
   <td style="text-align:left;"> 2022-01-05 21:21:00 </td>
   <td style="text-align:left;"> Brazil Service Sector at Steady Expansion in December </td>
   <td style="text-align:left;"> The IHS Markit Brazil Services PMI remained steady at 53.6 in December of 2021 pointing to the seventh successive month of expansion in the services sector, linked to continued progress in vaccine distribution and easing in pandemic-related restrictions. The upturn in sales supported output growth, brought by a recovery in international demand. New export business expanded for the first time in four months and at the third-fastest rate since 2014. New work intakes also expanded, from the release of pent-up demand from the pandemic. The ongoing business also encouraged hiring, sustaining employment growth and improving capacity, as service providers reported clearer backlogs of work. On the price front, both input and output costs rose at the slowest rate in five months. Looking forward, business sentiment for 2022 remains positive, amid expectations of higher vaccination rates and a further easing in restrictions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/adp-employment-change </td>
   <td style="text-align:left;"> 2022-01-05 21:20:00 </td>
   <td style="text-align:left;"> US Companies Add the Most Jobs in 7 Months: ADP </td>
   <td style="text-align:left;"> Private businesses in the United States hired 807K workers in December of 2021, the most in 7 months and more than double market forecasts of 400K, as the fallout from the Delta variant faded and Omicron’s impact had yet to be seen. Hiring was broad-based, though leisure and hospitality led with 246K new jobs. A significant number of jobs were also created in trade, transportation and utilities (138K), professional and business services (130K), education and health services (85K),  manufacturing (74K) and construction (62K). Large companies hired the most (389K), followed by midsized (214K) and small (204K). "December’s job growth brought the fourth quarter average to 625,000, surpassing the 514,000 average for the year. While job gains eclipsed 6 million in 2021, private sector payrolls are still nearly 4 million jobs short of pre-COVID-19 levels”, said Nela Richardson, chief economist, ADP. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/30-year-bond-yield </td>
   <td style="text-align:left;"> 2022-01-05 21:11:54 </td>
   <td style="text-align:left;"> Australia 30Y Bond Yield Hits 6-week High </td>
   <td style="text-align:left;"> Australia 30 Year Government Bond Yeld increased to a 6-week high of 2.534% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/05/kevin-oleary-on-why-he-thinks-nfts-will-become-bigger-than-bitcoin.html </td>
   <td style="text-align:left;"> 2022-01-05 21:06:52 </td>
   <td style="text-align:left;"> Kevin O'Leary explains why he thinks NFTs will become bigger than bitcoin </td>
   <td style="text-align:left;"> , "Shark Tank" investor Kevin O'Leary is a big believer in non-fungible tokens — he even thinks they have a shot at becoming bigger than bitcoin.                                                                                                                                                                                                                       , O'Leary, the chairman of O'Shares Investment Advisers, said his belief in NFTs stems from the idea that can they prove ownership of real-world items, such as designer watches or flash cars, digitally rather than with paper records.                                                                                                                               , NFTs are one-of-a-kind crypto tokens that serve to track the provenance and authenticity of rare virtual collectible items such as art and sports memorabilia. There have also been efforts to bring NFTs to physical assets.                                                                                                                                         , "You're going to see a lot of movement in terms of doing authentication and insurance policies and real estate transfer taxes all online over the next few years, making NFTs a much bigger, more fluid market potentially than just bitcoin alone," O'Leary told CNBC's "Capital Connection" Wednesday.                                                              , "We'll see what happens but I'm making that bet and I'm investing on both sides of that equation."                                                                                                                                                                                                                                                                    , Barely anyone had heard of NFTs in 2020, but they became a huge phenomenon the following year. More than $20 billion worth of the tokens changed hands throughout 2021, according to some estimates. The trend gained particular public attention after a collage by the digital artist Beeple, whose real name is Mike Winkelmann, was sold for a record $69 million., However, there are concerns about the sustainability of the market. Some have compared it to the initial coin offering frenzy of 2017, which saw several investors get defrauded by betting on start-ups through unregulated token sales. Meanwhile, there have been a number of scams and instances of stolen art, raising red flags for some traders.               , The millionaire Canadian investor has changed his tune on crypto over the years, having previously called bitcoin "garbage."                                                                                                                                                                                                                                          , "It is a useless currency," O'Leary told CNBC's "Squawk Box" in May 2019. "It's worthless."                                                                                                                                                                                                                                                                           , More recently, O'Leary has warmed to the space, viewing it as a way of diversifying from other assets such as real estate amid rising inflation. He is particularly bullish on "decentralized finance," a trend that aims to replicate traditional financial products using blockchain.                                                                               , O'Leary recently disclosed that his largest position is in ether, while he also owns some polygon, solana and bitcoin.                                                                                                                                                                                                                                                , Around 40% of new checks O'Leary has written in the last six months were for crypto and blockchain-related ventures.                                                                                                                                                                                                                                                  , O'Leary stressed the importance of ensuring crypto becomes regulated. Regulators in the U.S. and elsewhere are racing to catch up with developments in the market to prevent potential money laundering and protect consumers from financial harm.                                                                                                                    , "Different geographies have different policy regarding crypto," O'Leary said. "You have to go and find jurisdictions that are more progressive."                                                                                                                                                                                                                      , He cited Canada, his home country, as an example of a jurisdiction that is more progressive than others on the issue of crypto.                                                                                                                                                                                                                                       , Canada was the first to approve an exchange-traded fund that gives investors exposure to bitcoin. Though the U.S. Securities and Exchange Commission has since greenlit a bitcoin-linked ETF, the product tracks futures contracts instead of investing in bitcoin directly.                                                                                          , O'Leary also cited the United Arab Emirates and Switzerland as other countries that are opening up to crypto.                                                                                                                                                                                                                                                         , "You have to be optimistic and constructive," O'Leary said. "The floodgate of capital will come in through sovereign and pension plans that doesn't exist yet."                                                                                                                                                                                                       , Of particular concern to regulators are stablecoins, digital tokens pegged to the value of sovereign currencies like the dollar. Economists worry notable stablecoins like tether and USD Coin may not have the appropriate reserves available to justify their claims of being backed by dollars.                                                                    , "I think [stablecoins] will also get a chance to shine in the sun as a great way to get yield when you can't get any yield on cash," O'Leary said.                                                                                                                                                                                                                    , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                      , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                      , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                    , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-01-05 21:04:00 </td>
   <td style="text-align:left;"> WTI Crude Breaks Above $78 after OPEC+ Decision </td>
   <td style="text-align:left;"> WTI crude futures rose to above $78 per barrel on Wednesday, extending a 1.2% gain in the previous session after OPEC+ agreed to increase oil output by 400,000 barrels per day in February as major oil producers see a mild and short-lived impact on fuel demand from the omicron variant. Meanwhile, the American Petroleum Institute reported US crude inventories fell by 6.43 million barrels last week while gasoline stockpiles rose by 7.1 million barrels, raising concerns of declining demand in the world’s biggest oil consumer amid a surge in Covid cases caused by the fast-spreading omicron variant. </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2022-01-06 10:07:06 UTC +8

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
   <td style="text-align:left;"> 2022-01-06 10:06:43 </td>
   <td style="text-align:left;"> $BTC.X $SPY Fed be like 👇🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 10:06:21 </td>
   <td style="text-align:left;"> $SPY $ARKK heres the queen fool… BTFD 

https://www.cnbc.com/2022/01/05/cathie-wood-begins-2022-where-she-left-off-last-year-buying-the-dip-in-her-favorite-stocks.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 10:06:18 </td>
   <td style="text-align:left;"> $SPY so our mayor likes to blow dudes. He is laying off police, firemen, city planners, engineers etc. our beloved city is going to shit! We need 900 more, not 900 less! This isn’t nazi Germany here! What are we doing?!!! Do you know how long it takes to pull permits already? 8-12 months! STOP VOTING LEFT! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 10:05:40 </td>
   <td style="text-align:left;"> $SPY part of me thinks all the growth bs won’t stop until game stop goes back to where it belongs.  7

And amc is 3-4.  Then all this garbage will stop  maybe.    How many stocks will do reverse splits and get delisted is the question. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 10:05:36 </td>
   <td style="text-align:left;"> $SPY net worth of top 1% is double the monetary supply AKA it is all speculation. think for 1 second. it is not possible for ANY company or person to own the entire supply of money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 10:05:25 </td>
   <td style="text-align:left;"> $SPY how come no news story’s on the new covid “ihu” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 10:05:13 </td>
   <td style="text-align:left;"> $SPY   so much destruction out there ha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 10:04:25 </td>
   <td style="text-align:left;"> $SPY no politicians bearish but y’all think crash coming lol

New guys are hilarious </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 10:04:18 </td>
   <td style="text-align:left;"> $SPY when everyone thinks it is over for the dollar that is when the dollar gains value. reckless debts made, consequences to be had </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 10:03:58 </td>
   <td style="text-align:left;"> $SPY 

None of the major institutions are going to be accumulating a ton of shares, knowing that we&amp;#39;re about to taper and possibly even raise rates.  It&amp;#39;s a bearish nightmare that everyone knows about well in advance.

And when you consider the sheer amount of buying that led us to this point, where we are now, that&amp;#39;s a lot of selling that needs to happen.  It wouldn&amp;#39;t surprise me if they&amp;#39;re starting early. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 10:03:58 </td>
   <td style="text-align:left;"> $SPY Where all the bulls at tonight yall die? Lmao. Futures aren’t even bad yet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 10:03:57 </td>
   <td style="text-align:left;"> $SPY In the recent reporting quarter: 5 institutions increased their position, while 7 decreased https://insider-analysis.com/search_whales.php?ticker=TABLE_SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 10:03:47 </td>
   <td style="text-align:left;"> $SPY I been saying since august spy wouldn’t see a sell off until right around when 200 was at 440. Guess what? And no. It won’t drop to the 200 IMO. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 10:03:45 </td>
   <td style="text-align:left;"> $SPY people see the s&amp;amp;p 500 as a safe investment because of diversity, the FED pumping it and millions of Americans pumping bi-weekly paychecks into a retirement account. But anyone that looks at the chart can see that we have massive gaps in the $200 and change area as it recovered from coronavirus Lows. This went up too fast and it needed a correction last year and instead we rallied the entire year. We had a lot of new investors that came in the market with margin and they have been pumping this left and right at all time highs. No one knows where this is going but this is a dangerous place to invest your money especially at this all-time high prices. This idea that we have to the market always goes higher may come to an end very soon and we might not see another new time high for a very long time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 10:03:40 </td>
   <td style="text-align:left;"> $SPY Santa rally coming just wait 🥴😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 10:03:37 </td>
   <td style="text-align:left;"> $BTC.X $SPY $ETH.X Are you buying the dip on stocks or crypto? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 10:03:26 </td>
   <td style="text-align:left;"> $SPY Like always: Panic Panic! The big crash is here! Get ready mzcuckers it&amp;#39;s coming!... waiting.. wating.. and nothing again. Peace and quiet, buy again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 10:03:26 </td>
   <td style="text-align:left;"> $SPY BEAR FLAGGING GONNA DUMP SOON </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 10:02:51 </td>
   <td style="text-align:left;"> $SPY  a little pop in the am then more blood </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 10:02:42 </td>
   <td style="text-align:left;"> $spy

To easy 🤑🤑🤑

Hope to see you in my inbox wanting to join the team🙏🙏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 10:02:12 </td>
   <td style="text-align:left;"> $SPY Great sales out there, considering someone paid top solar of Apple yesterday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 10:02:11 </td>
   <td style="text-align:left;"> Going  cruise 🚢 tomorrow till Sunday .. Wont be  active much tomorrow afternoon. Wish best and some recover to all stocks Tomorrow  
$sofi $pltr $fubo $lcid $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 10:02:10 </td>
   <td style="text-align:left;"> $SPY lmfaoo just pray to God it tries to test ATH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 10:02:07 </td>
   <td style="text-align:left;"> $SPY “wE riPP’n” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 10:01:58 </td>
   <td style="text-align:left;"> $SPY spy 50%away from 200 week SMA 

Bulls may get humbled HARD this year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 10:01:32 </td>
   <td style="text-align:left;"> $SPY is there anything positive to look forward to??? Tomorrow???? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 10:01:02 </td>
   <td style="text-align:left;"> $SPY 
$465 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 10:00:38 </td>
   <td style="text-align:left;"> $SPY $SNIPF $AAPL $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 10:00:38 </td>
   <td style="text-align:left;"> $SPY I believe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 10:00:24 </td>
   <td style="text-align:left;"> $SPY feel like they are gonna try to screw both sides tomorrow. The play is theta burn. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 10:00:18 </td>
   <td style="text-align:left;"> $SPY market falls 2% because of hawkish fed statement and all the “let’s go Brandon” people come out of the woodwork. Being the president is not a job for 99% of people.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 10:00:10 </td>
   <td style="text-align:left;"> $SPY bears lost during Santa Claus rally back for round 2. Watch them disappear when we close green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 10:00:05 </td>
   <td style="text-align:left;"> $SPY

 $DAX hasn’t even begun to correct.  Dip buyers are too early. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:59:56 </td>
   <td style="text-align:left;"> $SPY i guess i&amp;#39;ll short here with rates at 0. They were 21%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:59:56 </td>
   <td style="text-align:left;"> $SPY Thinking about buying some stocks that Cathy sells. Should work perfectly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:59:55 </td>
   <td style="text-align:left;"> $SPY $btc.x  bictoin flows  into stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:59:48 </td>
   <td style="text-align:left;"> $SPY dont worry about calls. Worry about those selling Puts. 10x losses in hours for anyone who sold calls and held today. Flat out. We will feel the ripples into NEXT WEEK. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:59:47 </td>
   <td style="text-align:left;"> $SPY if the market pumps above 500 I will be a believer until then… sideways equals trap, small magic pump candles equal trap… a solid few days of ripping lll shut up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:59:21 </td>
   <td style="text-align:left;"> $SPY who is pushing it down..? Is that due to big buys shorting this? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:59:19 </td>
   <td style="text-align:left;"> $SPY 10 year T note yields are pulling back... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:59:18 </td>
   <td style="text-align:left;"> $SPY bunch of baggies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:59:01 </td>
   <td style="text-align:left;"> $SPY 

$465 is a good taking off point. 

Biden market. Always up. Btfd </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:58:52 </td>
   <td style="text-align:left;"> $SPY i ain’t gone lie, my long term portfolio got absolutely destroyed 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:58:43 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:58:41 </td>
   <td style="text-align:left;"> $SPY knock knock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:58:39 </td>
   <td style="text-align:left;"> $SPY Lower for longer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:58:36 </td>
   <td style="text-align:left;"> $SPY maybe you can forward split the S&amp;amp;P 500 to make it look cheap .. LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:58:29 </td>
   <td style="text-align:left;"> Ticker: $SPY 
Buy: January 07, 2022 $469.00 Calls 
Entry Price: $2.42 - $2.43 
Exit Price: $2.90 
Stop Loss: $2.13 
Potential ROI: 20% 
Estimated Hold Time: 57 Minutes 
Alert Courtesy Of: https://www.fastscalp.com/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:58:12 </td>
   <td style="text-align:left;"> $SPY oiling the bear pussies again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:58:09 </td>
   <td style="text-align:left;"> $SPY Some peeps trade for extra cash, some sell fart jars. Choose wisely. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:58:07 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:57:37 </td>
   <td style="text-align:left;"> $SPY I run out of dumb shit to say…🤷🏻‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:57:16 </td>
   <td style="text-align:left;"> $SPY Gotta love the 6 day distribution at ATHs. Look at these clowns. Puts green 500% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:57:03 </td>
   <td style="text-align:left;"> $SPY wait for it….                  

FUTES ARE RIPPIN’ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:56:38 </td>
   <td style="text-align:left;"> $SPY Didn&amp;#39;t even raise rates yet they just said they will LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:56:36 </td>
   <td style="text-align:left;"> It&amp;#39;s not the signals. It&amp;#39;s the reassurance the signals work, and that...that is the strategy.  
My $SPY #OPTIONS #DAYTRADE  
screamed out a 560% gain on today&amp;#39;s  478PUT. 
#560%! 
https://thegodoftrading.medium.com/here-the-big-money-is-made-e233d164c35f 
#1Kdaytrade #daytrading  
https://thegodoftrading.medium.com/membership 
https://thegodoftrading.medium.com/subscribe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:56:13 </td>
   <td style="text-align:left;"> $SPY My barometer for bottom fishing on these oversold risk assets like Teledoc and Palantir s $ARKK. Long term support comes in there at around $62. $NVTA has looked like it wants $10 for a while. $ARKG $42? If I see there prices hit, that&amp;#39;s where I think the pain simultaneously stops for most of these beat up growth plays. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:56:05 </td>
   <td style="text-align:left;"> $SPY Lol. FED raises rates and look at you. In shambles </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:55:59 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA  In these type of market conditions ..resistance is more relevant than support. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:55:53 </td>
   <td style="text-align:left;"> $SPY bloody red ready tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:55:46 </td>
   <td style="text-align:left;"> $SPY Made so much today I&amp;#39;m taking a three day weekend starting tomorrow $$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:55:18 </td>
   <td style="text-align:left;"> $SPY Futes Tripping! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:55:00 </td>
   <td style="text-align:left;"> $SPY the economy is so strong according to Biden and the FED … do you believe that cause </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:54:43 </td>
   <td style="text-align:left;"> $SPY more blood please. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:54:40 </td>
   <td style="text-align:left;"> $SPY All in puts…
- Warren Buffett </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:54:38 </td>
   <td style="text-align:left;"> $SPY shawty trifling! She must be from dirty docks! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:54:25 </td>
   <td style="text-align:left;"> $IWM Welcome to the  &amp;quot;Last Chance exit&amp;quot;
 $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:54:22 </td>
   <td style="text-align:left;"> $SPY Tech selling off because Fed is going to Taper, raise interest rates, and unwind balance sheet all in 2022! Lol  I call BS. Businesses and schools are shutting down and hotels restaurants laying people off at a rapid pace. The Fed needs to look forward instead of backward. 

https://www.washingtonpost.com/us-policy/2022/01/05/congress-omicron-coronavirus-aid/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:54:16 </td>
   <td style="text-align:left;"> Stay the long term course it’s so worth it $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:54:01 </td>
   <td style="text-align:left;"> $SPY I missed the March 2020 circuit breaker halts . Hopefully we experience it again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:53:58 </td>
   <td style="text-align:left;"> $SPY I’m raising the rent on my rentals 10% this year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:53:42 </td>
   <td style="text-align:left;"> $EBON Congrats, best performing stock of the day. Maintained green. Proceed to $14. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:53:31 </td>
   <td style="text-align:left;"> $SPY all these covid posts are getting boring, when the market doesn’t care about it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:53:27 </td>
   <td style="text-align:left;"> $SPY 

Piggie take 5 mes long at 4699 for fun! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:52:50 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ 

hope not </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:52:48 </td>
   <td style="text-align:left;"> $SPY feelin we reject the 50MA tmrw and up from there </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:52:45 </td>
   <td style="text-align:left;"> $SPY bed time 🥱 GN 

Bear Gang 🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:52:07 </td>
   <td style="text-align:left;"> $SPY Creo que el Fed se va pasar a SPY  y sus record historicos por los COJONES y van a causar una recession con su invento de subir los intereses en estos momentos.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:52:01 </td>
   <td style="text-align:left;"> $SPY Fed injection on the overnight. 477 within minutes. Headlines are starting about how strong the economy  is that the Fed can step back and return markets to normal and lower inflation. Bring on Earnings! 480 by EOW. Friday will be tear the bear a new {•} day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:51:50 </td>
   <td style="text-align:left;"> Covid post $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:51:49 </td>
   <td style="text-align:left;"> $DOGE.X $SPY $TSLA  everything trending is red as snow! The only thing I’m glad on is I didn’t get calls on anything but I did get shares and I’ll be ok ! 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:51:46 </td>
   <td style="text-align:left;"> $SPY wonder how put selling did today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:51:34 </td>
   <td style="text-align:left;"> $SPY I think this is what warren buffet is waiting for </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:51:13 </td>
   <td style="text-align:left;"> $SPY 385.5 on KOSPI is key level for tonight. If that breaks then it&amp;#39;s waterfalls for US tmrw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:51:10 </td>
   <td style="text-align:left;"> $SPY $QQQ if we are to enter true bear market for extended time, most retailer traders would get wiped out due to options. Today’s market is running purely on option flow. Nobody is buying actual shares 99% retail traders are options </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:51:03 </td>
   <td style="text-align:left;"> $SPY no real stress to credits </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:51:01 </td>
   <td style="text-align:left;"> $SPY big dogs made so much in 2021 they already cashing in on 2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:50:52 </td>
   <td style="text-align:left;"> $SPY tomorrow could be a call buying day 

Let’s see what VIX looks like in the AM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:50:46 </td>
   <td style="text-align:left;"> $SPY FED already rolled out the bed, you better hope factory orders cool, non manuf. pmi NOT hot, and, finally, that jobs Fri. comes in laisez faire , neither hot nor cold or you&amp;#39;re in t-ruh-uhb....

Zoiks! 

But that&amp;#39;s THREE shots to avoid the silver bullet which is, make no mistake, the FED with bo choice but to end QE abruptly announced 26th and a coup de Grace will be announcing 1st rate hike either MARCH....or, God forbid, bulls, Feb. 👍👌

$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:50:45 </td>
   <td style="text-align:left;"> $SPY My body, my choice. Period! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:50:32 </td>
   <td style="text-align:left;"> $SPY Bulls are kidding themselves if they think a drop like that with such insane momentum will just rebound tomorrow. 

This isn&amp;#39;t my first rodeo.

It will be a fun day tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:50:22 </td>
   <td style="text-align:left;"> $SPY tsla held the line, nvda did not however. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:49:26 </td>
   <td style="text-align:left;"> $BTC.X years later, no one can explain the point of this shi+ to me….🤔 
 
$TSLA $SPY $QQQ $DOGE.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:49:25 </td>
   <td style="text-align:left;"> $PTON $SPY $AMD 

These are my PUTS I’m swinging into tomorrow. Do y’all think I’m winning or losing in the morning? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:49:15 </td>
   <td style="text-align:left;"> $SPY futures are all over the place will check back around midnight. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:49:05 </td>
   <td style="text-align:left;"> $SPY don&amp;#39;t fight the Fed. They are eviscerating speculative assets. The only stocks/companies that will remain are those with positive free cash flow and low debt levels. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:48:39 </td>
   <td style="text-align:left;"> $SPY Interest rates need to be at 9 percent to stop inflation at this level. The fed lost control a long time ago. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:48:32 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;m just looking for a 10 point up to start new short come on dip buyers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:48:31 </td>
   <td style="text-align:left;"> $BTC.X retail investors are so dumb they fell for all the castle-in-the-sky cryptocurrency schemes $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:48:24 </td>
   <td style="text-align:left;"> $SPY ugh.  Don’t bounce overnight after what I just saw.  Got to be kidding me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:48:23 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA CORRECTION IS HERE WHO WANTS POPCORN 🍿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:48:21 </td>
   <td style="text-align:left;"> $QQQ $SPY the only way this is getting worse is if January 6th happens again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:48:03 </td>
   <td style="text-align:left;"> $SPY I don’t understand what’s going on my head is spinning how could this happen?! I’m so shook I’m trembling I just don’t know what to do it’s down big bad hurt </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:47:48 </td>
   <td style="text-align:left;"> $SPY to all the bears who didn’t sell eod or pick up puts.. prepare for pain </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:47:44 </td>
   <td style="text-align:left;"> $SPY what time is fed minutes today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:47:37 </td>
   <td style="text-align:left;"> $SPY &amp;quot;Irrational Exuberance&amp;quot; except this time Fed is serious about hiking. 2-3 rate hikes this year and QT later. 
The dollar is essentially worthless and they need to bring more life to it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:47:18 </td>
   <td style="text-align:left;"> $SPY flutopia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:46:57 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:46:56 </td>
   <td style="text-align:left;"> $SPY kiss of death

https://www.cnbc.com/2022/01/05/jim-cramer-charts-suggest-inflation-may-cool-down-faster-than-expected.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:46:26 </td>
   <td style="text-align:left;"> $SPY 

The newbie traders, who think they&amp;#39;re experts because Powell magically enabled their profits, are about to buy every single dip on the way down.

And I&amp;#39;ll be here cheering them on. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:45:40 </td>
   <td style="text-align:left;"> $SPY put holders tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:45:24 </td>
   <td style="text-align:left;"> $SPY this government has a knack for making sure they prop up the market. Don’t bet against the Fed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:45:23 </td>
   <td style="text-align:left;"> $SPY this is why democracy doesn’t work! Only property tax paying citizens should be able to vote. When you allow everyone (including illegals vote) we have are ruled by the majority, and the majority of folks are dumb AF! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:45:03 </td>
   <td style="text-align:left;"> $SPY what everyone will watch when  they are trading fired/futures etc

10 year note and Bitcoin for hints of margin calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:44:54 </td>
   <td style="text-align:left;"> $SPY Down 2%? And you guys are losing your ducking minds? 😂 I can’t believe you stock puss bags 😂🤦🏼‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:44:46 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:44:46 </td>
   <td style="text-align:left;"> $SPY and this is why people day trade. Do you have any idea of how much money goes in and out with day trading? COVID changed the market wether you like it or not. Chop galore </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:44:40 </td>
   <td style="text-align:left;"> $SPY is that your final answer? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:44:29 </td>
   <td style="text-align:left;"> $SPY Just buy Puts throughout Jan, Feb, and March. That’s what fuels the ups. Dolts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:44:23 </td>
   <td style="text-align:left;"> $SPY Nice AH pump, but will most likely Fade away during PM and open red. Makes sense since it will Most likely Fill the lower gaps in the 60’s range©️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:43:54 </td>
   <td style="text-align:left;"> $AMC Big ape party tomorrow $SPY $GME </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:43:48 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA “Bear Stearns is fine.” - Jim Cramer 🧊🚢 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:43:39 </td>
   <td style="text-align:left;"> $spy puss bulls, tomorrow another day of wreck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:43:30 </td>
   <td style="text-align:left;"> $SPY Russell 2000 futures are dead again. Nothing changes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:43:11 </td>
   <td style="text-align:left;"> $SPY  are there really people who believe CNN is support Joe Biden?  I can&amp;#39;t figure out why you would want to pay more for everything just to support Joe Biden 
My wife was a Joe Biden supporters and she hates Trump but nowadays she could of beared the hate rather than and to save money at the grocery store </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:42:37 </td>
   <td style="text-align:left;"> $TSLA $AAPL $MSFT $QQQ $SPY Anyone holding PUTS after that 2 day massacre isn’t going to get a wink of sleep tonight, the Market always over reacts, tomorrow is going bounce HARD!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:42:12 </td>
   <td style="text-align:left;"> $SPY OK, I&amp;#39;m sorry for the joke about Joe , forgive me for saying his wiener is the size of a 5 minute nuked oscar meyer hotdog.

Wong. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:41:47 </td>
   <td style="text-align:left;"> $SPY $TSLA best trading day of my life. new daily profit record !!! tomorrow will be amazing let’s go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:41:44 </td>
   <td style="text-align:left;"> $SPY weak hands out
Lets rip bears from face down through the other end </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:41:31 </td>
   <td style="text-align:left;"> $SPY this Almost always turns around overnight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:41:25 </td>
   <td style="text-align:left;"> $SPY forget Apple Google Microsoft Amazon Facebook nvda and and. There&amp;#39;s plenty of great companies out there for good prices if this is all you know how to invest in your in for a disaster long term </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:41:20 </td>
   <td style="text-align:left;"> $SPY can we turn the money printer back on

jk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:40:44 </td>
   <td style="text-align:left;"> $SPY ok so if we can go for it a few hours I would like 👍 but not to let me do anything for the weekend if you’d rather have the tapering guess we’ll see! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:40:41 </td>
   <td style="text-align:left;"> $YM_F Yesterday, Chart of the Day video explaining the short term view. A cycle might have ended, and three waves pullback can be underway. https://www.youtube.com/watch?v=PmYooGTO_5Y. #elliottwave #trading $DJIA $SPX $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:40:37 </td>
   <td style="text-align:left;"> $SPY no one should be buying this at the price that it is it is absolutely ridiculous that people put their money for retirement here. They&amp;#39;re going to pump every single paycheck out of there harder and money when this is at all time highs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:40:20 </td>
   <td style="text-align:left;"> $SPY spce still the 🐐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:40:01 </td>
   <td style="text-align:left;"> $SPY if you just bought this last week at all time highs you got to be a complete moron. You can&amp;#39;t even stick around for a mere 5% down. And that goes to show how you bought at the wrong time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:39:54 </td>
   <td style="text-align:left;"> $SPX someone new the direction today- Damn $SPY $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:39:43 </td>
   <td style="text-align:left;"> $SPY has anyone thought about why inflation was so hard to achieve over the last 15 years?  has anyone thought about what is causing inflation today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:39:34 </td>
   <td style="text-align:left;"> Bad Day? Relax. Don&amp;#39;t Sell When You Should Be Buying https://www.youtube.com/watch?v=_j5vZCT-_2g $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:39:18 </td>
   <td style="text-align:left;"> $SPY I bet the most people that sold this today were the people that just bought this at all time highs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:39:09 </td>
   <td style="text-align:left;"> $SPY what the fuck is this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:39:07 </td>
   <td style="text-align:left;"> $SPY speaking of jobs report, how long does it take to remove the dead working age from the numbers?  Because there were A LOT in 2021.  Best part is the main cause for most was NOT covid .. I wonder if it is the vax?? 🤔🤔

https://en-volve.com/2022/01/03/oneamerica-insurance-ceo-deaths-increase-40-among-people-ages-18-64/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:38:27 </td>
   <td style="text-align:left;"> $SPY Bears making out provocatively overnight in a sick, presumptuous way. The rest of us await a real signal. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:37:54 </td>
   <td style="text-align:left;"> $SPY was almost going to send it in and hood late and after gourd.  But only held 20,000 instead of 200,000.  Just too much of a gamble to do that for me.  Goes up.  Easy to say after shoulda </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:37:29 </td>
   <td style="text-align:left;"> $SPY futes about to tear up , V shape recovery to ATH 🪀💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:37:16 </td>
   <td style="text-align:left;"> $DJIA $SPY $SPX 
Futures ripping or Futures dipping is rarely of significance for several hours yet especially if you can&amp;#39;t open or close your options until Wall St. opens. Even relatively big moves up or down before 03:00 will probably be retraced at the London open. Around 05:00 - 07:00 will usually take a direction but even that is no guarantee what will happen at the Wall St. open. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:37:13 </td>
   <td style="text-align:left;"> $SPY Is this the begining or the end of downtrend? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:37:05 </td>
   <td style="text-align:left;"> $SPY GDP vs total market cap of US stocks 

https://ycharts.com/indicators/us_total_market_capitalization </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:36:52 </td>
   <td style="text-align:left;"> $SPY Why futures are going up? Asia traders are covering. Sadly this will keep going down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:36:33 </td>
   <td style="text-align:left;"> $SPY FUTES RIPPIN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:36:21 </td>
   <td style="text-align:left;"> $SPY why is futures violently swinging. Jesus calm down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:36:07 </td>
   <td style="text-align:left;"> $SPY We alway have SNL mates. Cheer up ⬆️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:35:56 </td>
   <td style="text-align:left;"> $SPY million dollar straddles where found late weeks of December. https://www.thepesreport.com/home I post options data on my website so you can see where the big money is moving. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:35:46 </td>
   <td style="text-align:left;"> $SPY $TSLA $NVDA $MSFT epic squeeze tomorrow 😂🤣🤑❤️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:35:36 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ $AMZN $AMC ;;,, 
 
 
Account Challenge Update:~ 
Start Date: Nov 2, 2021 
Starting Balance: $1,500 
Current Balance: $96,149 
Goal: $100,000 by end of January, 2022 
Strategy: Swing Trade Options, Stocks 
 
Watch out for next play👓 discord.io/MqakycG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:35:33 </td>
   <td style="text-align:left;"> $QQQ any one with puts tonight $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:35:24 </td>
   <td style="text-align:left;"> $SPY 
My buddy who is a mortgage broker told me that Fannie Mae’s interest rate just went to 2.5% today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:35:23 </td>
   <td style="text-align:left;"> $SPY it&amp;#39;s going to open above 470, that much is certain...the question is, will it retrace full 50%? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:35:13 </td>
   <td style="text-align:left;"> $SPY …all this talk.  $SPY fell 110 points in 2020 which was a 33% drop.  Today that would be down over $150.  Can you take that? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:35:07 </td>
   <td style="text-align:left;"> $SPY most likely gonna make a trip to the 50DMA.  465 zone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:35:05 </td>
   <td style="text-align:left;"> $SPY slingshot back to 477ish or 450 after jobs ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:35:04 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:34:55 </td>
   <td style="text-align:left;"> $SPY THE FED AMBUSHED HARDWORKING RETAIL INVESTORS TODAY THEY LOVE DISRUPTIONS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:34:50 </td>
   <td style="text-align:left;"> $SPY $NQ_F lol there is that little asia bull </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:34:46 </td>
   <td style="text-align:left;"> $SPY I’m thinking January 31 455 puts at open if there is a nice cat bounce. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:34:40 </td>
   <td style="text-align:left;"> $SPY I’m Fuking worry about job report </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:34:00 </td>
   <td style="text-align:left;"> If you possess this trait, then you have what it takes to be/become a great trader/investor. Build upon it with other essential skills like risk/money management and show the world what you’re capable of. $SPY 🚀💯🌟 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:33:44 </td>
   <td style="text-align:left;"> $NVDA $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:33:38 </td>
   <td style="text-align:left;"> $SPY   I just ate many donuts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:33:37 </td>
   <td style="text-align:left;"> $SPY definitely very bearish for the next few months.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:33:32 </td>
   <td style="text-align:left;"> $SPY too many bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:33:30 </td>
   <td style="text-align:left;"> $SPY 2% down on the day? Meh...could be worse...$BTC.X ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:33:23 </td>
   <td style="text-align:left;"> $SPY Joe the Trump killer!! Made Trump a one term LOSER!!! 🇺🇸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:33:17 </td>
   <td style="text-align:left;"> $SPY ok final update:: due to a lack on communication issues I am still bearish because the fed and tapered have a lot more pressure to keep us posted to them for the world and market…it’s because China and the other states will do that for sure what is wrong 😑 what happens with you all that this stock will do so you mean 😪 but really in other ways ores we don’t have a stock price range you want us, hawkish and tapered again for interest rates and we can see your shares and then you will do what you’d want and what you do for the next so don’t buy the dip unless you want to and don’t think it will keep dipping because Qaq and tech stocks are “the stocks@ for”” people
And that is why I’m bearish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:33:15 </td>
   <td style="text-align:left;"> $SPY futes rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:32:59 </td>
   <td style="text-align:left;"> $SPY so all the ws crooks got spooked and sold today ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:32:28 </td>
   <td style="text-align:left;"> $SPY 473+tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:31:55 </td>
   <td style="text-align:left;"> $SPY Futures up .005%. Everyone thinks casino is open again lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:31:35 </td>
   <td style="text-align:left;"> $SPY Is this real life? This is what Sleepy Joe is wasting his time on?  The country is about to shut down due to lack of healthy staff lol.  

Not because of government mandate.  The real pandemic is here.  And he’s writing a f’n speech? 

https://www.cnn.com/2022/01/05/politics/biden-presidency-jan-6/index.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:31:04 </td>
   <td style="text-align:left;"> $SPY $UVXY I really want to see Japanese market burning further down below support. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:30:59 </td>
   <td style="text-align:left;"> $QQQ $SPY Despite recent bloodbath in growth, most quality tech stocks are still expensive but we shall have better buying opportunities now through July. Bearish short term </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:30:58 </td>
   <td style="text-align:left;"> $SPY $qqq
I don’t think this is full blown market correction, not yet in my estimate. 
Let’s watch the vix closing over 20 is more cautious. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:30:57 </td>
   <td style="text-align:left;"> $SPY dumb bulls want it to go 500 take your profit and shut the hell up it’s our turn. Dumb kids </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:30:44 </td>
   <td style="text-align:left;"> $SPY Anything green tomorrow let a brother know </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:30:35 </td>
   <td style="text-align:left;"> $SPY Just think about it.. supply/demand. Fed owns 15 trillion in assets. They are going to be selling these assets into the open market. What exactly will that flood of supply do to the price of the market? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:30:23 </td>
   <td style="text-align:left;"> $SPY $QQQ The bears must be sweating hard if they are looking at the futures now lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:30:22 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:30:12 </td>
   <td style="text-align:left;"> $SPY sold my puts today, I’ll wait a few days to see what happens from here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:29:44 </td>
   <td style="text-align:left;"> $SPY it&amp;#39;s okay most of all of us with the vaccine or those with recent infections  have adaptive immunity.. take care and be cognizant of those with immunodeficiencies and that are elderly.. that is all it&amp;#39;s going to be a great summer.. if you still haven&amp;#39;t got the vaccine and refuse to get it have a Omicron party with you and your young friends and then quarantine for 10 days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:29:31 </td>
   <td style="text-align:left;"> $SPY now it’s up to you BULLS to carry the torch! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:28:56 </td>
   <td style="text-align:left;"> $SPY tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:28:39 </td>
   <td style="text-align:left;"> $SPY be part of history and buy and lose it all then bitch about it when your protesting at Occupy Wall Street 🤦‍♂️🤦‍♂️🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:28:35 </td>
   <td style="text-align:left;"> $SPY futes starting to looking sketchy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:28:28 </td>
   <td style="text-align:left;"> $SPY kyrie reminds me of myself </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:28:26 </td>
   <td style="text-align:left;"> $SPY ah yes… let’s chase that </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:28:19 </td>
   <td style="text-align:left;"> $SPY I just ate many donuts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:28:17 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;m in gold, uranium, General Motors, and building into biotech as $LABU nears the March 2020 lows. Those and telecom are where I&amp;#39;m assuming the winning trades for 2022 will be. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:28:10 </td>
   <td style="text-align:left;"> $SPY robots will buy this up $4 before continuing to selling off in morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:27:59 </td>
   <td style="text-align:left;"> $SPY market a little scary to buy atm should wait a bit to add </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:27:56 </td>
   <td style="text-align:left;"> $SPY lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:27:47 </td>
   <td style="text-align:left;"> Will the Fed policy crash the market?! The past week has proven this 2022 market will be more difficult to navigate. Here are some things to be thinking about in the $SPY $QQQ $IWM 

Ideas also in: $LCID $COIN 

https://youtu.be/FYcXaJOJOWk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:27:41 </td>
   <td style="text-align:left;"> $SPY futes pampin’ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:27:33 </td>
   <td style="text-align:left;"> $SPY bulls speaking of omicron like their last hope. A hint: omicron is priced in, and it&amp;#39;s actually bears thing.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:27:27 </td>
   <td style="text-align:left;"> $SPY with my luck market crashes now that I went all in long </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:27:26 </td>
   <td style="text-align:left;"> $SPY okay, who&amp;#39;s looking for a buy everything rally by noon? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:27:21 </td>
   <td style="text-align:left;"> $SPY 470 calls Friday hmmm cheap af </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:27:07 </td>
   <td style="text-align:left;"> $SPY yep it’s bouncing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:26:44 </td>
   <td style="text-align:left;"> $SPY $SPX $YM_F The SwingTradePro algo predicated this recent drop.  I will share updated data set tomorrow. If your interested in how it works visit my website https://www.tradingsafely.net/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:26:18 </td>
   <td style="text-align:left;"> $SPY this Covid surge feels like a dead cat bounce </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:26:15 </td>
   <td style="text-align:left;"> $SPY $QQQ fed responds to political pressure and right now the political pressure is on inflation not on making stonks only go up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:26:09 </td>
   <td style="text-align:left;"> $SPY bulls celebrating because they’re bouncing off lows </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:26:02 </td>
   <td style="text-align:left;"> $SPY fucked up big. But one thing I know is to buy the dip. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:25:32 </td>
   <td style="text-align:left;"> $SPY gap up gap down gap up gap down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:25:25 </td>
   <td style="text-align:left;"> $SPY btw powerball tonight at 630 million </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:25:06 </td>
   <td style="text-align:left;"> $SPY green morning easy. So many bears celebrate after 4pm to wake up in hibernation. Celebrate your win bears, but the market is designed to go 🆙 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:24:45 </td>
   <td style="text-align:left;"> $SPY I really hope this is the start of an EPIC meltdown. This nonsense has gone on long enough. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:24:44 </td>
   <td style="text-align:left;"> $SPY $QCOM 

Great growth ahead </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:24:43 </td>
   <td style="text-align:left;"> $SPY              Only vaccinated died

After Christmas </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:24:40 </td>
   <td style="text-align:left;"> $spy COVID-19 is just an excuse to take some extended sick leave. Lazy bitches </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:24:35 </td>
   <td style="text-align:left;"> $SPY unbelievable, an avocado at Wally mart for 2.78 that&amp;#39;s the size of Joe&amp;#39;s--k, middle finger </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:24:35 </td>
   <td style="text-align:left;"> $SPY yes the futures and red for you to buy them in stock market 📉 buy some stuff from stock price price and don’t buy a high price for the dip and Fed taper !! Yes it will be a day tomorrow . Thursday to be exact </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:24:28 </td>
   <td style="text-align:left;"> $SPY lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:24:28 </td>
   <td style="text-align:left;"> $SPY 
Let&amp;#39;s see how it plays out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:24:27 </td>
   <td style="text-align:left;"> $SPY fed is literally turning off the printer and looking to take money out of the system by reducing the balance sheet 

Expect a 2018 type environment with a side of inflation and alt right terrorism 

Perfect for trading options! High vol environment </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:24:04 </td>
   <td style="text-align:left;"> $SPY @Dexs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:23:55 </td>
   <td style="text-align:left;"> $SPY $QQQ lol losrs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:23:53 </td>
   <td style="text-align:left;"> $SPY 

Hi.  I guess you bulls didn&amp;#39;t buy enough calls.  You should&amp;#39;ve bought more calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:23:51 </td>
   <td style="text-align:left;"> $SPY                       Remember 

When jo said all unvaccinated will be dead after Christmas…… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:23:42 </td>
   <td style="text-align:left;"> $SPY futures are looking good, but it could be a fake out, if not calls at open. Should rip over a bagger. Puts today paid 328%, so time to ride it back up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:23:36 </td>
   <td style="text-align:left;"> $SOFI honestly out of all the growth stocks this one is the safest, ceo Anthony noto, NFL stadium named after them, commercials on every channel. Producing big revenue, will be profitable. Disruptor for sure $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:23:20 </td>
   <td style="text-align:left;"> $SPY financials need to rally 

Those calls on JPM fucked me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:23:18 </td>
   <td style="text-align:left;"> $SPY I HAVE 30 MINUTES TO TURN $100 to $1000. WHAT DO I DO? $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:23:18 </td>
   <td style="text-align:left;"> $MJ $MSOS Aren&amp;#39;t these supposed to make you high instead of low ? $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:23:09 </td>
   <td style="text-align:left;"> $SPY that’s probably the LOD for nikkei </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:22:53 </td>
   <td style="text-align:left;"> $SPY Feb 480c down 30% now from +18% yesterday open, 464/465 pds hedges up 60% now. This goes to 465 tomorrow, I&amp;#39;ll close hedges for 150% atleast. The problem - I didn&amp;#39;t add short term hedges as I was adding long term longs. Lesson for future.
Will see if I can still add naked puts in the morning if it doesn&amp;#39;t feel like chasing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:22:44 </td>
   <td style="text-align:left;"> $SPY lights out … free call 

https://www.cnbc.com/2022/01/05/fed-minutes-december-2021.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:22:23 </td>
   <td style="text-align:left;"> $SPY so circuit breakers on tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:22:19 </td>
   <td style="text-align:left;"> $SPY y’all think polosi is a smash or pass? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:22:04 </td>
   <td style="text-align:left;"> $SPY hahahahhaha what happened to “The -10% correction starts now” 🤣😂🤣😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:21:52 </td>
   <td style="text-align:left;"> $SPY fu bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:21:20 </td>
   <td style="text-align:left;"> $SPY it only goes red so the smart ones can buy cheap and the weak can freak out 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:21:06 </td>
   <td style="text-align:left;"> $SPY time for short traders and MM to eat your 401k. Still happy you threw away your freedom for a dog shit salary? Lolll </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:20:57 </td>
   <td style="text-align:left;"> $SPY Halle the bears calling for a correction wouldn’t know what to do when it comes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:20:42 </td>
   <td style="text-align:left;"> Open sea growing $SPY $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:20:34 </td>
   <td style="text-align:left;"> $SPY yo! The toilet paper hoarding thing is happening again. Buy some Charmin calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:20:22 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;m super confused bulls said 500 next week? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:20:11 </td>
   <td style="text-align:left;"> $SPY guess they are done buy the dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:20:08 </td>
   <td style="text-align:left;"> $SPY  Limit downs coming, money printer off, bring out the quantitative tightening shredder </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:20:04 </td>
   <td style="text-align:left;"> $SPY when you least expect it 3% leg up to kill all short pests </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:19:58 </td>
   <td style="text-align:left;"> $SPY spy aint going to crash just because it went down 1.92% doesn&amp;#39;t mean the market is crashing. Buy the dip because it&amp;#39;s coming back strong. I hope everyone enjoyed the money on the puts now its time to make money on the calls. People don&amp;#39;t be greedy and share the wealth. 😀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:19:58 </td>
   <td style="text-align:left;"> $SPY its over bear </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:19:57 </td>
   <td style="text-align:left;"> $SPY futures being weird someone hurt their feelings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:19:42 </td>
   <td style="text-align:left;"> $AMC $QQQ $SPY Thank goodness for the </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:19:39 </td>
   <td style="text-align:left;"> $SPY nice rug pull Jerome thanks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:19:21 </td>
   <td style="text-align:left;"> $SPY 

Can one unshave their balls? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:19:04 </td>
   <td style="text-align:left;"> $SPY VIETNAM FUTURES RIPPING HOLY SHIT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:19:00 </td>
   <td style="text-align:left;"> $SPY Bear Market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:18:58 </td>
   <td style="text-align:left;"> $SPY -7% tmrw -10% Friday would be greeeeeaaaat </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:18:35 </td>
   <td style="text-align:left;"> $SPY so wait. the only bullish case anyone can make is that it went down, so it has to go back up? Lmao y’all are fucked. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:18:32 </td>
   <td style="text-align:left;"> $SPY Futes ripping in the Philippines. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:18:26 </td>
   <td style="text-align:left;"> $SPY super fawked nasdaq turned  red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:18:14 </td>
   <td style="text-align:left;"> $SPY why is everyone always so crazy here? It&amp;#39;s really weird you&amp;#39;re all weird 😂. You&amp;#39;re crazy of you think markets will crash because of the fed tho. 

Markets already did crash guys. Plus, the fed probably isn&amp;#39;t gonna be as hawkish as they&amp;#39;re saying anyways. Also, did any of you see that ppi report? Innovation is already curbing inflation. The yeild curve is confusing, but its more of a cluster fuck of confusion than a signal of recession In my probably poor opinion. Either way I think spy probably goes to the weekly 9 before finding any solid footing. Perhaps the weekly 20ma but I don&amp;#39;t think so </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:18:04 </td>
   <td style="text-align:left;"> $SPY more like BRRROKE!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:17:58 </td>
   <td style="text-align:left;"> $SPY just a tip for new (1-2 years) traders based on some comments and sentiment on this board. The past two years have been atypical. Especially this last streak we have been on. Basically you’ve been able to mindlessly buy calls even when technicals defy it and macroeconomic factors would suggest the opposite. I have seen a lot of people at close saying “I bought the shit out of the dip.”  My point is, being down barely over 1%, isn’t a correction. It isn’t really even a dip. There is skill in having patience in buying on a pullback, whereas recently, you basically can’t hit the buy button fast enough and bought “the dip” when it’s been down .10% intraday from ATH and you end up with a 200% gain. What we had a taste of today was the first glimpse at the fed dialing back unprecedented monetary policy and QE - but only just a taste. This represents the most consequential change since you entered the market and will have a serious impact, if not now, relatively soon. Study fundamentals </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:17:58 </td>
   <td style="text-align:left;"> $SPY futures dipping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:17:52 </td>
   <td style="text-align:left;"> $SPY it&amp;#39;s you the weak people who make the bad news not the fed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:17:51 </td>
   <td style="text-align:left;"> $SPY 
I’m normally not a bear, but damn we need about a 15-20% correction. It isn’t healthy to be this bullish for this long. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:17:46 </td>
   <td style="text-align:left;"> $SPY all bears tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:17:29 </td>
   <td style="text-align:left;"> $SPY 
Real (not Adp) jobs numbers come out Friday !!! Didn’t 4.5 million people just quit their jobs last month?? 🤔🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:17:27 </td>
   <td style="text-align:left;"> $SPY: 2 scenarios to watch for. If we gap up, look for any signs of weakness to scale in puts. If we gap down, bias is more bullish for possible short-term capitulation and red to green moves. 467 and 464 supports to watch. 470 and 473.2 are resistance levels to watch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:17:21 </td>
   <td style="text-align:left;"> $SPY STOP the freakout there is no bad news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:17:05 </td>
   <td style="text-align:left;"> $SPY 4874.75 by Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:17:03 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA CORRECTION HERE U R FUK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:16:44 </td>
   <td style="text-align:left;"> $SPY imagine a limit down tmrw 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:16:41 </td>
   <td style="text-align:left;"> $SPY Rip Hang seng aka Hang Man. 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:16:40 </td>
   <td style="text-align:left;"> $SPY how weak are investors VERY WEAK TODAYS SELLOFF WAS A DISGRACE OF SLAUGHTER THE SHEEP

THERE ARE SO LITTLE AMOUNT OF STRONG PEOPLE 

ARE YOU REALLY SCARED OF INTEREST RATES CMON OBVIOUSLY THEY GO UP DOES NOT MEAN YOU GOT TO BE ALL FREAKED OUT A FULL 2 MONTHS BEFORE IT HAPPENS 
WHO CARES ANYWAY JUST KEEP BUYING STOCK WEAKLINGS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:16:39 </td>
   <td style="text-align:left;"> Posted 12/15 - Most important $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:16:38 </td>
   <td style="text-align:left;"> $GS saved my ass. Got the top exit price $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:16:35 </td>
   <td style="text-align:left;"> $SPY I don’t think the people screaming crash truly know what they’re asking for. Perhaps foreigners who knows but everyone would feel the effects. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:16:32 </td>
   <td style="text-align:left;"> $SPY did we win finally? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:16:31 </td>
   <td style="text-align:left;"> $SPY Big question is When $MCD bringing back the $1 Whopper for the US to feast on in the recession...... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:16:07 </td>
   <td style="text-align:left;"> Posted 12/15 $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:16:05 </td>
   <td style="text-align:left;"> $SPY This guy gets it, we&amp;#39;re in FEAR full territory, totally different parameters than anything in our history and the unknown is the &amp;#39;it gaxtir&amp;#39; why our current HIGH INFLATION has a real good chance of going &amp;#39;hyper,&amp;#39; and THAT , my grasshoppers, is why FED gave minutes gruesome foreboding details of coming rate hikes sooner than we were expecting, June, to May, to now what looks like MARCH for 1st rate hike.

K? 
$QQQ

Now back to your books, peeps 
#STUDY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:16:04 </td>
   <td style="text-align:left;"> $SPY POS Fed created the bubble and now they’re popping it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:16:03 </td>
   <td style="text-align:left;"> $SPY  $RUT  Yelling &amp;quot;Market Crash&amp;quot; on a crowded message board.  https://channelchek.com/news-channel/The_Results_of_the_Last_Five_Years_of_Market_Crash_Talk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:15:59 </td>
   <td style="text-align:left;"> Stocks finished sharply lower Wednesday following the release of the minutes of the Fed&amp;#39;s December meeting

$QQQ $DJIA $SPY $IWM

https://www.thestreet.com/investing/stocks/stocks-off-following-dows-record-close-high </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:15:50 </td>
   <td style="text-align:left;"> $SPY 😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:15:49 </td>
   <td style="text-align:left;"> $SPY fistula is green we are good, 500 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:15:45 </td>
   <td style="text-align:left;"> $SPY $QQQ asia feeble,was nice fishin, but you know they will pamp for a few hours because they can. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:15:26 </td>
   <td style="text-align:left;"> $QQQ $SPY waiting for the most obvious bull flag with a iH&amp;amp;S to fail. But still hopeful lmfao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:15:19 </td>
   <td style="text-align:left;"> $SPY cathie is getting pounded

She was a hero in 2020. In reality , all anyone had to do was hold Tesla in 2020 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:14:57 </td>
   <td style="text-align:left;"> $SPY will the spy 🕵️‍♂️ you can find a new place that is on? Or will the taper goes up 🆙 not the only time we are in there and you are still here to get the fed…guess we’ll see </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:14:48 </td>
   <td style="text-align:left;"> $SPY so much blood in the market yet the benchmarks are near all time highs. What do we make of this?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:14:47 </td>
   <td style="text-align:left;"> $SPY for you blind people, you can always master this skill </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:14:46 </td>
   <td style="text-align:left;"> $SPY like if you stay horny for random wild 🐈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:14:29 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:14:11 </td>
   <td style="text-align:left;"> $SPY When in the hell did I sign up for plus membership... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:14:10 </td>
   <td style="text-align:left;"> $SPY Futures update for the shorts 👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-06 09:14:03 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 10:05:35 </td>
   <td style="text-align:left;"> $QQQ $RIVN $ARKK More puts tomorrow 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 10:04:59 </td>
   <td style="text-align:left;"> $QQQ what do we think bounce tomorrow then more red Friday? 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 10:03:27 </td>
   <td style="text-align:left;"> $QQQ my chart says QQQ to 416 pretty soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:59:41 </td>
   <td style="text-align:left;"> $QQQ massive put volume for jan 7th 383 strike at the end of the day (when put prices were highest)...  volume was 10 times open interest.... could bounce tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:59:38 </td>
   <td style="text-align:left;"> Tesla, Nio, or Rivian? 

Why Choose When You Can Buy Them All, Says Top Analyst via @TipRanks.

Great article which gives a good bull thesis on buying them all.

Where is the love for $LCID??

$TSLA $NIO  $RIVN $QQQ

https://www.tipranks.com/news/article/tesla-nio-or-rivian-why-choose-when-you-can-buy-them-all-says-top-analyst/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:56:28 </td>
   <td style="text-align:left;"> $QQQ If you had puts to sell today, congratulations! So much money was made on the downside it’s incredible. Still holding my 398c’s for the 31st, however they do not look so incredible anymore….and I thought I was getting a steal yesterday lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:55:59 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA  In these type of market conditions ..resistance is more relevant than support. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:55:55 </td>
   <td style="text-align:left;"> $QQQ futs looking good but we should be +.5% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:54:25 </td>
   <td style="text-align:left;"> $IWM Welcome to the  &amp;quot;Last Chance exit&amp;quot;
 $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:52:50 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ 

hope not </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:51:10 </td>
   <td style="text-align:left;"> $SPY $QQQ if we are to enter true bear market for extended time, most retailer traders would get wiped out due to options. Today’s market is running purely on option flow. Nobody is buying actual shares 99% retail traders are options </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:50:54 </td>
   <td style="text-align:left;"> $QQQ green…I’m turning off all electronic devices while I’m up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:50:46 </td>
   <td style="text-align:left;"> $SPY FED already rolled out the bed, you better hope factory orders cool, non manuf. pmi NOT hot, and, finally, that jobs Fri. comes in laisez faire , neither hot nor cold or you&amp;#39;re in t-ruh-uhb....

Zoiks! 

But that&amp;#39;s THREE shots to avoid the silver bullet which is, make no mistake, the FED with bo choice but to end QE abruptly announced 26th and a coup de Grace will be announcing 1st rate hike either MARCH....or, God forbid, bulls, Feb. 👍👌

$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:50:10 </td>
   <td style="text-align:left;"> $BTC.X $QQQ How comical would it be if the government makes another quick push on “gun control.” Fucking clowns would spark the civil war </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:49:26 </td>
   <td style="text-align:left;"> $BTC.X years later, no one can explain the point of this shi+ to me….🤔 
 
$TSLA $SPY $QQQ $DOGE.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:48:23 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA CORRECTION IS HERE WHO WANTS POPCORN 🍿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:48:21 </td>
   <td style="text-align:left;"> $QQQ $SPY the only way this is getting worse is if January 6th happens again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:46:57 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:43:48 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA “Bear Stearns is fine.” - Jim Cramer 🧊🚢 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:42:37 </td>
   <td style="text-align:left;"> $TSLA $AAPL $MSFT $QQQ $SPY Anyone holding PUTS after that 2 day massacre isn’t going to get a wink of sleep tonight, the Market always over reacts, tomorrow is going bounce HARD!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:41:19 </td>
   <td style="text-align:left;"> Today $QQQ shows SELL signal (TA) for short term. Technical analysis source: https://stockinvest.us/stock/QQQ?utm_source=stocktwits&amp;amp;utm_medium=autopost </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:39:54 </td>
   <td style="text-align:left;"> $SPX someone new the direction today- Damn $SPY $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:39:34 </td>
   <td style="text-align:left;"> Bad Day? Relax. Don&amp;#39;t Sell When You Should Be Buying https://www.youtube.com/watch?v=_j5vZCT-_2g $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:39:14 </td>
   <td style="text-align:left;"> $QQQ if you were surprised by what Powell said you should come out of your cave </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:39:03 </td>
   <td style="text-align:left;"> $QQQ me watching futures after fat fingering 180 calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:38:21 </td>
   <td style="text-align:left;"> $QQQ bunch of babies crying over spilled milk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:35:36 </td>
   <td style="text-align:left;"> $QQQ  If the Fed just raised interest rates instead of talking about it then the uncertainty would be over, we might take an initial hit but these stupid speeches that most dont understand what they are saying is just spooking investors. Get the rates raised and get it over with </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:35:36 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ $AMZN $AMC ;;,, 
 
 
Account Challenge Update:~ 
Start Date: Nov 2, 2021 
Starting Balance: $1,500 
Current Balance: $96,149 
Goal: $100,000 by end of January, 2022 
Strategy: Swing Trade Options, Stocks 
 
Watch out for next play👓 discord.io/MqakycG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:35:33 </td>
   <td style="text-align:left;"> $QQQ any one with puts tonight $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:33:56 </td>
   <td style="text-align:left;"> $QQQ i texted this play for my brother 🤷🏻‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:33:44 </td>
   <td style="text-align:left;"> $NVDA $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:32:08 </td>
   <td style="text-align:left;"> $QQQ futures rippin 😐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:30:59 </td>
   <td style="text-align:left;"> $QQQ $SPY Despite recent bloodbath in growth, most quality tech stocks are still expensive but we shall have better buying opportunities now through July. Bearish short term </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:30:58 </td>
   <td style="text-align:left;"> $SPY $qqq
I don’t think this is full blown market correction, not yet in my estimate. 
Let’s watch the vix closing over 20 is more cautious. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:30:47 </td>
   <td style="text-align:left;"> $QQQ 379 open 377 low buy to 386 then end at 379 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:30:26 </td>
   <td style="text-align:left;"> $QQQ pump it! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:30:23 </td>
   <td style="text-align:left;"> $SPY $QQQ The bears must be sweating hard if they are looking at the futures now lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:28:05 </td>
   <td style="text-align:left;"> $QQQ — </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:27:47 </td>
   <td style="text-align:left;"> Will the Fed policy crash the market?! The past week has proven this 2022 market will be more difficult to navigate. Here are some things to be thinking about in the $SPY $QQQ $IWM 

Ideas also in: $LCID $COIN 

https://youtu.be/FYcXaJOJOWk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:27:25 </td>
   <td style="text-align:left;"> $QQQ Market open green FOMO buying then turn into bloody red!! Book mark this post.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:26:15 </td>
   <td style="text-align:left;"> $SPY $QQQ fed responds to political pressure and right now the political pressure is on inflation not on making stonks only go up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:25:24 </td>
   <td style="text-align:left;"> $QQQ BTFD gang has disbandoned. If you are not hedged short you in for major pain till March. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:23:55 </td>
   <td style="text-align:left;"> $SPY $QQQ lol losrs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:23:18 </td>
   <td style="text-align:left;"> $SPY I HAVE 30 MINUTES TO TURN $100 to $1000. WHAT DO I DO? $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:23:18 </td>
   <td style="text-align:left;"> $MJ $MSOS Aren&amp;#39;t these supposed to make you high instead of low ? $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:20:07 </td>
   <td style="text-align:left;"> $QQQ Damn. Cathy get cream pied hard!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:19:42 </td>
   <td style="text-align:left;"> $AMC $QQQ $SPY Thank goodness for the </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:18:39 </td>
   <td style="text-align:left;"> $QQQ Big tech ERs coming up late Jan/early Feb. Cleansing has started early. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:17:34 </td>
   <td style="text-align:left;"> $QQQ https://channelchek.com/news-channel/The_Results_of_the_Last_Five_Years_of_Market_Crash_Talk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:17:03 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA CORRECTION HERE U R FUK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:17:00 </td>
   <td style="text-align:left;"> $QQQ is currently trading in the upper part of its 52 week range, slightly lagging the index. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:16:32 </td>
   <td style="text-align:left;"> $QQQ Futures trading super volatile </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:16:05 </td>
   <td style="text-align:left;"> latexfe5bb04a0f66d8dee902a8f96f18cc99QQQ

Now back to your books, peeps 
#STUDY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:15:59 </td>
   <td style="text-align:left;"> Stocks finished sharply lower Wednesday following the release of the minutes of the Fed&amp;#39;s December meeting

$QQQ $DJIA $SPY $IWM

https://www.thestreet.com/investing/stocks/stocks-off-following-dows-record-close-high </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:15:45 </td>
   <td style="text-align:left;"> $SPY $QQQ asia feeble,was nice fishin, but you know they will pamp for a few hours because they can. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:15:26 </td>
   <td style="text-align:left;"> $QQQ $SPY waiting for the most obvious bull flag with a iH&amp;amp;S to fail. But still hopeful lmfao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:12:41 </td>
   <td style="text-align:left;"> $QQQ A slight relief rally / dead cat bounce tomorrow/Friday then free fall next week..? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:11:43 </td>
   <td style="text-align:left;"> $QQQ anyone find surprising stocks fall off 10% for many days each day is this normal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:10:35 </td>
   <td style="text-align:left;"> $QQQ $NASDAQ  
15700 first target - double bottom support zone 15540 
daily support zones 15100 and 14500 
bottoming  process to complete expected by mid next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:07:26 </td>
   <td style="text-align:left;"> $QQQ $SPY “Load puts ASAP, our Google &amp;amp; Roblox calls got crashed” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:06:34 </td>
   <td style="text-align:left;"> $SPY $QQQ Wall Street is probably collecting short term option premium in the kangaroo market. 🦘

Run it up and down so they can collect premium and leave people bag holding their options. Lol 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:05:06 </td>
   <td style="text-align:left;"> $QQQ so far 2022 has been the worst start for the NASDAQ since 2008.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:04:06 </td>
   <td style="text-align:left;"> Of course all my setups for tomorrow are bearish so buy puts at open because I guarantee we’ll rally now 😁 $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:02:39 </td>
   <td style="text-align:left;"> $QQQ @OldFngGuy you are a friend of the people right? So pls don’t hide when the little fellas are looking for guidance. Last dip or dip before wasn’t based on the fed is no longer your friend type action after a year of biggest gains in decades. All your followers want to know is should they jump in and buy this 1-2% dip hoping for a v up or could there be anything to worry about here? Last time fed pulled it was 20% dip and Covid wasn’t even involved so even if circumstances were slightly different doesn’t much more then 1-2% look likely here? Surly there isn’t anything to worry about right? Assuming everyone isn’t buying and holding for 20 years though? I mean for your followers that would get wiped out on a 5-10% correction. Pls advise👇🏼👇🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:02:25 </td>
   <td style="text-align:left;"> $QQQ wen delist? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:01:52 </td>
   <td style="text-align:left;"> $SPY $QQQ expecting a big rug pull over night.  Most hawkish Fed in a very long time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:01:16 </td>
   <td style="text-align:left;"> #QQQ $QQQ Daily view !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 09:01:14 </td>
   <td style="text-align:left;"> A gap up is the biggest SHORTING opportunity of all time  
 
Lets pray  
 
$spy $qqq $amzn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:59:19 </td>
   <td style="text-align:left;"> $QQQ pretty obvious they are pumping new variants of COVID in airports, that explains why all these air crews are sick and cancelling flights plus how it spread so fast.  DEAR BIDEN STOP TRYING TO KILL US WITH YOUR DISEASES!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:58:28 </td>
   <td style="text-align:left;"> $SPY Repeat with me, &amp;quot; 2001 .&amp;quot; $NDX $SOXX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:57:41 </td>
   <td style="text-align:left;"> $SPY yikes and there it flushes. Pls pls don’t fall for this people. This is not a buy the dip opportunity yet. $QQQ and $SPY will get torched this is all time highs with fed no longer your friend. Last time it dropped 20% and that was without Covid issues. Pls be safe be careful </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:56:32 </td>
   <td style="text-align:left;"> $SPY $FB $QQQ Did I do that ? I don&amp;#39;t know! Pathetic Manchurian PUPPET AND chief </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:56:15 </td>
   <td style="text-align:left;"> $QQQ $spy nothing to worry about I&amp;#39;m sure... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:55:33 </td>
   <td style="text-align:left;"> $SPY What if tech crashes , twice, does damage b4 it&amp;#39;s ERs ?
And after?

Asking for  friends 

$QQQ $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:53:39 </td>
   <td style="text-align:left;"> New Analysis: Why smart money was holding Wednesday morning and selling Wednesday afternoon. Plus what’s driving #bitcoin’s selloff https://cracked.market/2022/01/why-smart-money-was-holding-wednesday-morning-and-selling-wednesday-afternoon-plus-whats-driving-bitcoins-selloff/ $SPY $QQQ $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:53:33 </td>
   <td style="text-align:left;"> $QQQ no way we go any lower </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:52:58 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA 
It would be the funniest thing if the markets decides to go back up tomorrow and Friday and repeat the sell off again Monday to Wednesday…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:52:38 </td>
   <td style="text-align:left;"> $SPY $QQQ What&amp;#39;s behind the move in markets, per Charlie McElligott, Nomuma&amp;#39;s smarty pants.

As I suggested earlier this week, that’s important to grasp. If breakevens aren’t crumbling, rising real yields either represent “US growth being repriced somewhat higher, or [the] addition of risk-premia due to potential (negative) implications of Fed policy tightening,” McElligott went on to say.

“Where are we seeing this ‘confidence’ in US economic growth?,” McElligott asked, before answering his own question. It’s visible in factor behavior, “which shows a clear bullish tilt to ‘Economically Cyclical / Inflation Sensitives,’ and away from ‘Duration proxies,&amp;#39;” Charlie wrote, noting big “green” moves in a 10-year yield sensitive factor, cyclical value, a crude-sensitive basket and small-caps, among other relevant expressions.

On the other side of this trade is anything and everything duration. 

(Duration = growth/tech/biotech)

https://heisenbergreport.com/2022/01/05/mcelligott-on-where-we-are-and-what-may-be-next/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:52:00 </td>
   <td style="text-align:left;"> $QQQ All right 350 or 340 by eonw? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:51:26 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM  Rates are the cake, folks, you can walk out of here alive if they stay BELOW 1.70.

I just don&amp;#39;t think, well, well, ok, I want a double pump Red Ryder--wait, that&amp;#39;s not it, I am going to calm down and th--I JUST THINK THE 10 YEAR ABOUT TO KETCHUP TO THE 2 AND THAT WILL CREATE!!!----&amp;quot;hey,hey, dude&amp;quot;

Oh, sorrr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:51:20 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMZN $GOOG $FB “fearful when others are greedy, and greedy when others are fearful.” buffet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:50:43 </td>
   <td style="text-align:left;"> $QQQ Gap Down tomorrow…or slight green and then dump… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:50:20 </td>
   <td style="text-align:left;"> $QQQ The Fed is joking with us </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:48:59 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:48:49 </td>
   <td style="text-align:left;"> $QQQ weekly... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:47:17 </td>
   <td style="text-align:left;"> $SPY $QQQ had best bounce with conviction tomorrow or look out below. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:46:20 </td>
   <td style="text-align:left;"> $PINS 
When this garbage hits $27 buy $QQQ 
Don’t - still don’t- buy this garbage </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:44:50 </td>
   <td style="text-align:left;"> $QQQ  china is happy -  https://www.axios.com/jan-6-poll-axios-momentive-26ba0f30-e2b1-4530-803c-860e6302c5a9.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:43:15 </td>
   <td style="text-align:left;"> $SPY $QQQ wow 1,000 posts between market close, dinner and now.  WHO HAS THE TIME. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:42:40 </td>
   <td style="text-align:left;"> $SPY latex1cca9b7d8d37a641d080cdde7c3595bbTSLA -5%
$NIO -5%

Is this a sign of things to come? Is this a bump in the road? Discussing the best names to trade long and short right now amidst the current cycle and inflationary pressures. 

https://youtu.be/Izf37X7e1zo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:40:28 </td>
   <td style="text-align:left;"> $ARKK $SPY $QQQ $DIA 

Is Cathie Wood&amp;#39;s deflation prediction about to materialize in 2022-23?

All asset sell off pricked by the Fed? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:40:24 </td>
   <td style="text-align:left;"> $SPY don’t get too excited. A little bounce tonight still turns into a big sell off tomorrow. It’s only smart funds buying to sell to “buy the dippers” tomorrow in the morning. They know your mentality and are exploiting it. Mark this post tomorrow $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:39:46 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMD $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:39:28 </td>
   <td style="text-align:left;"> $MVIS $SPY $ARKK $QQQ $PLTR :&amp;quot;:&amp;quot;:-

Account Challenge Update:~
Start Date: Nov 2, 2021
Starting Balance: $1,500
Current Balance: $95,849
Goal: $100,000 by end of January.
Strategy: Swing Trade Options, Stocks

Watch out for next play👓  discord.io/fmeeTaW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:39:13 </td>
   <td style="text-align:left;"> $QQQ well. So support was broken. Now what. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:38:58 </td>
   <td style="text-align:left;"> $spy it&amp;#39;ll take days or weeks to get though more weakness as the balance sheet reduction/reducing liquidity is a significant change. agree that it&amp;#39;s particularly risky to buy the dip until large holders reposition etc.  $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:38:18 </td>
   <td style="text-align:left;"> $QQQ tqqq splitting soon buy 50 you get 100 🤑🤑🤑🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:38:15 </td>
   <td style="text-align:left;"> $QQQ deceased feline jump tomorrow then tinkle down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:38:11 </td>
   <td style="text-align:left;"> If $BTC.X sells off tonight, it’s going to bring $TSLA $QQQ and $SPY down with it. The correction is happening….I feel for the small/mid caps. They were already destroyed for the last 9 months…… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:36:15 </td>
   <td style="text-align:left;"> $QQQ Everyone claiming they called this market dip, This is you.  😆 $SPY  $TSLA $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:36:11 </td>
   <td style="text-align:left;"> $QQQ many bulls still on here.  I&amp;#39;m sure it&amp;#39;s nothing.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:34:30 </td>
   <td style="text-align:left;"> $QQQ resigned to be being a bag holder FOREVER 😭 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:33:57 </td>
   <td style="text-align:left;"> $QQQ bought 385 calls at close for friday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:33:24 </td>
   <td style="text-align:left;"> $QQQ Hye! I would appreciate it if you can show some love! ❤️ if you use Webull this setup is fire! https://youtu.be/lXTIn7sXwKI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:33:15 </td>
   <td style="text-align:left;"> $QQQ slight bounce tomorrow and we hold $382 this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:32:52 </td>
   <td style="text-align:left;"> $RUT $SPY $IWM $QQQ Short seller’s day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:32:13 </td>
   <td style="text-align:left;"> $QQQ will be back to 400 by next week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:31:04 </td>
   <td style="text-align:left;"> $SPCE like I said 
$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:29:52 </td>
   <td style="text-align:left;"> $PENN are  $SPY $QQQ just Gnna consolidate?? Or we goin downwhats y’all think </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:29:47 </td>
   <td style="text-align:left;"> $SPY Heavy insular damage today $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:29:18 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:26:16 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:25:36 </td>
   <td style="text-align:left;"> $QQQ holy crap the new dune is awesome 👏 I was a kid with the first one </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:25:32 </td>
   <td style="text-align:left;"> $QQQ rally incomingggg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:25:08 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:24:44 </td>
   <td style="text-align:left;"> $SPY Watch your step $QQQ $SOXX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:23:59 </td>
   <td style="text-align:left;"> $QQQ $SPY vix was barely up today and bleeding hard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:22:34 </td>
   <td style="text-align:left;"> $QQQ gotta love that vix zero fear yet my 401k could get whacked here lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:21:43 </td>
   <td style="text-align:left;"> $QQQ Now I get it! All companies are worth nothing. I&amp;#39;ve done fine here, still way fine. Have at it and we will see how it goes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:21:14 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:21:01 </td>
   <td style="text-align:left;"> $QQQ is this the safety play? 🤣💩🔥🔥☠️
 https://www.reddit.com/r/Epic_Economics/comments/rx15ww/tech_sells_off_everywhere_market_mayhem_beware/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:20:16 </td>
   <td style="text-align:left;"> $QQQ unfortunately this time I have to agree with the bears. Even if we had a small pump, there is no chance it would stand. News are really bad. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:18:20 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $ tinder @ElviaWallace2 haha i think u left me on read haha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:17:58 </td>
   <td style="text-align:left;"> $QQQ Let us go Brandon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:17:58 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $RUT $DJIA  

                 Bottom was put in today

If you are short you will be vaporized </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:17:39 </td>
   <td style="text-align:left;"> The Technology sector ETF could fall an additional 6% and still maintain its trend of higher-highs and higher-lows. http://www.equityclock.com/2022/01/05/stock-market-outlook-for-january-6-2022/ $XLK $VGT $IYW $QQQ $COMPQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:17:29 </td>
   <td style="text-align:left;"> $QQQ @Bold3r @MZel Weekly Q&amp;#39;s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:16:45 </td>
   <td style="text-align:left;"> $QQQ lot of bagholders here, very sad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:16:19 </td>
   <td style="text-align:left;"> WE NAILED $SPY &amp;amp; $QQQ PUTS TODAY!! 🔥🔥 PLEASE CHECK OUT OUR LATEST VIDEO JUST POSTED ON THE Y-TUBE CHANNEL FOR THE OTHER 1000% + OPTIONS RUNNER ON A HUGE RED DAY!!! LETS GOOO FAM INVEST WISELY PLEASE THIS MARKET IS A CASINO!!  $UVXY $SQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:15:01 </td>
   <td style="text-align:left;"> $QQQ  it is💀 🐈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:14:59 </td>
   <td style="text-align:left;"> $QQQ $SPY can we go back to these days ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:14:49 </td>
   <td style="text-align:left;"> $SPY $QQQ technicals would say bounce here but DAMN those fed minutes were terrible for markets. Holy shit if you actually read them you would be shitting your pants right now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:13:03 </td>
   <td style="text-align:left;"> $SPY $QQQ Okay, crash over now brrrrrrrrrrrrr back to ATH...right guys?!?!?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:12:49 </td>
   <td style="text-align:left;"> Data suggests digital ads demand will be strong in 2022, great for the entire social platform sector. 
 
&amp;quot;Data suggests digital ads set for strong &amp;#39;22 despite cross-currents. Search looks resurgent (good for GOOGL). In Social FB ROI is dominant but looks like a spend share donor (TikTok a major gainer). Results generally positive for SNAP, TWTR and PINS.&amp;quot; 
 
https://twitter.com/StreetGuruHQ/status/1478768387446788098?s=20 
 
$SNAP $PINS $FB $TWTR $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:12:15 </td>
   <td style="text-align:left;"> $SPY h&amp;amp;s on spy and $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:11:56 </td>
   <td style="text-align:left;"> $QQQ made in China hustle. Profits over people. Shame. 
 https://www.reddit.com/r/Epic_Economics/comments/rx0y02/buy_now_pay_later_implodes/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:11:39 </td>
   <td style="text-align:left;"> $NASDAQ $DJIA $SPY $QQQ $VXX

Are we looking at a replay of 2000? Some would say so. Judging by this, I have been one of those that are predicting that. If you know charts, you just KNOW performance like this will never last. It’s just unsustainable, plain &amp;amp; simple. Trade accordingly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:10:56 </td>
   <td style="text-align:left;"> We gave our members a heads up for a potential swift move down yesterday. Our buy signals were close to hitting on several names as $SPY was making a new all time high while money flowed out of $QQQ names. However, less than a handful of our buy signals were triggered and what resulted was a swift move down(screenshot attached).  
 
Some leadership names we are watching for $SPY and latex45b303a3816b9710874a326b84d0d6f8AAPL - a leading tech name. Look for support to establish in the coming days despite it&amp;#39;s topping pattern forming.  
$TSLA - at key support levels. Ideally longs would like to see a bounce in the coming days near $1051.37 
 
For more charts and commentary  read our free blog post! &amp;quot;2022 - The Year of The Tiger&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:10:52 </td>
   <td style="text-align:left;"> $QQQ $AAPL $TSLA Huge moves up tomorrow, Tesla filled it’s Gap, Apple needed to cool off and  QQQ got thrashed, I couldn’t imagine holding PUTS overnight y’all going to get SMASHED in the morning 😆😆😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:08:12 </td>
   <td style="text-align:left;"> $TSLA This will go with $QQQ but filling an up-gap, backtesting a break out, and (hopefully) getting bought up off the 50-day together make a pretty strong buy point </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:07:55 </td>
   <td style="text-align:left;"> $SPY $QQQ We&amp;#39;ll see bears, we&amp;#39;ll see. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:07:17 </td>
   <td style="text-align:left;"> $QQQ Fed announced early rate cuts already. Not much changing. I expect another rally for QQQs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:06:39 </td>
   <td style="text-align:left;"> $UVXY Good hold for the next few weeks / months?

$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:06:14 </td>
   <td style="text-align:left;"> $spy $qqq we were expecting this all along… what’s new?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:05:43 </td>
   <td style="text-align:left;"> $TSLA $QQQ FJB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:04:51 </td>
   <td style="text-align:left;"> $QQQ In the recent reporting quarter: 0 institutions initiated a position, while 0 completely liquidated https://insider-analysis.com/search_whales.php?ticker=TABLE_QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:04:16 </td>
   <td style="text-align:left;"> $spy $qqq ok oversold.  We rally tomorrow. Economy super strong </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:03:59 </td>
   <td style="text-align:left;"> $QQQ nothing new here today: inflation and rate hike. We still have tons of liquidities. Btd is still the best strategy until trend breaks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:01:00 </td>
   <td style="text-align:left;"> $SPY $QQQ Factory orders will come in hot tom., I keep warning you, guys. Non manuf.  ISM #s same .

Inflation.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:00:41 </td>
   <td style="text-align:left;"> $AAPL weaaaaaaaak drop!!  Too weak for me to avg down my calls 😂! Try harder , let see 10-15$ drop, I will avg down. Y’all bears can’t drop apple , we will see 180s again anyways ! Watch and learn, y’all let fluffy news and fed scare y’all to sell but u know we always go back up to all times high 🤣. U will regret .. keep sellling so I can load calls . $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:00:40 </td>
   <td style="text-align:left;"> $QQQ $SPY $AMD FUCK YOUR PUTS  
WAVE 2 IS DONE 
OFF THAT SUPPORT TRENDLINE  
1 HOUR BULLISH HAMMER 
NOW WE GO HIGHER FORM THE 4 HOUR BULLISH HAMMER  
 
QQQ TO 420+ at the end of wave 3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 08:00:32 </td>
   <td style="text-align:left;"> $QQQ crashing on old news?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:59:12 </td>
   <td style="text-align:left;"> $QQQ women and children first. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:58:05 </td>
   <td style="text-align:left;"> $QQQ I liked the absolutely absurd amount of money just thrown at call sweeps the end of the day across the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:57:54 </td>
   <td style="text-align:left;"> $QQQ After, march buy the dip isn’t going to be such a good idea. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:57:34 </td>
   <td style="text-align:left;"> $QQQ greedy bears bout to get played tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:57:04 </td>
   <td style="text-align:left;"> $QQQ we will see a 20% decline if not now soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:56:07 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:55:57 </td>
   <td style="text-align:left;"> $QQQ Down 5% in 2 days… Oh my, shorts will get absolutely SMOKED tomorrow!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:55:38 </td>
   <td style="text-align:left;"> $SPY $QQQ 

U saw this revision of Nov. plus Dec. ADP, yeah, peeps? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:53:28 </td>
   <td style="text-align:left;"> For those who think we are on verge of economic collapse and people are scared. If this is the case, such condition should be reflected in everyday people&amp;#39;s sentiment as well. According to data! people&amp;#39;s sentiment keeps getting better and better; people are happier today than 2 years ago. There are so many things one can learn from this graph.

This data show the average sentiment of English speaking $TWTR users. 

$SPY, $QQQ, $UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:53:24 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:53:02 </td>
   <td style="text-align:left;"> $AAPL if u think this 2.75% down is end of pain think again.
A lot more pain coming.🤞🧸

Start shorting PPL. Make up ur losses. 
This is just the beginning of a juicy crash and recession. 

If your buying the dip might as well burn your house down.

U either cash out, short or run off to banks stocks.

$SPY $QQQ $MARA $BTC.X 

I really do! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:52:50 </td>
   <td style="text-align:left;"> $SPY $SPY $QQQ $DIA $IWM   
 
1 out of every 3 dollars in existence today 
did not exist 2 years ago. 
 
A process that would normally take DECADES. 
Warp speed wealth creation. 
 
The theft of an entire future (English-speaking) generation. 
 
The most insidious form of terrorism.  Just ask any German. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:52:09 </td>
   <td style="text-align:left;"> $QQQ tech futures searching for a bottom (65 min.) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:50:53 </td>
   <td style="text-align:left;"> $QQQ Sloppy Joe will get impeached if they Nasdaq goes down anymore </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:47:47 </td>
   <td style="text-align:left;"> $QQQ way over sold. The fed was likely to increase rates in March anyway </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:46:30 </td>
   <td style="text-align:left;"> $QQQ $SPY Do we live to see another day after bouncing off the bottom of the channel for the 9th time? Or are things finally getting spicy up in here?...oh and don&amp;#39;t mind that blue channel at the bottom, it&amp;#39;s for ~recessionary~ times...you know, just in case </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:45:00 </td>
   <td style="text-align:left;"> See #Flora 

No problem 

I&amp;#39;m long #US markets and #fear of the #VIX is getting smaller

You&amp;#39;re welcome ( kicks door in )
Here are the markets $DIA $SPY $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:44:52 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures up, the bears could be in trouble tomorrow if they didn&amp;#39;t close out their short positions earlier today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:43:08 </td>
   <td style="text-align:left;"> $QQQ $SPY FUTES RIPPING!!!

sorry had to do it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:42:22 </td>
   <td style="text-align:left;"> $QQQ Sure hedge funds can trade in and out and play these trading games.  However, 401k money will keep rolling in.  I don’t see how 99% of these hedgies can beat SP500 over 5 year period.  🤣😀😂😆😅🤑😂💲💰💲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:42:15 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL BOO... interest rates, sell! bunch of fools.. puts*😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:42:15 </td>
   <td style="text-align:left;"> $QQQ This is what I tell my friends who get so scared of tumbles like today...  &amp;quot;When was the last time tech didn&amp;#39;t bounce back after a big tumble?  Never!&amp;quot;.  Don&amp;#39;t be scared.  Just go buy big quality tech stocks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:41:24 </td>
   <td style="text-align:left;"> $QQQ $SPY Starting going short stocks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:40:40 </td>
   <td style="text-align:left;"> $spy $qqq $zm $sq $enph No longer bearish. Had enough fun today with puts. But only short term bullish cuz this market move was very steep to continue further without a decent pump! 📈💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:39:39 </td>
   <td style="text-align:left;"> $QQQ ETFs &amp;gt; individual stocks 
https://shop.robindrip.com/collections/qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:39:36 </td>
   <td style="text-align:left;"> $SPY $QQQ It&amp;#39;s funny because bears are going to lose money again lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:39:17 </td>
   <td style="text-align:left;"> $SPY $QQQ My ports are now down almost 5% from their ATH. It makes me sick. I sold a bunch of stocks today that I didn’t want to but the market is telling me I’m wrong on some. I’m not going to lose what I earned. I will sell a bunch more very soon if need be. Mr. M has been very good to me. I deserve to get run over if I get greedy so I will sell what needs to be sold. It doesn’t feel good but all stocks are just instruments to make money. Nothing more. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:39:07 </td>
   <td style="text-align:left;"> $QQQ timed algo trading at its finest </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:38:34 </td>
   <td style="text-align:left;"> $QQQ Guess stonks don&amp;#39;t always go up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:37:26 </td>
   <td style="text-align:left;"> $QQQ joe Biden </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:37:19 </td>
   <td style="text-align:left;"> $QQQ 🎶because the night.. belong to Buyers🎶...🕺 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:36:39 </td>
   <td style="text-align:left;"> $QQQ why is this down 3 in one day? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:35:58 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ $IWM carnage into the close...Nasdaq got the worst of it.  Is $TNX (risk off) the culprit? idk...

The bad news is that stocks will need to go down even further before we&amp;#39;re in the &amp;quot;bargain/sale&amp;quot; zone. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:34:03 </td>
   <td style="text-align:left;"> $QQQ buy the night..sell the day! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:33:57 </td>
   <td style="text-align:left;"> $QQQ Looking for an oversold relief rally next couple of days.  🤑🤣😀😅😂😂💰💲💰💲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:33:13 </td>
   <td style="text-align:left;"> $QQQ bruh if this isn’t up 2-3 overnight… i don’t want it! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:32:50 </td>
   <td style="text-align:left;"> $QQQ 390 before more down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:32:08 </td>
   <td style="text-align:left;"> $QQQ down 3% is that enough? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:31:08 </td>
   <td style="text-align:left;"> $spy $qqq always relevant </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:30:57 </td>
   <td style="text-align:left;"> $QQQ bears chasing puts down here are as dumb as bulls chasing calls at the top, qqq is down 5% past two days how much more can it fall before a bounce </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:30:52 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ &amp;quot;In 48 hours I&amp;#39;ll be accepting  your apologies.&amp;quot; - John Hammond, Jurassic Park </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:30:41 </td>
   <td style="text-align:left;"> $SPY Tutes haven&amp;#39;t even entered yet, this is retail, big business will pick a spot soon, might wait til Fri. or even 26th, but be very wary, bulls, or the heffalumps and woozles will soon get you . Don&amp;#39;t sleep on this market, at all, you&amp;#39;ll wake up from dreaming good things to a massive nightmare 👍 .... $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:30:10 </td>
   <td style="text-align:left;"> $SPY $QQQ This is from the 80s. Still rings true today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:29:42 </td>
   <td style="text-align:left;"> $SPY negative market breadth and market divergence = stealth bear market. $QQQ $VTI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:29:25 </td>
   <td style="text-align:left;"> $QQQ lmao that bear trap was hilarious bought up so quick </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:29:14 </td>
   <td style="text-align:left;"> $QQQ f biden i command you to rise </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:28:14 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:27:21 </td>
   <td style="text-align:left;"> $SPY $QQQ give us a tech sector correction! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:25:54 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA zomg did  you  see that  Warren Buffett dumped all of his $AAPL shares?  Yeah that&amp;#39;s because he didn&amp;#39;t.  Just buy good companies and ride this bump out.  If you wanna chase  little shitter  plays down a hole you&amp;#39;re gonna have a bad year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:25:27 </td>
   <td style="text-align:left;"> $QQQ Wait.  So hedge funds are selling stocks and buying bonds so they can get that 2% return?  😀😀😂😆🤑🤣💰💲💰💲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:24:25 </td>
   <td style="text-align:left;"> $SPY  $QQQ Not convinced the bear has awakened, but if so, bring it you hairy SOBs! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:23:18 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:22:56 </td>
   <td style="text-align:left;"> $QQQ 💸💸💸💸💸💸💸💸💸💸
The stock market is a device to transfer money from the impatient to the patient.”
if you love yourself invest in Pre-IPos.  I am placing a link for who I always use.Send them a message they are a good group.
Investors.be4ipo.net </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:22:43 </td>
   <td style="text-align:left;"> $QQQ theta burn tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:22:34 </td>
   <td style="text-align:left;"> $SPY haven’t seen all futures including VIX red in a while lol $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:21:54 </td>
   <td style="text-align:left;"> $QQQ $SPY Worst start for tech stocks since 2008 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:21:26 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $IWM $DIA   
 
Stock buybacks hit the highest level in American history in 2021. 
Stock selling by insiders also hit a record high in 2021. 
 
Using shareholder money to juice up prices, 
then sell at these inflated levels for a massive profit. 
 
Oh the irony. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:21:02 </td>
   <td style="text-align:left;"> $QQQ remember march 2000? Its coming again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:20:40 </td>
   <td style="text-align:left;"> $QQQ Burtal. Fed meeting were raising interest rates. Stock market rallies. Fed minutes were raising interest rates stock market slip the rug. Can&amp;#39;t make this stuff up. Next week market rallies because interest rates are priced in :/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:19:45 </td>
   <td style="text-align:left;"> VIDEO: Broad Market Technical Analysis Chart 1/5/2022 $SPY $XLF $QQQ $TSLA $CL https://www.chartguys.com/daily-market-videos/4098/fear-back-on-the-menu </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:18:44 </td>
   <td style="text-align:left;"> $QQQ not thinking abt thinking abt . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:18:27 </td>
   <td style="text-align:left;"> $QQQ $SPY may just may have a chance but definitely not the nasdaq. If u are not a sharp shooter in this market u need to stay far far away from $QQQ while feds are no longer your friend. I’m telling u, warning u whatever u want to call it this isn’t a dip and rip it’s got a long way to come down to be close to ready to bounce. Pls be safe here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:16:03 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA today is one of those days... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:15:51 </td>
   <td style="text-align:left;"> $QQQ The best thing that&amp;#39;s happened to you both pompous and reckless irresponsible fools in a while... a 500 point plus haircut... I&amp;#39;m sure you&amp;#39;ll get a chance for a better exit point in coming days as the fools of Wall St will be out talking up chips and semis again like there&amp;#39;s some &amp;quot; deep value&amp;quot; to still be had but when the bubble in tech land bursts over the next few months you&amp;#39;ll only wish you had exited at this point ...enjoy folks!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:15:13 </td>
   <td style="text-align:left;"> Why The Stock Market Dropped Following Fed Minutes  $QQQ $SPY $DIA 

https://newsfilter.io/a/b739d4793e4d4e071e0b32c99b268521 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:15:00 </td>
   <td style="text-align:left;"> $QQQ outperforms 75% of all stocks! https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:14:58 </td>
   <td style="text-align:left;"> $NVDA  $SPY  $QQQ   --  Big move coming ???   - nvda </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:13:49 </td>
   <td style="text-align:left;"> https://www.youtube.com/watch?v=tDybEAtDbuc&amp;amp;ab_channel=UnlimitedOptionsInvesting $spy $qqq $msft $ndx </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:13:05 </td>
   <td style="text-align:left;"> $QQQ and here comes the selling.. round 2 heavy blood tmrw on $RIVN $AFRM $DASH $ABNB. Focus shorts and puts on companies that have terrible multiples or balance sheets. Those will be the ones everyone is selling on </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:12:50 </td>
   <td style="text-align:left;"> $QQQ hourly RSI is 12 wtf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:12:44 </td>
   <td style="text-align:left;"> $SPY $QQQ  Today Nasdaq saw the biggest red dildo since Jan 2021. Hope bulls enjoyed it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:12:28 </td>
   <td style="text-align:left;"> $SPY $QQQ $SOXL Today was a good day! 700% on my dec 7th puts, totally insane. 

Also I love watching gullible bulls lose their money. The pain is only getting started!! Woohoo!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:12:19 </td>
   <td style="text-align:left;"> $QQQ 20 week EMA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:11:57 </td>
   <td style="text-align:left;"> $QQQ ST price is wrong. 383 on Thinkorswim. Had to check my puts and what not 😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:11:56 </td>
   <td style="text-align:left;"> $SOFI $PLTR $DKNG does any one understand how additional 1-2% interest cost can be so devastating for growth companies? $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:11:44 </td>
   <td style="text-align:left;"> $QQQ bought $TQQQ for a bounce tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:11:00 </td>
   <td style="text-align:left;"> $SPY $QQQ wen meltup? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:10:32 </td>
   <td style="text-align:left;"> $USD weekly in a bull flag. This is bad news for equities. Also, Fed tightening QE. $QQQ $SPY $DIA $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:10:25 </td>
   <td style="text-align:left;"> $QQQ think we bounce early tom and end up back here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:10:04 </td>
   <td style="text-align:left;"> $QQQ this price is wrong. 383.23 on TD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:08:39 </td>
   <td style="text-align:left;"> $QQQ / steak price remains constant </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:07:55 </td>
   <td style="text-align:left;"> $QQQ maybe I shoulda waited till tomorrow to buy them calls 🙄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:07:28 </td>
   <td style="text-align:left;"> $QQQ and $SPY have not touched the 50 SMA (weekly) in a while. They are likely heading there. #SPY #QQQ $SPX $NDX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:07:18 </td>
   <td style="text-align:left;"> $QQQ $650 gap up tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:06:48 </td>
   <td style="text-align:left;"> $QQQ And so it begins! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:06:47 </td>
   <td style="text-align:left;"> $QQQ down a dollar AH sweet goodbye </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:06:45 </td>
   <td style="text-align:left;"> Why The Stock Market Dropped Following Fed Minutes $QQQ $SPY $DIA https://benzinga.com/z/24920106#.YdYkdKvuSVA.twitter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:05:28 </td>
   <td style="text-align:left;"> $SPY Any takers, the longer futures stay green the more the squid game is in play with rates, 

.8296
1.7
2.08.
$QQQ 
Ready, set, </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:05:08 </td>
   <td style="text-align:left;"> $spy $qqq the best turn around Tuesday in years - congrats winners </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:05:05 </td>
   <td style="text-align:left;"> $QQQ In the recent reporting quarter: 8 institutions increased their position, while 2 decreased https://insider-analysis.com/search_whales.php?ticker=TABLE_QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:04:57 </td>
   <td style="text-align:left;"> $SPY $VXX $IWM $QQQ if only you people understood how the VIX works 🤦‍♂️  (Everyone reading this who says “what does VIX have to do with anything”) is going to lose everything. TRUST ME. Understand how the CBOE volatility index effects EVERYTHING. And then watch this. https://youtu.be/0akBdQa55b4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:04:34 </td>
   <td style="text-align:left;"> $QQQ Weekly bearish doji star from last week played out - would a great place to bounce here at the 20 week MA.   If not, the 30 week MA has held since the week of April 13, 2020 and had 6 touches since then (with all opens and closes remaining above).   That level is 375.74 (2.2% below here). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:04:33 </td>
   <td style="text-align:left;"> $SPY $QQQ I’m not freaking selling! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:03:40 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $DIA $DJIA 

The StockMaster has it

Let the sell off begin 🧞‍♂️🔈. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:03:32 </td>
   <td style="text-align:left;"> $QQQ come back in 12 hours or so futes will be neon green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:02:20 </td>
   <td style="text-align:left;"> $SPY $QQQ Cathie Wood spotted on the streets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:02:07 </td>
   <td style="text-align:left;"> $QQQ more selling into the close &amp;amp; we got some panic selling. Back to test support of september highs. Will look for breadth to become oversold too and / or see a buy thrust to get a reliable buy signal from here in days to come.  $SPY $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:02:06 </td>
   <td style="text-align:left;"> $QQQ $DIA $spy futures are flying and ripping green…… huge reversal tomorrow…..yay !!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:01:42 </td>
   <td style="text-align:left;"> $SPY $QQQ my 600 points sell call target done and market oversold now . Let’s wait and enter . Most of the puts moved 300 to 2000% .. check the alerts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:00:28 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ 

VIX s/b at 40, not 20! 😂🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 07:00:27 </td>
   <td style="text-align:left;"> $QQQ you gotta love it. We have known about this fed decision for nearly a month as wallstreet constantly bought and stayed bullish. Today the retards ag wallstreet needed confirmation. They dont need confirmation for bullish investments as 10 years out they will keep buying, but once confirmed bearish, they flush the markets serving no integrity in the legs of the market. Wallstreet needs to be served with consequence for these irresponsible acts. Markets should not have to act in a psychological manner that has people jumping off rooftops but wallstreet does not care. Greedy fat pigs. We are the 99% . Fuck your feelings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:58:26 </td>
   <td style="text-align:left;"> $BTC.X lol remember when they were selling bitcoin 100K tee shirts $qqq $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:57:18 </td>
   <td style="text-align:left;"> $AAPL anyone with intelligence and experience in the game know what happens to tech stocks with massive balance sheets when reds raise rates? I mean … wasn’t this obvious knowing the fed is about to do so? I sure hope nobody jumped in paying top prices when they could have used psychological variables and history and a bit of foresight to buy 3-5-7% cheaper right? $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:55:19 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  you don&amp;#39;t wanna be in the stock market when the FED taking liquidity out.

no bonds
No stocks
No FAANG stocks
No #Bitcoin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:53:53 </td>
   <td style="text-align:left;"> $QQQ 

Nice dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:51:59 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM Call me what you want. But for the last 3 weeks EVERYTHING I’VE SAID HAS HAPPENED!!! Watch for yourself BEFORE you judge me. On both bullish and bearish topics. 100% accuracy.

https://youtube.com/channel/UCQHWBF5nNpVAmGfae8o4ExA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:51:35 </td>
   <td style="text-align:left;"> $QQQ NEW ARTICLE : Ray Dalio- 2022: A Year of Transition https://www.stck.pro/news/QQQ/20939723 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:50:37 </td>
   <td style="text-align:left;"> $SPY $QQQ trash ipo stocks that have been trading at 50-100x sales and people still confused why they’re puking🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:50:32 </td>
   <td style="text-align:left;"> $SPY good news is.... Volatility is back. Plenty of money to be made! Up or down! $AAPL $TSLA $NVDA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:50:24 </td>
   <td style="text-align:left;"> $QQQ $SPY Joe Biden memes never get old </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:49:48 </td>
   <td style="text-align:left;"> $QQQ wen more brrrrr?????🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:48:28 </td>
   <td style="text-align:left;"> $spy $qqq @OldFngGuy forever my bitch 💋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:48:11 </td>
   <td style="text-align:left;"> $BTC.X it’s how u can tell it’s a real sell of in markets not a dip. When big money from around the world sells they sell everything. It’s a rush to the dollar and everything else goes down. I will rebut btc at 19-34900 and in between, I will re buy $SPY  starting under 450 (could be too early but worth the start) and I will load the china markets $YINN etc in the $5.90-$7.29 range $QQQ is going to get absolutely slammed with rate hikes. I hope the newbies understand how overvalued these pigs are and how impossible it is for them to perform under rate hikes I know people like @OldFngGuy has enough knowledge to know what happens to valuations in tech and companies like $AAPL with that much cash on balance sheet when rates rise. And I know he will help people not too lose money by chasing light dips. TO BE CLEAR to the new kids that have only seen this past year and think it only goes straight up? Last fed raise it dropped 20% WITHOUT Covid issues. trade and buy in pieces not immediately </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:48:08 </td>
   <td style="text-align:left;"> $QQQ bought dip. Maybe if it dips to 370, will buy again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:47:00 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $DKNG $CLOV  
 
All I’m saying is….this dip feels different….  
 
🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:46:51 </td>
   <td style="text-align:left;"> $QQQ I honestly think events like today need to happen just to deleverage (liquidate derivatives) the market before another move up. Otherwise we would implode. As I said previously, free money isn’t stopping. If it was then Nancy pelosi would have pulled out instead of being leveraged to the tits in calls. Higher soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:46:33 </td>
   <td style="text-align:left;"> $QQQ time to shooooort everything!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:45:57 </td>
   <td style="text-align:left;"> $NDX Short 14210 puts 54 DTE $QQQ $TQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:45:35 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $DIA $SMH .. Proved right ! This 👇🏻 WAS a bad omen 🔻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:45:21 </td>
   <td style="text-align:left;"> $QQQ $SPY Thanks to all the permabulls for selling cheap puts this morning.  You keep us bears in business... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:44:29 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ 

No one gives a fuck about Covid no more. It’s rising rates that’s the worry. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:40:30 </td>
   <td style="text-align:left;"> $QQQ a truly insane opportunity exists and not in crypto. In volatility. Buy the calls!! 🚀🚀
 https://www.reddit.com/r/Epic_Economics/comments/rwytav/market_mayhem_buy_the_volatility_uvxy_the_17_13/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:40:26 </td>
   <td style="text-align:left;"> $QQQ $TSLA 
The fed giveth, and the fed taketh away. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:40:22 </td>
   <td style="text-align:left;"> $SPY $QQQ today was the 666th day of the pandemic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:39:56 </td>
   <td style="text-align:left;"> $QQQ $AQUAGOAT.X guys check out Aquagoat it’s the future of defi and ocean conservation! Aquagoat is the headline sponsor of this weeks miss earth USA Pageant televised live from Orlando! 

Visit Aquagoat.finance for more info!
Great entry now! Pumping even with btc down! LfG!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:39:52 </td>
   <td style="text-align:left;"> $QQQ $DIA $SPY  the next republican candidate has to win over the American female for votes, otherwise we are screwed for a very long time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:37:32 </td>
   <td style="text-align:left;"> $QQQ don’t listen stocktwits guru’s. https://youtu.be/QCVYoM6CZ9Y </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:37:11 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:36:51 </td>
   <td style="text-align:left;"> $QQQ wow this took a hit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:36:23 </td>
   <td style="text-align:left;"> $QQQ 📉📉📉📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:35:30 </td>
   <td style="text-align:left;"> $QQQ this is why elections matter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:35:12 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Give a honest opinion.

Do you thinks Dems know any thing about business execution other than wasting their time on issues not important to everyday family.

Print Money
Pursue Jan 6 people
Help cross the illegal borders
Ask of Fairshare without knowing what defined fair there?

 but not a single word about plan to ease supply chain and bring people back to work . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:35:03 </td>
   <td style="text-align:left;"> My $QQQ puts and $FIS calls only fueled this fire today boys and girls. Goes right into buying more synthetic shares. 

Told ya hedgies, drop it some more. Please, I need more fake shares. If you want em back, bring your check book. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:34:53 </td>
   <td style="text-align:left;"> $QQQ $SPY $RIVN  remember, you voted Liberal, only another 3 years🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:34:06 </td>
   <td style="text-align:left;"> $QQQ let’s go Brandon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:33:47 </td>
   <td style="text-align:left;"> $BTC.X CLIFF DIVING!! $QQQ $SPY $RIVN $MRNA more blood to come! We’ve been waiting 6 months for the market to realize what overvalued premiums are. Multiples are crazy! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:33:35 </td>
   <td style="text-align:left;"> $QQQ Back to September Highs. Whats next? May Highs? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:33:22 </td>
   <td style="text-align:left;"> $QQQ remember $AAPL $AMZN $GOOG $FB are still the giants and will be for a very long time, they are not at astronomical levels and that is the heart of the QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:33:18 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:32:52 </td>
   <td style="text-align:left;"> $QQQ Atleast $BTC.X is finally crashing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:31:50 </td>
   <td style="text-align:left;"> $SPY $qqq alright $AAPL we need you to go to 4 trillion. You are our only hope. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:31:47 </td>
   <td style="text-align:left;"> $QQQ $SPY You know it&amp;#39;s a bad day when these two are trending </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:31:06 </td>
   <td style="text-align:left;"> $QQQ 😞 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:29:39 </td>
   <td style="text-align:left;"> $SPY $QQQ  carefully friends, these dips haven’t lasted long. Don’t chase plays. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:29:16 </td>
   <td style="text-align:left;"> $QQQ first move is always the wrong one </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:24:35 </td>
   <td style="text-align:left;"> $SPY $QQQ

https://www.youtube.com/watch?v=QCVYoM6CZ9Y&amp;amp;t=92s

Seems like Tom Lee is calling for the 10% correction in the H1 of the year but then the market will surge in the H2 of the year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-06 06:24:29 </td>
   <td style="text-align:left;"> $SPY $BTC.X $QQQ $ETH.X 

Wow .. one thing the media was right about.. was characterizing this moment as a “ taper tantrum”. The perma bulls are literally having a fucking tantrum .. bitching, complaining it’s rigged , getting nasty. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 10:00:38 </td>
   <td style="text-align:left;"> $SPY $SNIPF $AAPL $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 09:58:46 </td>
   <td style="text-align:left;"> $AAPL carnage in the markets today. 3%is no fun </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 09:56:03 </td>
   <td style="text-align:left;"> $NVDA $TSLA $AAPL The Fed blew their load and now they are pulling out. 

Look back at history what happens when they try to raise rates.

Good Game entire world. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 09:55:30 </td>
   <td style="text-align:left;"> $AAPL ha ha AAPL hell tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 09:47:48 </td>
   <td style="text-align:left;"> $AAPL damn, I love my own chart. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 09:42:37 </td>
   <td style="text-align:left;"> $TSLA $AAPL $MSFT $QQQ $SPY Anyone holding PUTS after that 2 day massacre isn’t going to get a wink of sleep tonight, the Market always over reacts, tomorrow is going bounce HARD!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 09:33:57 </td>
   <td style="text-align:left;"> $AAPL What do you think Apple will be by 2023? Show me your bets! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 09:25:36 </td>
   <td style="text-align:left;"> @jadebronco $AAPL how do you handle a shock to an industry? Simple. Deploy built-in reversal for 20%+ profit in one day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 09:23:19 </td>
   <td style="text-align:left;"> $AAPL wouldn’t people wanna buy more before the interest rates go up? ... like take advantage while it lasts? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 09:13:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 48 analysts. The buy consensus is at 83%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/quote/AAPL/analyst-ratings?utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 09:12:37 </td>
   <td style="text-align:left;"> $AAPL I lnow I-m cheesing and soap boxing here but shouldnt these last couple days fall in  the ol &amp;#39;dont pull out of the market/cant keep a good economy down&amp;#39; category 🤷‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 09:10:26 </td>
   <td style="text-align:left;"> $AAPL Covered here as well. GL mates. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 09:09:01 </td>
   <td style="text-align:left;"> $SPY - 1,100% PROFITS ON SPY PUTS.! WHAT A DAY FOR OUR MEMBERS 👑
FALL-O FOR MORE, LYNX IN BAYU.
$TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 09:06:11 </td>
   <td style="text-align:left;"> $AAPL the two guys sitting in the car showing cinematic mode was a lame commercial </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 09:05:19 </td>
   <td style="text-align:left;"> $AAPL   🍏 AfterHours Closing Price, 175.07  up +0.15. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 09:04:28 </td>
   <td style="text-align:left;"> Ticker: $AAPL 
Buy: January 07, 2022 $175.00 Calls 
Entry Price: $2.02 - $2.14 
Exit Price: $2.22 
Stop Loss: $1.78 
Potential ROI: 10% 
Estimated Hold Time: 21 Minutes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 09:03:48 </td>
   <td style="text-align:left;"> $AAPL FOMO buying is over now valuations will come back down to earth as the smart money exits knowing how insane this FOMO run has been. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 09:03:28 </td>
   <td style="text-align:left;"> Posted 12/15/21 $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 09:02:05 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-01-05 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=P0FCmYwN5aQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 09:00:22 </td>
   <td style="text-align:left;"> $AAPL Simulated 177.5 dollar CALLS for Thursday&amp;#39;s open on StockOrbit.
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 08:59:07 </td>
   <td style="text-align:left;"> $AAPL market will likely remain bearish until price reaches $115ish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 08:57:46 </td>
   <td style="text-align:left;"> $AAPL people calling this a sell off.  This opened Monday at $177.  Down 2.5 points this week.  Big deal.  Haha.  Sit back and relax, the real sell off is under way! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 08:46:32 </td>
   <td style="text-align:left;"> latex084c9720cfc7af19669d89c1a957e2adMSFT/$AAPL/ MSFT /GOOG /NVDA  after fed min we are going to have @ least 10 to 15% correction and when this happen these are my buy list, so get smart and raise Cash to buy the Delicious dip! 
FYI first time ever I heard Josh brown today saying right now he likes Cash so Dan Niels. $SPY 
GLTA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 08:44:43 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $NVDA $MSFT Margin call fiasco will be epic, keep buying the dip numb nuts… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 08:43:54 </td>
   <td style="text-align:left;"> $AAPL wait for 170! Will start a new position!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 08:39:19 </td>
   <td style="text-align:left;"> $AAPL heeeeeeelp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 08:38:33 </td>
   <td style="text-align:left;"> 🚨Today’s Recap 🚨

🔥01/07 $AAPL $177.50P @1.43&amp;gt;1.15 (25%)
🔥01/07 $LCID $1.35&amp;gt;.95 (40%)
🔥01/05 $SPY $1.50&amp;gt;1.03 (50%)
🔥01/07 $TSLA $1085P @20.60&amp;gt;17.45 (20%)
🚀01/21 $SPY $470P @5.50&amp;gt;1.08 (500%)
🔥01/07 $SPY $475P @2.14&amp;gt;1.88 (14%)
🔥 01/07 $AAPL $177.50P @1.32&amp;gt;1.17 (13%)

7/7 today 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 08:38:32 </td>
   <td style="text-align:left;"> $AAPL Man all the instagram gurus getting hammered today. I guess buying short term calls in tech everyday isn&amp;#39;t that great of a trade strategy lol $MSFT $SPY $IWM $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 08:35:21 </td>
   <td style="text-align:left;"> $SPY I would never ever buy crypto, microcap stocks yes. Not fake currency $AAPL $AMD $AMZN $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 08:33:20 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : How Meaningful Will Time Spent Be in Virtual Worlds? https://www.stck.pro/news/AAPL/20944622 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 08:32:13 </td>
   <td style="text-align:left;"> What Investors Should Know About Amazon, Sony And John Deere&amp;#39;s Latest Push Into The Electric Vehicle Sector  $TSLA $F $GM $SONY $AAPL 

https://newsfilter.io/a/61273ce504a884821eea439d8c44023c </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 08:26:24 </td>
   <td style="text-align:left;"> $AAPL puts worked great! Bought calls at the close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 08:23:37 </td>
   <td style="text-align:left;"> $AAPL Backtesting the channel and checking the 50-day at around $165 would be healthy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 08:22:27 </td>
   <td style="text-align:left;"> $SPY Moment of silence for Pelosi recent $AAPL FAANG buys.

K, long enough. Woooot! Wooooooo!!!! 

$DWAC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 08:21:57 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA still bullish but too early to btd imo, especially growth stocks… stick to value with this market condition </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 08:20:40 </td>
   <td style="text-align:left;"> $AAPL made in China
 https://www.reddit.com/r/Epic_Economics/comments/rx15ww/tech_sells_off_everywhere_market_mayhem_beware/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 08:19:00 </td>
   <td style="text-align:left;"> $AAPL is a display maker, very expensive Chinese display maker, using slave labor basically. When they mentioned the car coming up I knew it was over. Desperate to bring something new to the market but car ain’t the thing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 08:16:48 </td>
   <td style="text-align:left;"> $BTC.X lol no one would buy below 10K let alone paying 50K, 40K for a price of air garbage. It might be worth buying 4 $AAPL airtags for 100$ at least you can search your keys. Darn these dumbos </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 08:14:41 </td>
   <td style="text-align:left;"> $MSFT $GOOG $AAPL  Cramer all morning boasting how great the economy is doing...  I guess these companies can&amp;#39;t handle a little bit of interest rate hikes... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 08:13:07 </td>
   <td style="text-align:left;"> $AAPL buy now pay later. 💣☠️ crypto kids hustled. 
 https://www.reddit.com/r/Epic_Economics/comments/rx0y02/buy_now_pay_later_implodes/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 08:12:12 </td>
   <td style="text-align:left;"> $IWM so many small cap stonks straight &amp;quot;GUH&amp;#39;d&amp;quot;. When mega cap GUH? $WISH $DKNG $MSFT $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 08:10:56 </td>
   <td style="text-align:left;"> We gave our members a heads up for a potential swift move down yesterday. Our buy signals were close to hitting on several names as $SPY was making a new all time high while money flowed out of $QQQ names. However, less than a handful of our buy signals were triggered and what resulted was a swift move down(screenshot attached).  
 
Some leadership names we are watching for $SPY and latex45b303a3816b9710874a326b84d0d6f8AAPL - a leading tech name. Look for support to establish in the coming days despite it&amp;#39;s topping pattern forming.  
$TSLA - at key support levels. Ideally longs would like to see a bounce in the coming days near $1051.37 
 
For more charts and commentary  read our free blog post! &amp;quot;2022 - The Year of The Tiger&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 08:10:52 </td>
   <td style="text-align:left;"> $QQQ $AAPL $TSLA Huge moves up tomorrow, Tesla filled it’s Gap, Apple needed to cool off and  QQQ got thrashed, I couldn’t imagine holding PUTS overnight y’all going to get SMASHED in the morning 😆😆😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 08:10:34 </td>
   <td style="text-align:left;"> $AAPL Added shares 174.2 ah for quick flip. Selling tomorrow AM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 08:09:29 </td>
   <td style="text-align:left;"> $AAPL Short Short Short into double digits. Dinosaur of a company just like Exon GLTA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 08:08:39 </td>
   <td style="text-align:left;"> $AAPL making money either way. Puts are up 126%. Still Bullish on $AAPL. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 08:07:49 </td>
   <td style="text-align:left;"> $AAPL I think the earnings are going to be great but stock will tank. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 08:06:09 </td>
   <td style="text-align:left;"> $AAPL some people just want to watch the world burn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 08:05:58 </td>
   <td style="text-align:left;"> $AAPL I really just want this to have a fat ass green candle at the end here, so all the people who mistakenly hung onto their greedy puts get some overnight sweating. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 08:01:29 </td>
   <td style="text-align:left;"> $AAPL watch these noobs seller get mad when we go back to all times highs 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 08:00:59 </td>
   <td style="text-align:left;"> $AAPL bought today and will buy more in the morning if it goes down! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 08:00:41 </td>
   <td style="text-align:left;"> $AAPL weaaaaaaaak drop!!  Too weak for me to avg down my calls 😂! Try harder , let see 10-15$ drop, I will avg down. Y’all bears can’t drop apple , we will see 180s again anyways ! Watch and learn, y’all let fluffy news and fed scare y’all to sell but u know we always go back up to all times high 🤣. U will regret .. keep sellling so I can load calls . $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 08:00:07 </td>
   <td style="text-align:left;"> $AAPL open at $177.65🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:59:34 </td>
   <td style="text-align:left;"> $AAPL bounce back tomorrow. This sell off is annoying... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:58:00 </td>
   <td style="text-align:left;"> $AAPL Added 177.5 c .96 and shares at 174.2 ah. Flipping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:54:44 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #2 ticker with sweep activity where institutions are trading options urgently with 114.3K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:53:10 </td>
   <td style="text-align:left;"> $BTC.X $SPY $TSLA $AAPL $KISHU.X Itsmymoneyandiwantitnow has marked himself safe from the tiny flash crash of 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:53:07 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Jim Cramer&amp;#39;s 2022 forecast for the best-performing Dow stocks last year https://www.stck.pro/news/AAPL/20944381 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:53:02 </td>
   <td style="text-align:left;"> latex2036e98ef6253ce382fca8ec53254228SPY latex5a660ebc0344205a51d78664848ab8a9QCOM - 95% call flow
$F - 69% call flow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:50:32 </td>
   <td style="text-align:left;"> $AAPL love to see the rocket emoji’s from pumping machines again.
Tomorrow gonna be interesting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:49:35 </td>
   <td style="text-align:left;"> $AAPL juicy dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:48:37 </td>
   <td style="text-align:left;"> $AAPL  AHs Volume, 4.6 Million. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:47:01 </td>
   <td style="text-align:left;"> $AAPL the best of the best! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:42:15 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL BOO... interest rates, sell! bunch of fools.. puts*😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:40:55 </td>
   <td style="text-align:left;"> $AAPL      🍏❗️Alert❗️ Oh it’s wayyyy early…but, just had to share: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:40:25 </td>
   <td style="text-align:left;"> $AAPL $188 at close tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:39:49 </td>
   <td style="text-align:left;"> Unusual Options Activity: $AAPL is the #27 ticker with unusual activity from institutional traders with an average of 14% out of the money, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:38:36 </td>
   <td style="text-align:left;"> $AAPL scooped up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:31:07 </td>
   <td style="text-align:left;"> $AAPL Simulated 177.5 dollar CALLS for Thursday&amp;#39;s open on StockOrbit.
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:30:08 </td>
   <td style="text-align:left;"> $AAPL $TSLA $MSFT 😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:28:35 </td>
   <td style="text-align:left;"> $AAPL 
No brainer buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:27:25 </td>
   <td style="text-align:left;"> $AAPL doesn’t deserve its valuation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:26:57 </td>
   <td style="text-align:left;"> $AAPL I think we see 160 before any bounce. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:25:54 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA zomg did  you  see that  Warren Buffett dumped all of his $AAPL shares?  Yeah that&amp;#39;s because he didn&amp;#39;t.  Just buy good companies and ride this bump out.  If you wanna chase  little shitter  plays down a hole you&amp;#39;re gonna have a bad year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:21:54 </td>
   <td style="text-align:left;"> $AAPL this garbage company ruined the stock market with its valuation. Now everyone suffers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:20:14 </td>
   <td style="text-align:left;"> Apple given $142.00 PT by The Goldman Sachs Group, Inc.. https://www.marketbeat.com/r/1694822 $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:18:56 </td>
   <td style="text-align:left;"> $AAPL FINALLY  a Sale. Bull market still intact. We are still going higher </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:13:51 </td>
   <td style="text-align:left;"> $AAPL poo stock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:12:43 </td>
   <td style="text-align:left;"> $AAPL I wonder if we will get a sale here, so I can buy some more! https://youtu.be/BVAUUD6F2zw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:11:04 </td>
   <td style="text-align:left;"> $AAPL Let the market digest the news, stay cool and if you need to spend money in the market buy shares. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:11:00 </td>
   <td style="text-align:left;"> $AAPL outperforms 89% of all stocks! https://www.chartmill.com/stock/quote/AAPL/technical-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:08:54 </td>
   <td style="text-align:left;"> $AAPL 180 within a week; 200 within a month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:06:54 </td>
   <td style="text-align:left;"> $AAPL  just close eyes..disregard the nuisance. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:04:39 </td>
   <td style="text-align:left;"> $AAPL I own an iPhone since 2007 but never bought its share.  What am
I up to ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:03:36 </td>
   <td style="text-align:left;"> $AAPL long here..6 months-  $200s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:03:30 </td>
   <td style="text-align:left;"> $SPY hows it legal to manipulate the market, allow 30-1  to 300-1 leverage, allow FTDS, unlimited shorting in dark pools along with allowing short interest to be over 10% on any stock ESPECIALLY an illiquid stock let alone 20%! 40%! 60%! 100%!!!!?????? feds, SEC mainstream media all SCREAM its a &amp;quot;FAIR MARKET&amp;quot;. BUT THESE ARE THE TOOLS USED BY THE ONES WHO CONTROL MOST OF THE MARKET TO INDUCE &amp;quot;MARKET CORRECTONS&amp;quot;. IN REALITY THEY AREJUST STEALING ALL RETAIL MONEY THAT HAS ENTERED THE MARKET TO PROVIDE A BETTER FUTURE FOR THEIR FAMILY. 

 MY THEORY IS THIS IS WHY THE PENTAGON AND WORLD TRADE CENTERS WERE HIT DURING THE 9/11 TERRORIST ATTACKS. BC OUR FINANCIAL INSTITUTIONS WHO FUND HEDGE FUNDS AND MANY MORE WERE WASHING DIRTY MONEY AND THEIRMONEY ENDED UP BEING LOST 6 MONTHS PRIOR. DONT BE SURPRISED TO SEE ANOTHER WAR OR ATTACK HAPPEN FOLLOWINH THE MARKET COLLAPSE. $GME $AMC $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:01:47 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 07:00:48 </td>
   <td style="text-align:left;"> $AAPL More red tomorrow or we expecting some green? I am thinking it will bleed all this week and next may be up week until earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:58:57 </td>
   <td style="text-align:left;"> $TSLA 😯 market $AAPL $LKCO why red?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:57:18 </td>
   <td style="text-align:left;"> $AAPL anyone with intelligence and experience in the game know what happens to tech stocks with massive balance sheets when reds raise rates? I mean … wasn’t this obvious knowing the fed is about to do so? I sure hope nobody jumped in paying top prices when they could have used psychological variables and history and a bit of foresight to buy 3-5-7% cheaper right? $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:56:12 </td>
   <td style="text-align:left;"> $CRSP Cathie sold $AAPL saying it does not cure cancer and this will and now it is 220 to 69.  I feel really bad.  She believed.  But her investors will lose. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:50:32 </td>
   <td style="text-align:left;"> $SPY good news is.... Volatility is back. Plenty of money to be made! Up or down! $AAPL $TSLA $NVDA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:50:25 </td>
   <td style="text-align:left;"> $AAPL $ADBE *** jeez, sold puts a bit too early. bloody ugly market, after Fed minutes, hint at earlier liftoff on interest rates </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:50:11 </td>
   <td style="text-align:left;"> 🎁Daily watchlist recap for Jan 5, 2022!!🎁
Profit potential per 100 shares is $12,193

$AAPL $TSLA $MYNZ $LGVN $PFE PYPL MA

✔Follow and turn on notifications for more amazing trade ideas!!

#unitedtraders #teamwork #finance </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:49:54 </td>
   <td style="text-align:left;"> 🎁Daily watchlist recap for Jan 5, 2022!!🎁
Profit potential per 100 shares is $12,193

$AAPL $TSLA $MYNZ $LGVN $PFE PYPL MA

✔Follow and turn on notifications for more amazing trade ideas!!

#unitedtraders #teamwork #finance </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:48:19 </td>
   <td style="text-align:left;"> $AAPL Any derivative involving time will never work for punters. Time is your friend. Long stocks work, but are exhausting admittedly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:48:11 </td>
   <td style="text-align:left;"> $BTC.X it’s how u can tell it’s a real sell of in markets not a dip. When big money from around the world sells they sell everything. It’s a rush to the dollar and everything else goes down. I will rebut btc at 19-34900 and in between, I will re buy $SPY  starting under 450 (could be too early but worth the start) and I will load the china markets $YINN etc in the $5.90-$7.29 range $QQQ is going to get absolutely slammed with rate hikes. I hope the newbies understand how overvalued these pigs are and how impossible it is for them to perform under rate hikes I know people like @OldFngGuy has enough knowledge to know what happens to valuations in tech and companies like $AAPL with that much cash on balance sheet when rates rise. And I know he will help people not too lose money by chasing light dips. TO BE CLEAR to the new kids that have only seen this past year and think it only goes straight up? Last fed raise it dropped 20% WITHOUT Covid issues. trade and buy in pieces not immediately </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:45:44 </td>
   <td style="text-align:left;"> $AAPL such a terrible day in the markets .  What caused the meltdown? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:45:13 </td>
   <td style="text-align:left;"> What Investors Should Know About Amazon, Sony And John Deere&amp;#39;s Latest To Push Into The Electric Vehicle Sector  $TSLA $F $GM $SONY $AAPL 

https://newsfilter.io/a/516ba1b3ffafe6fc5bd9f0d8bc3edcd8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:40:38 </td>
   <td style="text-align:left;"> $AAPL it’s the feeling of not being able to catch a break no matter what you do 😕 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:40:17 </td>
   <td style="text-align:left;"> $AAPL $TSLA $GOOGL could have sworn Nancy peloci was buying calls on the martet not puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:35:30 </td>
   <td style="text-align:left;"> $AAPL is one of the fast growing companies . Berkshire Hathway has the most valued stock but AAPLE is the best one. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:34:16 </td>
   <td style="text-align:left;"> $AAPL https://nypost.com/2022/01/05/warren-buffetts-apple-bet-yields-120b-in-on-paper-windfall/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:33:35 </td>
   <td style="text-align:left;"> $AAPL $TSLA $MARA $GREE $BTC.X 

Don&amp;#39;t fear shorting, i genuinely made 450K out of 120K last 3 months  shorting/puts overvalued companies specifically CRYPTO MINERS.

You gotta bite whenever there&amp;#39;s money, nothing unethical in shorting.

Make up your losses already, start shorting.

Use all of ur tools.🧸🤞

This place about to blow, don&amp;#39;t miss out.💣💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:33:22 </td>
   <td style="text-align:left;"> $QQQ remember $AAPL $AMZN $GOOG $FB are still the giants and will be for a very long time, they are not at astronomical levels and that is the heart of the QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:31:50 </td>
   <td style="text-align:left;"> $SPY $qqq alright $AAPL we need you to go to 4 trillion. You are our only hope. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:31:21 </td>
   <td style="text-align:left;"> $BTC.X the first to get hit.it’s not just that they’re not injecting liquidity, they’re taking liquidity out. Anyone knows the part of its balance sheet that went to #FAANG stocks past two years ?

$AAPL $TSLA $GOOG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:30:37 </td>
   <td style="text-align:left;"> $AAPL $180 by this friday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:29:11 </td>
   <td style="text-align:left;"> $AAPL  🍏 In the “final second” of the Close, 9.5 Million AAPL Shares traded to the “Buy Side”. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:28:32 </td>
   <td style="text-align:left;"> $UVXY $SPY guys get on reddit. The board here are so stupid.
$aapl $TSLA $BA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:28:00 </td>
   <td style="text-align:left;"> $AAPL Don’t trade Apple, invest! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:26:32 </td>
   <td style="text-align:left;"> $AAPL Really CNBC buy IBM CSCO INTC HP ?? Nope </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:25:40 </td>
   <td style="text-align:left;"> $AAPL is spoiling my ass.🤞🧸

My ass is greedy tho. 
Promised my followers for profits porn.
Here you go.
Again i dont respond to dms. 
Charts looks ugly, No signs of recovery.

am holding. 

$TSLA $GOOGL $BTC.X $MARA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:24:11 </td>
   <td style="text-align:left;"> Apple, Carnival, JPMorgan Stocks Provide Entry Point For Bullish Traders: How To Play It $SPY $AAPL $CCL $JPM https://www.benzinga.com/trading-ideas/technicals/22/01/24914763/apple-carnival-jpmorgan-stocks-provide-entry-point-for-bullish-traders-how-to-play-it#.YdYaWwkuCNw.twitter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:24:09 </td>
   <td style="text-align:left;"> $AAPL made in China. Safety play? Lmao
Get wrecked. 
 https://www.reddit.com/r/Epic_Economics/comments/rwydlr/meme_stonks_lowest_close_in_a_year_no_end_to/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:23:29 </td>
   <td style="text-align:left;"> $AAPL this always happens to me.  i think things are trending down and going to fall.  buy puts.  then next thing you know, all the talk on CNBC is about markets hitting ATH.  FML  i can&amp;#39;t do anything right this year or any previous year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:21:06 </td>
   <td style="text-align:left;"> $AAPL Powell was ok until today. The one day he really needed to be dovish he wasn’t. Ass </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:17:11 </td>
   <td style="text-align:left;"> 01/04 #DayTrade Ideas Recap:

$AAPL 📉 $1.43 —&amp;gt; $2.31 | +62%
$CHWY 📉 $1.06 —&amp;gt; $5.50 | +419%
$SQ 📉 $1.87 —&amp;gt; $5.50 | +194%

Video: https://youtube.com/watch?v=Ep4q4NAUzrM

Join the COmmunity at https://chartingoptions.com/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:15:39 </td>
   <td style="text-align:left;"> $SPY  my shit plays today was not knowing fomc minutes were today, held $QQQ 493P for .51c overnight as hedge for my other longs in $AAPL, $MSFT $TSLA, sold them for 2x early on before knowing it was FOMC minute drop today, that went to 9$ almost 20x gain(left 17k on the table), entered 388P for 0.16c as hedge into the event, sold for 4x that went on to ~12x into the close. Not too salty but these somehow limited my losses. in on some 1020c tsla 180c aapl with 370p 1/10 on QQQ as hedge + 466P 1/7. I need big moves either way fingers crossed, 80% in cash for that dip if it happens </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:14:03 </td>
   <td style="text-align:left;"> $TSLA $AAPL $MDB   $MRNA 🥲🥲🥲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:12:17 </td>
   <td style="text-align:left;"> $AAPL 

Wtf! 

I was wondering if you have read the FOMC minutes ..

My reaction - it’s normal .. NOT hawkish as media described ..

I am like fk you media for spreading bullshit FUD .. playing with short side…

The FOMC clearly signalize for normal safe health of US financial system
and more liquidity for US Treasury.

This doesn’t warrant such 5 dollars off of this stock.

This is over reaction and this is illegal shorting terrorism! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:12:13 </td>
   <td style="text-align:left;"> $AAPL $MSFT $NVDA $AMD and other similar.  These are taking a hit in the market, but it&amp;#39;s game playing by the MM and retail shorters.  The fundamentals of these companies are very strong.  Buy the dips now, it won&amp;#39;t be a bargain price for long.  For those waiting to see a half-price sale, you can forget that dream. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:09:54 </td>
   <td style="text-align:left;"> $BTC.X doubters to believers 🤞🧸

$AAPL $MARA latexe5452341dce5f8034c4da028c613fdc2TSLA
$AAPL 
 
Emotional states of bulls, in the Nasdaq 2021/2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:07:52 </td>
   <td style="text-align:left;"> $AAPL blood is running on the streets. Can’t go wrong adding more shares </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:05:17 </td>
   <td style="text-align:left;"> $AAPL did this really tank because of the fed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:05:17 </td>
   <td style="text-align:left;"> $AAPL here comes the apple pump again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:05:03 </td>
   <td style="text-align:left;"> $AAPL https://finance.yahoo.com/news/apples-road-to-4-trillion-starts-with-its-rumored-headset-and-apple-car-180910042.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:04:45 </td>
   <td style="text-align:left;"> $AAPL just laughing how fast this goes back up after all this bs talk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:04:43 </td>
   <td style="text-align:left;"> $SRNE $Aapl market cap is $3 trillion. We could beat that… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:03:24 </td>
   <td style="text-align:left;"> $AAPL Biden can’t fix the economy. Tying his shoes in the morning is his only goal. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:02:20 </td>
   <td style="text-align:left;"> $AAPL well that 3T was short lived </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 06:00:08 </td>
   <td style="text-align:left;"> $AAPL 160P Exp:19-Jan-24 ↓  🔥 Total(Day): $171,325 
#UnusualActivity 
 
 
Sign-up free for beta ver.:https://app.jarvisalerts.com 
charts: courtesy of finviz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:59:18 </td>
   <td style="text-align:left;"> $AAPL $TSLA $SPY the volumes at the end of the day looks encouraging for a nice move tomorrow for money jumping back into the stock.  AAPL and SPY just does not have 2% days and the 1-2 trading days after, $$$$$.  This is how easy it will be tomorrow to have a 500 point green day and close at new highs, again! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:59:05 </td>
   <td style="text-align:left;"> $AAPL 170 - 172 minimum. If that doesn&amp;#39;t happen in a week or less I&amp;#39;d be surprised. $QQQ looking to finally show downtrend on its monthly / yearly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:58:56 </td>
   <td style="text-align:left;"> $AAPL $180 by friday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:53:12 </td>
   <td style="text-align:left;"> How to become a successful Investor in the share market🌄🌞
1. Goal setting✔️
2. Knowledge ✔️
3. Right Decision✔️
4. Keep calm and carry on!✔️
5. Risk Aversion✔️
6. budget✔️

$TSLA  $NIO  $AAPL  $JPM  $LCID </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:53:01 </td>
   <td style="text-align:left;"> $AAPL Added 177.5 c eod </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:52:09 </td>
   <td style="text-align:left;"> $LCID NASDAQ 100 future drops lager , 500 points, that&amp;#39;s  making $TSLA, $AAPL, $LCID, $NVDA… down too.  The market is skittish because of Federal’s hint. Actually, automation trading system is skittish. Tomorrow it will bounce for sure.  Buy $LCID under $37 you win tomorrow. 📈📈📈💯👈✅ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:52:07 </td>
   <td style="text-align:left;"> $AAPL GIVE ME $160 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:50:59 </td>
   <td style="text-align:left;"> $AAPL i&amp;#39;m afraid to look at my account today.  it&amp;#39;ll depress me.  i&amp;#39;ll look at it on friday if we have 2 up days.  :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:50:42 </td>
   <td style="text-align:left;"> $AAPL Simulated 177.5 dollar CALLS for Thursday&amp;#39;s open on StockOrbit.
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:50:23 </td>
   <td style="text-align:left;"> $AAPL this has a $8.00 correction coming this week! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:49:48 </td>
   <td style="text-align:left;"> $AAPL J Pow is an idiot. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:49:39 </td>
   <td style="text-align:left;"> Today&amp;#39;s video discusses 2 things to be aware of heading into 2022, and top-down analysis of over 30 stocks including $SPY $QQQ $MSFT latex76f50bc147c06407d3157914a39d2c85TSLA
$AAPL 
 

Believe me that not even the Universe is eternal, much less will this bubble of Wall S be, which is already in its last breath. .
And remember that historically, it is the technological ones that generate the stock market bubbles. .
At the moment, the weekly EMA20 has been pierced, but, one would expect a technical recovery tomorrow. . something, I understand, inconsequential, and that will not alter the trend. .
El MACd en vista mensual, comienza a dar una señal de venta por  6ta vez en la historia del Nasdaq  . .That could translate into a decompression of about 4 thousand points
Coinciding with the EMA200 in weekly view (orange line).
It could go on later, but that is the projected scenario for the short / medium term. .
........ ** // </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:47:04 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:46:27 </td>
   <td style="text-align:left;"> $AAPL In 2020, The New York Times reported that Apple receives an estimated $8-12 billion per year in exchange for making Google the default search on its devices. According to one analyst, Google&amp;#39;s payment to Apple in 2021 to maintain this status quo may have reached up to $15 billion.

I don&amp;#39;t see anything wrong with this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:45:41 </td>
   <td style="text-align:left;"> $AAPL waited for the so called rally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:43:51 </td>
   <td style="text-align:left;"> $AAPL threw  $20k and it goes down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:43:21 </td>
   <td style="text-align:left;"> $MSFT  I trust  $MSFT , $AAPL  , $GOOGL $NVDA   for long.  No trust TSLA, RIVN, NKLA, </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:42:18 </td>
   <td style="text-align:left;"> $AAPL this stock ruined the market. The biggest bubble ever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:40:47 </td>
   <td style="text-align:left;"> $AAPL Hello Traders
We are alerting AAPL long. Trending close to All time highs, we
anticipate AAPL to continue to show strength over $180 into the coming
months. 

Potential Trades:

- Long shares - Buy Under $178.50
Target: Over $200
Stop Loss: under $170.5

- Buy Call Options - Strike $190 Calls. Expiration 3/18/2022. Current
Bid Price at $4.35/contract
Profit Goal: +60%
Stop Loss: 30% (varies depending on trade)

Profit goals and risk stops are unique to every trader. Be sure to
manage the trade based on respective risk &amp;amp; goals.

As always, positioning in a trade is much easier by scaling/sizing in.
This benefits the trader because it allows them to get a more optimal
average price, since all entries can&amp;#39;t be perfect. In doing that, it
minimizes risk potential on the trade.

Dm @iTradeSmartAlertsbot on telegram for more! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:40:41 </td>
   <td style="text-align:left;"> $aapl I don’t have diamond hands. Same puts are now at $2.3 at close and could be $3 or $10 tomorrow. Wtf.  Had a great conviction that it will drop after massive run, had time of 2+ weeks and is a RED day. But sold early at cost with almost no gain.  DONT BE LIKE ME. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:37:58 </td>
   <td style="text-align:left;"> $aapl Third level support at $174.41

Shorts may get squeezed if any rally. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:36:31 </td>
   <td style="text-align:left;"> The Difference in 10 years $SPY $TSLA $AAPL $NIO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:36:18 </td>
   <td style="text-align:left;"> $AAPL I predicted 175 by eow. I sold my puts and made a pretty penny. Now I’m loaded on calls!!! BUY THE FEAR!!! 💸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:35:56 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $AAPL is the #1 stock that institutions are trading over rolling 5 day window with 424.3K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:34:55 </td>
   <td style="text-align:left;"> $DIDI $14 &amp;lt; soon. IPO Price. Believer!

Investors: Softbank, Tencent, $BABA , $UBER, $AAPL...... 
TAM 1.6Billion
Daily rides: 25 Million
Active customers: 500 Million+ (1.5 times US population)

BUY NOW: low downside risk, infinite upside reward. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:34:24 </td>
   <td style="text-align:left;"> $AAPL Feeling sorry for pumpers(not
Longs) who were saying $200 by EOW for no fucking reason. It will go to $200 but not healthy run. Dont expect a 10% move up every day. This market was running like a casino bets. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:34:23 </td>
   <td style="text-align:left;"> $AAPL bought at 179.80 at the eod. What a steal! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:33:34 </td>
   <td style="text-align:left;"> $AAPL Sell and take 50% gains or reenter on dips? decisions </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:33:31 </td>
   <td style="text-align:left;"> $MSFT 180 $AMZN 2400 $AAPL $90 if these follow the same trends as growth stocks that sold off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:32:14 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-01-05 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=P0FCmYwN5aQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:30:50 </td>
   <td style="text-align:left;"> $AAPL Double TOP, sell the News, 3T pull back, 170 is a natural retrace level on the chart 1D 1 YR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:30:35 </td>
   <td style="text-align:left;"> $AAPL this rallied 40% past 6 months. Ofcourse not the bubble is gonna pop back to reality @ 85$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:27:55 </td>
   <td style="text-align:left;"> $AAPL right side is bullish on multiple timeframes.  We only like to buy it in 3, 7 or 11 swing at the blue boxes.  Can still see some more upside and new highs before another larger pullback takes place.  Like to watch the $NQ_F at equal leg which can give some sense of timing for larger cap tech for buy areas. We don’t like to the chase the upside at this point.   #Elliottwave #Trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:26:13 </td>
   <td style="text-align:left;"> $AAPL this time next week we will be talking about new ATH.  you just wait and see </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:26:02 </td>
   <td style="text-align:left;"> $AAPL Which one looks like it’ll have a better year? This or $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:25:00 </td>
   <td style="text-align:left;"> $AAPL   🍏 Deep Think:  The Close:  Negative Mkt Reaction to FOMC Minutes,  which were “interpreted” as more Hawkish than expected.  Remember, time has passed, since the last FOMC Meeting, with Omicron Case Count expanding in the interim.  Most importantly, every Mkt Participant must ask:  What can the Mkt do to change the Fed’s Trajectory?  The answer:  Absolutely, nothing.  When the Mkt cannot muster against “nothing”, then it “digests” the “Fed News”, and moves forward.  The Mkt, “prices in the News”.  It did that today, by “over reacting” to the down side.  True “price discovery”, will begin tomorrow morning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:24:55 </td>
   <td style="text-align:left;"> $AAPL nothing wrong with pull backs and consolidation.  Let&amp;#39;s deal with it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:24:41 </td>
   <td style="text-align:left;"> $AAPL using the Samsung Z Fold3 to make some money📱 https://youtu.be/25QPjVAyPlk Put Puts... Watch and let me know what you see! $study </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:24:36 </td>
   <td style="text-align:left;"> $AAPL Hopes and dreams of 180 are over. Down the drain </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:23:48 </td>
   <td style="text-align:left;"> $TSLA $SPY $AAPL $QQQ crash and burn baby keep buying puts you&amp;#39;ll be fine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:21:03 </td>
   <td style="text-align:left;"> $AAPL anyone see that massive spike @ close to $179.80??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:20:28 </td>
   <td style="text-align:left;"> $AAPL Every year same shit :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:20:21 </td>
   <td style="text-align:left;"> $AAPL   $110 ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:20:19 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL 
Back to eating ramen noodles for dinner tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:19:25 </td>
   <td style="text-align:left;"> $SPY $AAPL $QQQ  
 
Good evening ! 
 
We bought 1/7 AAPL 177.5 C for swing .96 avg holding overnight. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:18:17 </td>
   <td style="text-align:left;"> Top Flow for Today 😲: $AAPL with a single PUT Trade for total premium worth $948.2K Ranking #12 Today | This was a TRADE trade.  | Visit SweepCast.com or Join our Premium Room For Access! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:17:30 </td>
   <td style="text-align:left;"> $AAPL   $95.? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:17:18 </td>
   <td style="text-align:left;"> $AAPL Another day of running  with the bears. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:16:27 </td>
   <td style="text-align:left;"> $SPY WHEN ASIA MARKETS WAKE UP AND SEE THE SEA OF BLOOD ITS GAME OVER $QQQ $IWM $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:16:26 </td>
   <td style="text-align:left;"> $AAPL is begging for $170 hopefully she wants to go back to 160s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:16:25 </td>
   <td style="text-align:left;"> $AAPL commercial on German TV saying: &amp;quot;supply bottlenecks possible &amp;quot; - is this 
- necessary 
- stupid 
- or genius 
?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:15:43 </td>
   <td style="text-align:left;"> latexca2193a25071966b9f3489cae025ed70TSLA 
$AAPL 
 
I would recommend to the Nasdaq bulls that they ask for their turn to have a vasectomy. .and prepare for a mass sodomization. . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:14:54 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $WMT $UVXY    
 
Days like today are a welcome sight to the savvy investor who was rebalancing overweight positions into the end of the year and executing a game plan to act on local price weakness. Nobody made money running from a sale. The only thing that changed today was price. The earnings trajectory didn&amp;#39;t change, the economic outlook didn&amp;#39;t change, just price. Price generally gets adjusted to reflect the value of the equity risk premium. It&amp;#39;s why the average 3m gain for the SPX after the first rate hike is just .3%. There is usually some pricing in ahead and through, but a catch up thereafter to reflect an almost flat market post first rate hike.  
 
You&amp;#39;re either following the data or flailing about, chasing and reacting without a plan! Be savvy  mate ;-) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:14:48 </td>
   <td style="text-align:left;"> $SPY HATE TO SAY UT, BUT GET READY FOR SEPTEMBER 11TH 2001 ALL OVER AGAIN. MOST LIKELY BLAME IT ON SOME BULLSHIT AS BUSH DID SAYING THEY HATE THE FACT WERE A FREE COUNTRY. IN REALITY THEY OUR VERY OWN GOVERNMENT AND FINANCIAL INSTITUTIONS MAKING SHADY DEALS AND TAKING MONEY FROM TERRORIST ORGANIZATIONS FROM AROUND THE WORLD TO WASH IT LEGALLY THROUGH OUR CORRUPT FINANCIAL SYSTEM ONLY FOR THEM TERRORIST GROUPS TO LOSE 100S OF BILLIONS DOLLARS DUE TO &amp;quot;MARKET CYCLES&amp;quot; OR &amp;quot;WEAK ECONOMIES&amp;quot; OR ANY OTHER BULLSHIT EXCUSE. 

THIS IS LITERALLY THE SAME PLAY BOOK PRIOR TO SEPTEMBER 11TH. EXCEPT A WHOLE LOT MORE MONEY BEING STOLEN FROM OUR FINANCIAL INSTITUTIONS AND GOVERNMENTS.

WELCOME TO AMERICA $GME $AMC $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:14:36 </td>
   <td style="text-align:left;"> $AMD $NVDA $LSCC $AMBA $AAPL DRY POWDER DAY!! that dip needed to be bought if you are bullish with a bit of a timeframe. Tomorrow might be balls-deep-day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:14:34 </td>
   <td style="text-align:left;"> $AMZN $UBER $AAPL 

Our AI-Holly system will give suggested Entry Signals that are statistically weighted. There will be an accompaniment of suggested Exit Signals based on different risk management for intraday trade management. 

It is important to note that while Exit Signals are for intraday, many of Holly&amp;#39;s entries go on to be successful multi day holds.

tinyurl.com/laskterdy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:13:35 </td>
   <td style="text-align:left;"> $AAPL what a opportunity to load up !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:12:58 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL 
We will bounce back strong </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:12:33 </td>
   <td style="text-align:left;"> $AAPL had 30 $170p for 1/21 . Sold at $1.56 each even cost . Now it is $2.3 each. Almost $2500 loss..of profit.. fk.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:12:21 </td>
   <td style="text-align:left;"> $AAPL $AMZN $MSFT Time to go shopping!
Act wise!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:12:00 </td>
   <td style="text-align:left;"> $AAPL   $110? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:11:51 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL Snopes confirmed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:11:49 </td>
   <td style="text-align:left;"> $AAPL woke up to red across the board. If AAPL dumps like this I check the other FANGS. What spooked and caused this dump? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:11:15 </td>
   <td style="text-align:left;"> $QQQ $aapl $fb $mcd in severe corrections, the &amp;quot;privates&amp;quot; may be first to be sold, but they always come for the &amp;quot;generals&amp;quot;. If you have profits in even the big loved stocks like Apple &amp;amp; McDonalds, take them, or at least sell some. After hours market open. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:10:00 </td>
   <td style="text-align:left;"> $AAPL has a Return On Assets of 26.97%. This is amongst the best returns in the industry. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=fundamental-analysis&amp;amp;key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:09:53 </td>
   <td style="text-align:left;"> $AAPL  $105 ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:09:51 </td>
   <td style="text-align:left;"> $AAPL Bought 400 1/7 $170 puts today at $.10, sold just before the bell at $.42. Not a bad day! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:09:48 </td>
   <td style="text-align:left;"> $SPY .70 to 3$ per put $AMZN $TSLA $AAPL $NIO 🩸🔥💵✅ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:09:47 </td>
   <td style="text-align:left;"> $AAPL why is the stock still over $140 , come on guys DON&amp;#39;T get screwed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:09:47 </td>
   <td style="text-align:left;"> $SPY $NIO $XPEV $AAPL
This is how SHOrts never need to cover…

Who things Warren Buffet lost money?

MANIPULATED! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:09:03 </td>
   <td style="text-align:left;"> $NIO china is future buy Chinese $SPY $TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:08:55 </td>
   <td style="text-align:left;"> $AMD $NVDA $FB $AAPL $MU Today was rough.  What will tomorrow bring us. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:08:22 </td>
   <td style="text-align:left;"> $AAPL 3Trillion dollars then comes fed &amp;quot;minute&amp;quot; what a bear shake up, feeling like second nature timing ha??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:08:05 </td>
   <td style="text-align:left;"> $AAPL next Trillion company on your list? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:08:03 </td>
   <td style="text-align:left;"> $AAPL support around 173.50. Could get interesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:07:40 </td>
   <td style="text-align:left;"> $AAPL we haven’t had a dip like this since Black Friday! I’m buying at this prices! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:07:09 </td>
   <td style="text-align:left;"> $AAPL dont forget about all the phones they wont sell after the mass vaxtinction </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:06:38 </td>
   <td style="text-align:left;"> $MSFT Todd CNBC you know today cash was King dude-eptic fail.  I made coins galore in 2021. Cramer we hold $AAPL-Nope not today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:06:23 </td>
   <td style="text-align:left;"> $AAPL Looks like another opportunity to buy shares again 😌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:06:10 </td>
   <td style="text-align:left;"> Take your money our of $MSFT  and $AAPL come and join $NNDM market cap under 1B, 5 companies together with 1.385B cash.... rates hike ? Who gives a shit when you already have money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:06:09 </td>
   <td style="text-align:left;"> $AAPL guess shorts really took over the market. They shorted everything and banked on it smh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:05:07 </td>
   <td style="text-align:left;"> $AAPL $DKNG $SOFI ADDING ALL OF THESE FOR SWINGS FIRE SALE FOLKS 🔥🔥starter amount </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:05:02 </td>
   <td style="text-align:left;"> $AAPL excuse my language but what the actual fuck...174? Really? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:04:58 </td>
   <td style="text-align:left;"> $AAPL Anyone smell a Trans-Bear market? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:04:48 </td>
   <td style="text-align:left;"> $AAPL 

CALLING ALL BEARS, LETS HEAR YOUR SHIT UNTIL YOU GO BACK TO HIBERNATION 

LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:04:35 </td>
   <td style="text-align:left;"> $AAPL best stock no matter which way you swing.....green red doesn&amp;#39;t matter!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:03:46 </td>
   <td style="text-align:left;"> $AAPL I buy only 🍏 for my retirement plan. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:03:45 </td>
   <td style="text-align:left;"> $MSFT $AAPL  Started two 2024 in the money leap positions at close today.  IMO they are due for a bounce close to ER. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:03:33 </td>
   <td style="text-align:left;"> $SPY hahaha follow for more @whackyzachy $AAPL $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:03:29 </td>
   <td style="text-align:left;"> $AAPL first time made money on a straddle....what an awesome market!!  Love Apples....... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:03:03 </td>
   <td style="text-align:left;"> latex6f7466c554224e56daf2307fad943382SNDL (Vol: 93.96M) 
$AAPL (Vol: 91.51M) 
 
Alerts &amp;amp; Technical Analysis via tradethehalt.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:01:58 </td>
   <td style="text-align:left;"> $AAPL SNEAKY GRENADES 💣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:01:54 </td>
   <td style="text-align:left;"> $AAPL next point 172.78 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:00:11 </td>
   <td style="text-align:left;"> $AAPL getting nasty </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 05:00:08 </td>
   <td style="text-align:left;"> $AAPL one of those saved by the bell sort of days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:59:20 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:59:06 </td>
   <td style="text-align:left;"> $AAPL Ovnght calls till 9:45 then more puts for Fed fears. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:58:53 </td>
   <td style="text-align:left;"> $AAPL might be more red here tomorrow... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:58:49 </td>
   <td style="text-align:left;"> $AAPL 

Jeez </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:58:08 </td>
   <td style="text-align:left;"> $AAPL that buffet sure walked away with money leaving alot of you guys hurting but go on praise him for the trade </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:58:04 </td>
   <td style="text-align:left;"> $AAPL $TSLA $BTC.X $SPY 

You doing good newbies...keep it up!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:57:53 </td>
   <td style="text-align:left;"> $AAPL Sold my protection way to early today argggggg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:57:33 </td>
   <td style="text-align:left;"> $AAPL yuckity yuck yuck. Oh well, we&amp;#39;ll be back to 3T soon enough. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:57:14 </td>
   <td style="text-align:left;"> Stopped out most of the names today, now sitting mostly cash 6% down for 2022🤨 super tempted for $AAPL and $NVDA but will hold off today. Need to resist </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:57:02 </td>
   <td style="text-align:left;"> $AAPL 170 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:56:51 </td>
   <td style="text-align:left;"> latexee0bfb57eb91cb1d13989645c5c9b358TSLA 
$AAPL 
 
Strong selling force, and closing at absolute daily lows. . It seems that at last, Tulipomania has blossomed. . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:56:38 </td>
   <td style="text-align:left;"> @GoodieGood buy the fear like a muufu! Good shit takers. I gotta miss out 😣 $amzn $tsla $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:56:28 </td>
   <td style="text-align:left;"> $AAPL 42 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:56:00 </td>
   <td style="text-align:left;"> Unusual Option Alert on $AAPL $938,448 call block traded with $30.0 strike expiring on 2023-01-20. Via: https://www.stockgrid.io/optionsflowcumulativestats/AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:55:36 </td>
   <td style="text-align:left;"> $AAPL under the 21dma on the daily as of now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:55:31 </td>
   <td style="text-align:left;"> $AAPL 

Crazy short attack terrorism going on !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:55:10 </td>
   <td style="text-align:left;"> $AMZN  AMZN deep charting weekly shows that this sell off is overdone. 📈📈📈. This is  crazy. I am buying the fcking dip. $baba $BA $AAPL $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:55:05 </td>
   <td style="text-align:left;"> $AMC puts called out two days ago. Up over 60% already. Link in bio.
$SPY $TSLA $AAPL $SQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:54:01 </td>
   <td style="text-align:left;"> $AAPL lets shave off $40 over the next month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:53:48 </td>
   <td style="text-align:left;"> $AAPL $TSLA $BA $F CAN SOMEONE PLEASE GIVE ME GOOD NEWS....WTF! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:53:05 </td>
   <td style="text-align:left;"> $AAPL People shorting this since the 3rd Jan, up trend are making a shity 5%. Common people are you all that desperate </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:53:02 </td>
   <td style="text-align:left;"> $AAPL I&amp;#39;m so sorry for the Tesla people. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:52:52 </td>
   <td style="text-align:left;"> $AAPL going to slingshot up to 180 by morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:52:44 </td>
   <td style="text-align:left;"> $GOOG $AAPL  you know you&amp;#39;re King Kong when Google pays you to stay away. Google was sued for paying Apple billions of dollars to not get into search business. Looks bad! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:51:49 </td>
   <td style="text-align:left;"> $AAPL 

See another short attack at close of EOD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:51:40 </td>
   <td style="text-align:left;"> $SPY $TSLA $NIO latexa79fe7f83bbb6306e2164e87f11dc8ce. That’s 7500$ profit 🍰🏦🩸🔥💵✅ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:51:13 </td>
   <td style="text-align:left;"> $AAPL 
Biden, Powell and Fauci.

Fcuking it all big time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:50:36 </td>
   <td style="text-align:left;"> $AAPL another headfake </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:50:03 </td>
   <td style="text-align:left;"> $AAPL 
What’s a good “Buy” price on this? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:50:00 </td>
   <td style="text-align:left;"> $AAPL 

The trend indicate oversold…

People keep shorting whatever they like for no reason! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:49:14 </td>
   <td style="text-align:left;"> $AAPL what a garbage market. Covid overtakes it all fnr. Like clock work </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:47:48 </td>
   <td style="text-align:left;"> $AAPL give me 180! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:46:50 </td>
   <td style="text-align:left;"> $AAPL don&amp;#39;t think will see red or any dip tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:46:17 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMD $AAPL $AMC well fuck. Gonna need those christmas presents back for my broker. Rebound tmr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:45:57 </td>
   <td style="text-align:left;"> $AAPL $SPY You are still buying? I wonder if you boomers know others stocks and companies in America. Very soon 3T will become 300B.  
 
$UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:44:33 </td>
   <td style="text-align:left;"> $AAPL fucking the down trend is more then the uptrend, sadly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:44:16 </td>
   <td style="text-align:left;"> $AAPL bull call sweeps next move up coming soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:44:13 </td>
   <td style="text-align:left;"> Google Pays Apple Billion Of Dollars To Keep Cupertino Out Of Search Business: Lawsuit Alleges  $GOOGL $GOOG $AAPL 

https://newsfilter.io/a/f69c2a28ce8ca1dc1c25d7fbd91fe155 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:44:12 </td>
   <td style="text-align:left;"> $AAPL probably continues decline tomorrow Like the rest of the market. Correction after insane market bull ride. As always, if it goes up quickly it comes down as well. Just know when to buy and sell. Those who thought it would continue to rally to 200, should reconsider if they are fit for investing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:44:10 </td>
   <td style="text-align:left;"> $AAPL $PLTR $TSLA $SHOP god I am going to have a feast this week.

fire sale once again lads. Get em while they hot </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:44:05 </td>
   <td style="text-align:left;"> $AAPL fingers crossed for 170 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:43:59 </td>
   <td style="text-align:left;"> latex7cf131548419607741857201dac816ebTSLA 
$AAPL 
 
If you are one of those who only go long, I would recommend that you forget about equities for a long time. .
Now. . If you want to lose money, you have come to the right place. .
#NDX #FIBO #ROUNDED ROOF #WEEKLY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:42:50 </td>
   <td style="text-align:left;"> $AAPL be greedy when others are fearful… I believe that applies here ✌🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:42:04 </td>
   <td style="text-align:left;"> $AAPL bought puts this am, just sold and loaded up on calls. Whatever makes money, I’m going with that 👍🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:41:27 </td>
   <td style="text-align:left;"> BRIDGETECH SIGNS 34.&amp;lt;&amp;gt; BILLION-SCALE SUPPLY AGREEMENT WITH $KT

https://m.stock.naver.com/index.html#/domestic/stock/030200/news/view/277/0005025403

$AAPL $SPY $GOOG $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:40:59 </td>
   <td style="text-align:left;"> $AAPL The only green I have is my AAPL calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:40:16 </td>
   <td style="text-align:left;"> $AAPL 180 calls are moving, were at .40 and now at .60 and growing....TONS of volume. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:39:59 </td>
   <td style="text-align:left;"> $AAPL who in their right mind would sell aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:39:41 </td>
   <td style="text-align:left;"> So no more helicopter 💰 from the FED &amp;amp; rising rates. $ARKK and majority of its holdings in for a long ride down this year. Those trying to buy bottoms in this 💩 will get their asses handed to them. Better to just buy the dips in profitable beasts that have bright futures $googl $aapl $fb $amzn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:39:18 </td>
   <td style="text-align:left;"> $AAPL There&amp;#39;s no way this drops this much EOD, and it doesn&amp;#39;t have another sell off at the opening bell tomorrow. Today&amp;#39;s market action is going to scare the shit out of plenty of people and they&amp;#39;ll sell in the AM. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:38:16 </td>
   <td style="text-align:left;"> $AAPL $FB $GOOG $NVDA $AMZN 

Keep investing. Keep compounding. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:37:10 </td>
   <td style="text-align:left;"> $UVXY In this corner, UVXY and this one , $SOXS , 

LET&amp;#39;S GET READY TO RUMBLE!!!!! 

$SPY $AAPL $SOXX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:36:12 </td>
   <td style="text-align:left;"> $AAPL Almost here....🙃 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:34:14 </td>
   <td style="text-align:left;"> $AAPL Must be a wallstreetbets  push on.  :)) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:33:26 </td>
   <td style="text-align:left;"> $AAPL who’s smart enough to buy today’s dip?🙋‍♂️? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:32:29 </td>
   <td style="text-align:left;"> $AAPL watching time and sales.  There are idiots still trying to short this stock. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:32:28 </td>
   <td style="text-align:left;"> $AAPL bulls pound this harderrrrrr 🍏🍏🍏🍏🍏👊🏼👊🏼👊🏼👊🏼👊🏼👊🏼🤲🏻🤲🏻🤲🏻🎉🎉🎉🍏🙏🏻💪🏻💪🏻💪🏻💪🏻💪🏻💪🏻💪🏻💪🏻🍏🍏🎉🎉🎉🍏🍏🍏🍏🍏🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:31:51 </td>
   <td style="text-align:left;"> $TSLA $AAPL 

These will be flight to safety once the initial scare is done. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:31:29 </td>
   <td style="text-align:left;"> $TSLA $SNE $AAPL Sony also could be competition and beat Apple to release. The future of EV looks full of competition. Good fir consumers and any company ok with a piece of pie. Not ok for Tesla and investors hoping to own the future EV space.  https://www.marketwatch.com/story/sony-announces-new-electric-vehicle-unit-rolls-out-prototype-suv-at-ces-2022-11641356454 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:31:16 </td>
   <td style="text-align:left;"> $AAPL Buying here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-06 04:30:41 </td>
   <td style="text-align:left;"> $AAPL bought </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 10:04:47 </td>
   <td style="text-align:left;"> $TSLA well it better be fucking hard green tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 10:02:36 </td>
   <td style="text-align:left;"> $TSLA If you are up 1000% and did not take profits, you deserve to lose it all. 

Even Elon sold significant amounts of his equity, and no not just for taxes you gullible bulls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 10:02:33 </td>
   <td style="text-align:left;"> $TSLA What is this new PT of $325 😲, how does Barclay come up with that? 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 10:01:43 </td>
   <td style="text-align:left;"> $TSLA 1125 area early then back to 1080 area my guess but tomorrow is a bitch gonna pop early n drop the whole market participates till Monday! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:59:38 </td>
   <td style="text-align:left;"> Tesla, Nio, or Rivian? 

Why Choose When You Can Buy Them All, Says Top Analyst via @TipRanks.

Great article which gives a good bull thesis on buying them all.

Where is the love for $LCID??

$TSLA $NIO  $RIVN $QQQ

https://www.tipranks.com/news/article/tesla-nio-or-rivian-why-choose-when-you-can-buy-them-all-says-top-analyst/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:59:11 </td>
   <td style="text-align:left;"> $TSLA even with rate hikes the yield is just too low, way lower than the markets yield </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:58:51 </td>
   <td style="text-align:left;"> $TSLA Time to make a decision
https://share.trendspider.com/chart/TSLA/66822blxng </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:58:02 </td>
   <td style="text-align:left;"> $TSLA Bears took our food from the table. Unforgivable. $60 drop after Fed min, it’s a total manipulated action. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:57:45 </td>
   <td style="text-align:left;"> $TSLA fill that gap ya filthy animals </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:57:33 </td>
   <td style="text-align:left;"> $TSLA futes greener and greener! 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:56:03 </td>
   <td style="text-align:left;"> $NVDA $TSLA $AAPL The Fed blew their load and now they are pulling out. 

Look back at history what happens when they try to raise rates.

Good Game entire world. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:56:00 </td>
   <td style="text-align:left;"> $TSLA it took Tesla 14 years to be what it is today, w no burden of old factory transformation, how long do you think Chrysler, Ford, GM, Toyota to catch up?  Super charging station network is another win for Tesla. And if ICE going to be stop by 2028 by all these old manufacturers, how much they have to spend to get rid of the old and build the new?  Tesla will always be the leader for them to play catch up.  One think I feel for Tesla is they need to roll out new models every 5 years , not just face lifts on old models. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:55:44 </td>
   <td style="text-align:left;"> Even the best stocks will need some work $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:55:11 </td>
   <td style="text-align:left;"> $TSLA Holding </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:54:43 </td>
   <td style="text-align:left;"> $TSLA I love how we were saying that the gap would never get filled and then the next day it&amp;#39;s gets filled 💀💀💀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:54:11 </td>
   <td style="text-align:left;"> $NKLA $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:53:38 </td>
   <td style="text-align:left;"> $TSLA tomorrow 1070 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:53:11 </td>
   <td style="text-align:left;"> 🚨 ARK LATEST TRADES 🚨 :

$SE - $ROKU - $NET - $TSLA - $PYPL 💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:51:49 </td>
   <td style="text-align:left;"> $DOGE.X $SPY $TSLA  everything trending is red as snow! The only thing I’m glad on is I didn’t get calls on anything but I did get shares and I’ll be ok ! 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:51:36 </td>
   <td style="text-align:left;"> $TSLA  Friends you are still up for the year 2022.  There is nothing in the Fed Minutes that matter to TESLA&amp;#39;s outcomes. So, You have nothing to fear.  Here is the Fed Minutes &amp;quot;https://www.federalreserve.gov/monetarypolicy/files/fomcminutes20210728.pdf&amp;quot; Stay focused in the man-made financial storm. Daylight and sunshine is coming soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:50:49 </td>
   <td style="text-align:left;"> $TSLA Now this 400 mile range 660hp Chevrolet E Silverado looks like a truck. Haters gon hate. I dont love the look but its not bad. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:50:46 </td>
   <td style="text-align:left;"> $BYND If you think meat industry is going down with out a fight then you better ask $TSLA about the fossil fuel industry </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:49:26 </td>
   <td style="text-align:left;"> $BTC.X years later, no one can explain the point of this shi+ to me….🤔 
 
$TSLA $SPY $QQQ $DOGE.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:48:54 </td>
   <td style="text-align:left;"> $TSLA this not a bluechip??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:48:22 </td>
   <td style="text-align:left;"> $TSLA   Winning!

Tesla Short at 1170, Why it was a short.  1/5/2022
https://youtu.be/Z71LeEAYC8A </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:47:39 </td>
   <td style="text-align:left;"> $TSLA my bitcoins my ethereum and my shib burnt toást.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:46:28 </td>
   <td style="text-align:left;"> $TSLA Garbage. Buyer beware. Caution </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:46:18 </td>
   <td style="text-align:left;"> $TSLA so Tesla delivered close to 309,000 vehicles and basically the stock hasn’t moved in the last couple of days..all the original gains gone Absolutely amazing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:45:58 </td>
   <td style="text-align:left;"> $TSLA is the unemployment numbers  tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:45:55 </td>
   <td style="text-align:left;"> $TSLA scared paperhands who sold today will regret tomorrow! 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:45:34 </td>
   <td style="text-align:left;"> $TSLA   $500 coming soon, then $250 for this overinflated garbage stock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:43:48 </td>
   <td style="text-align:left;"> $TSLA Lol. Rinse and repeat Elo wants to eat. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:42:59 </td>
   <td style="text-align:left;"> $TSLA bears were crying a couple of days ago, now they can stop posting shit… lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:42:39 </td>
   <td style="text-align:left;"> $TSLA this post will prob get reported too like the last one, but I’ll say it anyways:

KEEP SELLING YOU PUSSIES. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:42:37 </td>
   <td style="text-align:left;"> $TSLA $AAPL $MSFT $QQQ $SPY Anyone holding PUTS after that 2 day massacre isn’t going to get a wink of sleep tonight, the Market always over reacts, tomorrow is going bounce HARD!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:41:47 </td>
   <td style="text-align:left;"> $SPY $TSLA best trading day of my life. new daily profit record !!! tomorrow will be amazing let’s go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:41:22 </td>
   <td style="text-align:left;"> $TSLA with more than one rate hike this year, there won’t be enough liquidity in the market for this to add another trillion. That is the fundamental problem for the bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:40:55 </td>
   <td style="text-align:left;"> $TSLA 

Get in $1080-- $1050, it will attempt ATH around earning,  but not likely this week, market needs time to digest the reports. 

The direction is NORTH. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:39:34 </td>
   <td style="text-align:left;"> $TSLA $NIO Not bashing, just something interesting to think about lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:37:40 </td>
   <td style="text-align:left;"> $TSLA lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:37:12 </td>
   <td style="text-align:left;"> $TSLA When something comes right for you.....you grab it. easy money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:36:52 </td>
   <td style="text-align:left;"> $BTC.X $TSLA $DWAC yea people he got more votes than Obama and Trump more than any President in US History, oh and Bitcoin is going to 100k 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:36:31 </td>
   <td style="text-align:left;"> $TSLA bears/shorts production starting soon out of the Berlin Gigafactory! Prepare to cover…

https://insideevs.com/news/557996/tesla-modely-seen-leaving-gigaberlin/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:36:15 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:35:46 </td>
   <td style="text-align:left;"> $SPY $TSLA $NVDA $MSFT epic squeeze tomorrow 😂🤣🤑❤️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:35:36 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ $AMZN $AMC ;;,, 
 
 
Account Challenge Update:~ 
Start Date: Nov 2, 2021 
Starting Balance: $1,500 
Current Balance: $96,149 
Goal: $100,000 by end of January, 2022 
Strategy: Swing Trade Options, Stocks 
 
Watch out for next play👓 discord.io/MqakycG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:34:54 </td>
   <td style="text-align:left;"> $ARKK what really happens if $TSLA falls 50 percent if the valuation is the big concern now? Can’t imagine cathie thought process. Can we call this as conviction or madness? How long could she or how much cash can she put in to buy these dead stocks to prove her right. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:34:38 </td>
   <td style="text-align:left;"> $TSLA My profit. Ahhhhh 😢 it&amp;#39;s gone. Yiiii 😢 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:33:53 </td>
   <td style="text-align:left;"> $TSLA 😇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:33:35 </td>
   <td style="text-align:left;"> $TSLA P/E ratio over 350 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:32:18 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-05 Options Analysis Video: 
https://www.youtube.com/watch?v=ZVquD6RhX18 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:31:43 </td>
   <td style="text-align:left;"> $TSLA easy comes easy goes, let’s see how fast Elon loses 200 bil 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:31:22 </td>
   <td style="text-align:left;"> $TSLA back to $1200 soon… 

https://www.torquenews.com/15475/tesla-double-production-2022-giga-shanghai-sets-manufacturing-records/amp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:31:16 </td>
   <td style="text-align:left;"> $TSLA: Not a good look. After the breakout above the channel, it closed right back in. Watch for a break of today&amp;#39;s low of day (1081) to short. Target: 1061, 1047, and 1024 area. Like it long above 1110 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:31:12 </td>
   <td style="text-align:left;"> $TSLA just witnessed a white Tesla just veer over the median and strike a pole. Wtf is wrong with these POS cars. Clear visibility and dry conditions.  smh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:28:46 </td>
   <td style="text-align:left;"> $TSLA Elon probably built the pyramids 👽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:28:38 </td>
   <td style="text-align:left;"> $BTC.X now only $TSLA crash and the mayhem is complete </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:28:15 </td>
   <td style="text-align:left;"> $TSLA 
-“Mr Wrong here with a Tsla news prediction for 1/6/22…. Tsla will go waaaaayyyy down tomorrow, waaaay down….”

This has been a LiveAt5 wallstreet report with Mr Wrong…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:27:58 </td>
   <td style="text-align:left;"> $TSLA Sold MONDAY AT 4:00 
Buyer tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:27:46 </td>
   <td style="text-align:left;"> $TSLA hi guys, it’s Mary ( I’m leading the charge here! I just sold 26 EV’s so…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:27:17 </td>
   <td style="text-align:left;"> $TSLA had to sell a few to load up on $AABB.  Bottom is in.  Zero risk imho.  I&amp;#39;m preloading betting on an update this month.  Load up chaps. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:26:50 </td>
   <td style="text-align:left;"> $TSLA So Tesla built the entire Berlin factory before the Government was able to complete their review of whether Tesla is allowed to build the factory.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:26:44 </td>
   <td style="text-align:left;"> $TSLA All I know is this sucker bounced up like crazy just under $900. Since Then they came out with the Production news.. If anyone thinks they’re going to get it any cheaper than that they’re crazy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:26:35 </td>
   <td style="text-align:left;"> $TSLA Let&amp;#39;s see a show of hands of how many people buying January 7, $1200 calls tomorrow.  LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:26:17 </td>
   <td style="text-align:left;"> Talk about panic sale I’m hodling $SHIB $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:25:18 </td>
   <td style="text-align:left;"> $TSLA fack looks like it is going to be super red tomorrow again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:25:00 </td>
   <td style="text-align:left;"> $TSLA well will fill the gap for sure tomorrow 1060.00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:24:17 </td>
   <td style="text-align:left;"> $TSLA Japanese Stock Market dumping hard right off the bat.  Down 400 points already. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:22:01 </td>
   <td style="text-align:left;"> $TSLA You idiots pumped this over 30% in 10 days. Enjoy soaking in your musty bath water greedy pigs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:21:54 </td>
   <td style="text-align:left;"> Ticker: $TSLA 
Buy: January 07, 2022 $1090.00 Calls 
Entry Price: $20.49 - $20.85 
Exit Price: $28.48 
Stop Loss: $18.03 
Potential ROI: 39% 
Estimated Hold Time: 41 Minutes 
Alert Courtesy Of: https://www.fastscalp.com/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:20:09 </td>
   <td style="text-align:left;"> $TSLA Bought the DIP 2 mins before after hours closing.

Always a bull on TSLA. It filled the gap on Monday. I filled my entry. 😃 

https://www.noobsellingoptions.com/post/woke-up-and-bought-the-dip-for-tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:19:53 </td>
   <td style="text-align:left;"> $TSLA green or red tomorrow🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:18:41 </td>
   <td style="text-align:left;"> $TSLA we need a split and free Tesla Tequila bottles for everyone 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:18:05 </td>
   <td style="text-align:left;"> $TSLA Remember my prediction last night about taking out the $1100 calls today?  Next up: Retrace to $650, fast. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:17:33 </td>
   <td style="text-align:left;"> $TSLA a fool and his money are soon parted </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:17:04 </td>
   <td style="text-align:left;"> $TSLA $ARKK I‘ve lost all of my respect for that Jesus freak Cathie Wood. She truly is an idiot. Got lucky with one pick that’s it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:16:33 </td>
   <td style="text-align:left;"> $TSLA Whoever caused yesterday and today I hope you rot in hell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:14:20 </td>
   <td style="text-align:left;"> $TSLA $SQ $PLTR $MSFT Isn&amp;#39;t it odd that almost all the CEO&amp;#39;s of top companies sold huge amounts of stock.. It&amp;#39;s almost like they knew the FED was going to do this. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:14:05 </td>
   <td style="text-align:left;"> $ARKK HAHAHAH an ETF falling 7%. This is complete crap, filled with shit like $TSLA $DKNG etc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:13:52 </td>
   <td style="text-align:left;"> $TSLA a leveraged bubble. Like shibby bitty. Shame on Elon for the pump fest
Warning!! max leverage. 
 https://www.reddit.com/r/Epic_Economics/comments/rx28oj/feds_chasing_inflation_balance_sheet_runoff/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:13:21 </td>
   <td style="text-align:left;"> $TSLA wooo let’s all enjoy the nasdaq being green for 10 minutes before we get another kick in the balls tomorrow 🙃 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:13:16 </td>
   <td style="text-align:left;"> $TSLA Tesla Model S Goes 752 Miles with a Prototype Battery from a Michigan Startup.. Pump Pump Pump.. make my cals fly tomorrow.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:12:52 </td>
   <td style="text-align:left;"> $TSLA FED meeting in December said exactly the same things. It’s just tragicomic they say ok we will be green but when you release minutes of this meeting in January we will fuckkk retail investors </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:11:19 </td>
   <td style="text-align:left;"> $TSLA is the next $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:10:04 </td>
   <td style="text-align:left;"> $TSLA 

FYI! 

U.S. 10-YEAR YIELD MAY HIT 2% IN 2H AS FED HIKES: NOMURA

🙏🏻🐉🦅👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:09:06 </td>
   <td style="text-align:left;"> $F I hope bears get smoked for their dice rolling puts, though you might get your pullback, quite frankly you deserve to lose. Ford is cheap. Trading cheap. Now a futurist company. Tons of catalysts. Get your heads out of your asses ford is the $TSLA underdog. You’re stupid to think otherwise. Farley said it himself. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:09:01 </td>
   <td style="text-align:left;"> $SPY - 1,100% PROFITS ON SPY PUTS.! WHAT A DAY FOR OUR MEMBERS 👑
FALL-O FOR MORE, LYNX IN BAYU.
$TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:08:50 </td>
   <td style="text-align:left;"> $TSLA 

OK. 
$1050 area and I am betting my farm, farmhouse, all the cows, all the pigs, all the chickens, all dogs but one, and all my wives. 

GLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:07:44 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:07:22 </td>
   <td style="text-align:left;"> $TSLA https://electrek.co/2022/01/05/tesla-model-s-752-miles-range-one-energy-dense-battery-pack/
For the Tesla killers, hahaha
Tesla 4 years head of the test...!!!
Tesla long 🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:06:19 </td>
   <td style="text-align:left;"> $TSLA two big open gaps at 1056 and 939. Bulls better pray to god those don’t fill </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:05:32 </td>
   <td style="text-align:left;"> $TSLA ---

Oops .....LOL     ---  $SPY $SPX $DIA $DJIA 

https://www.the-sun.com/motors/4396577/mercedes-benz-vision-eqxx-electric-car-tesla/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:05:22 </td>
   <td style="text-align:left;"> $TSLA https://www.etsy.com/listing/1154186083/dogecoin-vinyl-decals?ref=shop_home_active_1&amp;amp;frs=1 🏎⚡ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:05:16 </td>
   <td style="text-align:left;"> $TSLA Nasdaq down 4.25% YTD. Nice. FJB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:04:34 </td>
   <td style="text-align:left;"> Hi, I am Elon from Mars ... shall I sell the rest of my shares to support my x-wife and my expected alien child once I arrive on Mars and find a like minded martian babe wife to birth our child to be named \○{¤♤}¿? $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:04:17 </td>
   <td style="text-align:left;"> $TSLA I just noticed I was blocked by the lead Cultist and biggest pumper on here, Borggss LMAO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:04:16 </td>
   <td style="text-align:left;"> $TSLA Only people are worried here are ones who buy weekly options and buy on margin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:04:00 </td>
   <td style="text-align:left;"> $TSLA ⚡https://www.etsy.com/listing/1138257430/buy-doge-tshirt?ref=shop_home_active_3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:03:22 </td>
   <td style="text-align:left;"> $TSLA https://www.thetimes.co.uk/article/tesla-rises-to-second-in-uk-car-sales-qnwkgwljm

THIS IS NOT FAKE NEWS LOL !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:03:14 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-05 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=ETxDHxRmSIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:03:03 </td>
   <td style="text-align:left;"> $TSLA I think we are in for a market correction get ready </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:02:22 </td>
   <td style="text-align:left;"> $TSLA so we basically doubled production from last year and we have some gigafactories opening. I’m not worried in the slightest. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:02:14 </td>
   <td style="text-align:left;"> $TSLA Simulated 1095.0 dollar CALLS for Thursday&amp;#39;s open on StockOrbit.
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:02:09 </td>
   <td style="text-align:left;"> $TSLA Do you notice all of the sudden when the bulls are posting tonight they are leaving out the Bullish tag?  LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:02:07 </td>
   <td style="text-align:left;"> $TSLA congrats to bear people </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:01:39 </td>
   <td style="text-align:left;"> $TSLA

Bought today&amp;#39;s dip. Buying all around. Wait till you see. 1 month later, omg all time highs for SPY and everything else. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:00:39 </td>
   <td style="text-align:left;"> $PTON $TSLA $NIO $ZM
Tesla is the only wet paper bag left,
loaded with geniuses…clearly
$spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:00:19 </td>
   <td style="text-align:left;"> $TSLA $GM sold 26 EVs in Q4. You fucking did it Mary. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 09:00:18 </td>
   <td style="text-align:left;"> $TSLA New US STAMPS 2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:59:30 </td>
   <td style="text-align:left;"> $TSLA tomorrow our puts print. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:59:26 </td>
   <td style="text-align:left;"> $TSLA

$2200 end of year. Nothing has changed. Hold. 👍👍👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:58:58 </td>
   <td style="text-align:left;"> $TSLA we need a 10-1 split </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:57:29 </td>
   <td style="text-align:left;"> $TSLA Nasdaq down 5% in 2 days...another 5% or so to flush down the toilet this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:57:15 </td>
   <td style="text-align:left;"> $VWAGY $TM $TSLA Volkswagen and Toyota are planning to invest $170B in EVs to take on Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:57:09 </td>
   <td style="text-align:left;"> $TSLA I had to dump my calls at an 8K loss today but I still have my shares I’m sure everybody gives a shit I’m sure everybody </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:56:37 </td>
   <td style="text-align:left;"> $TSLA In place of Elon, I would acquire some of the deep in debt “titans” and turn them into my Tesla part suppliers 🤣  https://www.smh.com.au/business/companies/the-titans-of-carmaking-are-plotting-the-overthrow-of-elon-musk-20220106-p59m8a.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:56:07 </td>
   <td style="text-align:left;"> $TSLA SMH Not Another Recall </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:55:37 </td>
   <td style="text-align:left;"> $TSLA well, so much for electric vehicles </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:54:46 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:54:32 </td>
   <td style="text-align:left;"> Short TESLA bs premarket 340 shares at 1,138.50 ... laughed at the bs sheeple rally to 1,170&amp;#39;s ... covered afterhours at 1,079 = 26,565$🇨🇦 in profits ... hello ... stfu jawboning silly sheeples and bulls ... btw ... thanks for lending me shares to short for profits at your expense ... you dudes are the best ... let&amp;#39;s do this again on Crash Thursday ... 🐻❤✔ $tsla 🕺 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:54:01 </td>
   <td style="text-align:left;"> $TSLA 

The fools that sold Tesla today, don&amp;#39;t deserve to make a penny in the stock market period.

https://www.thetimes.co.uk/article/tesla-rises-to-second-in-uk-car-sales-qnwkgwljm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:53:04 </td>
   <td style="text-align:left;"> $TSLA another flesh wound pftt </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:52:31 </td>
   <td style="text-align:left;"> $TSLA tomorrow you shld trade based off the 50 day moving average. Bullish above and bearish below. Only true safe way to play it if a trader </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:51:32 </td>
   <td style="text-align:left;"> $EWTX $TSLA &amp;gt;:&amp;quot;:&amp;quot;~

Account Challenge Update:~
Start Date: Nov 2, 2021
Starting Balance: $1,500
Current Balance: $95,849
Goal: $100,000 by end of January.
Strategy: Swing Trade Options, Stocks

Watch out for next play👓  discord.io/fmeeTaW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:50:37 </td>
   <td style="text-align:left;"> $TSLA  $2000 EOY 🚀🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:50:04 </td>
   <td style="text-align:left;"> $TSLA the 5 day chart looks like it’s about to explode… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:49:52 </td>
   <td style="text-align:left;"> $PLTR make up your losses at $PQEFF. Buyout at .58, plenty of time to tender your shares $SPY $TSLA $MVIS 

If you get mad that means you’re salty af and lost a lot of money today 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:49:43 </td>
   <td style="text-align:left;"> $TSLA EXCELLENT NEWS OUT OF UK !! TESLA MODEL 3 SALES !! GAP UP IN THE AM !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:48:23 </td>
   <td style="text-align:left;"> $TSLA yummy yummy puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:48:04 </td>
   <td style="text-align:left;"> $TSLA wow ! Breaking news ! UK CAR SALES ! BUCKEL UP BULLS !!! gap up tomarrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:47:40 </td>
   <td style="text-align:left;"> $TSLA Fuck it we go back to the Future tomorrow $1100+++🍀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:47:36 </td>
   <td style="text-align:left;"> $TSLA 
Lesson of the day:
Bubble stocks don’t like the hint of interest rate hikes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:47:11 </td>
   <td style="text-align:left;"> $TSLA       ..THE BIG GIFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:47:00 </td>
   <td style="text-align:left;"> Looking at the last year, $TSLA shows a very strong growth in Revenue. The Revenue has grown by 66.27%. https://www.chartmill.com/stock/quote/TSLA/fundamental-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:46:08 </td>
   <td style="text-align:left;"> $TSLA 👎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:46:03 </td>
   <td style="text-align:left;"> $TSLA by end of next week should be back around 1200s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:45:36 </td>
   <td style="text-align:left;"> $TSLA will I bleed tomorrow or be triumphant?!? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:45:35 </td>
   <td style="text-align:left;"> $TSLA 

BREAKING!!

Tesla Model 3 Britain’s executive company car of choice and it became the UK’s second best-selling new car in 2021.

🙏🏻🐉🦅

https://www.thetimes.co.uk/article/tesla-rises-to-second-in-uk-car-sales-qnwkgwljm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:45:33 </td>
   <td style="text-align:left;"> $TSLA  FUCK JOE BIDEN. Commie fuck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:45:24 </td>
   <td style="text-align:left;"> $AMD $TSLA Its easy to say tomorrow will be bloody after the FED sell off. Let’s Rip tomorrow. It would be unusual to see 3 red days in a row </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:45:14 </td>
   <td style="text-align:left;"> $TSLA The perfect storm is brewing.  Now Bitcoin is dumping and down 6%.  Retrace to $650 in the works. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:44:43 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $NVDA $MSFT Margin call fiasco will be epic, keep buying the dip numb nuts… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:44:27 </td>
   <td style="text-align:left;"> $TSLA if u have bought puts $1200+ this week, i hate you but congratulations 🎊🎈🎉 mo fo. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:42:46 </td>
   <td style="text-align:left;"> latex5f387084259a490e261d89ef0bc477b9TSLA -5%
$NIO -5%

Is this a sign of things to come? Is this a bump in the road? Discussing the best names to trade long and short right now amidst the current cycle and inflationary pressures. 

https://youtu.be/Izf37X7e1zo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:42:08 </td>
   <td style="text-align:left;"> $TSLA Nice job Brandon you won’t get another fucking term </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:41:31 </td>
   <td style="text-align:left;"> $TSLA 🧐🤓🤤🤑 
https://insideevs.com/news/558848/tesla-direct-sales-model-positives/?fbclid=IwAR2HRHQZEjZ74KBCfcs-FKfqvhERXK0Iv3rDsDaaVMtvxRV5esnFXVqb-yg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:41:15 </td>
   <td style="text-align:left;"> $TSLA FJB FJB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:41:00 </td>
   <td style="text-align:left;"> $TSLA great info https://youtu.be/D69emG0ESM4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:40:39 </td>
   <td style="text-align:left;"> $TSLA the liberal agenda everybody! Destroyers of wealth. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:40:26 </td>
   <td style="text-align:left;"> $TSLA next time don’t vote
For Biden. And don’t say trump messed things up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:39:28 </td>
   <td style="text-align:left;"> $TSLA oh god bitcoin dumped </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:39:04 </td>
   <td style="text-align:left;"> $BTCS anyone short thinking $BTC.X wouldn’t be rebounding is silly. Watch Elon Musk buy the dip with all his free capital from selling his $TSLA shares. 😉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:38:33 </td>
   <td style="text-align:left;"> 🚨Today’s Recap 🚨

🔥01/07 $AAPL $177.50P @1.43&amp;gt;1.15 (25%)
🔥01/07 $LCID $1.35&amp;gt;.95 (40%)
🔥01/05 $SPY $1.50&amp;gt;1.03 (50%)
🔥01/07 $TSLA $1085P @20.60&amp;gt;17.45 (20%)
🚀01/21 $SPY $470P @5.50&amp;gt;1.08 (500%)
🔥01/07 $SPY $475P @2.14&amp;gt;1.88 (14%)
🔥 01/07 $AAPL $177.50P @1.32&amp;gt;1.17 (13%)

7/7 today 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:38:29 </td>
   <td style="text-align:left;"> $TSLA 1200 by Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:38:11 </td>
   <td style="text-align:left;"> If $BTC.X sells off tonight, it’s going to bring $TSLA $QQQ and $SPY down with it. The correction is happening….I feel for the small/mid caps. They were already destroyed for the last 9 months…… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:37:28 </td>
   <td style="text-align:left;"> $TSLA At the end of the day Elon always wins! Modern day Thomas Edison! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:37:16 </td>
   <td style="text-align:left;"> $TSLA oh well 😑 I guess tonight I&amp;#39;ll just have to deal with a couple of those stop-loss hit nightmares I like so much yeah.. ☠ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:36:15 </td>
   <td style="text-align:left;"> $QQQ Everyone claiming they called this market dip, This is you.  😆 $SPY  $TSLA $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:35:21 </td>
   <td style="text-align:left;"> $SPY I would never ever buy crypto, microcap stocks yes. Not fake currency $AAPL $AMD $AMZN $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:34:45 </td>
   <td style="text-align:left;"> $TSLA dead cat tomorrow then trickle </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:34:29 </td>
   <td style="text-align:left;"> $BTC.X this usually runs up close to $TSLA earnings so this is rinse and repeat like clockwork </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:32:44 </td>
   <td style="text-align:left;"> $TSLA just going to buy the 1000$ dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:32:32 </td>
   <td style="text-align:left;"> $TSLA omnicorn looks like coming in hard, may have to buy some puts to hedge my long position so i dont have to have anxiety from huge dips.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:32:28 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-05 Technical Analysis Video: 
https://www.youtube.com/watch?v=vVxo6WahaE4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:32:17 </td>
   <td style="text-align:left;"> Been busy all day today.  What did I miss?? $SPY $TSLA …wtf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:32:13 </td>
   <td style="text-align:left;"> What Investors Should Know About Amazon, Sony And John Deere&amp;#39;s Latest Push Into The Electric Vehicle Sector  $TSLA $F $GM $SONY $AAPL 

https://newsfilter.io/a/61273ce504a884821eea439d8c44023c </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:31:55 </td>
   <td style="text-align:left;"> $TSLA I would truly appreciate it if you can show some love! ❤️ if you use Webull this setup is fire! https://youtu.be/lXTIn7sXwKI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:30:37 </td>
   <td style="text-align:left;"> $TSLA People need to get off this tangent about blaming this on the big bad shorts.  Currently only 3% of the float is being shorted.  What you are witnessing is the Tutes and Hedgies dumping shares and refocusing their attention to precious metals and traditional Blue Chips. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:29:05 </td>
   <td style="text-align:left;"> $TSLA tomorrow it will drop to 1030 and then I will sell my put and buy a call </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:27:58 </td>
   <td style="text-align:left;"> $TSLA i run puts and calls i dont give a fuck about this doing good or bad!! Just making 🍞 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:27:52 </td>
   <td style="text-align:left;"> $TSLA Big Musk lecture 01-26-22 (PDLC related (Project Aanalysis stuff (Cybertruck/25K sports car) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:27:21 </td>
   <td style="text-align:left;"> $TSLA Show me the money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:27:18 </td>
   <td style="text-align:left;"> $TSLA if this was green when the WHOLE market was red, what makes you think this would rise when futes are up? serious question </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:27:15 </td>
   <td style="text-align:left;"> $TSLA 🤞🏻🤞🏻🤞🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:24:14 </td>
   <td style="text-align:left;"> $TSLA good luck all and happy news guys. It is very interested to see more then 22 ev companies in USA ev race against tesla. Kia EV6 it will be my buy list this year. Way cheaper then tesla. Nissan ev suv would be nice too. Cadillac ev is way too fancy for a normal guy like me but all cheaper and Fancier then tesla for sure </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:24:12 </td>
   <td style="text-align:left;"> $TSLA futures are green so far, hope you bought the dip. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:23:57 </td>
   <td style="text-align:left;"> $TSLA interest rates are very good for profitable companies. Because investors  invest in profitable companies during such times since they don’t pose any threat with their steady earnings. All companies that don’t make any profit will be definitely fukked since their investors will run from them and invest in companies like Tesla that already make profit for tens of billions of dollars each year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:22:25 </td>
   <td style="text-align:left;"> $TSLA the Elon hustle. It’s a thing
 https://www.reddit.com/r/Epic_Economics/comments/rx15ww/tech_sells_off_everywhere_market_mayhem_beware/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:22:15 </td>
   <td style="text-align:left;"> $TSLA sorry longs, no position ATM but I&amp;#39;D TAKE another 890 long entry (with a tight stop loss) in a week or 2 would make my day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:21:57 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA still bullish but too early to btd imo, especially growth stocks… stick to value with this market condition </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:21:56 </td>
   <td style="text-align:left;"> $SPY $TSLA they lied to keep the market afloat until January and crash by March. O well ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:20:23 </td>
   <td style="text-align:left;"> $TSLA the Shorts  will suffer tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:20:13 </td>
   <td style="text-align:left;"> $BB working hard on getting $TSLA  on board. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:19:29 </td>
   <td style="text-align:left;"> $TSLA doesn’t Jan 7th have significance for company.  

Just saying, watch Friday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:19:17 </td>
   <td style="text-align:left;"> $TSLA paper handed that one at 3.65, $2700 profit but these are at 8.45 now 🙃😅 missed out on $32k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:18:37 </td>
   <td style="text-align:left;"> $TSLA 
Back up tomorrow. This stock makes millionaires. You should thank Uncle Elon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:18:20 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $ tinder @ElviaWallace2 haha i think u left me on read haha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:18:02 </td>
   <td style="text-align:left;"> $TSLA 
Shorts!
Futures are green after Fed Minutes!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:17:29 </td>
   <td style="text-align:left;"> $ARKK sell $tsla amd buy $HOOD last week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:16:49 </td>
   <td style="text-align:left;"> $TSLA going to touch 890&amp;#39;s before moving up imo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:16:49 </td>
   <td style="text-align:left;"> $TSLA $SPX $NVDA Federal Reserve puts wheels in motion for balance sheet reduction https://www.cnbc.com/2022/01/05/fed-minutes-december-2021.html?__source=iosappshare%7Ccom.stocktwits.StockTwits.STShareExtension </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:16:26 </td>
   <td style="text-align:left;"> $TSLA what % of tesla investors are short seller? I say at least 50%. What if first earning quarter, tesla reported they lost more 50% in sales because of more then 22 ev companies are in race this Year now consu have more ev choices for better price and better car then tesla?  Remember 2021 tesla sold 900k ev cars amd 500k car recalled without any ev competitors. if more then 22 ev competitors just in ev race then tesla drop like 50% in sales then what will the next 3 quarters look like. Will be very awful don’t you think? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:16:05 </td>
   <td style="text-align:left;"> $TSLA Beautiful AH&amp;#39;s rise! We are primed for a leg up back into the $1100&amp;#39;s at the very least! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:16:03 </td>
   <td style="text-align:left;"> $TSLA Toyota market cap &amp;gt; 312 billion 
 Tesla &amp;gt; 1.1 trillion 

Lmao 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:15:59 </td>
   <td style="text-align:left;"> $TSLA Green day tomorrow.  It is rare to have three red days in a row. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:15:53 </td>
   <td style="text-align:left;"> $TSLA Shorts!! 

Futures green after Minutes!

Musk lectures on pending car projects (Cybertruck) 01-26-22 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:14:17 </td>
   <td style="text-align:left;"> $TSLA Dow, SPX after Minutes https://www.investing.com/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:13:53 </td>
   <td style="text-align:left;"> $SPY $TSLA feels good to not be holding anything overnight! Not worried about how we open tomorrow. 🤠 $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:13:04 </td>
   <td style="text-align:left;"> $TSLA Elon, send a tweet! 🙂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:12:36 </td>
   <td style="text-align:left;"> $TSLA oh shit, your puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:12:21 </td>
   <td style="text-align:left;"> $TSLA They told exactly the same things about rate hikes in their last meeting in December and it was known by markets and markets skyrocketed after meeting. Today they released minutes of that meeting it’s so corrupted!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:12:08 </td>
   <td style="text-align:left;"> $TSLA if WSB, and the Reddit crew bought calls on the dip today, get ready for tomorrow and Friday! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:12:08 </td>
   <td style="text-align:left;"> $TSLA 
Just for a reality check for all this back and forth. 
I’m not a rich man… I bought Testla back in 2012 at an average of 250 something a share. Put it into my ira I manage for my wife as well.
Also converted an old ira to a Roth which contained Testla. (My sons college fund) he is 5.
Testla alone from those investments has made me about a million. So that said, with all the back and forth just buy it and forget about it for the next 10-14 years and save us all the bear/bull drama. My two cent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:11:47 </td>
   <td style="text-align:left;"> $TSLA THIS WILL BE BACK STRONGER!! 💪🏼✅✅🔥🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:11:46 </td>
   <td style="text-align:left;"> $TSLA closed under support, definitely seeing more red tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:10:56 </td>
   <td style="text-align:left;"> We gave our members a heads up for a potential swift move down yesterday. Our buy signals were close to hitting on several names as $SPY was making a new all time high while money flowed out of $QQQ names. However, less than a handful of our buy signals were triggered and what resulted was a swift move down(screenshot attached).  
 
Some leadership names we are watching for $SPY and latex45b303a3816b9710874a326b84d0d6f8AAPL - a leading tech name. Look for support to establish in the coming days despite it&amp;#39;s topping pattern forming.  
$TSLA - at key support levels. Ideally longs would like to see a bounce in the coming days near $1051.37 
 
For more charts and commentary  read our free blog post! &amp;quot;2022 - The Year of The Tiger&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:10:52 </td>
   <td style="text-align:left;"> $QQQ $AAPL $TSLA Huge moves up tomorrow, Tesla filled it’s Gap, Apple needed to cool off and  QQQ got thrashed, I couldn’t imagine holding PUTS overnight y’all going to get SMASHED in the morning 😆😆😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:10:17 </td>
   <td style="text-align:left;"> $TSLA  sweet!   competition is good!! https://www.the-sun.com/motors/4396577/mercedes-benz-vision-eqxx-electric-car-tesla/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:09:46 </td>
   <td style="text-align:left;"> $TSLA to many bears that’s means we going green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:09:20 </td>
   <td style="text-align:left;"> $TSLA it gave it all back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:09:01 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:08:56 </td>
   <td style="text-align:left;"> $TSLA Shorts Futures green in Thur Asia after Minutes!!

-----------------------------------------------------------------------------
US Fed Minutes more hawkish than anticipated:-&amp;gt;  8 Rate hikes  projected thru 2024 (3 -2022, 3 -2023, 2 -2024) and a possible, Fed Balance Sheet reduction (Selling bonds, previously purchased  (Reverse QE)) .  recap-&amp;gt; US Equities Futures flat green after Minutes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:08:21 </td>
   <td style="text-align:left;"> $TSLA if you aren’t consistently making money trading (ending each week green) then stop. Buy shares </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:08:12 </td>
   <td style="text-align:left;"> $TSLA This will go with $QQQ but filling an up-gap, backtesting a break out, and (hopefully) getting bought up off the 50-day together make a pretty strong buy point </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:08:12 </td>
   <td style="text-align:left;"> $TSLA wtf happened today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:07:57 </td>
   <td style="text-align:left;"> $TSLA futes green and we recovered some of that AH mess </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:07:48 </td>
   <td style="text-align:left;"> $TSLA back to $1085. This will open strong tomorrow with fute greens 💪🏼✅🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:07:27 </td>
   <td style="text-align:left;"> $TSLA Pump up the jam, pump it up
While your feet are stompin&amp;#39; And the jam is pumpin&amp;#39;Look ahead, the crowd are jumpin&amp;#39;&amp;#39; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:06:45 </td>
   <td style="text-align:left;"> $TSLA up 40 tomorrow up 30 Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:06:43 </td>
   <td style="text-align:left;"> $TSLA looks like hedgies done buying </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:06:40 </td>
   <td style="text-align:left;"> $TSLA I can’t believe I took a L on my 1150 calls I just couldn’t hold overnight. I have a 1200 so hopefully I make something off of that </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:06:29 </td>
   <td style="text-align:left;"> $TSLA ummm well ok </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:06:17 </td>
   <td style="text-align:left;"> Here&amp;#39;s my take on Tesla $TSLA and a few other stocks to watch...from a distance https://youtu.be/tbylis2R88Q </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:06:04 </td>
   <td style="text-align:left;"> $TSLA WTF just happened </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:05:43 </td>
   <td style="text-align:left;"> $TSLA $QQQ FJB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:05:41 </td>
   <td style="text-align:left;"> $TSLA don’t be surprised on that reversal 🤣😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:05:34 </td>
   <td style="text-align:left;"> $TSLA loaded $1200 for friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:05:24 </td>
   <td style="text-align:left;"> $TSLA be a good day tomorrow, hoping for that big announcement… let’s go! Elon likes dropping them end of week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:05:17 </td>
   <td style="text-align:left;"> $TSLA this a a buy time. You won’t regret buying at this price </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:02:52 </td>
   <td style="text-align:left;"> $TSLA $1200 tomorrow! Don’t @ me. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:02:44 </td>
   <td style="text-align:left;"> $TSLA Vwap 1085.35 💂🏿‍♂️💰🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:02:44 </td>
   <td style="text-align:left;"> $TSLA double top </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:02:28 </td>
   <td style="text-align:left;"> $TSLA price of house and rentals have been going up almost 40% plus the price of groceries have been going up like 30%. On the other hand, people still have made same salaries. i Know there are a lot of home owners have still not paid their mortgages. Do you think this will set the bubble bigger? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:02:22 </td>
   <td style="text-align:left;"> $TSLA SPX just broke through 20 dma today. If it doesn&amp;#39;t bounce back, this stock has a lot more room below. Cathie better buy this back insofar selling her only winner </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:02:16 </td>
   <td style="text-align:left;"> Sweep Options Activity: $TSLA is the #4 ticker with sweep activity where institutions are trading options urgently with 45.2K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:02:14 </td>
   <td style="text-align:left;"> $TSLA 

You want an economy to grow with interest rate at or near zero ?! Seriously … 

The market spooked?! About what?! You call a manufactured outcome a “market reaction” ?! 

Is someone trying to steal our moon 🌝 ?! 

This is seriously messed up! 

Bad idea … numbskulls 0.02 

🙏🏻🦅🐉IMO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:02:13 </td>
   <td style="text-align:left;"> $AMD $ES Futures lookin&amp;#39; good, this is key. $AMD $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:01:14 </td>
   <td style="text-align:left;"> $TSLA go ahead buy it! They turned it green for you  so they can make it red in the morning! Buy now dump at open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:01:10 </td>
   <td style="text-align:left;"> $TSLA  a lot of other company&amp;#39;s getting into the ev field.  like ford. as ford takes the sales away, tsla will drop.  maybe thats why elon is selling .  get out on top.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:00:53 </td>
   <td style="text-align:left;"> $TSLA made 42K Monday and lost most of it the past 2 days. Gotta be able to shake it off if you’re a true long. Most cannot stomach the swings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:00:36 </td>
   <td style="text-align:left;"> $TSLA grabbed some cheap calls on the low low today little candle hanging on and green spy recovering a little in AH exp on these calls 1/14, if thisbarea holds bears could be in for a good dickn down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 08:00:08 </td>
   <td style="text-align:left;"> $TSLA should I roll 30k into her tomorrow? First reply to this message is what I’m doing. Go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:59:30 </td>
   <td style="text-align:left;"> $TSLA Futures is green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:59:20 </td>
   <td style="text-align:left;"> $TSLA https://www.tickerreport.com/banking-finance/8290872/analysts-anticipate-tesla-inc-nasdaqtsla-will-announce-quarterly-sales-of-15-51-billion.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:59:16 </td>
   <td style="text-align:left;"> $TSLA all time highs this month. If not I&amp;#39;ll delete my stocktwits account </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:59:11 </td>
   <td style="text-align:left;"> $TSLA man I was up 3k and then down 3 I never want to do this again. I feel so terrible </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:59:06 </td>
   <td style="text-align:left;"> $TSLA 

pr on robotaxi tomorrow 

DISAPPOINTED </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:58:48 </td>
   <td style="text-align:left;"> $TSLA does this rise or fall tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:58:09 </td>
   <td style="text-align:left;"> $TSLA going to scalp the bounces on this tomorrow unless I get a full confirmation it’s got more downside. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:58:01 </td>
   <td style="text-align:left;"> $TSLA buying on an overshoot down to 950ish.  We&amp;#39;ll see no hurry </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:57:50 </td>
   <td style="text-align:left;"> $TSLA tesla earning quarter doesn’t look good because of 500k ev recalls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:57:47 </td>
   <td style="text-align:left;"> $TSLA could not hold the breakout of the trendline.  That usually is a simple buy after such a gap and go.  Interesting.  On motherfucking watch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:57:44 </td>
   <td style="text-align:left;"> $TSLA power hour! will we make that jump up or drop more in bear land 🐻 🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:57:28 </td>
   <td style="text-align:left;"> $TSLA BUY THE DIP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:57:18 </td>
   <td style="text-align:left;"> $TSLA Musk lectures on pending Project(s) completion (Estimated time when two future cars hit the road (Cybertruck &amp;amp; possibly 25K sports car) - Jan 26th after earnings post </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:55:59 </td>
   <td style="text-align:left;"> $TSLA A great long term hold and addition to the challenge.  https://youtu.be/GESJcGqH8CI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:55:55 </td>
   <td style="text-align:left;"> $TSLA 5 more min till close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:55:49 </td>
   <td style="text-align:left;"> $ARKK like all tech stocks are being smashed, it’s not a Cathy thing like your friendly bears would like you to believe. Realize you have not lost a dime if you have not panic sold. The stocks of the Arkk like $TSLA , $ROKU and $PLTR are not penny stocks but leaders in their market focus and on a huge growth curve.  It’s very comfortable to buy the banks until quarterly results come out and growth stocks are growing exponentially while value duds are doing nothing.  

Then the FOMO will kick back in for small caps and growth stocks. 

Take it easy man and just wait it out, Tesla and the Ark aren’t going to zero so be Patient my friends and abide. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:55:36 </td>
   <td style="text-align:left;"> $TSLA 1300 end of month </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:55:10 </td>
   <td style="text-align:left;"> $TSLA futures positive. $1115 in pre $1150 high tomorrow $20 lower than today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:54:42 </td>
   <td style="text-align:left;"> $TSLA $1140 pivot… will it make it tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:54:19 </td>
   <td style="text-align:left;"> $TSLA what’s these after hour long ticks mean? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:53:10 </td>
   <td style="text-align:left;"> $BTC.X $SPY latexeaf5a66a376ef6368eb90d53dfcabe9dF - 69% call flow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:51:52 </td>
   <td style="text-align:left;"> And further away…$AAPL should eventually back to 3T based on fundamentals, maybe sooner on liquidity overdrive. $TSLA? I wouldn’t bet on it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:51:36 </td>
   <td style="text-align:left;"> $TSLA Child noise. TSLA will be $5000 in 2-3 yrs with 2 splits. same idiots said Aapl was done at pre split equivalent of $100, now post split equivalent of $4000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:51:21 </td>
   <td style="text-align:left;"> $TSLA --&amp;gt;Nasdaq posts biggest daily drop since Feb 2021 after &amp;#39;hawkish&amp;#39; Fed minutes 
http://www.streetinsider.com/Market+Check/Nasdaq+posts+biggest+daily+drop+since+Feb+after+hawkish+Fed+minutes/19421901.html via @Street_Insider 

&amp;quot;Indications that the Fed is very concerned about inflation...The Fed minutes &amp;quot;more hawkish than expected.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:50:38 </td>
   <td style="text-align:left;"> $TSLA ..sold out bc of the dip at -235$ loss smh but was like ITS MY MONEY AND I NEED IT NOW so i shorted it and made 5k 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:50:36 </td>
   <td style="text-align:left;"> $TSLA If tesla is crashing hard, then market is not doing good :) Lately i consider Tesla as the future index ;) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:50:32 </td>
   <td style="text-align:left;"> $TSLA just getting started .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:50:28 </td>
   <td style="text-align:left;"> $TSLA Just another buying opportunity before earnings that’s it 🤑🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:50:12 </td>
   <td style="text-align:left;"> $TSLA bear soup for breakfast, Elon will tweet tonight! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:49:51 </td>
   <td style="text-align:left;"> $TSLA  Texas is a republica state and All donors are well rich by oils and gas. Austin gigafactory don’t mean anything. Plus Texas has never supported clean and green energy that is why they have their own independen. Texas just passed the bill just make every single ev driver pay like over $400 extra a year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:49:29 </td>
   <td style="text-align:left;"> $TSLA when everybody selling that’s when you buy 😎💰💂🏿‍♂️🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:48:42 </td>
   <td style="text-align:left;"> $PL FUCK JOE BIDEN 👏🏻👏🏻👏🏻👏🏻👏🏻 $IPOF $TSLA $DMYS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:48:19 </td>
   <td style="text-align:left;"> $ARKK God told me to wait until $45 to buy the dip and that $TSLA will hit $450 in 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:47:44 </td>
   <td style="text-align:left;"> $TSLA Just look at your other holdings bulls, GME and AMC (it must be you still holding), thats what coming, even worse. Thats all this ever was, a long overdue short-squeeze, and it has come to an end. 
We welcome you with open arms  Mr and Ms True valuations </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:45:50 </td>
   <td style="text-align:left;"> $TSLA soon, bears be lookin for lube lmao 🤦‍♂️😂 https://www.tickerreport.com/banking-finance/8290872/analysts-anticipate-tesla-inc-nasdaqtsla-will-announce-quarterly-sales-of-15-51-billion.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:45:49 </td>
   <td style="text-align:left;"> $TSLA tesla faced zero competitors 2021 and 2022 face more then 22 ev companies to compete? Pick one more sales or less? Common Sense </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:45:18 </td>
   <td style="text-align:left;"> $TSLA  not my typical play but at this point they love f ing us up. i know we will pop again with Texas and Germany plus Upcoming Er. Lmk your honest opinion </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:45:00 </td>
   <td style="text-align:left;"> $TLRY $SAVA $BNGO $TSLA $GME one of the biggest frauds in stock market that got exposed by Game Stop spike is NAKED SHORT SELLING and Failure To Deliver that SEC has invented and is heavily abused. It needs to be banned. This is a good article, read and educate yourself and spread the word.  
https://www.thekomisarscoop.com/2021/02/how-the-gamestop-spike-reveals-corruption-of-naked-short-selling/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:44:51 </td>
   <td style="text-align:left;"> $TSLA if you&amp;#39;re still holding shares, take advantage of any pump to dump. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:44:39 </td>
   <td style="text-align:left;"> $TSLA This is not the way to crush the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:43:45 </td>
   <td style="text-align:left;"> $TSLA lets $1200 tomorrow, the last horrah </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:43:24 </td>
   <td style="text-align:left;"> $TSLA where we opening at tomorrow?  Will my 1025 puts 1/7 hit? Yolo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:43:14 </td>
   <td style="text-align:left;"> $TSLA let me get this straight to. 2021 tesla sold just over 900k cars but 500k cars recalled. Toyota and Volkswagen announced invested billion dollars to USA ev race against tesla and also more then 22 ev companies in USA ev race against tesla such as Toyota, Nissan, hyundai, kia. Volkswagen and so on. of course we know now there are more ev choices for better price, better styles and better quality then tesla. Plus Tesla made Most profit by selling ev in China but selling less then xpeng and nio. Now Chinese government huawei also in ev race with tesla. for Sure communist Chinese have played dirty way to put more restrictions on tesla To slow down tesla sales. So I don’t think 2022 there are much room for tesla to grow in sales </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:43:12 </td>
   <td style="text-align:left;"> $TSLA  she going back down and dragging the market with her..  900 or lower. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:42:33 </td>
   <td style="text-align:left;"> $TSLA 
BRUH 😲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:42:15 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL BOO... interest rates, sell! bunch of fools.. puts*😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:41:59 </td>
   <td style="text-align:left;"> $TSLA back to 900 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:41:45 </td>
   <td style="text-align:left;"> $TSLA won&amp;#39;t be surprised if it opens $1120 pre-market, and recovers $1170 lvls ✅🔥🤷 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:41:34 </td>
   <td style="text-align:left;"> $TSLA what bear 🐻 is gonna be fucked the most.  When this blast off again 

https://www.tickerreport.com/banking-finance/8290872/analysts-anticipate-tesla-inc-nasdaqtsla-will-announce-quarterly-sales-of-15-51-billion.html https://www.tickerreport.com/banking-finance/8290872/analysts-anticipate-tesla-inc-nasdaqtsla-will-announce-quarterly-sales-of-15-51-billion.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:41:23 </td>
   <td style="text-align:left;"> $TSLA 

Bears actually think Tesla has no more good news coming?  Ok whatever🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:40:20 </td>
   <td style="text-align:left;"> $TSLA 1088 indicated from the clouds. We may see more volatility tomorrow. Support 1050, below that we may see 1000 support if this is not holding huge down to 910. Inflation growing too fast and is keeps going higher if that&amp;#39;s not stopping hikes will be here quicker then we want to... SPY in correction and Tech got big problems. New ath after ER or around march-april.. from now tsla in bearish field cloud, could hit 1050 by tomorrow already...🥲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:40:13 </td>
   <td style="text-align:left;"> $TSLA get ready for an even bigger bear 🐻 dry
Ass hole Fuckin s A comin soon. 

https://www.tickerreport.com/banking-finance/8290872/analysts-anticipate-tesla-inc-nasdaqtsla-will-announce-quarterly-sales-of-15-51-billion.html https://www.tickerreport.com/banking-finance/8290872/analysts-anticipate-tesla-inc-nasdaqtsla-will-announce-quarterly-sales-of-15-51-billion.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:39:37 </td>
   <td style="text-align:left;"> $TSLA I think we will all bleed a bit but will turn around after the fud </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-06 07:39:10 </td>
   <td style="text-align:left;"> $TSLA that $100 run up was great right 😝😝😝 </td>
  </tr>
</tbody>
</table></div>

---
