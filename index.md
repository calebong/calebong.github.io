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



Last Updated: 2022-01-28 09:15:00 UTC +8

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
   <td style="text-align:left;"> https://tradingeconomics.com/vietnam/manufacturing-pmi </td>
   <td style="text-align:left;"> 2022-01-28 09:12:30 </td>
   <td style="text-align:left;"> Vietnam Manufacturing PMI Rises to 9-Month High </td>
   <td style="text-align:left;"> The IHS Markit Vietnam Manufacturing PMI rose to 53.7 in January 2022 from 52.5 in December, pointing to the fourth straight month of growth. The latest reading was also the highest figure since April, amid a further recovery y from the Delta wave. Both output and new orders rose the most in 9 months, while foreign sales expanded at the strongest pace since November 2018. A 2nd straight rise in employment was seen, while backlogs of work fell marginally which was the first drop in 5 months. Buying levels, meanwhile, grew for the 4th month running, as some firms tried to build inventory reserves.  Suppliers' delivery times continued to lengthen, amid problems with shipping and ongoing disruption despite the latest deterioration eased from September's series record. On inflation, input cost rose at the 2nd-slowest pace in 7 months, while output price inflation eased to the weakest since last September. Looking ahead, sentiment improved with overall optimism the strongest in over 3 years. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/taiwan/manufacturing-pmi </td>
   <td style="text-align:left;"> 2022-01-28 08:55:39 </td>
   <td style="text-align:left;"> Taiwan Manufacturing Growth Eases </td>
   <td style="text-align:left;"> The IHS Markit Taiwan Manufacturing PMI fell to 55.1 in January 2022 from a four-month high of 55.5 a month earlier. Still, the latest reading remained much higher than that seen on average since the survey began in April 2004 at 52.4. Output rose for the second month running, though the pace of growth softened slightly on the back of moderation in new orders. At the same time, the rate of job creation was mild and insufficient to prevent a further rise in backlogs; while buying levels eased to a four-month low. Meantime, export sales rose sharply with firms often citing stronger demand from Europe, China, and the US. Logistic delays was the least severe for 14 months, but the rate at which lead times increased stayed rapid. On prices, the rate of input cost inflation eased for the 2nd month in a row and the rate of output charge inflation also slowed but remained sharp. Finally, sentiment hit a 5-month high, amid anticipation of further recovery and the release of new products. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-28/singapore-house-prices-surge-most-in-decade-as-curbs-test-market?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-28 08:50:51 </td>
   <td style="text-align:left;"> Singapore House Prices Surge Most in Decade as Curbs Test Market </td>
   <td style="text-align:left;"> Faris Mokhtar                                                                                                                                                                                                                                                                     , Singapore home prices climbed the most in more than a decade last year, underpinning the government’s move to introduce cooling measures that will test the market’s resilience.                                                                                                  , Prices grew 10.6% in 2021, Urban Redevelopment Authority figures showed Friday. That’s the most since 2010, when they surged 17.6%. Values grew by 2.2% in 2020. Meanwhile, fourth-quarter prices climbed 5% from the previous three months, the same as the preliminary estimate. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/01/27/health/routine-vaccinations-millions-missed/index.html </td>
   <td style="text-align:left;"> 2022-01-28 08:49:47 </td>
   <td style="text-align:left;"> Millions of routine vaccinations have been missed amid the Covid-19 pandemic - CNN </td>
   <td style="text-align:left;"> (CNN)Millions of people in the United States are behind on their Covid-19 vaccinations, and millions more have missed other routine vaccinations throughout the pandemic.                                                                                                                                                                                           , Long before the coronavirus, public health officials were concerned about low levels of routine vaccinations that are recommended by the US Centers for Disease Control and Prevention for adults and adolescents for diseases like flu and HPV. A sharp drop in uptake over the two years of the pandemic has cut into the progress that has been made.             , Adults and adolescents have missed more than 37 million routine vaccinations during the Covid-19 pandemic, according to an analysis of insurance claims by Avalere, a health care consulting firm.                                                                                                                                                                   ,                                                                                                                                                                                                                                                                                                                                                                      , The firm compared monthly claims from January 2020 through June 2021 against baselines from 2019. On average, the analysis found, monthly claims were down 32% for adults and 36% for adolescents compared with 2019. Vaccinations ticked up briefly in March 2021 but otherwise consistently lagged behind 2019 levels in all markets.                              , Along with flu and HPV, vaccinations tracked in the analysis included hepatitis, chickenpox and shingles, MMR (measles, mumps and rubella), meningococcal, pneumococcal and Tdap (tetanus, diphtheria and pertussis).                                                                                                                                                , In the US Department of Health and Human Services' Healthy People 2030 plan, one goal in development is to increase the share of adults who receive recommended age-appropriate vaccines.                                                                                                                                                                            , "We were increasing coverage rates pretty consistently every year, and we wanted to do more," said Claire Hannan, executive director of the Association of Immunization Managers.                                                                                                                                                                                    , Improving vaccination coverage for flu and HPV are particularly of high priority, she said.                                                                                                                                                                                                                                                                          , Meningitis and Tdap are required by schools in most states, and coverage rates tend to be higher. But with flu and HPV, there's a "lack of urgency," and coverage rates were among the lowest.                                                                                                                                                                       ,                                                                                                                                                                                                                                                                                                                                                                      , As with Covid-19 vaccines, experts say that recommendations from health care providers -- including primary care physicians, nurses and pharmacists -- are one of the most effective ways to boost vaccination rates in general.                                                                                                                                     , The CDC recently published an outline of strategies to increase adult vaccination rates that was drafted by members of the National Adult and Influenza Immunization Summit and that served as a call to action to health care providers.                                                                                                                            , "Their recommendation remains the number one reason why people get vaccinated," said Dr. L.J. Tan, summit co-chair and former liaison to the CDC's vaccine advisory committee for the American Medical Association.                                                                                                                                                  , And Tan says the drop in routine vaccinations will come with costs in the years to come.                                                                                                                                                                                                                                                                             , "The biggest challenge here is an increase in vaccine-preventable diseases. We'll see outbreaks. We'll see surges of increased morbidity because of increased disease. And we'll see increased costs to the health care system," he said.                                                                                                                            , "When you couple it with Covid, we might see increased demand on the capacity of the health care system."                                                                                                                                                                                                                                                            , Between January 2020 and June 2021, adolescents ages 7 to 18 missed a total of about 10 million routine vaccinations, and adults age 19 and older missed a total of about 27 million vaccinations since January 2020, according to the Avalere analysis. Overall, those insured by commercial insurance plans accounted for nearly two-thirds of missed doses.       , Experts stress the importance of getting up to date as soon as possible.                                                                                                                                                                                                                                                                                             , "Go get that vaccine that you're missing. Catch up on the series. Have you started something, but you haven't finished the series? Go finish it now. If you're due for something that you haven't even started, go get it now," Tan said. "Now is the time to get caught back up again."                                                                             ,                                                                                                                                                                                                                                                                                                                                                                      , Getting a flu shot now can still make a difference in the current season, he said.                                                                                                                                                                                                                                                                                   , And as Covid-19 continues to circulate at an extremely high level in the US, keeping up with other routine vaccinations can help ease stress in a time of uncertainty.                                                                                                                                                                                               , "Routine vaccinations should give peace of mind," Hannan said. "We know these vaccines work."                                                                                                                                                                                                                                                                        , The analysis by Avalere -- and funded by GlaxoSmithKline -- used millions of de-identified patient records captured in a clearinghouse database. The datasets capture 42% of the US population insured by commercial plans, 69% of the Medicaid population, 25% of the Medicare Advantage population and less than 10% of Medicare Fee-For-Service claims nationwide., </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/producer-price-inflation-qoq </td>
   <td style="text-align:left;"> 2022-01-28 08:38:14 </td>
   <td style="text-align:left;"> Australia Q4 Producer Prices Rise the Most in Over 8 Years </td>
   <td style="text-align:left;"> The final demand producer price index in Australia increased by 1.3% qoq in Q4 2021, after a 1.1% rise in Q3. This was the sixth straight quarter of rises in the index and the highest reading since Q3 2013, boosted by a faster economic recovery in the wake of COVID-19 disruptions. There were rises in prices received for output of building construction (2.9%), due to ongoing strong demand for housing and builders passing on rising material and labor costs; heavy and civil engineering construction (1.4%), due to rises in steel, oil; motor vehicle and motor vehicle part manufacturing (4.4%), due to ongoing shortages of semi-conductors and other components limiting production.  Offsetting the rise were price falls in utilities and drainage services (-0.9%), due to higher electricity consumption spread over fixed costs; and sugar and confectionery manufacturing (4.4%), amid Christmas discounting. Through the year to Q4, producer prices went up 3.7%, the most since Q1 2009. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/singapore/housing-index </td>
   <td style="text-align:left;"> 2022-01-28 08:38:00 </td>
   <td style="text-align:left;"> Singapore Q4 Home Prices Rise the Most Since 2009 </td>
   <td style="text-align:left;"> Private home prices in Singapore surged 5.0 percent quarter-on-quarter in the three months to December of 2021, accelerating sharply from a 1.1 percent rise in the previous period and in line with a preliminary estimate. This marked the seventh straight quarter of increases in private home prices and the strongest growth since 2009, which prompted the government to introduce cooling measures in December, including raising additional stamp duties for second-home buyers and foreigners purchasing private residences, amid concerns over affordability. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-28/china-s-world-beating-bond-rally-may-have-run-its-course?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-28 08:32:38 </td>
   <td style="text-align:left;"> China’s World-Beating Bond Rally May Have Run Its Course </td>
   <td style="text-align:left;"> For those touting Chinese sovereign bonds as the place to be for debt investors, China market watchers are warning that the best parts of a rally could already be over.                                                                                                                                                          , Chinese bonds have been gaining since October as the People’s Bank of China pivots toward easing, even as Treasuries lead a global rout with other major central banks normalizing pandemic-era policies. The easy gains are over, and traders are now watching if the supportive policies will revive the economy, analysts said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/stock-market </td>
   <td style="text-align:left;"> 2022-01-28 08:21:01 </td>
   <td style="text-align:left;"> Stocks in New Zealand Hit 15-month Low </td>
   <td style="text-align:left;"> NZX 50 decreased to a 15-month low of 11976 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-01-28 08:12:13 </td>
   <td style="text-align:left;"> US Futures Rise as Apple Jumps on Record Sales </td>
   <td style="text-align:left;"> US stock futures rose on Friday as Apple shares jumped on after-hours trading towards the end of another volatile week. Dow futures edged up 0.5%, while S&amp;P 500 and Nasdaq 100 futures gained 0.6% and 1%, respectively. Shares of Apple surged nearly 5% in late trading after the company reported its largest quarterly revenue ever despite pandemic-induced supply disruptions. In regular trading on Thursday, the major indices were up more than 1% earlier in the session, before turning lower towards the close. The Nasdaq led the declines, falling 1.4% as prospects of higher rates continued to pressure technology and other growth stocks. The S&amp;P 500 dropped 0.54% and the Dow shed 0.02%. The major averages experienced outsized intraday swings each day this week as investors continued to digest the Federal Reserve’s pivot to tighter policy, with each set to end the week lower. The S&amp;P 500 and Nasdaq are both in correction territory, sitting 10.2% and 17.6% below their respective record highs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/biogen-stock-pops-after-agreement/story.aspx?guid={A83B371B-2865-46F5-915A-472A0EB1199B}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-28 08:10:44 </td>
   <td style="text-align:left;"> Biogen stock pops after agreement to sell Samsung part of joint venture - MarketWatch </td>
   <td style="text-align:left;"> Biogen Inc. 
        BIIB,
        -0.30%
       shares jumped in after-hours trading Thursday following an announcement that it is selling its part of a joint venture to Samsung Electronics Co. Ltd. 
        005930,
        +0.28%
       Biogen has been working with Samsung Bioepis since 2012, according to a news release, and will sell its equity stake in the bio-similars venture to the Samsung parent company for $2.3 billion. Biogen will receive $1 billion at closing with the rest split into two payments due over two years, and will continue with the two companies' exclusive arrangement, which includes commercialization of the current portfolio. Biogen shares jumped as much as 9% in after-hours trading following the announcement, though gains later settled back down to less than 3%., The order is expected to come in the next few weeks, a person familiar with the plan tells Barron's.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Jeremy Owens is MarketWatch’s technology editor and San Francisco bureau chief. You can follow him on Twitter @jowens510. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60161094?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-28 08:03:39 </td>
   <td style="text-align:left;"> Dover queues: The firms struggling with Brexit red tape </td>
   <td style="text-align:left;"> On the approach into Dover, there are queues of lorries, parked in one lane of the A20, stretching back for miles.                                                                           , They're being held along this road to avoid congesting the town, as they wait to board ferries across the Channel.                                                                           , Queues are not uncommon close to Britain's main trading hub with the EU, but they've been really long in recent weeks.                                                                       , And a month after more post-Brexit border bureaucracy came into force, many businesses - smaller ones especially - are struggling to cope.                                                   , Drivers waiting at a customs facility in Dover - most of them from elsewhere in Europe - are phlegmatic, but fed up.                                                                         , "I'm waiting maybe one hour, next week maybe five hours, it's always different," said one.                                                                                                   , "When we're waiting, there's no money," said another.                                                                                                                                        , For drivers who are paid by the kilometre that's a real concern, and it means some will be reluctant to come back.                                                                           , The drivers blame cancelled ferry crossings - there are temporarily fewer ferries in operation than normal.                                                                                  , But they also blame the post-Brexit rules that now govern their working lives.                                                                                                               , Last year, which was Britain's first outside the EU single market and customs union, companies had sixty days to fill in UK customs documents after exporting goods to the EU.               , But since 1 January, those forms have to completed in full, before lorries and vans can board ferries heading for Europe every day.                                                          , Thousands of drivers need to get their documents checked, and the process is taking time.                                                                                                    , "For us, the government is staging Brexit bit-by-bit," says John Shirley, who's run a freight-forwarding company in Dover for 25 years.                                                      , "That's caused all sorts of headaches for people, they don't know the paperwork properly or haven't prepared themselves - that's what's causing the delays here."                            , He recounts meeting a driver earlier in the week who had been stuck in Dover for four days, with a lorry going to Germany, a journey which used to be routine.                               , Won't it get better with time, I suggest, as companies get used to a new system?                                                                                                             , "I don't know, I suspect it won't do," he replies. "And in July we get an additional set of controls on foodstuffs."                                                                         , That is a development David Pavon is having to prepare for.                                                                                                                                  , At the small Spanish deli he runs in Bristol, he relies on imports from his homeland.                                                                                                        , All businesses bringing goods into the country from Europe have also been dealing with new bureaucracy over the last few weeks.                                                              , That means each individual consignment of the olives, chorizos or serrano ham that David imports now needs separate customs forms, where there used to be none at all.                       , But later in the year, most of the food products he imports will need to be physically inspected as well, when they arrive in the UK.                                                        , "We will need to do more paperwork, and pay more, and we might need to increase the prices," he says.                                                                                        , "It's certainly more difficult, but there is no other way unless we close the doors and shut the business. We need to do it."                                                                , So, what happens in places like Dover will have a wider impact. The smoother the system can become, the better for businesses across the country.                                            , But while those who still believe they can make a profit are finding new ways to trade, and to cope with bureaucracy and delay, others have concluded that it is no longer worth the hassle. , Global trade rebounded pretty well last year from the slump produced by the Covid pandemic in 2020.                                                                                          , But there was not much bounce back for British trade with the EU.                                                                                                                            , Many European exporters who used to trade into Great Britain seem to have decided to focus their attention elsewhere in the single market instead, or further afield.                        , German exports to the rest of the EU, for example, grew by 17% in the first eleven months of last year, compared to the same period in 2020. They also rose by 18% to the US.                , But exports to the UK fell by 2%.                                                                                                                                                            , That's a massive difference. Britain is doing much less trade with Europe than it used to.                                                                                                   , From the cliffs above Dover, you can watch ferries coming and going on a constant basis.                                                                                                     , The government says traders need to get used to new rules here, and also take advantage of new trade deals it is negotiating on the other side of the world.                                 , But two years after Britain left the EU, the idea of seamless trade across the narrow stretch of water beneath the white cliffs?                                                             , That ship seems to have already sailed.                                                                                                                                                      , The story of the Holocaust through the eyes of remarkable 106-year-old Boris Pahor                                                                                                           , Watch the gripping new police drama, The Responder, starring Martin Freeman                                                                                                                  , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/team:us </td>
   <td style="text-align:left;"> 2022-01-28 07:55:40 </td>
   <td style="text-align:left;"> Atlassian Corporation PLC earnings above expectations at 0.50 USD </td>
   <td style="text-align:left;"> Atlassian Corporation PLC (TEAM) released earnings per share at 0.50 USD, compared to market expectations of 0.39 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-27/biogen-sells-bioepis-stake-for-2-3-billion-to-samsung-biologics?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-28 07:52:35 </td>
   <td style="text-align:left;"> Biogen Sells Bioepis Stake for $2.3 Billion to Samsung Biologics </td>
   <td style="text-align:left;"> Biogen Inc. headquarters in Cambridge, Massachusetts, U.S.                                                                                                                         , Heejin Kim                                                                                                                                                                         ,  and Angelica Peebles                                                                                                                                                              , Samsung Biologics Co. will buy 49.9% of Samsung Bioepis from Biogen Inc., according to a regulatory filing, giving the South Korean drugmaker full ownership of the joint venture. , Shares of Biologics rose as much as 0.4% in Seoul on Friday. Shares of Cambridge, Massachusetts-based Biogen rose 2.29% during after-hours trading in New York.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/construction-output </td>
   <td style="text-align:left;"> 2022-01-28 07:16:36 </td>
   <td style="text-align:left;"> South Korea Construction Output Rebounds </td>
   <td style="text-align:left;"> Construction output in South Korea rose 1.5 percent year-on-year in December of 2021, following a 5.6 percent drop in the previous month. It was the time that the construction output increased after fourteen consecutive months of falling activity as civil the building activity growth accelerated to a 6.5 percent increase (from 1.8 percent), civil engineering output contraction eased to 7.8 percent (from a 24.5 percent drop). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/retail-sales-annual </td>
   <td style="text-align:left;"> 2022-01-28 07:11:19 </td>
   <td style="text-align:left;"> South Korea Retail Sales Grows For the 11th Consecutive Month </td>
   <td style="text-align:left;"> Retail sales in South Korea increased 6.5 percent year-on-year in December of 2021, accelerating from a 4.6 percent rise in the prior month, and marking the eleventh straight month of gains in retail trade. On a monthly basis, retail sales increased 2.0 percent, after dropping 1.9 percent in the previous period. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/industrial-production </td>
   <td style="text-align:left;"> 2022-01-28 07:08:40 </td>
   <td style="text-align:left;"> South Korea Industrial Output Tops Forecast </td>
   <td style="text-align:left;"> Industrial production in South Korea increased 6.2 percent year-on-year in December of 2021, after an upwardly 6.3 percent increase in the previous month and above market expectations of a 2 percent increase. It was the third consecutive month with a positive number as manufacturing activity rose 6.8 percent, up from a 6.2 percent increase in November. On a seasonally adjusted monthly basis, industrial production rose 4.3 percent, following an upwardly revised 5.3 percent increase in the previous month and well above market expectations of a 1 percent increase. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/27/stock-market-futures-open-to-close-new.html </td>
   <td style="text-align:left;"> 2022-01-28 07:03:57 </td>
   <td style="text-align:left;"> Stock futures rise as market set to wrap up a wild week, Apple shares pop </td>
   <td style="text-align:left;"> , Stock futures rose in overnight trading Thursday, boosted by a jump in Apple shares, as Wall Street looks to wrap up a roller-coaster week on a high note.                                                                                                                                                                , Futures on the Dow Jones Industrial Average gained about 100 points. S&amp;P 500 futures climbed 0.3% and Nasdaq 100 futures jumped 0.7%.                                                                                                                                                                                     , Shares of Apple popped nearly 5% in after-hours trading after the company reported its largest single quarter in terms of revenue ever. Its sales grew more than 11% even amid supply challenges and the lingering effects of the pandemic. Apple beat analyst estimates for sales in every product category except iPads., Major averages have experienced outsized intraday swings each day this week as investors continued to digest the Federal Reserve's pivot to tighter policy. The market's fear gauge Cboe Volatility Index shot up to its highest level since October 2020 earlier this week and has traded above the 30 threshold.        ,                                                                                                                                                                                                                                                                                                                           , The Dow just came off its ninth negative session in 10, falling 0.3% on the week and could head for its fourth negative week in a row. The S&amp;P 500 is down 1.62% week to date, while the tech-heavy Nasdaq Composite has dropped 1.4%, on track for its straight fifth negative week.                                     , The S&amp;P 500 and the Nasdaq are both now in correction territory, sitting 10.2% and 17.6% below their respective record highs.                                                                                                                                                                                             , The Fed indicated Wednesday that it could soon raise interest rates for the first time in more than three years as part of a broader tightening of historically easy monetary policy.                                                                                                                                     , Acquisition talk is in the air. Goldman thinks it knows who may be next                                                                                                                                                                                                                                                   , Stanley Druckenmiller says listen to the bond market. Here's what that means                                                                                                                                                                                                                                              , Morgan Stanley, Barclays say UK stocks are looking cheap and can weather risk-off period                                                                                                                                                                                                                                  , "The FOMC meeting did not bring any surprises in terms of monetary policy, however, it may be perceived as more hawkish than expectations owing to Chair Powell's suggestion of a need to enter a 'steady' phase of policy normalization," Chris Hussey, a managing director at Goldman Sachs, said in a note.            , The fourth-quarter earnings season has been solid so far. Of the 145 companies in the S&amp;P 500 that have reported to date, 79.3% topped analyst expectations, according to Refinitiv.                                                                                                                                      , Chevron is set to report numbers before the bell on Friday.                                                                                                                                                                                                                                                               , "For now, I am determined to not fight the Fed. I'm bracing for heightened market volatility and significantly more modest market returns," said Brian Levitt, Invesco's global market strategist.                                                                                                                        , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                    , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                    , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                          , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                          , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                        , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-27/u-s-labor-department-chief-economist-jones-departs-from-post?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-28 07:03:42 </td>
   <td style="text-align:left;"> U.S. Labor Department Chief Economist Jones Departs From Post </td>
   <td style="text-align:left;"> Katia Dmitrieva                                                                                                                                                                                                                                                               , Janelle Jones, the first Black woman to serve as chief economist at the U.S. Department of Labor, said she left her position Thursday after less than a year serving in the role.                                                                                             , Jones announced her departure on Twitter, saying that working in the administration “has been an incredible experience. And it ended today.” She didn’t specify the reason for the unexpected departure, and said she would spend all of February reading sci-fi and fantasy.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60163814?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-28 07:02:02 </td>
   <td style="text-align:left;"> Apple sales soar despite supply constraints </td>
   <td style="text-align:left;"> Apple sales soared in the key Christmas shopping season, despite constraints due to a global shortage of microchips.                                                                                                                                                              , Sales at the iPhone giant rose 11% to a record $123.9bn (£92.6bn) in the October to December period, beating forecasts.                                                                                                                                                           , Shares jumped more than 4% in after-hours trade, as the report suggested the firm's pandemic boom is continuing.                                                                                                                                                                  , Apple has seen purchases skyrocket during the pandemic as people spend more time online.                                                                                                                                                                                          , The firm's market value briefly hit the $3tn milestone in early January though its share price has slipped more recently amid weeks of market turmoil.                                                                                                                            , Executives had warned last year that the global shortage of microchips might limit its sales, but the firm's quarterly  update to investors on Thursday showed it brushing past those constraints.                                                                                , Mac sales were up 12%, while iPhone sales jumped 9%.                                                                                                                                                                                                                              , With few rival phones debuting in the holiday shopping season, the iPhone 13, which started shipping days before the quarter began, led to worldwide phone sales revenue for Apple of $71.6b.                                                                                     , Revenue from the company's services unit - which includes Apple Pay, the App store and its TV streaming service, was up more than 23%.                                                                                                                                            , The iPad, which executives said was particularly affected by the supply issues, was the one product that showed weakness, with sales slipping 14%.                                                                                                                                , Demand in China, where sales rose 20%, propelled the firm's growth in the quarter.                                                                                                                                                                                                , Apple said profits were $34.6bn, up 20%.                                                                                                                                                                                                                                          , The company, which has more than 1.8 billion active devices in the market, has been able to put pressure on suppliers and manufacturers to produce big quantities of iPhones and other devices despite shortages brought on by the pandemic and most recently the Omicron variant., "They've navigated the supply chain better than everybody, and it's showing in the results," said Ryan Reith, who studies the smartphone market for industry tracker IDC.                                                                                                         , Chief Financial Officer Luca Maestri said that supply constraints would decrease in the current quarter, which ends in March.                                                                                                                                                     , "The level of constraint will depend a lot on other companies, what will be the demand for chips from other companies and other industries. It's difficult for us to predict, so we try to focus on the short term," he said.                                                     , The story of the Holocaust through the eyes of remarkable 106-year-old Boris Pahor                                                                                                                                                                                                , Watch the gripping new police drama, The Responder, starring Martin Freeman                                                                                                                                                                                                       , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/27/business/libor-manipulation-deutsche-bank-traders.html </td>
   <td style="text-align:left;"> 2022-01-28 06:47:55 </td>
   <td style="text-align:left;"> Two former Deutsche Bank traders win their appeal in a Libor manipulation case. - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                  , But ruling is another indication of the difficulty prosecutors have had making the case that traders at a handful of big banks conspired to profit from manipulating Libor, the benchmark once used by banks to set interest rates.                                                                                                                                                                                                            , By Matthew Goldstein                                                                                                                                                                                                                                                                                                                                                                                                                           , The decade-long pursuit of holding Wall Street accountable for trying to manipulate Libor, the once-prominent interest rate benchmark, suffered another blow Thursday when a federal appeals court overturned the convictions of two former Deutsche Bank traders.                                                                                                                                                                             , A three-judge panel for the U.S. Court of Appeals for the Second Circuit in New York said federal prosecutors had failed to provide sufficient evidence to support the 2018 convictions of Matthew Connolly and Gavin Black on fraud and conspiracy charges.                                                                                                                                                                                   , The unanimous ruling is the latest in a series of defeats for prosecutors in the United States and Britain, as more than a dozen traders have been acquitted at trial or had their convictions overturned. In 2017, another appellate panel from the Second Circuit tossed out the Libor manipulation convictions of two former Rabobank traders.                                                                                              , The convictions of some traders who took guilty pleas still stand. But the latest ruling is another indication of the difficulty prosecutors have had making the case that traders at a handful of big banks conspired to profit from manipulating Libor, the benchmark once used by banks to set interest rates on an array of loans.                                                                                                         , Libor relied on self-reported estimates of borrowing costs from banks, and prosecutors and regulators said traders pushed for those bids to be artificially high or low to make certain financial assets more profitable.                                                                                                                                                                                                                      , In dismissing the convictions of Mr. Connolly and Mr. Black, the appellate panel said the prosecutors hadn’t proved that the bids submitted by the bank were not rates that it could have borrowed at. “The government failed to show that any of the trader-influenced submissions were false, fraudulent or misleading,” the panel wrote. It added, “The Libor submissions were not false.”                                                  , Kenneth Breen, a lawyer for Mr. Connolly, said his client had been “fully exonerated in this contrived case.” Seth Levine, a lawyer for Mr. Black, said his client had committed no crime and was “deeply appreciative” that the appeals panel agreed.                                                                                                                                                                                         , The Justice Department did not immediately comment.                                                                                                                                                                                                                                                                                                                                                                                            , The crackdown on the manipulation of what was formally known as the London Interbank Offered Rate was one of the major criminal prosecutions to arise from the financial crisis of 2008. Big lenders including Deutsche Bank paid billions of dollars in penalties to authorities in the United States and Britain to resolve accusations that their traders sought to rig Libor. Some banks pleaded guilty in deferred prosecution agreements., The investigations helped prompt international banking officials to phase out Libor as the primary benchmark for setting rates on loans and in derivatives contracts.                                                                                                                                                                                                                                                                          , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/27/robinhood-wants-to-make-stock-trading-available-more-hours-of-the-day-with-hyper-extended-hours.html </td>
   <td style="text-align:left;"> 2022-01-28 06:42:26 </td>
   <td style="text-align:left;"> Robinhood wants to make stock trading available more hours of the day with 'hyper-extended hours' </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Robinhood is planning to roll out a feature to let its millions of clients trade stocks well outside of normal market hours.                                                                                                                                                                                                                                                                                                                                                   , "We're also close to delivering a feature that our customers have been asking for: an ever larger window of available trading hours. We call this feature 'hyper-extended hours' and anticipate rolling it out later this quarter," Robinhood CEO Vlad Tenev said on the company's earnings call on Thursday.                                                                                                                                                                  , Depending on how much extended trading it will offer, this is the kind of change that likely needs the approval of the Securities and Exchange Commission, but the company did not say whether it has petitioned the regulatory body. The U.S. stock market opens at 9:30 a.m. ET and closes at 4:00 p.m. as part of its regular session. Extended trading is allowed as early as 4 a.m. and goes as late as 8 p.m. and some electronic brokers do offer that extended access. , Currently, Robinhood offers trading 30 minutes before the open and 2 hours after the close.                                                                                                                                                                                                                                                                                                                                                                                    , A representative for the SEC did not immediately respond to CNBC's request for comment.                                                                                                                                                                                                                                                                                                                                                                                        , Robinhood is not alone in seeking more trading hours than the norm, especially in a world where cryptocurrencies are traded 24 hours a day including weekends. A start-up backed by Steve Cohen, 24 Exchange, has filed a draft application with the SEC to provide 24-hour stock trading and told CNBC it expects a decision this summer.                                                                                                                                     , Robinhood ended 2021 with 22.7 million net cumulative funded accounts, with more than 10 million of the accounts being added in 2021 alone. However, the latest quarter showed the broker lost monthly active users last quarter. Shares of Robinhood tumbled as much as 15% in after hours trading after the company gave a weak revenue forecast for the first quarter.                                                                                                      , —With reporting by Tom Franck and Yun Li                                                                                                                                                                                                                                                                                                                                                                                                                                       , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                                         , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                                         , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                                               , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                                               , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                                             , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60163757?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-28 06:35:28 </td>
   <td style="text-align:left;"> Former traders cleared of US rate rigging </td>
   <td style="text-align:left;"> A US appeals court has overturned the convictions of two former Deutsche Bank traders who were prosecuted for rigging interest rates.                                                                                                    , In a legally significant judgment, US judges acquitted Matthew Connolly, 58, from New Jersey and Gavin Black, 52, from Twickenham, Middlesex.                                                                                            , The court ruled that their conduct was not against the rules.                                                                                                                                                                            , It means that what has been prosecuted as interest rate rigging in the UK is not regarded as a crime in the US.                                                                                                                          , The US Court of Appeals for the Second Circuit ruled that it was not against the rules to seek to influence the estimates a bank submits of the cost of borrowing cash.                                                                  , That is different to a key British appeal court ruling that was used to prosecute 24 traders, nine of whom were jailed between 2015 and 2019.                                                                                            , For Mr Connolly and Mr Black, it's the end of an eight-year struggle to prove that what they were accused of was not criminal.                                                                                                           , The evidence against Matt Connolly was just four emails from 14 years ago, asking for high or low interest rate estimates to be submitted.                                                                                               , Matt Connolly told the BBC on Thursday he was "speechless" to have won in court for the first time.                                                                                                                                      , "My family and I are very thankful this ordeal is finally ending, and that the courts have finally recognised once and for all my innocence," he said.                                                                                   , "I am hoping the rest of the story emerges so others that have been denied justice get their peace as well."                                                                                                                             , "The nine trials on both sides of the Atlantic have been a whole series of miscarriages of justice where innocent people were jailed who had done nothing wrong.                                                                         , "The only Libor 'rigging' that was really bad was the lowballing. That was ordered from the top - from central banks and governments. And neither the Department of Justice nor the Serious Fraud Office has ever brought that to trial.", The evidence against Mr Connolly was only four emails that he had sent 12 years previously.                                                                                                                                              , A BBC investigation in 2019 raised questions about the safety of his convictions.                                                                                                                                                        , A few weeks later, a judge in the New York court gave them light sentences of home confinement after learning that the Bank of England had been involved in the same conduct on a much larger scale.                                     , Judge Colleen McMahon said at the time: "I'm always uncomfortable when I'm asked in any context - it usually happens in the drug context - to sentence the low man on the totem pole while the big guy goes free."                       , The evidence against traders, both in the US and the UK, were emails and messages requesting that colleagues publish "high" or "low" estimates of the cost of borrowing cash.                                                            , The estimates would be averaged to get a rate called Libor (London Interbank Offered Rate) which is being phased out in favour of other benchmarks.                                                                                      , What the FTSE or Nikkei are to share prices, Libor was to interest rates - an index that tracked the cost of borrowing cash between the banks.                                                                                           , It was used to set interest rates on millions of residential and commercial loans around the world.                                                                                                                                      , To work out Libor each day, 16 banks answered a question - at what interest rate could they borrow money? They submitted their answers and an average was taken.                                                                         , The evidence against Tom Hayes and other traders consisted of messages and emails asking for those interest rates to be submitted "high" or "low".                                                                                       , There were no laws or written regulations about Libor at the time the traders made the requests.                                                                                                                                         , In late 2014, lawyers for Tom Hayes, the first trader jailed for rate rigging, argued that because there was no rule against the traders' requests the case should be dismissed.                                                         , In January 2015, Lord Justice Davies ruled that it was "self-evident" that the requests were against the rules.                                                                                                                          , Banks were not allowed to take into account commercial interests, such as trading positions linked to the Libor rate, when making their estimates.                                                                                       , That ruling was used to prosecute 24 traders in the UK.                                                                                                                                                                                  , Mr Hayes, who got the longest sentence, told the BBC: "This considered court ruling completely contradicts [UK] Court of Appeal rulings ahead of my trial.                                                                               , "Those rulings formed the basis of the case in law to prosecute not only myself but every trader subsequently who faced trial.                                                                                                           , "Four times, traders have been denied leave by the Court of Appeal to make the case to the Supreme Court, when there is clearly a point of law of significance that needs to be heard at the highest level.                              , "I hope that the British courts will, in time, reach the same conclusion."                                                                                                                                                               , The story of the Holocaust through the eyes of remarkable 106-year-old Boris Pahor                                                                                                                                                       , Watch the gripping new police drama, The Responder, starring Martin Freeman                                                                                                                                                              , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-27/asia-stocks-may-rise-u-s-shares-fall-dollar-up-markets-wrap </td>
   <td style="text-align:left;"> 2022-01-28 06:33:21 </td>
   <td style="text-align:left;"> Asian Stocks, U.S. Futures Up as Apple Eases Gloom: Markets Wrap </td>
   <td style="text-align:left;"> Sunil Jagtiani                                                                                                                                                                                                                             , Asian stocks Friday recovered some of the losses sparked by the Federal Reserve’s pivot to tighter monetary policy, while U.S. equity futures climbed after strong Apple Inc. earnings aided sentiment.                                    , Shares rose in Japan and Australia but South Korea fluctuated. Contracts on the tech-heavy Nasdaq 100 outperformed S&amp;P 500 futures following a rally in Apple Inc. in extended trading on record sales that weathered supply-chain snarls.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/technology/affirm-ceo-new-super-app-with-google-chrome-extension-will-help-bring-consumer-spending-power-back </td>
   <td style="text-align:left;"> 2022-01-28 06:30:02 </td>
   <td style="text-align:left;"> Affirm CEO: New super app, Google Chrome extension will help bring consumer ‘spending power’ back </td>
   <td style="text-align:left;"> Affirm co-founder and CEO Max Levchin discusses his plan to streamline consumer finance on 'The Claman Countdown.'                                                                                                                                                                                                                                                , Affirm CEO Max Levchin announced on Thursday the launch of a new app that consolidates all its services in one place, while incorporating a Google Chrome extension for online consumers.                                                                                                                                                                         , The co-founder and CEO explained on "The Claman Countdown" that the feature will create "more places to buy in a safe, transparent way" from merchants who have not yet been integrated with the service.                                                                                                                                                         , "We'll generate a one-time card number the consumer can easily plug into the standard checkout flow at the merchant site and complete the transaction," Levchin said of the browser extension. "The merchant gets the sale, Affirm, of course, pays the merchants, and the consumer pays back Affirm as they normally would. More coverage for our consumers."    , SHRINKFLATION REDUCES SIZE OF POPULAR CONSUMER PRODUCTS                                                                                                                                                                                                                                                                                                           , Affirm, a financial technology company, is known for its "buy now, pay later" installments with no hidden fees. Depending on the size of the purchase and the merchant involved, the term lengths typically vary around 3, 6, or 12-month durations.                                                                                                              , "We stand for transparency and simplicity, and that’s really captured the minds of our customers," Levchin said of the company's values.                                                                                                                                                                                                                          , Affirm CEO on lending amid coronavirus                                                                                                                                                                                                                                                                                                                            , The new app will offer consumers the option to manage their finances, shop personalized offers, and even invest.                                                                                                                                                                                                                                                  , "The reason for the super app, frankly, is to unify and showcase all of the good things we can do for you as a customer," Levchin told co-host Liz Claman. "We feel very confident about our ability to assure these transactions and bring on more growth."                                                                                                      , Levchin said while Americans are grappling with record-high inflation, the company is excited to "help regular people buy the things they need." GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                      , "The country is in a much better shape," He added. "Which is also our cue. Our business is to help folks regain that spending power ability to pay over time, in a safe way, without revolving, without gotchas and fees. That’s what Affirm is.""Our moment to shine is to actually bring this spending power back to those hit hard by inflation," he concluded. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/us-steel-sales-come-above/story.aspx?guid={CEBCC4C3-B938-443F-8606-D6B5FC6A753A}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-28 06:22:50 </td>
   <td style="text-align:left;"> U.S. Steel sales come in above Wall Street expectations - MarketWatch </td>
   <td style="text-align:left;"> U.S. Steel Corp. 
        X,
        -0.11%
       shares rose nearly 2% in the extended session Thursday after the steel producer posted quarterly sales above Wall Street expectations. U.S. Steel said it earned $1.1 billion, or $3.75 a share, in the quarter, compared with $49 million, or 22 cents a share, in the year-ago period. Adjusted for one-time items, the company earned $3.64 a share. Sales rose to $5.6 billion, from $2.6 billion a year ago. Analysts polled by FactSet expected adjusted earnings of $4.37 a share on sales of $5.4 billion. The company said its board has authorized a new $500 million stock buyback program to start in the first quarter. That is in addition to a previously announced $300 million program, U.S. Steel said. Shares of the company ended the regular trading day down 0.1%, On the anniversary of Kobe Bryant's death, here’s a look how the NBA legend invested the money that he earned on and off the court                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/politics/2022/01/27/conservatives-biden-scotus-pick-lead-vpx.cnn </td>
   <td style="text-align:left;"> 2022-01-28 06:22:06 </td>
   <td style="text-align:left;"> Fox anchor: 'What kind of qualification is that, being a Black woman?' - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/home-depot-names-new-ceo/story.aspx?guid={1062CD4A-D0C1-425D-AA79-D6C1E1507620}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-28 06:07:43 </td>
   <td style="text-align:left;"> Home Depot names new CEO, Craig Menear to remain chairman - MarketWatch </td>
   <td style="text-align:left;"> Home Depot Inc. 
        HD,
        -0.24%
       said late Thursday that Ted Decker has been named its chief executive and president, effective March 1. Decker also has been elected to the company's board of directors. Chief Executive and Chairman Craig Menear will continue to serve as chair of the board, the retailer said. Shares of Home Depot rose 2% in the extended session Thursday after ending the regular trading day down 0.2%., Here's what the chief executive of ARK Invest had to say.                                                                                                                                                                                                                                                                                                                                                                                               , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/mondelezs-q4-sales-rise-5/story.aspx?guid={E834F9F3-9452-468F-A021-B306F6B5D0D3}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-28 05:59:08 </td>
   <td style="text-align:left;"> Mondelez's Q4 sales rise 5% - MarketWatch </td>
   <td style="text-align:left;"> Shares of Mondelez International Inc. 
        MDLZ,
        +1.28%
       fell nearly 2% in the extended session Thursday after the snacks and candy giant posted mixed quarterly results. Mondelez said it earned $1 billion, or 71 cents a share, in the quarter, compared with $1.2 billion, or 80 cents a share, in the year-ago period. Adjusted for one-time items, the company earned 72 cents a share. Sales rose 5% to $7.7 billion, from $7.3 billion a year ago. Analysts polled by FactSet expected adjusted EPS of 73 cents on sales of $7.6 billion. Mondelez guided for "high single digit" per-share growth in 2022. "2021 marked another year of strong top and bottom-line results despite a challenging macro environment," Chief Executive Dirk Van de Put said in a statement. Mondelez stock ended the regular trading dayup 1.3%. , After being poor, rich—then poor again—she now helps people avoid costly money mistakes.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/27/stocks-making-the-biggest-moves-after-hours-robinhood-apple-visa-and-more.html </td>
   <td style="text-align:left;"> 2022-01-28 05:53:54 </td>
   <td style="text-align:left;"> Stocks making the biggest moves after hours: Robinhood, Apple, Visa and more </td>
   <td style="text-align:left;"> , Check out the companies making headlines after the bell:                                                                                                                                                                                                                                                                          , Robinhood — Shares of the trading app plunged a whopping 15% after the company gave a disappointing revenue forecast for the first quarter of 2022. Its latest earnings report also showed a decline in users. Monthly active users fell to 17.3 million last quarter from 18.9 million in the third quarter.                     , Apple — The tech stock rose more than 2% in after-hours trading after the company reported its largest single quarter in terms of revenue ever. Its sales grew more than 11% even amid supply challenges and the lingering effects of the pandemic. Apple beat analyst estimates for sales in every product category except iPads., Visa — The credit card company saw its shares jump 5% in extended trading after a better-than-expected earnings report. Visa's adjusted earnings per share came to $1.81, higher than a Street estimate of $1.70 per share, according to Refinitiv. Its revenue also topped expectations.                                         , Western Digital — Shares of the data storage company slid 12% in extended trading even after a strong earnings report. The company's EPS came in at $2.30 per share, compared with an estimate of $2.13 per share, according to FactSet. Sales also beat analysts' forecast. The stock has fallen more than 17% in 2022.          , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                            , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                            , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                  , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                  , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/features/california-law-cost-some-farmers-millions-inflation-food-bacon-price </td>
   <td style="text-align:left;"> 2022-01-28 05:38:20 </td>
   <td style="text-align:left;"> California's new law could cost some farmers millions, raise the price of one of America's favorite foods </td>
   <td style="text-align:left;"> Animal activists say Proposition 12 is about treating farm animals humanely. But, pork farmers say the law doesn't improve care and could cost them thousands per pig.                                                                                                                         , A California law that took effect this month is forcing Midwest farmers to make tough financial decisions. Proposition 12 requires farmers to increase the sizes of animal cages if they’re shipping pork, veal, or eggs to California.                                                        , Iowa is the country’s number one pork-producing state, and California consumes 13% of U.S. pork. Animal activists say Proposition 12 is about humane treatment for the breeding pigs, but farmers say the new requirements don’t improve care and could cost them thousands of dollars per pig., WILL NEW BACON LAW BEGIN? CALIFORNIA GROCERS SEEK DELAY                                                                                                                                                                                                                                        , Mike Paustian is a sixth-generation pork farmer on his family’s farm.                                                                                                                                                                                                                          , "It was started by my great-great-great-grandfather who came over from Germany and there have been Paustian’s farming there ever since then," said Paustian.                                                                                                                                   , Paustian says the pork industry is a huge deal in Iowa, but Proposition 12 is forcing farmers like him to gamble with their future. The law requires more cage space for breeding pigs. If barns don’t follow the new standards, they can’t sell their raw meat in California.                 , "Most of the pigs currently being raised don’t meet those standards," said Paustian.                                                                                                                                                                                                           , Farmers say the new cage requirements don't improve the care of breeding pigs.                                                                                                                                                                                                                 , Paustian says another issue with the law is it's unclear if the standards will stick around or be replaced by something different in the future. Iowa Pork Producers Association CEO Pat McGonegle says the standards will cost up to $3,000 per breeding pig.                                 , ‘BACON BAN’: IOWA CONGRESSWOMAN INTRODUCES EATS ACT IN RESPONSE TO CALIFORNIA'S BAN ON CERTAIN MEAT PRODUCTS                                                                                                                                                                                   , "It certainly has a significant economic impact," said McGonegle.                                                                                                                                                                                                                              , McGonegle says the Proposition 12 requirements don’t improve the care of the breeding pigs.                                                                                                                                                                                                    , "It is in our interest to take good care of them. So, I think the implication that we don’t take care of them today is completely wrong," said McGonegle.                                                                                                                                      , California is also expected to feel the financial effects of Prop 12. Some Proposition 12 opponents say the state could see bacon prices initially spike 60%, and a University of California study says the law will cost state residents $320 million more annually.                          , BIDEN AIMS TO REDUCE MEAT PRICES WITH MORE REGULATIONS, FEDERAL SPENDING                                                                                                                                                                                                                       , The Humane Society of the United States Vice President of Farm Animal Protection Josh Balk says hundreds of farmers are already following Proposition 12, and this is about treating farm animals humanely.                                                                                    , "Policies have united across the industry calling on pork producers to stop treating animals this cruelly and such barbarically to confine them in a cage unable ever to move around," said Balk.                                                                                              , Proposition 12 is trying to ban gestation crates seen above. Source: Humane Society of the U.S.                                                                                                                                                                                                , Balk says wanting farm animals to have humane treatment is an ordinary American value to have.                                                                                                                                                                                                 , "It passed overwhelmingly with support from Republicans, independents, and Democrats alike, and that’s because it’s common sense that we shouldn’t confine an animal in a cage barely larger than her entire animal," said Balk.                                                               , But farmers say they’re the ones getting a raw deal.                                                                                                                                                                                                                                           , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                    , "My whole goal is to make sure that the farm is around so that if my kids want to farm someday that they’d be able to, and so right now, Prop 12 is not a gamble that I’m willing to make on my farm," said Paustian.                                                                          , The California Superior Court is delaying the enforcement of Proposition 12 since regulations still aren't finalized. The law remains in effect, but farmers can’t be penalized yet. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-korea/currency </td>
   <td style="text-align:left;"> 2022-01-28 05:37:10 </td>
   <td style="text-align:left;"> South Korean Won Hits 19-month Low </td>
   <td style="text-align:left;"> USDKRW increased to a 19-month high of 1208 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/klac:us </td>
   <td style="text-align:left;"> 2022-01-28 05:35:17 </td>
   <td style="text-align:left;"> KLA-Tencor earnings above expectations at 5.59 USD </td>
   <td style="text-align:left;"> KLA-Tencor (KLAC) released earnings per share at 5.59 USD, compared to market expectations of 5.44 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/syk:us </td>
   <td style="text-align:left;"> 2022-01-28 05:34:29 </td>
   <td style="text-align:left;"> Stryker earnings below expectations at 2.71 USD </td>
   <td style="text-align:left;"> Stryker (SYK) released earnings per share at 2.71 USD, compared to market expectations of 2.73 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mdlz:us </td>
   <td style="text-align:left;"> 2022-01-28 05:34:15 </td>
   <td style="text-align:left;"> Mondelez International earnings meet market expectations at 0.71 USD </td>
   <td style="text-align:left;"> Mondelez International (MDLZ) released earnings per share at 0.71 USD, in line with market expectations. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/v:us </td>
   <td style="text-align:left;"> 2022-01-28 05:33:31 </td>
   <td style="text-align:left;"> Visa earnings above expectations at 1.81 USD </td>
   <td style="text-align:left;"> Visa (V) released earnings per share at 1.81 USD, compared to market expectations of 1.70 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/aapl:us </td>
   <td style="text-align:left;"> 2022-01-28 05:32:51 </td>
   <td style="text-align:left;"> Apple earnings above expectations at 2.1 USD </td>
   <td style="text-align:left;"> Apple (AAPL) released earnings per share at 2.1 USD, compared to market expectations of 1.890 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-27/fidelity-joins-invesco-schwab-in-adding-china-warnings-to-funds?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-28 05:23:56 </td>
   <td style="text-align:left;"> Fidelity Joins Invesco and Schwab in Adding China Warnings to Funds </td>
   <td style="text-align:left;"> Miles Weiss                                                                                                                                                                                                                                             , Fidelity Investments joined a growing list of money managers warning of potential losses tied to some of China’s largest companies, including Alibaba Group Holding Ltd. and JD.com Inc.                                                                , The Boston-based asset manager updated prospectuses for the Strategic Advisers Fidelity Emerging Markets Fund and four exchange-traded funds this month to add a risk factor on companies structured as variable interest entities, also known as VIEs.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-01-28 05:23:13 </td>
   <td style="text-align:left;"> Brazilian Equities Rally For 3rd Session </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Bovespa jumped 1.1% to close at 112,489 on Thursday, extending gains for a third straight session to the highest since October 18th, as investors digested better-than-expected US GDP growth figures, mixed US corporate earnings, and the Fed's hawkish stance. Domestically, traders monitor the issue of the PEC of fuels, which still has no room in the 2022 Budget, as well as the movement of congressional wings to overturn presidential vetoes to the text signed. Brazilian President Jair Bolsonaro said on Tuesday that a proposed amendment to the Constitution being drafted by the government along with Congress will allow the reduction of federal and state taxes on fuel, electricity, and cooking gas. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-27/ceaseless-repricing-vortex-serves-up-more-vicious-s-p-500-swings?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-28 05:20:13 </td>
   <td style="text-align:left;"> Ceaseless Repricing Vortex Serves Up More Vicious S&amp;P 500 Swings </td>
   <td style="text-align:left;"> Lu Wang                                                                                                                                                                                                                                                                                         ,  and Peyton Forte                                                                                                                                                                                                                                                                               , Jerome Powell says the Federal Reserve will be nimble in formulating monetary policy. The stock market is running itself ragged trying to figure out where it will land.                                                                                                                        , Twice in two days, S&amp;P 500 has erased a gains of roughly 2% to close the session lower. Such a streak of big back-to-back downside reversals has occurred only once before in Bloomberg’s four decades’ worth of data: October 2008. Equally big swings rocked the market on Monday and Tuesday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-01-28 05:18:00 </td>
   <td style="text-align:left;"> Canada Stocks Close Negative </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, slipped 0.3% to close at 20,544 On Thursday after closing flat in the prior session, as the gains in the energy sector (+1.4%) were offset by losses in mining (-1.3%), tech (-2.2%), and healthcare (-2.9%) stocks. Meanwhile, the Bank of Canada and US Fed decisions on Wednesday continued to play a role in investors’ picks. Traders also digested upbeat GDP data from the world’s largest economy and Canada’s main trade partner. Domestically, average weekly earnings rose 1.9% over a month earlier in November, the sixth straight month of increases. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-27/chile-s-jumbo-hike-stokes-momentum-as-investors-turn-optimistic?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-28 05:15:22 </td>
   <td style="text-align:left;"> Chile’s Jumbo Hike Stokes Momentum as Investors Turn Optimistic </td>
   <td style="text-align:left;"> Sydney Maki                                                                                                                                                                                                                                                                                                                                                                                            , Chile is becoming a darling of emerging-market investors as the central bank’s hawkish pivot added to a string of positive developments that have been buoying some the nation’s assets.                                                                                                                                                                                                               , The outlook for the peso -- already the world’s best-performing currency this year -- got a boost from the larger-than-expected rate hike announced Wednesday, which pushed swap rates higher and improved returns for carry traders. At the same time, the sale of $4 billion in sustainable sovereign dollar bonds was well received by markets, and stocks closed at their highest in about a week.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-27/robinhood-revenue-misses-estimates-on-weaker-equities-trading?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-28 05:11:02 </td>
   <td style="text-align:left;"> Robinhood Plunges Anew After Earnings Miss, Dour Revenue Outlook </td>
   <td style="text-align:left;"> Annie Massa                                                                                                                                                                                                                                                                                                                          , One year after Robinhood Markets Inc. found itself at the center of the meme-stock tempest, the retail brokerage now finds itself with another set of challenges that could prove even more difficult to overcome.                                                                                                                   , On Thursday, the Silicon Valley upstart reported fourth-quarter revenue and losses that were worse than analysts’ estimates, and its stock, already down 69% since its July initial public offering, plunged again in late trading, as the company’s projections for the current quarter fell well short of Wall Street expectations. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/27/robinhood-shares-tumble-9percent-after-first-quarter-revenue-forecast-is-well-below-estimates.html </td>
   <td style="text-align:left;"> 2022-01-28 05:10:38 </td>
   <td style="text-align:left;"> Robinhood shares tank 15% after it loses active users, forecasts weak revenue </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                      , Stock-trading app Robinhood gave a bleak revenue forecast for the first quarter of 2022 on Thursday as its latest earnings report showed a decline in active users.                                                                                                                                                  , Shares of Robinhood tanked 15% in after hours trading.                                                                                                                                                                                                                                                               ,                                                                                                                                                                                                                                                                                                                      , The newly public brokerage anticipates first-quarter revenue of less than $340 million, down 35% compared with 2021. Wall Street's consensus estimate was for $448.2 million in revenue for Q1, according to FactSet.                                                                                                , Monthly active users fell to 17.3 million last quarter from 18.9 million in the third quarter. This number was also below estimates of 19.8 million, according to FactSet.                                                                                                                                           , Meanwhile, net cumulative funded accounts totaled 22.7 million at the end of the fourth quarter, about in-line with estimates. This is up from 22.4 million accounts in the third quarter. To be sure, Robinhood added 10 million accounts alone in 2021.                                                            , For the fourth quarter, Robinhood reported a net loss of $423 million, or a 49 cent loss per diluted share, wider than the 45 cent loss estimate collected by Refinitiv. However, Robinhood posted $363 million in revenue in the final three months of 2021, slightly above analysts expectations of $362.1 million., Robinhood is about to face its toughest comps in the first and second quarters of 2022 following its record year in 2021 from events like the GameStop short squeeze.                                                                                                                                                , Robinhood's stock is more than 86% off its most recent high since the trading app's July 2021 public debut. Shares are down more than 34% in January, bringing its market capitalization to less than $10 billion.                                                                                                   ,                                                                                                                                                                                                                                                                                                                      , Fourth-quarter transaction-based revenue was $264 million. Options trading made up $163 million, cryptocurrency trading added $48 million and equities contributed $52 million to transaction based revenue in Q4.                                                                                                   , Revenue from crypto has been declining since the second quarter of 2021. After a banner $233 million in the second quarter of 2021, crypto-based revenue was only $51 million in the third quarter. And Thursday's report shows its continuing to decline.                                                           , However, Robinhood is still investing heavily in its crypto business.                                                                                                                                                                                                                                                , Acquisition talk is in the air. Goldman thinks it knows who may be next                                                                                                                                                                                                                                              , Stanley Druckenmiller says listen to the bond market. Here's what that means                                                                                                                                                                                                                                         , Morgan Stanley, Barclays say UK stocks are looking cheap and can weather risk-off period                                                                                                                                                                                                                             , "Robinhood has set aggressive goals to start opening its crypto platform up to customers internationally in 2022. The company believes in the immense potential of the crypto economy and sees a big opportunity in serving customers across the globe," the company said in a release.                              , Robinhood's assets under custody rose to $98 billion on an annualized basis. Average revenue per user decreased by 39% to $64 year over year from $106.                                                                                                                                                              , Looking ahead to 2022, Robinhood said it will build products intended to support long-term investing, as well as products in spending and savings. Some of these products will include instant debit card deposits and withdrawals.                                                                                  , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                               , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                               , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                     , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                     , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                   , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/stocks-give-up-strong-early/story.aspx?guid={A264A85E-8D2A-4631-935D-37E74E0E91F3}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-28 05:05:29 </td>
   <td style="text-align:left;"> Stocks give up strong early gains to end lower in another volatile session - MarketWatch </td>
   <td style="text-align:left;"> Stocks ended lower Thursday, giving up strong early gains in another whipsaw trading session. The Dow Jones Industrial Average 
        DJIA,
        -0.02%
      lost around 7 points, or less than 0.1%, to close near 34,161, according to preliminary figures, after rising more than 600 points in earlier action. The S&amp;P 500 
        SPX,
        -0.54%
       fell around 23 points, or 0.5%, to close near 4,327, while the Nasdaq Composite 
        COMP,
        -1.40%
       dropped around 189 points, or 1.4%, finishing near 13,353., U.S. stock-index futures sank Wednesday night, as investors digested the possibility of multiple interest-rate hikes by the Fed this year, starting as soon as March.                                                                                                                                                                                                                                                                                                                                                                                            , William Watts is MarketWatch’s senior markets writer. Based in New York, Watts writes about stocks, bonds, currencies and commodities, including oil. He also writes about global macro issues and trading strategies. Before moving to New York, he reported for MarketWatch from Frankfurt, London and Washington, D.C. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-01-28 04:43:04 </td>
   <td style="text-align:left;"> FTSE 100 above 7550 </td>
   <td style="text-align:left;"> FTSE 100 rose above 7550 points. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/apple-earnings-highest-ever </td>
   <td style="text-align:left;"> 2022-01-28 04:25:44 </td>
   <td style="text-align:left;"> Apple hits new quarterly revenue record despite supply chain troubles </td>
   <td style="text-align:left;"> Constellation Research founder Ray Wang explains why he believes Apple will reveal it had a 'pretty good' quarter and that the company, along with news from Microsoft and Tesla, will likely help keep the floor under the market.                                                                                                                                                                   , Apple posted its highest quarterly revenue increase in the company's history on Thursday at $123.9 billion, showing an 11% year-over-year boost during last year's critical holiday season despite ongoing supply chain challenges and chip shortages.                                                                                                                                                , An Apple logo hangs above the entrance to the Apple store on 5th Avenue in the Manhattan borough of New York City, July 21, 2015. (REUTERS/Mike Segar/File Photo / Reuters Photos)                                                                                                                                                                                                                    , APPLE'S TIM COOK AND GOOGLE'S SUNDAR PICHAI WORKING CAPITOL HILL TOGETHER TO STOP BIG TECH BILL                                                                                                                                                                                                                                                                                                       , "This quarter’s record results were made possible by our most innovative lineup of products and services ever," CEO Tim Cook said in a letter to investors reporting the results.                                                                                                                                                                                                                     , "We are gratified to see the response from customers around the world at a time when staying connected has never been more important," Cook continued. "We are doing all we can to help build a better world — making progress toward our goal of becoming carbon neutral across our supply chain and products by 2030, and pushing forward with our work in education and racial equity and justice.", Apple CEO Tim Cook poses with a new MacBook Pro for Apple's Unleashed 2021 event at Apple Park in Cupertino, California, U.S., in a photograph released October 18, 2021.  (Apple Inc/Handout via REUTERS / Reuters Photos)                                                                                                                                                                           , TIM COOK ‘STALKER’: APPLE FILES FOR RESTRAINING ORDER AGAINST VIRGINIA WOMAN ACCUSED OF HARASSING CEO                                                                                                                                                                                                                                                                                                 , The Q1 2022 results showed profits of $34.63 billion, or $2.10 per share, beating Wall Street estimates of $1.90 per share. Were it not for parts shortages and supply chain woes, Apple's earnings might have been even higher.                                                                                                                                                                      , Cook had said in October that demand for Apple products was strong, but blamed supply chain issues for costing the company an estimated $6 billion in the previous quarter. It appears the firm was able to navigate through a lot of the problems during the last three months of 2021.                                                                                                              , "We saw supply constraints across most of our products," Cook told The Wall Street Journal on Thursday as the company released its Q1 2021 results. He expressed optimism that further issues would be alleviated, adding, "We’re forecasting that we will be less [constrained] in March than we were in the December quarter."                                                                      , Apple Inc. has seen its market capitalization surge to nearly $3 trillion. (Photo: Bridget Bennett for The Wall Street Journal) (The Wall Street Journal)                                                                                                                                                                                                                                             , GET FOX BUSINESS ON THE BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                              , Apple's stock price climbed more than 3.5% in after-hours trading following the release of the results.                                                                                                                                                                                                                                                                                               , In early January, the tech behemoth became the first U.S. company to hit $3 trillion in market value. Fellow titan Microsoft was valued at around $2.5 trillion at the time.                                                                                                                                                                                                                          , FOX Business' Suzanne O'Halloran contributed to this article </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/lifestyle/omicron-deals-major-blow-to-restaurant-industry </td>
   <td style="text-align:left;"> 2022-01-28 04:22:30 </td>
   <td style="text-align:left;"> Omicron deals major blow to 'struggling' restaurant industry: National Restaurant Association executive </td>
   <td style="text-align:left;"> Executive Vice President of Public Affairs at the National Restaurant Association Sean Kennedy argues the industry is currently 'struggling' to keep doors open, noting the vast majority of owners say conditions are worse now.                                                                                                                                                                                                                                                                                                                   , Executive Vice President of Public Affairs at the National Restaurant Association Sean Kennedy argued on Thursday that the industry is currently "struggling" to keep doors open, noting that the vast majority of owners say conditions are worse now compared to a few months ago.                                                                                                                                                                                                                                                                , Speaking on "Cavuto: Coast to Coast," he stressed that more financial relief is needed to help restaurant owners continue to stay afloat as the omicron variant has been dealing a major blow to the restaurant industry.                                                                                                                                                                                                                                                                                                                           , Kennedy pointed to a recent national survey completed by the National Restaurant Association, which he said noted that 76% of restaurant operators reported "that their conditions are worse now than they were just three months ago."                                                                                                                                                                                                                                                                                                             , "Programs like the Restaurant Revitalization Fund have saved, by our estimates, 900,000 jobs," he went on to say.                                                                                                                                                                                                                                                                                                                                                                                                                                   , "Congress continues to sit on the sidelines [and] has not taken care of funding that program, which could save, by our estimates, an additional 1.6 million jobs."                                                                                                                                                                                                                                                                                                                                                                                  , In a survey released by the National Restaurant Association on Monday, data highlighted the impact omicron has had so far as well as the positive impact the Restaurant Revitalization Fund had on the industry.                                                                                                                                                                                                                                                                                                                                    , NYC STEAKHOUSE OWNER SAYS HE LOST MILLIONS IN BUSINESS DUE TO CITY'S VACCINE MANDATE                                                                                                                                                                                                                                                                                                                                                                                                                                                                , The release showcasing the survey results noted that the first round of funding saved more than 900,000 jobs and helped 96% of recipients of a grant stay in business.The survey also found that nearly half of restaurant operators that did not receive grants feel it’s unlikely that they will stay in business beyond the pandemic without any financial assistance. It also found that 94% of restaurant owners that applied for a grant, but did not receive funding, said a future grant would help them to retain or hire back employees.  , The Melting Pot CEO Bob Johnston discusses how the pandemic and COVID protocols have impacted the service industry.                                                                                                                                                                                                                                                                                                                                                                                                                                 , New York restaurants are some of those that have been most impacted by the coronavirus pandemic and its associated lockdowns.                                                                                                                                                                                                                                                                                                                                                                                                                       , In a news release, the New York State Restaurant Association pointed to estimates from the National Restaurant Association that one out of every six restaurants in the country closed due to the pandemic and said that, based on estimates, that means more than 8000 restaurants in New York state, 4,500 of which are in New York City, have shut their doors for good.                                                                                                                                                                         , A bipartisan group of lawmakers has started exploring another round of coronavirus relief funding for small businesses as the surge of the highly contagious omicron variant threatens to unleash more economic havoc.                                                                                                                                                                                                                                                                                                                              , Sens. Ben Cardin, D-Md., and Roger Wicker, R-Miss., have spearheaded an effort to provide small businesses with additional federal aid, a person familiar with the matter told FOX Business earlier this month. The news was first reported by The Washington Post.                                                                                                                                                                                                                                                                                 , NYC STEAKHOUSE OWNER SLAMS VACCINE, MASK MANDATES: 'BAD NEWS FOR US'                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , The source said the duo is crafting a package based on a bill the pair introduced in August that would replenish the Restaurant Revitalization Fund, a program created by Democrats in March 2021 that gave food and beverage providers grants equal to their pandemic-related revenue loss, with a maximum of $10 million per business and $5 million per location.                                                                                                                                                                                , The proposed legislation, which failed to pass, would have allocated an additional $48 billion to the fund. The Post reported that Wicker and Cardin put together a $68 billion proposal in mid-December that includes a mix of new spending and reallocation of unused cash authorized under previous packages.                                                                                                                                                                                                                                    , The Restaurant Revitalization Fund launched May 3 and paid out approximately $29 billion to eligible applicants, which included restaurants, bars, food trucks and carts, brewpubs, tasting rooms and other food service establishments. Businesses could use the grants to cover expenses, rent and supply costs. The fund ran out of money in less than two months after providing grants to more than 100,000 businesses.                                                                                                                        , Nello owner Thomas Makkos argues New York City COVID mandates have been 'catastrophic' for restaurants.                                                                                                                                                                                                                                                                                                                                                                                                                                             , "Restaurants are a low-profit industry on a good day, and we are still loaded with debt from government-mandated shutdowns - so it has been really tough for us to come back online," Kennedy said on Thursday. "We don’t have the customer traffic that we need."                                                                                                                                                                                                                                                                                  , He went on to point out that "90,000 restaurants have closed their doors temporarily or long term" and stressed the importance of moving the legislation to replenish the Restaurant Revitalization Fund forward in order to prevent the industry, which he noted is the nation’s second-largest private sector employer, from shrinking further.                                                                                                                                                                                                   , "We need to get that legislation pushed through Congress," he stressed.                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Any spending plan faces an uphill battle in the narrowly divided Senate, where Republicans previously sank efforts to provide small businesses with additional aid over concerns about the nation's deficit. But the talks underscore growing unease on Capitol Hill over the stunning recent rise in cases driven by the highly transmissible omicron variant.                                                                                                                                                                                     , Asked earlier this month about the possibility of a relief package that targets restaurants and other small businesses, White House press secretary Jen Psaki pointed to the $1.9 trillion package that Democrats passed nearly a year ago.                                                                                                                                                                                                                                                                                                         , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , "We did a major relief package that included helping restaurants just last year," she said. "We are in constant discussions with Congress and leadership about the needs of the American people, whether they are small businesses or restaurants or people sitting in their homes as we continue to fight the pandemic, but don't have any new prediction of new pending requests or specific requests and wouldn't predict that at this moment in time."                                                                                          , Only about one-third of restaurants that applied for relief through the fund received a grant, and the Independent Restaurant Coalition, a trade group formed during the pandemic, estimates that nearly 80% of restaurants could close this winter without additional aid.                                                                                                                                                                                                                                                                         , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , FOX Business’ Megan Henney contributed to this report.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/federal-reserves-rate-hike-plans-may/story.aspx?guid={20C05575-04D4-B545-78C9-46F517FA2E91}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-28 04:14:00 </td>
   <td style="text-align:left;"> Federal Reserve's rate-hike plans may be exacerbating the risk of a U.S. economic slowdown in 2022, based on bond-market signals - MarketWatch </td>
   <td style="text-align:left;"> Just as Federal Reserve policy makers gear up for a likely series of interest rate hikes starting in March, the Treasury market is warning that there may be limits around how far policy makers can go without triggering fears of an impending recession.A day after the Fed’s policy update, the widely followed spread between 2- and 10-year Treasury yields shrank to  the narrowest level since November 2020, while the counterpart gap between 5- and 30-years flattened to a level not seen since January 2019, according to Tradeweb data as of 2 p.m. Eastern time Thursday. Parts of the government bond market also moved closer to inversion — such as the gap between 7- and 10-year Treasury rates.While the likelihood of at least five rate hikes by year-end has risen to more than 50% as of Thursday, there’s a distinction between what the market expects the Fed to do and what the market thinks the Fed can do without harming economic growth.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Yield spreads that fall below zero are typically seen as a harbinger of an economic downturn. The last time the 2s10s spread went negative was in 2019. Months later, the U.S. economy fell into a two-month downturn that lasted from February 2020 to April of that year, driven by the onset of the COVID-19 pandemic.“We’re not anywhere near a massive inversion, but to me the signal from the curve tends to be a very good indicator of where we are headed,” said Societe Generale’s Subadra Rajappa, head of U.S. rates strategy. “The flattening curve has to be a concern because it raises the question of just how much the Fed will be able to hike in order to bring down inflation, without signaling risks of a recession.”Both the 2s10s and 5s30s spreads have already fallen sharply this year, even before the Fed has delivered its first rate hike. One big factor influencing the trajectory of long-term rates, and thus the flattening of the curve, is demand for Treasurys from overseas investors and domestic asset liability managers, Rajappa said.Meanwhile, other corners of the Treasury market, such as the gap between 20-year and 30-year yields, remain inverted at a time when forecasters expect the economy to be slowing.  The median estimate of economists polled by the Wall Street Journal this month is for GDP growth to slow to 3.3% in 2022, down from more than 5% in 2021, and to continue slowing to 2.4% and 2.2% in 2023 and 2024, respectively. Economists at the American Bankers Association are also bracing for a U.S. slowdown over much of this year, while the International Monetary Fund has cut its forecast for global growth in 2022, to 4.4% from a previously expected 4.9%. Read: Hidden in the GDP report is proof that the air is already coming out of the economyFor his part, Powell told reporters on Wednesday that many factors are influencing longer-term interest rates, and that the central bank does “monitor the slope of the yield curve, but we don’t control the slope of the yield curve.” “I don’t think of it as some kind of an iron law,” he said. “But we do look at it and try to understand the implications and what it’s telling us. And it’s one of many things that we monitor.”During Powell’s prepared remarks on Wednesday, the bond market began to price in higher inflation expectations, as reflected in the 10-year TIPS breakeven rate, on the view that the Fed would be adopting  “a more measured approach” to removing accommodation than previously thought, Rajappa said. But as Powell’s comments turned decidedly more hawkish during the question-and-answer session, the market walked back, leaving expectations at roughly where they were before Wednesday, she said.On Thursday, most Treasury yields turned lower, except for the 1- and 2-year rates 
        TMUBMUSD02Y,
        1.196%,
       which rose by 15 and 12 basis points, respectively, to 0.73% and 1.19%. The 10- 
        TMUBMUSD10Y,
        1.811%
       and 30-year yields 
        TMUBMUSD30Y,
        2.097%
       each fell,  as major stock indexes were mixed.Sign up for our Market Watch Newsletters here   , The stock market tends to perform better amid rate hikes than some might guess. Here's what history shows, according to Dow Jones Market Data.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Vivien Lou Chen is a Markets Reporter for MarketWatch. You can follow her on Twitter @vivienlouchen. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/27/why-the-stock-market-hates-the-idea-of-rising-interest-rates.html </td>
   <td style="text-align:left;"> 2022-01-28 04:02:39 </td>
   <td style="text-align:left;"> Why the stock market hates the idea of rising interest rates </td>
   <td style="text-align:left;"> , The specter of rising interest rates is spooking the stock market.                                                                                                                                                                                                                                , The Federal Reserve, the U.S. central bank, is expected to increase its benchmark rate several times this year to tame stubbornly high inflation. Fed chair Jerome Powell affirmed that likelihood on Wednesday.                                                                                  , The move would increase borrowing costs from near zero — where they've been since the beginning of the Covid pandemic — for businesses and consumers.                                                                                                                                             , The forecast has caused stocks to nosedive in January.                                                                                                                                                                                                                                            , The S&amp;P 500 index is down about 9% for the year. At one point this week, the basket of U.S. stocks dipped below 10% — the first time that's happened since the initial pandemic turmoil of March 2020. The index closed down 0.2% Wednesday after Powell's remarks, erasing earlier gains.        , Why does the stock market care?                                                                                                                                                                                                                                                                   , Broadly, the reasons seem to be twofold: A slowdown of the U.S. economy and the prospect of other investments like bonds becoming more attractive relative to stocks.                                                                                                                             , When the Fed raises its benchmark interest rate, banks and lenders tend to raise borrowing costs, too. Mortgages, credit cards and other debt become pricier, reducing consumer spending and demand. Businesses also pay more to finance their operations.                                        , More from Personal Finance:What the Fed's plan to raise interest rates means for youWhy new parents may qualify for another $1,400 stimulus check3 reasons to keep your will or estate plan updated                                                                                               , Broadly, this dampens the outlook for company profits and reduces investor enthusiasm for buying their stock.                                                                                                                                                                                     , "A tightening of monetary policy will put pressure on economic activity," according to Blair duQuesnay, a certified financial planner and investment advisor at Ritholtz Wealth Management, who is based in New Orleans. "And it's by design."                                                    , The Fed's "design" is to cool off inflation. Consumer prices jumped 7% in December from a year earlier, the fastest pace since 1982.                                                                                                                                                              , But the stock market isn't reacting just to a likely rate bump; stock gyrations have as much to do with uncertainty over how fast the Fed will accelerate.                                                                                                                                        , "What the market doesn't like, is rapid changes in the monetary landscape," according to David Stubbs, the global head of cross-asset thematic strategy at J.P. Morgan Private Bank.                                                                                                              , When inflation began accelerating in early 2021, Fed officials signaled it was likely temporary, the short-term result of a hyperactive economy emerging from its pandemic hibernation.                                                                                                           , Now, their tone has shifted as inflation has lingered well above the Fed's 2% long-run target. In large part, that seems due to consumer demand for physical goods outstripping supply, as Covid continues to disrupt manufacturers.                                                              , "Since the December meeting, I would say that the inflation situation is about the same but probably slightly worse," Powell said Wednesday. "I think to the extent the situation deteriorates further, our policy will have to address that," he added.                                          , Investors worry an aggressive Fed response may slam the brakes on the economy — though Powell has sought to reassure the policy response will be "nimble."                                                                                                                                        , Anxiety over that outcome is the main reason for market jitters, according to CFP Lee Baker, founder of Apex Financial Services in Atlanta.                                                                                                                                                       , "What are the trickle-down effects if the Fed raises rates too far, too fast? If it slows down the economy, what does that do to [company] earnings? You just sort of follow that domino," Baker said. "If you're talking about earnings, you're talking about stocks."                           , (This discussion is relative to a broad basket of U.S. stocks. It's not true that all companies necessarily suffer if rates rise. Some may do better — like a bank, for example, that charges more to lend.)                                                                                      , If rates rise, investors may see more value in bonds, certificates of deposit and other assets thought to be less risky than stocks.                                                                                                                                                              , Yields in those conservative assets have been relatively paltry since the 2008 financial crisis, which led to a prolonged period of rock-bottom interest rates to spur the economy.                                                                                                               , Investors looking for returns were essentially "forced" into stocks, Baker said.                                                                                                                                                                                                                  , The value proposition may change, if bond yields and CD rates move upward in tandem with the Fed's benchmark rate.                                                                                                                                                                                , Though it seems to play the biggest role, Fed policy isn't the only thing putting investors on edge.                                                                                                                                                                                              , For one, there's the prospect of war between Ukraine and Russia. Those geopolitical tensions fuel more uncertainty — for example, how might the energy sector be impacted if fighting breaks out?                                                                                                 , The stock selloff may be a good thing, independent of what's causing it, duQuesnay said. The Federal Reserve is discussing higher interest rates because the economy and labor markets are strong; a reduction in stock prices may also tether lofty company valuations more to reality, she said., "If you take away all the outside news and information about the stock market, it's gone up double digits for three years in a row," according to duQuesnay. "Maybe it should sell off despite anything else."                                                                                    , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                            , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                            , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                  , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                  , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/natural-gas-futures-jump-more-46/story.aspx?guid={C9A14D43-EF59-4CBA-8B23-F8EB52F257C4}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-28 03:56:48 </td>
   <td style="text-align:left;"> Natural-gas futures jump by more than 46%; oil settles lower  - MarketWatch </td>
   <td style="text-align:left;"> Natural-gas prices rallied Thursday, with traders shocked by a more than 46% jump in prices at the settlement, as the front-month February futures contract expired at the end of the trading session. Natural gas for February delivery 
        NGG22,
        +37.95%
       settled at $6.265 per million British thermal units, up $1.99, or 46.5% on the New York Mercantile Exchange, according to Dow Jones Market Data - the largest one-day percentage move on record and highest finish since October. The 219 billion-cubic-foot weekly fall in U.S. supplies of the fuel reported by the Energy Information Administration Thursday leaves stockpiles more than 10% below last year's levels, Tyler Richey, co-editor at Sevens Report Research, said ahead of the Nymex settlement. Meanwhile, oil futures posted their first loss in three sessions on Thursday, easing back from the multiyear highs seen a day earlier. Traders remained focused on the Russia-Ukraine situation and the possibility of a disruption to global crude supplies. March West Texas Intermediate crude 
        CLH22,
        +0.67%
       fell 74 cents, or nearly 0.9%, to settle at $86.61 a barrel, after settling Wednesday at $87.35, the highest front-month contract finish since October 2014. , Intel Corp. weathered another tough investor reaction to its earnings report Thursday despite strong results, as the chip maker faces another challenge in addition to falling margins: A looming oversupply of PCs that promises to hit its largest business segment.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/rty:ind </td>
   <td style="text-align:left;"> 2022-01-28 03:49:54 </td>
   <td style="text-align:left;"> Russell 2000 Hits 12-month Low </td>
   <td style="text-align:left;"> US2000 decreased to a 12-month low of 1931 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/27/heres-what-to-consider-before-taking-a-pay-cut.html </td>
   <td style="text-align:left;"> 2022-01-28 03:44:28 </td>
   <td style="text-align:left;"> Most Americans say work and life balance is more important than a higher salary. How to manage if you need to take a pay cut </td>
   <td style="text-align:left;"> , The pandemic has upended millions of American lives, and for many has made them reconsider priorities around work.                                                                                                                                                                                      , That's prompted many to quit jobs amid the so-called Great Resignation. In November, a record 4.5 million workers left their jobs, according to data from the Labor Department.                                                                                                                         , There are also signs that people are open to shifting careers for jobs that better fit their new pandemic normal. About two-thirds of working adults said that work-life balance is more important to them than having a higher salary, according to KeyBank's 2022 financial mobility survey.          , The survey also found that many Americans' priorities shifted to include more time with friends and family.                                                                                                                                                                                             , "If you know a bigger paycheck is no longer your priority and spending time with family and friends is, there's probably going to be some financial ramifications," said Mitch Kime, head of consumer lending and payments at KeyBank. "That's okay."                                                   , More from Invest in You:If you are quitting a job, here are some options for health insuranceHere are the top jobs in the U.S. — and how to land themThis company just decided to give employees a 4-day workweek permanently                                                                           , Another survey of workers from Paro, which provides accounting and finance solutions for businesses, focused on those who think for a living – such as programmers, pharmacists and lawyers. The survey found the group also prioritized their work-life balance over making more money.                , Some may also consider taking a pay cut to have a better balance between work and life, or to change careers to something more meaningful.                                                                                                                                                              , "The pandemic and experiences they have had have shifted their values," said Anita Samojednik, CEO of Paro. "Right now, the salary is just not enough."                                                                                                                                                 , Of course, taking a pay cut will directly affect your finances and may not be advisable right away, according to Tania Brown, an Atlanta-based certified financial planner and founder of FinanciallyConfidentMom.com.                                                                                  , If you're considering taking a job where you will make less money, there are a few things you need to consider before you make any moves, she said.                                                                                                                                                     , The first thing is to ask yourself why you want to leave your current job. Are you burned out? Will a different job or career be more fulfilling? Are you planning to move?                                                                                                                             , Doing this ensures you don't make a rash decision you'll later regret, said Brown.                                                                                                                                                                                                                      , "Emotions have no logic, and you're trying to make a math decision based on emotion," Brown said. "It's just not going to turn out."                                                                                                                                                                    , If you're only a few months from paying off debts or hitting another financial goal, you may want to hold off.                                                                                                                                                                                          , Plus, you may realize you don't want to leave your job, but instead would like more flexibility or a change in your role. If this is the case, now is a great time to ask for a different schedule, to take on different responsibilities or introduce other flexibility into your job, Samojednik said., "There is a lot more flexibility," she said. She added that she's seen many people dip their toes into freelancing in addition to a full-time job to test the waters of a new gig or becoming their own boss.                                                                                           , But, if you discover that switching jobs is truly what you want, then you have some important math to do, Brown said.                                                                                                                                                                                   , This includes looking at your current budget and financial goals and seeing if you can still make them work on a smaller income.                                                                                                                                                                        , If you will need to trim your budget, Brown suggests living as though you've already taken the pay cut for a few months to see how it works out. It will give you a test-run of what life will be like with a smaller salary and help you decide if a pay cut is truly what you want.                   , You should also think about how making less will impact your long-term goals, Brown said. If you're saving up for a house or plan on having a baby, how will your new income change the timelines on those milestones? If it will take longer, is it worth it to you to wait?                           , If you're part of a family, you should also consult the other members in your household. That means talking with your spouse and children about what changes would take place, such as fewer trips or less money for extra activities, and deciding if it works for everyone.                           , "This has to be a family decision because your decision is impacting everyone in the household," said Brown.                                                                                                                                                                                            , SIGN UP: Money 101 is an 8-week learning course to financial freedom, delivered weekly to your inbox. For the Spanish version Dinero 101, click here.                                                                                                                                                   , CHECK OUT: The 'old convention' for saving in retirement won't work anymore, expert says: Here's how to shift your strategy with Acorns+CNBC                                                                                                                                                            , Disclosure: NBCUniversal and Comcast Ventures are investors in Acorns.                                                                                                                                                                                                                                  , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                  , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                  , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                        , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                        , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                      , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/01/27/us/oklahoma-donald-grant-execution/index.html </td>
   <td style="text-align:left;"> 2022-01-28 03:32:21 </td>
   <td style="text-align:left;"> Oklahoma death row inmate who requested firing squad executed by lethal injection - CNN </td>
   <td style="text-align:left;"> (CNN)An Oklahoma death row inmate who had requested execution by firing squad was executed by lethal injection on Thursday, according to the state Department of Corrections.                                                                                                                                                                      , The execution of Donald Grant "was carried out with zero complications" at 10:16 a.m., state Attorney General John O'Connor said in a statement.                                                                                                                                                                                                    , In October 2021 the state resumed executions by lethal injection, after a lengthy hiatus following a botched execution in 2014.                                                                                                                                                                                                                     ,                                                                                                                                                                                                                                                                                                                                                     , Grant and another death row inmate, Gilbert Postelle, had asked a federal judge to intervene and allow their executions by firing squad rather than lethal injection. The judge denied the preliminary injunction.                                                                                                                                  , Grant's lawyers appealed to the US Supreme Court for a stay, but Justice Brett Kavanaugh denied the application.                                                                                                                                                                                                                                    , Grant was sentenced to death for the 2001 murders of Brenda McElyea and Felecia Suzette Smith, according to court documents filed to the Supreme Court by the Oklahoma attorney general.                                                                                                                                                            , "Justice is now served for Brenda McElyea, Felecia Suzette Smith, and the people of Oklahoma," the attorney general said in a statement.                                                                                                                                                                                                            , Postelle is scheduled to be executed on February 17.                                                                                                                                                                                                                                                                                                , In their initial petition to the court, lawyers for the two inmates had sought an injunction to stop Oklahoma from using lethal injection to administer the death penalty. Attorneys for the inmates had asked for the executions to be delayed pending a late February trial on the constitutionality of the lethal injection protocol.            , Testimony submitted by the plaintiffs in court filings from a "board-certified anesthesiologist and a board-certified pain medicine specialist" alleged that execution by firing squad -- not Oklahoma's process of lethal injection -- is appropriate because "firing squad will reliably cause a death that will be quick and virtually painless.", On November 30, 2021, Oklahoma's Pardon and Parole Board voted 4-1 against recommending clemency for Grant. CNN affiliate KOCO reported that during the hearing, Grant's lawyers argued that although their client admitted to a 2001 double murder, he shouldn't be executed because he "is severely mentally ill."                                , CNN's Paul Murphy and Ray Sanchez contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/gold-futures-settle-below-1800/story.aspx?guid={AC94A514-DF6A-415F-856E-F60B88DC86C3}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-28 02:44:18 </td>
   <td style="text-align:left;"> Gold futures settle below $1,800 for the first time in nearly 3 weeks - MarketWatch </td>
   <td style="text-align:left;"> Gold prices fell sharply on Thursday to settle below the key $1,800 mark for the first time in nearly three weeks, pressured by strength in the U.S. dollar which followed indications from the Federal Reserve that it plans to raise interest rates as soon as March. February gold 
        GCG22,
        +0.19%
       lost $36.60, or 2%, to settle at $1,793.10 an ounce. That was the first finish below $1,800 since Jan. 10 and lowest settlement since Jan. 6, FactSet data show. April gold 
        GCJ22,
        +0.19%,
       which is also among the most active, settled at $1,795, down $37, or 2%., Apple Inc. reported record overall and iPhone holiday sales as well as its best revenue ever in a calendar year Thursday, as the tech giant's quarterly earnings topped $30 billion for the first time.                                                                                                                                                                                                                                                                                                                                                                                                                      , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/jetblue-ceo-omicrons-worst-behind/story.aspx?guid={5C487CA0-72D5-4A09-BD23-49810896CBDA}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-28 02:29:52 </td>
   <td style="text-align:left;"> JetBlue CEO: Omicron's 'worst is behind us' - MarketWatch </td>
   <td style="text-align:left;"> JetBlue Airways Corp. is "confident the worst (of the omicron's wave) is behind us," as evidenced by recent case-count trends in New York City "plummeting," Chief Executive Robin Hayes said in a call with analysts following the airline's fourth-quarter results. "We believe demand is poised to reaccelerate through the quarter into a robust spring and peak summer travel season, similar to the setup around this time last year," Hayes said, according to a FactSet transcript of the call. "And we are already seeing demand rebound strongly, with net revenue builds up roughly 30% compared to the first week of January." JetBlue earlier Thursday reported a fourth-quarter loss that was narrower than expected and revenue above forecasts. The stock was the sole major U.S. airline stock to trade higher on Thursday amid broader market weakness. JetBlue shares have lost 6% in the past 12 months, contrasting with gains of around 15% for the S&amp;P 500 index. 
        SPX,
        -0.54%
       and underperforming in relation to the U.S. Global JETS ETF 
        JETS,
        -1.45%,
       which lost about 5%  in the same period., Here's what the chief executive of ARK Invest had to say.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/money/child-tax-credit-irs-incorrect-tax-form </td>
   <td style="text-align:left;"> 2022-01-28 02:26:18 </td>
   <td style="text-align:left;"> Child tax credit 2022: IRS warns some families may have received incorrect letter </td>
   <td style="text-align:left;"> IRS to require use of facial recognition software to access government documents. FOX Business' Gerri Willis with more.                                                                                                                                                                                                                                                                                                                                                                                , A crucial letter that will help child tax credit recipients figure out how much money the IRS still owes them may contain incorrect information.                                                                                                                                                                                                                                                                                                                                                       , The IRS said this week that it is investigating reports from some taxpayers that Letter 6419 includes the wrong dollar amount that parents received from the boosted child tax credit, which was paid out in monthly installments from July to December.                                                                                                                                                                                                                                               , IRS DELIVERS FINAL CHILD TAX CREDIT PAYMENT OF 2021 TO 36M FAMILIES                                                                                                                                                                                                                                                                                                                                                                                                                                    , The wrong information could have serious implications for some households' finances: Because at least half of the enhanced credit will be paid out as a lump sum when parents receive their 2021 tax return, recipients need to keep the letter and use it to accurately reconcile the credit they already received when filing their taxes this year. The information is pertinent to determining how much more money families receive from the credit when they fill out Schedule 8812 and Form 1040., The Internal Revenue Service (IRS) headquarters building in Washington (AP Photo/J. David Ake/File / AP Newsroom)                                                                                                                                                                                                                                                                                                                                                                                      , IRS Commissioner Chuck Rettig told reporters during a call on Monday that the scope of the error is likely limited, and maintained that he was "highly confident that it is nowhere near millions or hundreds of thousands." Rettig said the IRS will release more information on the matter once it becomes available.                                                                                                                                                                                , It's possible the people who received the erroneous letters could be a small group of taxpayers who recently moved or changed bank accounts in December. Ken Corbin, the IRS chief taxpayer experience officer, said Monday the child tax credit checks may have been undeliverable in those cases, or bounced from bank accounts.                                                                                                                                                                     , "Then the letters may not reflect what the taxpayer actually received," Corbin said.                                                                                                                                                                                                                                                                                                                                                                                                                   , People who received the monthly payments can also check the amount of their payments by using the CTC Update Portal.                                                                                                                                                                                                                                                                                                                                                                                   , If families opted out of the monthly payments, they can claim the full amount of the child tax credit on their 2021 federal tax return. This also applies to families who don't normally need to file a tax return.                                                                                                                                                                                                                                                                                    , IRS Commissioner Charles Rettig testifies on his agency's budget before the House Appropriations Subcommittee on Capitol Hill April 9, 2019. (Reuters/Aaron P. Bernstein  / Reuters Photos)                                                                                                                                                                                                                                                                                                            , The IRS is already warning taxpayers of a potentially challenging tax season and has urged individuals to file their tax returns electronically in order to receive the refund within 21 days as the agency wades through a deluge of 6 million unprocessed paper returns.                                                                                                                                                                                                                             , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Democrats temporarily expanded the child tax credit in early 2021 as part of a sweeping coronavirus relief package, but it expired at the end of the year. Under the expansion, low- and middle-income parents could receive up to $3,000 for every child ages 6 to 17 and $3,600 for every child under age 6. The payments were income-based and began to phase out for individuals earning more than $75,000 and married couples earning more than $150,000.                                         , The first half was delivered in monthly payments from July to December with $300 for children under the age of 6 and $250 for those ages 6 to 17, but the last check was mailed out last month. The second half will be delivered as a lump sum when families file their 2021 tax returns in the spring. The IRS said that 36 million families received the payments each month, or about 60 million children.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-01-28 02:23:00 </td>
   <td style="text-align:left;"> Wall Street Closes Negative In Another Volatile Session </td>
   <td style="text-align:left;"> US stocks gave up gains to turn negative on Thursday as traders balance better-than-expected economic data and prospects of rates hikes while monitoring corporate earnings. The US economy expanded a much better-than-expected 6.9% in Q4 while the Fed signaled yesterday it may tighten monetary policy faster than anticipated, with some market participants now betting on 5 rate hikes this year. The Dow Jones was little changed after adding more than 600 points, the S&amp;P fell 0.5%, and the tech-heavy Nasdaq Composite dropped 1.4% after being more than 1.6% higher at session highs. On the corporate front, Tesla plunged almost 10% after the carmaker warned supply chain issues could persist throughout 2022 while Intel was down 7% on the mixed outlook for the first quarter. Also, earnings from McDonald's missed estimates and the company's stocks slipped 0.4%. Meanwhile, Netflix soared 8% on news that Pershing's Bill Ackman bought 3.1 million shares. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/sec-fidelity-bitcoin-etf-crypto </td>
   <td style="text-align:left;"> 2022-01-28 02:19:07 </td>
   <td style="text-align:left;"> SEC rules on Fidelity's Bitcoin ETF </td>
   <td style="text-align:left;"> Bitcoin Foundation Chairman Brock Pierce argues crypto's correlation with the stock market is 'very real,' which he says indicates that institutional capital in the U.S. is 'in lockstep.'                                                                                                                                                                                                                                                , The Securities and Exchange Commission nixed another Bitcoin exchange-traded fund (ETF) application.                                                                                                                                                                                                                                                                                                                                       , The commission said mutual fund giant Fidelity’s application did not satisfy regulators because it failed to show it can protect investors from fraud, as detailed in the SEC ruling. In November, the commission rejected VanEck’s Bitcoin ETF for similar reasons.                                                                                                                                                                       , LIVE: CRYPTOCURRENCY PRICE DATA                                                                                                                                                                                                                                                                                                                                                                                                            , In a statement to FOX Business, Fidelity said:                                                                                                                                                                                                                                                                                                                                                                                             , "While we are disappointed by the outcome of the SEC’s deliberations resulting in today’s disapproval order, we reaffirm our belief in market readiness for a physical bitcoin exchange traded product and look forward to continued constructive dialogue with the SEC.                                                                                                                                                                   , "Fidelity’s comprehensive research on bitcoin trading in global spot and futures markets shows the maturation of these markets and the price discovery leadership of the regulated CME Bitcoin futures market, which satisfies the SEC’s standards for listing approval as applied to many existing spot-backed exchange products currently available for trading, including gold, silver, platinum, palladium and copper," the firm said. , The SEC has given the green light to ETFs that offer exposure to Bitcoin but are not pure plays, including ProShares Bitcoin Strategy ETF, WisdomTree’s Enhanced Commodity Strategy Fund and the Bitwise Crypto Industry Innovators ETF.                                                                                                                                                                                                   , Bitcoin has declined over 20% this year, impacted in part by the volatility in U.S. stocks, as investors rotate out and around riskier assets.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-01-28 02:11:20 </td>
   <td style="text-align:left;"> WTI Crude Snaps 2-Day Rally </td>
   <td style="text-align:left;"> WTI crude futures fell around 0.5% to below $87 per barrel, as expectations that Fed will tighten soon outweighed concerns about tight worldwide supply. During its last meeting, the Fed signaled a rate hike in March as expected, while suggesting more frequent and larger interest rate increases could happen this year. Chairman Powell also said that inflation could go even higher and there's a risk it will not decline to pre-pandemic levels any time soon. Meanwhile, concerns over tight supply and energy disruptions if Russia invades Ukraine linger. Also, recent threats to the United Arab Emirates from Yemen’s Houthi movement have added to jitters in the oil market. Still, OPEC+ is expected to ratify another modest production increase of 400,000 bpd next week although the cartel has been struggling to accomplish with the output rise. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/wheat </td>
   <td style="text-align:left;"> 2022-01-28 02:05:47 </td>
   <td style="text-align:left;"> Wheat Futures Fall from 8-Week High </td>
   <td style="text-align:left;"> Chicago wheat futures traded at $7.8 per bushel, falling from the near two-month high of $8.3 touched on January 25th, amid eased fears of supply disruptions and expectations of lower demand. Kremlin spokesman Dmitry Peskov signaled that Moscow was not closing the door on diplomacy with the United States regarding security arrangements with NATO in Europe, significantly lowering traders’ concerns that wheat trade in Black Sea ports could be halted. Up to January 24th, Ukraine has been running a strong export campaign in the 2021/22 marketing year, 29% higher than the previous year, while Russia is the world’s largest exporter. In the meantime, Algeria announced it will reduce its grain imports by 25-26% in the current marketing year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/chevron-stock-track-close-record/story.aspx?guid={4554B64A-5F3E-46AF-849C-041D15C25C13}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-28 02:03:24 </td>
   <td style="text-align:left;"> Chevron stock on track to close at record - MarketWatch </td>
   <td style="text-align:left;"> Shares of Chevron Corp. 
        CVX,
        +2.02%
       on Thursday were poised to close at a record ahead of the company's quarterly results on Friday. The stock extended its winning streak for a fourth session, up more than 7% over that period. Chevron is up 16% in January, contrasting with losses of more than 8% for the S&amp;P 500 index 
        SPX,
        -0.54%
       and 6% for the Dow Jones Industrial Average 
        DJIA,
        -0.02%.
       Chevron is the sole energy stock on the Dow after Exxon Mobil Corp. 
        XOM,
        +1.28%
       was removed from the index in 2020 to make room for Salesforce Inc. 
        CRM,
        +0.82%.
       The integrated energy giant is scheduled to report fourth-quarter results before the bell Friday, with analysts polled by FactSet calling for adjusted earnings of $3.14 a share on sales of $45 billion.   , Some Canadian retailers are now requiring proof of vaccination due to local regulations, resulting in some critics calling to boycott Walmart in response                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/zambia/inflation-cpi </td>
   <td style="text-align:left;"> 2022-01-28 01:33:11 </td>
   <td style="text-align:left;"> Zambia Inflation Rate Slows for 6th Month </td>
   <td style="text-align:left;"> The annual inflation rate in Zambia eased for a sixth consecutive month to 15.1 percent in January of 2022 from 16.4 percent in the previous month. That was the lowest rate since March 2020, due to a slowdown in prices of food (16.9 percent vs 19.9 percent in December) and despite a further depreciation of the kwacha. On the other hand, the inflation rate for non-food accelerated (12.7 percent vs 12.1 percent), amid increases in pump and transport prices. On a monthly basis, consumer prices were up 2.6 percent, the most in a year, after increasing 0.6 percent in December. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-01-28 01:27:19 </td>
   <td style="text-align:left;"> South African Stocks End Lower </td>
   <td style="text-align:left;"> The FTSE/JSE All Share Index closed 0.4% down at 73,504 on Thursday, led by tech companies and gold stocks after the South African Reserve Bank decided to lift its repo rate by 25bps to 4% and suggested it would increase rates gradually in the future.
At the same time, US Federal Reserve Chairman Jerome Powell signaled it was ready to raise interest rate as early as March and warned about the potential for even more inflation going forward. Meanwhile, authorities and the South African government are expected to discuss further adjustments to lockdown restrictions, as the country continues to see a drop in Covid-19 cases. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/sweden/currency </td>
   <td style="text-align:left;"> 2022-01-28 01:03:49 </td>
   <td style="text-align:left;"> Swedish Krona Hits 18-month Low </td>
   <td style="text-align:left;"> USDSEK increased to a 18-month high of 9.3843 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-01-28 00:59:00 </td>
   <td style="text-align:left;"> European Shares Close Higher Thursday </td>
   <td style="text-align:left;"> Equity markets in Europe closed higher at the end of a volatile session Thursday, with Frankfurt's DAX 30 booking a 0.2% gain and other major bourses rising between 0.4% and 1.1%, mostly on the back of an upbeat earnings season. Deutsche Bank climbed more than 4% after making its biggest profit since 2011 last year, defying expectations for a loss in the fourth quarter, while French-Italian chipmaker STMicroelectronics gained 2% after reporting better-than-expected earnings and announcing plans to double its investments this year. On the other hand, German business software group SAP fell 6.7% after saying it has agreed to buy a majority stake in privately held US fintech firm Taulia. In other corporate news, UniCredit has signed an agreement with unions for 1,200 voluntary job cuts to be partly offset by 725 new hires. Elsewhere, investors digested US Federal Reserve chairman Powell's remarks that suggested there will be a sustained policy tightening this year to combat inflation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/currency </td>
   <td style="text-align:left;"> 2022-01-28 00:55:24 </td>
   <td style="text-align:left;"> New Zealand Dollar Hits 15-month Low </td>
   <td style="text-align:left;"> NZDUSD decreased to a 15-month low of 0.65889 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/currency </td>
   <td style="text-align:left;"> 2022-01-28 00:55:14 </td>
   <td style="text-align:left;"> Australian Dollar Hits 7-week Low </td>
   <td style="text-align:left;"> AUDUSD decreased to a 7-week low of 0.70435 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/27/the-fund-that-made-700-million-on-gamestop-knew-it-was-time-to-sell-after-an-elon-musk-tweet.html </td>
   <td style="text-align:left;"> 2022-01-28 00:48:10 </td>
   <td style="text-align:left;"> The fund that made $700 million on GameStop knew it was time to sell after an Elon Musk tweet </td>
   <td style="text-align:left;"> , One hedge fund got the GameStop trade just about perfectly right last year — buying it under $10 and selling when the meme stock peaked.                                                                                                                                                                                                                                                      , The sell signal it used? An Elon Musk tweet.                                                                                                                                                                                                                                                                                                                                                  , That's how 2021's top-performing hedge fund, Senvest Management, was able to notch $700 million in profit from GameStop and bring its annual return to more than 85%. The trade was the firm's single best in its 25 years in existence.                                                                                                                                                      , "His piling on with that tweet for us was … we all looked at each other, and thought how do you top that?" Richard Mashaal, Senvest Management's founder, CEO and co-CIO, said in an interview. "And so for that, for us, that signified peak momentum and we proceeded to exit the rest of our position."                                                                                    , The Tesla CEO tweeted "Gamestonk!!" on Jan. 26, 2021, after the bell. The next day, GameStop reached its closing top of $347.51 apiece, when Senvest dumped its bet.                                                                                                                                                                                                                          , The meme stock saga started just days into 2021 when retail traders teamed up on Reddit's WallStreetBets forum, aiming to bid up GameStop's shares, which were heavily shorted by hedge funds. The retail buying triggered massive short covering among hedge funds that fueled the rally even further.                                                                                       , Mashaal decided to buy shares of GameStop in September 2020 amid a slew of analyst sell ratings and unprecedentedly high short interest.                                                                                                                                                                                                                                                      , "It's a classic contrarian play for us," Mashaal said. "Wall Street doesn't issue very many sell recommendations and GameStop had plenty of those and very few, if not, no, buy recommendations. And then, of course, the short interest, which was over 100% of the shares outstanding. ... So both of those would be pretty glaring indicators that this was a stock that was out of favor.", Senvest is indeed an anomaly in the hedge fund industry where plenty of players got burned by the unprecedented short squeeze.                                                                                                                                                                                                                                                                , Melvin Capital was one of the biggest losers amid the meme stock mania. Its steep losses once prompted Citadel and Point72 to infuse close to $3 billion into Gabe Plotkin's hedge fund to shore up its finances.  Melvin suffered a 39% loss in 2021 after the GameStop short squeeze.                                                                                                       , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                        , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                        , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                              , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                              , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                            , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-01-28 00:48:00 </td>
   <td style="text-align:left;"> Italian Stocks Extend Gains on Thursday </td>
   <td style="text-align:left;"> The FTSE MIB Index closed 1% higher at 26,882 on Thursday, extending last session’s 2.3% gain, amid better than expected growth data from the United States and strong corporate earnings, as investors digested the Federal Reserve’s hawkish forward guidance. The US economy expended 6.9% annually in the fourth quarter, surpassing expectations of 5.5%, while the Fed signaled an interest rate hike in March. On the corporate front, STMicroelectronics gained 1.8% after increasing its net sales expectations to USD 14.8-15.3 billion during 2022, citing projections of higher demand and USD 3.4-3.6 billion in investments to grow capacity. Meanwhile, UniCredit gained 0.9% after signing an agreement with unions for 1,200 voluntary job cuts to be offset by 725 new hires. On the political front, Italian lawmakers expect to elect a new head of state in tomorrow’s 5th round of elections, after today’s vote was dominated by blank votes while parties discuss potential candidates. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/27/the-manager-of-2021s-top-performing-hedge-fund-on-his-winning-gamestop-trade-and-lessons-from-it.html </td>
   <td style="text-align:left;"> 2022-01-28 00:46:55 </td>
   <td style="text-align:left;"> The manager of 2021's top-performing hedge fund on his winning GameStop trade and lessons from it </td>
   <td style="text-align:left;"> , (Click here to subscribe to the new Delivering Alpha newsletter.)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , On this day last year, investors watched in amazement as GameStop shares surged to a record high of $347.51. The stock had skyrocketed amid a trading frenzy brought on by retail investors swapping stock tips — and related memes — on social media.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Professional investors also got in on the action but not all of them were on the short side of the trade. GameStop became Senvest Management's single best trade of all time, notching $700 million in profit for the firm. Those gains contributed to Senvest's more than 85% returns last year, making it the top performing hedge fund of 2021.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Senvest Founder &amp; CEO Richard Mashaal sat down with CNBC's Delivering Alpha newsletter to discuss how he navigated his firm's position in GameStop and shared lessons he learned along the way.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , (The below has been edited for length and clarity. See above for full video.)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Leslie Picker: You had been invested in GameStop for months prior to the frenzy that we saw in January 2021. Did you know what would happen?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Richard Mashaal: Surely we didn't know what would happen but you know, we did get in in September. So that was September [2020], so well before the stock caught fire, and it's a classic contrarian play for us. There's one word that's synonymous with Senvest: it's contrarian. That's what we look for — things that are really out of favor that have the potential to come back into favor. And we saw that kind of setup there.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Picker: You were looking at the short interest as well, which I think was similar to some of the back and forth that we saw over the Reddit forums with the retail investors. How do you kind of look at those things when making a decision to invest in a company that has been out of favor? And kind of figuring out what catalysts could make it return to favor?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Mashaal: There's a couple of really easy indicators. So how many sells and buy recommendations. Wall Street doesn't issue very many sell recommendations and GameStop had plenty of those and very few, if not, no, buy recommendations. So that's a starting point. And then, of course, the short interest, which was over 100% of the shares outstanding, which is certainly the first time in my career — our fund's going on 25 years so it's quite a long time — that I've ever seen anything like that. So both of those would be pretty glaring indicators that this was a stock that was out of favor. Actually the high short interest concerned us a little bit, in a way, because that also meant it was a battleground stock and we don't usually like to get involved in a battleground stock and, boy, this really turned out to be a big battle.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , So that's the negative side of it, but the positive side is, we saw management who had been there for over a year come in and do a hell of a lot of cost cutting, really reacted to the inability to operate their stores normally because of the pandemic and really push their foot to the pedal on e-commerce. So we saw some really good things happening there in terms of e-commerce, in terms of cost cutting, and just in general, repairing the balance sheet. They had debt, so really trying to raise cash. And so that sort of convinced us that the company had breathing room. And then another positive was the new console cycle. We were at the beginning of a new Xbox and Sony PlayStation console cycle. Those were going to be introduced in the November timeframe, so we were in September, so we thought that could be a driver of positive results, and with a higher revenue, lower costs, that would really have a positive effect on profitability.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , And then, as well, you had an activist in the wings. And this was no regular activist, this was Ryan Cohen, Ryan Cohen had tremendous success founding Chewy, a pet food e-commerce company. And he did this in the face of severe competition from Amazon. So there was the thinking that this activist got involved in the management or on the board of GameStop, that he could then affect real positive change and help a transformation story.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Picker: So Ryan Cohen takes a board seat, he gets several others onto that board, and then the stock, from there, really kind of started to go haywire. What was that like for you? Take us into  the offices of Senvest during that time period and the calculus of whether to hold or whether to sell when the stock started skyrocketing.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Mashaal: These things are certainly nerve wracking when they start happening and sort of start having a life of their own. I've always been aware of message boards and chatter about stocks, retail chatter about stocks, in general, obviously, never saw anything like this before, this is clearly unprecedented. So we definitely felt that once Ryan got on the board, that was a real catalyst for further upside. While we have short term and long term targets for stocks, with usually the short term being much, much lower, and really based on what could happen in the near term in terms of new sales of consoles, and the effect on their P&amp;L, we felt that the long term and the transformation could lead to a much higher stock price. Now, when you're talking about a transformation story, I mean, any company can say they're going to have a transformation story, you need credibility. And that's what Ryan Cohen brought to the table. He brought credibility, he had done it before. And I think that's why the retail crowd and others really jumped on it.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Picker: But you didn't hold on, you did decide to sell throughout the frenzy. What were some of the key indicators to you that made you say, "Okay, it's time to take our gains and walk away from here."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Mashaal: When we saw what was going on, and it really was only the last week or two, we saw what was really recognized and fully appreciated, what was going on on Reddit and Wall Street Bets. We recognized it as a mania and once you recognize something as a mania, you sort of put aside the fundamental analysis you've done with spreadsheets about what the earnings possibilities are, what multiples should get. You recognize a mania and then you start to say, "Okay, well how do manias work?" Manias go extreme peak then peter out at some point and so what are we looking for? We're looking for peak momentum. And that was sort of the framework we were looking at how we were going to sell the stock.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , We had different indicators. One of them was, you had a Chamath tweet, and that was an indicator that this thing could even go higher now that fellows, like, at the time, Chamath was the king of SPACs and SPACs are hot and he was speaking out. So clearly, people listened to him. And, obviously we felt it culminated with the Elon Musk tweet, that I believe came out on that Tuesday afternoon, where he just tweeted one word: [Gamestonk!!]. And you know, clearly Elon Musk is a person that people listen to, particularly retail investors, And he's someone who has done a transformation himself. He's also someone who happens to not have a very favorable view of short sellers. So his piling on with that tweet for us was, we all looked at each other and said, "How do you top that?" in terms of, what else is going to happen from a momentum point of view. And so for us that signified peak momentum and we proceeded to exit the rest of our position.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Picker: From a portfolio construction standpoint, I'm curious where your head is at with regard to short selling. Obviously, kind of bringing things back full circle to GameStop. There was the short squeeze element to it, which I know the SEC said wasn't as much of a part of the momentum upward as I think a lot of people made it out to be, but still a component of it. Are you currently hedging your portfolio with individual stocks indexes? What's your thoughts on the state of short selling right now?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Mashaal: Obviously, we are very attuned to short interest and those stocks that are heavily barred and try and stay away from those. We've kept our short positions in general smaller unless they're larger, more liquid stocks that we've got something on the long side of gains. So really, short squeezes have always been a risk and certainly they were a much bigger risk last year. But I think that this will be a good year for stock pickers to really differentiate themselves both on the long and short side. And again the indexes are still pretty close to the highs, even though they've had a bit of a correction here. So I think that does present opportunities to short some stocks that are overvalued, that perhaps won't meet lofty expectations. And at the same time, there are some really beaten down stocks trading at their 52 week lows and we're looking at those.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Picker: Lastly, are there any lessons that you learned from what happened with GameStop that you're now applying to your portfolio? I know you've been in the business for 25 years or so. But obviously, what we saw last year and how it impacted Senvest was remarkable. Is there anything that you kind of think back over the last year that you can kind of take away from that experience?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Mashaal: I think it's important to pay attention to the zeitgeist, of the moment, what's going on in the moment, and that can have an extremely powerful effect, as it did with GameStop. And narratives. We're fundamental investors and contrarian value investors, all those tags apply to us. But it's important to listen, to understand the narratives and what narratives are working in the market or not. And certainly for the last several years, the narratives of growth stocks and SaaS stocks, that was big, and you really couldn't fight that. Now those stocks have taken a bit of a tumble. So many of them are great companies, it's just a question of valuation. So really to listen to what's going on, and really, that's talking to people younger than me. So that's really, to pay attention and some of that can come by reading the message boards and seeing what the retail traders are saying. And it's great to see the [retail] traders come back. When I started my career, it was a lot about retail traders and then for the last several years you really didn't hear much about it, so it's good to see. I mean, definitely, the financial markets and the stock market, sometimes people treat it like a game. It's not a game. There's real money there and you make money and lose money. But you also do learn, you learn and I do believe in learning by doing. So, a lot of these retail investors are doing exactly that. And then you've got the apps like Robinhood, which really make it accessible so that's here to stay, I think. And whether it's stocks or crypto, young retail investors are very engaged., Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-01-28 00:46:10 </td>
   <td style="text-align:left;"> UK Stocks Rally For 3rd Session </td>
   <td style="text-align:left;"> The FTSE 100 jumped 1.1% to close at 7,550 on Thursday, in line with its European counterparts, and extending gains for 3rd straight session, with the help of weaker pound sterling and a rally in the banking sector more than offsetting jitters over the US Fed hawkish turn. Standard Chartered (+5.1%), HSBC (+3.4%), Natwest Group (+2.1%), and Barclays (+1.1%) rallied on the back of higher government bond yields as traders bet on more rate hikes by the Bank of England after the Federal Reserve signaled it would raise interest rates in March. On the earnings front, Easyjet reported total losses after tax of £858M in FY2021, compared with a £1,079M loss in FY2020. The low-cost airline said it will ramp up capacity to two-thirds of pre-pandemic levels to absorb resurging bookings as the Omicron impact fades. Meanwhile, beverages manufacturer Diageo saw 1H FY2022 profits climb to £1,965M from £1,580M in the same period of FY2021. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-01-28 00:46:00 </td>
   <td style="text-align:left;"> French Shares Erase Losses </td>
   <td style="text-align:left;"> The CAC 40 Index erased early losses to close 0.6% higher at 7,024 on Thursday, amid better than expected growth data from the United States and strong corporate results. The US economy expended 6.9% annually in the fourth quarter, surpassing expectations of 5.5%. In the meantime, investors digested the Fed’s signal of higher interest rates in March, with the possibility rate hikes in every Fed meeting of 2022. On the corporate front, STMicroelectronics gained 1.8% after increasing its net sales expectations to USD 14.8–15.3 billion during 2022, citing projections of higher demand and USD 3.4-3.6 billion in investments to grow capacity. Total Energies (1.4%) and Engie (2.5%) also booked gains. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/hca:us </td>
   <td style="text-align:left;"> 2022-01-28 00:41:04 </td>
   <td style="text-align:left;"> HCA earnings below expectations at 4.42 USD </td>
   <td style="text-align:left;"> HCA (HCA) released earnings per share at 4.42 USD, compared to market expectations of 4.54 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ma:us </td>
   <td style="text-align:left;"> 2022-01-28 00:40:58 </td>
   <td style="text-align:left;"> Mastercard earnings above expectations at 2.35 USD </td>
   <td style="text-align:left;"> Mastercard (MA) released earnings per share at 2.35 USD, compared to market expectations of 2.21 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/rok:us </td>
   <td style="text-align:left;"> 2022-01-28 00:39:53 </td>
   <td style="text-align:left;"> Rockwell Automation earnings above expectations at 2.14 USD </td>
   <td style="text-align:left;"> Rockwell Automation (ROK) released earnings per share at 2.14 USD, compared to market expectations of 1.93 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/trow:us </td>
   <td style="text-align:left;"> 2022-01-28 00:39:47 </td>
   <td style="text-align:left;"> T. Rowe Price earnings above expectations at 3.17 USD </td>
   <td style="text-align:left;"> T. Rowe Price (TROW) released earnings per share at 3.17 USD, compared to market expectations of 3.10 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mmc:us </td>
   <td style="text-align:left;"> 2022-01-28 00:39:37 </td>
   <td style="text-align:left;"> Marsh &amp; McLennan Companies earnings above expectations at 1.36 USD </td>
   <td style="text-align:left;"> Marsh &amp; McLennan Companies (MMC) released earnings per share at 1.36 USD, compared to market expectations of 1.34 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mexico/balance-of-trade </td>
   <td style="text-align:left;"> 2022-01-28 00:30:39 </td>
   <td style="text-align:left;"> Mexico December Trade Surplus Below Forecasts </td>
   <td style="text-align:left;"> Mexico’s trade surplus shrank to USD 0.59 billion in December of 2021 after a surplus of USD 6.2 billion in the corresponding month of the previous year, smaller than market expectations of USD 1.1 billion trade surplus. Exports rose 10.8 percent to USD 47.7 billion , boosted by a 41.6 percent increase in oil exports to USD 2.8 billion and a 9.3 percent rise in non-oil exports to USD 44.8 billion. Imports increased by 27.7 percent to USD 47.1 billion, boosted by purchases of oil (64.8 percent), consumer goods (32.5 percent), and intermediate goods (27.7 percent). In 2021, Mexico recorded a USD 11.5 billion deficit as imports surged 32.1 percent to USD 505.7 billion and exports rose 18.5 percent to USD 494.2 billion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/georgia-republicans-democrats-challenge-gov-kemp-strong-state-economy </td>
   <td style="text-align:left;"> 2022-01-28 00:25:21 </td>
   <td style="text-align:left;"> Georgia Republicans, Democrats lining up to challenge Gov. Kemp and his ‘strong’ state economy </td>
   <td style="text-align:left;"> Rep. Barry Loudermilk, R-Ga., argues incumbent Gov. Brian Kemp is a ‘strong’ governor who has a slight edge in the polls.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , A potentially serious primary showdown is mounting as Georgia’s gubernatorial race heats up.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , While Georgia Governor Brian Kemp looks to use the state’s economic metrics as a campaign advantage, poll numbers for Trump-endorsed former Sen. David Perdue and Democrat Stacey Abrams just trail the incumbent.                                                                                                                                                                                                                                                                                                                                                                                                                      , A Quinnipiac University survey released Wednesday indicated Kemp held a single-digit lead over his main challenger in the Republican primaries and predicted the general election votes between Kemp and Abrams to be "almost evenly split."                                                                                                                                                                                                                                                                                                                                                                                            , "The fact that Georgia has a really strong economy, that it has a budget surplus, one would expect that Gov. Kemp could sail towards renomination without a challenge," Emory University political science professor Andra Gillespie told FOX Business’ Connell McShane.                                                                                                                                                                                                                                                                                                                                                                , PRO-HERSCHEL WALKER PAC HITS WARNOCK OVER GAS PRICES, INFLATION IN BILLBOARD ADS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , "I wouldn't expect high-quality challengers like David Perdue to enter a race against an incumbent," Gillespie continued.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , In addition to strong real estate, consumer and business spending data in Georgia, Kemp promised to use the state’s budget surplus to pay teachers more and give taxpayers a refund in a legislative preview earlier this month.                                                                                                                                                                                                                                                                                                                                                                                                        , Former Sen. David Perdue, R-Ga., left, and Senate Minority Leader Mitch McConnell, R-Ky., walk through the Ohio Clock Corridor in the Capitol. (Bill Clark/CQ-Roll Call, Inc via Getty Images)                                                                                                                                                                                                                                                                                                                                                                                                                                          , "Kemp has done an exceptional job in leading our state," Rep. Barry Loudermilk, R-Ga., told Stuart Varney on Thursday. "I mean, every economic factor is high."                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Agreeing with the recent polling data, Loudermilk believes Gov. Kemp has the slight edge over both Perdue and Abrams.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , "I had endorsed Brian Kemp as the incumbent governor many, many months ago, and he hasn't given me a reason to pull that endorsement," Loudermilk said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , FOX Business' Connell McShane reports from Atlanta, Georgia, where candidates are looking to challenge incumbent Gov. Brian Kemp and the state economy's budget surplus.                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Four years ago, with the support of Trump, Kemp narrowly defeated Democrat Stacey Abrams to win the governorship. But Kemp earned Trump’s ire starting in late 2020, after he certified now President Biden’s narrow victory in Georgia in the presidential election, following two recounts of the vote. Trump, who had unsuccessfully urged Kemp and other top Republican officials in the state to overturn the results, has repeatedly vowed to return to Georgia to campaign against Kemp. Trump for months urged Perdue to primary challenge the governor, and he endorsed Perdue a day after the former senator launched his bid., Abrams, a former Democratic leader in the state legislature and a voting rights champion who’s become a rising star in the Democratic Party, faces nominal primary opposition as she runs a second straight time for governor.                                                                                                                                                                                                                                                                                                                                                                                                          , READ MORE FROM FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Fox News’ Paul Steinhauser contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/red-hot-inflation-millions-americans-financial-pain </td>
   <td style="text-align:left;"> 2022-01-28 00:22:32 </td>
   <td style="text-align:left;"> Red-hot inflation hurting millions of Americans financially, poll says </td>
   <td style="text-align:left;"> FOX Business’ Cheryl Casone reports on the Federal Reserve’s first policy-setting meeting of the year, where the Federal Open Market Committee also reaffirmed its commitment to withdrawing its asset purchase program.                                                                                                                                                                                                                                                                       , The hottest inflation in nearly four decades is inflicting financial pain on millions of U.S. households as prices for everyday necessities like food and gasoline continue to surge, according to a new Gallup survey.                                                                                                                                                                                                                                                                        , The price spike has caused some degree of financial hardship for about 49% of Americans, according to the poll of 811 people conducted between Jan. 3 and Jan. 16. Roughly 9% of respondents said that inflation is causing "severe" hardship that has made it difficult to maintain their standard of living, while 40% described it as "moderate" financial pain. That's an uptick from November, when 45% of Americans said inflation was hurting their wallets.                            , BIDEN TO MEET WITH CEOS IN PUSH TO SALVAGE MEGA SPENDING BILL                                                                                                                                                                                                                                                                                                                                                                                                                                  , The effect is more pronounced among lower-income families: Two-thirds of those making less than $40,000 a year say they experienced hardship compared with 56% of middle-income families and 32% of those earning more than $100,000 a year. What's more, 20% of Americans who are considered lower-income said the hardship they are experiencing is severe and hindering their ability to maintain their current standard of living.                                                         , Inflation jumped at its fastest pace in nearly 40 years last month, a 7% increase from the year-ago period, the Labor Department said recently.                                                                                                                                                                                                                                                                                                                                                , NEW YORK, NEW YORK - JANUARY 19: View of Major World, a used car dealership in Astoria, Queens, New York on January 19, 2022. ((Photo by Pablo Monsalve/VIEWpress via Getty Images) / Getty Images)                                                                                                                                                                                                                                                                                            , The rise in prices has been bad news for President Biden, who has seen his approval rating plunge as consumer prices rose. The White House has blamed the price spike on supply-chain bottlenecks and other pandemic-induced disruptions in the economy, while Republicans have pinned it on the president's massive spending agenda.                                                                                                                                                          , Price increases were widespread.                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Although energy prices fell 1.1% in December from the previous month, they're still up 29.3% from last year. Gasoline, on average, costs 49.6% more than it did last year. Food prices have also climbed 6.3% higher over the year, while used car and truck prices – a major component of the inflation increase – are up 37.3%. Shelter costs, which make up nearly one-third of the total increase, jumped 0.4% for the month and 4.1% year over year, the fastest pace since February 2007., Billboard on the cruelties of inflation in Coon Rapids, Minnesota. (Universal Images Group via Getty Images / Getty Images)                                                                                                                                                                                                                                                                                                                                                                    , The typical U.S. worker is actually worse off today than they were a year ago, even though nominal wages are rising at the fastest pace in years: Average hourly earnings for all employees decreased 2.4% in December from the same month a year ago when factoring in the impact of rising consumer prices. On a monthly basis, average hourly earnings increased by just 0.1% in December, when factoring in the 0.5% inflation spike.                                                      , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                                    , The poll shows that Americans think inflation will get worse before it begins to improve, with nearly eight in 10 survey respondents predicting that prices will continue to rise this year, with more than 50% expecting it to go up "a lot."                                                                                                                                                                                                                                                 , "In the past, Americans have always been more likely to say inflation will increase rather than decrease, but the current expectation is higher than usual -- in fact, it is the highest Gallup has measured in its trend," the survey said. The previous high was recorded in September 2005, when 76% of Americans predicted higher inflation.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2022-01-28 00:19:00 </td>
   <td style="text-align:left;"> US Natural Gas Futures at 2-Week High </td>
   <td style="text-align:left;"> US natural gas futures extended gains towards $4.4 per million British thermal units at the end of January, the highest since the middle of the month, underpinned by stronger demand prospects. According to the EIA, utilities pulled 219 bcf of natural gas from storage in the third week of January, the largest withdrawal since last year’s February freeze and it lowered total US inventory levels to roughly 1% below the five-year average. At the same time, freezing weather boosted heating demand in the US Northeast, such that next-day power and gas prices hit four-year highs. Elsewhere, strong demand for US exports from Asia and Europe have kept export plants working at new record levels in January. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mexico/currency </td>
   <td style="text-align:left;"> 2022-01-28 00:17:00 </td>
   <td style="text-align:left;"> Mexican Peso at Near 5-Week Low </td>
   <td style="text-align:left;"> The Mexican peso traded around 2.7 per USD, the lowest since December 21st, amid a stronger dollar. The dollar index traded above 97, near levels not seen since June 2020, after stronger-than-expected US Q4 GDP growth reinforced a more hawkish Federal Reserve stance. Yesterday, Chair Powell suggested the central bank will tight monetary policy faster than anticipated, with some market participants now betting on 5 rate hikes this year. Still, domestically, preliminary data showed that the economy likely contracted 0.2% in December and the Mexican economy is facing a potential credit rating downgrade in the medium term due to political developments, including the likely passage of a controversial energy bill. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/currency </td>
   <td style="text-align:left;"> 2022-01-28 00:13:00 </td>
   <td style="text-align:left;"> Canadian Dollar Not Far From 1-Month Low </td>
   <td style="text-align:left;"> The Canadian dollar traded around 1.27 per USD, not far from a one-month low of 1.27566 hit on January 5th, amid a stronger dollar. The dollar index traded above 97, near levels not seen since June 2020, after stronger-than-expected US Q4 GDP growth reinforced a more hawkish Federal Reserve stance. Still, domestically, the Bank of Canada left the interest rate steady in its first 2022 meeting disappointing some investors but signaled a hike will happen soon, probably during the next meeting on March 2nd. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/kansas-fed-manufacturing-index </td>
   <td style="text-align:left;"> 2022-01-28 00:09:00 </td>
   <td style="text-align:left;"> Tenth District Factory Growth at 6-Month High </td>
   <td style="text-align:left;"> The Kansas City Fed's Manufacturing Production Index rose to 20 in January of 2022, the highest in six months, from an upward revised 11 in the previous month. Factory growth was driven more by activity at durable goods plants in January, especially primary metals, machinery, electrical, furniture, and transportation equipment manufacturing. Indexes for production, employment, and order backlog rose at a faster pace, while the growth in supplier delivery time continued to ease slightly. New orders for exports also inched up. “Regional factory activity expanded at a faster pace in January. However, over half of firms indicated that 10% or more of their workers were out at some point in January due to COVID. Expectations for future activity remained strong, despite firms reporting difficulties from COVID, labor shortages, and continued supply chain issues”, said Chad Wilkerson, vice president and economist at the Federal Reserve Bank of Kansas City. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/baltic </td>
   <td style="text-align:left;"> 2022-01-27 23:54:00 </td>
   <td style="text-align:left;"> Baltic Exchange Dry Index Snaps 14-Day Losing Run </td>
   <td style="text-align:left;"> The Baltic Exchange Dry Index went up 0.5% to 1,302 on Thursday, after 14 straight sessions of declines, as the capesize index, which tracks iron ore and coal cargos of 150,000-tonnes, rebounded sharply by 16.5% to 818, crawling up from a 1-1/2-year low, likely tracking higher iron ore prices. Meanwhile, the panamax index which tracks cargoes of about 60,000 to 70,000 tonnes of coal and grains, fell 3.6% to 1,846, its lowest since April; and the supramax index fell 41 points to its lowest since February 2021 at 1,613. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60158934?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-27 23:50:37 </td>
   <td style="text-align:left;"> US economy grows at fastest pace in decades </td>
   <td style="text-align:left;"> The US economy expanded at its fastest rate in decades last year as it roared back from pandemic lockdowns.                                                                                                                                                       , Official figures from the Commerce Department showed the economy grew by 5.7% - its best performance since 1984.                                                                                                                                                  , But analysts are expecting growth to slow this year, as the government scales back stimulus spending and the Federal Reserve raises interest rates.                                                                                                               , Other risks include high inflation and threats from new Covid variants, such as Omicron.                                                                                                                                                                          , The World Bank is predicting the US economy will grow by 3.7% this year, in line with other forecasts.                                                                                                                                                            , "The Omicron wave means the economy is starting 2022 on a much weaker footing and we expect growth to disappoint over the rest of this year too," said Andrew Hunter, senior US economist at Capital Economics.                                                   , Consumer spending and government stimulus helped power the rebound from 2020, when gross domestic product contracted by 3.4% as the pandemic struck.                                                                                                              , The labour market has now regained some 19 million of the 22 million jobs lost amid shutdowns that year.                                                                                                                                                          , Output remained robust in the final three months of the year, when it grew at a better-than-expected annual rate of 6.9%.                                                                                                                                         , President Joe Biden hailed the figures, saying they were "no accident" but rather driven by the government's recovery efforts.                                                                                                                                    , As pandemic stimulus winds down, he urged Congress to move forward with additional spending plans focused on areas such as renewable energy, manufacturing and child care.                                                                                        , But with Mr Biden's agenda currently stalled in Congress, the economy is likely to have to perform without that boost - and with less help from America's central bank.                                                                                           , On Wednesday, Federal Reserve chair Jerome Powell signalled officials were planning to raise its key interest rate in March for the first time since 2018, saying the economy no longer needed extra-low borrowing costs put in place in 2020 to help it along.   , "The defining challenge for the economy in the next year or two will be how well we can sustain growth not just in the absence of fiscal policy, but in the face of tightening monetary policy," Wells Fargo economists wrote in a research note.                 , The Fed is under pressure to tackle inflation as the US sees prices rise at their fastest rate in nearly 40 years.                                                                                                                                                , Bank officials had initially said the pressures would be transitory and fade as the world moved past supply chain problems triggered by the virus - something that has proved to be far more difficult than hoped.                                                , Some analysts say the Fed has already moved too slowly to respond to the issue, while others fear the bank will move too aggressively, and the higher borrowing costs will reduce demand by more than expected.                                                   , US stock markets have seen three consecutive weeks of declines amid the concerns, as well as more recent data suggesting a slowdown as Omicron hit at the end of December and January.                                                                            , "Today's figures measure GDP up until the end of December 2021, excluding some of the recent surges in Covid-19 cases," said Richard Flynn, managing director at Charles Schwab UK.                                                                               , "Indeed, there's been weakness across US stock indices in the first weeks of 2022, as investors digest some of the risks facing the economy: receding monetary and fiscal liquidity, persistent effects from the pandemic, and a rise in inflationary pressures." , The story of the Holocaust through the eyes of remarkable 106-year-old Boris Pahor                                                                                                                                                                                , Watch the gripping new police drama, The Responder, starring Martin Freeman                                                                                                                                                                                       , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-01-27 23:24:02 </td>
   <td style="text-align:left;"> Canada Stocks Consolidate Gains </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, resumed their upward trend on Thursday after closing flat in the prior session, as higher oil prices supported the heavyweight energy sector. Meanwhile, the Bank of Canada and US Fed decisions on Wednesday continued to play a role in investors’ picks, with banking stocks in positive territory. Traders also digested upbeat GDP data from the world’s largest economy and Canada’s main trade partner. Domestically, average weekly earnings rose 1.9% over a month earlier in November, the sixth straight month of increases. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-27 23:16:00 </td>
   <td style="text-align:left;"> Russian 10Y Bond Yield Eases from Near 6-Year High </td>
   <td style="text-align:left;"> The yield on the 10-year OFZ treasury bond decreased to 9.5% from the near six-year high of 9.8% hit on January 26th as military tensions with Ukraine momentarily eased. Kremlin spokesman Dmitry Peskov signaled Moscow was not closing the door on diplomacy after the US rejected Russia’s demands over security arrangements in Europe. Still, investors remain cautious with Russian assets, as volatility due to sanction threats and geopolitical tension led the Ministry of Finance to cancel OFZ bond auctions for the second consecutive week. Meanwhile, Bank of Russia Governor Elvira Nabiullina said global pressures driving inflation represent a change in trends and continue to rise in the foreseeable future. Russian consumer inflation was held at 8.4% during December, despite aggressive rate hikes in 2021, erasing previous expectations that the Russian policy rate would ease through 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/pending-home-sales-mom </td>
   <td style="text-align:left;"> 2022-01-27 23:09:00 </td>
   <td style="text-align:left;"> Pending Home Sales Fall for 2nd Month </td>
   <td style="text-align:left;"> Contracts to buy US previously owned homes declined 3.8% in December of 2021, following an upwardly revised 2.3% drop in November and much worse than market forecasts of a 0.2% fall. It is the biggest decrease in pending home sales in 8 months, as a diminished housing supply offered consumers very few options. All four major US regions posted drops in contract activity. Existing-home sales are expected to decline by 2.8% in 2022, and home prices are expected to move higher by 5.1% due to the ongoing housing shortage, even as builders ramp up production, the NAR reported. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/australia/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-27 22:54:06 </td>
   <td style="text-align:left;"> Australia 10Y Bond Yield Near 3-Year Highs </td>
   <td style="text-align:left;"> The yield on the Australian 10-year government traded close to 2%, hovering highs not seen since March 2019, as global bond markets were rattled by the hawkish shift in the Federal Reserve’s interest rate outlook. The US central bank signaled a rate hike in March, as expected, and didn’t rule out further hikes at the following meetings of the year. Meanwhile, investors are betting that the Reserve Bank of Australia’s benchmark interest rate will be set at 0.25% as soon as May of this year, followed by four more hikes for the rest of the year, following hotter-than-expected inflation rate data in the final quarter of 2021. Additionally, core inflation climbed to a 7-1/2-year high of 2.6%, above the midpoint of the central bank’s 2%-3% target range. The RBA wasn’t expecting underlying inflation to breach the 2.5% level before late 2023, which stood as a key reading for its interest rate outlook. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-01-27 22:52:00 </td>
   <td style="text-align:left;"> Brazilian Equities Rise for 3rd Day </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Bovespa rose over 1% to around 112,530 on Thursday, extending gains for a third straight session, as investors digested better-than-expected US GDP growth figures, mixed US corporate earnings and the Fed's hawkish stance. Domestically, traders monitor the issue of the PEC of fuels, which still has no room in the 2022 Budget, as well as the movement of congressional wings to overturn presidential vetoes to the text signed. Brazilian President Jair Bolsonaro said on Tuesday that a proposed amendment to the Constitution being drafted by the government along with Congress will allow the reduction of federal and state taxes on fuel, electricity and cooking gas. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/hong-kong/balance-of-trade </td>
   <td style="text-align:left;"> 2022-01-27 22:43:00 </td>
   <td style="text-align:left;"> Hong Kong Trade Deficit Narrows in December </td>
   <td style="text-align:left;"> The trade deficit in Hong Kong narrowed to HKD 32.8 billion in December of 2021 from HKD 45.7 billion a year earlier. Exports jumped 24.8% to a record HKD 489.5 billion, mainly driven by sales of electrical machinery, apparatus, appliances, and related parts (29.8%), and office machines and automatic data processing machines (44.0%). Among the largest trade partners, exports to Mainland China rose 20.8%, to the US 19.9%, to India 84.0%, and to Taiwan 31.7%. Meanwhile, imports advanced a slower 19.3% to an all-time high of HKD 522.3 billion, driven mostly by electrical machinery, apparatus, appliances, and related parts (25.5%), and office machines and automatic data processing machines (37.2%). Among major suppliers, imports from China rose 20.9%, from the US 24.5%, from Singapore 29.5%, and from Korea 16.1%. For 2021 as a whole, Hong Kong registered a trade deficit of H$347.1 billion, as exports jumped 26.3% to HKD 4,968.1 billion and imports rose 24.3% to HKD 5,311.2 billion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-01-27 22:41:00 </td>
   <td style="text-align:left;"> Wall Street Rebounds </td>
   <td style="text-align:left;"> US stocks rebounded on Thursday, with the Dow Jones surging more than 400 points and both the S&amp;P 500 and the Nasdaq adding more than 1.5% each as investors digest the latest FOMC statement, encouraging US GDP growth figures and mixed earnings reports. The US economy expanded a much better-than-expected 6.9% in Q4 while the Fed signaled yesterday it may tighten monetary policy faster than anticipated, with some market participants now betting on 5 rate hikes this year. On the corporate front, shares of Tesla were down more than 3% and Intel almost 6%. The carmaker warned supply chain issues could persist throughout 2022 and Intel showed a mixed outlook for the first quarter. Also, earnings from McDonald's missed estimates and the company's stocks dropped 1%. Apple stocks however, were up around 1.5% ahead of the earnings release today after the closing bell. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/varney-rips-bidens-weak-leadership-for-making-energy-russias-best-weapon </td>
   <td style="text-align:left;"> 2022-01-27 22:40:39 </td>
   <td style="text-align:left;"> Varney rips Biden’s ‘weak’ leadership for making energy Russia’s best weapon </td>
   <td style="text-align:left;"> FOX Business host Stuart Varney argues Germany and much of Europe are 'beholden' to Russia, which 'supplies 40 percent' of the region's natural gas.                                                                                                             , During his latest "My Take," "Varney &amp; Co." host Stuart Varney ripped Biden's "weak" leadership and the climate crowd for "making energy Russia's best weapon" as tensions rise in Eastern Europe.                                                               , STUART VARNEY: Back in the day, President Trump hammered the Europeans: he wanted them to defend themselves against the Russians instead of relying on us.                                                                                                       , He warned them against relying on Russia for their oil and gas supplies.                                                                                                                                                                                         , But they hated Trump, especially Germany's Angela Merkel. She wouldn't spend much on defense, and when Mr. Trump lost the election, she promptly canceled plans to import gas from America! She threw Germany into Russia's hands.                               , And that’s where Germany and much of Europe is now. Beholden to Russia which supplies 40% of Europe's nat gas.                                                                                                                                                   , BIDEN ADMINISTRATION WEIGHING 'SEVERE' RUSSIA SANCTIONS IN CASE OF UKRAINE INVASION                                                                                                                                                                              , That’s why Germany is not behaving like an ally over Ukraine. They are scared to oppose Russia. They are reluctant to impose sanctions, and they won't help Ukraine's defense. Asked to send military supplies, they sent 5,000 helmets.                         , Europe is not helping itself either. The climate crowd won't let 'em. There's as much nat gas under European soil as there is in America, but they won't go get it! No fracking over there. And Germany is about to shut down its last two nuclear power plants. , OIL RISKS PRICE RISE AMID UKRAINE-RUSSIA TENSIONS                                                                                                                                                                                                                , Putin is laughing: oppose me, and you'll freeze!                                                                                                                                                                                                                 , After meeting virtually with European leaders, President Biden says there's 'total unity.'                                                                                                                                                                       , That’s a facade, and Putin won't believe it.                                                                                                                                                                                                                     , Truth is, the greens, and weak leadership made energy Russia's best weapon. Trump saw it coming.                                                                                                                                                                 , GET FOX BUSINESS ON THE GO BY CLICKING HERE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/technology-60154782?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-27 22:17:48 </td>
   <td style="text-align:left;"> Musk: Robots to be bigger business than Tesla cars </td>
   <td style="text-align:left;"> Elon Musk likes to have a focus - and this year, it looks like it might be robots.                                                                                                                                                      , He told investors on a Tesla earnings call his nascent robot plans had "the potential to be more significant than the vehicle business, over time".                                                                                     , And they would be the most important things Tesla worked on this year.                                                                                                                                                                  , The robot in question, part of a project dubbed Optimus, was previewed last year - to raised eyebrows - by a human in a robot suit dancing on stage.                                                                                    , And the performance became a popular internet meme.                                                                                                                                                                                     , The Tesla Bot, as it was dubbed, would use the same artificial-intelligence (AI) systems that helped power Tesla vehicles, Mr Musk said at the event last August - but no prototype has yet been made.                                  , He also said the not-yet-built 5ft 8in robot would have a screen on its "face" and be able to lift 150lb and travel at about 5mph.                                                                                                      , This week, Mr Musk told investors the humanoid robot's first application would be at a Tesla plant "moving parts around the factory, or something like that".                                                                           , But in the future, he sees it helping solve labour shortages.                                                                                                                                                                           , And earlier this week, he tweeted: "Tesla AI might play a role in AGI [artificial general intelligence], given that it trains against the outside world, especially with the advent of Optimus".                                        , AGI refers to the ability of a machine to learn or understand tasks currently performed by humans.                                                                                                                                      , Mr Musk has previously warned AI risks killing off human civilisation.                                                                                                                                                                  , And in the same Twitter thread, he added: "Decentralised control of the robots will be critical."                                                                                                                                       , Professor of robot ethics Alan Winfield, at the University of West England, said: "AGI is an exceptionally hard problem.                                                                                                                , "The idea that you can crack AGI because you have created a driverless vehicle is absurd.                                                                                                                                               , "Even if that car is highly capable, that would not be AGI - it would be high-functioning narrow intelligence.                                                                                                                          , "Google and Facebook have hired some of the best AI people in the world and the idea that Musk can come in and crack the problem is hubristic in the extreme."                                                                          , Mr Musk does likes hard problems though, from autonomous cars to trips to Mars, and has plenty of successes.                                                                                                                            , SpaceX's reusable rockets are widely regarded as representing a big step forward for space flights, for example.                                                                                                                        , But previous efforts to create cost-effective mass-market humanoid robots have failed.                                                                                                                                                  , In June, Japanese conglomerate Softbank announced production of Pepper, a friendly little humanoid, had been paused and would start again only when the robots were needed, much to the dismay of the academic community that used them., That said, robots are increasingly used in factories around the world, with a current average of 126 robots per 10,000 employees in the manufacturing industry, according to the International Federation of Robotics.                  , Many, though, remained sceptical about Mr Musk's plans.                                                                                                                                                                                 , Accel Robotics software engineer Filip Piekniewski tweeted: "Anyone who thinks Tesla is actually building a humanoid robot is living in an alternate reality.                                                                           , "Mars bases is more likely than the bot."                                                                                                                                                                                               , And professor of cognitive robotics Tony Prescott, at the University of Sheffield, told BBC News Mr Musk would face many challenges.                                                                                                    , "If it is being used in a factory, then a wheel-based robot would be much easier to build and have no problems of balance - but then it wouldn't be humanoid," he said.                                                                 , Keeping the robot upright would be one of the biggest issues, Prof Prescott said, along with creating hands and any form of hand-to-eye co-ordination.                                                                                  , "These are fundamental research problems that you need to solve," he said.                                                                                                                                                              , And even robots such as Atlas, designed by Boston Dynamics and regarded as one of the most sophisticated humanoid bots available "will be attached to the ceiling when it is not making videos".                                        , "Tesla cars are robots - but they are a much simpler form, so this will be starting from scratch," Prof Prescott added.                                                                                                                 , Prof Winfield agrees with Mr Musk on one thing though.                                                                                                                                                                                  , "The only thing that Musk is getting right is that the path towards AGI will be through physical robots," he said.                                                                                                                      , "Our own intelligence is grounded in the real world."                                                                                                                                                                                   , The Tesla boss's new robotics focus may disappoint some customers - in the same earnings call, he also said the company would not be introducing any new car models in 2022.                                                            , And he does have a history of making rather ambitious promises.                                                                                                                                                                         , In 2019, he said Tesla would have one million robot-taxis on the road by the end of 2020.                                                                                                                                               , The story of the Holocaust through the eyes of remarkable 106-year-old Boris Pahor                                                                                                                                                      , Watch the gripping new police drama, The Responder, starring Martin Freeman                                                                                                                                                             , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-27 22:17:00 </td>
   <td style="text-align:left;"> Japan 10Y Bond Yield at 11-Month High </td>
   <td style="text-align:left;"> The yield on the benchmark Japan 10-year JGB climbed more than 2 bps to an eleven-month high of 0.159% on Thursday, following the Federal Reserve’s hawkish shift in the interest rate outlook. Still, the Bank of Japan’s goal to keep yields within 0.25% range of zero, made possible through debt purchases in the secondary market, has helped keep yields from rising too much. Meanwhile, two and five-year government bond yields climbed to six-year highs to -0.055% and -0.01%, respectively. The Federal Reserve signaled a rate hike in March, as expected, while it didn’t dismiss the possibility of rate hikes in every future meeting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/port-of-savannah-hits-container-record-amid-continued-supply-chain-disruptions </td>
   <td style="text-align:left;"> 2022-01-27 22:14:29 </td>
   <td style="text-align:left;"> Major US port hits container record as supply chain disruptions continue to roil US </td>
   <td style="text-align:left;"> FOX Business' Ashley Webster speaks with Griff Lynch, the executive director of the Georgia Ports Authority, about how the Port of Savannah is handling the supply chain disruptions.                                                                                                                                                                                                                                                                                , The Port of Savannah hit a container record last year, handling 5.6 million container units of imports and exports, an increase of 1 million container units from the year before amid continued supply chain disruptions.                                                                                                                                                                                                                                           , The Georgia Ports Authority provided the data on Tuesday, noting the 20% increase in shipping containers moving through the Port of Savannah in 2021 as seaports across the U.S. struggled to keep up with the surge in cargo that packed container yards and forced ships to wait at sea.                                                                                                                                                                           , Reporting on "Mornings with Maria" on Thursday, FOX Business correspondent Ashely Webster noted that the situation has "improved" at the port since his last visit about three and a half months ago when the port was "completely packed with containers, with more than close to 40 ships anchored offshore." Webster reported that on Thursday morning he saw only one ship anchored offshore waiting to come into port.                                          , Executive director of the Georgia Ports Authority Griff Lynch told Webster during a live interview on "Varney &amp; Co." that while every major port is experiencing a backup of ships, the Port of Savannah is "fortunate that we have the expansion capability," which is helping to navigate the situation.                                                                                                                                                           , He told Webster that a few months ago more space was needed "in order to get the cargo moving and once we did that, we’d be able to get those ships caught up, well more space has come."                                                                                                                                                                                                                                                                            , He noted that while more capacity has been added, "we are only part of the way done."                                                                                                                                                                                                                                                                                                                                                                                , Lynch has said retailers rushed to refill inventories and kept ordering in an attempt to keep shelves stocked while online shopping also continued to grow amid the coronavirus pandemic, contributing to the record volumes at The Port of Savannah during all 12 months of 2021.                                                                                                                                                                                   , "It literally is three to four years of growth in one year," Lynch said in an interview with The Associated Press, stressing that "it didn’t come out without pain."                                                                                                                                                                                                                                                                                                 , He went on to note that the port’s container yard is still largely full and said the outlook for 2022 remains uncertain.                                                                                                                                                                                                                                                                                                                                             , Lynch expects strong cargo volumes to continue in the first quarter but noted that some forecasts predict a slowdown driven by inflation later in the year.                                                                                                                                                                                                                                                                                                          , Federal Reserve Chair Jerome Powell holds a briefing following the FOMC's decision on interest rates.                                                                                                                                                                                                                                                                                                                                                                , "I would not say that I would expect the supply chain issues to be completely worked out by the end of this year, I do not expect them and I have not expected them," Federal Reserve Chairman Jerome Powell said on Wednesday responding to a question from FOX Business during a news conference.                                                                                                                                                                  , "What I would say, and I have been saying is that I expect progress to be made in the second half of this year mainly, progress because we are not making much progress" he went on to say. "Things like the semiconductor issue, they’re going to be quite a long time, I think they’ll go more than through 2023."                                                                                                                                                 , Powell’s comments on Wednesday contradicted claims from the Biden administration last month that there has been "significant progress" by his Supply Chain Disruptions Task Force.                                                                                                                                                                                                                                                                                   , In a document released last month, the White House struck an optimistic tone on gas prices, supply chain issues, and inflation – factors that have caused him polling issues and subjected him to intense Republican criticism.                                                                                                                                                                                                                                      , Late last year, Powell acknowledged inflation was no longer transitory as the supply chain crisis raged.                                                                                                                                                                                                                                                                                                                                                             , "Bottlenecks and supply constraints are limiting how quickly production can respond to higher demand in the near term. These problems have been larger and longer-lasting than anticipated, exacerbated by waves of the virus" he said during the December meeting.                                                                                                                                                                                                  , WORKERS IN THE DRIVER'S SEAT AS JOB OPENINGS SURGE AMID LABOR SQUEEZE                                                                                                                                                                                                                                                                                                                                                                                                , The consumer price index rose 7% in December from a year ago, according to a Labor Department report released earlier this month, marking the fastest increase since June 1982, when inflation hit 7.1%. The CPI – which measures a bevy of goods ranging from gasoline and health care to groceries and rents – jumped 0.5% in the one-month period from November.                                                                                                  , Price increases were widespread. Although energy prices fell 1.1% in December from the previous month, they're still up 29.3% from last year. Gasoline, on average, costs 49.6% more than it did last year. Food prices have also climbed 6.3% higher over the year.                                                                                                                                                                                                 , Ports have become one of many bottlenecks in global supply chains as ships have been filling up with boxes carrying everything from electronics to frozen chickens. The backlogs have been leading to some empty shelves at stores.                                                                                                                                                                                                                                  , FOX Business' Ashley Webster reports from the Port of Savannah.                                                                                                                                                                                                                                                                                                                                                                                                      , The Port of Savannah, which has the fourth-busiest U.S. seaport for cargo shipped in containers, experienced shipping traffic jams last fall when as many as 25 ships at a time waited off the Georgia coast while up to 85,000 containers piled up on the terminal awaiting transport amid the surge in trade.                                                                                                                                                      , The port authority added more workers and equipment, and the agency set up inland sites to temporarily store cargo and free up space at Savannah’s container terminal. The agency won approval from the federal government to use $8 million in leftover grant money to set up four container yards in different parts of the state.                                                                                                                                 , Webster noted on Thursday that "the cost of shipping freight continues to rise," which will likely lead to higher prices for the consumer as inflation has soared to the highest level in four decades.                                                                                                                                                                                                                                                              , Container freight rates have soared 130% globally year over year, according to the Freightos Baltic Index.                                                                                                                                                                                                                                                                                                                                                           , Wholesale prices rose at the fastest pace on record in December, the latest evidence that inflationary pressures are continuing to plague the U.S. economy.                                                                                                                                                                                                                                                                                                          , CRUCIAL US CONTAINER PORT COMPLEX EXECUTIVE DIRECTOR: NORMALCY IN MID 2022 DEPENDS ON COVID                                                                                                                                                                                                                                                                                                                                                                          , The Labor Department said earlier this month that its producer price index, which measures inflation at the wholesale level before it reaches consumers, surged 9.7% in December from the year-ago period. It marked the highest figure on record since the government began tracking the data in 2010.                                                                                                                                                              , Still, there are some signs that inflation could be decelerating: On a monthly basis, prices rose just 0.2% in December following a revised gain of 1% in November. Economists surveyed by Refinitiv expected producer inflation to rise by 9.8% on an annual basis and 0.4% from the previous month.                                                                                                                                                                , Former Chairman of the Council of Economic Advisers Kevin Hassett argues Treasury Secretary Janet Yellen is ‘decoupling’ Americans’ expectations about future inflation.                                                                                                                                                                                                                                                                                             , Food prices declined 0.6% in December after climbing 1.2% in November, while energy prices dropped 3.3%, following a 2% gain the previous month.                                                                                                                                                                                                                                                                                                                     , Powell has said the Fed mistakenly expected that supply chain bottlenecks driving up prices for goods including cars, appliances, and furniture would not last nearly as long as they have. Once unsnarled, prices for things like used cars, which have soared in 2021, would come back down, Powell noted.                                                                                                                                                         , However, for now, those supply chain problems have persisted, and while there are some signs they are easing, Powell has acknowledged that progress is limited. He noted earlier this month that many cargo ships remain docked outside the ports of Los Angeles and Long Beach, the nation's largest, waiting to unload.                                                                                                                                            , The Los Angeles area saw a backup of a record 157 ships in October of last year.                                                                                                                                                                                                                                                                                                                                                                                     , Webster reported on Thursday that the ports in Long Beach and Los Angeles are "still struggling" with more than 100 ships offshore as the omicron variant has posed added challenges.                                                                                                                                                                                                                                                                                , He also noted that the truck driver shortage is contributing to those challenges at U.S. ports as it has been difficult to find the resources needed to transport the offloaded cargo to retailers and warehouses across the country.                                                                                                                                                                                                                                , Chris Spear, president and CEO of the American Trucking Associations argues the slow return to work is 'exacerbating the supply chain's ability to meet demand,' noting that truckers are moving more with less people.                                                                                                                                                                                                                                              , Last week, American Trucking Associations President and CEO Chris Spear argued that the slow return to work is "exacerbating the supply chain's ability to meet demand."                                                                                                                                                                                                                                                                                             , Speaking on "Mornings with Maria," Spear explained the impact on the supply chain due to the "chronic shortage of talent," which has led to cargo sitting unused and unloaded at U.S. ports. He noted that the trucking industry is "short 81,000 drivers."                                                                                                                                                                                                          , Port of Long Beach executive director Mario Cordero also provided insight into the supply chain issues he is facing while speaking on "Mornings with Maria" last month. He noted that the crucial harbor has been "making progress" with capacity constraints and predicted that by the middle of this year there will be "some sense of normalcy," stressing that the progress will be contingent on the track of the coronavirus and its impact on the labor force., Cordero had been warning of an industry "crisis" over supply chain disruptions.                                                                                                                                                                                                                                                                                                                                                                                      , Port of Long Beach executive director Mario Cordero notes that currently the ports are in the peak season and in the coming months 'we do expect a diminishment with regard to the vessels that are coming to over here to the west coast.'                                                                                                                                                                                                                          , Speaking with "Mornings with Maria" in September, Cordero noted that there was a "confluence of factors" on why the situation developed into a "crisis," explaining that the disruption to the supply chain is "very much" due to the COVID-19 pandemic.                                                                                                                                                                                                             , Cordero also pointed out that another big factor is skyrocketing consumer demand in the United States, especially pertaining to online orders amid the pandemic as more people opted to shop from home.                                                                                                                                                                                                                                                              , He also pointed to "the healthy appetite of the American consumer," which he acknowledged is "good news," but noted they are "purchasing at numbers that were not foreseen," which is contributing to the supply chain bottleneck.                                                                                                                                                                                                                                   , In September, Cordero pointed out there were as many as 73 vessels at anchor. Last month, he noted that the number was at around 28, acknowledging the situation is "much better" compared to several weeks ago.                                                                                                                                                                                                                                                     , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                          , Earlier this month The Wall Street Journal reported that the prospect of continued COVID disruptions in China, the world’s second-largest economy, is increasing worries that bottlenecks will continue to weigh on the supply chain and will ripple through the global economy.                                                                                                                                                                                     , China has a zero-tolerance strategy for combating the coronavirus pandemic and has been experiencing a flare-up of cases, which is leading to major manufacturers shutting factories at a time while workers are in short supply as officials impose city lockdowns and mass testing on a scale that was not experienced in nearly two years, according to the Journal.                                                                                              , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                              , FOX Business’ Edward Lawrence, Suzanne O’Halloran, Andrew Mark Miller, Megan Henney and The Associated Press contributed to this report.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/small-business-sentiment </td>
   <td style="text-align:left;"> 2022-01-27 22:13:14 </td>
   <td style="text-align:left;"> Canada Small Business Morale at Over 1-Year Low </td>
   <td style="text-align:left;"> Canada's CFIB's Business Barometer long-term index, which is based on 12-month outlook, declined by 8.3 points to 54.3 in January of 2021, its lowest since October of 2020. In addition to concerns about renewed restrictions and ongoing labour shortages, many businesses are reporting supply chain challenges. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/01/27/us/joe-rogan-jordan-peterson-climate-science-intl/index.html </td>
   <td style="text-align:left;"> 2022-01-27 22:00:19 </td>
   <td style="text-align:left;"> Joe Rogan: Scientists slam climate denialism from Jordan Peterson as 'absurd'  - CNN </td>
   <td style="text-align:left;"> (CNN)As podcaster Joe Rogan faces condemnation from medical scientists for spreading misinformation about vaccines and Covid-19, another interview by the controversial host this week has become the subject of mockery -- this time among climate scientists.                                                                          , Canadian clinical psychologist Jordan Peterson appeared on "The Joe Rogan Experience" on Monday, making false and generalized claims that the modeling scientists use to project climate change and its impacts are flawed.                                                                                                               ,                                                                                                                                                                                                                                                                                                                                           , In waffling remarks, Peterson said that "there's no such thing as climate, right?" He then went on to mock "climate types," who he said typically suggest that "climate is about everything."                                                                                                                                             , "But your models aren't based on everything. Your models are based on a set number of variables. So that means you've reduced the variables -- which are everything -- to that set. But how did you decide which set of variables to include in the equation if it's about everything?"                                                   , Rogan, whose podcast is hosted on Spotify, did little to challenge the unsubstantiated comments.                                                                                                                                                                                                                                          , Peterson's remarks show a general misunderstanding of how scientific modeling works. Scientists use models, or simulations, to project particular aspects of climate change, such as the rise in global temperatures, changes in rainfall patterns and the likelihood of drought.                                                         , Climate scientists are now ridiculing Peterson's claims.                                                                                                                                                                                                                                                                                  , "Such seemingly-comic nihilism would be funny if it weren't so dangerous," Michael E. Mann, a climate scientist at Pennsylvania State University, told CNN.                                                                                                                                                                               ,                                                                                                                                                                                                                                                                                                                                           , "Similar anti-science spread by these two individuals about COVID-19 likely has and will continue to lead to fatalities. Even more will perish from extremely dangerous and deadly weather extremes if we fail to act on the climate crisis. So the promotion of misinformation about climate change is in some ways even more dangerous.", Mann said that Peterson's claims were "nonsensical and false," and seems to boil down to the idea that climate science is so complicated that scientists could never model it or understand it.                                                                                                                                           , "Such an absurd argument leads to a dismissal of physics, chemistry, biology, and every other field of science where one formulates (and tests—that's the critical part Peterson seems to fail to understand) conceptual models that attempt to simplify the system and distill the key components and their interactions," Mann said.    , "Every great discovery in science has arisen this way. Including the physics of electromagnetism that allowed Peterson and Rogan to record and broadcast this silly and absurd conversation."                                                                                                                                             , Spotify declined to comment on the criticism. CNN has reached out to "The Joe Rogan Experience" for comment.                                                                                                                                                                                                                              , NASA climate scientist Gavin Schmidt shared similar views on Twitter, pointing out that Peterson didn't appear to understand how climate models work.                                                                                                                                                                                     , Zeke Hausfather, a research scientist at Berkeley Earth, tweeted graph showing how accurate scientists' projections of global warming have been over several decades.                                                                                                                                                                     , "For what it's worth, we have been projecting future warming since the first climate models in the late 1960s/early 1970s. We can look back to see how well they have performed. It turns out our models generally did a good job," he wrote.                                                                                             , The backlash comes as musician Neil Young told audio streaming giant Spotify he no longer wanted his music to be featured on on the service because of Rogan's frequent false claims around Covid-19 and vaccines.                                                                                                                        , Spotify announced on Wednesday it would no longer stream the music of Neil Young, according to a Washington Post report.                                                                                                                                                                                                                  , This story has been updated with comments from climate scientist Michael E. Mann.                                                                                                                                                                                                                                                         , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/01/27/health/omicron-booster-wait-wen-wellness/index.html </td>
   <td style="text-align:left;"> 2022-01-27 21:59:13 </td>
   <td style="text-align:left;"> Should you wait for an Omicron-specific booster? - CNN </td>
   <td style="text-align:left;"> (CNN)Pfizer and BioNTech announced Tuesday that they're beginning a clinical trial for an Omicron-specific Covid-19 vaccine, and Moderna revealed Wednesday that it has entered Phase 2 of its own trial of a vaccine that targets the variant, which is by far the dominant one in the United States right now.                                                                                                                                                                                                                                                                         , About 50% of eligible Americans have received a booster shot, according to the US Centers for Disease Control and Prevention, but the Pfizer and Moderna news might raise questions regardless. For those who have yet to get inoculated, should they wait until there is an Omicron-specific vaccine? What if someone has already had Covid-19 during the Omicron surge, do they still need a booster? And what does this mean for people who've already gotten a booster, or those who received the one-dose Johnson &amp; Johnson vaccine and then subsequently got a dose of another kind?,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , For answers to these and other questions, I spoke with CNN Medical Analyst Dr. Leana Wen. Wen is an emergency physician and professor of health policy and management at the George Washington University Milken Institute School of Public Health. She is also author of "Lifelines: A Doctor's Journey in the Fight for Public Health."                                                                                                                                                                                                                                                 , CNN: Should people hold off on getting their booster until they can receive an Omicron-specific one?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Dr. Leana Wen: No, they shouldn't. Everyone eligible to receive a booster should do so now.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Here are two key reasons why: First, there is growing evidence that a third shot of Pfizer or Moderna or a second vaccine following Johnson &amp; Johnson is needed to sustain strong protection against Covid-19. Last week, three large new studies from the CDC found that boosters protect against severe illness and reduce the likelihood of contracting coronavirus.                                                                                                                                                                                                                   , During a period in December and January when Omicron was dominant, one study found that getting a booster dose was 90% effective at preventing hospitalization, compared with the 57% effectiveness seen in vaccinated people who had not been boosted and were six months past their second shot. Another study examining over 13,000 Omicron cases found that the likelihood of developing symptomatic infection was 66% lower in participants with three doses compared with two.                                                                                                      ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Second, the Omicron-specific vaccines are still in clinical trials. The trials will take months complete. We don't know yet the results of the trial and whether these variant-specific vaccines will be better than the original vaccines. Even if they end up getting authorized, it will be months from now, and with Omicron still surging, people shouldn't delay their boosters.                                                                                                                                                                                                    , If you are an adult at least five months out from your two doses of Pfizer or Moderna, or two months out from your one dose of Johnson &amp; Johnson, you should get a booster now. Adolescents 12 and older are also recommended to receive a third dose of the Pfizer vaccine if it's been at least five months since their second dose (only the Pfizer/BioNtech vaccine is authorized for adolescents 12 to 17).                                                                                                                                                                          , CNN: If you get the regular booster now, does that mean you can't get the Omicron-specific booster later?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Wen: No. One of the groups Pfizer is studying includes individuals who received three doses and now are receiving a fourth vaccine dose that is an Omicron-specific booster. The company will be studying the effect of this fourth dose. It may be that a fourth shot isn't needed because the initial booster will continue to provide very good protection. But if the variant-specific booster, in addition to the third dose, is something that adds a lot more protection, the recommendation may well be that people receive it in the future.                                     , CNN: What if someone has just had Omicron? Should they still get the regular booster now?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Wen: Most people don't find out what variant of Covid-19 they had if they were infected, but given that Omicron now constitutes over 99% of new infections, if they recently contracted the coronavirus, it probably was Omicron.                                                                                                                                                                                                                                                                                                                                                         , Individuals who are vaccinated and also recovered from infection appear to have a very high degree of immune protection. The immunity from recovery is variable, though. Someone who became very ill may have a stronger antibody response compared with someone who had an asymptomatic infection, and we don't know how long that immunity lasts.                                                                                                                                                                                                                                       , That's why boosters are still recommended for people who have had Covid-19. They can receive one as soon as their isolation period ends, as long as they no longer have a fever and their symptoms are improving.                                                                                                                                                                                                                                                                                                                                                                         , CNN: How long does the booster last? Do you think we will need a second booster soon?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Wen: We don't know. A new pre-print study from the University of Texas, online but not yet peer-reviewed, found that antibodies against Omicron remain robust four months after the booster dose. There are also other components of the immune response, T-cells and B-cells, that may remain strong for months, too, but we just don't know yet when immunity after three shots may wane. This is something that researchers will monitor very carefully. In the meantime, the evidence is very clear that people need to receive that booster dose.                                    , CNN: What about people who initially received the Johnson &amp; Johnson vaccine, and then subsequently got their booster? Do they need a third shot?                                                                                                                                                                                                                                                                                                                                                                                                                                          , Wen: I'm one of these people -- I initially received the one-dose Johnson &amp; Johnson vaccine in a clinical trial and then decided to "mix and match" and got a Pfizer booster.                                                                                                                                                                                                                                                                                                                                                                                                             , I don't think those of us who have received a second dose of any of the vaccines (Pfizer, Moderna or J&amp;J) following the initial J&amp;J shot need to receive a third shot at this time. A study out of South Africa found that a second dose of J&amp;J was 85% effective against hospitalization during a time when Omicron was circulating, compared with 63% after one dose. Another real-world study from the United Kingdom looked at the AstraZeneca vaccine, which is similar to J&amp;J.                                                                                                      ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , It found that while two doses of AstraZeneca provided little protection against Omicron, a Pfizer booster following AstraZeneca resulted in 71% protection against symptomatic illness. This was a similar level of protection to those who received three doses of the Pfizer vaccine.                                                                                                                                                                                                                                                                                                   , At the moment, the recommendation is that those of us in the US who received J&amp;J initially are fine with a second dose of any of the three authorized vaccines. I am not planning to get a third vaccine dose any time soon. However, I do think there's been a sense that federal health guidance has lagged for J&amp;J recipients, and I hope there will not be a delay in advising us should research come out that a third dose is needed.                                                                                                                                               , CNN: Do you think the development of Omicron-specific vaccines will help with speeding up the end of the pandemic?                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Wen: I am optimistic, in general, about the Covid-19 pandemic coming to an end. Not that Covid-19 is going to disappear -- it's something that's almost certainly going to be with us for the foreseeable future -- but we have many more tools that will allow us to coexist with the virus so that it doesn't have to dominate our lives.                                                                                                                                                                                                                                               ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Developing new vaccines will be a key part of living with Covid-19. I hope there will be more research into vaccines that target coronaviruses broadly, so that if new mutations arise, we don't need to keep playing Whack-a-Mole.                                                                                                                                                                                                                                                                                                                                                       , That said, I do think it's a good thing that companies are developing variant-specific vaccines, especially if they end up providing better, more robust protection. Again, though, we won't know whether that's the case for months, and people should really not delay getting their boosters now.This story has been updated to include additional information about Moderna's clinical trials.                                                                                                                                                                                        , </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2022-01-28 09:15:20 UTC +8

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
   <td style="text-align:left;"> 2022-01-28 09:14:55 </td>
   <td style="text-align:left;"> $SPY Okay so yesterday futures were like -2% and somehow we opened green. So I really don’t care about futures anymore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:14:55 </td>
   <td style="text-align:left;"> $SPY the next breakung record earnings will be amazon next week..mark this post </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:14:54 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $BTC $AAPL  Volatility got the markets gas break dippin! Tell me when to Go tell me when to Goooo 📈📉📈📉📈📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:14:28 </td>
   <td style="text-align:left;"> $SPY of course it’s oversold, it’s a market crash 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:14:28 </td>
   <td style="text-align:left;"> $SPY the news tomorrow boutta send this down to lows </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:14:28 </td>
   <td style="text-align:left;"> $SPY Ever think you&amp;#39;re being witty or insightful here and review what you said at a later time and realize you&amp;#39;re on the wrong end of the bell curve? Me neither. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:14:27 </td>
   <td style="text-align:left;"> $SPY Everyone on CNBC is bearish. Everyone on Twitter is bearish. 

The max pain would be a gigantic short squeeze to fool the bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:14:13 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:14:06 </td>
   <td style="text-align:left;"> $SPY Send it to hell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:14:00 </td>
   <td style="text-align:left;"> $SPY inflation through the roof and recession , dump this market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:13:57 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $HOOD 

Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:13:53 </td>
   <td style="text-align:left;"> $SPY Tomorrow red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:13:51 </td>
   <td style="text-align:left;"> $SPY $QQQ Damn, I hope y&amp;#39;all are long! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:13:40 </td>
   <td style="text-align:left;"> $SPY Allstar lineup 
👍😍🤑🤦🏻‍♂️🥳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:13:23 </td>
   <td style="text-align:left;"> $SPY free money Friday after a while </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:13:22 </td>
   <td style="text-align:left;"> $ARKK Cramer just said buy $SARK Could this be an indication that we’ve seen the blow off bottom on growth??? $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:13:14 </td>
   <td style="text-align:left;"> $SPY $QQQ I think we will see a massive rally tomorrow because too many people are shorting now, they will have to cover with the weekend coming up . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:12:54 </td>
   <td style="text-align:left;"> $SPY Japan recovered. China should rocket. May see 3% tomorrow. Who knows and who really cares </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:12:52 </td>
   <td style="text-align:left;"> $SPY futures looking green. Crypto green 🚀💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:12:48 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:12:47 </td>
   <td style="text-align:left;"> $SPY  bear market rally. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:12:31 </td>
   <td style="text-align:left;"> $SPY once again don’t let the futures fool you. They don’t really matter; green or red. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:12:29 </td>
   <td style="text-align:left;"> $SPY I heard Rona got OFG. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:12:18 </td>
   <td style="text-align:left;"> $SPY how long til we turn red? 4am? 8am? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:12:15 </td>
   <td style="text-align:left;"> $SPY Hey bulls, back in the trenches sooner than you think. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:12:07 </td>
   <td style="text-align:left;"> $SPY bears you do realize apple had its best sales quarter ever in their history..you do realize that...that doesn&amp;#39;t look like recession numbers at all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:12:00 </td>
   <td style="text-align:left;"> The technical rating of $SPY is bad and it also does not present a quality setup at the moment. https://www.chartmill.com/stock/analyzer/stock/SPY?key=84303b30-e7bc-44d7-b0b1-1493858db9a2&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=SPY&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:11:21 </td>
   <td style="text-align:left;"> $SPY same routine. So buy calls then end the day with puts or vise versa. Regardless, tomorrow will have a nice Friday for lottos 🙏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:11:21 </td>
   <td style="text-align:left;"> $SPY the whole point is my follower who’s not on here views me as his teacher not his broker. He follows me to learn not to make the moves for him…brokers make u broke, teachers teach </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:11:19 </td>
   <td style="text-align:left;"> $SPY bulls getting all cocky because Nikkie flipped green. 

Ok but what now doe? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:11:15 </td>
   <td style="text-align:left;"> $SPY $IWM $QQQ $RBLX $SHOP  
 
https://www.financegreater.com/post/managing-a-bearish-market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:11:04 </td>
   <td style="text-align:left;"> All future bounces are a chance to sell. Fed Put no longer a factor, Powell&amp;#39;s focused on inflation to protect POTUS ratings. 🐻 markets call for selling ALL $SPY  $QQQ  $DJIA  &amp;amp; $AAPL  included. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:11:02 </td>
   <td style="text-align:left;"> $SPY Market makers pricing in $440 tomorrow. Need to close above $442 to confirm reversal. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:10:49 </td>
   <td style="text-align:left;"> $SPY I’ve been bearish, but you need to know how to play both sides. Like things don’t  “only go up” they also dont “only go down”. Obviously crashes pretty much only go down, but I don’t believe we’re there yet. Why ?  Because FED kicked the can until March… do we have more lows to come ? Probably, but the risk vs. reward is becoming too risky for me in the near future. I’ll be in and out of volitilaty, but I’m not holding any options too long. Just my .02 good luck to all :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:10:37 </td>
   <td style="text-align:left;"> $SPY it is fake again, tommorow we lose again 5 points </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:10:35 </td>
   <td style="text-align:left;"> $SPY dont even bother til tomorrow around 7:30am </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:10:27 </td>
   <td style="text-align:left;"> $SPY so we got inflation numbers and normal Friday sell off tomorrow? I’m pretty beaaarish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:10:10 </td>
   <td style="text-align:left;"> $SPY Nice </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:10:02 </td>
   <td style="text-align:left;"> $SPY bottom is in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:09:59 </td>
   <td style="text-align:left;"> $SPY bulls girlfriend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:09:53 </td>
   <td style="text-align:left;"> Even looking at SPY to VIX ratios here (top pane) has seen, where $SPY starts to lose R/S against VIX, sellers move in and the market rolls over..  👀   
(looking at shorter-term moves) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:09:48 </td>
   <td style="text-align:left;"> $SPY how’s the casino doing? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:09:36 </td>
   <td style="text-align:left;"> $SPY 🚀🚀🚀🚀🚨🚀🚀🚀🚀🚨🚀🚀🚀🚀🚨 futures going INSANE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:09:10 </td>
   <td style="text-align:left;"> $SPY Holy shit! They still haven’t figured it out! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:09:00 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:08:47 </td>
   <td style="text-align:left;"> $SPY Ripping hard AF. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:08:43 </td>
   <td style="text-align:left;"> $SPY Putting money in anything not named Apple or Microsoft isn&amp;#39;t &amp;quot;investing&amp;quot;.

It&amp;#39;s a donation to quant hedge funds. 

This is one of the first times in my life that I truly feel the market is rigged. Names going down faster than at any point in history and it&amp;#39;s not just because of selling. 

It&amp;#39;s because a small group of talented Algo fund managers literally pillaging every retail donor on the planet. 

Complete horse </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:08:36 </td>
   <td style="text-align:left;"> $SPY Cramer is bullish on oil and bearish on ark, guy&amp;#39;s always late to the party, pathetic performance. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:08:34 </td>
   <td style="text-align:left;"> $SPY Going to be some really good sales in the near future I can see the headlines now &amp;quot;spring savings&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:08:33 </td>
   <td style="text-align:left;"> $SPY bears girlfriends every night. They like 🏆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:08:31 </td>
   <td style="text-align:left;"> It seems simple - it’s all about the overnight sessions - bears get absolutely raped if they hold overnight because just like all of 2021 the bulls control markets during futures sessions as they can get way more bang for their buck during the low liquidity of overnight sessions $spy $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:08:08 </td>
   <td style="text-align:left;"> $SPY Is the bottom in … yes or no. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:07:55 </td>
   <td style="text-align:left;"> $SPY Hey </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:07:54 </td>
   <td style="text-align:left;"> $SPY why I’m showing you guys this clip is because one of my followers who’s not even on ST yet says, “when he thinks of a broker and a teacher, he thinks of josh(me)…josh  is obviously not the broker”

https://youtu.be/KvITs5E5zv4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:07:54 </td>
   <td style="text-align:left;"> $SPY “green” but way down from earlier today lolll </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:07:34 </td>
   <td style="text-align:left;"> $SPY 143 at 4350 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:07:29 </td>
   <td style="text-align:left;"> $SPY nice move in futures but need to hold 435 in cash session and break 441 we will see tommorrow, at least we don&amp;#39;t have to deal with an apple dump er. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:07:27 </td>
   <td style="text-align:left;"> $SPY you know futes do seem to be futing a bit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:07:16 </td>
   <td style="text-align:left;"> $SPY so we got inflation numbers and normal Friday sell off tomorrow? I’m pretty beaaarish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:07:15 </td>
   <td style="text-align:left;"> $SPY Futes green?!?!? WUAH?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:07:04 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;ll be a bull next week tbh. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:06:54 </td>
   <td style="text-align:left;"> $SPY futures green again... not that is really helps 🙈🤷‍♀️🤯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:06:49 </td>
   <td style="text-align:left;"> $SPY this has essentially traded almost $10 up and down nearly everyday to be exactly in the same price range for the whole week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:06:48 </td>
   <td style="text-align:left;"> $SPY full boat of $442 calls expiring tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:06:46 </td>
   <td style="text-align:left;"> $SPY expecting a decent bounce back over the next few trading sessions. Godspeed 🍻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:06:24 </td>
   <td style="text-align:left;"> $SPY Hey bulls, back in the trenches sooner than you think. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:06:22 </td>
   <td style="text-align:left;"> $SPY check out $TONIC.X  it’s running hard just dropped a zero 🔥🔥🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:06:21 </td>
   <td style="text-align:left;"> $SPY Truly a perfect summary of stonktwits. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:06:01 </td>
   <td style="text-align:left;"> $SPY bears are only good for one job </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:05:57 </td>
   <td style="text-align:left;"> $SPY we up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:05:39 </td>
   <td style="text-align:left;"> $SPY I don&amp;#39;t know how to interpret moo making alts like Sonicbull. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:05:35 </td>
   <td style="text-align:left;"> $SPY futures ripin LOL Love it and -6% close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:05:32 </td>
   <td style="text-align:left;"> latexef2e122a44071d3a3f08e5d682b6a26caapl goes nuts insane quarter despite supply problems oh my  
 
$spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:05:30 </td>
   <td style="text-align:left;"> $SPY they put Martha Stewart in jail for her little inside trading. What should happen to the Pelosis and Griffins 🧐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:05:16 </td>
   <td style="text-align:left;"> $SPY how are we. I hedged with the uvxy just for day. The spy options weren’t available late </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:05:15 </td>
   <td style="text-align:left;"> $SPY why you so…! Bear </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:05:12 </td>
   <td style="text-align:left;"> $SPY what the hell happened towards close any news? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:04:48 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ tomorrow morning will be charitable </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:04:45 </td>
   <td style="text-align:left;"> $SPY longest business cycle in history! 
you call that a drop? Strap in we can go much much lower as you buy the dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:04:45 </td>
   <td style="text-align:left;"> $SPY $AAPl until the US Fed Meeting in March..  Full truck loads incoming!!   #Overtime hours   $TLT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:04:43 </td>
   <td style="text-align:left;"> $SPY $UVXY If you take yourself seriously, you run the risk of being alone, seriously. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:04:39 </td>
   <td style="text-align:left;"> $SPY $440 open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:04:34 </td>
   <td style="text-align:left;"> $SPY haha bear trap 🅿️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:04:21 </td>
   <td style="text-align:left;"> $SPY folks the party is over lol....why are you fighting it...you will lose most, if not everything </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:04:09 </td>
   <td style="text-align:left;"> $SPY  
 
SPY  Rough trading day - looking for a rebound tomorrow. Will be watching closely in pre-market. It is still one of the top trending tickers on Twitter and StockTwits - with over 5 million impressions in the last 24hrs. 
 
Wanted to share the tool we built so you can track social and price trends in real-time. Gives you a  good view of what&amp;#39;s going on in the market. 
 
https://utradea.com/social-dashboard?utm_source=stocktwits&amp;amp;utm_medium=ssd-stocktwits&amp;amp;utm_campaign=sm_20220127 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:04:01 </td>
   <td style="text-align:left;"> $SPY Nikkei is blowing as I said before over 440 easily </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:03:43 </td>
   <td style="text-align:left;"> $SPY What&amp;#39;s causing the futes to rip? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:03:37 </td>
   <td style="text-align:left;"> $SPY Enjoy this crazy rally we’re about to get. It could be the last one for a while </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:03:32 </td>
   <td style="text-align:left;"> $SPY 🍿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:03:28 </td>
   <td style="text-align:left;"> $SPY lol Tim just said fuk yo puts I’ll save the market if Jpow can’t 🤤🏆🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:03:24 </td>
   <td style="text-align:left;"> $SPY Short again 4345 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:03:07 </td>
   <td style="text-align:left;"> $SPY what a boring day 🙄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:02:59 </td>
   <td style="text-align:left;"> $SPY It is funny to hear bulls are excited by GDP numbers and &amp;quot;good earnings&amp;quot;. This &amp;quot;health economy and market&amp;quot; was spared with 3.7 trillions of Cares Act. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:02:35 </td>
   <td style="text-align:left;"> $SPY What numbers are coming out in the morning? CPI? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:02:34 </td>
   <td style="text-align:left;"> $SPY noooo way theseeee gaiinnnsssa hold lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:02:30 </td>
   <td style="text-align:left;"> $QQQ $SPY the fed put a time bomb on yield implosion where does all that money go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:02:08 </td>
   <td style="text-align:left;"> $SPY Watch Asia take over 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:01:56 </td>
   <td style="text-align:left;"> $SPY lol All you Gen Y’ers gonna have a hard time finding a job when your port falls through because Boomers retirement accounts got fucking liquidated trying to play options. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:01:44 </td>
   <td style="text-align:left;"> $SPY bulls who bought at the top are now turning to bears, uno reverse soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:01:43 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:01:41 </td>
   <td style="text-align:left;"> $SPY Tim Apple gave us a lemon 🍋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:01:14 </td>
   <td style="text-align:left;"> $SPY No matter what the play, I&amp;#39;m a clown </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:01:12 </td>
   <td style="text-align:left;"> $SPY take it in
https://music.youtube.com/watch?v=SehI6DE6B6s&amp;amp;feature=share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:01:09 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures gaining momentum here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:01:04 </td>
   <td style="text-align:left;"> $AAPL sadly the fact that they didn’t have guidance will def clap this. People are worried about the future not the past 😭 $SPY $QQQ but won’t be surprised from a slight rally Friday just to relief some of the oversold signals then Monday prob dumps more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:00:41 </td>
   <td style="text-align:left;"> $SPY Whats happening is these inexperienced retail investors are flipping out over $VTI while the FIRE boys are throwing up in the toilet because passive investing doesn&amp;#39;t work.  
 
People!  Passive investing is the APEX of untrying.  Remember that.  Nobody gets rewarded for putting their investment life on autopilot. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:00:41 </td>
   <td style="text-align:left;"> $SPY when futures open this will will tank </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:00:40 </td>
   <td style="text-align:left;"> Very interesting pennant building on the short term time frames for the $VX_F $VIX futures. We could be in so a major move Friday… not to mention the wedge building on the indexes daily’s $SPY $QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:00:17 </td>
   <td style="text-align:left;"> $SPY Should open at 442ish and then RIP up to 450

🙂🙂📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 09:00:05 </td>
   <td style="text-align:left;"> $SPY Hey bull did you do it? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:59:48 </td>
   <td style="text-align:left;"> $SPY paperhands boomers finally went to bed I guess. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:59:46 </td>
   <td style="text-align:left;"> $SPY Japan recovered. China should rocket. May see 3% tomorrow. Who knows and who really cares </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:59:34 </td>
   <td style="text-align:left;"> $SPY $BTC.X  is kendra lust on stocktwits? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:59:27 </td>
   <td style="text-align:left;"> $SPY $427 tomorrow would be lovely!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:59:24 </td>
   <td style="text-align:left;"> $SPY Clown Gang is turning agianst the Muppet Gang. Last time that happend was DotCom Bubble. 
Few understand this. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:59:21 </td>
   <td style="text-align:left;"> $SPY what the hell is going on? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:59:18 </td>
   <td style="text-align:left;"> $SPY 
These Bulls act like $AAPL earnings solved our inflation problem. 😂😂💀💀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:59:15 </td>
   <td style="text-align:left;"> $SPY damn bears fucked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:59:11 </td>
   <td style="text-align:left;"> $SPY lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:58:48 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $INTC Some Historical Perspective on the S&amp;amp;P 500 Index &amp;quot;Death Cross&amp;quot; | Nasdaq https://www.nasdaq.com/articles/some-historical-perspective-on-the-sp-500-index-death-cross </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:58:40 </td>
   <td style="text-align:left;"> $SPY if Japan index blows up tonight this goes to 440 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:58:23 </td>
   <td style="text-align:left;"> $SPY vol is diabolic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:58:11 </td>
   <td style="text-align:left;"> latexf449cf4c669e3c805b915f55d635156c 21% roi in profits since premarket Monday. All short trades on full margin, all profit, some more profitable than others, always holding overnight, not by choice, beauties included   tsla   f   hood   pton   ccl 🐻❤😈☠ Carry on following me for profits @Profit_Maker https://stocktwits.com/Profit_Maker your 24/7 short trading care bear specialist, thanks bulls for lending me your shares to short for profits at your expense ✔ Good health and trading to all 🕺 ... as a reminder I block all who imho jawbone stupid wasting my time and broadband 😜 Enjoy the Armageddon Depression, what a crash year 2022 it is going to be and beyond, so demented the economy and stock market rallies since 2009 have been in tandem with many socioeconomic concerns. 👍$djia $SPX $NDX $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:58:02 </td>
   <td style="text-align:left;"> $SPY COLORING IS VERY FUN. I FEEL LIKE I CAN MAKE A MILLION DOLLARS OFF OF MINES NOW. WOW. 10/10 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:57:59 </td>
   <td style="text-align:left;"> $SPY Japan recovered </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:57:56 </td>
   <td style="text-align:left;"> Wow what face ripper into the close?! So bulls do have it?! This market is fin crazy $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:57:53 </td>
   <td style="text-align:left;"> $DIA $QQQ $SPY pretty clear we are going to sit herr and chop it up a bit in all the indices until one decides to make a sharp move north or the gain enough room on the RSIs to drop so more. Either way we shall see with all the bullshit goin around us. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:57:27 </td>
   <td style="text-align:left;"> $SPY at least it&amp;#39;s not following btc anymore lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:57:17 </td>
   <td style="text-align:left;"> $SPY this thing has been basically flat all week and everybody on all sides are cheering whenever it goes either red or green it’s hilarious </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:57:10 </td>
   <td style="text-align:left;"> $SPY $QQQ pretty sure $AAPL just put a short term floor under the indexes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:57:05 </td>
   <td style="text-align:left;"> $SPY THE BEST RENDITION https://music.youtube.com/watch?v=nmwW44xkfxI&amp;amp;feature=share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:56:21 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL Friday $421 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:56:10 </td>
   <td style="text-align:left;"> $SPY Short ES at intraday VWAP. Simple. Profitable. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:55:57 </td>
   <td style="text-align:left;"> $SPY that&amp;#39;s a diamond bottom formation right there.. a directional change primed for a pop tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:55:53 </td>
   <td style="text-align:left;"> $SPY fuckin apple saved this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:55:46 </td>
   <td style="text-align:left;"> $SPY lol... imagine market will hold because of apple... praising the obvious inflation  Apple earnings beat with no guidance. You like the lip service by China worshipping Tim Cook on supply chain constraints? LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:55:45 </td>
   <td style="text-align:left;"> $SPY she’s international now 🤣 a diplomatic gem will learn on Honduras then Russia 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:55:21 </td>
   <td style="text-align:left;"> $QQQ $SPY $UVXY $SVXY  
 
Those unfamiliar, SVXY is an inverse short term vix futures etf.  
 
That M shaped cliff looks nasty. It&amp;#39;s sitting right at the neckline. , RSI is divergent. It&amp;#39;s looking like VIX will continue higher. There are so many bad signals right now, I don&amp;#39;t believe a word the news says about having a good second half of the year, unless they&amp;#39;re referring to the massive bull trap rally that could happen before the big crash. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:55:15 </td>
   <td style="text-align:left;"> $SPY like this if you hate the new format after the update </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:55:01 </td>
   <td style="text-align:left;"> $SPY $APPL 166.60 price action is a bad sign </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:54:50 </td>
   <td style="text-align:left;"> $SPY Go take a piss and futes go from .1% to .4%. Jeez la weez papa cheez </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:54:47 </td>
   <td style="text-align:left;"> $VXX $IWM $SPY inflation FUD is over now WallStreet idiots start rambling abut deflation 🤦🏻

 https://seekingalpha.com/article/4482202-the-danger-is-deflation-not-inflation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:54:34 </td>
   <td style="text-align:left;"> $SPY $AAPL Bullish on these two. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:54:33 </td>
   <td style="text-align:left;"> $SPY just incase you did not hear it properly.... 
the fed is still buying....... 
or we would have crashed hard by now..... 
they are easing it down....... 
as not to upset anyone to much at once.... 
as they know most are kitty cats </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:54:33 </td>
   <td style="text-align:left;"> $BTC.X $SPY $NASDAQ Russia just put a ship over the under water fiber optics the supply 97% of the internet comms from us to Europe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:54:33 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:54:28 </td>
   <td style="text-align:left;"> $SPY since market has so much fear and there’s more bearish sentiment than bullish I bought calls 👌🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:54:11 </td>
   <td style="text-align:left;"> $SPY Apple just saved futures at the low </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:53:40 </td>
   <td style="text-align:left;"> $SPY nice drop onto spy and making the strangle print 🙏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:53:31 </td>
   <td style="text-align:left;"> $SPY AM I DOING THIS RIGHT BEARS? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:53:24 </td>
   <td style="text-align:left;"> $SPY tomorrow puts are going to fooked up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:53:09 </td>
   <td style="text-align:left;"> $SPY Amazing but it looks like we could do a third straight day of identical movement .

Biden: Making market volatility great again.

PCE likely tempers that pattern.
Wait, &amp;quot;tempers,&amp;quot; is not right word. 

How about inflates the pattern,  to the downside

$QQQ $AAPL $KLAC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:53:08 </td>
   <td style="text-align:left;"> $SPY Lucky 8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:52:50 </td>
   <td style="text-align:left;"> $SPY $QQQ Investor sentiment  
 
https://twitter.com/MacroCharts/status/1486670324351463428 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:52:46 </td>
   <td style="text-align:left;"> $SPY you people are fucking weird. All 9 of you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:52:19 </td>
   <td style="text-align:left;"> $SPY Will you go long if you get the $420 Double Bottom chance? Think about it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:52:10 </td>
   <td style="text-align:left;"> $SPY Got YOLO 415 puts that close tomorrow.....here&amp;#39;s to lambo or homeless </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:52:10 </td>
   <td style="text-align:left;"> $SPY about to bend and open second butthole for you degenerate V conditioned buyers. Today fute is sell the rip. Fuck your calls. $qqq $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:51:57 </td>
   <td style="text-align:left;"> $SPY Imagine being threatened by a Senile Clown. 
You think Putin or China will take this idiot or the rest of the cucks in DC and Europa as a scare. 
This dumb fck left 80 billion in U.S. Assets to a small group of Terrorist. But hell take on Russia and China. 
Soumds like Obama talking big just to back down like a btch. Imho. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:51:56 </td>
   <td style="text-align:left;"> $SPY This market contains many of our hopes and dreams. 

Will you be able to grab yours? 

It takes discipline and education. You gotta learn what works, and then learn what works best for you! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:51:51 </td>
   <td style="text-align:left;"> $SPY 

Too many folks staying home and 
“Trading “”

Ok mr president I will crash the markets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:51:48 </td>
   <td style="text-align:left;"> $SPY bulls were excited earlier💀 I knew it would drop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:51:47 </td>
   <td style="text-align:left;"> $SPY I wish my broker would hurry up and get the tax forms done. I need that $2k return to blow on weeklies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:51:45 </td>
   <td style="text-align:left;"> $SPY I just woke up it’s 2024, nope not yet, still got 1 year and 11 months and 4 days. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:51:27 </td>
   <td style="text-align:left;"> $TSLA Tesla had $1.26 billion in bitcoin at the end of quarter.  Since Bitcoin lost 40% value since then, that 1.26 billion is now closer to $800 million.   Tesla will take a hit next earnings unless bitcoin bounces bigly.  $BTC.X $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:51:01 </td>
   <td style="text-align:left;"> $SPY all bulls get a free u2 digital album download </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:50:56 </td>
   <td style="text-align:left;"> $SPY I think it’s gonna double bottom.  Will wait to confirm before I buy. Can’t get excited though because they’ll probably slow-walk it down to 3800 by fall </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:50:56 </td>
   <td style="text-align:left;"> $HOOD maybe $SPY bottoms when this goes under. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:50:52 </td>
   <td style="text-align:left;"> $SPY $AFRM $IPOF Account Challenge Update: 
Start Dec 30,2021 
Starting: $5,000 
Current: $85,212 
Goal: $100,000 by end of January 
Strategy: Swing Trade Options, Stocks 
 
Watch out for next pay👀, discord.io/ongoing_alerts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:50:39 </td>
   <td style="text-align:left;"> $SPY  $QQQ  These shits aint holding nothing up and that little fake pump on $AAPL aint fooling anyone. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:50:37 </td>
   <td style="text-align:left;"> $SPY dump dump…. Worthless market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:50:15 </td>
   <td style="text-align:left;"> $QQQ $SPY I&amp;#39;m still waiting on a proper bounce to short in to..go back 2020 COVID crash, then the 2018 correction then end of year nosedive, then before that to 2015 drop..all at least had some hard upside bounces before the next leg down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:49:58 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:49:55 </td>
   <td style="text-align:left;"> $SPY SINK IN THIS
JUST GOVE IT A SHOT
https://music.youtube.com/watch?v=Y6QrwosStLc&amp;amp;feature=share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:49:42 </td>
   <td style="text-align:left;"> $SPY let me make this clear before we kick off the night. Futes aren’t going to determine how the markets go tomorrow at 8:01pm lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:49:41 </td>
   <td style="text-align:left;"> $QQQ $SPY Both of you&amp;#39;s are going to the shit house tomorrow. Not even $AAPL can save you. 🔻🚽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:49:38 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:49:32 </td>
   <td style="text-align:left;"> $BTC.X $ETH.X $TSLA $SPY 
As an observer from the great white north… I must say, your country isn’t short of entertainment this last week. Heading to zero,  and most are happy to bring the system down. Also-
“BUT wE HaVENO VACCINe ManDATES”
what a shit show. Sheesh. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:49:27 </td>
   <td style="text-align:left;"> $SPY Still haven&amp;#39;t closed under Mondays low, let the games continue this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:49:16 </td>
   <td style="text-align:left;"> $SPY bears VERY cocky for all GREEN FUTES !!!!!!

🤡🤡📈🙂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:49:08 </td>
   <td style="text-align:left;"> $SPY need to retest 52 week low </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:49:03 </td>
   <td style="text-align:left;"> $SPY Damn someone is buying the dip in futes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:48:57 </td>
   <td style="text-align:left;"> $SPY I suggest the Longs stop trading stocks and take up knitting ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:48:20 </td>
   <td style="text-align:left;"> $SPY  It&amp;#39;s nice when she doesn&amp;#39;t drop her pants too fast at the end of the night </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:48:12 </td>
   <td style="text-align:left;"> $SPY  $AAPL gettin a boner after hours </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:47:54 </td>
   <td style="text-align:left;"> $SPY $QQQ Friday Selloff </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:47:54 </td>
   <td style="text-align:left;"> $SPY futures are very peculiar, gifted 30 handles out of the gate and has been bleeding ever since </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:47:43 </td>
   <td style="text-align:left;"> $SPY fill that 400.67 gap already </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:47:25 </td>
   <td style="text-align:left;"> $SPY Putin ain’t doing anything before olympics. He wouldn’t do that to his good friend next door. They will both do it the same time to overwhelm NATO after. We sink then </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:47:21 </td>
   <td style="text-align:left;"> $SPY when is the next reverse split? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:47:15 </td>
   <td style="text-align:left;"> $SPY is S&amp;amp;P 5000 still going to happen this year or not anymore??? Asking for a friend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:47:02 </td>
   <td style="text-align:left;"> $SPY How are bulls going to explain to all your loved ones you squandered your 2021 gains on spy calls this month....give me your story lines </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:46:58 </td>
   <td style="text-align:left;"> $SPY hopefully we get a nice pop to short. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:46:55 </td>
   <td style="text-align:left;"> $AAPL $QQQ $SPY any price movement not in the interest of my positions is targeted manipulation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:46:28 </td>
   <td style="text-align:left;"> $SPY Futes are about to turn red . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:46:26 </td>
   <td style="text-align:left;"> $SPY the markets just got fucked by the Asian trades blood bath Japan and hongkong </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:46:12 </td>
   <td style="text-align:left;"> $SPY Short this garbage. Wheres OLDFNGGUY. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:46:10 </td>
   <td style="text-align:left;"> $SPY $SPX $VIX  
 
The Option Market has been building (hedge) a big floor  
(gamma wall/magnet) on SPY at the 425 strike (and below) for the following weekly OpExs through the &amp;#39;Feb 18 Monthly OpEx&amp;#39;.  
 
The 420-425 area on SPY held strong on Monday. 
 
------------- </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:46:01 </td>
   <td style="text-align:left;"> $SPY interesting close so far </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:45:55 </td>
   <td style="text-align:left;"> $SPY ES1 15min 50ma rejected </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:45:40 </td>
   <td style="text-align:left;"> $SPY After Hours price movement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:45:35 </td>
   <td style="text-align:left;"> $SPY at this point I go to casino and do better </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:45:19 </td>
   <td style="text-align:left;"> $SPY @OldFngGuy is dead, I heard it through the grapevine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:44:42 </td>
   <td style="text-align:left;"> $SPY the 2020 crash was the greatest transfer of wealth in human history.  they will try to do it again.  be ready for it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:44:39 </td>
   <td style="text-align:left;"> $SPY can’t get above the 200ma.  NOT. GOOD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:44:35 </td>
   <td style="text-align:left;"> $SPY Bulls are telling me 430 is the bottom but @OldFngGuy hasn&amp;#39;t told me to buy the dip and other big $$ VIX contango math yet. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:44:28 </td>
   <td style="text-align:left;"> $SPY short 10 jan 28 430 puts and.... that&amp;#39;s about it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:44:11 </td>
   <td style="text-align:left;"> $SPY We haven’t even touched the monthly 20MA. Relax. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:44:09 </td>
   <td style="text-align:left;"> $ARKK $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:44:08 </td>
   <td style="text-align:left;"> $AAPL $SPY $MSFT Inverse Expectations 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:44:06 </td>
   <td style="text-align:left;"> $SPY futes rippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:44:04 </td>
   <td style="text-align:left;"> $SPY The corona crash of 2020 was a -35% loss on the SPY to the bottom.  Right now we are right at -10%.  If Bulls don&amp;#39;t step in tomorrow, SPY is going a lot lower over the next few weeks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:43:58 </td>
   <td style="text-align:left;"> $SPY wouldn&amp;#39;t be surprised if this opens green af tomorrow. Retail puts going to get bamboozled again? BTW I have puts overnight. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:43:54 </td>
   <td style="text-align:left;"> $ARKK $SPX $SPY 

Let&amp;#39;s talk about the current $ARK Investment Management LLC  ETF stock - latex7454dbe8dc0ba9d5aea3ea84376130adARKK went up 151% in 308 days after the buy signals.
👉$ARKK dropped around 47% after the sell signals. Our members saved 47%!
👉 $ARKK also dropped 57% from its ATH. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:43:45 </td>
   <td style="text-align:left;"> $SPY All the great companies are delivering great earnings, but the market continues to tank on TWO manufactured issues 1) POTENTIAL war with Russia 2) POTENTIAL rate hike.   NONE has happened yet, but market is fearful.  It&amp;#39;s all designed to crash the market without engaging in a war or rate hike.  $QQQ  $UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:43:44 </td>
   <td style="text-align:left;"> $SPY legitimately afraid to wake up in the morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:43:44 </td>
   <td style="text-align:left;"> $SPY will we close AH negative?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:43:44 </td>
   <td style="text-align:left;"> $SPY ohhh futes cmon papi </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:43:43 </td>
   <td style="text-align:left;"> $AAPL $SPY anyone else think peak earnings for awhile? Or wage increases gonna help out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:43:43 </td>
   <td style="text-align:left;"> $SPY burn and spiral. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:43:29 </td>
   <td style="text-align:left;"> $SPY oh lawd we fading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:43:25 </td>
   <td style="text-align:left;"> $SPY house of cards market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:43:22 </td>
   <td style="text-align:left;"> $SPY 

Gonna diverge from $cook ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:43:21 </td>
   <td style="text-align:left;"> $SPY lmfao so many head fakes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:43:11 </td>
   <td style="text-align:left;"> $SPY i hope you guys put money aside for taxes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:43:09 </td>
   <td style="text-align:left;"> $SPY 360-310 by September 🤝 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:43:00 </td>
   <td style="text-align:left;"> $SPY Fraud St wants lower prices </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:42:56 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;m hoping for market crash caused by unicorn and popcorn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:42:40 </td>
   <td style="text-align:left;"> $SPY more continuation of the trend or a breakout/down tomorrow boys? Last candle is telling me the latter 😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:42:38 </td>
   <td style="text-align:left;"> $SPY Prediction for tomorrow. Opens under 430, and it will touch 420 again. If so, Monday we’ll see another new low. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:42:31 </td>
   <td style="text-align:left;"> $AAPL $QQQ $TSLA  $SPY 

Chief Executive Tim Cook said Thursday that despite ongoing issues affecting the availability of supplies used in some of its products, the company is still managing to turn in the strongest sales in its history 💎🍏💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:42:19 </td>
   <td style="text-align:left;"> $SPY Futures from deep red to green this morning. I’m sensing the opposite when we wake up tomorrow. Unless an AAPL ER is that powerful </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:42:10 </td>
   <td style="text-align:left;"> $SPY man is the housing market in a bubble? I’m seeing 50% returns compared to last year in my city </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:42:10 </td>
   <td style="text-align:left;"> $SPY My YouTube financial advisor is telling me we&amp;#39;re fine. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:42:00 </td>
   <td style="text-align:left;"> $SPY I remember yesterday futures down 300 woke up to up 300 no one knows . Night </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:41:50 </td>
   <td style="text-align:left;"> $QQQ $SPY will ackman have a commercial during the super bowl to tell us he bought netflix?..I&amp;#39;ve only seen it 1k times today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:41:46 </td>
   <td style="text-align:left;"> $SPY let’s goo 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:41:37 </td>
   <td style="text-align:left;"> $SPY is going to 360-370 faster the better. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:41:32 </td>
   <td style="text-align:left;"> $AAPL Apple gets the love even with their lower guidance for &amp;quot;slower&amp;quot; development.  In the mean time, $NFLX beats and delivers all metrics and says &amp;quot;slower growth of subscribers&amp;quot; and stock plummets 28%.   Netflix would&amp;#39;ve dropped even if they raised guidance because the market is rigged.  $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:41:25 </td>
   <td style="text-align:left;"> $SPY Ok let’s hear em’. What’s tomorrow’s open? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:41:15 </td>
   <td style="text-align:left;"> $SPY 380 febuary. 200 march. 🤗 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:41:11 </td>
   <td style="text-align:left;"> $SPY it looks like the Apple pop almost all faded . That was surprisingly quicker than I thought . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:41:03 </td>
   <td style="text-align:left;"> $SPY Happy....this will break  420 shortly and head to 365 before a bottom. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:40:59 </td>
   <td style="text-align:left;"> $SPY These futures are super predictable man maybe i should open up a futures account </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:40:47 </td>
   <td style="text-align:left;"> $SPY $AAPL $INDO $TSLA $QQQ If you really want to make huge profits on trading then, Join this winning chat discord.io/MqakycG 
 
 
##01 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:40:38 </td>
   <td style="text-align:left;"> $SPY almost time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:40:27 </td>
   <td style="text-align:left;"> $SPY 425 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:40:20 </td>
   <td style="text-align:left;"> $SPY LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:40:09 </td>
   <td style="text-align:left;"> $TSLA $AAPL  $SPY   #1 in the world 💡💡💡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:40:00 </td>
   <td style="text-align:left;"> $IWM $BTC $NILE $SPY remember three words. &amp;quot;Mid Term Election&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:39:57 </td>
   <td style="text-align:left;"> $SPY can you bull dicks sustain a pump for more then 5 minutes tomorrow? Trying to get more Mar puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:39:35 </td>
   <td style="text-align:left;"> $SPY this is me in the convo but 390$ spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:39:27 </td>
   <td style="text-align:left;"> $SPY  this time crash is worsted than 2020 COVID crash. Do buy and hold sell same day close your position </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:39:24 </td>
   <td style="text-align:left;"> $SPY just give us spy 0 and start the human race all over again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:39:16 </td>
   <td style="text-align:left;"> $SPY Can we just eliminate Russia from the face of the earth already? My god </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:39:16 </td>
   <td style="text-align:left;"> $SPY Nikki s on fire bro. Aapl beat ! Monday was the bottom ! Bears are scared ! 100k bro Lambos moass </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:39:14 </td>
   <td style="text-align:left;"> $SPY monday will be the worst day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:39:11 </td>
   <td style="text-align:left;"> $SPY I have no idea why bulls don’t want 360-400 range? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:38:54 </td>
   <td style="text-align:left;"> $SPY face ripper drop to 410 tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:38:47 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA The futes are red right now, but once again the market can&amp;#39;t ignore great earnings! 👉 $AAPL  Green by morning bulls! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:38:28 </td>
   <td style="text-align:left;"> $SPY look for Asia to follow through on $AAPL earnings.   Gap up, then fade into closing.   Ain&amp;#39;t that the program now?  $UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:38:27 </td>
   <td style="text-align:left;"> $SPY stock analysis based on today&amp;#39;s closing price. Full analysis is available on youtube 

https://youtu.be/GopQIs_hVsE

Here is $spy snapshot at closing price </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:38:16 </td>
   <td style="text-align:left;"> $TSLA  $AAPL $SPY  That part !!! Tesla is the leading the race !!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:38:14 </td>
   <td style="text-align:left;"> $SPY Nikkie 225 is straight fire right now. Should bump up futes here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:38:12 </td>
   <td style="text-align:left;"> $SPY futures keep tumbling down. No one knows where the Fed put is. JPM adamantly thinks it’s at 4000. We shall see soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:37:58 </td>
   <td style="text-align:left;"> $SPY so no 445 tmr instead we get 400? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:37:56 </td>
   <td style="text-align:left;"> $SPY Apple earnings not saving this asset. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:37:53 </td>
   <td style="text-align:left;"> $AAPL $SPY $INTC There’s too many reasons why you shouldn’t invest right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:37:47 </td>
   <td style="text-align:left;"> $SPY Big move up to start the day then it goes down , coupke of days in a row …. everyone expects this tomorrow…. so you short it and make easy money ???😄i think it will do the opposite , up to start the day then higher close at the end 🚀that is my hope speaking . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:37:47 </td>
   <td style="text-align:left;"> $SPY market is so ducking terrible </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:37:38 </td>
   <td style="text-align:left;"> $SPY idk what y’all keep thinking we’re gonna crash.

50 EMA  still above 200
RSI is oversold
MACD is crossing
We keep trying to break 200 ema
EVERYONE is so damn bearish
Cramer is bearish
Russia and Ukraine is in negotiations
4-5 Rate hikes are priced in
ERs are great

Why the panic? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:37:38 </td>
   <td style="text-align:left;"> $SPY If they can pump the futures tonight, then I suspect tomorrow we could see a morning pump based on how the market responded to the AAPL earnings..   The reaction didn&amp;#39;t meet the earnings beat, (which shows the weakness in the market), but none the less the big sellers will want to pump the price of AAPL to get out higher.. And since AAPL moves the market, the index&amp;#39;s will move with it.   BUT if they cannot pump the futures, then get ready for more downside..  No matter if we open red or green,  I can see an end of day sell off.  The VIX is still high. And the DXY and US02Y both have a rocket booster attached to them.. Market doesn&amp;#39;t like any of the this.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:37:26 </td>
   <td style="text-align:left;"> $SPY if it was going to bounce it would have been today. Downward channel still in effect </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:36:56 </td>
   <td style="text-align:left;"> $ASTS $ORGN $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:36:54 </td>
   <td style="text-align:left;"> $SPY who died more?
Aborted babies or covid patients? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:36:44 </td>
   <td style="text-align:left;"> $SPY red soon. Change it up MM’s…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:36:41 </td>
   <td style="text-align:left;"> $SPY hanging by a thread. 🤪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:36:31 </td>
   <td style="text-align:left;"> $SPY  Expected Futes to be up substantially, times are changing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:36:30 </td>
   <td style="text-align:left;"> $SPY gonna wait until markets to close for futures to take it the direction wanted. Smh. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:36:27 </td>
   <td style="text-align:left;"> $SPY down to 300 on spy as soon as the first Russian soldier crosses the border of Ukraine . My prayers to all the lost souls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:36:25 </td>
   <td style="text-align:left;"> $SPY dead market….investing in this market is a losing game </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:36:24 </td>
   <td style="text-align:left;"> $DIA $SPY $QQQ Is the Fed crashing the market on purpose? This guy has a very good explanation of what is happening and also the reason I stay short the market overall this year:  
 
https://www.youtube.com/watch?v=lPUTG-THWoU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:36:20 </td>
   <td style="text-align:left;"> $SPY $UVXY $QQQ $DJIA 

Send this shit to the bottom of the ocean. All of it. I’ve been calling for this reset for a while— and UVXY going to make me a millionaire </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:36:09 </td>
   <td style="text-align:left;"> $SPY soon 450 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:36:09 </td>
   <td style="text-align:left;"> $SPY Putin is short ES </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:36:08 </td>
   <td style="text-align:left;"> $aapl $spy $qqq $ndx $xlk https://www.youtube.com/watch?v=ddEuU458vlw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:35:52 </td>
   <td style="text-align:left;"> $SPY bears getting hyped about priced-in news. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:35:49 </td>
   <td style="text-align:left;"> $SPY rolling over </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:35:46 </td>
   <td style="text-align:left;"> $SPY looks like another 1000% for 429P LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:35:40 </td>
   <td style="text-align:left;"> $SPY you know theres a war about to happen right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:35:18 </td>
   <td style="text-align:left;"> $SPY this market is a joke </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:35:15 </td>
   <td style="text-align:left;"> $SPY Maybe just a weird fact, spy making similar pattern on a weekly chart as 2020 march. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:35:13 </td>
   <td style="text-align:left;"> $SPY Market won&amp;#39;t recover until Sleepy Joe gives out more handouts.  Shows how weak Market has become. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:35:06 </td>
   <td style="text-align:left;"> $SPY Reality is setting it until everything (stocks) reset back to proper and verifiable valuations. Why would you be buying a company with triple digits PE ratio with little justification of profits margin? 28x of earnings? 🤔🤔🤔🤔🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:35:02 </td>
   <td style="text-align:left;"> $SPY Looks like were breaking $420 - probably Monday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:34:49 </td>
   <td style="text-align:left;"> $BTC.X 32k and $SPy 428 was support for pricing the first rate hike in. Market will start pricing the June hike in here in a week. Hold your pants. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:34:24 </td>
   <td style="text-align:left;"> $SPY does dave portnoy still trade? That guy must of lost so much money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-28 08:34:23 </td>
   <td style="text-align:left;"> $SPY Pelosi has to be getting crushed right now, all she buys is calls, and at the top no less. Didn’t she say she was running for re-election this past week? 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 09:14:54 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $BTC $AAPL  Volatility got the markets gas break dippin! Tell me when to Go tell me when to Goooo 📈📉📈📉📈📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 09:14:30 </td>
   <td style="text-align:left;"> $QQQ Red like cherry tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 09:14:00 </td>
   <td style="text-align:left;"> The technical rating of $QQQ is bad and it also does not present a quality setup at the moment. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 09:13:57 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $HOOD 

Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 09:13:51 </td>
   <td style="text-align:left;"> $SPY $QQQ Damn, I hope y&amp;#39;all are long! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 09:13:14 </td>
   <td style="text-align:left;"> $SPY $QQQ I think we will see a massive rally tomorrow because too many people are shorting now, they will have to cover with the weekend coming up . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 09:11:15 </td>
   <td style="text-align:left;"> $SPY $IWM $QQQ $RBLX $SHOP  
 
https://www.financegreater.com/post/managing-a-bearish-market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 09:11:04 </td>
   <td style="text-align:left;"> All future bounces are a chance to sell. Fed Put no longer a factor, Powell&amp;#39;s focused on inflation to protect POTUS ratings. 🐻 markets call for selling ALL $SPY  $QQQ  $DJIA  &amp;amp; $AAPL  included. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 09:06:44 </td>
   <td style="text-align:left;"> $QQQ Japan’s fake market boutta shoot up 4% or some shit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 09:05:49 </td>
   <td style="text-align:left;"> $QQQ futures are green!!! 🤪🤪🤪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 09:05:33 </td>
   <td style="text-align:left;"> Post-effective amendment [Rule 485(b)] https://www.conferencecalltranscripts.com/summary/?id=10363512 $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 09:04:48 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ tomorrow morning will be charitable </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 09:03:28 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-01-27 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=qNJxPJWLscU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 09:03:01 </td>
   <td style="text-align:left;"> $AAPL $MSFT $QQQ load the hell upppp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 09:02:30 </td>
   <td style="text-align:left;"> $QQQ $SPY the fed put a time bomb on yield implosion where does all that money go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 09:02:12 </td>
   <td style="text-align:left;"> $TSLA $QQQ  there&amp;#39;s more Volatility here than in a Strippers bank account balance </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 09:01:09 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures gaining momentum here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 09:01:04 </td>
   <td style="text-align:left;"> $AAPL sadly the fact that they didn’t have guidance will def clap this. People are worried about the future not the past 😭 $SPY $QQQ but won’t be surprised from a slight rally Friday just to relief some of the oversold signals then Monday prob dumps more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 09:00:40 </td>
   <td style="text-align:left;"> Very interesting pennant building on the short term time frames for the $VX_F $VIX futures. We could be in so a major move Friday… not to mention the wedge building on the indexes daily’s $SPY $QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:58:48 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $INTC Some Historical Perspective on the S&amp;amp;P 500 Index &amp;quot;Death Cross&amp;quot; | Nasdaq https://www.nasdaq.com/articles/some-historical-perspective-on-the-sp-500-index-death-cross </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:58:13 </td>
   <td style="text-align:left;"> latexb6d24c13c9a8e2df55a8d1f07d63d132 21% roi in profits since premarket Monday. All short trades on full margin, all profit, some more profitable than others, always holding overnight, not by choice, beauties included   tsla   f   hood   pton   ccl 🐻❤😈☠ Carry on following me for profits @Profit_Maker https://stocktwits.com/Profit_Maker your 24/7 short trading care bear specialist, thanks bulls for lending me your shares to short for profits at your expense ✔ Good health and trading to all 🕺 ... as a reminder I block all who imho jawbone stupid wasting my time and broadband 😜 Enjoy the Armageddon Depression, what a crash year 2022 it is going to be and beyond, so demented the economy and stock market rallies since 2009 have been in tandem with many socioeconomic concerns. 👍$djia $SPX $NDX $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:57:56 </td>
   <td style="text-align:left;"> Wow what face ripper into the close?! So bulls do have it?! This market is fin crazy $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:57:53 </td>
   <td style="text-align:left;"> $DIA $QQQ $SPY pretty clear we are going to sit herr and chop it up a bit in all the indices until one decides to make a sharp move north or the gain enough room on the RSIs to drop so more. Either way we shall see with all the bullshit goin around us. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:57:10 </td>
   <td style="text-align:left;"> $SPY $QQQ pretty sure $AAPL just put a short term floor under the indexes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:56:21 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL Friday $421 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:55:21 </td>
   <td style="text-align:left;"> $QQQ $SPY $UVXY $SVXY  
 
Those unfamiliar, SVXY is an inverse short term vix futures etf.  
 
That M shaped cliff looks nasty. It&amp;#39;s sitting right at the neckline. , RSI is divergent. It&amp;#39;s looking like VIX will continue higher. There are so many bad signals right now, I don&amp;#39;t believe a word the news says about having a good second half of the year, unless they&amp;#39;re referring to the massive bull trap rally that could happen before the big crash. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:54:11 </td>
   <td style="text-align:left;"> $QQQ As it turns out, during so-called rate-hike periods, which we seem set to enter into as early as March, the market tends to perform strongly, not poorly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:53:09 </td>
   <td style="text-align:left;"> $SPY Amazing but it looks like we could do a third straight day of identical movement .

Biden: Making market volatility great again.

PCE likely tempers that pattern.
Wait, &amp;quot;tempers,&amp;quot; is not right word. 

How about inflates the pattern,  to the downside

$QQQ $AAPL $KLAC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:52:50 </td>
   <td style="text-align:left;"> $SPY $QQQ Investor sentiment  
 
https://twitter.com/MacroCharts/status/1486670324351463428 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:52:10 </td>
   <td style="text-align:left;"> $SPY about to bend and open second butthole for you degenerate V conditioned buyers. Today fute is sell the rip. Fuck your calls. $qqq $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:50:39 </td>
   <td style="text-align:left;"> $SPY  $QQQ  These shits aint holding nothing up and that little fake pump on $AAPL aint fooling anyone. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:50:15 </td>
   <td style="text-align:left;"> $QQQ $SPY I&amp;#39;m still waiting on a proper bounce to short in to..go back 2020 COVID crash, then the 2018 correction then end of year nosedive, then before that to 2015 drop..all at least had some hard upside bounces before the next leg down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:49:41 </td>
   <td style="text-align:left;"> $QQQ $SPY Both of you&amp;#39;s are going to the shit house tomorrow. Not even $AAPL can save you. 🔻🚽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:48:25 </td>
   <td style="text-align:left;"> $TSLA $BTC.X $QQQ

$900 calls might print who fucking knows in this market. Elon is unpredictable and might have some cards he’s ready to play. 
 
Either way I have learned to love the chaos. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:48:18 </td>
   <td style="text-align:left;"> $QQQ Man bears are SO frothy right now.  
 
It took just 8 weeks for them to reach full euphoria mode. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:47:54 </td>
   <td style="text-align:left;"> $SPY $QQQ Friday Selloff </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:46:55 </td>
   <td style="text-align:left;"> $AAPL $QQQ $SPY any price movement not in the interest of my positions is targeted manipulation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:43:50 </td>
   <td style="text-align:left;"> $AAPL $MSFT $AMD $QQQ

Margin Just called again, he wasn&amp;#39;t friendly this time though; he last time said, &amp;quot;It&amp;#39;s important.&amp;quot; 
I said, &amp;quot;you&amp;#39;d be home in 15 minutes. And, it&amp;#39;s almost as if he was watching his watch for exactly 15 minutes.&amp;quot;

Yeah, K, I am almost home and---&amp;quot;Honey, just sec, phone ringing, OH,  it&amp;#39;s Margin Just&amp;#39;s caller ID again.&amp;quot; 

YEAH, honey, I&amp;#39;m at the bank, I was wondering, do you have any money on..... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:43:45 </td>
   <td style="text-align:left;"> $SPY All the great companies are delivering great earnings, but the market continues to tank on TWO manufactured issues 1) POTENTIAL war with Russia 2) POTENTIAL rate hike.   NONE has happened yet, but market is fearful.  It&amp;#39;s all designed to crash the market without engaging in a war or rate hike.  $QQQ  $UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:42:32 </td>
   <td style="text-align:left;"> $QQQ $DIA $TSLA Account Challenge Update: 
Start Dec 30,2021 
Starting: $5,000 
Current: $80,212 
Goal: $100,000 by end of January 
Strategy: Swing Trade Options, Stocks 
 
Watch out for next pay👀, discord.io/ongoing_alerts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:42:31 </td>
   <td style="text-align:left;"> $AAPL $QQQ $TSLA  $SPY 

Chief Executive Tim Cook said Thursday that despite ongoing issues affecting the availability of supplies used in some of its products, the company is still managing to turn in the strongest sales in its history 💎🍏💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:41:50 </td>
   <td style="text-align:left;"> $QQQ $SPY will ackman have a commercial during the super bowl to tell us he bought netflix?..I&amp;#39;ve only seen it 1k times today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:40:47 </td>
   <td style="text-align:left;"> $SPY $AAPL $INDO $TSLA $QQQ If you really want to make huge profits on trading then, Join this winning chat discord.io/MqakycG 
 
 
##01 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:39:18 </td>
   <td style="text-align:left;"> $QQQ Lmfao...they really about to close this right on support? Has been the battleground all week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:39:05 </td>
   <td style="text-align:left;"> $QQQ  grantee by next Friday this index  will be up 5% or more. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:39:04 </td>
   <td style="text-align:left;"> $QQQ January is coming to an end. I’m starting to load up for February bounce. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:38:47 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA The futes are red right now, but once again the market can&amp;#39;t ignore great earnings! 👉 $AAPL  Green by morning bulls! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:38:35 </td>
   <td style="text-align:left;"> $QQQ huge losses coming tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:37:46 </td>
   <td style="text-align:left;"> $QQQ March 23 2020 ; everyone panics. A new diseases arises from Wuhan, China, and is spreading faster than anyone thought, disturbing and scaring everyone and every government. Stocks are crashing, people see their accounts plumetting - some people pull the plug because they can&amp;#39;t no more. A &amp;quot;relief rally&amp;quot; emerges and everyone calls bullshit. Then, FOMO kicks in and you rebuy at a higher price all the stocks you have sold - I don&amp;#39;t wanna be this type of person, ever lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:37:03 </td>
   <td style="text-align:left;"> $QQQ stock analysis based on today&amp;#39;s closing price. Full analysis is available on youtube 

https://youtu.be/9tA5mqQ9-c0

Here is $QQQ snapshot </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:36:56 </td>
   <td style="text-align:left;"> $ASTS $ORGN $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:36:24 </td>
   <td style="text-align:left;"> $DIA $SPY $QQQ Is the Fed crashing the market on purpose? This guy has a very good explanation of what is happening and also the reason I stay short the market overall this year:  
 
https://www.youtube.com/watch?v=lPUTG-THWoU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:36:20 </td>
   <td style="text-align:left;"> $SPY $UVXY $QQQ $DJIA 

Send this shit to the bottom of the ocean. All of it. I’ve been calling for this reset for a while— and UVXY going to make me a millionaire </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:36:18 </td>
   <td style="text-align:left;"> $QQQ A recession would be better than runaway inflation. Took nearly a decade the last time it happened. The Fed needs to be proactive not reactive , they are already falling behind. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:36:08 </td>
   <td style="text-align:left;"> $aapl $spy $qqq $ndx $xlk https://www.youtube.com/watch?v=ddEuU458vlw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:34:52 </td>
   <td style="text-align:left;"> $QQQ shorting via NQ futures again.  May be an ugly Friday.  Even Apple can’t fight the Fed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:34:31 </td>
   <td style="text-align:left;"> $AAPL $QQQ 

Apple and the rest of tech will be red at open

Massive selling in Japan.  EU will follow.

Tomorrow is going to be the worst day of the year. 

If you can sell now, sell. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:33:22 </td>
   <td style="text-align:left;"> $SPY Margin Just called 
$QQQ $AAPL $XLY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:32:36 </td>
   <td style="text-align:left;"> $SPY $QQQ NQ 800 points range of consolidation for a week now. I thought a good chance itll break down, but with these good earnings, maybe the correction will end and be done with now. Many stock have already tanked roughly 50%. I guess we will find out soon enough </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:32:06 </td>
   <td style="text-align:left;"> $QQQ rally unfortunately probably won’t come until after rare hikes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:30:31 </td>
   <td style="text-align:left;"> $QQQ $SPY www.theforecast.co called the crash huge rally coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:27:46 </td>
   <td style="text-align:left;"> $SPY $QQQ I want my damn FMF tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:27:38 </td>
   <td style="text-align:left;"> $RBLX Damn, this thing got the ramming of a lifetime. 😆 20 RSI ? Do technicals even matter at this point ? Market Psychology &amp;gt; technicals at the moment $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:27:22 </td>
   <td style="text-align:left;"> Nothing better than watching Cramer out Patty G of $INTC for being the lying slime ball he truly is. Closed by saying $NVDA and $AMD were buys especially after China’s approval of the $XLNX deal. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:26:35 </td>
   <td style="text-align:left;"> $QQQ Funny how everyone is worried about inflation all of a sudden, where were these people the last 5 years? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:25:29 </td>
   <td style="text-align:left;"> $QQQ Initial jobless claims for the week ending January 22 decreased by 30,000 to 260,000. Continuing claims for the week ending January 15 increased by 51,000 to 1.675 million. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:25:25 </td>
   <td style="text-align:left;"> $QQQ Hahaha, this market is weak af. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:23:08 </td>
   <td style="text-align:left;"> $QQQ  $SPY

A gap down could mean a green close. They have to throw you a bone. They’re not going to kill it in one setting. They need every dip buyer with a paycheck and margin loans to donate and keep donating. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:22:03 </td>
   <td style="text-align:left;"> $AMD IF your a long term investor good for you, this market is probably testing your convictions.....But if your a short term trader like me, this market has been terrific.  
Keep it simple, buy the drops/sell pops. It ain&amp;#39;t complicated. 
Just stick to good companies, no trashy shit.  
$QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:21:48 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL $MSFT not very good news here… 👤 https://www.bloomberg.com/news/articles/2022-01-27/u-s-nato-respond-to-russia-rejecting-demands-ukraine-update </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:16:57 </td>
   <td style="text-align:left;"> $SPY $QQQ We might see global inflation easing soon since the global economy outside of the US isn&amp;#39;t really doing all that well. If the economy is weak then companies can&amp;#39;t raise prices that much. While inflation is kinda high now, we should also be thankful that the US is in such a better shape than rest of the world right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:16:19 </td>
   <td style="text-align:left;"> $SPY $QQQ what&amp;#39;s up with Biden&amp;#39;s sick fantasy of black females? His VP and now supreme justice ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:16:09 </td>
   <td style="text-align:left;"> $QQQ $AAPL did just enough to kiss the 200 on 1 hour. Tweezer top at that.  😬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:15:12 </td>
   <td style="text-align:left;"> $QQQ Cramer says not to buy… Bottom is in boys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:14:01 </td>
   <td style="text-align:left;"> $QQQ crypto leads the way </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:13:49 </td>
   <td style="text-align:left;"> latex864fb1aa55b5d887fc298a27e1f9e1daSPY latex275cee51689cd0eb637a7d02f1e004ac$es </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:13:04 </td>
   <td style="text-align:left;"> $QQQ futures deteriorating </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:10:21 </td>
   <td style="text-align:left;"> $QQQ Commence the overnight bleed out and heartache. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:09:48 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures sharply higher, thanks to $AAPL the bulls can finally celebrate tomorrow and have some extra money to spend for the weekend lol 😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:09:16 </td>
   <td style="text-align:left;"> If $QQQ and $SPY go negative after $AAPL earnings, we are in trouble. Not to mention all the 425 puts. Fugly!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:08:41 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ   IWM and DJT have already given up the monday low ... who is next????? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:08:21 </td>
   <td style="text-align:left;"> $AAPL $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:07:15 </td>
   <td style="text-align:left;"> $AAPL I just see these little associative moves w/ Apppe by tech, I think it subsides afterhours.

Core PCE Deflator will kill rally quick tomorrow, but might die sooner too
$QQQ $NDX $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:06:33 </td>
   <td style="text-align:left;"> $QQQ F*** piece of shit.  
 
both MSFT and AAPL doing good. this is F*** going down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:06:20 </td>
   <td style="text-align:left;"> $BTC.X $QQQ $AAPL 
Bitcoin indirectly linked to Apple as Bitcoin continues to rise/fall with QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:06:16 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL will buy cheap Apple put tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:03:23 </td>
   <td style="text-align:left;"> $QQQ $SPY y’all gonna need more than apple and Microsoft to save this piece of junk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:02:28 </td>
   <td style="text-align:left;"> $QQQ this won’t go much lower until apple and Microsoft break down. We can all hope for dump but looks like the time isn’t here quite yet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:02:21 </td>
   <td style="text-align:left;"> Haven’t seen Capitulation yet.  Be patient . $IWM $SPY $$qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:01:45 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM SMall caps isn’t buying it. It’s not over yet 🧐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:01:11 </td>
   <td style="text-align:left;"> $QQQ &amp;#39;futes ripping&amp;#39; 
 
It was ripping today too 
 
Oh, TSLA was up too </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:00:29 </td>
   <td style="text-align:left;"> $QQQ futes ripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 08:00:05 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL  massive money bet on earnings..  the World  ready to buy a load at premarket open.. could be one of largest Gap up n Go&amp;#39;s  of the Year.. 21% increase in China is big.  
 
a gap over red tenkansen would leave  a trail of Cheese whiz..   heading  to future cloud bottom to complete the 
&amp;quot; triple Triscuit Lindie&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:59:46 </td>
   <td style="text-align:left;"> $QQQ If Apple was such a big deal this would be up 3%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:59:04 </td>
   <td style="text-align:left;"> $SPY $QQQ Thinking out loud…what could happen over the weekend to help the market? Not much…but war that could pop off at any minute certainly won’t help. Holding puts and doubling down before the weekend if tomorrows green. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:58:34 </td>
   <td style="text-align:left;"> $QQQ 
Market will rebound gradually 
Do not panic
Trillions of $ on side lines will come to market soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:56:40 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X $ETH.X thinking relief bounce coming after the bullish reaction to $AAPL earnings but who knows maybe we fade right back down lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:56:33 </td>
   <td style="text-align:left;"> $VERB oh yea i feel a Valentines day event, maybe 2,  Then a full Launch

https://youtu.be/c5xKOK6VhZg

Its definitley close 

https://youtu.be/pFiCcP6h94Y

Anyway Didnt $AAPL sign this guy? He uses Verbs technology to make his streaming programming shoppable? Click a button on screen &amp;amp; throw it in the Bag? Is that what Apple is using on their Streaming tv?

https://www.prnewswire.com/news-releases/apple-tv-and-david-meltzer-announce-a-2-year-content--distribution-deal-301454813.html

Dont care what the
 $SPY , $QQQ $SMH do when Verb launches live stream ecommere app stock goes or it gets bought out simple as that. 9% institutional ownership vanguard fidelity &amp;amp; blackrock all index buyers. All institutions will come to take a stake </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:56:28 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X  all hands on deck The crypto crash is officially  over crypto bears are about to get scammed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:56:22 </td>
   <td style="text-align:left;"> $SPY $QQQ Donate a testicle for $35k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:55:43 </td>
   <td style="text-align:left;"> Took a small loss on $GLD  and still holding couple short that are doing well, trimmed some profit on the way down and still holding the rest as the market still showing signs of lower prices ahead... $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:54:20 </td>
   <td style="text-align:left;"> $QQQ only so many Chinese iPhones can support the NASDAQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:53:35 </td>
   <td style="text-align:left;"> $SPY  $QQQ $DIA $IWM the VIX is losing steam. Can we just go to 425 and get it over with this tiring yo-yo moves? But if MMs are reprogrammed to start moving upwards, that’s fine with me too. 🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:52:53 </td>
   <td style="text-align:left;"> $XBI Wow, 4.55% down on a not so bad $QQQ day. Carnage at its best!  It&amp;#39;s sitting below the 78.6% fib retracement level at 86.8.  Look at the weekly RSI at 24.65, lowest since ever. lol 
 
For now, I am selling covered calls as that&amp;#39;s the only I can do other than take a loss, which is not a good idea after it lost so much this year. 
 
$LABU $IBB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:52:51 </td>
   <td style="text-align:left;"> $SPY $QQQ Cramer says not to buy… Bottom is in boys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:50:53 </td>
   <td style="text-align:left;"> $SPY So I discussed $aapl &amp;amp; Timmy prior to the Open, its just the job  he has to save America &amp;amp; he takes it seriously 
 
$amzn $qqq $msft </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:50:45 </td>
   <td style="text-align:left;"> $QQQ Whether or not this market goes lower, it is absolutely time for some greedy bears to question their decisions and run for the hills. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:48:05 </td>
   <td style="text-align:left;"> $SPY $QQQ You can just see it happening...This market is weak as hell at the moment... Apple is the only reason why both etf&amp;#39;s are up...Rug pull incoming after 8pm and into tomorrow morning. 
not saying apple will go red but many other tech names will fall </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:48:02 </td>
   <td style="text-align:left;"> $QQQ needs to break that 14200 level again.. 

Been the issue all week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:42:02 </td>
   <td style="text-align:left;"> $QQQ it’s not about earnings, it’s about forward guidance. The earnings are already baked in. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:41:42 </td>
   <td style="text-align:left;"> $SPY anyone know where to get live 10yr and 2 yr treasury yield spread? Thx $AAPL $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:41:35 </td>
   <td style="text-align:left;"> $SPY $QQQ Been selling off a month and bears want more? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:41:29 </td>
   <td style="text-align:left;"> $SPY $QQQ $ARKK 2021 Oscar best actor and actress belong to JPow and cathie Wood. One put on a stern look every time he went on a show lying about “transitory”. The other advertised herself nonstop with “5-year perspective” and “in deep value”, which attracted a cult following and fattened her wallet. Liars lie, and there ain’t any consequences </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:40:24 </td>
   <td style="text-align:left;"> $QQQ just short every pop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:40:01 </td>
   <td style="text-align:left;"> $QQQ need to do a 5% to kick all these bears😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:39:32 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA $QQQ 

FUTURES UPDATE FOR THE BEARS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:37:48 </td>
   <td style="text-align:left;"> $QQQ $SPY Let&amp;#39;s talk stocks 
https://youtu.be/doy0492j2Ls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:35:48 </td>
   <td style="text-align:left;"> $QQQ Same story every single day of the week. Buy calls at low, sell them when we pop. Bought a bunch of calls at close and will sleep like a baby. Thanks to $AAPL for the lift! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:34:40 </td>
   <td style="text-align:left;"> $GRPN $AAPL $SPY $QQQ $HOOD 💵🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:34:04 </td>
   <td style="text-align:left;"> $SPY $QQQ $TLT $UUP 

Daily Market Recap! Check it out!

https://www.youtube.com/watch?v=FT2u9srKg6g </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:33:37 </td>
   <td style="text-align:left;"> A Tale Of Two Markets: #AAPL vs #HOOD #Earnings $AAPL $HOOD Also $ARKK $QQQ https://talkmarkets.com/content/stocks--equities/a-tale-of-two-markets-aapl-vs-hood-earnings?post=342727 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:31:51 </td>
   <td style="text-align:left;"> latexa42345c6aa9f255735c0050952c9170eINTC
Calls over 50.50
Puts below 47

$NFLX
Calls over 395
Puts below 378 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:29:04 </td>
   <td style="text-align:left;"> $QQQ so let’s say apple gaps ups and holds these ah gains tomorrow, what kinda impact can we see here given it’s like 11% of the qqq? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:29:00 </td>
   <td style="text-align:left;"> $QQQ closure was still bearish on triple Q, id be careful incase the boomers decide to take advantage of the ER pump to exit. people got heavy bags from the top and they tryna empty them $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:29:00 </td>
   <td style="text-align:left;"> $QQQ Apple is about to peak here. What happens tmrw When Apple isn’t holding everything up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:28:53 </td>
   <td style="text-align:left;"> $QQQ $SPY $RUT I swear small caps and growth get shorted and sold into oblivion leading up into every fed meeting, Big tech sells off a bit, and overvalued value stocks rally, and then the fed pushes back rate hikes, and says the same thing they said last time, big tech recovers, small caps never see their previous prices, and “value” just keeps rallying… rinse and repeat over the last 3 or 4 meetings and here we are today with the exact same breakneck crash for small caps without anything but rumours. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:28:48 </td>
   <td style="text-align:left;"> $AAPL So we break this down vs. $MSFT 

Little better REV, 1B vs 2.75B . I&amp;#39;m little less than halfing REV , so what it would be if had done 50b REV instead  of 120B.

And for EPS, $MSFT Tutes est. 2.32 vs actual 2.48.

K, so Microsoft beat by 16 cents.

And, Apple EPS was 2.10 vs 1.90 est
 So, 20 cents.
Then......what for guidance? 

&amp;quot;No guidance, sir&amp;quot; 

WHAT YOU GOTTA BE SHTICKING ME, THAT CAN&amp;#39;T BE TRUE.
Let me hear it again.
&amp;quot;No guidance, sir.&amp;quot;

Okee , well, $MSFT went from 296 pre-ER right before to 305, maybe, b4 the elevator down to 298 where at now. 

So, by rights, w/ SIMILAR ERs, Apple should just slowly deteriorate from 168, 167, 166, 159, by morning or at least get close to those #s. 

$QQQ  $NDX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:27:34 </td>
   <td style="text-align:left;"> $QQQ saueeze time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:27:17 </td>
   <td style="text-align:left;"> I cannot trade futures on etrade anyone else having issues? $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:27:01 </td>
   <td style="text-align:left;"> $SPY $QQQ every pop is a gift to short </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:26:55 </td>
   <td style="text-align:left;"> $AAPL apple made $123b in 3 months , enough said . Bears give up … you are  just wasting time and energy posting meaningless rubbish here  $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:26:14 </td>
   <td style="text-align:left;"> $QQQ  I sold my 347 PUT. for a nice profit. I am looking for the Q&amp;#39;s  to drop down another 22-28 Dollars </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:23:45 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL WTF 🧐🧐🧐!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:21:30 </td>
   <td style="text-align:left;"> $QQQ  I am gonna have me  nice juicy burger tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:20:08 </td>
   <td style="text-align:left;"> $QQQ Someone bought my after hours apple short at 168.15, beautiful </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:19:57 </td>
   <td style="text-align:left;"> $AAPL Who just reported, was s&amp;#39;pose to be a big event.
Forget who.

Eh, wasn&amp;#39;t important , guess we just continue tomorrow with a little futures takedown b4 we really rode up ON....

INFLATION PCE Core report🥶😱🥶😱🥶😱🥶😱🥶😱

$QQQ $NDX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:19:28 </td>
   <td style="text-align:left;"> $QQQ can AAPL carry the market while TSLA dragged it down today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:17:53 </td>
   <td style="text-align:left;"> $HOOD only problem is that half their users are going to be broke and won&amp;#39;t invest after the market just got humped to death.  $QQQ $IWN $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:17:36 </td>
   <td style="text-align:left;"> $QQQ  Here we go again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:17:20 </td>
   <td style="text-align:left;"> Stocktwits: 
VIDEO: Broad Market Technical Analysis Chart 1/27/2022 $SPY $XLF $QQQ $TSLA $CMPS https://www.chartguys.com/daily-market-videos/4117/tightening-ranges-crystal-clear-setups </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:17:00 </td>
   <td style="text-align:left;"> $AAPL yes it beat nicely. Everyone believes this will be the savior of TECH...News Flash...We&amp;#39;re far from done! I&amp;#39;m 100% certain tomorrow or overnight market will pull the rug on everyone. Not saying apple will finish red, but many TECH stocks will continue to HELL 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:16:58 </td>
   <td style="text-align:left;"> $AAPL Great Earnings!  Hopefully it’s not a “sell the news” event. $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:16:18 </td>
   <td style="text-align:left;"> $QQQ Looks kind of bearish tomorrow ngl... https://stockbet.io/home/QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:15:18 </td>
   <td style="text-align:left;"> $QQQ $SPY  
look around. bears have already entered full euphoria mode. 
 
@fundatech bear soup wen? long bear death </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:14:24 </td>
   <td style="text-align:left;"> $spy Biden is going to leave a legacy of green thinking.

Green energy thinking, green air thinking, green market thinking, even.

Get it he&amp;#39;ll want the stock market green but it&amp;#39;s only in his dreams 😂🤣😅

$qqq $ndx 

$aapl Willy jus widdow beats fo such a bwig cwompany </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:13:00 </td>
   <td style="text-align:left;"> The technical rating of $QQQ is bad and it also does not present a quality setup at the moment. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:12:24 </td>
   <td style="text-align:left;"> $RBLX $GEVO $INDI $HOOD $QQQ  
I offer the following mantra from Sri Nisargadatta Maharaj: 
 
&amp;quot;I am not my mind.  It&amp;#39;s problems are not mine.&amp;quot; 
 
It&amp;#39;s one thing putting up with this manipulation on the daily, but allowing the stress of it to take years off of your life is a whole nother thing.  It will all come around, it always does. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:11:10 </td>
   <td style="text-align:left;"> Ouch $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:10:00 </td>
   <td style="text-align:left;"> $QQQ Nothing like a 200pt opening spike to bury the morons on here ... LMFAO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:09:29 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-01-27 Daily Forecast Video: 
https://www.youtube.com/watch?v=q-5n6mymXC4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:09:12 </td>
   <td style="text-align:left;"> $QQQ $AAPL Some poor fool is about to buy off the 161.8% fib </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:08:47 </td>
   <td style="text-align:left;"> $QQQ - Stay with the program as long as the Fed is tightening 

Sell the rip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:08:33 </td>
   <td style="text-align:left;"> $SPY woot-woot 

$qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:06:31 </td>
   <td style="text-align:left;"> $QQQ $ARKK Lets keep driving innovation down. I’m fine going back to typewriters and microfiches. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:05:26 </td>
   <td style="text-align:left;"> $SPY Cramer says stay the course.  Don&amp;#39;t trade Apple or other quality stocks... as if market really cares.  When JPOW reduces balance sheet, ALL stocks tank on a relative basis.  Cramer says hold, so do the opposite. SELL SELL SELL.  $UVXY  $SQQQ $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:05:19 </td>
   <td style="text-align:left;"> $QQQ Powell vs Cook. I&amp;#39;m riding with Powell. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:04:13 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ  oil is up after hours! drug companies up after hours! wow. this will be a rude awakening tomorrow… again! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:02:59 </td>
   <td style="text-align:left;"> Mega caps are a bubble awaiting to pop last in this downtrend IMO. 📉
$QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:02:40 </td>
   <td style="text-align:left;"> $SPY futes rip and open deep red. That&amp;#39;s the pattern. Apple ain&amp;#39;t saving anything. $qqq $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:02:37 </td>
   <td style="text-align:left;"> $SPY $QQQ Bears who didn’t close puts today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:01:12 </td>
   <td style="text-align:left;"> $AAPL $QQQ Based on this price action apparently Apple just cured cancer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:00:47 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ $NVDA rip puts 🍎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:00:38 </td>
   <td style="text-align:left;"> $QQQ distance from the 200 WMA (bottom graph) was ~triple the distance it had ever been since 2002 = crazy extended. It&amp;#39;s now closed the gap by more than half and is back to pre-Covid levels, which itself was relatively extended. feels like more dip coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 07:00:24 </td>
   <td style="text-align:left;"> $QQQ keep going up! More to short tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:59:43 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $AAPL 

Can Apple hold its gains? Or these mf’ers will shoot it down? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:58:57 </td>
   <td style="text-align:left;"> $QQQ hoping for another pop in the morning to add to spreads for afternoon fade </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:57:45 </td>
   <td style="text-align:left;"> $QQQ technical analysis for tomorrow. 
 
https://youtu.be/BGVG88QR5BQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:56:39 </td>
   <td style="text-align:left;"> $SPY $QQQ apple saving lives </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:55:45 </td>
   <td style="text-align:left;"> $AAPL If this breaks 170 not only it will save $QQQ market will 🚀 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:55:40 </td>
   <td style="text-align:left;"> $qqq $aapl Dear Market Gods, hold these levels until my calls can sell and this week will go down in my trading history... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:55:23 </td>
   <td style="text-align:left;"> $QQQ relief rally tmrw? Be careful tho..it might not hold. But this definitly bullish for tmrw morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:54:38 </td>
   <td style="text-align:left;"> $SPY $QQQ The best thing that could happen to this market, is to open flat and go down near Monday lows and reverse. But with Apple magical earnings it does not look like it will be the case.  
I just can&amp;#39;t see how this market can move up substantially without a double bottom near Monday lows. 
IMO the $SPX will go up to 4500 then come down near the lows, before rallying. We will see. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:53:56 </td>
   <td style="text-align:left;"> $AAPL $TSLA $QQQ $MSFT $SPY 

SHORTS ARE ABSOLUTELY DESTROYED TOMORROW!!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:53:45 </td>
   <td style="text-align:left;"> $QQQ oh my god another spike to short, thanks bulls for everyday free money !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:53:28 </td>
   <td style="text-align:left;"> $AAPL saving one index at a time $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:52:37 </td>
   <td style="text-align:left;"> $qqq $spy $tqqq https://www.youtube.com/watch?v=8f141JxQvfY&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:51:38 </td>
   <td style="text-align:left;"> $QQQ T&amp;#39;FAANG&amp;#39;s own the world. Were hitting below the COvid19 Crash indicators. Don&amp;#39;t underestimate how quickly we can turn around. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:50:24 </td>
   <td style="text-align:left;"> $QQQ $AAPL there’s your guidance … paying way too high of a multiple for 10% forward growth </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:50:01 </td>
   <td style="text-align:left;"> $QQQ Gap up tomorrow the flush </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:49:52 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $TSLA $AAPL  
 
https://www.financegreater.com/post/managing-a-bearish-market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:49:28 </td>
   <td style="text-align:left;"> $SPY $QQQ  Viral POLL for the SPY, DO YOU THINK The MARKET Will CRASH during 2022? Yes or NO? Discussing LIVE here, 
https://strawpoll.com/o2h1x9has </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:48:16 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ this is how I know I’m so much better than 99% of you. 💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:48:13 </td>
   <td style="text-align:left;"> $QQQ bull trap into AH on $AAPL false hope, tomorrow we push below this week’s support for new lows </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:47:28 </td>
   <td style="text-align:left;"> $SPY $QQQ I went short </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:47:05 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA

Staying out of markets for 2 months until this fckry is over and we have clear direction.  Not adding anymore positions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:46:52 </td>
   <td style="text-align:left;"> $spy $qqq $ndx $spx $aapl https://www.youtube.com/watch?v=dBKoETVDcRM&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:46:05 </td>
   <td style="text-align:left;"> $QQQ As expected AAPL did not disappoint. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:46:00 </td>
   <td style="text-align:left;"> $QQQ hey have to bring it up to bring her down.  Watch and learn. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:45:56 </td>
   <td style="text-align:left;"> My latest blog, “A Tale Of Two Markets: AAPL vs HOOD Earnings”, is available:

https://www.topgunfp.com/a-tale-of-two-market-aapl-vs-hood-earnings/ 

@sentimentrader 

$QQQ $AAPL $HOOD $ARKK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:45:34 </td>
   <td style="text-align:left;"> $QQQ $IWM $SPY $DJIA 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:45:34 </td>
   <td style="text-align:left;"> $QQQ apple tesla intel, all showing good results. Am not worried about techs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:42:06 </td>
   <td style="text-align:left;"> $AAPL Supply issues and shipping problem with no clear guidance! bloodbath for apple tomorrow and the whole market!  Just ask $TSLA!   $QQQ $SPY $UPST </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:42:01 </td>
   <td style="text-align:left;"> $AAPL ... Approximate Daily resistance to look out for on Apple for tomorrow 🍀 $STUDY $QQQ 📚 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:41:44 </td>
   <td style="text-align:left;"> $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:40:55 </td>
   <td style="text-align:left;"> Apple reports Q1 results: ‘beyond what bulls were hoping for’ $AAPL $QQQ https://invezz.com/news/2022/01/27/apple-reports-q1-results-beyond-what-bulls-were-hoping-for/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:40:12 </td>
   <td style="text-align:left;"> Indices looking to challenge Monday&amp;#39;s lows $QQQ $IWM $SPX https://talkmarkets.com/content/stocks--equities/indices-looking-to-challenge-mondays-lows?post=342725 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:39:33 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $AAPL  many of you guys shorted the close? AAPL put a floor under the market for a few days me thinks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:37:45 </td>
   <td style="text-align:left;"> $QQQ 
$127 🧲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:37:20 </td>
   <td style="text-align:left;"> $QQQ When this goes red, tonight or tomorrow, it&amp;#39;ll rip the soul out of rookie traders who have only known btfd. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:36:32 </td>
   <td style="text-align:left;"> $AAPL $spy $qqq huge upgrades tomorrow 🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:36:16 </td>
   <td style="text-align:left;"> Slow bleed sucks your account. This individual’s balance was $1.2m in Nov and it’s cut in half, $5.7m now. 🤯 We all believe today is the last day and things will turn around but if we pay attention to why markets is headed down (Fed tightening) we’d be less bullish &amp;amp; don’t gamble. 
$QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:34:56 </td>
   <td style="text-align:left;"> $QQQ profit taking coming... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:34:41 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ $BTC.X  Just do your thing.  Even the &amp;quot;experts&amp;quot; get it wrong most of the time when looking short term. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:33:54 </td>
   <td style="text-align:left;"> $QQQ soon.  U vil own nussing und b heppy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:32:36 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:31:57 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ  annnnd here we are $5 later .. you guys don’t get tired of seeing me winning ? 👁💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:31:10 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ  apple fixed the inflation issue going on? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:30:47 </td>
   <td style="text-align:left;"> $QQQ 350 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:30:43 </td>
   <td style="text-align:left;"> $SPY $QQQ Thanks to the strong earnings from $AAPL, the market likely will be up massively tomorrow, let&amp;#39;s hope we can keep this positive momentum into next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:30:30 </td>
   <td style="text-align:left;"> $SPY $QQQ just got here and already see several posts for 500 spy.   
on what planet...with what  flavor koolaid? 
nasdaq has sunk to June 2021 levels 
5 trillion dollars gone from market this year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:29:49 </td>
   <td style="text-align:left;"> $QQQ after hours bull trap to lure out the impatient ... red close Friday too predictable, good luck all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:28:55 </td>
   <td style="text-align:left;"> $QQQ Read a comment today asking why the market can&amp;#39;t just drop 50% overnight, correct, and be done with it.  Because the real target is more than 50%.  It&amp;#39;s a Depression-level scenario.  In the 1980&amp;#39;s, it would have been 20%.  1990&amp;#39;s - 30%.  2000&amp;#39;s - 40%, 2010&amp;#39;s - 50%, 2020&amp;#39;s - ?  We&amp;#39;ve kicked the can down the road so many times, it&amp;#39;s like a Ponzi scheme now.  The best thing to do would have been to let the Great Recession play out without market manipulation, abolish the Fed, and adopt the gold standard again.  There&amp;#39;s only one problem, folks think the Fed manages all things USD financial but they don&amp;#39;t.  They manage the monetary supply and play a loose game with the Treasury.  Facing the music and abolishing the Fed would bankrupt the USA, with the debt-levels we have now.  The only reason we aren&amp;#39;t insolvent is that inflation and money-printing makes our debt serviceable. The world is going to do this for us (abolish Fed) and dethrone the USD as the world currency.  Hold on tight. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:28:37 </td>
   <td style="text-align:left;"> $SPY ok, back to our regularly scheduled slaughter, Apple ER was a

$QQQ $NDX $SOXL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:28:25 </td>
   <td style="text-align:left;"> $QQQ take a monthly chart for NDX over a 20 year and max time frame.   Look at the MACD crossovers on those timeframes along with the stochastic as and rsi and the corresponding bear markets that resulted.   Notice how long we’ve sustained an overbought ndx in recent years.   Not sure we can avoid the coming MACD crossover.   Tell me your thoughts.  I’d love to hear others insights. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:26:44 </td>
   <td style="text-align:left;"> $QQQ I called it this just broke out of a falling wedge it’s only clear skies ahead </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:26:20 </td>
   <td style="text-align:left;"> $SPY $QQQ HEARD IT HERE FIRST:

$IWM Double Bottom gonna lead the market up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:26:12 </td>
   <td style="text-align:left;"> $SPY $QQQ would not be surprised to see a gap up and sell off again tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:25:42 </td>
   <td style="text-align:left;"> $QQQ $AAPL powell should stay home, let Tim be the boss of fed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:25:38 </td>
   <td style="text-align:left;"> $QQQ  
 
The Bears better look at that Visa number and thier guidance. The economy is strong, you won&amp;#39;t be talking crap for too much longer. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:24:52 </td>
   <td style="text-align:left;"> $SPY $UPRO $QQQ $AAPL Apple revenue pops 11% to $123.9 billion, Cook says supply chain improving https://www.cnbc.com/2022/01/27/apple-aapl-earnings-q1-2022.html?__source=iosappshare%7Ccom.apple.UIKit.activity.CopyToPasteboard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:23:26 </td>
   <td style="text-align:left;"> $QQQ weekly volume most since August 2011.  Over a decade ago </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:23:18 </td>
   <td style="text-align:left;"> $QQQ What&amp;#39;s going on, did Powell change his mind? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:23:06 </td>
   <td style="text-align:left;"> $QQQ At what price would you take your ENTIRE life savings and go all fucking in? Truly balls deep with no hands </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:19:46 </td>
   <td style="text-align:left;"> $QQQ retail investors are endangered species </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:19:37 </td>
   <td style="text-align:left;"> $QQQ go green QQQ!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:19:17 </td>
   <td style="text-align:left;"> $QQQ doomberg says sec hard at investor protection </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:19:02 </td>
   <td style="text-align:left;"> $QQQ 📜 SEC Form 485BPOS filed by Invesco QQQ Trust, Series 1

https://quantisnow.com/insight/2315098?s=s

45 seconds delayed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:18:36 </td>
   <td style="text-align:left;"> #Apple Soars After Smashing Expectations In Record Revenue Quarter $AAPL Also $QQQ https://talkmarkets.com/content/stocks--equities/apple-soars-after-smashing-expectations-in-record-revenue-quarter?post=342722 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:18:18 </td>
   <td style="text-align:left;"> $QQQ Form 485BPOS (post-effective amendment [rule 485(b)]) filed with the SEC 

https://newsfilter.io/a/166512b623bfca0dc29d9a176d47fab7 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:18:14 </td>
   <td style="text-align:left;"> $AAPL here come the expected rug pull and no way to cash in on those calls in ah.  It like they don’t learn from what happened to $TSLA!     $SPY $QQQ $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:16:26 </td>
   <td style="text-align:left;"> $QQQ 
The  economy is doing just fine, it’s the market mechanism that changed and not for the best… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:15:36 </td>
   <td style="text-align:left;"> $AAPL 5%

4..............^

%          3

2 percent, 1, 0 -1, -2 

#ER
$QQQ $NDX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:14:33 </td>
   <td style="text-align:left;"> $QQQ Setting up another shorting opportunity. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:14:19 </td>
   <td style="text-align:left;"> $QQQ $SQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:14:10 </td>
   <td style="text-align:left;"> $QQQ Seriously, why the sell off every day? Why can&amp;#39;t it just be one day of pure hell and get it over with? Let me lose 50% of my portfolio in diginity. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:13:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM bears might be more greedy than bulls. it&amp;#39;s best to play both sides imo. i was feeling pretty bearish at $455 and $475. raised cash and waited. how much more do you want? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:13:41 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:13:24 </td>
   <td style="text-align:left;"> $SPY $QQQ Bears who didn’t close puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:13:19 </td>
   <td style="text-align:left;"> $QQQ $AAPL after hours action slammed the price of apple right up against the top of the channel. I&amp;#39;d be really surprised if it breaks back above the channel with the expectations of slowed economic growth. Above the channel basically requires parabolic price action.  I consider that move to have been a blow off top and we all know it only happened to hide the dying market over the past few months. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:12:40 </td>
   <td style="text-align:left;"> There is a dog ... thank dog I did not get coverage on shirting 40,000 overpriced shares of ROBINHOOD afterhours at 10 bucks ... TD had no afterhours coverage  ... thanks bulls for not selling me your junk afterhours  ... will review again tomorrow  ... you da best ❤ $HOOD  ... the shit last check afterhours selling for close to 10.50 ... what da fk ... there&amp;#39;s a sucker born every day 😜  good health and trading to all 👍 ... fyi scored nicely today full short 30,700 shares of $f .... next on the 22 calibre long barrel is full short $ccl ... so much overpriced crap on Fraud Street for easy short for profits for fks like me ... thanks pals ... $spy $qqq  ... carry on sticking forks in the stock markets at large for profits  ... love it ... yes i know .... lol ... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:12:23 </td>
   <td style="text-align:left;"> $QQQ Can the market just tank 50% please. The whole damn thing. I&amp;#39;m sick of this shit every day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:12:13 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM Bears are over over over  overestimating their power </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:11:14 </td>
   <td style="text-align:left;"> $QQQ retail loves buying the bags of whales. Congrats $AAPL apes. You are getting played. Nothing to do with Apple, great company, big believer. However, high valuation in this market down trend, zero forward guidance. It&amp;#39;s going no where but down over the next month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:11:12 </td>
   <td style="text-align:left;"> $QQQ $AAPL $SPY skipping guidance = I don’t want to give a guidance number because I know my company’s growth with be negatively impacted by the current supply chain issue for atleast the next quarter. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:10:42 </td>
   <td style="text-align:left;"> $aapl $tsla $msft $spy $qqq  tech heavy weights all guided higher🚀🚀🚀

We will see nasdaq +1000 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:10:04 </td>
   <td style="text-align:left;"> $TSLA $QQQ S.O.S. to $AAPL &amp;#39;save our shares&amp;#39; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:09:54 </td>
   <td style="text-align:left;"> $AAPL $MSFT and many other tech companies all reporting monster numbers. Any of these selloffs in tech are ridiculous as these are the companies of the future that will drive the economy. These rates even if raised to 3 percent are still at historical lows. Adding on great tech companies all day $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:08:39 </td>
   <td style="text-align:left;"> $AAPL Putin is mad about his 0dte $QQQ puts and is now going to invade Ukraine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:08:30 </td>
   <td style="text-align:left;"> $SPY $QQQ yaas futes ripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:08:17 </td>
   <td style="text-align:left;"> $QQQ who keeps buying this shit ? Everyday the same feels like … </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:08:11 </td>
   <td style="text-align:left;"> $AAPL I was thinking about shorting this but held off. Buying now. We may have bottomed at 157. That was an earnings blow out. Might save the $QQQ  and $spy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:08:10 </td>
   <td style="text-align:left;"> $AAPL old news but Affirm shall pump
https://9to5mac.com/2021/08/11/apple-affirm-financing-canada/
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:07:47 </td>
   <td style="text-align:left;"> $QQQ is that green or red? Im colorblind as fck and been without alcohol for 11 days….as I try to lose this layer of skin referred to as fat. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:07:37 </td>
   <td style="text-align:left;"> $SPY $QQQ $F  
 
$AAPL apples sales were strong in China </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:07:31 </td>
   <td style="text-align:left;"> $QQQ this is Q4 earnings. Everyone asking why the market is skeptical. Reason is every blue chip has revised guidance down. Apple pleads the 5th. You pay high multiples for growth curve to be sustained, forward guidance is everything. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:07:31 </td>
   <td style="text-align:left;"> $SPY $QQQ Bears who bought puts at market close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:07:10 </td>
   <td style="text-align:left;"> $spy $qqq $labu $iwm
The selloff is over IMO
Melt up here we come $$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:06:21 </td>
   <td style="text-align:left;"> $AAPL $MSFT Holding markets from a Recession 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:06:18 </td>
   <td style="text-align:left;"> $QQQ Feel like the Apple beat should pick up S and P in the short term. Visa and Master card also shows positive momentum. Feb gonna be bullish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:05:59 </td>
   <td style="text-align:left;"> $QQQ wall st  screwed investors royally dumping crappie papers on retail of course sec was looking out for the small investor in approving them </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:05:51 </td>
   <td style="text-align:left;"> $QQQ kill the bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:05:50 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ bears right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:05:40 </td>
   <td style="text-align:left;"> $QQQ I mean how much good economic news do you need at this point? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:05:24 </td>
   <td style="text-align:left;"> $QQQ what companies so far haven’t reported guidance? So funny how retail is buying into no guidance when if that were actually bullish why haven’t companies been doing that all along? Smdh 🤦‍♂️ perma bulls gonna get dumped on </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:05:09 </td>
   <td style="text-align:left;"> $SPY RIP jabroni bears. You&amp;#39;ve had a week to cover your positions. Now you&amp;#39;ll be the greedy ones $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:05:06 </td>
   <td style="text-align:left;"> $AAPL they pumped in ah when you can’t sell your calls. This will be back down by market opening tomorrow. Also retail investors are buying this up which set up the expected rug pull by the whales. Just ask $TSLA. $SPY $QQQ $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:04:48 </td>
   <td style="text-align:left;"> $AAPL Taking up the entire market
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:04:33 </td>
   <td style="text-align:left;"> $QQQ Until semis get some traction and start moving into bullish territory, beats like appl and msft are all going to be treated the same. Semis are the key to recovery with supply issues all stemming from them. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:03:11 </td>
   <td style="text-align:left;"> $SPY You all can thank $AAPl for lifting the entire index.  $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:03:10 </td>
   <td style="text-align:left;"> $AAPL $SPY $IWM $QQQ  apple just avoided the nail in the coffin. thanks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:02:54 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL Unless both $AMZN and $GOOGL F@#$% up their earnings(next week), Apple sales records earnings of $123.90 billion(actual) vs $118.28 billion (estimate) &amp;quot;could be&amp;quot; the beginning of the normalizing process for the market that has been skittish over the first rate hike by the FED. GLTA. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:02:51 </td>
   <td style="text-align:left;"> $QQQ Bears! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:02:48 </td>
   <td style="text-align:left;"> $aapl $spy $qqq aapl will take over 3T MC tomorrow 🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:02:42 </td>
   <td style="text-align:left;"> $SPY $DJIA $NASDAQ $QQQ Exactly as i said earlier. Cook says supply chain improving.

We will be 5% higher by Monday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:02:14 </td>
   <td style="text-align:left;"> $AAPL $AAPL CEO Tim Cook says they will not provide guidance because of supply chain issues
Blood Soon $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:01:56 </td>
   <td style="text-align:left;"> $QQQ I just don&amp;#39;t understand - any active trader on here, why didn&amp;#39;t you get out?  Oil and natural gas are the unequivocal plays of 2022.  This will hemorrhage throughout the year, but the major bleeding will occur when the insane USD bull market comes to a screeching halt.  Guess what happens when the USD falls?  Oil and NG go to the moon.  You can still get out but there will be some wound licking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:01:35 </td>
   <td style="text-align:left;"> $SPY guidance cruel for Apple $AAPl $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:01:19 </td>
   <td style="text-align:left;"> $QQQ just looking at some of these prices on 100s of tech stocks. Wow! It&amp;#39;s buy time!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:01:09 </td>
   <td style="text-align:left;"> $AAPL can we finally get a green day $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 06:00:24 </td>
   <td style="text-align:left;"> $SPY $QQQ $ITOT $AAPL LOTS OF SICKS BEARS C...  HERE !!! SICK. WANT TO TANK THE MARKET AFTER THIS &amp;quot;BUY THE DIP&amp;quot; OPP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 05:59:42 </td>
   <td style="text-align:left;"> $AAPL $SPY $NASDAQ $QQQ BOOM
Smart money habe benn loading since yesterday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 05:59:04 </td>
   <td style="text-align:left;"> $SPY $QQQ With the strong earnings from $AAPL, nothing can save the bears tomorrow lol 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 05:58:54 </td>
   <td style="text-align:left;"> $AAPL Market is a forward looking entity and its looking forward to rates $NXPI
$QQQ $NDX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 05:58:37 </td>
   <td style="text-align:left;"> $QQQ $AAPL Aapl where are you ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 05:58:32 </td>
   <td style="text-align:left;"> $BTC.X $SPY $QQQ who supports Biden? 
Yes : comment 
No : like </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 05:57:56 </td>
   <td style="text-align:left;"> $QQQ So 1 stock in going to help everything and fix the economy?? A minor beat magically fixes everything?? Sure it could be up tomorrow, but some point reality will set in, and a rug will be pulled... do I want it to happen? Fuck no... is our market toxic ad fuck right now? You better believe it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 05:57:48 </td>
   <td style="text-align:left;"> $SPY calls may work out after all! 
 
$QQQ on radar on Friday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 05:57:23 </td>
   <td style="text-align:left;"> $QQQ $AAPL going up on very low volume 
Looks weak like everything else </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 05:57:11 </td>
   <td style="text-align:left;"> $aapl some might have expected a bigger beat, agree, and ipad sales missed.  $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 05:57:06 </td>
   <td style="text-align:left;"> $AAPL 4 trillion market cap so you can prop up the entire market $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 05:57:02 </td>
   <td style="text-align:left;"> $AAPL Supply issues and shipping problems with no clear guidance? Now I wish I bought  more puts. Short this pos like we did with tesla! $TSLA $QQQ $VIX $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 05:56:41 </td>
   <td style="text-align:left;"> $QQQ still got 5% to fall btw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 05:55:49 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWN  Don&amp;#39;t worry all green in the futures, will open green and then close deep red into the weekend and then $BTC.X and $ETH.X will sell off over the weekend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 05:54:42 </td>
   <td style="text-align:left;"> $AAPL won’t post guidance!? lol $QQQ big boys getting out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 05:54:40 </td>
   <td style="text-align:left;"> $QQQ $AAPL if the futures rip tonight I will believe it for once… growth is back? For at least a week :) be smart. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 05:54:26 </td>
   <td style="text-align:left;"> $QQQ market not healthy . Really 
I am leaning towards just wait $QQQ is again at Above MA200 , and have a direction 

Right now we’ll below MA200 and last time the index $QQQ broke MA and stay there for days was 2020 pandemia dump and 2018 end of year sell off 

Both -17% below ma200 at the bottom 
If we apply the same : $QQQ 305$ bottom </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-28 05:54:05 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA 

So many bag holders... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:14:54 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $BTC $AAPL  Volatility got the markets gas break dippin! Tell me when to Go tell me when to Goooo 📈📉📈📉📈📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:14:51 </td>
   <td style="text-align:left;"> $AAPL good see a nice pump and then can ride outs for Friday . Let see how it goes. For updates hit the follow and join the sessions </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:14:15 </td>
   <td style="text-align:left;"> $AAPL bulls vs bears all day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:13:39 </td>
   <td style="text-align:left;"> $AAPL when aapl gives a free membership to pornhub, then ill buy my first mac book, until then ima short it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:13:38 </td>
   <td style="text-align:left;"> $AAPL Bears get absolutely rekt. Let’s see screen shots of the put positions </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:12:57 </td>
   <td style="text-align:left;"> $AAPL if you’re bearish on apple just get out of the stock market lmao. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:12:37 </td>
   <td style="text-align:left;"> $AAPL  got a boner after hours </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:11:45 </td>
   <td style="text-align:left;"> $AAPL Lick my dogs balls bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:11:36 </td>
   <td style="text-align:left;"> $AAPL same as last time great pr ran after hours opening red as Fuxk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:11:17 </td>
   <td style="text-align:left;"> $AAPL Great opportunity to get some long puts on this bad boy tomorrow for 80% off clearance sale. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:11:04 </td>
   <td style="text-align:left;"> All future bounces are a chance to sell. Fed Put no longer a factor, Powell&amp;#39;s focused on inflation to protect POTUS ratings. 🐻 markets call for selling ALL $SPY  $QQQ  $DJIA  &amp;amp; $AAPL  included. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:10:47 </td>
   <td style="text-align:left;"> $AAPL  better grab dem shares. Don&amp;#39;t know what to tell ya a L is a. L </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:10:07 </td>
   <td style="text-align:left;"> $AAPL 8 bucks, that&amp;#39;s a nice post market move. Congrats to all. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:09:39 </td>
   <td style="text-align:left;"> $TSLA $AAPL $NIO Futures way up, so will be red by open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:09:02 </td>
   <td style="text-align:left;"> $VIAC Tim $AAPL needs to buy viacomcbs soon. Frankly, it&amp;#39;s quite racist he hasn&amp;#39;t already. He can own Beats by Dre and BET for Dre. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:08:53 </td>
   <td style="text-align:left;"> If you bought $AAPL Apple this week before earnings that entry would still be 99% likely above the price it is at now 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:08:31 </td>
   <td style="text-align:left;"> It seems simple - it’s all about the overnight sessions - bears get absolutely raped if they hold overnight because just like all of 2021 the bulls control markets during futures sessions as they can get way more bang for their buck during the low liquidity of overnight sessions $spy $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:08:22 </td>
   <td style="text-align:left;"> $AAPL what I don&amp;#39;t get is this.  The market dumped huge gains KNOWING Apple reporting AH and Apple crushes earnings all the time so if that was all it was gonna take to &amp;quot;save the market&amp;quot; then why did everyone dump off end of day knowing Apple would crush estimates AGAIN. that&amp;#39;s why I just feel like a rug pull is coming after market opens and it will bleed into end of day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:08:16 </td>
   <td style="text-align:left;"> $AAPL Rule of Thumb when you hear the bears chirping be confident the stock will be going up! Apple is not a penny Stock have confidence ! Long and Strong 💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:07:36 </td>
   <td style="text-align:left;"> $AAPL all these elite company’s are run by satanic cults it’s crazy. They will never fail </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:07:27 </td>
   <td style="text-align:left;"> $AAPL $MSFT showing why tech demands higher forward PE ratios. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:07:11 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:06:41 </td>
   <td style="text-align:left;"> $AAPL when do upgrades start being posted. Let’s take 200 to 215 upgrade </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:05:35 </td>
   <td style="text-align:left;"> latexebae8a384b31fd6d4a482b577b2cd276aapl goes nuts insane quarter despite supply problems oh my  
 
$spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:04:48 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ tomorrow morning will be charitable </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:04:45 </td>
   <td style="text-align:left;"> $SPY $AAPl until the US Fed Meeting in March..  Full truck loads incoming!!   #Overtime hours   $TLT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:04:17 </td>
   <td style="text-align:left;"> $AAPL jeez. Growing like it’s a startup </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:03:57 </td>
   <td style="text-align:left;"> $AAPL  
 
What a beast! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:03:56 </td>
   <td style="text-align:left;"> $AAPL good job longs, see you in the am. Happy with earnings for sure!  Gotta love Apple 🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:03:51 </td>
   <td style="text-align:left;"> $AAPL Gotta give props to Tim Cook even though I’m a bear probably about to lose a couple grand in puts. He handled that earning call like a true lawyer. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:03:40 </td>
   <td style="text-align:left;"> $AAPL let’s get to $200 now! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:03:39 </td>
   <td style="text-align:left;"> $AAPL all they wanna do is eat the $150 put Premiums Tomorrow until the puts are worthless. This was obvious. I’ll eat $150 credit spreads for Feb. 18 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:03:34 </td>
   <td style="text-align:left;"> $AAPL Correct-ion </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:03:28 </td>
   <td style="text-align:left;"> $AAPL market is currently in denial phase. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:03:18 </td>
   <td style="text-align:left;"> $AAPL well I’m killing myself now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:03:01 </td>
   <td style="text-align:left;"> $AAPL $MSFT $QQQ load the hell upppp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:02:10 </td>
   <td style="text-align:left;"> $AAPL 
190 next month </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:02:05 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-01-27 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=4oUnk_vCrsI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:01:58 </td>
   <td style="text-align:left;"> $AAPL  anyone want to laugh and guess how much he lost? 😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:01:53 </td>
   <td style="text-align:left;"> $AAPL Simulated Weekly $165.0 CALLS for Friday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:01:44 </td>
   <td style="text-align:left;"> $AAPL I hope when we wake up in the morning, this doesn’t disappear. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:01:37 </td>
   <td style="text-align:left;"> $AAPL need to buy viac and become the dominant force in streaming, those sub numbers across all apple services would sky rocket. Imagine yellowstone and 1883 exclusive on apple tv +. Are you listening Tim? You can make that buy on just the iPhone revenue for a single quarter and deal Netflix their death blow. Something to think about. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:01:18 </td>
   <td style="text-align:left;"> $AAPL tomorrow🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:01:17 </td>
   <td style="text-align:left;"> $AAPL likely more puts than calls expiring tomorrow. 😅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:01:16 </td>
   <td style="text-align:left;"> USMarkets most active stocks during last session $AMD $AAPL $FAMI $F $INTC  
 
Learn more: https://www.finscreener.org/screener/most-active/stocks/us-markets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:01:04 </td>
   <td style="text-align:left;"> $AAPL sadly the fact that they didn’t have guidance will def clap this. People are worried about the future not the past 😭 $SPY $QQQ but won’t be surprised from a slight rally Friday just to relief some of the oversold signals then Monday prob dumps more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:00:21 </td>
   <td style="text-align:left;"> $AAPL gonna tank when futures open. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:00:03 </td>
   <td style="text-align:left;"> $AAPL beard today thinking this was tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 09:00:00 </td>
   <td style="text-align:left;"> $MTTR $AAPL Acquisition season around the corner. Apple going shopping soon. Matterport, you&amp;#39;re 1st in line... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:59:39 </td>
   <td style="text-align:left;"> $AAPL Absolute beast. This thing is gonna open at like $172 lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:59:38 </td>
   <td style="text-align:left;"> $AAPL 22 cent div prettt solid </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:59:27 </td>
   <td style="text-align:left;"> $AAPL Notice how Cook manages to speak after earnings and not completely crash the stock. Elon Musk over at $TSLA should study </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:59:25 </td>
   <td style="text-align:left;"> $AAPL damn son I&amp;#39;m glad I&amp;#39;m not a bear right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:59:18 </td>
   <td style="text-align:left;"> $SPY 
These Bulls act like $AAPL earnings solved our inflation problem. 😂😂💀💀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:59:14 </td>
   <td style="text-align:left;"> $AAPL sitting right at $167 max pain, just as I  called it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:59:09 </td>
   <td style="text-align:left;"> $AAPL 5 162.50 contracts at close 🙏🙏🙏 hope we get paid. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:59:05 </td>
   <td style="text-align:left;"> $AAPL not going to reverse the whole market...  
Jerome Powell beat around the bush on interest rates moving forward and reiterated numerous times how &amp;quot;great our job market is&amp;quot;. 
 
Like, you mean how many open jobs are available in the job market??  
 
Lol 
 
Supply chains are suffering for real, no joke. Inflation, interest rates, COVID, war.... 
Manufactured chaos.  
Totally preventable. 
The writing is on the wall.  
Read it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:59:00 </td>
   <td style="text-align:left;"> $AAPL and when is the world falling off the cliff? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:58:58 </td>
   <td style="text-align:left;"> $AAPL 
YEAH BABY!!   I’m stacking those LEAPS calls!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:58:56 </td>
   <td style="text-align:left;"> $AAPL get in while you can… $XCUR🔥🔥 the next penny multiplier 📈📈 get in before .20🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:58:48 </td>
   <td style="text-align:left;"> $AAPL Still waiting for Ah dump where you at bears??😊😊😊 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:58:21 </td>
   <td style="text-align:left;"> $AAPL bears sound so desperate in here tonight 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:57:51 </td>
   <td style="text-align:left;"> $TSLA I think this just initiated the market crash today.  Rotating to Puts on $AAPL now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:57:30 </td>
   <td style="text-align:left;"> $UVXY I truly believe NAS futures have a chance to be up 500 tomo am. Thank you $AAPL for saving us all from the depths of hell. Maybe 1000 point NAS day coming. I sh*t you not. Good luck all who are still afraid. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:57:22 </td>
   <td style="text-align:left;"> $AAPL tick tock tick tock shorts…lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:57:16 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Earnings alert: Apple on the move after earnings https://www.stck.pro/news/AAPL/22074785 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:57:10 </td>
   <td style="text-align:left;"> $SPY $QQQ pretty sure $AAPL just put a short term floor under the indexes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:56:27 </td>
   <td style="text-align:left;"> $AAPL $HOOD $RBLX Last 2 months I lost more than 40K that disappointed me, Finally doubled my account (nearly 48k) in a week after join their chat room and using their alerts. 
 
 Highly recommended! It&amp;#39;s free joining!! discord.io/fBGVa29wnf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:56:21 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL Friday $421 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:56:06 </td>
   <td style="text-align:left;"> $AAPL $170 calls finna print tomorrow!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:56:03 </td>
   <td style="text-align:left;"> latexa30b39718fda0757fb8eee9d3af97f1eMA
$V </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:55:10 </td>
   <td style="text-align:left;"> $AAPL 

Daniel Ives has an Outperform rating on Apple with a $200 price target. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:55:07 </td>
   <td style="text-align:left;"> $AAPL yall are buying calls tomorrow because you see good earnings in a shitty market, im buying puts tomorrow because i see good earnings in a shitty market. We aint the same. Dont be naive. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:55:04 </td>
   <td style="text-align:left;"> $FJB.X Cant wait to drink the tears of some iPhone fan bois when we rip that #1 spot from $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:54:59 </td>
   <td style="text-align:left;"> $AAPL 
I&amp;#39;ll be honest, if I had Apple Calls, I&amp;#39;m selling if first thing tomorrow. After seeing what happened to $TSLA , there&amp;#39;s no way I&amp;#39;m risking it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:54:34 </td>
   <td style="text-align:left;"> $SPY $AAPL Bullish on these two. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:54:04 </td>
   <td style="text-align:left;"> $AAPL own it, don’t trade it 💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:54:01 </td>
   <td style="text-align:left;"> $AAPL  🍏 Remember, the next Five Days are “Historically Seasonally Strong” for Equites.  Trade smart.  History, might repeat itself. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:53:59 </td>
   <td style="text-align:left;"> $AAPL you can&amp;#39;t be serious... Apple has the best numbers and then only these small percentages... you bears are kidding us🤔🤷‍♀️👋😆😆😆😆😆😆😆😆😆😆🧚‍♀️🧚‍♀️🧚‍♀️🧚‍♀️🧚‍♀️🧚‍♀️❤ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:53:41 </td>
   <td style="text-align:left;"> $AAPL bulls trap just wait </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:53:09 </td>
   <td style="text-align:left;"> $SPY Amazing but it looks like we could do a third straight day of identical movement .

Biden: Making market volatility great again.

PCE likely tempers that pattern.
Wait, &amp;quot;tempers,&amp;quot; is not right word. 

How about inflates the pattern,  to the downside

$QQQ $AAPL $KLAC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:52:53 </td>
   <td style="text-align:left;"> $AAPL this going to do what Tesla did. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:52:50 </td>
   <td style="text-align:left;"> $AAPL FOMO for apple car coming :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:52:34 </td>
   <td style="text-align:left;"> $AAPL bears getting louder and louder. While bulls just Poppin bottles </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:52:34 </td>
   <td style="text-align:left;"> $AAPL $200 tomorrow, break some records.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:52:19 </td>
   <td style="text-align:left;"> $AAPL there she goes, right on cue.  Faithful as always Go baby go!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:52:06 </td>
   <td style="text-align:left;"> $AAPL 

Goodnight, bears.  I really don’t care if it sells off tomorrow or next week.  Buying more.  That being said, I hope y’all burn tomorrow‼️ Y’all are a fraud for the scam you been running all these years on $AAPL and you’ll be proven wrong, again and again and again 🐻🔥✅🤑😅🍎😑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:51:27 </td>
   <td style="text-align:left;"> $AAPL what a banger and still have some more room to run! Thanks to @RiskVsReward for the tech setup! Next resistance at $168!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:50:39 </td>
   <td style="text-align:left;"> $SPY  $QQQ  These shits aint holding nothing up and that little fake pump on $AAPL aint fooling anyone. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:49:44 </td>
   <td style="text-align:left;"> $AAPL Gotta make the bulls feel safe overnight...trapping more before 8:00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:49:43 </td>
   <td style="text-align:left;"> $AAPL this is the best place to buy puts tomorrow in the market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:49:41 </td>
   <td style="text-align:left;"> $QQQ $SPY Both of you&amp;#39;s are going to the shit house tomorrow. Not even $AAPL can save you. 🔻🚽 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:49:40 </td>
   <td style="text-align:left;"> $AAPL and the rush to cover begins!! 😃😃😃 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:49:40 </td>
   <td style="text-align:left;"> $AAPL Pt 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:49:29 </td>
   <td style="text-align:left;"> $AAPL 175 close the week potential </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:48:49 </td>
   <td style="text-align:left;"> $AAPL not a 1 man army of stocks don’t hold their weight it will be dragged down with apple. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:48:32 </td>
   <td style="text-align:left;"> $AAPL 
Red delicious apples are the best !!! Who wants a sour Granny apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:48:30 </td>
   <td style="text-align:left;"> $AAPL Just bought 2 new iPhones to help the cause. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:48:30 </td>
   <td style="text-align:left;"> $AAPL unfortunately it will be bearish tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:48:12 </td>
   <td style="text-align:left;"> $SPY  $AAPL gettin a boner after hours </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:47:44 </td>
   <td style="text-align:left;"> $AAPL for charity tomorrow apple will be going (RED) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:47:41 </td>
   <td style="text-align:left;"> $AAPL the market savior </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:47:17 </td>
   <td style="text-align:left;"> $AAPL and let the coving begin 😃😃😃 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:47:11 </td>
   <td style="text-align:left;"> $AAPL this is same set up as Tesla yesterday.  Pump earnings and kill it the next day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:47:10 </td>
   <td style="text-align:left;"> $AAPL bye bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:46:55 </td>
   <td style="text-align:left;"> $AAPL $QQQ $SPY any price movement not in the interest of my positions is targeted manipulation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:46:46 </td>
   <td style="text-align:left;"> $AAPL like this if you had a bear talk shit and now they’ve just disappeared </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:46:38 </td>
   <td style="text-align:left;"> $AAPL inflation would magically diminish in Feb. Things are looking good again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:46:38 </td>
   <td style="text-align:left;"> #30 Robinhood Dippin&amp;#39; Below $10 Tesla Slide Ackman Buying Netflix Apple Rip $HOOD $TSLA $NFLX $AAPL https://youtu.be/7qaOyvtc8BQ via  
@YouTube </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:46:29 </td>
   <td style="text-align:left;"> $AAPL biggy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:45:54 </td>
   <td style="text-align:left;"> $AAPL 

Earnings 🌶💰

Tim Cook this is for you 😉

https://www.instagram.com/doctorstockz/reel/CZQQMG-BQTB/?utm_medium=copy_link </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:45:53 </td>
   <td style="text-align:left;"> $AAPL Maybe AAPL can single handedly carry the NAZ for all of 2022, while the rest keeps of tech keeps getting obliterated for another yr straight. 🤣🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:45:30 </td>
   <td style="text-align:left;"> $AAPL what am I missing? It grew 11% year over year and is facing tough comps now. Has a pe like Shopify. If this isn&amp;#39;t faded tomorrow or in the near future I&amp;#39;ll be very surprised. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:44:36 </td>
   <td style="text-align:left;"> $AAPL I can’t wait to hear the Bulls crying manipulation tomorrow🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:44:08 </td>
   <td style="text-align:left;"> $AAPL $SPY $MSFT Inverse Expectations 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:44:02 </td>
   <td style="text-align:left;"> $AAPL almost at the 15 minute warning, get the popcorn ready!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:43:50 </td>
   <td style="text-align:left;"> $AAPL $MSFT $AMD $QQQ

Margin Just called again, he wasn&amp;#39;t friendly this time though; he last time said, &amp;quot;It&amp;#39;s important.&amp;quot; 
I said, &amp;quot;you&amp;#39;d be home in 15 minutes. And, it&amp;#39;s almost as if he was watching his watch for exactly 15 minutes.&amp;quot;

Yeah, K, I am almost home and---&amp;quot;Honey, just sec, phone ringing, OH,  it&amp;#39;s Margin Just&amp;#39;s caller ID again.&amp;quot; 

YEAH, honey, I&amp;#39;m at the bank, I was wondering, do you have any money on..... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:43:43 </td>
   <td style="text-align:left;"> $AAPL $SPY anyone else think peak earnings for awhile? Or wage increases gonna help out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:43:14 </td>
   <td style="text-align:left;"> $AAPL Huge congrats again to the bulls. Earnings were pure nuts. Still in shock that SPY and QQQ are going red soon AH. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:43:09 </td>
   <td style="text-align:left;"> $AAPL anything on raising the divvy? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:43:02 </td>
   <td style="text-align:left;"> $AAPL when the bears stop posting back and go back to being broke hahahah </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:42:32 </td>
   <td style="text-align:left;"> $AAPL    🍏:  The Trader needed $165…and, he got it!  $MultiMillions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:42:31 </td>
   <td style="text-align:left;"> $AAPL $QQQ $TSLA  $SPY 

Chief Executive Tim Cook said Thursday that despite ongoing issues affecting the availability of supplies used in some of its products, the company is still managing to turn in the strongest sales in its history 💎🍏💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:42:15 </td>
   <td style="text-align:left;"> $AAPL markets sinking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:41:32 </td>
   <td style="text-align:left;"> $AAPL Apple gets the love even with their lower guidance for &amp;quot;slower&amp;quot; development.  In the mean time, $NFLX beats and delivers all metrics and says &amp;quot;slower growth of subscribers&amp;quot; and stock plummets 28%.   Netflix would&amp;#39;ve dropped even if they raised guidance because the market is rigged.  $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:41:15 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:40:49 </td>
   <td style="text-align:left;"> $AAPL  put will print tomorrow sorry bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:40:47 </td>
   <td style="text-align:left;"> $SPY $AAPL $INDO $TSLA $QQQ If you really want to make huge profits on trading then, Join this winning chat discord.io/MqakycG 
 
 
##01 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:40:19 </td>
   <td style="text-align:left;"> $AAPL Delays should be expected </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:40:09 </td>
   <td style="text-align:left;"> $TSLA $AAPL  $SPY   #1 in the world 💡💡💡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:39:29 </td>
   <td style="text-align:left;"> $AAPL buy and relax and watch your wealth grow with the worlds savings account. $180 tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:39:28 </td>
   <td style="text-align:left;"> $AAPL please bring Tesla and Amazon up tomorrow 🤞 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:39:02 </td>
   <td style="text-align:left;"> $AAPL 22 minutes to get out bears, tomorrow will be brutal!!  😃 hehehe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:38:47 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA The futes are red right now, but once again the market can&amp;#39;t ignore great earnings! 👉 $AAPL  Green by morning bulls! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:38:42 </td>
   <td style="text-align:left;"> $AAPL   🍏👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:38:34 </td>
   <td style="text-align:left;"> $AAPL Apple ain’t saving shit… just prolonging the inevitable. Monster earnings tho great company bearish on market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:38:30 </td>
   <td style="text-align:left;"> $FJB.X WE GONNA MAKE APPLE JUICE OUT OF YOUR #1 SPOT $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:38:28 </td>
   <td style="text-align:left;"> $SPY look for Asia to follow through on $AAPL earnings.   Gap up, then fade into closing.   Ain&amp;#39;t that the program now?  $UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:38:16 </td>
   <td style="text-align:left;"> $TSLA  $AAPL $SPY  That part !!! Tesla is the leading the race !!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:38:12 </td>
   <td style="text-align:left;"> $AAPL someone has to step up to become a voice of average investors this market is rigged it’s never ending </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:37:54 </td>
   <td style="text-align:left;"> $FJB.X WE ARE COMING FOR $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:37:53 </td>
   <td style="text-align:left;"> $AAPL $SPY $INTC There’s too many reasons why you shouldn’t invest right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:37:52 </td>
   <td style="text-align:left;"> $AAPL we will dump this garbage to 140 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:37:48 </td>
   <td style="text-align:left;"> $AAPL nothing negative with the exception of iPad sales, other than that over the top in every other platform/level </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:37:37 </td>
   <td style="text-align:left;"> $AAPL 
Imagine having killer Earnings but only go up 4% in your stock price. 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:36:45 </td>
   <td style="text-align:left;"> $AAPL  ready to Short tomorrow at 67 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:36:17 </td>
   <td style="text-align:left;"> $AAPL tesla P/e ratio is 100..apple p/e ratio is 29...enough said </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:36:13 </td>
   <td style="text-align:left;"> $AAPL can’t hold $167 ggs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:36:09 </td>
   <td style="text-align:left;"> $AAPL apple is saving market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:36:08 </td>
   <td style="text-align:left;"> $aapl $spy $qqq $ndx $xlk https://www.youtube.com/watch?v=ddEuU458vlw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:35:57 </td>
   <td style="text-align:left;"> $AAPL Asian market be like… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:35:43 </td>
   <td style="text-align:left;"> $AAPL market crash? https://twitter.com/itradecontracts/status/1486834643437600769?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:35:13 </td>
   <td style="text-align:left;"> $AAPL bottom line still holding, fact dictate nothing less.  Apple rise as always will continue up up up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:35:04 </td>
   <td style="text-align:left;"> $AAPL Morning will be bullish, then time for the selloff 🙂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:34:59 </td>
   <td style="text-align:left;"> $AAPL just keep buying calls huh? *perma bulls were premie all week. 🩸☠️  “expect our revenue growth rate to decelerate from the December quarter.”  Topped. Enjoy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:34:58 </td>
   <td style="text-align:left;"> $AAPL 
If the $TSLA cult can&amp;#39;t hold Tesla, then what makes you think Apple people can? 😂🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:34:53 </td>
   <td style="text-align:left;"> Tim Cook says the $AAPL card is the #1 credit card by customer satisfaction. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:34:40 </td>
   <td style="text-align:left;"> 🍎 $AAPL CC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:34:37 </td>
   <td style="text-align:left;"> $AAPL $170 before the Bell tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:34:31 </td>
   <td style="text-align:left;"> $AAPL $QQQ 

Apple and the rest of tech will be red at open

Massive selling in Japan.  EU will follow.

Tomorrow is going to be the worst day of the year. 

If you can sell now, sell. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:34:30 </td>
   <td style="text-align:left;"> $AAPL Short term it may go down but long term it is a good buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:34:22 </td>
   <td style="text-align:left;"> $AAPL will open at 170 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:34:21 </td>
   <td style="text-align:left;"> $AAPL   🍏Repost:  👀👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:34:01 </td>
   <td style="text-align:left;"> $AAPL everyone is addicted to their iPhone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:33:55 </td>
   <td style="text-align:left;"> $AAPL PUMP &amp;amp; DUMP.  AAPL CAN’T SAVE THE MARKET. 🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:33:44 </td>
   <td style="text-align:left;"> $AAPL Ultimate flush tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:33:22 </td>
   <td style="text-align:left;"> $SPY Margin Just called 
$QQQ $AAPL $XLY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:33:22 </td>
   <td style="text-align:left;"> $AAPL puts to $0 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:33:20 </td>
   <td style="text-align:left;"> $SPY how was $aapl guidance in a nutshell? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:33:19 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL  $ARK  
  
Short them to hell with 500x leverage -&amp;gt; https://simplefx.com/n/_5039 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:32:52 </td>
   <td style="text-align:left;"> $AAPL weekly bull trap and red close on Monday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:32:48 </td>
   <td style="text-align:left;"> $AAPL Now that ER is out of the way, expect a spectacular bounce here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:32:41 </td>
   <td style="text-align:left;"> $AAPL $HOOD $RBLX  I made a huge profit stay with this community more than 93K+ with in 4 months.  
So many many thanks to&amp;gt;&amp;gt; discord.io/stock_alerts !!You can earn as you want!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:32:38 </td>
   <td style="text-align:left;"> $AAPL pretty good probably it will be flat or red tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:32:26 </td>
   <td style="text-align:left;"> $AAPL Not holding like you would want before a Friday! Lets Gooooo... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:32:14 </td>
   <td style="text-align:left;"> $AAPL Apple 785m subscribers paying 1 or many monthly fees … that’s loyalty to the brand </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:32:08 </td>
   <td style="text-align:left;"> $AAPL i think this is going to get rocked harder than tsla tomorrow, market doesn&amp;#39;t care about your earnings. where is the new ipod? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:32:01 </td>
   <td style="text-align:left;"> $AAPL ready to Short tomorrow at 67 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:31:59 </td>
   <td style="text-align:left;"> Stock futures rise as market set to wrap up a wild week, Apple shares pop

$SPX $AAPL

https://www.cnbc.com/2022/01/27/stock-market-futures-open-to-close-new.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:31:50 </td>
   <td style="text-align:left;"> $AAPL Mega-cap holders at this juncture: It would be wise to hear what Sir Jeremy Grantham had to say, IMHO. 
In this super-mega-cap down-trend, be extremly nimble to book your profits, lest your profits turn into losses in a couple days! 
Super-Mega-caps&amp;#39; charts are in a linear marching order to their respective 52-week lows it seems. JP&amp;#39;s vacuum-pump has 
started in earnest to suck-in the liquidity, severely compressing these multiples now.  Until the multiples match to 
the median-growth-rate of next three-years, (additional -10% for a good measure, in this accelerated-down-elevator momentum of this year)  the selling may not stop.  Hedgy-boys are in a mood now to extract the cash anywhere they can find it and here they find 
some profits to book and thus, the avalanche has started! Be extra careful! May the Lord Bless us all! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:31:32 </td>
   <td style="text-align:left;"> $AAPL Bearish 🧸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:31:21 </td>
   <td style="text-align:left;"> $AAPL dam you greedy shorts 
How will things ever move up when you idiots keep bringing it down
Shorting will be banned in the future </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:31:20 </td>
   <td style="text-align:left;"> $AAPL smart bulls gonna take profit tmr, computers definitely gonna take profit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:30:45 </td>
   <td style="text-align:left;"> $AAPL $MATIC.X is rocketing 🚀🐳💎💯💰🔥🔥🔥

Let’s go Polygon

Target price is $10,000.00 a coin within 15 years </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:30:30 </td>
   <td style="text-align:left;"> $SPY dont worry $AAPL sabed the market.. LMAOO🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:30:15 </td>
   <td style="text-align:left;"> $AAPL My worry is it’s still up 170% in under two years </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:30:11 </td>
   <td style="text-align:left;"> $AAPL I got an iPhone, it’s ok </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:29:48 </td>
   <td style="text-align:left;"> $AAPL Apple reports a parade of sales records as earnings top $30 billion for the first time, stock gains

https://www.marketwatch.com/story/apple-reports-a-parade-of-sales-records-as-earnings-top-30-billion-for-the-first-time-stock-gains-11643319426?mod=home-page </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:29:45 </td>
   <td style="text-align:left;"> $AAPL Metaverse vision &amp;gt; $FB Metaverse. It should be AR, not VR with Oculus. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:29:40 </td>
   <td style="text-align:left;"> $AAPL i hope no-one is actually paying these bears for these posts. In that regard they are pathetic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:29:40 </td>
   <td style="text-align:left;"> $AAPL should pop +10% tomorrow because too many idiots short pre earning and not enough idiots short post earning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:29:39 </td>
   <td style="text-align:left;"> $TSLA Tesla is the leading indicator of sentiment, and $AAPL Apple will never get Apple Car off the production line </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:29:36 </td>
   <td style="text-align:left;"> $AAPL HOLD!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:29:28 </td>
   <td style="text-align:left;"> $AAPL 🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:29:24 </td>
   <td style="text-align:left;"> $AAPL y up ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:29:19 </td>
   <td style="text-align:left;"> $AAPL Updated for today&amp;#39;s results </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:28:57 </td>
   <td style="text-align:left;"> $SPY $AAPL nice guidance bro. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:28:02 </td>
   <td style="text-align:left;"> $AAPL A lot of butt hurt going on around here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:26:56 </td>
   <td style="text-align:left;"> $SPY 31k is what I’ve shorting $AAPL with tomorrow.
It ain’t much but it’s honest work </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:26:37 </td>
   <td style="text-align:left;"> $AAPL wooooot woooot and $HOOD .. god.. youre painful to own </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:26:31 </td>
   <td style="text-align:left;"> $AAPL in sha allauah FRIDAY SELL OFF OTW 🐻 🌈 🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:26:30 </td>
   <td style="text-align:left;"> $aapl bears right now  https://i.kym-cdn.com/photos/images/original/001/285/944/d9d.jpg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:26:08 </td>
   <td style="text-align:left;"> $AAPL zzzzzzzz boring ! Their earnings reaction was about as innovative as their products ! A nothing burger 🍔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:26:00 </td>
   <td style="text-align:left;"> $AAPL Dow will be shaded and 5k coming soon 🔜 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:25:53 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:25:45 </td>
   <td style="text-align:left;"> $IWM so funny how AH chasers got trapped in high 192s because they got confused over $AAPL and thought they had something to do with the Russell smh lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:25:26 </td>
   <td style="text-align:left;"> $SPY the daily drill begins… overnight bloodbath, morning run… rinse repeat until one day it limits down hard! Alone $AAPL cant save the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:25:20 </td>
   <td style="text-align:left;"> $AAPL https://www.wsj.com/articles/apples-supply-chain-is-its-strongest-link-11643326241?mod=wsj_RHF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:25:05 </td>
   <td style="text-align:left;"> $AAPL dump off tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:24:59 </td>
   <td style="text-align:left;"> $AAPL This was at $168 just a few days ago - just chill and hold - with such great earnings it will shoot higher </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:24:08 </td>
   <td style="text-align:left;"> $AAPL $MSFT $FB $GOOG  For long term gains, just buy these 4 and you’ll be rewarded with at least 20% per year. 
Such solid companies, and when their organic growth slows down, they have all the power in the world to do M&amp;amp;A. 

Beating estimates almost every time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:23:59 </td>
   <td style="text-align:left;"> $AAPL bears right now 🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:23:27 </td>
   <td style="text-align:left;"> $AAPL Shorts will scramble to cover the last half hour - this will go over $180 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:22:53 </td>
   <td style="text-align:left;"> $AAPL $hood tomorrow Hood green apple red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:22:48 </td>
   <td style="text-align:left;"> $AAPL bears are scared 😱 lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:22:32 </td>
   <td style="text-align:left;"> $AAPL This will sell off after initial pop .  The mega cap techs will be sold off next in this market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:22:20 </td>
   <td style="text-align:left;"> $AAPL $SPY grab some puts in the open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:21:48 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL $MSFT not very good news here… 👤 https://www.bloomberg.com/news/articles/2022-01-27/u-s-nato-respond-to-russia-rejecting-demands-ukraine-update </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:21:15 </td>
   <td style="text-align:left;"> $AAPL I’m a gay bear, u can be Nancy bullishski but my technical analsis says GET THE FUCK OUT 🌈 🐻 #bulltrap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:21:07 </td>
   <td style="text-align:left;"> $AAPL That should be illegal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:20:59 </td>
   <td style="text-align:left;"> $SPY here’s why tomorrow we’re going to have a great day!!! $AAPL  amazing 🤩 earnings 🚀 , $TSLA  rebound and much more but with those 2 should suffice 🚀🚀. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:20:14 </td>
   <td style="text-align:left;"> $AAPL Stocktwits still cracks me up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:20:10 </td>
   <td style="text-align:left;"> $spy $aapl I&amp;#39;m surprised that apple didn&amp;#39;t get clobbered after not giving guidance. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:20:06 </td>
   <td style="text-align:left;"> $AAPL Guidance bullet points anyone? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:20:05 </td>
   <td style="text-align:left;"> $AAPL for Bull . Let’s buy at least one more share . We can burn all the Bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:20:02 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:19:46 </td>
   <td style="text-align:left;"> $AAPL everyone talking like their calls or puts will be worth anything by the time market opens😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:19:30 </td>
   <td style="text-align:left;"> $AAPL apple today...Google and amazon next week..Amazon had record sales thus quarter also </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:19:22 </td>
   <td style="text-align:left;"> $AAPL see this trading sideways tommo both bears and bulls will be screwed … circle of life </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:19:21 </td>
   <td style="text-align:left;"> $AAPL 
You would think you&amp;#39;ll get a better price action with such gOod ER. 🤣💀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:18:52 </td>
   <td style="text-align:left;"> $TSLA $NIO $AAPL all I need! Second best TNA!! Kwyo! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:18:47 </td>
   <td style="text-align:left;"> $AAPL it reached its all time high on Jan 3rd at 180. So where do we go from here? Back to all time highs tomorrow while everything else is struggling? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:18:35 </td>
   <td style="text-align:left;"> $AAPL Such strong earnings and it barely pumped, the bubble of big tech  will soon be busting. Short cover target:$100, $80, $65! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:18:33 </td>
   <td style="text-align:left;"> $AAPL market conditions keep this down? Or is Apple the market lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:18:26 </td>
   <td style="text-align:left;"> $AAPL fuck Apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:18:15 </td>
   <td style="text-align:left;"> $AMD $ON $MRVL $NVDA All eye on $AAPL tomorrow for a bull massive come back </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:18:14 </td>
   <td style="text-align:left;"> $AAPL seeing an uptick in chatter on 4chan over the last 24 hours

Via topstonks.com/stocks/AAPL?st_aapl

#aapl    #4chan </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:18:07 </td>
   <td style="text-align:left;"> $AAPL where are all the bears at? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:18:06 </td>
   <td style="text-align:left;"> $AAPL wish I doubled up here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:17:41 </td>
   <td style="text-align:left;"> $AAPL “I’m in that hoe” - bulls getting trapped 🌈 🐻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:17:32 </td>
   <td style="text-align:left;"> $AAPL 
🎲😎🤣
Its bleeding slowly. All the 4% gain will gone before anyone able to secure profit. 🤣

https://tenor.com/Q4A5.gif </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:17:30 </td>
   <td style="text-align:left;"> $AAPL Who cares about the Apple flakes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:17:28 </td>
   <td style="text-align:left;"> $AAPL Welp, lost my gamble. That&amp;#39;s what I get for being greedy and not taking profit early. Congrats to everyone with a bullish position! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:17:17 </td>
   <td style="text-align:left;"> $AAPL only record earnings will save this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:17:13 </td>
   <td style="text-align:left;"> $AAPL 
Nobody wants to hold overpriced garbage. Sell of coming tomorrow most likely. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:16:43 </td>
   <td style="text-align:left;"> $AAPL holy wow up a whole 4% lol 😂 don’t spend it all in one place bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:16:32 </td>
   <td style="text-align:left;"> $AAPL The big ER &amp;quot;Changing of the Bags&amp;quot; can&amp;#39;t you see what&amp;#39;s happening? LMAO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:16:21 </td>
   <td style="text-align:left;"> $AAPL can’t wait too see last 15 mins </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:16:13 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : This is beyond what bulls were hoping for, Wedbush&amp;#39;s Dan Ives on Apple&amp;#39;s Q1 earnings https://www.stck.pro/news/AAPL/22074472 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:16:09 </td>
   <td style="text-align:left;"> $QQQ $AAPL did just enough to kiss the 200 on 1 hour. Tweezer top at that.  😬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:16:07 </td>
   <td style="text-align:left;"> $AAPL Closing at $170 - large buyers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:16:05 </td>
   <td style="text-align:left;"> $AAPL  Upgrades tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:16:03 </td>
   <td style="text-align:left;"> $AAPL 200+++ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:15:35 </td>
   <td style="text-align:left;"> $AAPL WHERE ALL THE BEARS I LOST MY GODDAMN LAST 40k on this shit #daddychill </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:15:26 </td>
   <td style="text-align:left;"> $AAPL that why I trade small caps used to volitility make 5-10% multiple times a month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:15:17 </td>
   <td style="text-align:left;"> $AAPL at 165 go short easy play </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:15:15 </td>
   <td style="text-align:left;"> $AAPL rug pull coming bulls! You been warned! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:14:31 </td>
   <td style="text-align:left;"> $AAPL it will go red last time I played earning got fucked on calls watch y’all will see </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:14:27 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL  
 
Short them to hell with 500x leverage https://simplefx.com/n/_5039 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:14:26 </td>
   <td style="text-align:left;"> $AAPL Time to buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:14:25 </td>
   <td style="text-align:left;"> $AAPL Saved the day again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:14:18 </td>
   <td style="text-align:left;"> $AAPL 172$ am </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:14:08 </td>
   <td style="text-align:left;"> $SPY HEY !! COMM ON . $AAPL  Itself wont save Market Correction 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:13:51 </td>
   <td style="text-align:left;"> $AAPL will drop some more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:13:42 </td>
   <td style="text-align:left;"> $AAPL so what now? $175 or $155 tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:13:27 </td>
   <td style="text-align:left;"> $AAPL i don’t hold any calls or puts but wouldn’t be surprised if it goes down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:12:58 </td>
   <td style="text-align:left;"> $AAPL like just be long forever buy every dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:12:45 </td>
   <td style="text-align:left;"> $AAPL Futures will be red by midnight...gap this AAPL down 🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:12:42 </td>
   <td style="text-align:left;"> $SPY 2020-2021 were the year of bubble under the disguise of covid. 2022 is a year of deflating and resetting the bubble created. $TSLA $AAPL can’t be excluded 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:12:40 </td>
   <td style="text-align:left;"> $AAPL talk to me about your puts bears? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:12:27 </td>
   <td style="text-align:left;"> $AAPL All money should be rotating here will hold up SPY QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:12:27 </td>
   <td style="text-align:left;"> $AAPL somebody tell me Cramer is saying buy so at least maybe I can get some sleep tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:12:13 </td>
   <td style="text-align:left;"> $AAPL https://seekingalpha.com/amp/article/4482282-apple-earnings-beat-calms-market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:12:08 </td>
   <td style="text-align:left;"> $AAPL lol bears will have a smack </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:11:24 </td>
   <td style="text-align:left;"> $AAPL Lot of nervous bears posting. 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:10:58 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:10:40 </td>
   <td style="text-align:left;"> $AAPL apple saved the stock market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:10:21 </td>
   <td style="text-align:left;"> $AAPL
Earning Report was already priced in. Ask your big Tech Brother $TSLA . Apple is about to end up in the same hospital. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:10:14 </td>
   <td style="text-align:left;"> $AAPL add another $7 by pre market 👀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:10:01 </td>
   <td style="text-align:left;"> $MSFT $AAPL $V their earnings just prove how retarded Stocktwits is </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:09:53 </td>
   <td style="text-align:left;"> $AAPL so many bears must have bet the farm on apple tanking. All this capitulation.  “Tomorrow it will tank” and “mark my words” posts. 

Look, you are not a good trader if you go short on at the bottom.   You are not a good trader if you buy ATH. My advice is you step away from trading for a few months and get some focus. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:09:48 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures sharply higher, thanks to $AAPL the bulls can finally celebrate tomorrow and have some extra money to spend for the weekend lol 😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:09:35 </td>
   <td style="text-align:left;"> $AAPL nice beat … 11% growth but they did say growth will reduce going forward than they said 2-3% impact on FX … basically puts you around 8-9% growth tops … Inflation is running at 7% YoY …. That puts real growth at 2% … so very minimal growth going forward  … really not that good of report especially with no commitments on projection just an statement saying solid growth </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:09:26 </td>
   <td style="text-align:left;"> $AAPL There’s a white pony black stallion pattern forming on the 1 hour. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:09:16 </td>
   <td style="text-align:left;"> If $QQQ and $SPY go negative after $AAPL earnings, we are in trouble. Not to mention all the 425 puts. Fugly!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:09:15 </td>
   <td style="text-align:left;"> $AAPL never seen Bears so desperate. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:09:11 </td>
   <td style="text-align:left;"> $AAPL you guys think aapl will hold the market... watch premarket when this thing drops </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:08:57 </td>
   <td style="text-align:left;"> $AAPL was gonna buy short term puts bc supply chain issue and to hedge for my long cal but y’all went up :’) I’m so happy for us :’) glad I only played $HOOD puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:08:51 </td>
   <td style="text-align:left;"> $AAPL I’m like Apple but can’t pull trigger for call at this time. Will play some PUT at 170 tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:08:49 </td>
   <td style="text-align:left;"> $AAPL max is $130 Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:08:48 </td>
   <td style="text-align:left;"> $AAPL rejected 😂🤮 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:08:45 </td>
   <td style="text-align:left;"> $AAPL best company of 2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:08:43 </td>
   <td style="text-align:left;"> $AAPL WILL DUMP TOM HAHAHHAA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:08:41 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ   IWM and DJT have already given up the monday low ... who is next????? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-28 08:08:31 </td>
   <td style="text-align:left;"> $AAPL Will it rally or dump like Tesla? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:14:54 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $BTC $AAPL  Volatility got the markets gas break dippin! Tell me when to Go tell me when to Goooo 📈📉📈📉📈📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:14:40 </td>
   <td style="text-align:left;"> $TSLA the duality of man lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:14:08 </td>
   <td style="text-align:left;"> $TSLA 

$100,000,000,000 in market cap lost in a day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:13:57 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $HOOD 

Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:13:57 </td>
   <td style="text-align:left;"> $TSLA where can we see ark bought Tesla today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:13:45 </td>
   <td style="text-align:left;"> $TSLA he told you he was selling... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:13:43 </td>
   <td style="text-align:left;"> $TSLA this could make a crazy move in either direction tomorrow. Could be printing. Follow for more updates on the play or join the live session 👍 It only takes a few seconds </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:13:02 </td>
   <td style="text-align:left;"> $TSLA Who start buying shares at 7:33pm and made me off by 4 points. You all loved losing money. I specifically said 830. Now it&amp;#39;s 834 and counting. SMH. I&amp;#39;m not being cocky or anything, but I&amp;#39;m good at this. Market Makers and everyone on this board, good luck tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:12:47 </td>
   <td style="text-align:left;"> $TSLA Tough titties Fling bear </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:12:32 </td>
   <td style="text-align:left;"> $TSLA  continues to fall this month. 11% drop today and is now sitting at $837 in after-hours trading.  
https://www.cnbc.com/2022/01/27/tesla-stock-investors-digest-new-vehicle-delays.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:12:21 </td>
   <td style="text-align:left;"> $TSLA everything is turning around tomorrow we rally going to 1500 💵💰🏦 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:12:03 </td>
   <td style="text-align:left;"> $TSLA I got it all plan out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:11:45 </td>
   <td style="text-align:left;"> $TSLA Tesla to 6k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:10:48 </td>
   <td style="text-align:left;"> $TSLA cathie buying Tesla so that&amp;#39;s it... it&amp;#39;s going down further...shorts will love this. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:10:44 </td>
   <td style="text-align:left;"> $TSLA Cathy bought.... then you know this is heading down to the 400s. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:10:42 </td>
   <td style="text-align:left;"> $TSLA you bears are going to be poor tomorrow if you didn’t sell your puts. KATHY BACK ON OUR SIDE BABY! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:10:40 </td>
   <td style="text-align:left;"> $TSLA remember when this was like $1200 and Elon I mean doge daddy was just talking up robots and cyber trucks and stuff. Well that’s all gone now and all he tweeters about is hamburgers and doge. There’s your clue. #fraud
 https://www.tradingview.com/chart/TSLA/XLT5y30E-Tesla-Trillion-Trillion-Trillion-Oh-My/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:10:35 </td>
   <td style="text-align:left;"> $LCID followed tesla right down the tubes.  Quit pretending you&amp;#39;re your own stock ticker. Lucid is at best a wet dream of $TSLA. 

Half the ppl here idealize getting crazy rich as if this is the next Tesla. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:10:15 </td>
   <td style="text-align:left;"> $TSLA   FSD pump didn’t work so now Elon is pumping robot B.S.   LOCK HIM UP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:10:07 </td>
   <td style="text-align:left;"> $TSLA  Will be looking for a 200dma bounce tomorrow for a scalp.  👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:10:05 </td>
   <td style="text-align:left;"> $TSLA NASDAQ futures is up 152. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:09:59 </td>
   <td style="text-align:left;"> $TSLA can Cathy buy options on ARKK? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:09:47 </td>
   <td style="text-align:left;"> $TSLA adding 2023 1500 call options. Holding 7 contracts as if today. Will buy one every dip . Either make millions or FUCK go back to my grand father coconut farm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:09:43 </td>
   <td style="text-align:left;"> Tesla given $325.00 PT by Barclays PLC. https://www.marketbeat.com/r/1705600 $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:09:41 </td>
   <td style="text-align:left;"> latex06d328672ae1e92e9cdc29200e0662b4 soon enough. Possibly even 550$ again. But I guess its not her money she&amp;#39;s using to buy the dip,so why not lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:09:39 </td>
   <td style="text-align:left;"> $TSLA $AAPL $NIO Futures way up, so will be red by open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:08:57 </td>
   <td style="text-align:left;"> $TSLA oh shit. Cathie bought 🤦‍♀️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:08:53 </td>
   <td style="text-align:left;"> $TSLA Cathie babe started loading .. let’s have a NFLX type of run and squeeze some shorts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:08:40 </td>
   <td style="text-align:left;"> $TSLA OMG $1000 calls got wiped out 80% wtf? 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:07:59 </td>
   <td style="text-align:left;"> $TSLA  We need Trump back  !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:07:58 </td>
   <td style="text-align:left;"> $TSLA Cathy s back 💵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:07:33 </td>
   <td style="text-align:left;"> $TSLA  EV stocks are  just agonizing with Biden </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:07:29 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:06:54 </td>
   <td style="text-align:left;"> $TDOC Cathie bought $TSLA smart finally  
 
she didn’t sell this or buy  
 
short squeeze coming for $TDOC  
 
hold on </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:06:17 </td>
   <td style="text-align:left;"> $TSLA aunt Kathy reloading. That can’t be good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:05:58 </td>
   <td style="text-align:left;"> $TSLA ARK just bought TSLA today😑

thought they were selling... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:05:49 </td>
   <td style="text-align:left;"> $TSLA Have no investment here but I would look at a reversal from here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:05:35 </td>
   <td style="text-align:left;"> $TSLA he should put his own money into those ridiculous robots, or focus on FSD.  What’s that 10 years now? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:05:00 </td>
   <td style="text-align:left;"> Technical indicators based on daily timeframe $TSLA  
 
Learn more: https://www.finscreener.org/technicals/indicators/us-markets?&amp;amp;tframe=4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:04:14 </td>
   <td style="text-align:left;"> I happen to agree with Elon Musk that Biden is a moron. It will not help $TSLA share price to be openly feuding with a senile old man over Twitter however. He should care more about the investors that have created all of his net worth. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:03:57 </td>
   <td style="text-align:left;"> $TSLA  
 
TSLA Rough trading day - looking for a rebound tomorrow. Will be watching closely in pre-market. It is still one of the top trending tickers on Twitter and StockTwits - with over 5 million impressions in the last 24hrs. 
 
Wanted to share the tool we built so you can track social and price trends in real-time. Gives you a  good view of what&amp;#39;s going on in the market. 
 
https://utradea.com/social-dashboard?utm_source=stocktwits&amp;amp;utm_medium=ssd-stocktwits&amp;amp;utm_campaign=sm_20220127 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:03:54 </td>
   <td style="text-align:left;"> $XPEV what the heck!! Cathy bought $TSLA today and not $XPEV </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:03:51 </td>
   <td style="text-align:left;"> $TSLA  better deposit  your money in your saving account 0.2% then long investing in Tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:03:25 </td>
   <td style="text-align:left;"> $TSLA Cathie is back baby </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:03:18 </td>
   <td style="text-align:left;"> $TSLA only for tomorrow. $855 target </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:02:55 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-27 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=fxdo4zsQeuc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:02:49 </td>
   <td style="text-align:left;"> $TSLA Dumb chasers need to be shook no matter how long it takes. Mr. M rules. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:02:39 </td>
   <td style="text-align:left;"> $TSLA May be Elon seen me going ham on this pig. Is he mad? Aww. Poor Baby. Poor. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:02:35 </td>
   <td style="text-align:left;"> $TSLA We have a horrible president. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:02:28 </td>
   <td style="text-align:left;"> $TSLA all I’m asking for tomorrow is reclaiming the 850$ support not 900 not 1000 just reclaiming support. There has been so much pain across the market a relief rally after apples blowout ER would be nice, but a rally that doesn’t sell at noon. All I’m asking for 🥲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:02:28 </td>
   <td style="text-align:left;"> $TSLA 

Kitty 🐈‍⬛ cat !! Hold. !! 

🙏🏻🐉🦅👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:02:20 </td>
   <td style="text-align:left;"> $TSLA Elon sold the top </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:02:12 </td>
   <td style="text-align:left;"> $TSLA $QQQ  there&amp;#39;s more Volatility here than in a Strippers bank account balance </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:02:09 </td>
   <td style="text-align:left;"> $TSLA 

Elon:

&amp;quot;FSD in 6 years&amp;quot; - 2014
&amp;quot;FSD in 2 years&amp;quot; - 2015
&amp;quot;FSD in 2 years&amp;quot; - 2016 (solved problem)
&amp;quot;FSD in 2 years&amp;quot; - 2017
&amp;quot;FSD in Next year&amp;quot; - 2018
&amp;quot;FSD end of this year&amp;quot; - 2019
&amp;quot;FSD end of this year&amp;quot; - 2020 (level 5)
&amp;quot;FSD end of this year&amp;quot; - 2021 (level 5)
&amp;quot;FSD end of this year&amp;quot; - 2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:01:48 </td>
   <td style="text-align:left;"> $TSLA ark buying on these dips? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:01:47 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:01:31 </td>
   <td style="text-align:left;"> $TSLA  Added 100 @ $836 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:01:28 </td>
   <td style="text-align:left;"> $TSLA 760 tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:01:22 </td>
   <td style="text-align:left;"> $TSLA analyst remain bullish here with a 1200$ PT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:01:08 </td>
   <td style="text-align:left;"> $TSLA Even IF tesla develops the full service driving FSD feature in cars 🚗 , will government or should the government allow it ?? seems totally unsafe to me...daamn with what the tech can and cannot do, safety and comfort of the public on the roads should be priority #1. I am so not comfortable with other drivers driving fully autonomous cars 🚗 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:00:53 </td>
   <td style="text-align:left;"> $TSLA Stop Elon&amp;#39;s Con. SEC. Been telling you all day my fellow Americans. Geez. Reckt it Ralph. Broke the internet. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 09:00:10 </td>
   <td style="text-align:left;"> $TSLA Simulated Weekly $830.0 CALLS for Friday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:59:49 </td>
   <td style="text-align:left;"> $TSLA I forgot Cathie the jinx owns this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:59:27 </td>
   <td style="text-align:left;"> $AAPL Notice how Cook manages to speak after earnings and not completely crash the stock. Elon Musk over at $TSLA should study </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:58:48 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $INTC Some Historical Perspective on the S&amp;amp;P 500 Index &amp;quot;Death Cross&amp;quot; | Nasdaq https://www.nasdaq.com/articles/some-historical-perspective-on-the-sp-500-index-death-cross </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:58:43 </td>
   <td style="text-align:left;"> $TSLA Tesla   What&amp;#39;s the return policy on these Velvet Tesla Short Shorts?  Will they return them with 💩 in them?  I just had an accident when I checked the price 🤦 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:57:54 </td>
   <td style="text-align:left;"> $TSLA Goes Without Saying. We all think alike anyway. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:57:51 </td>
   <td style="text-align:left;"> $TSLA I think this just initiated the market crash today.  Rotating to Puts on $AAPL now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:57:09 </td>
   <td style="text-align:left;"> $TSLA so many people cheering a red market. I just don&amp;#39;t understand being that unhappy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:57:09 </td>
   <td style="text-align:left;"> $TSLA wen $760? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:57:07 </td>
   <td style="text-align:left;"> $TSLA Not a hair on his head though. That is not happening either. Understand? No one will hurt him or anything. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:56:54 </td>
   <td style="text-align:left;"> Cute, indices-futures are weak. https://www.investing.com/indices/indices-futures  I&amp;#39;m calling it ... welcome to crash Friday. Great week it has been MTWR, 4 days, 43,000$ 21% roi in profits since premarket Monday. All short trades on full margin, all profit, some more profitable than others, always holding overnight, not by choice, beauties included $tsla $f $hood $pton $ccl 🐻❤😈☠ Carry on following me for profits @Profit_Maker https://stocktwits.com/Profit_Maker  your 24/7 short trading care bear specialist,  thanks bulls for lending me your shares to short for profits at your expense ✔ Good health and trading to all 🕺 ... as a reminder I block all who imho jawbone stupid wasting my time and broadband 😜 Enjoy the Armageddon Depression, what a crash year 2022 it is going to be and beyond, so demented the economy and stock market rallies since 2009 have been in tandem with many socioeconomic concerns.  👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:56:15 </td>
   <td style="text-align:left;"> $TSLA...YOU OWN TESLA AT 1200 THINKING IT WILL BE 3000 ONE DAY.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:55:34 </td>
   <td style="text-align:left;"> $TSLA got in AH with 30 shares @ 839….Good move you think? ☺️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:55:23 </td>
   <td style="text-align:left;"> $TSLA No one likes Elon Musk. Who will protect him when ALL come? Come against one. Come against all. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:55:20 </td>
   <td style="text-align:left;"> $TSLA #SMAPRO AI-Enabled Crystal ball current suggestion:  
 
Accumulate this dip. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:55:04 </td>
   <td style="text-align:left;"> $TSLA 770 area next support </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:55:02 </td>
   <td style="text-align:left;"> $LCID $TSLA $HOOD $WISH 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:54:59 </td>
   <td style="text-align:left;"> $AAPL 
I&amp;#39;ll be honest, if I had Apple Calls, I&amp;#39;m selling if first thing tomorrow. After seeing what happened to $TSLA , there&amp;#39;s no way I&amp;#39;m risking it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:54:49 </td>
   <td style="text-align:left;"> $TSLA Glad it pop up too high. Gives me time to load up on Calls in morning before the sqweeze. Its $400 down oversold from highs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:54:33 </td>
   <td style="text-align:left;"> $TSLA  Auntie Cathy sold at the top and she will be buying big time when this bottoms </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:54:12 </td>
   <td style="text-align:left;"> $TSLA See you at $600 tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:54:11 </td>
   <td style="text-align:left;"> $TSLA ...THE SMARTEST MOVE THIS COMPANY COULD EVER MAKE WOULD TO OFFER MORE SHARES AND DILUTE IT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:53:51 </td>
   <td style="text-align:left;"> Legacy auto makers pose NO threat to $TSLA . They are just too far behind.  
 
However, China has a significant battery metals supply chain choke hold, and that is where the competition sits. 
 
Discussing $TSLA earnings, and why the stock is down 11.5% in REGUALR trading hours. Is this a broader market warning? 
 
https://youtu.be/o1OqwJt6xbw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:53:29 </td>
   <td style="text-align:left;"> $TSLA ok one more ride before we all die </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:53:27 </td>
   <td style="text-align:left;"> $TSLA Come One Come All... know what that means? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:53:07 </td>
   <td style="text-align:left;"> $TSLA well unless algorithms have a crystal ball oh it does sell first 
Robo advisers do the same </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:52:57 </td>
   <td style="text-align:left;"> $TSLA holding ten years </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:52:51 </td>
   <td style="text-align:left;"> $TSLA tomorrow going back to $900 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:52:33 </td>
   <td style="text-align:left;"> $TSLA Im sorry Elon but this is too much </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:52:27 </td>
   <td style="text-align:left;"> $F $GM $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:52:24 </td>
   <td style="text-align:left;"> $TSLA strong   &amp;amp; green in premkt tomorrow and then pullback by 10 or 10:40 am back deep into red is my guess. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:52:10 </td>
   <td style="text-align:left;"> $SPY about to bend and open second butthole for you degenerate V conditioned buyers. Today fute is sell the rip. Fuck your calls. $qqq $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:51:58 </td>
   <td style="text-align:left;"> $TSLA let&amp;#39;s go down to 700 area so we can double our money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:51:27 </td>
   <td style="text-align:left;"> $TSLA Tesla had $1.26 billion in bitcoin at the end of quarter.  Since Bitcoin lost 40% value since then, that 1.26 billion is now closer to $800 million.   Tesla will take a hit next earnings unless bitcoin bounces bigly.  $BTC.X $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:50:22 </td>
   <td style="text-align:left;"> $TSLA come on 10 minutes to go! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:50:20 </td>
   <td style="text-align:left;"> $TSLA here comes the blast 💥 like usual </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:49:32 </td>
   <td style="text-align:left;"> $BTC.X $ETH.X $TSLA $SPY 
As an observer from the great white north… I must say, your country isn’t short of entertainment this last week. Heading to zero,  and most are happy to bring the system down. Also-
“BUT wE HaVENO VACCINe ManDATES”
what a shit show. Sheesh. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:49:08 </td>
   <td style="text-align:left;"> $TSLA put szn. Daddy jpow putting an end to this meme stock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:49:02 </td>
   <td style="text-align:left;"> $TSLA  $HOOD  $COIN $SPCE  
 
Jim Cramer has the nerve to  blame SPACs for this disastrous market.  No Jim, it’s you and all those people on the shows that relentlessly pump up stocks and the market that did this! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:48:48 </td>
   <td style="text-align:left;"> $TSLA Man My puts making me a fortune Thanks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:48:25 </td>
   <td style="text-align:left;"> $TSLA $BTC.X $QQQ

$900 calls might print who fucking knows in this market. Elon is unpredictable and might have some cards he’s ready to play. 
 
Either way I have learned to love the chaos. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:47:49 </td>
   <td style="text-align:left;"> $TSLA Did Elon Musk mention bitcoin profit/loss during earnings call? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:47:43 </td>
   <td style="text-align:left;"> $TSLA You guys know that if you don&amp;#39;t want you kids that someone else will gladly take them and love and spoil them like their own here in America right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:47:21 </td>
   <td style="text-align:left;"> $TSLA Tesla has a bear flag that’s sexy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:46:48 </td>
   <td style="text-align:left;"> $TSLA Elon said they “will comfortably be above 50% growth in 22” and they will have “solved autonomous driving solved in 2022” - Wow. 

Stock doesn’t deserve the today’s price action after incredible earning numbers. Anyway, Bought more today!!!! This baby is going way uppppp. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:46:45 </td>
   <td style="text-align:left;"> $HOOD to be rational here, definitely adding tomorrow based on their 6b on hand and their mc. Citadel and Kathy will add at this level, like she did with $WKHS when they didn&amp;#39;t get the contract and $SKLZ in the 10s I belive...she got that $TSLA money now from selling it...anyway buy $BRGX.X that&amp;#39;s my point </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:46:43 </td>
   <td style="text-align:left;"> $TSLA does anyone know what Nany Pelosi and Dan Crenshaw’s positions are? They seem to have inside info based on how much they’ve made in the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:46:38 </td>
   <td style="text-align:left;"> #30 Robinhood Dippin&amp;#39; Below $10 Tesla Slide Ackman Buying Netflix Apple Rip $HOOD $TSLA $NFLX $AAPL https://youtu.be/7qaOyvtc8BQ via  
@YouTube </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:45:59 </td>
   <td style="text-align:left;"> $RECAF got me remembering $TSLA 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:45:50 </td>
   <td style="text-align:left;"> $TSLA Biden may seem like a senile old man, but he knows Musk is his enemy, expect some backdoor retaliation via regulatory.  Musk is a fool to openly attack him on Twitter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:45:33 </td>
   <td style="text-align:left;"> $TSLA I&amp;#39;m a buyer at 475 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:45:15 </td>
   <td style="text-align:left;"> $TSLA Biden is the worst for USA. Knew it. Neither Trump. Only Elon 2024 for president. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:45:05 </td>
   <td style="text-align:left;"> $TSLA Small Potatoe Elon Musk. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:44:51 </td>
   <td style="text-align:left;"> $TSLA You all woke though huh? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:44:34 </td>
   <td style="text-align:left;"> $TSLA % 11.11 down right now - sucks but cool numbers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:44:21 </td>
   <td style="text-align:left;"> $TSLA $TQQQ buy Load up on Friday and Monday. Watch it rally from the 1st of February to mid-February before retreating back. Should have a good 2 week run from Feb 1 - mid Feb. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:43:35 </td>
   <td style="text-align:left;"> $TSLA When Trump said Abortion was murder and passed a law. He got a free ticket to do whatever he wants. Abortion is murder. Don&amp;#39;t matter what you believe. Don&amp;#39;t make it any less true. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:43:19 </td>
   <td style="text-align:left;"> $TSLA tomorrow back to $990 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:43:14 </td>
   <td style="text-align:left;"> $NIO $tsla $f $gm Chip Shortage Crisis: UK PLUNGES to 65-year low for Car Production 

Fewer than 900,000 vehicles rolled off UK production lines in 2021, the lowest number since 1956, due to the crisis of semiconductor chips that could affect the industry into 2023 experts fear.

Last year’s production marked a drop of 6.7% from 2020, and 34% from pre-pandemic levels, as the industry body’s CEO Mike Hawes warned the chip problem was far from the only hurdle.

He also cited 70% energy cost hikes, staff shortages due to Covid regulations, Brexit paperwork affecting electric car battery imports and near 30-year high inflation as compounding the issue. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:43:13 </td>
   <td style="text-align:left;"> $TSLA todays volume on downside was 48.75MM. Hopefully this was the flush. Currently hovering at 20 dma on daily. Would like to see this hold and have new buyers who want to own this. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:42:32 </td>
   <td style="text-align:left;"> $QQQ $DIA $TSLA Account Challenge Update: 
Start Dec 30,2021 
Starting: $5,000 
Current: $80,212 
Goal: $100,000 by end of January 
Strategy: Swing Trade Options, Stocks 
 
Watch out for next pay👀, discord.io/ongoing_alerts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:42:31 </td>
   <td style="text-align:left;"> $AAPL $QQQ $TSLA  $SPY 

Chief Executive Tim Cook said Thursday that despite ongoing issues affecting the availability of supplies used in some of its products, the company is still managing to turn in the strongest sales in its history 💎🍏💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:42:23 </td>
   <td style="text-align:left;"> $TSLA this may pop a but in the morning then resume lower. it’s nit oversold yet. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:41:35 </td>
   <td style="text-align:left;"> I have $ARKK in my 9 year old sons long term portfolio. Jim Cramer just implied that he’s burning my son and his portfolio. What a disgusting commie $DKNG $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:41:20 </td>
   <td style="text-align:left;"> $TSLA im a bear </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:41:12 </td>
   <td style="text-align:left;"> $TSLA is Fed fuxkin market on purpose? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:41:04 </td>
   <td style="text-align:left;"> $TSLA NOT GOOD FUNNELING DOWN NO BREAKOUT. Under $800 tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:40:56 </td>
   <td style="text-align:left;"> $TSLA Biden might be under the guise of blue but he is Red One&amp;#39;s President. Too bad you don&amp;#39;t get that. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:40:47 </td>
   <td style="text-align:left;"> $SPY $AAPL $INDO $TSLA $QQQ If you really want to make huge profits on trading then, Join this winning chat discord.io/MqakycG 
 
 
##01 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:40:09 </td>
   <td style="text-align:left;"> $TSLA $AAPL  $SPY   #1 in the world 💡💡💡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:40:03 </td>
   <td style="text-align:left;"> $TSLA throw more money on it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:39:58 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:39:47 </td>
   <td style="text-align:left;"> $TSLA iterally every tiny pump got sold off today.

Rough day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:39:45 </td>
   <td style="text-align:left;"> $TSLA can still see a minor new low before a larger bounce can take place.  We don’t like to sell it short down here, only like to look for the blue boxes where a bounce can take place in 3, 7 or 11 swing  #Ellliottwave #Trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:39:08 </td>
   <td style="text-align:left;"> $TSLA if I were Elon Musk I would spend less time making cars and space ships and more time developing my own stock market algorithms 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:38:16 </td>
   <td style="text-align:left;"> $TSLA  $AAPL $SPY  That part !!! Tesla is the leading the race !!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:38:00 </td>
   <td style="text-align:left;"> $TSLA: The EPS has grown by an impressive 174.51% over the past year. https://www.chartmill.com/stock/analyzer/stock/TSLA?view=fundamental-analysis&amp;amp;key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:37:25 </td>
   <td style="text-align:left;"> $TSLA You CEO went to war with the entire illuminati. BOTH SIDES. In their own house. Lmfao. Ugh. Now you wonder why I been here trying to save you? Gary Gensler come get this pig already. We are allergic to pig but you can bacon this company and eat it all you want. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:37:12 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/BfnjX88Va4Y </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:37:12 </td>
   <td style="text-align:left;"> $TSLA the amount of bears here is impressive </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:35:39 </td>
   <td style="text-align:left;"> Big drop in #tesla after earnings.  $TSLA currently  testing 200ma support. Full analysis is available on youtube 

https://youtu.be/yRxJ9W2vu4Q

Here is $TSLA snapshot based on today&amp;#39;s closing price </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:35:31 </td>
   <td style="text-align:left;"> $TSLA bulls better hope AAPL brings the whole market up with it tomorrow, so far all the AH pop in non AAPL shares have come back to around closing price….don’t be surprise if all the big boys hide in AAPL &amp;amp; MSFT and dump everything else….will see… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:35:26 </td>
   <td style="text-align:left;"> $TSLA Moon next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:34:58 </td>
   <td style="text-align:left;"> $AAPL 
If the $TSLA cult can&amp;#39;t hold Tesla, then what makes you think Apple people can? 😂🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:34:16 </td>
   <td style="text-align:left;"> $TSLA Bears mostly live in moms basement. Tell me one successful bear which has consistently made big money shorting the stocks??

Bulls: Warren Buffet, Peter Lynch, etc etc etc 

No bears on the list 😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:34:03 </td>
   <td style="text-align:left;"> $TSLA all in at $250 ... just let me dream dont ruin this moment for me 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:34:00 </td>
   <td style="text-align:left;"> $TSLA I hope no longer got stopped out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:33:19 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL  $ARK  
  
Short them to hell with 500x leverage -&amp;gt; https://simplefx.com/n/_5039 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:33:17 </td>
   <td style="text-align:left;"> $TSLA going to buy back at $600 GL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:33:09 </td>
   <td style="text-align:left;"> $TSLA preparing 680 landing pad. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:33:07 </td>
   <td style="text-align:left;"> $TSLA waiting for this to 500 then I will buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:32:22 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-27 Technical Analysis Video: 
https://www.youtube.com/watch?v=oMlBAivtVqo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:32:22 </td>
   <td style="text-align:left;"> $TSLA Watch this baby shoot up like crazy

Tomorrow morning is going to be phenomenal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:32:17 </td>
   <td style="text-align:left;"> $TSLA this dropped 17$ in the after market going down more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:32:11 </td>
   <td style="text-align:left;"> $TSLA https://youtu.be/fWFDReSFJZ0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:31:36 </td>
   <td style="text-align:left;"> $TSLA just bought multiple shares $832 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:31:22 </td>
   <td style="text-align:left;"> $TSLA imagine EVs separate from index and keep falling like green energy did for a while now $LCID </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:30:43 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:30:10 </td>
   <td style="text-align:left;"> $TSLA Just called the police to report a murder. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:29:39 </td>
   <td style="text-align:left;"> $TSLA Tesla is the leading indicator of sentiment, and $AAPL Apple will never get Apple Car off the production line </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:29:35 </td>
   <td style="text-align:left;"> $TSLA Elon has accomplished more in a few years than Biden has in his entire life </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:28:55 </td>
   <td style="text-align:left;"> $TSLA I bought into Tesla yesterday for the first time 🤣 Fucking typical </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:28:40 </td>
   <td style="text-align:left;"> $TSLA Nati Time for Musk. Musk Been Naughty. We going to spank him. Bad little Boy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:28:20 </td>
   <td style="text-align:left;"> $TSLA 90% of posts from retails r bearish:) u know what’s going to happen tmr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:27:57 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:27:51 </td>
   <td style="text-align:left;"> $TSLA In few years this $100 move down will look like a joke 😂😂 TSLA to 3,000 by 2025. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:27:46 </td>
   <td style="text-align:left;"> $TSLA Tesla is doing fine. They didn’t close down or planning to bankrupt. The whole market went down including Tesla. It will pickup. Do not panic and do not sell with lose. Just wait. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:27:35 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:26:57 </td>
   <td style="text-align:left;"> $TSLA I feel lucky to be able to add more at these levels </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:26:56 </td>
   <td style="text-align:left;"> $TSLA this&amp;#39;ll be $2k before we know it. Relax.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:26:17 </td>
   <td style="text-align:left;"> $TSLA GO LOWER!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:26:13 </td>
   <td style="text-align:left;"> $TSLA time for Bulls to support the #1 man Elon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:26:11 </td>
   <td style="text-align:left;"> $TSLA 🔋🔋🔋🔋 &amp;amp; Hydrogen is the Future 🌎💯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:26:00 </td>
   <td style="text-align:left;"> $TSLA lololol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:25:55 </td>
   <td style="text-align:left;"> $TSLA 100 would be cool </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:25:51 </td>
   <td style="text-align:left;"> $TSLA Believe in omens? Red one playing - Small Potatoes. Small Potatoes. Small Potatoes. Small Potatoes. ¿?¿?¿?¿? Small Potatoes Lmfao. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:25:48 </td>
   <td style="text-align:left;"> $TSLA Within a couple of hours, Elon will have triggered enough millionaires, billionaires and politicians and law makers... on Twitter to ensure that the bubble bursts. Congrats, Elon.  Guy is on a rampage today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:25:46 </td>
   <td style="text-align:left;"> $FGI FGI stands at $3.16 on closing today. Yet this home and bath remodelling company which is carried by Home Depot and Lowes is valued at 4x its current SP. This was clearly a hard week to IPO. 
 
Here&amp;#39;s the analysis: https://simplywall.st/stocks/us/capital-goods/nasdaq-fgi/fgi-industries 
 
$BNGO $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:25:37 </td>
   <td style="text-align:left;"> $TSLA  justvtrade only do not buy and hold. If you hold you will lose money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:25:06 </td>
   <td style="text-align:left;"> $TSLA can&amp;#39;t even release out Cybertruck after years, now the new scam of Optimus will keep this going for a few more years </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:25:00 </td>
   <td style="text-align:left;"> $TSLA only got 60K left in bank. All of its going into Tesla if this gets crushed back to $600 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:24:52 </td>
   <td style="text-align:left;"> $TSLA at least Musk owes the investors a detailed explanation of WHY he made the promises of million robotaxis back then and WHY that plan was derailed and WHY he keeps moving from one promise/idea to another?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:24:43 </td>
   <td style="text-align:left;"> $TSLA hahahahahahahahahahahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:24:18 </td>
   <td style="text-align:left;"> $TSLA  Come on Elon, stop hinting around and just tell everyone covid was a global scam </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:24:00 </td>
   <td style="text-align:left;"> $TSLA kept hearing:

1200 is the bottom
1100 is the bottom
1000 is the bottom
900 is the bottom

Guess what I am hearing now 🙄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:23:55 </td>
   <td style="text-align:left;"> $TSLA  It’s funny how close the moving average is … if this closes above 831 we should see a rebound … Bullish for now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:23:52 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:23:51 </td>
   <td style="text-align:left;"> $TSLA give me the whip, not the dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:23:16 </td>
   <td style="text-align:left;"> $CFVI $DWAC $PHUN $TSLA 

That’s my tweet shared by Rumble ($CFVI)! 🔥🚀🎤☁️🙏

Let it Rumble podcasts in Tesla cars! 🔥🔥🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:23:01 </td>
   <td style="text-align:left;"> $TSLA I still remember the outright lie of 1 million robotaxis by 2020 from Con Artist in Chief Elon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:22:57 </td>
   <td style="text-align:left;"> $TSLA 920+ tmr see u </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:22:57 </td>
   <td style="text-align:left;"> $TSLA Lololol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:22:29 </td>
   <td style="text-align:left;"> latex42e88783b451b13ba097aa200b8d7e4f$ off

https://www.youtube.com/watch?v=eBPqksG9nbA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:22:11 </td>
   <td style="text-align:left;"> $TSLA  I am completely fucked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:22:03 </td>
   <td style="text-align:left;"> $TSLA good buy opportunity here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:22:00 </td>
   <td style="text-align:left;"> $TSLA 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:21:57 </td>
   <td style="text-align:left;"> $TSLA loading up on calls tomorrow afternoon, because that’s the way </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:21:55 </td>
   <td style="text-align:left;"> From a $TSLA bull: &amp;quot;Yeah this sell off makes no sense, even if you think Elon is lying, the things he said were only good for the company.&amp;quot; 🤡🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:21:49 </td>
   <td style="text-align:left;"> $TSLA like if you think this will correct to low 700s tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:21:48 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AAPL $MSFT not very good news here… 👤 https://www.bloomberg.com/news/articles/2022-01-27/u-s-nato-respond-to-russia-rejecting-demands-ukraine-update </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:21:41 </td>
   <td style="text-align:left;"> $TSLA next promise: Full FSD in 2022 ?? so when 2023 comes and IF we are nowhere close to FSD, what will Musk say to investors then?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:21:40 </td>
   <td style="text-align:left;"> $TSLA split it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:21:22 </td>
   <td style="text-align:left;"> $TSLA bagholders galore </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:20:59 </td>
   <td style="text-align:left;"> $SPY here’s why tomorrow we’re going to have a great day!!! $AAPL  amazing 🤩 earnings 🚀 , $TSLA  rebound and much more but with those 2 should suffice 🚀🚀. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:20:46 </td>
   <td style="text-align:left;"> $TSLA Is this on the SSR list tomorrow? Should be? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:20:34 </td>
   <td style="text-align:left;"> $KYNC That 30 day is beautiful. $TSLA  only wishes they could compete 🤣🤣🤣 What a sh it hole </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:20:11 </td>
   <td style="text-align:left;"> $TSLA this is going to $629 the 500 day ema </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:20:06 </td>
   <td style="text-align:left;"> $TSLA LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:19:46 </td>
   <td style="text-align:left;"> $TSLA where you at bulls?  Retard alert. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:19:45 </td>
   <td style="text-align:left;"> $TSLA folks please listen... this company was pumped to trillion market map. It is not sustainable, competition will become fierce FORD/ GM etc...NIO/LUCID the list goes.  
 
The hype was great, the ride was amazing but TESLA&amp;#39;s rein is coming down from the clouds.. This will come down to the 600-700 at very least this year if not lower. 
 
The market is about to make overvalued large caps pay for their ride. 
 
The small cap sector has beaten to the ground on political tensions etc. 
 
Take a look at $CLEU $QD  balance sheets trading below cash at levels unprecedented 300% below cash. 
 
Misconstrued CLEU is not a tutoring stock, its a smart classroom solutions providers. TECH! 2.74 a share in cash no debt trading at 0.84 cents a share... where can you buy 3 dollars for 1....  
 
QD CEO announced to be repurchasing 10M of its stock. 10M shares... trading at a P/E of 1... lol thats right 1.... 
 
Not recommending you buy anything just add it to your watchlist... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:19:22 </td>
   <td style="text-align:left;"> $TSLA grrr I hate the market makers fucking this market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:19:17 </td>
   <td style="text-align:left;"> $TSLA Ford and GM are establishment money. That’s why Washington backs them. They have given patronage for a century. 
 
that Elon is calling Washington out makes me want to buy the stock. I will. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:19:15 </td>
   <td style="text-align:left;"> $TSLA Breaking news 🗞 Elon Sold alllll is shares </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:19:07 </td>
   <td style="text-align:left;"> $TSLA https://www.bloomberg.com/news/articles/2022-01-27/u-s-nato-respond-to-russia-rejecting-demands-ukraine-update </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:18:52 </td>
   <td style="text-align:left;"> $TSLA $NIO $AAPL all I need! Second best TNA!! Kwyo! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:18:51 </td>
   <td style="text-align:left;"> $TSLA demand is great I wish they would’ve communicated that much better yesterday 😓 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:18:32 </td>
   <td style="text-align:left;"> $TSLA go Elon give them hell. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:18:28 </td>
   <td style="text-align:left;"> $TSLA freeeeee falllling Overrrrrrrr donnnnnne finishhhhhhhh lololollololllll </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:18:16 </td>
   <td style="text-align:left;"> $TSLA 
Wow what a ride for last three months enjoyed it. Back to the ground!
I don’t know when the next launch will be. My portfolio really look good for a few months now it’s still OK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:18:05 </td>
   <td style="text-align:left;"> $DWAC $AMC $GME $TSLA $FB Biden and Putin explain things!! https://www.youtube.com/watch?v=CssUXNPHsbM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:17:59 </td>
   <td style="text-align:left;"> $TSLA Russia news on bloomberg mid feb attack says biden </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:17:22 </td>
   <td style="text-align:left;"> $TSLA figure out a tree by its fruit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:17:01 </td>
   <td style="text-align:left;"> $TSLA go Elon give them hell. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:17:00 </td>
   <td style="text-align:left;"> $DOGE.X $TSLA missed it... sold out already 😪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:16:32 </td>
   <td style="text-align:left;"> $TSLA Used to love the fact that Elon wasn’t afraid to open his mouth but the last 3 months he’s driving me crazy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:16:03 </td>
   <td style="text-align:left;"> $TSLA question for the pragmatic perma bulltard, that’s feeling sketchy af…will $650 be a good starter? 🤔

LES GOH BRANDON! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:15:54 </td>
   <td style="text-align:left;"> $TSLA musk is going to trigger so many powerful people with his tweets. if this crashes, the guy played a part in this. just look at his twitter today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:15:47 </td>
   <td style="text-align:left;"> Another day of trading, another day in the green!  
 
I honestly just have so much fun doing my job and working with the #1 trading community in the world!  
 
Thank you to the 1,000 viewers on YouTube today! I hope you had a blast and made some awesome gains as well!  
 
$INDO $SRRA $TSLA $APPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:15:24 </td>
   <td style="text-align:left;"> $TSLA If you attack our people. Our president. Our dollar. We will show you how real the illuminati is. Home of the enlightened ones was never a joke. Like Twin Towers are Two Twin Souls. Red and Blue. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:15:17 </td>
   <td style="text-align:left;"> $TSLA Is musk having a fit on Twitter because Biden won’t include him with gm and Ford? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:15:08 </td>
   <td style="text-align:left;"> $TSLA Robotaxis, where art thou? Cybertruck where art thou? $25k cheap azz EV car 🚗 where art thou? Semis &amp;amp; Roadsters, where art thou? Human Robot replies back: At least I am here....NOT 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:14:40 </td>
   <td style="text-align:left;"> $TSLA easiest $$$$ dough around do yourself a favor and put!!! Don’t let the hedges destroy your assets. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:14:35 </td>
   <td style="text-align:left;"> $TSLA  we gapping up tomorrow mark it !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:14:27 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL  
 
Short them to hell with 500x leverage https://simplefx.com/n/_5039 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:14:20 </td>
   <td style="text-align:left;"> $TSLA CLIR is the symbol in case you forget this video shows what just the old holes in the ground look like after there finnish with them https://www.cnn.com/videos/us/2021/02/05/methane-texas-abbott-biden-natural-gas-weir-pkg-vpx.cnn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:14:16 </td>
   <td style="text-align:left;"> $TSLA not done dropping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:14:06 </td>
   <td style="text-align:left;"> $TSLA you know what kool aid drinkers think. It’ll go to 8000 soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:14:04 </td>
   <td style="text-align:left;"> $TSLA overvalued and supply issues </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:13:56 </td>
   <td style="text-align:left;"> $TSLA ouch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:13:49 </td>
   <td style="text-align:left;"> $TSLA could you imagine being Michal Burry today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:13:46 </td>
   <td style="text-align:left;"> Can You Solve Elon Musk&amp;#39;s Word Riddle On Who The U.S. EV Leader Is That Ratioed President Joe Biden?  $TSLA $GM $F 

https://newsfilter.io/a/18d7e5f521d76e139c21030ed193c9c0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:13:39 </td>
   <td style="text-align:left;"> $SHIB.X $BTC.X $TSLA 
Biden wants to ban #crypto in which i have said many times usa is behind in modern technology . People that are well traveled know this #fact. Dubai, Japan etc. Putin and Salvador President are adapting Crypto because the world is changing  and yet Biden wants to ban cause is a National Security . Old man old school mentality. Get with the program Congress. Geez </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:13:34 </td>
   <td style="text-align:left;"> $TSLA Well when someone picks a war with the United States what do you think will happen down there? He knows he is done. Biden knows Elon Musk is a fraud and no offense to sleepy Joe but even if he knows how don&amp;#39;t you? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:13:21 </td>
   <td style="text-align:left;"> $TSLA hey bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:12:51 </td>
   <td style="text-align:left;"> $TSLA FULL ON fsd glitch at a 4-way 👇

LES GOH BRANDON! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:12:42 </td>
   <td style="text-align:left;"> $SPY 2020-2021 were the year of bubble under the disguise of covid. 2022 is a year of deflating and resetting the bubble created. $TSLA $AAPL can’t be excluded 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:11:50 </td>
   <td style="text-align:left;"> $TSLA single handedly destroyed the market.. hawww you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:11:32 </td>
   <td style="text-align:left;"> $TSLA 

Youtubers are cranking up the pump for this scam valuation fairytale. You haven’t seen “cheap” yet! It was here just this past October. Wait for $50. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:11:23 </td>
   <td style="text-align:left;"> $TSLA This is the most important company going forward. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:10:47 </td>
   <td style="text-align:left;"> $TSLA 2k in 2 years. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:10:44 </td>
   <td style="text-align:left;"> $TSLA this comment alone makes me want to buy more and support Elon. @elonmusk 
Elon is saying what others are scared to say. 
Elon is only big name standing up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:10:35 </td>
   <td style="text-align:left;"> $TSLA just $400 down? 😛😛 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:10:33 </td>
   <td style="text-align:left;"> $TSLA gotta dump it to pump it as usual </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:10:30 </td>
   <td style="text-align:left;"> $TSLA this has been fun just short the bounces all the way to 790 the I will leave to you bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:10:21 </td>
   <td style="text-align:left;"> $AAPL
Earning Report was already priced in. Ask your big Tech Brother $TSLA . Apple is about to end up in the same hospital. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:10:21 </td>
   <td style="text-align:left;"> $TSLA I’m ALL IN . I have no desire to hold any other stock … </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:10:19 </td>
   <td style="text-align:left;"> $AMD and $TSLA are on my Watchlist. 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:10:15 </td>
   <td style="text-align:left;"> $TSLA Elon busy pumping $DOGE.X and tweeting memes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:10:08 </td>
   <td style="text-align:left;"> $TSLA I need a favor can your tell you&amp;#39;ll Boss to invest into CLIR or just buy it out in a all stock deal at the price it&amp;#39;s trading at the cost would be about 100 shares of TSLA to buy it I maybe off by an zero or two the math gets hard sometimes he will feel better about all the electric he cars use that isn&amp;#39;t made from solar panels plus it will probably come with a one year subscription to the Paris Agreement can you tell him about that please thanks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:09:59 </td>
   <td style="text-align:left;"> $TSLA Where are the Robotaxis that Musk promised back in 2018 was it ? Anyone remember the Robotaxis promises and predictions by Musk ? It was supposed to come in 2020. Is it 2020 yet? 😂😂 why does Musk make claims n promises he can&amp;#39;t keep ?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:09:35 </td>
   <td style="text-align:left;"> $TSLA Was at 980 yesterday 😂 they’ll pump it back up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:09:29 </td>
   <td style="text-align:left;"> $TSLA 😐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:09:22 </td>
   <td style="text-align:left;"> $TSLA pure BS!!!! All the call buyers are screwed!!!!!! because of Elon&amp;#39;s big F mouth. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:09:18 </td>
   <td style="text-align:left;"> $TSLA got to keep it loading, long term hold </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:09:14 </td>
   <td style="text-align:left;"> $TSLA you don’t have to do this Tesla 🤕 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:08:58 </td>
   <td style="text-align:left;"> $TSLA I will buy a few shares when this reaches $85/share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:08:58 </td>
   <td style="text-align:left;"> $TSLA SP DROPS HARD SOON BELOW 4,000.  This stock will follow.  a fucking market red all the way.  Biden&amp;#39;s Musketeers need to go back to school for more education not stock trading.  Too many Youtubers they are like college students only.  They said, I do not need school any more.  Fuck yeah. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:08:49 </td>
   <td style="text-align:left;"> $TSLA if you were foaming at the mouth to buy at $1200 and are scared at $830 you should reevaluate your priorities. Don’t trade Tesla, buy and hold for long term. DCA don’t go all in buy into it little at a time but this is a great opportunity. Delivery #s have not changed. - Sincerely a $87 avg cost holder </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:07:19 </td>
   <td style="text-align:left;"> $TSLA another quick decode for today..

https://youtube.com/shorts/OSq7iePMds4?feature=share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:07:09 </td>
   <td style="text-align:left;"> $TSLA joke of the market tbh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:07:07 </td>
   <td style="text-align:left;"> $TSLA Nows the time to buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:07:05 </td>
   <td style="text-align:left;"> $TSLA where are all the Tesla Fanboys on this board? It&amp;#39;s not fun if I am unable to troll them! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:07:03 </td>
   <td style="text-align:left;"> $TSLA what the he’ll happened here despite great earnings? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:06:33 </td>
   <td style="text-align:left;"> $TSLA The pursuit of material-external things as if they can provide deep and lasting happiness is contributing to a dwindling of real meaning and is a factor contributing to an increase in mental health problems. It just isn&amp;#39;t possible to fill the hole inside us by piling up the things outside us.&amp;quot; pg9 ~ Janet Harris </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:06:31 </td>
   <td style="text-align:left;"> $TSLA Unquestionably this has turned into a heavyweight fight.  One corner you have Elon/Tesla and in the other is the Democratic party and sleepy Joe.  Not sure this is the fight Elon needs right now but he seems frustrated and determined.  He does not like to be bullied.  While I agree with him we don’t need more headwinds. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:06:26 </td>
   <td style="text-align:left;"> $TSLA It honestly broke the weekly and the daily supports. No position. I see the the next support at $800. What do you guys see? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:05:34 </td>
   <td style="text-align:left;"> $TSLA Elon Musk is ugly hes look lile an alien . that why he explore the space to find his familly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:04:48 </td>
   <td style="text-align:left;"> $TSLA 😜 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:04:36 </td>
   <td style="text-align:left;"> $TSLA no worries guys because you asked I’ll make sure this goes 1,000 tomorrow 🤣🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:04:27 </td>
   <td style="text-align:left;"> $SPY $TSLA $MSFT $AAPL 
We finally got though the main Tech Giants Earning Reports. Now there&amp;#39;s no more catalyst and all chips are down for the Bulls. Starting tomorrow, the blood bath will start. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:04:25 </td>
   <td style="text-align:left;"> 👉👑 $TSLA - BANKED OVER 500% ON THESE DEBIT SPREADS TODAY 🚨🚨 
💎 FALL-O FOR MORE, LYNC IN BAYU ⏳📈💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:04:16 </td>
   <td style="text-align:left;"> $TSLA how much did musk loose today, ballpark?…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:04:11 </td>
   <td style="text-align:left;"> $TSLA how low can this open tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:04:11 </td>
   <td style="text-align:left;"> $TSLA after hours beginning to look sexy.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:03:57 </td>
   <td style="text-align:left;"> $TSLA $AAPL &amp;#39;s er might possibly save tomorrow 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:03:55 </td>
   <td style="text-align:left;"> $TSLA but some analyst increased their price target to $1400! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:03:37 </td>
   <td style="text-align:left;"> $TSLA 

Wow !!   So sad 😞.. 

A residing President is anti American #1 EV Maker in the world !! 

Lie before the public and herds cheers !! 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:03:28 </td>
   <td style="text-align:left;"> $TSLA -EL for Elohim-in 1952  a German Engineer named Wernher Von Braun wrote a book about the colonization of Mars. In this book, he stated that the Martian Government would be directed by ten men, the leader was elected by universal suffrage for five years and entitled &amp;quot;ELON&amp;quot;. 
 Did Wernher predict the future or has it been set in stone? Could it be, we will have, or have WE had THE ELOHIM ON MARS, EL- ON MARS. Could there really be more to this as we theorize the possibilities of what could be plausible in our mind&amp;#39;s eye. Von Braun has meeting with NASA in 1958  and begins work with them. After his death in 1977, he is honored outside NASA building with a statue headpiece for his hard dedication and fueling Nasa and America&amp;#39;s secret space program. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:03:22 </td>
   <td style="text-align:left;"> $TSLA Same movement after 3q earnings then a week later started the terror from $640 to $1200. Not worried a bit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:03:12 </td>
   <td style="text-align:left;"> $TSLA What corporation will deliver over a million BEVs next year? Hint: Not Ford, GM, VW, Toyota, Daimler. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:02:55 </td>
   <td style="text-align:left;"> $TSLA  target reduced $600 now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:02:55 </td>
   <td style="text-align:left;"> $TSLA fake bull trap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:02:35 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-27 Trade Analysis Video: 
https://www.youtube.com/watch?v=bq0fCdgtwCo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:02:29 </td>
   <td style="text-align:left;"> $TSLA  avid high growth stocks. This year it will not work buy and hold </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:02:08 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:01:47 </td>
   <td style="text-align:left;"> $TSLA if all the Jim Jones guys buy , it can short squeeze </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:01:46 </td>
   <td style="text-align:left;"> $TSLA we are in a bear market! No more money printer. Trade accordingly!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:01:43 </td>
   <td style="text-align:left;"> $TSLA I feel the selling might not be done. 🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-28 08:01:40 </td>
   <td style="text-align:left;"> $TSLA $100 BILLION </td>
  </tr>
</tbody>
</table></div>

---
