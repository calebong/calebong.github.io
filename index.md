---
output:
  html_document:
    keep_md: true
---

# Investment Analytics Portfolio

My portfolio exhibits some examples data analytics and financial modelling that I conduct in my daily workflows.

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

TBA:
[View the latest Economic Forecasts](/sample_page)

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



Last Updated: 2021-12-24 09:48:31 UTC +8

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
   <td style="text-align:left;"> 2021-12-24 09:44:00 </td>
   <td style="text-align:left;"> Australian Shares Climb Near 1-Month High </td>
   <td style="text-align:left;"> The S&amp;P/ASX 200 Index gained 0.6% to 7,430 on Friday, hovering close to 1-month highs, following a strong overnight finish on Wall Street as concerns eased about the omicron variant’s economic impact. Financials including banks, insurance firms and asset managers were up, led by AMP Ltd which jumped 7% after the wealth manager said it would sell its infrastructure debt platform to Ares Management. Technology stocks also advanced, with gains from Afterpay (1.7%) and Wisetech Global (1.5%). Elsewhere, heavyweight miners, lithium explorers and energy firms were also up, while gold stocks eased from a recent run up. The benchmark index is set to close higher for a fourth straight session and is headed for its best week since the week ended Nov. 5. Australian markets will be closed on Monday and Tuesday for the Christmas and Boxing Day holidays. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/inflation-cpi </td>
   <td style="text-align:left;"> 2021-12-24 08:32:00 </td>
   <td style="text-align:left;"> Japan Inflation Rate at Near 2-Year High </td>
   <td style="text-align:left;"> Japan's consumer prices rose 0.6% YoY in November 2021, accelerating at its fastest pace in nearly two years and compared with a 0.1% gain a month earlier. The upward pressure on prices came mainly from a 9.2% annual increase in fuel, light and water charges, confirming signs that soaring energy and raw material prices are pushing more broadly through the Japanese economy and are being felt by consumers. Consumer prices also increased for culture &amp; recreation (4.3%), food (1.4%) and education (1.2%). In contrast, prices decreased in transportation &amp; communication (-6.9%) and medical care (-0.2%). Core consumer prices, which exclude fresh food, went up at 0.5% YoY in November, beating market expectations for a 0.4% increase but remains well below the central bank’s 2% target. On a monthly basis, consumer prices rose 0.3% in November, swinging from a 0.3% decline in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-59729874?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2021-12-24 08:10:57 </td>
   <td style="text-align:left;"> Cities start to attract property buyers again </td>
   <td style="text-align:left;"> Prospective property buyers have returned to cities, with flats the most highly in demand during the autumn, according to property portal Rightmove.                                                                                                                    , The UK housing market was relatively immune to the economic effects of Covid, with demand and price rises remaining high throughout the crisis.                                                                                                                         , This was driven by the race for space, with buyers attracted by larger, coastal or rural properties.                                                                                                                                                                    , But as workers returned to offices, interest in apartments revived.                                                                                                                                                                                                     , However, this is not a return to the pre-pandemic property market. Rightmove says there has been a long-term shift with buyers willing to pay more for space and privacy.                                                                                               , That means the gap in asking prices between detached and semi-detached homes has been stretched. In October, the typical asking price for a detached house was 76% higher than a semi-detached, compared with 70% in March 2020.                                        , Prospective buyers have also widened their searches by an average of 50 sq km, perhaps willing to move slightly further away from transport links and High Streets as they spend more time working and entertaining themselves at home.                                 , "The pandemic redefined the role of the home and placed new emphasis on its importance, and people looked for more room in order to work, exercise, and often teach under one roof," said Tim Bannister, who works in property data at Rightmove.                       , "While we know from our data that people really care about people and their local community, the pandemic also made us more conscious of our personal space."                                                                                                           , There was a surge in buyers in 2020, as people reassessed where and how they wanted to live. Government support through stamp duty holidays, as well as historically low mortgage rates, also encouraged many people to move, or bring forward future plans to relocate., The biggest demand, and subsequent rise in prices, were for houses in outer city or countryside locations. There were concerns in some areas that locals were being priced out of the market as a result.                                                               , At the same time, many flat owners were struggling to sell as a result of the cladding crisis, following the tragic fire at Grenfell Tower.                                                                                                                             , City centres had become less attractive places to live for those who were not going into an office, or - during the height of the pandemic - were unable to socialise or enjoy the entertainment attractions of urban centres.                                          , As workplaces and venues reopened - before the onset of the Omicron variant - there was a shift in buyer preferences, according to Rightmove.                                                                                                                           , The slowest rise in prices over the last year was for flats, and demand was much lower than for houses, especially those with gardens.                                                                                                                                  , By the autumn, flats had moved to the top of the list among prospective buyers to become the most in-demand type of property.                                                                                                                                           , Mr Bannister said demand to live in London and other major cities had been restored faster than anticipated, as employers encouraged people to return to their desks, at least through a hybrid working model.                                                          , The market may still be affected by the pandemic and its impact on jobs and the wider economy.                                                                                                                                                                          , The analysis is also based on averages, but local housing markets, demand and property prices can be affected by a host of factors ranging from the success of local schools to roads and new development.                                                              , Hayley Pearce chats terrible Christmas gifts...                                                                                                                                                                                                                         , Follow the true story of one man's struggle to find out why his home disappeared                                                                                                                                                                                        , © 2021 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/core-inflation-rate </td>
   <td style="text-align:left;"> 2021-12-24 08:08:43 </td>
   <td style="text-align:left;"> Japan Core Inflation Rate Accelerates in November </td>
   <td style="text-align:left;"> Core consumer prices in Japan increased 0.5% in November 2021 over the same month in the previous year, higher than market expectations for a 0.4% increase and accelerating at its fastest pace in nearly two years. The upward pressure on prices came mainly from a 9.2% annual increase in fuel, light and water charges, confirming signs that soaring energy and raw material prices are pushing more broadly through the Japanese economy and are being felt by consumers. However, Japan’s core inflation rate remains well below the central bank’s 2% target, and still lags behind other advanced economies amid a softer wage growth and weak consumption. The Bank of Japan maintained ultra-loose interest rate policy in its December meeting, and governor Haruhiko Kuroda stressed his readiness to keep rates low, even as other major central banks head for exit from crisis-mode stimulus measures. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/media/kudlow-big-government-socialism-is-not-the-america-we-love </td>
   <td style="text-align:left;"> 2021-12-24 07:56:32 </td>
   <td style="text-align:left;"> Kudlow: Big government socialism is not the America we love </td>
   <td style="text-align:left;">  ‘Kudlow’ discusses Biden’s leadership qualities amid crises with inflation, COVID, and Afghanistan.                                                                                                                                                                                                                                                                                                                                                                                                                                         , This has not been a great year for our great country. We'll talk about that in a minute.                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Save America, kill the bill was one of the better things that happened this year.                                                                                                                                                                                                                                                                                                                                                                                                                                                            , But I want to go back and quote President Trump's super-optimistic message for Thanksgiving, but I'm going to substitute Christmas.                                                                                                                                                                                                                                                                                                                                                                                                          , Here it is:                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , "A very interesting time in our country, but do not worry, we will be great again—and we will all do it together... America will never fail, and we will never allow it to go in the wrong direction. Too many generations of greatness are counting on us. Enjoy your Christmas - knowing that a wonderful future lies ahead!"                                                                                                                                                                                                              , This is Trump at his absolute best – his faith in America and its democracy and freedoms, his faith in "America first" and its resiliency against all odds or events.                                                                                                                                                                                                                                                                                                                                                                        , FORMER TREASURY SECRETARY ISSUES GRIM WARNING ABOUT LOOMING RECESSION                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Whether you agree with aspects of Mr. Trump or not, I would propose that his message is exactly the kind of optimistic leadership that this country needs right now.  Instead of a "winter of severe illness and death," we need an optimistic link to the strength of the people in America throughout the country, including the so-called "deplorables" attacked by media elites with their snooty noses in the air and their snarky responses to those who don't agree with their left-wing wokeism. So count me as a Christmas optimist., Brigg Macadam founding partner Greg Swenson discusses market volatility and the president's Build Back Better bill.                                                                                                                                                                                                                                                                                                                                                                                                                          , Traditional conservative values will, in the end, triumph. So will free-enterprise capitalism. So will freedom to choose. So will the importance of religion.                                                                                                                                                                                                                                                                                                                                                                                , President Biden has had a rough year because he has gone in a completely different, extremist direction.                                                                                                                                                                                                                                                                                                                                                                                                                                     , His polls are collapsing, but he won't listen. Afghanistan was a catastrophe. We could be on the edge of war with Russia in the Ukraine.                                                                                                                                                                                                                                                                                                                                                                                                     , TRUMP IN ‘BETTER POSITION’ THAN BIDEN FOR 2024 RUN, EX-CLINTON ADVISER SAYS                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Catastrophic flows of illegal immigrants from an open-borders policy. The inflation rate has soared because of the massive government spending financed by huge money creation from the Fed.                                                                                                                                                                                                                                                                                                                                                 , Big government socialism is not the America we love. Over-regulation for state control of energy, banking, health care, and education is not the American way. Government replacing parents and families is not the American way. A radical left agenda is not the American way. Across-the-board mandates is not the American way.                                                                                                                                                                                                          , GOP REP SAYS BIDEN ADMIN MADE ‘EVERY FOOLISH DECISION’ POSSIBLE                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , The fact that we killed the bill should give Biden pause that he is on the wrong track. But he won't listen. He and his crowd are stubborn, radical lefties.                                                                                                                                                                                                                                                                                                                                                                                 , Frankly, President Trump left this country in very good shape. Tax cuts, deregulation, energy dominance, securing our southern border, tough on China and Russia, near-zero inflation, record low unemployment for minority groups, falling poverty, reducing inequality, and boosting middle-class family income.                                                                                                                                                                                                                           , RealClearPolitics White House reporter Phil Wegmann argues that Biden seems to be ‘all-in’ to run in the 2024 race.                                                                                                                                                                                                                                                                                                                                                                                                                          , As I said on this show, right from its very beginning, if it ain't broke, don't fix it. Biden has made the tragic mistake of attempting to reverse all the successful Trump policies. This was a big mistake.                                                                                                                                                                                                                                                                                                                                , Sometimes I think that Biden acted on his own Trump Derangement Syndrome without any thoughtful analysis of his policies.                                                                                                                                                                                                                                                                                                                                                                                                                    , But while nothing is perfect, Donald Trump handed Joe Biden a silver platter. Sadly, Joe Biden has taken that silver platter and badly tarnished, twisted, and contorted that beautiful platter almost beyond recognition.                                                                                                                                                                                                                                                                                                                   , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , To return to Donald Trump's optimistic message:                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , "We will be great again—and we will all do it together. America will never fail ... Too many generations of greatness are counting on us."                                                                                                                                                                                                                                                                                                                                                                                                   , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , On that note, Merry Christmas folks. We will save America, and we will kill the bill.                                                                                                                                                                                                                                                                                                                                                                                                                                                        , This article is adapted from Larry Kudlow's opening commentary on December 23, 2021  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-59761294?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2021-12-24 05:53:19 </td>
   <td style="text-align:left;"> Covid: £10m Bounce Back Loan fraudsters jailed </td>
   <td style="text-align:left;"> Two men have been jailed for a total of 33 years for running a £70m money laundering scheme, £10m of which came from fraudulent Covid loans.                                                                                                                                                                               , Artem Terzyan, 38, from Russia and Deivis Grochiatskij, 44, from Lithuania were sentenced earlier this month at Kingston Crown Court.                                                                                                                                                                                      , Police believe the Bounce Back Loan fraud was one of the largest since the scheme started in 2020.                                                                                                                                                                                                                         , At present, police have recovered only £17,000, with most money sent abroad.                                                                                                                                                                                                                                               , Details of the case can be reported after court restrictions were lifted.                                                                                                                                                                                                                                                  , The two men were first arrested in 2018 following a police operation which started the year before.                                                                                                                                                                                                                        , Police officers from the National Crime Agency and the Metropolitan Police watched large bags of cash being carried into their East London flats that had been picked up in lorry parks and service stations.                                                                                                              , Both men, plus other members of their criminal network, opened bank accounts in the names of various fake companies they had set up, the NCA said.                                                                                                                                                                         , The money was then sent from one shell company to another "in a complex web of transfers", before being sent to accounts in Germany, the Czech Republic, U.A.E, Hong Kong, and Singapore.                                                                                                                                  , While on bail after their 2018 arrest, the men started fraudulently claiming Bounce Back Loans in 2020 for the various shell companies they had set up.                                                                                                                                                                    , The loans were part of government measures designed to cushion the UK economy from the effects of the coronavirus pandemic.                                                                                                                                                                                                , They claimed up to £50,000 a time, generating over £10m in total, with £3.2m claimed from one UK bank alone.                                                                                                                                                                                                               , Sentencing the two men, High Court judge Rajeev Shetty said their Bounce Back Loan fraud played a part in "undermining the government and financial institutions" and that the "the British taxpayer will be staggered and upset that part of their hard-earned tax contributions was going into the pockets of criminals"., At Kingston Crown Court, Terzyan was sentenced to 17 years in prison and Grochiatskij to 16 years after being convicted following a trial.                                                                                                                                                                                 , Andy Tickner, from the Organised Crime Partnership, said the pair had built "a sophisticated, large-scale money laundering system".                                                                                                                                                                                        , "They did so by setting up hundreds of bogus companies and utilising an international network of criminals under their control," he added.                                                                                                                                                                                 , "To top it off, they stole over £10m from British taxpayers in what is believed to be one of the largest Bounce Back Loan frauds since the scheme was introduced in 2020.                                                                                                                                                  , "These men and their network played a vital role in enabling other criminals to conceal and access their illicit earnings.                                                                                                                                                                                                 , "The removal of this service will have been a massive blow to organised criminals in the UK and globally."                                                                                                                                                                                                                 , Hayley Pearce chats terrible Christmas gifts...                                                                                                                                                                                                                                                                            , Follow the true story of one man's struggle to find out why his home disappeared                                                                                                                                                                                                                                           , © 2021 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2021-12-24 05:24:37 </td>
   <td style="text-align:left;"> Toronto Stocks at Near 1-Month High </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, rose 0.7% to close at 21,219 on Thursday, in line with its international peers, and extending gains for a third consecutive session to near a one-month high, boosted by gains in the tech and healthcare sector, while concerns over the new covid-19 variant Omicron eased as a South African study confirmed again the omicron variant is less severe than previous strains, albeit more infectious. On the data front, October’s GDP report showed that the economy expanded 0.8% during the month, as expected, with broad-based increases across sectors. Also, the Canada Government will temporally expand the support to businesses and people hit by the new covid strain, as provincial governments reimposed restrictions. On the week, the Canadian index jumped 2.4%, rebounding from last week's 0.7% loss. The markets are closed Friday for the Christmas holiday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2021-12-24 05:19:00 </td>
   <td style="text-align:left;"> Brazilian Equities Extend Losses </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Bovespa, fell 0.4% to close at 104,852 on Thursday, underperforming its international peers, and extending last session losses. The session was marked by a thin volume which added to the volatility. On the data front, the mid-month inflation data showed an increase of 0.78%, below market expectations, and ending the year 10.42% higher than 2020. Despite the headline inflation having decelerated from 1.17% in November, the breakdown showed that more sectors presented a positive increase in prices, at the same time that the services sector observed higher inflation. Meanwhile, the Brazilian economy created a net 324.1 thousand formal jobs in November of 2021, following a 415 thousand increase in November 2020 and higher than market forecasts of 216 thousand. On the week, the index shed 0.3%, extending last week's loss of 0.2%. The markets are closed Friday for the Christmas holiday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/sp-500-ends-record-ahead/story.aspx?guid={8CC95290-45FC-4FB9-A729-44349912B21E}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2021-12-24 05:04:02 </td>
   <td style="text-align:left;"> S&amp;P 500 ends at record ahead of Christmas holiday - MarketWatch </td>
   <td style="text-align:left;"> U.S. stocks ended higher Thursday in the final trading session ahead of the Christmas holiday, with the S&amp;P 500 closing at a record as investors appeared more confident the economy won't be derailed by the omicron variant of the coronavirus that causes COVID-19. The S&amp;P 500 
        SPX,
        +0.62%
       rose around 29 points, or 0.6%, to finish near 4,726, according to preliminary figures, exceeding its previous record finish of 4,712.02 set on Dec. 10. The Dow Jones Industrial Average 
        DJIA,
        +0.55%
       advanced around 197 points, or 0.5%, to end near 35,951, while the Nasdaq Composite 
        COMP,
        +0.85%
       gained around 131 points, or 0.8%, to close near 15,653. The S&amp;P 500 logged a 2.3% weekly rise, while the Dow rose 1.7% and the Nasdaq rallied 3.2%., A weekly look at the most important moves and news in crypto and what's on the horizon in digital assets.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , William Watts is MarketWatch’s senior markets writer. Based in New York, Watts writes about stocks, bonds, currencies and commodities, including oil. He also writes about global macro issues and trading strategies. Before moving to New York, he reported for MarketWatch from Frankfurt, London and Washington, D.C. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2021-12-24 05:02:29 </td>
   <td style="text-align:left;"> Wall Street Extends Gains, S&amp;P at New Record High </td>
   <td style="text-align:left;"> US stocks rose for the third straight session on Thursday, the S&amp;P gained 0.6% to finish at 4,726 a new closing record high, the Dow Jones added almost 200 points to close at 35,951 and the Nasdaq Composite jumped 0.9% as fears that the omicron variant would derail economic growth receded and President Biden said the US will not go back to lockdown. A South African study confirmed again the omicron variant is less severe than previous strains, albeit more infectious. On the data front, US consumer spending rose for the 6th straight month but slowed from October while the annual PCE inflation rose to 5.7%, the highest in 39 years. Also, jobless claims remained below pre-pandemic levels last week. All three main averages finished the week high, the Nasdaq Composite jumped 2.8%, the S&amp;P rose 2.2%, and the Dow Jones added 1.7%. US markets are closed Friday for the Christmas holiday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mauritius/gdp-growth-annual </td>
   <td style="text-align:left;"> 2021-12-24 04:14:28 </td>
   <td style="text-align:left;"> Mauritius Economy Slows to 5.5% in Q3 </td>
   <td style="text-align:left;"> The economy of Mauritius grew 5.5 percent from a year earlier in the third quarter of 2021, easing from a downwardly revised 17.8 percent growth in the previous period which was the strongest expansion since 2001. Output rose at a softer pace mainly for: manufacturing (10.1 percent vs 54.8 percent in Q2), mining &amp; quarrying (flat vs 95.3 percent), electricity, gas, steam and air conditioning supply (8.3 percent vs 17.6 percent), construction (12.8 percent vs 566.6 percent); wholesale &amp; retail trade (3.1 percent vs 11 percent); and transportation &amp; storage (0.1 percent vs 58.4 percent). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/mercury-systems-stock-pops-after/story.aspx?guid={B85256AC-90FF-4F59-B0F3-54D781B80875}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2021-12-24 04:06:04 </td>
   <td style="text-align:left;"> Mercury Systems stock pops after activist investor discloses stake - MarketWatch </td>
   <td style="text-align:left;"> Mercury Systems Inc. 
        MRCY,
        +10.27%
       shares jumped in Thursday trading after activist investor Jana Partners disclosed a fresh 6.6% stake in the component supplier to the aerospace and defense industry. Mercury stock was up 10% with about an hour to go in Thursday's trading session. In a filing with the Securities and Exchange Commission, Jana disclosed the purchase of roughly 3.7 million shares for approximately $181.1 million, with options to purchase another 173,300 shares. The activist investor said in the filing that it "intends to have discussions with the issuer's board of directors ... and management regarding maximizing value for shareholders including evaluating strategic alternatives including a sale of the Issuer, operations, capital allocation, corporate governance, board composition, and compensation practices." Even with Thursday's gains, Mercury shares have declined 36.7% so far this year, as the S&amp;P 500 index 
        SPX,
        +0.62%
       has gained 25%., Here's what to know about the verdict.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Jeremy Owens is MarketWatch’s technology editor and San Francisco bureau chief. You can follow him on Twitter @jowens510. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/oil-ends-higher-ahead-christmas/story.aspx?guid={6229DC8F-81E8-4B2F-980C-D44326EA157A}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2021-12-24 03:41:34 </td>
   <td style="text-align:left;"> Oil ends higher ahead of Christmas holiday as omicron worries fade - MarketWatch </td>
   <td style="text-align:left;"> Oil futures rose for a third straight day Thursday in the final session ahead of the Christmas holiday, boosted as worries over the effect of the omicron variant of the coronavirus on fuel demand faded, analysts said. West Texas Intermediate crude for February delivery 
        CL00,
        +1.37%
        CLG22,
        +1.37%
       rose $1.03, or 1.4%, to end at $73.79 a barrel on the New York Mercantile Exchange., Here's what to know about the verdict.                                                                                                                                                                                                                                                                                                                                                                                                   , William Watts is MarketWatch’s senior markets writer. Based in New York, Watts writes about stocks, bonds, currencies and commodities, including oil. He also writes about global macro issues and trading strategies. Before moving to New York, he reported for MarketWatch from Frankfurt, London and Washington, D.C. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/argentina/monthly-gdp-yoy </td>
   <td style="text-align:left;"> 2021-12-24 03:27:07 </td>
   <td style="text-align:left;"> Argentina Economic Activity Growth Eases Mores Than Expected </td>
   <td style="text-align:left;"> Argentina's economic activity advanced by 6.7 percent from a year earlier in October of 2021, following a downwardly revised 11.4 percent rise in the prior month and below market expectations of a 7.9 percent growth. Output growth eased for manufacturing (4.9 percent vs 11.1 percent), construction (6.9 percent vs 26.9 percent), retail &amp; wholesale trade (4.2 percent vs 8.9 percent), hotels &amp; restaurants (61 percent 72.8 percent), social services &amp; healthcare (3.3 percent vs 8.5 percent). Meanwhile, the activity level decreased for fishing (-32.6 percent vs -6.9 percent), agriculture (-1.6 percent vs -1 percent), utilities (-1 percent vs 4 percent), and financial intermediations (-1.2 percent vs 0.6 percent). On the other rate, output grew at a faster pace for mining (17 percent vs 16.4 percent), and transports (11.9 percent vs 11.1 percent). On a monthly basis, economic activity fell 0.8 percent, after expanding 0.8 percent in September. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/dow-tops-36000-afternoon-trade/story.aspx?guid={A43CA32B-8EF9-4A2C-95F4-9F97870B626E}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2021-12-24 03:19:53 </td>
   <td style="text-align:left;"> Dow tops 36,000 in afternoon trade, stocks touch session highs in final trading day before Christmas - MarketWatch </td>
   <td style="text-align:left;"> The Dow Jones Industrial Average topped the 36,000 mark in afternoon trade Thursday, as stocks rallied to session highs in the final session of trade before Christmas. The Dow 
        DJIA,
        +0.55%
       was up 260 points, or 0.7%, at 36,015, while the S&amp;P 500 index 
        SPX,
        +0.62%
       was up 36 points, or 0.8%, near 4,733, which was above its prior closing record of 4,712.02 set on Dec. 10. The Nasdaq Composite Index 
        COMP,
        +0.85%
       rose 148 points, or 1%, to 15,670. Equities got a boost from the approval of additional therapies to treat COVID-19 in high-risk adults and as concerns waned about the potential for the omicron variant to cause strict lockdowns to be imposed in the U.S. , The post-Christmas period represents the confluence of three powerful seasonal patterns.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Joy Wiltermuth is a news editor and senior markets reporter based in San Francisco. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/argentina/balance-of-trade </td>
   <td style="text-align:left;"> 2021-12-24 03:15:40 </td>
   <td style="text-align:left;"> Argentina Trade Surplus Widens Less Than Expected </td>
   <td style="text-align:left;"> Argentina's trade surplus rose to USD 397 million in November of 2021 from USD 383 million in the same month a year earlier and below market expectations of a USD 1,000 million surplus. Exports surged 37 percent to USD 6,164 million, boosted by sales of agroindustrial (13.5 percent), industrial manufacturing (59.7 percent), primary goods (75.2 percent), and fuels &amp; energy (25.3 percent). Meanwhile, imports advanced 40.1 percent to USD 5,767 million, sustained by higher purchases of intermediate products (53.4 percent), parts &amp; accessories for capital goods (27.8 percent), capital goods (19.1 percent), and consumer goods (21.9 percent), while the purchase of passenger motor vehicles plunged (-20.6 percent). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2021-12-24 02:56:40 </td>
   <td style="text-align:left;"> Dow Jones above 36000 </td>
   <td style="text-align:left;"> Dow Jones rose above 36000 points. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2021/12/23/politics/trump-vaccine-covid-effectiveness/index.html </td>
   <td style="text-align:left;"> 2021-12-24 02:54:40 </td>
   <td style="text-align:left;"> Trump touts effectiveness of Covid-19 vaccine - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)Former President Donald Trump pushed back on a questioner's skepticism about the effectiveness and safety of the Covid-19 vaccine in a new interview, saying that the "vaccine works" and "people aren't dying when they take the vaccine."                                                                                                                                                                                                                                  , "Look, the results of the vaccine are very good, and if you do get (Covid), it's a very minor form. People aren't dying when they take the vaccine," he said in an interview with The Daily Wire's Candace Owens that was released Tuesday.                                                                                                                                                                                                                                        , When Owens began raising doubt about the vaccine efficacy, Trump interjected, saying, "Well, no, the vaccine works."                                                                                                                                                                                                                                                                                                                                                               , "The ones that get very sick and go to the hospital are the ones that don't take their vaccine. But it's still their choice, and if you take the vaccine, you are protected," he said.                                                                                                                                                                                                                                                                                             , It's the latest endorsement by Trump, who has repeatedly declined opportunities to more forcefully urge Americans, and especially his supporters, about the importance of getting vaccinated. Cases and hospitalizations are presently surging across the US due to the Delta and Omicron variants, but reports largely indicate much milder outcomes for those who have been vaccinated and boosted as opposed to those who haven't been vaccinated.                              , Trump, however, has frequently politicized the development and rollout of the vaccines and told The Wall Street Journal in September that he was unlikely to get a booster shot. He was also inconsistent on promoting science-backed recommendations to slow the spread of the virus and pushed disproven treatments for Covid-19.                                                                                                                                                , In the interview with Owens, Trump championed his administration's efforts to develop Covid vaccines.                                                                                                                                                                                                                                                                                                                                                                              , "I came up with a vaccine, with three vaccines. All are very, very good. Came up with three of them in less than nine months," he said.                                                                                                                                                                                                                                                                                                                                            , Trump, however, called mandates requiring children to wear masks in school "a terrible thing."                                                                                                                                                                                                                                                                                                                                                                                     , "I don't like to see the kids with the masks on," he said in his interview with Owens. "They're sitting in school, they have a hard enough time sitting in school."                                                                                                                                                                                                                                                                                                                , During a recent speaking tour stop in Dallas, Trump revealed that he received his booster shot of the Covid-19 vaccine, an answer that prompted boos from a portion of the audience that he brushed off.                                                                                                                                                                                                                                                                           , Last fall, Trump contracted Covid-19 and experienced such severe illness that he had to be hospitalized, treated with a number of drugs and vitamins and given supplemental oxygen. As President, Trump rarely discussed his own immunization and declined to receive his shots of the vaccine publicly to help boost confidence in vaccination. After he left the White House, it was reported that he and Melania Trump had quietly received their Covid-19 vaccines in January. , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2021/12/23/stocks-making-the-biggest-moves-midday-nikola-las-vegas-sands-stitch-fix-crocs-and-more.html </td>
   <td style="text-align:left;"> 2021-12-24 01:50:59 </td>
   <td style="text-align:left;"> Stocks making the biggest moves midday: Nikola, Las Vegas Sands, Stitch Fix, Crocs and more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                                                                    , Check out the companies making headlines in midday trading.                                                                                                                                                                                                                                                                                                                                                                        , Nikola — The electric truck maker saw its stock surging 17.9% a day after the company announced on Twitter that its first customer delivery is done and signaled there's more to come.                                                                                                                                                                                                                                             , Novavax — Vaccine producer Novavax fell 3.3% despite reporting on Wednesday that a two-dose treatment of its Covid-19 vaccine demonstrated strong immune responses against the omicron variant. It also said the response to omicron was lower than the response against the original virus strain and added a booster dose would be helpful.                                                                                      , JD.com — Shares of JD.com fell about 7% after the Chinese social media company Tencent said it will distribute most of its stake in the Chinese e-commerce giant to shareholders in the form of a $16.4 billion dividend.                                                                                                                                                                                                          , Las Vegas Sands, Wynn — Casino stocks with exposure to Macao rose on Thursday after the local government released the results of a review of the gaming industry. The review determined that there should be six operators, according to FactSet's StreetAccount. Shares of Wynn rose 3.5%, while Las Vegas Sands added 4.2%. Both stocks are still trading below where they were in mid-September when Macao announced the review., Stitch Fix — Shares of Stitch Fix gained 8% after one of its shareholders, Working Capital Advisors, disclosed that it purchased 3.4 million shares in the company, bringing its total holdings to 10.6 million shares.                                                                                                                                                                                                            , Crocs — Shares of Crocs dropped more than 11.6% after the footwear maker announced it would buy privately held rival Heydude for $2.5 billion in cash and stock. The companies said they expect the deal to close in the first quarter of next year.                                                                                                                                                                               , Tesla — Tesla shares rose more than 5% after CEO Elon Musk announced he's "almost done" selling his shares, after offloading more than $15 billion worth for more than one month. Earlier in the week he suggested he had completed "enough" transactions to reach his goal of selling 10% of his shares.                                                                                                                          , Ortho Clinical Diagnostics, Quidel — Shares of the in-vitro diagnostics company climbed 6.9% following news that Ortho will be acquired by Quidel, a diagnostics technology provider. The cash-and-stock deal is valued at about $24.68 per share. Quidel shares tumbled by about 17%.                                                                                                                                             , Sciplay, Scientific Games — SciPlay, a digital games developer and publisher, saw its shares slide 12.8% a day after Scientific Games, one of its largest shareholders, withdrew its offer to acquire the remaining 19% equity interest in the company. Meanwhile, Scientific Games shares jumped more 8.9%.                                                                                                                       , Mission Produce — The produce company's shares tumbled 8.5% after it reported a quarterly miss on both earnings and revenue, noting that its results were affected by supply challenges.                                                                                                                                                                                                                                           ,  — CNBC's Hannah Miao, Jesse Pound and Yun Li contributed reporting                                                                                                                                                                                                                                                                                                                                                                , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                             , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                             , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                   , © 2021 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                   , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                 , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2021-12-24 01:25:00 </td>
   <td style="text-align:left;"> Wall Street Extends Gains, S&amp;P Towards Record High </td>
   <td style="text-align:left;"> US stocks rose for the third straight session on Thursday, the S&amp;P gained 0.7% marching towards intraday record high of 4,743 hit on November 22nd, the Dow Jones added more than 200 points and the Nasdaq Composite jumped 0.8% as fears that the omicron variant would derail economic growth receded and President Biden said the US will not go back to lockdown. A South African study confirmed again the omicron variant is less severe than previous strains, albeit more infectious. On the data front, US consumer spending rose for the 6th straight month but slowed from October while the annual PCE inflation rose to 5.7%, the highest in 39 years. Also, jobless claims remained below pre-pandemic levels last week. All three averages are on track to end the week higher. US markets are closed Friday for the Christmas holiday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2021-12-24 01:18:46 </td>
   <td style="text-align:left;"> Oil Extends Gains to Near 1-Month High </td>
   <td style="text-align:left;"> WTI crude futures rose more than 1% to trade around $73.5 per barrel on Thursday, hovering near 4-week highs, amid an improvement in risk appetite as economic optimism grows. Despite the rise in Covid-19 cases and new restrictions, investors are betting that the economic recovery will not derail as studies showed that the omicron variant is less severe than previous strains, albeit more infectious. Also, US crude stockpiles declined more than expected. US inventories fell by 4.72 million barrels, its fourth straight weekly draw and well above market estimates for a 2.75 million barrel decline. Tightness in supply has also been exacerbated by an energy crunch in Europe and supply disruptions in Africa. Natural gas prices in Europe surged to record highs as flows from a key Russian pipeline stopped, forcing some countries to boost electricity imports and burn oil to meet demand. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/biden-administration-response-come-january/story.aspx?guid={CC36B769-87F8-43B6-A5F7-11C0C1DEC316}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2021-12-24 01:16:20 </td>
   <td style="text-align:left;"> Biden administration: Response will come in January to Putin's security proposals - MarketWatch </td>
   <td style="text-align:left;"> The Biden administration plans to offer a substantive response to recent security proposals from Russian President Vladimir Putin during January talks and has not yet responded substantively, a senior administration official told reporters on Thursday. An exact date for the talks has not yet been set, and the U.S. is continuing to watch closely Russia's "alarming" military movements along the border with Ukraine, the official also said., The Biden White House on Tuesday expresses openness to working with Republican Sen. Mitt Romney on child tax credit payments, after the Utah lawmaker calls for a bipartisan approach on the issue.                                                                                                                                                                                                                                                     ,                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Victor Reklaitis is MarketWatch's Money &amp; Politics reporter and is based in Washington, D.C. Prior to joining MarketWatch, he served as an assistant editor and reporter at Investor's Business Daily. Before IBD, he worked for several newspapers in Virginia. Follow Victor on Twitter at: @vicrek. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/government-bond-yield </td>
   <td style="text-align:left;"> 2021-12-24 01:07:00 </td>
   <td style="text-align:left;"> Brazil 10Y Bond Yield Rebounds From Near 4-Month Low </td>
   <td style="text-align:left;"> Brazil's 10-year government bond yield traded above 10.60% on the third week of December, after hitting a near 4-month low of 10.24% on December 22nd, tracking a rebound in international government bond yields amid an improvement in risk appetite as economic optimism grows. Despite the rise in Covid-19 cases and new restrictions, investors are betting that the economic recovery will not derail as studies showed that the omicron variant is less severe than previous strains, albeit more infectious. Domestically, Congress approved the 2022 budget, decreasing short-term uncertainties, while pointing to a very inflexible budget. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mexico/currency </td>
   <td style="text-align:left;"> 2021-12-24 00:59:39 </td>
   <td style="text-align:left;"> Mexican Peso at 6-Week High </td>
   <td style="text-align:left;"> The Mexican peso traded around 20.65 per USD in the third week of December, the strongest since November 12th, amid an improvement in risk appetite and a rebound in oil prices as economic optimism grows. Despite the rise in Covid-19 cases and new restrictions, investors are betting that the economic recovery will not derail as studies showed that the omicron variant is less severe than previous strains, albeit more infectious. Also, in its last meeting, the Mexican Central bank surprised the markets and hiked the borrowing costs by 50 bps to 5.5%, above expectations of 25 bps saying inflation risk balance has deteriorated, with both the headline inflation and the core inflation expectations for the next year increasing again, and the ones for the medium-term remaining above the target. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2021/12/23/politics/donald-trump-supreme-court-records-january-6/index.html </td>
   <td style="text-align:left;"> 2021-12-24 00:57:44 </td>
   <td style="text-align:left;"> House panel asks Supreme Court to say by mid-January whether it's taking Trump's January 6 records case - CNNPolitics </td>
   <td style="text-align:left;"> Washington (CNN)Former President Donald Trump appealed to the Supreme Court on Thursday to block the release of documents from his White House to the House committee investigating the January 6 riot at the Capitol, escalating his effort to keep about 700 pages of records secret.                                                                                                                                                                                                                                                                     , Hours after Trump's request was filed, the House committee asked the justices to expedite their consideration of the request, with a proposed schedule that would allow the court to say by the middle of next month whether it was taking up the case.                                                                                                                                                                                                                                                                                                     , The committee, which is charged with investigating the US Capitol attack to provide recommendations for preventing such assaults in the future, seeks the documents as it explores Trump's role in trying to overturn the election. That includes his appearance at a January 6 rally when he directed followers to go to the Capitol where lawmakers were set to certify the election results and "fight" for their county. The documents are currently held by the National Archives.                                                                     , In filings submitted to the Supreme Court on Thursday, Trump asked the justices to take up a full review of the case and he requested that while they consider his position, they put a hold on the lower court decision permitting the disclosure of his records while they consider taking up the case.                                                                                                                                                                                                                                                   , "The limited interest the Committee may have in immediately obtaining the requested records pales in comparison to President Trump's interest in securing judicial review before he suffers irreparable harm," Trump's lawyers wrote in the court filings.                                                                                                                                                                                                                                                                                                  , Records could answer longstanding questions about riot                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , At issue are hundreds of documents including activity logs, schedules, speech notes and three pages of handwritten notes from then-White House chief of staff Mark Meadows -- paperwork that could reveal goings-on inside the West Wing as Trump supporters gathered in Washington and then overran the US Capitol, disrupting the certification of the 2020 vote. The records could answer some of the most closely guarded facts of what happened between Trump and other high-level officials, including those under siege on Capitol Hill on January 6., Trump is also seeking to keep secret a draft proclamation honoring two police officers who died in the siege and memos and other documents about supposed election fraud and efforts to overturn Trump's loss of the presidency, the National Archives has said in court documents.                                                                                                                                                                                                                                                                         , In its expedition request Thursday evening, the House committee said that any delay in the Supreme Court's consideration would "inflict a serious injury on the Select Committee and the public."                                                                                                                                                                                                                                                                                                                                                           , "The Select Committee needs the requested documents now to help shape the direction of the investigation and allow the Select Committee to timely recommend remedial legislation," the panel said. It said the committee and the Biden administration would file by December 30 their responses to Trump's request that the Supreme Court take up the case. The lawmakers are asking the Supreme Court to consider during its January 14 conference whether it will take up the case.                                                                       , The fight over the documents stems from a lawsuit Trump filed against the Archives as well as the House committee, seeking to stop the records' disclosure. Trump is arguing that those documents should remain secret under the former President's own assertions of executive privilege, though so far, lower courts have rejected his arguments.                                                                                                                                                                                                         , Thursday's filing with the Supreme Court marks an escalation of the dispute, in which President Joe Biden has determined that withholding the documents based on executive privilege is not in the interest of the United States. In a letter to the National Archives in October, White House Counsel Dana A. Remus said that the President had declined to assert privilege because Congress has a "compelling need in service of its legislative functions to understand the circumstances that led to these horrific events."                           , In their filings with the Supreme Court Thursday, the former President's lawyers said that the House's request for the Trump White House documents was "untethered from any valid legislative purpose and exceeds the authority of Congress under the Constitution and the Presidential Records Act."                                                                                                                                                                                                                                                       , Trump told the Supreme Court that the case posed "novel and important questions of law that the Court should resolve."                                                                                                                                                                                                                                                                                                                                                                                                                                      , "While the protections of executive privilege and restrictions on access to presidential records are qualified, it is critical that future Presidents and their advisers understand the contours and perimeters of that privilege—and its exceptions—after the conclusion of a presidential term," Trump said in his request that the court take up the case.                                                                                                                                                                                               , Arguments rejected by lower courts                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Previously, both a district court judge and the DC US Circuit Court of Appeals rejected Trump's arguments in decisions that backed the legitimacy of the document requests and the investigation more broadly.                                                                                                                                                                                                                                                                                                                                              , "Former President Trump has given this court no legal reason to cast aside President Biden's assessment of the Executive Branch interests at stake, or to create a separation of powers conflict that the Political Branches have avoided," the DC Circuit said in its opinion earlier this month. In its December 9 ruling against Trump, the appeals court gave him 14 days to request a Supreme Court intervention.                                                                                                                                      , In his application with Chief Justice John Roberts -- who oversees emergency matters arising from the DC Circuit -- to put the appeals court decision on hold, Trump said that allowing for the documents to be released before the Supreme Court considered the case would "detrimentally impact Presidential decisionmaking for all future Presidents."                                                                                                                                                                                                   , "There will not be another Presidential transition for more than three years; Congress has time to allow this Court to consider this expedited appeal," Trump wrote in the filing.                                                                                                                                                                                                                                                                                                                                                                          , Left unsaid was that Republicans are expected to take control of the House in next year's election and would likely end the House select committee's investigation.                                                                                                                                                                                                                                                                                                                                                                                         , This story has been updated with further developments and additional information.                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2021-12-24 00:48:00 </td>
   <td style="text-align:left;"> UK Stocks Extend Gains to Near 5-Week High </td>
   <td style="text-align:left;"> The FTSE 100 rose 0.4% to close at 7,375 on Thursday, in line with its European peers and extending gains for a 3rd straight session to near a 5-week high of 7,379 hit on December 8th, as concerns over the new covid-19 variant Omicron eased boosting air travel companies gains, while banks shares climbed on the back of higher government bond yields. A South African study showed reduced omicron hospitalizations and severe cases, while researchers in Scotland and at Imperial College of London also found lower hospitalization rates among omicron infections. Traders also welcomed the approval by the US FDA of the new Pfizer antiviral COVID-19 pill for people aged 12 or above at risk of severe disease. On the data front, UK auto production slumped 28.7% yoy in November amid ongoing supply chain issues and the global semiconductor chip shortage. On corporate news, online bookmaker Flutter Entertainment rose almost 5% after announcing it would buy Italian peer Sisal for £1.62 billion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2021-12-24 00:48:00 </td>
   <td style="text-align:left;"> Italian Shares Close at 2-Week Highs </td>
   <td style="text-align:left;"> The FTSE MIB extended yesterday’s gains to close 0.7% higher at 27,016.22, the highest in two weeks, as investors welcomed supportive data from the US and digested new pandemic related restriction measures. Manufactured durables orders and University of Michigan’s consumer sentiment indicator beat market forecasts, while weekly jobless claims held below pre-pandemic levels. At the same time, Prime Minister Mario Draghi announced further restriction measures to be implemented. Masks are to be worn outdoors and ffp2 masks are mandated for cultural events and public transportation, but the government did not deem any lockdowns necessary. National data indicates that Omicron variant cases are currently being doubled every two days. On the corporate front, Cnh Industrial rose 3.5% after shareholders approved the spin-off of its track-making subsidiary Iveco. Shareholders are to receive one Iveco share for every five Cnh shares in posession. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2021-12-24 00:47:00 </td>
   <td style="text-align:left;"> European Stocks Close at 2-Week Highs </td>
   <td style="text-align:left;"> European stocks traded closed at two-week highs on Thursday, as concerns about the omicron strain faded. The pan-European Stoxx 600 gained 1.0%, with the travel &amp; leisure sector up 1.7%, while Germany’s DAX rose 1.1%. Sentiment improved after a trio of studies showed that infections with the omicron strain led to lower hospitalization rates and milder cases. On the corporate front, Ryanair warned its losses this year could be more than double due to renewed travel restrictions in response to the spread of the Omicron. On the data front, German import prices surged by the most since 1974, while in the US December consumer confidence beat expectations. Meanwhile, Italy’s PM said he’d be willing to become Italy’s next President if Parliament voted him to the position, adding that political stability in the country is not in danger. On a weekly basis, the DAX rose 0.7% and the Stoxx 600 ended 1.4% higher. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2021-12-24 00:46:00 </td>
   <td style="text-align:left;"> French Stocks Close at 1-Month High </td>
   <td style="text-align:left;"> The CAC 40 Index extended earlier gains to close 0.8% higher at 7,106.15 on Thursday, the a one-month high, as investors welcomed promising US macroeconomic figures while pandemic fears momentarily waned. Orders for manufactured durable goods and University of Michigan’s consumer sentiment indicator both beat market forecasts, while initial jobless claims held below pre-pandemic levels. In the meantime, studies from South Africa, England, and Scotland suggest that those infected with the Omicron variant face lower likelihoods of hospitalization when compared to the Delta variant. On the corporate front, Airbus rose 0.6% after securing a EUR 10 billion contract with the French Armed Forces for the supply of 169 helicopters. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2021/12/23/nikola-shares-surge-after-company-delivers-its-first-ev-truck-says-more-to-come.html </td>
   <td style="text-align:left;"> 2021-12-24 00:22:08 </td>
   <td style="text-align:left;"> Nikola shares surge 18% after company delivers its first EV truck, says more to come </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                             , Nikola shares jumped 18% on Thursday after the electric truck maker completed delivery of its first vehicle.                                                                                                                                                                ,                                                                                                                                                                                                                                                                             , The surge in the stock came a day after the company announced on Twitter that its first customer delivery is done, signaling more to come.                                                                                                                                  , Earlier this week, Nikola said it agreed to pay the Securities and Exchange Commission $125 million to settle charges it defrauded investors by misleading them about its products, technical capacity and business prospects.                                              , The SEC said Nikola is responsible for misleading claims made by the company's founder and former chief executive officer, Trevor Milton. He pleaded not guilty to fraud charges brought by the Justice Department in July.                                                 , Nikola went public in June 2020 by merging with a SPAC. The stock hit a record high above $90 a share soon after the IPO but came all the way back down due to the regulatory probe.                                                                                        , A slew of pre-revenue electric vehicle start-ups sought to go public through SPAC deals following Nikola, which garnered regulators' attention. Nikola was one of at least four EV companies under investigation by federal agencies about potentially misleading investors., — CNBC's Tom Franck and Mike Wayland contributed reporting.                                                                                                                                                                                                                 , Wall Street analysts pick their favorite Tesla alternatives for 2022                                                                                                                                                                                                        , Top auto analyst Adam Jonas shares his 2022 surprises, plus a prediction for a big move by Tesla                                                                                                                                                                            , Major Wall Street firms remain largely positive on Rivian despite post-earnings sell-off                                                                                                                                                                                    , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                      , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                      , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                            , © 2021 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                            , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                          , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/hong-kong/current-account </td>
   <td style="text-align:left;"> 2021-12-24 00:19:06 </td>
   <td style="text-align:left;"> Hong Kong Q3 Current Account Surplus 2nd Largest on Record </td>
   <td style="text-align:left;"> Hong Kong’s current account surplus narrowed to HKD 96.7 billion in the third quarter of 2021, the second largest surplus in the series history, after a record HKD 99.9 billion in the same period of the previous year and accounted for 13.2 percent of GDP. The goods account surplus shrank to HKD 4.2 billion, from HKD 32.7 billion in 2Q 2020 and the services surplus widened to HKD 33.5 billion from HKD 24.5 billion a year earlier. At the same time, the primary income surplus expanded sharply to HKD 63.8 billion from HKD 47.5 billion, while the secondary income gap increased to HKD 4.8 billion from HKD 4.7 billion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2021-12-24 00:12:00 </td>
   <td style="text-align:left;"> Toronto Stocks Extend Gains for 3rd Session </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, opened higher trading above 21,100 on Thursday, in line with its international peers, and extending gains for a third consecutive session,  boosted by gains in the energy and financial sector, while concerns over the new covid-19 variant Omicron eased as a South African study confirmed again the omicron variant is less severe than previous strains, albeit more infectious. The energy sector extended gains on the back of higher oil prices, at the same time that the financial stocks were boosted by prospects of higher yields, the Canadian 10-year bond yield rose to around 1.46% while the US was higher at 1.5%. On the data front, October’s GDP report showed that the economy expanded 0.8% during the month, as expected, with broad-based increases across sectors. Also, the Canada Government will temporally expand the support to businesses and people hit by the new covid strain, as provincial governments reimposed restrictions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/spx:ind </td>
   <td style="text-align:left;"> 2021-12-24 00:07:54 </td>
   <td style="text-align:left;"> S&amp;P 500 Hits 4-week High </td>
   <td style="text-align:left;"> US500 increased to a 4-week high of 4732 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/larry-summers-recession-surging-inflation </td>
   <td style="text-align:left;"> 2021-12-24 00:04:14 </td>
   <td style="text-align:left;"> Larry Summers warns of looming recession over surging inflation </td>
   <td style="text-align:left;"> 'FOX Business Tonight' host examines the cause of higher gas prices.                                                                                                                                                                                                                                                                                                                                                                                  , Former Treasury Secretary Larry Summers on Thursday warned the U.S. economy could slide into a recession as the Federal Reserve takes what he described as long-delayed action to cool the hottest inflation in nearly four decades.                                                                                                                                                                                                                  , Summers, during an interview on a Bloomberg Economics podcast, said the U.S. central bank has been late to spot the dangers of inflation, and that steps it takes now to mitigate soaring prices risk tipping the economy into a slump.                                                                                                                                                                                                               , JEROME POWELL FACES TURBULENT 2022 AS FED WALKS ECONOMIC TIGHTROPE                                                                                                                                                                                                                                                                                                                                                                                    , "If I thought we could sustainably run the economy in a red-hot way, that would be a wonderful thing, but the consequence – and this is the excruciating lesson we learned in the 1970s – of an overheating economy is not merely elevated inflation, but constantly rising inflation," Summers said. "That’s why my fear is, that we are already reaching a point where it will be challenging to reduce inflation without giving rise to recession.", Members of President Biden's task force on supply chain issues listen as he speaks during a meeting, Wednesday, Dec. 22, 2021, in the South Court Auditorium on the White House campus in Washington.  (Patrick Semansky / AP Newsroom)                                                                                                                                                                                                               , Summers, a Harvard University professor who served in both the Clinton and Obama administrations, has repeatedly sounded the alarm over rising inflation and has spent much of 2021 arguing that the Biden team, as well as Fed policymakers, have underestimated the risk of soaring consumer prices.                                                                                                                                                , He has warned that putting off tackling inflation will only require more severe action down the road that could undermine the economy's recovery from the pandemic.                                                                                                                                                                                                                                                                                   , "We’ve got a fairly serious inflationary situation," Summers said.                                                                                                                                                                                                                                                                                                                                                                                    , Soaring inflation that has shown no signs of slowing down has forced the central bank and the White House to shift closer to Summers' stance. The government reported earlier this month that prices jumped 6.8% in November from the previous year, the fastest pace since June 1982, when inflation hit 6.1%.                                                                                                                                       , A separate report out Thursday morning showed the Fed's preferred inflation gauge also hit a 39-year high last month, surging to 5.7% – well above the central bank's preferred target of 2%.                                                                                                                                                                                                                                                         , Larry Summers speaks during the World Bank/IMF annual meetings in Washington, Oct. 9, 2014.  (Joshua Roberts / Reuters Photos)                                                                                                                                                                                                                                                                                                                        , Last week, the Fed took a hawkish pivot, announcing that it would accelerate its withdrawal of support from the economy in order to tackle rising prices.                                                                                                                                                                                                                                                                                             , The Federal Open Market Committee said at the conclusion of its two-day policy-setting meeting that it would double the reduction of its asset-purchase program to $30 billion a month, a timeline that could phase out the purchases entirely by March rather than the original June trajectory laid out last month.                                                                                                                                 , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                           , Although policymakers voted to hold rates near zero, where they have sat since March 2020, new economic projections show that a majority of Fed officials have penciled in three rate hikes next year.                                                                                                                                                                                                                                                , Officials now project rates to stand at 0.9% at the end of 2022, 1.6% at the end of 2023 and 2.1% at the end of 2024. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ivory-coast/inflation-cpi </td>
   <td style="text-align:left;"> 2021-12-24 00:03:00 </td>
   <td style="text-align:left;"> Ivory Coast August Inflation rate at 10-1/2-Year High </td>
   <td style="text-align:left;"> The annual inflation rate in Ivory coast picked up to 5.5 percent in November of 2021, the highest since May of 2011, from 4.5 percent in the prior month. Main upward pressure came from prices of food &amp; non-alcoholic beverages (11.4 percent vs 8.9 percent in October), of which vegetables (26.3 percent) and Tubers and plantains (18.5 percent); housing &amp; utilities (4.8 percent vs 4.3 percent) and transport (4.3 percent vs 2.6 percent). Meanwhile prices eased for furnishings (1.3 percent vs 2.1 percent) and education (0.7 percent vs 1.6 percent) and continued to decline for recreation and culture (-1.1 percent vs -1.2 percent). On a monthly basis, consumer prices, edged up 0.7 percent, accelerating from a 0.3 percent uptick in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-59769393?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2021-12-23 23:59:27 </td>
   <td style="text-align:left;"> Intel apologises to China over supplier advice </td>
   <td style="text-align:left;"> US microchip maker Intel has apologised following a backlash over its letter urging suppliers not to source products or labour from China's Xinjiang region.                                                                                     , The company's letter sparked criticism in China, with calls for a boycott.                                                                                                                                                                       , The letter said Intel had been "required to ensure" its supply chain did not use labour or source goods from Xinjiang, following restrictions imposed by "multiple governments".                                                                 , China has been accused of human rights abuses in Xinjiang.                                                                                                                                                                                       , The region is home to many of country's Muslim Uyghur population and there have been allegations of forced labour and possibly genocide.                                                                                                         , In December last year, the BBC published an investigation based on new research showing China was forcing hundreds of thousands of minorities, including Uyghurs, into manual labour in Xinjiang's cotton fields.                                , Beijing has repeatedly denied the claims.                                                                                                                                                                                                        , In a Chinese-language statement on its official WeChat and Weibo accounts, Intel said that its commitment to avoid supply chains from Xinjiang was an expression of compliance with US law, rather than a statement of its position on the issue., "We apologise for the trouble caused to our respected Chinese customers, partners and the public. Intel is committed to becoming a trusted technology partner and accelerating joint development with China," the firm said.                     , The White House said President Joe Biden signed into a law a bill that requires companies to prove that goods imported from China's Xinjiang region have not been produced with forced labour.                                                   , The bill was passed by Congress last week with the aim of stopping US companies from benefitting from forced labour, something which China denies is the case.                                                                                   , Many Weibo users derided Intel's apology as an attempt at protecting sales in China, with one saying: "A mistake is a mistake! Retract the statement about Xinjiang!"                                                                            , Meanwhile, the hashtag "Is Intel's apology sincere?" was trending on Weibo on Thursday, Reuters reported.                                                                                                                                        , Singer Karry Wang said he would no longer serve as brand ambassador for Intel, adding in a statement that "national interests exceed everything".                                                                                                , Intel is not the first company to come under pressure over aims to comply with sanctions related to Xinjiang while continuing to operate in China.                                                                                               , Retail giants Nike and H&amp;M faced a backlash earlier this year after they expressed concern about the alleged use of Uyghur forced labour in cotton production.                                                                                   , Intel, which has 10,000 employees in China, said in its apology that it respected "the sensitivity of the issue in China".                                                                                                                       , Meanwhile, China's foreign ministry said "accusations of forced labour in Xinjiang are lies concocted by anti-China American forces" aimed at destabilising China and hindering its development.                                                 , "We note the statement and hope the relevant company will respect facts and tell right from wrong," said foreign ministry spokesman Zhao Lijian.                                                                                                 , Hayley Pearce chats terrible Christmas gifts...                                                                                                                                                                                                  , Follow the true story of one man's struggle to find out why his home disappeared                                                                                                                                                                 , © 2021 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/albania/gdp-growth-annual </td>
   <td style="text-align:left;"> 2021-12-23 23:59:00 </td>
   <td style="text-align:left;"> Albania GDP Growth Eases to 6.99% in Q3 </td>
   <td style="text-align:left;"> Albania's gross domestic product expanded 6.99 percent year-on-year in the third quarter of 2021, easing from an upwardly revised 18.38 percent rise in the previous period. There was a slowdown in all sectors: household consumption (3.33 percent vs 10.91 percent in Q2 of 2021), gross fixed capital formation (3.84 percent vs 36.84 percent) and government expenditure (7.59 percent vs 11.33 percent). Meanwhile, foreign demand contributed positively to growth as exports went up 62.73 percent (vs 130.55 percent in Q2) while imports rose at a softer 35.87 percent (vs 53.72 percent). On a quarterly basis, the economy expanded by 0.73 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/currency </td>
   <td style="text-align:left;"> 2021-12-23 23:57:00 </td>
   <td style="text-align:left;"> Canadian Dollar Extends Rebound </td>
   <td style="text-align:left;"> The Canadian dollar traded around 1.28, after hitting a one-year low of 1.294 on December 20th, amid an improvement in risk appetite and a rebound in oil prices as economic optimism grows. Despite the rise in Covid-19 cases and new restrictions, investors are betting that the economic recovery will not derail as studies showed that the new variant is less severe than previous strains, albeit more infectious. On the data front, October’s GDP report showed an expansion of 0.8%, as expected, accelerating from a 0.2% increase in September, and marking the fifth consecutive month of expansion. Meanwhile, preliminary data showed that the economy is likely to grow for the sixth month in November. A more robust economic recovery strengthens the appeal for higher rates from the BoC, which dashed investors’ expectations in its last meeting arguing that the new variant Omicron had raised uncertainty around the economic recovery. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/kosovo/gdp-growth-annual </td>
   <td style="text-align:left;"> 2021-12-23 23:54:00 </td>
   <td style="text-align:left;"> Kosovo Economy Grows 14.5% in Q3 </td>
   <td style="text-align:left;"> Kosovo’s GDP advanced 14.5 percent year-on-year in the third quarter of 2021, following an upwardly revised record of 16.8 percent rise in the previous period. Gross capital formation (0.14 percent vs 33.5 percent in Q2), government spending (4.6 percent vs 8.3 percent), and household consumption (4.6 percent vs 8.3 percent) expanded at a softer pace. Meanwhile, net external demand contributed positively to growth as total exports jumped 147.4 percent (vs 126.66 percent in Q2) while imports rose at a slower 44.4 percent (vs 53.8 percent in Q2). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/palladium </td>
   <td style="text-align:left;"> 2021-12-23 23:51:00 </td>
   <td style="text-align:left;"> Palladium Hits 4-week High </td>
   <td style="text-align:left;"> Palladium futures rose above $1900, the highest since November 22nd amid expectations of a rebound in demand, particularly from China and easing of the supply chain constraints from the second half of 2022. Nikos Kavalis, managing director at Metals Focus reported that Chinese imports would go up due to rise in demand supplemented by stock replenishment after a year of extremely low imports. He further added that the market would then see a deficit in metal from the second half of 2022, driving up the prices further. Meanwhile, Morgan Stanley in its December report said that a revival in auto production where Palladium is used in pollution-reducing catalytic converters, would also boost the demand for the metal in 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/intel-china-apologizes-for-xinjiang-statement </td>
   <td style="text-align:left;"> 2021-12-23 23:42:19 </td>
   <td style="text-align:left;"> Intel is latest US company to apologize to China while pushing social justice at home </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.
                                                                                                                                                                                                                                                                                                                                                                                                                       , Intel has apologized for discouraging suppliers from doing business with China's Xinjiang region, after a letter published on its website sparked backlash from a Chinese state-run publication and social media users.                                                                                                                                                                                                                                                 , Citing government restrictions in multiple countries on products from the area, Intel said they were "required to ensure our supply chain does not use any labor or source goods or services from the Xinjiang region." Now the company is trying to play damage control to quell the ire of their Chinese customers.                                                                                                                                                   , AMAZON REPORTEDLY TOOK DOWN REVIEWS OF CHINESE PRESIDENT'S BOOK AFTER DEMANDS                                                                                                                                                                                                                                                                                                                                                                                           , "We deeply apologize for the confusion caused to our respected Chinese customers, partners and the public," Intel said in a statement reported by The Wall Street Journal, in which they claimed that the previous letter had only been issued to be in compliance with American legal requirements.                                                                                                                                                                    , The statement was issued around the same time the Senate passed the Uyghur Forced Labor Prevention Act, which bans goods produced by slave labor in Xinjiang or other parts of China from entering the U.S. President Biden later signed the bill into law.                                                                                                                                                                                                             , ‘WOKE’ CORPORATIONS HIT FOR ‘BOWING TO CHINA WHILE SNUBBING AMERICA’ AS THEY IGNORE CHINESE UYGHUR GENOCIDE                                                                                                                                                                                                                                                                                                                                                             , Bob Swan, chief executive officer of Intel Corp., poses for a photograph at the company's headquarter in Taipei, Taiwan, on Tuesday, Oct. 8, 2019. (Ashley Pon/Bloomberg via Getty Images) (Ashley Pon/Bloomberg via Getty Images / Getty Images)                                                                                                                                                                                                                       , Intel in the past has taken a strong position for social justice regarding domestic issues in the U.S., including a May 2020 memo from CEO Bob Swan declaring that black lives matter following the deaths of George Floyd, Ahmaud Arbery and Breonna Taylor.                                                                                                                                                                                                           , "While racism can look very different around the world, one thing that does not look different is that racism of any kind will not be tolerated here at Intel or in our communities," Swan said.                                                                                                                                                                                                                                                                        , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                             , Now, however, Intel joins a growing list of major firms cozying up to China, despite government officials taking action against human rights abuses against the Uyghur population in Xinjiang. Airbnb, Coca-Cola, and General Electric are among the sponsors of the 2022 Winter Olympics in Beijing. The NBA famously capitulated to China by speaking against then-Houston Rockets general manager Daryl Morey after he tweeted in support of protesters in Hong Kong., Bob Swan, chief executive officer of Intel Corp., listens during a Bloomberg Studio 1.0 television interview in San Francisco on Tuesday, Dec. 10, 2019. (David Paul Morris/Bloomberg via Getty Images) (David Paul Morris/Bloomberg via Getty Images / Getty Images)                                                                                                                                                                                                   , Disney is often criticized for alleged self-censorship in its content to appease China. According to The Hollywood Reporter, a kiss scene in the Disney movie "Mulan" – which was filmed in the Xinjiang region of China – was cut under pressure from Chinese censors.                                                                                                                                                                                                 , Most recently, Reuters reported that Amazon took down all reviews of Chinese President Xi Jinping's book on one of the company's sites following a less than perfect review.                                                                                                                                                                                                                                                                                            , FOX Business' Tyler Olson and Samuel Dorman contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/russia/currency </td>
   <td style="text-align:left;"> 2021-12-23 23:34:15 </td>
   <td style="text-align:left;"> Russian Ruble Rebounds From 3-Week Low </td>
   <td style="text-align:left;"> The Russian ruble traded higher around $73.4 per dollar on the third week of December, strengthening from a 3-week low of $74.06 hit on December 20th amid an improvement in risk appetite and a rebound in oil prices as economic optimism grows. Despite the rise in Covid-19 cases and new restrictions, investors are betting that the economic recovery will not derail as studies showed that the omicron variant is less severe than previous strains, albeit more infectious. Brent crude oil, a global benchmark for Russia's main export, rebounded to above $75 per barrel, after hitting $71.5, the lowest since December 3rd. Also, on the monetary policy front, officials in Russia raised rates by 100bps last week to curb inflation and left the door open to further hikes. Meanwhile, lingering concerns over East-West tensions over Ukraine capped additional gains as President Vladimir Putin sought an immediate response from the United States and its allies to Russia's demands for security guarantees. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/government-bond-yield </td>
   <td style="text-align:left;"> 2021-12-23 23:13:48 </td>
   <td style="text-align:left;"> Germany 10Y Bond Yield Hits 4-week High </td>
   <td style="text-align:left;"> Germany 10 Year Government Bond Yeld increased to a 4-week high of -0.242% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/new-home-sales </td>
   <td style="text-align:left;"> 2021-12-23 23:04:00 </td>
   <td style="text-align:left;"> US New Home Sales Miss Forecasts </td>
   <td style="text-align:left;"> New home sales in the US jumped 12.4 percent month-over-month to a seasonally adjusted annual rate of 744K in November of 2021, following a downwardly revised 662K in October. It was the fastest rise in seven months and the highest reading since April, but below market expectations of 770K. Positive contributions from the West (53.2 percent), Northeast (15.6 percent) and the South (2.7 percent) were partly offset by a decline in the Midwest (-25.4 percent). The median sales price of new houses sold in November 2021 was $416,90014.1% higher than a year ago. There were 402K new homes available for sale in the market. At the current sales pace, it would take 6.5 months to exhaust the supply of new homes, compared with 3.6 months at the start of the year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/consumer-confidence </td>
   <td style="text-align:left;"> 2021-12-23 23:04:00 </td>
   <td style="text-align:left;"> US December Consumer Sentiment Beat Flash Estimates </td>
   <td style="text-align:left;"> The University of Michigan's consumer sentiment for the US rose to 70.6 in December of 2021, from 67.4 last month and above preliminary estimates of 70.4 points. The gauge for expectations was revised higher to 68.3 from 67.8 and the current conditions subindex was revised lower to 74.2 from 74.6. Inflation expectations for the year ahead moderated to 4.8% from 4.9% in the previous month and slightly below preliminary figures of 4.9%. Meanwhile, the 5-year outlook also eased to 2.9%, compared with 3.0% in both advance figures and November’s reading. The uptick was primarily supported by higher income expectations in the bottom third of the population distribution, who see their incomes rise at the fastest pace since 1999. The results were also influenced by the low number of interviews conducted to capture the impact of the rapid spread of the omicron variant. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 22:59:52 </td>
   <td style="text-align:left;"> FTSE 100 Hits 5-week High </td>
   <td style="text-align:left;"> GB100 increased to a 5-week high of 7379 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/belgium/inflation-cpi </td>
   <td style="text-align:left;"> 2021-12-23 22:48:20 </td>
   <td style="text-align:left;"> Belgium Inflation Rate at Over 13-Year High </td>
   <td style="text-align:left;"> Belgium’s annual inflation rate rose to 5.7 percent in December of 2021 from 5.6 percent in the previous month. It was the highest reading since July of 2008, as prices accelerated for food and non-alcoholic beverages (1.2 percent vs 0.2 percent in November), recreation and culture (3 percent vs 2.6 percent), and restaurants and hotels (4.4 percent vs 4.2 percent). On the other hand, inflation eased for housing and utilities (18.2 percent vs 18.6 percent) and transportation (8 percent vs 9 percent). On a monthly basis, consumer prices rose slightly rose by 0.1 percent, easing from a 1.25 percent increase in the prior month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/fda-authorizes-mercks-covid-19-antiviral/story.aspx?guid={FBEB1DC6-2EDB-43F5-BC34-0D0368535A3E}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2021-12-23 22:48:04 </td>
   <td style="text-align:left;"> FDA authorizes Merck's COVID-19 antiviral but only when other treatments are 'not accessible' or 'appropriate' - MarketWatch </td>
   <td style="text-align:left;"> Shares of Merck &amp; Co. Inc. 
        MRK,
        -0.56%
       were down 0.8% in trading on Thursday after the Food and Drug Administration authorized the company's COVID-19 antiviral for adults who have tested positive for the virus and are at high risk of disease progression. The other caveat of the FDA's authorization for this pill is that it should only be given "when alternative COVID-19 treatment options authorized by the FDA are not accessible or clinically appropriate." The regulator on Wednesday authorized Pfizer Inc.'s 
        PFE,
        -1.41%
       COVID-19 antiviral for teens and adults at high risk of disease progression; that authorization did not include any limitations relating to other treatments. Patients should start taking Merck's drug, molnupiravir, within five days of symptom onset; the regimen is four pills taken twice a day for five days. Data from clinical trials showed the drug can reduce the risk of COVID-19 hospitalization and death by 30%. Merck's stock is down 2.6% for the year, while the broader S&amp;P 500 
        SPX,
        +0.62%
       has gained 25.0%., An easing of pandemic fear and stronger U.S. economic data also were buoying markets ahead of the Christmas holiday.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Jaimy Lee is a health-care reporter for MarketWatch. She is based in New York. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gold </td>
   <td style="text-align:left;"> 2021-12-23 22:47:00 </td>
   <td style="text-align:left;"> Gold Prices Erase Gains after US Data </td>
   <td style="text-align:left;"> Gold prices traded around $1,800 an ounce on Thursday, pausing after a 1% rise in the previous session, pressured by a stronger greenback and higher US Treasury note yields after traders digested a batch of upbeat economic data. New orders for US manufactured durable goods rose 2.5% over the same period, faster than forecasts of 1.6%, and initial jobless claims were steady at 205 thousand last week, still below pre-pandemic levels, reflecting businesses’ resilience amid increasing headwinds from disruptions caused by the pandemic. Also, the Core PCE price index, the Fed’s preferred inflation gauge, rose 4.7% yoy in November, 0.2pp above market forecasts, a level that should keep the pressure on policymakers to control rising prices. Elsewhere, studies suggest that the omicron variant poses a reduced risk of hospitalization and severe diseases in infected people, easing concerns about rising cases. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 22:35:00 </td>
   <td style="text-align:left;"> Wall Street Rises for 3rd Day </td>
   <td style="text-align:left;"> US stocks rose for the third session on Thursday, with the Dow Jones gaining more than 200 points and the S&amp;P touching a 4-week high of 4732 as fears that the omicron variant would derail economic growth receded and President Biden said the US will not go back to lockdown. A South African study confirmed again the omicron variant is less severe than previous strains, albeit more infectious. On the data front, US consumer spending rose for the 6th straight month but slowed from October while the annual PCE inflation rose to 5.7%, the highest in 39 years. Also, jobless claims remained below pre-pandemic levels last week. All three averages are on track to end the week higher. US markets are closed Friday for the Christmas holiday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/belgium/business-confidence </td>
   <td style="text-align:left;"> 2021-12-23 22:31:00 </td>
   <td style="text-align:left;"> Belgium Business Morale at 9-Month Low </td>
   <td style="text-align:left;"> The business confidence barometer in Belgium edged down to 3.6 percent in December of 2021 from 4.2 in the previous month. It was the lowest level in business morale since March as sentiment weakened in business-related services (10.2 vs 15.3), particularly the outlook for activity; and building industry (1.2 vs 2.3) due to contraction in order books and lower use of the available equipment. Also, sentiment declined further for trade (-3.5 vs -2.4) on account of lower forecasts for employment and orders placed with suppliers. Meanwhile, business confidence increased in manufacturing industry (2.5 vs 3.1) due to a more favourable assessment of stock levels. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/government-bond-yield </td>
   <td style="text-align:left;"> 2021-12-23 22:21:00 </td>
   <td style="text-align:left;"> US 10Y Treasury Note Yield Gains Steam </td>
   <td style="text-align:left;"> The yield on the benchmark 10-year Treasury note rose past 1.49% on Thursday, as traders digested a batch of economic data, while omicron woes faded. The Core PCE price index, the Fed’s preferred inflation gauge, rose 4.7% yoy in November, 0.2pp above market forecasts, a level that should keep the pressure on policymakers to control rising prices. Meanwhile, initial jobless claims were steady at 205 thousand last week, still below pre-pandemic levels, reflecting businesses’ resilience amid increasing headwinds from disruptions caused by the pandemic. Meanwhile, studies showed infections from the omicron strain were less likely to develop to severe disease, while President Biden pushed back against concerns about a new lockdown. Finally, traders await developments about the “Build Back Better” Act, as the White House resumes talks with Senator Manchin. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/wage-growth </td>
   <td style="text-align:left;"> 2021-12-23 21:59:00 </td>
   <td style="text-align:left;"> Canada Weekly Earnings Rise for the 5th Month </td>
   <td style="text-align:left;"> Average weekly earnings of non-farm payroll employees in Canada rose 2.7 percent year-on-year to CAD 1,133.93 in October of 2021 and little changed from the previous month. It was the fifth straight month of increases in average weekly earnings and at the steepest pace since March. The largest gains were seen in information &amp; cultural industries (15.7 percent to CAD 1,636.27); mining, quarrying, oil and gas extraction (13.6 percent to CAD 2,223.34); accommodation &amp; food services (8.1 percent to CAD 464.69). Across Canadian provinces, earnings rose the most in Manitoba (5.3 percent to CAD 1.044.68); British Columbia (4 percent to CAD 1,137.39); Alberta (3.4 percent to CAD 1,227.97); Yukon (3.4 percent to CAD 1,328.93); and Ontario (2.7 percent to CAD 1,169.96). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/pce-price-index </td>
   <td style="text-align:left;"> 2021-12-23 21:59:00 </td>
   <td style="text-align:left;"> PCE Consumer Prices Rise the Most in 39 Years </td>
   <td style="text-align:left;"> The personal consumption expenditure price index in the US increased 5.7 percent from a year earlier in November, the most in 39 years, reflecting increases in both goods and services. Energy prices were up 34 percent while food prices increased 5.6 percent. Excluding food and energy, the index was up 4.7 percent. Month-over-month, the PCE rose by 0.6 percent, following an upwardly revised 0.7 percent advance in October as prices of goods grew at a slower pace (0.9 percent vs 1.3 percent in October) and services inflation picked up (0.5 percent from 0.4 percent). Within goods, durable goods inflation eased to 0.4 percent from 1.4 percent in the previous month, while non-durable goods inflation remained steady at 1.2 percent. Excluding food and energy, PCE prices advanced 0.5 percent, above market expectations of 0.4 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/monthly-gdp-mom </td>
   <td style="text-align:left;"> 2021-12-23 21:56:00 </td>
   <td style="text-align:left;"> Canada GDP Expands for 5th Month </td>
   <td style="text-align:left;"> The Canadian economy expanded 0.8% month-over-month in October of 2021, following a 0.2% growth in September and in line with market expectations. It was the fifth consecutive monthly expansion, as both goods-producing (+1.6%) and services-producing (+0.6%) industries were up, with 17 of 20 industrial sectors posting gains in October. Leading the growth were accommodation and food services, wholesale trade, construction and the arts and entertainment sectors, while the mining, quarrying, and oil and gas extraction sector offset some of the gains. Meanwhile, preliminary data showed that the economy expanded 0.3 percent in November. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/currency </td>
   <td style="text-align:left;"> 2021-12-23 21:56:00 </td>
   <td style="text-align:left;"> Greenback Edges Higher after Economic Data </td>
   <td style="text-align:left;"> The dollar index traded flat to higher above 96 on Thursday, steadying from a 0.4% drop in the previous session, as traders digested a large batch of economic data. Personal spending growth eased to 0.6% mom in November, from an upwardly revised 1.4% rise in October, as expected. Meanwhile, new orders for US manufactured durable goods rose 2.5% over the same period, faster than forecasts of 1.6%, as orders for transportation equipment rebounded on the back of a sharp jump in nondefense aircraft and parts orders. Meanwhile, the core PCE price index, the Fed’s favored inflation gauge, rose a faster-than-expected 4.7% yoy in November, strengthening the case that inflationary pressures are building up stronger than policymakers had expected. Encouraging news also came from the pandemic front, with a trio of studies showing the infections with the omicron strain led to lower hospitalization rates and milder cases. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 21:51:00 </td>
   <td style="text-align:left;"> US Futures Rise </td>
   <td style="text-align:left;"> US stock futures drifted higher on Thursday, pointing to the third session of gains as fears that the omicron variant would derail economic growth receded and President Biden said the US will not go back to lockdown. A South African study confirmed again the omicron variant is less severe than previous strains, albeit more infectious. On the data front, US consumer spending rose for the 6th straight month but slowed from October while the annual PCE inflation rose to 5.7%, the highest in 39 years. On Wednesday, the Dow Jones rose 0.7%, the S&amp;P 500 gained 1% and the Nasdaq climbed 1.2%. All three averages are on track to end the week higher. US markets are closed Friday for the Christmas holiday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/feds-inflation-gauge-hits-fresh-39-year-high-as-prices-soar-higher </td>
   <td style="text-align:left;"> 2021-12-23 21:47:54 </td>
   <td style="text-align:left;"> Inflation hits highest level in 39 years as consumer prices surge </td>
   <td style="text-align:left;"> Alba Wheels Up President Salvatore Stile discusses the supply chain disruption on 'FOX Business Tonight.'                                                                                                                                                                                                                                         , Annual inflation is running at the hottest pace in nearly four decades as widespread supply disruptions, extraordinarily high consumer demand and worker shortages fuel rapidly rising price increases.                                                                                                                                           , Prices soared by 5.7% in the year through November, according to the Personal Consumption Expenditures price index data released Thursday morning. That topped the previous month's rate of 5%, becoming the fastest pace increase since February 1982, when the gauge hit 6.17%.                                                                 , Excluding the more-volatile measurements of food and energy, prices rose 4.7% in November from the previous year – the highest since 1982. That measurement is the Federal Reserve's preferred gauge to track inflation; their target range is around 2%.                                                                                         , A shopper walks through the aisles of the Dollar Tree store in Alhambra, California on December 10, 2021.  (Photo by FREDERIC J. BROWN/AFP via Getty Images / Getty Images)                                                                                                                                                                       , In the one-month period between October and November, prices jumped 0.6% (0.5% when excluding food and energy costs).                                                                                                                                                                                                                             , The inflation spike largely reflected surging energy costs, which rose 34% from a year ago, and food costs, which were up 5.6% over that same time period. Services inflation rose by 4.3% in November, and goods inflation increased 8.5% – up from the 7.6% pace a month prior, the data shows.                                                 , JEROME POWELL FACES TURBULENT 2022 AS FED WALKS ECONOMIC TIGHTROPE                                                                                                                                                                                                                                                                                , The inflation data was accompanied by data on household spending, which showed that consumers saved less in November and that their consumption was largely unchanged after accounting for inflation. If consumer spending remains flat, the decrease ini demand could help tame inflation.                                                       , Petrol prices are seen displayed at a Conoco gas station, a brand owned by Phillips 66, in Brooklyn, New York, Nov. 11, 2021.  (REUTERS/Andrew Kelly / Reuters Photos)                                                                                                                                                                            , The data is further evidence of a spike in prices illustrated by a separate measure – the Consumer Price Index – which showed inflation rose by 6.8% in November from the previous year.                                                                                                                                                          , The report will likely reinforce the Federal Reserve's decision last week to accelerate the withdrawal of its monetary support for the U.S. economy, and could create additional pressure on the central bank to further tighten policy in 2022 by hiking interest rates.                                                                         , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                       , The Federal Open Market Committee said at the conclusion of its two-day policy-setting meeting last week that it would double the reduction of its asset-purchase program to $30 billion a month, a timeline that could phase out the purchases entirely by March rather than the original June trajectory laid out last month.                   , FILE - Federal Reserve Chairman Jerome Powell, right, testifies before the Senate Banking Committee on Capitol Hill.  (AP / AP Newsroom)                                                                                                                                                                                                          , Although policymakers voted to hold rates near zero, where they have sat since March 2020, new economic projections show that every Fed official has penciled in at least one rate hike next year – a considerable shift from September, when half of the central bankers believed interest rate increases were not warranted until at least 2023., Officials now project rates to stand at 0.9% at the end of 2022, 1.6% at the end of 2023 and 2.1% at the end of 2024. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/jobless-claims </td>
   <td style="text-align:left;"> 2021-12-23 21:37:00 </td>
   <td style="text-align:left;"> US Jobless Claims Hold Below Pre-Pandemic Levels </td>
   <td style="text-align:left;"> The number of Americans filing new claims for unemployment benefits remained unchanged from last week’s upwardly revised level at 205 thousand in the week that ended December 18th, in line with market expectations and remaining below pre-pandemic levels. The 4-week moving average of claims, which removes week-to-week volatility, rose to 206.25 thousand. On a non-seasonally adjusted basis, initial claims went down by 11,686 to 254,006, with notable decreases from Missouri (-5,736), Pennsylvania (-4,582), Georgia (-1,972), and Kentucky (-1,931). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/personal-income </td>
   <td style="text-align:left;"> 2021-12-23 21:32:00 </td>
   <td style="text-align:left;"> US Personal Income Rises 0.4% in November </td>
   <td style="text-align:left;"> Personal income in the United States increased 0.4 percent from a month earlier in November 2021, following a 0.5 percent growth in October and matching market expectations as most companies increased wages to attract and keep workers and in spite of waning federal stimulus. Wages and salaries rose 0.5 percent, slowing from a 0.8 percent gain in October while personal income receipts on assets grew 0.3 percent also slowing from 0.8 percent a month earlier. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/personal-spending </td>
   <td style="text-align:left;"> 2021-12-23 21:32:00 </td>
   <td style="text-align:left;"> US Personal Spending Rises for 6th Month </td>
   <td style="text-align:left;"> Personal spending in the United States increased 0.6 percent from a month earlier in November of 2021, easing from an upwardly revised 1.4 percent rise in the previous month as holiday shopping started earlier this year in anticipation of product shortages. Still, it was the 6th consecutive gain, reflecting an increase of $97.4 billion in spending for services and a $7.4 billion increase in spending for goods. The increase in services was widespread, led by housing and utilities. Within goods, an increase in nondurable goods (mainly gasoline and other energy goods) was partly offset by a decrease in durable goods (led by recreational goods and vehicles as well as motor vehicles and parts). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/durable-goods-orders </td>
   <td style="text-align:left;"> 2021-12-23 21:32:00 </td>
   <td style="text-align:left;"> US Durable Goods Orders Beat Forecasts </td>
   <td style="text-align:left;"> New orders for US manufactured durable goods rose 2.5 percent month-over-month in November of 2021, extending gains from a revised 0.1 percent increase in October and compared to market expectations of a 1.6 percent increase. Orders of transportation equipment rebounded significantly (6.5 percent vs -0.3 percent in October), namely nondefense aircraft and parts (34.1 percent vs -4.1 percent) and defense aircraft and parts (3.0 percent vs -18.5 percent). Fabricated metal products also saw orders bounce back (0.6 percent vs -0.7 percent), while orders for computers and related products rose at a stronger pace (4.0 percent vs 1.2 percent). Excluding defense, new orders climbed 2.0 percent and excluding transportation went up 0.8 percent, the latter beating forecasts of a 0.6 percent gain. Meanwhile, orders for non-defense capital goods excluding aircraft, a closely watched proxy for business spending plans, edged down 0.1 percent, missing forecasts of a 0.6 percent increase. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/initial-jobless-claims-december-18 </td>
   <td style="text-align:left;"> 2021-12-23 21:28:00 </td>
   <td style="text-align:left;"> Jobless claims remain unchanged at 205,000, near half-century low </td>
   <td style="text-align:left;"> 'FOX Business Tonight' host explains why the labor force isn't rebounding like the president says it is.                                                                                                                                                                                                                                                                                       , The number of Americans filing for unemployment benefits last week continued to hover around a half-century low, the latest sign the labor market is bouncing back from the coronavirus pandemic.                                                                                                                                                                                              , Figures released Thursday by the Labor Department show that applications for the week ended Dec. 18 stayed at 205,000, unchanged from the previous week's level. It was in line with the 206,000 forecast by Refinitiv analysts.                                                                                                                                                               , FED'S INFLATION GAUGE HITS 39-YEAR HIGH AS PRICES SOAR HIGHER                                                                                                                                                                                                                                                                                                                                  , Continuing claims, or the number of Americans who are consecutively receiving unemployment aid, dropped to 1.859 million, a decrease of 8,000 from the previous week. That is the lowest level for insured unemployment since March 14, 2020, when it was 1.77 million.                                                                                                                        , A man walks into a restaurant displaying a "Now Hiring" sign March 4, 2021, in Salem, New Hampshire. (AP Photo/Elise Amendola / AP Newsroom)                                                                                                                                                                                                                                                   , The report shows that roughly 2.14 million Americans were collecting jobless benefits for the week ending Dec. 11, a minor decrease of 123 from the previous week; by comparison, just a little over one year ago, an estimated 21.03 million Americans were receiving benefits.                                                                                                               , "It appears we may have finally settled into a normal, pre-pandemic level," said Robert Frick, corporate economist at Navy Federal Credit Union. "The rapid rise of omicron cases may cause a temporary increase in claims, but hiring is strong and employers continue clinging to workers who are tough to hire and quick to quit."                                                          , People arrive to seek employment opportunities at a JobTrain office in Menlo Park, California, on Aug. 24, 2020,  (Associated Press)                                                                                                                                                                                                                                                           , The report underscores a strengthening labor market as the economy recovers from the pandemic and Americans continue to venture out to travel, shop and eat. Businesses have struggled to keep up with the demand, however, and have reported difficulties in onboarding new employees. Thursday's report suggests that companies are making an effort to retain the workers they already have., GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                    , There were about 11.03 million job openings in October, up from 10.6 million in September, according to the Labor Department. By comparison, there were about 7.4 million unemployed workers that month – meaning there are nearly 4 million more available jobs than there are workers.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/media/biden-administration-made-every-foolish-decision-possible-rep-michael-burgess </td>
   <td style="text-align:left;"> 2021-12-23 21:17:54 </td>
   <td style="text-align:left;"> Biden administration made every foolish decision possible: Rep. Michael Burgess </td>
   <td style="text-align:left;"> Rep. Michael Burgess, R-Texas reflects on the first year of the Biden administration and how it is impacting American families.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Rep. Michael Burgess, R-Texas, said during an interview on "Mornings with Maria" that the first year of Biden's presidency has been filled with foolish decisions.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , KUDLOW: REPUBLICANS ARE ON THE VERGE OF HISTORIC MIDTERM GAINS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , MICHAEL BURGESS: Tough year and an absolutely unforced error on almost every front. Look, the new administration came in at inauguration last January. The country was energy-independent. Inflation was at historic lows. All they had to do was not do anything foolish. And yet what happened was every foolish decision they possibly could have made. They did make, whether it was from executive orders, closing the Keystone Pipeline, upsetting things up and down the scale by continuing to pump vast amounts of federal money into a system that could barely handle the money that they already had gotten in the previous year. All of this done with no supervision, no oversight, no going back to congressional committees and say, ‘Hey, what have we already done? What could we do more?’ No, none of that happened. And it was just to push the accelerator harder, push more dollars out into the system and get those things we wanted for 50 or 60 years that we've never been able to get through Congress because they are bad ideas. And that's what everyone sort of forgot., GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , WATCH THE FULL INTERVIEW HERE:                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Rep. Michael Burgess, R-Texas, weighs in on the future of the Build Back Better bill and reflects on year one of the Biden administration. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2021/12/23/stocks-making-the-biggest-moves-premarket-novavax-tesla-jdcom-nikola-and-others.html </td>
   <td style="text-align:left;"> 2021-12-23 21:01:56 </td>
   <td style="text-align:left;"> Stocks making the biggest moves premarket: Novavax, Tesla, JD.com Nikola and others </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                                                          , Check out the companies making headlines before the bell:                                                                                                                                                                                                                                                                                                                                                                , Novavax (NVAX) – Novavax jumped 3.4% in the premarket after the drugmaker said a two-dose treatment of its Covid-19 vaccine demonstrated strong immune responses against the omicron variant. It did add that the response to omicron was lower than that against the original virus strain and that a booster dose would likely be helpful.                                                                             , Macau gaming stocks – Companies operating casinos in Macau saw their shares jump in premarket trading, following the end of a 45-day public gaming consultation. The results of that consultation apparently calmed fears about new regulations that could hurt industry profits. Las Vegas Sands (LVS) rallied 4.2%, Wynn Resorts (WYNN) added 3.4%, Melco Resorts (MLCO) jumped 5.2% and MGM Resorts (MGM) was up 1.1%., Tesla (TSLA) – Tesla CEO Elon Musk said he was "almost done" with share sales after suggesting earlier in the week that he had completed planned sales. His latest statement made reference to the completion of prearranged sales related to the exercise of stock options. Tesla rose 1% in premarket trading.                                                                                                         , JD.com (JD) – JD.com shares slumped 7.8% in premarket action, following news that China-based social media company Tencent would distribute most of its stake in the e-commerce firm to shareholders in the form of a $16.4 billion dividend.                                                                                                                                                                            , Nikola (NKLA) – Nikola added 3.9% in the premarket after saying it had completed delivery of its first electric vehicle and that more were on the way.                                                                                                                                                                                                                                                                   , Stitch Fix (SFIX) – Stitch Fix added 1.8% in the premarket after shareholder Working Capital Advisors disclosed the purchase of 3.4 million shares in the online clothing styling company, bringing its total holdings to 10.6 million shares.                                                                                                                                                                           , Mission Produce (AVO) – The provider of fresh produce to retail and wholesale customers fell 6 cents short of estimates with a quarterly profit of 24 cents per share, while revenue also fell short of forecasts. The company said supply challenges impacted its results, and the stock tumbled 9% in premarket trading.                                                                                               , Crocs (CROX) – The casual footwear company announced a deal to buy privately held rival Heydude for $2.5 billion in cash and stock. The two sides expect the transaction to close during the first quarter of 2022. Crocs fell 3.4% in the premarket.                                                                                                                                                                    , Ortho Clinical Diagnostics (OCDX) – The in vitro diagnostics company will be acquired by diagnostics technology provider Quidel (QDEL) in a $6 billion cash-and-stock deal valued at $24.68 per share. Ortho stock surged 16.1% in premarket trading while Quidel tumbled 7.2%.                                                                                                                                          , SciPlay (SCPL) – The digital game developer's stock plummeted 18.2% in the premarket after it ended talks to sell itself to majority shareholder Scientific Games (SGMS). Scientific Games shares surged 7.9%.                                                                                                                                                                                                           , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                   , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                   , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                         , © 2021 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                         , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                       , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/government-bond-yield </td>
   <td style="text-align:left;"> 2021-12-23 20:30:00 </td>
   <td style="text-align:left;"> Italian 10Y Bond Yield at 7-Week High </td>
   <td style="text-align:left;"> The yield on the Italian 10-year BTP rose to 1.1% in the third week of December, amid growing uncertainty of Italy’s political future. On December 22nd, Prime Minister Mario Draghi signalled that he would be willing to become Italy’s president when the seat becomes available in January, a move that could trigger early parliamentary elections after his 10-month administration. Meanwhile, investors fear that the country’s debt problems could re-emerge as the ECB reduces its stimulus in January. In the meantime, Draghi will meet with Italian health authorities and ministers on Thursday, as the government attempts to avoid the drastic lockdown measures taken by other European countries. Alternatives on the table include an outdoor mask mandate, shortening the validity of the vaccine certificate, and requiring vaccinated people to take covid tests to access cultural events. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2021-12-23 20:28:00 </td>
   <td style="text-align:left;"> Natural Gas Futures Ease as EU Prices Fall </td>
   <td style="text-align:left;"> US natural gas futures eased below $4.0 per million British thermal units in late December, as traders digested lower prices in Europe and forecasts of mild weather after Christmas. Media reports said the reversal of gas flows in the key Yamal-Europe pipeline were due to a drop in imports from German utilities, while higher US LNG exports to Europe are expected to bring some relief. Additionally, Refinitiv projected US gas demand, including exports, would fall by 5 bcf a day to 118.6 bcf/d next week, as temperatures warm slightly between Christmas and New Years Eve in the United States and weather forecasts see slightly milder temperatures in Europe. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/currency </td>
   <td style="text-align:left;"> 2021-12-23 20:14:43 </td>
   <td style="text-align:left;"> Sterling Strengthens to 5-Week High </td>
   <td style="text-align:left;"> The British pound break above $1.34, the highest in near five weeks as traders turned more positive about the economic outlook amid upbeat economic data and signs the Omicron variant is less severe than previously thought. The latest data showed the UK economy recovered from the pandemic faster than previously thought and the government decided not to toughen restrictions ahead of the holidays. The UK economy is now only 1.5% below its pre-pandemic level in the last quarter of 2019, compared with a previous estimate of 2.1% below, because of upward revisions to growth in 2020. Still, ONS figures showed GDP grew by 1.1% on quarter in Q3, weaker than a preliminary estimate of growth of 1.3%. Last week, the pound jumped as high as $1.337 after the Bank of England unexpectedly raised rates for the first time since the onset of the pandemic due to a spike in inflation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/mexico/unemployment-rate </td>
   <td style="text-align:left;"> 2021-12-23 20:11:00 </td>
   <td style="text-align:left;"> Mexico Unemployment Rate at Pandemic Low </td>
   <td style="text-align:left;"> The Mexican Unemployment rate decreased to 3.7 percent in November of 2021 from 4.4 percent in the corresponding month of 2020 and in line with expectations. It was the lowest jobless rate since pre-pandemic levels of March of 2020, as the number of unemployed persons declined by 252 thousand to 2.1 million, while employment increased by 3.7 million persons to 56.5 million, elevating the labor force to a rate of 59.6 percent from 56.9 percent in November of 2020. On a seasonally adjusted basis, the unemployment rate eased to 3.8 percent from 3.9 percent in October. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/government-bond-yield </td>
   <td style="text-align:left;"> 2021-12-23 20:10:00 </td>
   <td style="text-align:left;"> German 10-Year Bund Yield Rises to 4-Week High </td>
   <td style="text-align:left;"> Germany's benchmark Bund yield rose further to -0.26% in the third week of December, the highest in four weeks as risk appetite returned to markets and equity indexes recovered while investors assess how the Omicron coronavirus variant will impact the global economy. Preliminary data from Scotland, England, and South Africa pointed to lower hospitalization rates for those infected with the Omicron variant when compared to the Delta variant. Still, Germany renewed restrictions in the country amid a fourth wave, and the Netherlands entered a lockdown. On the data front, Germany’s GfK Consumer Confidence gauge for January 2022 fell more than expected to a seven-month low of -6.8. Meanwhile, ECB policymaker Peter Kazimir said inflation in the bloc could stay elevated for even longer than the ECB anticipates. Last week, the ECB announced a reduction in the pace of its asset purchases but pledged further stimulus avoiding any discussion about the possibility of future rate hikes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/government-bond-yield </td>
   <td style="text-align:left;"> 2021-12-23 19:56:00 </td>
   <td style="text-align:left;"> UK 10Y Bond Yield at 1-Month High </td>
   <td style="text-align:left;"> The yield on the UK 10-year government bond rose past 0.9%, the highest in a month, as concerns that the omicron variant would derail the economy eased after the government took a wait-and-see approach before further tightening restrictions. Additionally, investors were seen ramping up their bets that the Bank of England will hike its key interest rate to 1.25% by the end of next year, after last week it unexpectedly raised rates for the first time since the onset of the pandemic. Meanwhile, the British government reduced the self-isolation period from 10 to 7 days, provided people also showed two negative tests. Still, UK Prime Minister Boris Johnson warned that further lockdown measures may be needed as hospitalizations in London rose for the third week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2021/12/23/heres-what-some-of-the-the-biggest-crypto-ceos-and-expect-in-2022-.html </td>
   <td style="text-align:left;"> 2021-12-23 19:48:11 </td>
   <td style="text-align:left;"> What the top crypto execs predict for the industry in 2022: Regulation and a Big Tech 'brain drain' </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Cryptocurrencies have had yet another wild year.                                                                                                                                                                                                                                                                                                                                                                                                                                      , Bitcoin, the world's largest digital asset, has seen a roughly 65% gain since January — with some ten to twenty percent swings in between. It brought in a crop of new, individual investors along the way as payment giants like PayPal started letting users trade crypto. More billionaires and institutional investors dove in to help legitimize the asset class.                                                                                                                , The industry now sprawls well beyond bitcoin. NFTs, blockchain-based videogames and "Web3" are top of executives' minds heading into next year. Regulation remains as the biggest uncertainty.                                                                                                                                                                                                                                                                                        , Here's a look at what some of the industry's most influential executives had to say.                                                                                                                                                                                                                                                                                                                                                                                                  , The 29-year-old founder and CEO told CNBC he doesn't expect legislative action to be the immediate answer for "regulatory clarity." Especially since it's "pretty hard right now to get things through Congress."                                                                                                                                                                                                                                                                     , It's just as likely to be cobbled together from a series of statements, enforcement actions, and "other indications" to set the guardrails," Bankman-Fried said.                                                                                                                                                                                                                                                                                                                      , The CEO is still bullish on Solana as an alternative to Ethereum. But it's possible that a new blockchain pops up as the "Holy Grail" that would eventually be able to host a million transactions per second. Right now, he said there are "very few even trying to get that point."                                                                                                                                                                                                 , "There will be substantial fleshing out of the crypto regulatory systems over the next few years."                                                                                                                                                                                                                                                                                                                                                                                    , "Most banks have effectively decided internally that they will be entering the crypto ecosystem. But how and when they do it is going to depend a lot on the details of regulatory structure."                                                                                                                                                                                                                                                                                        , "There's enormous worry about stablecoins right now. But it's pretty straightforward to address. You have attestations, or you have an audit from a regulator."                                                                                                                                                                                                                                                                                                                       , "The thing that people are worried about with stablecoins is are they stable? If you can address that, you've addressed most of the worries about it from a customer protection and a systemic risk perspective. It's not that hard to do. So I'm cautiously optimistic that that's where we're going."                                                                                                                                                                               , The CEO of Circle is calling for more use of dollar-pegged cryptocurrencies, or stablecoins, by e-commerce firms, consumers and financial institutions. Circle, which is set to go public via SPAC, operates its own stablecoin called USDC.                                                                                                                                                                                                                                          , Allaire expects to see more institutional adoption and celebrity trendsetters lending their brands to crypto through NFTs. DAOs, which rely on crowdfunding, may even "challenge venture capital investors on some of the largest and hottest deals in crypto," he said.                                                                                                                                                                                                              , The biggest threat? "Incoherent and inconsistent, hastily formed regulations and policy," Allaire said.                                                                                                                                                                                                                                                                                                                                                                               , "Even in an environment where the Fed raises interest rates, investors and businesses will be hungry for the high-yield opportunities offered through digital assets. So expect to see institutional adoption of digital assets balloon — directly, through ETFs, or custom yield-generating products."                                                                                                                                                                               , "There is bipartisan recognition that blockchain and crypto technologies represent a U.S. competitive advantage, especially if properly regulated, so new legislation and laws will come quicker than many people expect."                                                                                                                                                                                                                                                            , "In 2022 stablecoin adoption will continue its upward trajectory. We believe that dollars on the internet will soon be as efficient and widely available as text messages and email."                                                                                                                                                                                                                                                                                                 , Brian Brooks, the former Acting Comptroller of the Currency, said there's now consensus among lawmakers in Washington that crypto is here to stay. He expects more blockbuster funding rounds after a record 2021, continued mainstream understanding of the crypto space.                                                                                                                                                                                                            , For example, not all "crypto" are currencies, or meant to act like currencies, he said.                                                                                                                                                                                                                                                                                                                                                                                               , "Retail adoption is there and will continue to accelerate, but for those established Wall Street firms and other financial services companies that are not already involved in the crypto ecosystem, it is a matter of "when" not "if".                                                                                                                                                                                                                                               , "The need for clear regulatory action that creates a sustainable framework to allow crypto and Web 3 to grow in the United States will reach its tipping point."                                                                                                                                                                                                                                                                                                                      , "The level of activity and innovation occurring in the space is too great to ignore, as is the risk to American competitiveness in technology and capital markets."                                                                                                                                                                                                                                                                                                                   , Paxos is the company powering PayPal's crypto offering behind the scenes. CEO Charles Cascarilla also expects more action in the stablecoin market. His company offers its own dollar-pegged coin, USDP. The CEO is one of many warning that the U.S. has a lot to lose if it gets regulation wrong.                                                                                                                                                                                  , "Big tech and finance players like Venmo, Interactive Brokers and Mercado Libre entered crypto in 2021. There will be even more and bigger players joining the onslaught next year."                                                                                                                                                                                                                                                                                                  , "2022 is the year of the stablecoin. Consumer wallets enabled stablecoins for the first time this year. Money is a product and it needs to be updated for how people live today. Regulated stablecoins like USDP are the answer."                                                                                                                                                                                                                                                     , "Regulatory clarity, consistency and certainty will foster Safe blockchain innovation in the US. This technology presents many opportunities for American market primacy in the long-term if we get this right, and there are many risks if we get it wrong."                                                                                                                                                                                                                         , This year marked an industry milestone of the first futures-based bitcoin ETF. But Grayscale and others in the industry are looking to take that a step further.                                                                                                                                                                                                                                                                                                                      , It's looking to convert the world's largest bitcoin trust, GBTC, into an ETF and CEO Michael Sonnenshein is optimistic for an approval in 2022. He's also seeing investor interest beyond bitcoin, and "tension" between Big Tech and start-ups.                                                                                                                                                                                                                                      ,  "We're entering into 2022 without a [spot] Bitcoin ETF, but believe that in the coming year the SEC and other regulators will continue to dig in on this issue. We remain optimistic that they will allow for an even playing field -- and give investors the optionality between both spot and futures-based ETF products for getting exposure."                                                                                                                                    , "This was certainly a year when we thought people were diversifying beyond Bitcoin and Ether. We're starting to see that investors are going to specific protocols and projects, and an increasing mindshare among investors that the universe of crypto assets is only broadening."                                                                                                                                                                                                  , "There will be an expanded conversation around the tension between some of these centralized platforms that are today managed by social media and e-commerce giants, and established tech companies versus some of these up and coming decentralized platforms."                                                                                                                                                                                                                      , Robinhood started as a stock-trading start-up. But in its second quarter as a public company, it got more than half of total revenue from crypto trades. Of that, more than 60% came from Dogecoin transactions. As the asset class becomes more important to the company's bottom line, executives have said they're moving slowly on adding new assets to the platform, until there's more regulatory clarity.                                                                      , "2021 was the year crypto went mainstream."                                                                                                                                                                                                                                                                                                                                                                                                                                           , "Whether through NFTs or their token of choice, more people engaged in crypto in what was a breakout year."                                                                                                                                                                                                                                                                                                                                                                           , "Crypto has long had a HODL mentality, and that extended to NFTs in 2021 where JPGs replaced photos all across social media. The infrastructure investment from 2017 is ready for primetime, with multiple layer L1s and L2 platforms flourishing in 2021. With more crypto enthusiasts to cater to, 2022 will see companies focus more on design and user experience to ease that transition from web 2 to web 3, and we'll continue to see major brands continuing to get involved.", If you've ever perused crypto Twitter, you probably know "Pomp." With more than 1 million followers, the investor is known for his bullish calls on bitcoin and said the asset has transitioned from a contrarian idea, to a "consensus idea on Wall Street in 2021." He expects more adoption next year from legacy companies buying bitcoin for their balance sheets, and eventually building dedicated business units.                                                             , Pompliano also highlighted moves in the bitcoin mining industry after China made the activity illegal, bitcoin's potential for global payments, and a "brain drain" underway from Big Tech and Wall Street.                                                                                                                                                                                                                                                                           , "Bitcoin mining transitioned from a largely international activity to a US-centric activity in 2021. It would not surprise me to see new all-time highs in the bitcoin hash rate in 2022, along with continued market share growth for the US as a whole, along with Texas as a single state."                                                                                                                                                                                        , "We saw a major social media platform, Twitter, embrace the Lightning Network for payments in 2021 via Strike's API (I'm an investor). We also saw a nation state, El Salvador, embrace the Lightning Network for payments. We should expect multiple large Fortune 500 companies to embrace the Lightning Network in 2022 for payments."                                                                                                                                             , "The brain drain from legacy technology and finance industry will continue. Young people, and increasingly the most skilled people, want to focus their talents on the industry where they can have the greatest impact. Crypto has been growing at an incredible rate, both in terms of new jobs, new companies, funding, economic value created, etc. This transition has only begun and will likely accelerate in 2022."                                                           , While this was a busy year for the crypto trade association in DC, "2022 is going to be way busier," Bond said. She also expects the SEC to come out with more enforcement actions.                                                                                                                                                                                                                                                                                                   , "The Biden administration has been in office for a year. We're now presented with a window where something can get done on a bipartisan basis. And that will advance the industry and it will provide guardrails for market integrity and consumer protection."                                                                                                                                                                                                                       , "While final legislation may not actually take place, take effect in 2022. I think the direction of travel is going to be clear, and what we're doing in 2022 is setting the stage for 2023, 2024 and beyond."                                                                                                                                                                                                                                                                        , "The balance is going to be one finding a policy framework in which the industry can flourish and the U.S. can benefit where consumers can also be protected."                                                                                                                                                                                                                                                                                                                        , The crypto exchange, founded by Tyler and Cameron Winklevoss, climbed to a $7 billion valuation this year and is among the dozens with a bitcoin ETF application in the works. Its COO, Noah Perlman, sees crypto payments going mainstream, more non-tech companies embracing the Metaverse, and more women jumping into a male-dominated market.                                                                                                                                    , "More retail companies with household names will expand their crypto offerings, further legitimizing digital currencies as a form of payment and as an asset. Credit card companies such as Mastercard and Visa that offer crypto rewards will become more prevalent, which will make investing in digital assets as easy as swiping your card at a store."                                                                                                                           , "It's no surprise to see tech giants Apple, Meta, Snap, Alphabet, and Microsoft build out their Metatverse ecosystem, but we expect this trend will target other industries as we've seen with Nike's acquisition of RTFKT and Adidas launching an NFT collection called "Into the Metaverse".                                                                                                                                                                                        , "The profile of the typical crypto investor will change significantly in 2022. Previously, the typical crypto investor was a man in his 30s making more than $100,000 per year. We already saw some significant demographic shifts in the past year. According to Gemini's 2021 State of the US Crypto Report, 63 percent of U.S. adults are crypto-curious, meaning they don't yet own crypto but report interest in learning more or holding digital assets soon."                  , "We'll see an approval for a spot bitcoin ETF most likely in H1."                                                                                                                                                                                                                                                                                                                                                                                                                     , Ethereum has had a break-out year but new, alternative blockchains are popping up as platforms to build NFTs and other apps. Avalanche is among the new challengers to Ethereum. The president of Ava Labs, a former hedge fund trader, predicts a shake out of "speculative" assets, and a "brain drain" as software developers leave Big Tech in search of next wave of computing. He also expects bitcoin's market dominance to keep declining.                                    , "We will continue to see inflows into smart contract platforms, DeFi, Gaming and metaverse. The winners will be the ones with strong growth of users, use cases and transaction activity. Speculative assets with no network effects will be the losers."                                                                                                                                                                                                                             , "BTC still has strong interest from both institutional and retail investors. Let's not forget that it has had a 10 year lead time compared to other platforms so it still has the biggest brand name out there. On the other hand, it's dominance over the crypto market is declining and will continue to do so."                                                                                                                                                                    , "While these smart contracts platforms do compete with each other for developers, the real competition is with traditional web 2.0 companies like Google and Facebook. We are seeing tremendous interest from web 2.0 developers who want to now build on decentralized systems because they find web 3.0 to be a lot more creative and exciting."                                                                                                                                    , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                                                , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                                                , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                                                      , © 2021 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                                                      , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                                                    , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/macau/tourist-arrivals </td>
   <td style="text-align:left;"> 2021-12-23 19:35:35 </td>
   <td style="text-align:left;"> Macau Tourist Arrivals Rebound in November </td>
   <td style="text-align:left;"> Visitor arrivals in Macau increased by 25.9 percent year-on-year to 801,300 in November of 2021, after a 43.6 percent decline in the previous month on account of hosting of tourism events such as the Grand Prix and the Food Festival. Same-day visitors grew by 64.4 percent to 513,887 while overnight visitors fell by 11.2 percent to 287,413. In terms of source of visitors, visitors from China surged by 25.9 percent to 741,226 including 195,868 of them travelling under the Individual Visit Scheme. Also, visitors rose from Hong Kong by 26.6 percent to 54,655 and those from Taiwan went up by 15.4 percent to 5297. Considering the first eleven months of 2021, visitor arrivals soared 31.5 percent year-on-year to 6.8 million. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-59760331?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2021-12-23 19:33:38 </td>
   <td style="text-align:left;"> Energy bills to soar 50% unless government intervenes, industry warns </td>
   <td style="text-align:left;"> Energy bills will soar another 50% next year unless the government intervenes, the industry has warned.                                                                                                                                                         , Supplier EDF said the situation was "critical" as customers, already seeing record bills, are hit with more rises due to surging wholesale gas prices.                                                                                                          , Emma Pinchbeck, head of trade body Energy UK, said rising prices were now starting to hurt the economy.                                                                                                                                                         , The government said it had measures to protect consumers, but she told the BBC tax cuts and green levies would help.                                                                                                                                            , Other European governments, also hit by the global rise in energy costs, were doing more, Ms Pinchbeck said.                                                                                                                                                    , "We've had record-breaking gas prices since September, and over the last couple of weeks prices have spiked again," she said. "They are at levels that, frankly, we have not seen before.                                                                       , "It's looking pretty serious for the spring. Domestic energy bills are going to go up 45-50%."                                                                                                                                                                  , Wholesale costs hit another record this week of 450p a therm, which experts predict could take average annual bills to about £2,000 next year.                                                                                                                  , Ms Pinchbeck said that across Europe, governments were asking energy-intensive commercial users to curb demand from factories in order to make savings and ease the knock-on impact.                                                                            , "We are asking our Treasury to intervene as other governments have. When it comes to bills, it's worth remembering that less than a fifth is in the control of suppliers," she said.                                                                            , Many other governments across Europe have reduced taxes and other levies, and similar action could save close to £200 a year on an average bill, she said.                                                                                                      , These countries include Spain, which has extended a series of tax cuts brought in last June until May 2022.                                                                                                                                                     , "The price is now so high that this affects the whole of the economy. So does the Treasury need to do more? They have been reluctant to intervene so far in the bits that are within their control," she said.                                                  , Philippe Commaret, a managing director at EDF, the UK's fourth-biggest supplier, said: "We urge government to act now to support energy customers. The situation is critical this winter and unfortunately, this is only the beginning.                         , "The increase in the price cap in April could be as much as £700, and by next October, the cap could easily exceed £2,000 - that is, twice as much as the levels seen last winter."                                                                             , If you think your gas and electricity bills are high now - just wait. That's the message coming from the energy industry.                                                                                                                                       , The cost of gas on the wholesale markets - where providers buy what they need - has been rocketing in recent weeks. It has more than doubled since early November.                                                                                              , A swathe of suppliers has already gone out of business as a result. Ofgem can hold back the tide for vulnerable consumers for a bit with its price cap but it is just delaying the inevitable. Even capped bills will rise dramatically next year.              , The problem is, the market simply wasn't designed to deal with this kind of situation. That's why calls for the government to step in are growing louder by the day.                                                                                            , Consumers have been shielded from the full increase in wholesale costs by the price cap, a limit on domestic rises set by the regulator Ofgem. The cap is next due to change in April.                                                                          , Many in the industry blame the cap for problems in the sector. More than two dozen energy suppliers have gone bust since the start of September, putting thousands of people out of work and leaving millions of homes in limbo as they wait for a new supplier., These failed firms include Bulb Energy, with 1.7 million customers and which because of its size was put "special administration", where it is run by Ofgem.                                                                                                    , The cap is set every six months. As gas prices have soared this year, it has forced suppliers to provide energy to households at eye-watering losses.                                                                                                           , Industry regulator Ofgem has proposed a series of short and long-term solutions to the issues that the price cap causes in extreme circumstances.                                                                                                               , These include reviewing the price cap every three months or overhauling it in favour of a six-month fixed tariff.                                                                                                                                               , A government spokesperson said: "The Energy Price Cap is insulating millions of customers from record increases in global gas prices and will remain in place, and at the same rate, this winter.                                                               , "We continue to support those most in need through our £500m Household Support Fund, the Warm Home Discount and Winter Fuel Payments."                                                                                                                          , Next year the government will publish an updated Energy Retail Market Strategy, once the market has stabilised, to ensure the market is working in the best interests of consumers, the spokesperson said.                                                      , Last week, the governor of the Bank of England warned that a recent further spike in wholesale gas prices would help drive UK inflation to about 6% early next year. The inflation rate is already at a 10-year high of 5.1%.                                   , Hayley Pearce chats terrible Christmas gifts...                                                                                                                                                                                                                 , Follow the true story of one man's struggle to find out why his home disappeared                                                                                                                                                                                , © 2021 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/government-bond-yield </td>
   <td style="text-align:left;"> 2021-12-23 19:11:24 </td>
   <td style="text-align:left;"> US 10Y Treasury Note Yield Rebounds </td>
   <td style="text-align:left;"> The yield on the benchmark 10-year Treasury note climbed to 1.48% on Thursday, the highest in eleven days, as concerns about the omicron strain calmed ahead of key economic data, namely personal spending, durable goods orders, jobless claims, among others. After a South African study showed reduced omicron hospitalizations and severe cases, researchers in Scotland and at Imperial College of London also found lower hospitalization rates among omicron infections. Also, core prices for personal consumption expenditure are expected to have increased 0.4% mom in November, when data is released later in the day. Meanwhile, the White House said it was resuming talks with Democrat Senator Manchin about the spending bill “Build Back Better Act”. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2021/12/23/politics/saudi-ballistic-missiles-china/index.html </td>
   <td style="text-align:left;"> 2021-12-23 19:00:09 </td>
   <td style="text-align:left;"> CNN Exclusive: US intel and satellite images show Saudi Arabia is now building its own ballistic missiles with help of China - CNNPolitics </td>
   <td style="text-align:left;"> Washington (CNN)US intelligence agencies have assessed that Saudi Arabia is now actively manufacturing its own ballistic missiles with the help of China, CNN has learned, a development that could have significant ripple effects across the Middle East and complicate the Biden administration's efforts to restrain the nuclear ambitions of Iran, the Saudis' top regional rival.                                                    , Saudi Arabia is known to have purchased ballistic missiles from China in the past but has never been able to build its own -- until now, according to three sources familiar with the latest intelligence. Satellite images obtained by CNN also suggest the Kingdom is currently manufacturing the weapons in at least one location.                                                                                                      , US officials at numerous agencies, including the National Security Council at the White House, have been briefed in recent months on classified intelligence revealing multiple large-scale transfers of sensitive ballistic missile technology between China and Saudi Arabia, according to two sources familiar with the latest assessments.                                                                                             , The Biden administration is now confronted with increasingly urgent questions about whether Saudi's ballistic missile advancements could dramatically change regional power dynamics and complicate efforts to expand the terms of a nuclear deal with Iran to include restraints on its own missile technology -- a goal shared by the US, Europe, Israel and Gulf countries.                                                             , Iran and Saudi Arabia are bitter enemies and it is unlikely Tehran will agree to stop making ballistic missiles if Saudi Arabia has begun manufacturing its own.                                                                                                                                                                                                                                                                           , "While significant attention has been focused on Iran's large ballistic missile program, Saudi Arabia's development and now production of ballistic missiles has not received the same level of scrutiny," Jeffrey Lewis, a weapons expert and professor at the Middlebury Institute of International Studies, told CNN.                                                                                                                   , "The domestic production of ballistic missiles by Saudi Arabia suggests that any diplomatic effort to control missile proliferation would need to involve other regional actors, like Saudi Arabia and Israel, that produce their own ballistic missiles," Lewis added.                                                                                                                                                                    , Any US response could also be complicated by diplomatic considerations with China, as the Biden administration seeks to reengage Beijing on several other high-priority policy issues, including climate, trade and the pandemic.                                                                                                                                                                                                          , "It's all a matter of calibration," a senior administration official told CNN.                                                                                                                                                                                                                                                                                                                                                             , The National Security Council and CIA declined to comment.                                                                                                                                                                                                                                                                                                                                                                                 , Asked if there have been any recent transfers of sensitive ballistic missile technology between China and Saudi Arabia, a spokesperson for China's Ministry of Foreign Affairs told CNN in a statement that the two countries are "comprehensive strategic partners" and "have maintained friendly cooperation in all fields, including in the field of military trade."                                                                   , "Such cooperation does not violate any international law and does not involve the proliferation of weapons of mass destruction," the statement said.                                                                                                                                                                                                                                                                                       , The Saudi Government and embassy in Washington did not respond to CNN's request for comment.                                                                                                                                                                                                                                                                                                                                               , New challenges for Biden                                                                                                                                                                                                                                                                                                                                                                                                                   , CNN first reported in 2019 that US intelligence agencies were aware that Saudi Arabia was collaborating with China to advance its ballistic missile program.                                                                                                                                                                                                                                                                               , The Trump administration did not initially disclose its knowledge of that classified intelligence to key members of Congress, infuriating Democrats who discovered it outside of regular US government channels and concluded it had been deliberately left out of a series of briefings where they say it should have been presented.                                                                                                     , That fueled Democratic criticism that the Trump administration was too soft on Saudi. Nuclear proliferation experts also say Trump's lack of response emboldened the Saudis to continue expanding their ballistic missile program.                                                                                                                                                                                                         , "Normally, the U.S. would have pressured Saudi Arabia not to pursue these capabilities, but the first indicators that the Saudis were pursuing these capabilities indigenously emerged during the Trump era. The Trump administration, to put it lightly, was not interested in bearing down on Riyadh over these issues," according to Ankit Panda, a nuclear policy and weapons expert at the Carnegie Endowment for International Peace., Some lawmakers have been briefed over the past few months on new intelligence about transfers of ballistic missile tech between Saudi Arabia and China, multiple sources told CNN.                                                                                                                                                                                                                                                         , The Biden administration is preparing to sanction some organizations involved in the transfers, sources told CNN, though some on Capitol Hill are concerned the White House is not willing to impose significant consequences on the Saudi government for its actions.                                                                                                                                                                     , Given the current state of negotiations with Iran, the Saudi missile program could make an already thorny problem even more difficult.                                                                                                                                                                                                                                                                                                     , "A robust Saudi missile program would introduce new challenges to constraining other missile programs in the region. To take just one example, Iran's missiles, which are a major concern to the U.S., would be more difficult to constrain in the future without parallel constraints on a growing Saudi program," Panda told CNN.                                                                                                        , 'First unambiguous evidence'                                                                                                                                                                                                                                                                                                                                                                                                               , New satellite images obtained by CNN indicate the Saudis are already manufacturing ballistic missiles at a site previously constructed with Chinese assistance, according to experts who analyzed the photos and sources who confirmed they reflect advancements that are consistent with the latest US intelligence assessments.                                                                                                          , Satellite photos taken by Planet, a commercial imaging company, between October 26 and November 9 show a burn operation occurred at a facility near Dawadmi, Saudi Arabia, according to researchers at the Middlebury Institute of International Studies, who told CNN this is "the first unambiguous evidence that the facility is operating to produce missiles."                                                                        ,                                                                                                                                                                                                                                                                                                                                                                                                                                            , "The key piece of evidence is that the facility is operating a 'burn pit' to dispose of solid-propellant leftover from the production of ballistic missiles," said Lewis, a weapons expert and professor at the Middlebury Institute of International Studies who reviewed the images.                                                                                                                                                     , "Casting rocket motors results in leftover propellant, which is an explosive hazard. Solid-propellant missile production facilities often have burn pits where leftover propellant can be disposed of by burning. Burn operations are, therefore, a strong signature that the facility is actively casting solid rocket motors," he added.                                                                                                 ,                                                                                                                                                                                                                                                                                                                                                                                                                                            , Still, little is known about the ballistic missiles that Saudi Arabia is building at this site, including important details like range and payload.                                                                                                                                                                                                                                                                                        , Considering the facility in question was built with Chinese assistance and new intelligence assessments showing Saudi Arabia has recently purchased sensitive ballistic missile technology from China, it is possible that the missiles being produced there are of Chinese design, according to Lewis.                                                                                                                                    , But there is also evidence Saudi Arabia has looked to other countries for help with developing a ballistic missile program in recent years, making it difficult to identify exactly which weapons system the Kingdom is now building at this facility, Lewis noted.                                                                                                                                                                        , CNN's Natasha Bertrand and Jeremy Herb contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2021/12/23/us/kim-potter-trial-thursday/index.html </td>
   <td style="text-align:left;"> 2021-12-23 18:34:58 </td>
   <td style="text-align:left;"> Kim Potter trial: Ex-officer found guilty of two counts of manslaughter for fatally shooting Daunte Wright  - CNN </td>
   <td style="text-align:left;"> (CNN)Kim Potter, the former Minnesota police officer who drew a gun instead of a Taser and fatally shot Daunte Wright during a traffic stop, was found guilty Thursday of first- and second-degree manslaughter in the young Black man's death.                                                                                        , Potter, who is White, displayed no emotion as the verdicts were read and was ordered held without bail. One of her lawyers rested his head on his hands at the defense table.                                                                                                                                                           , Wright's parents, Arbuey Wright and Katie Bryant, let out sighs and cries, according to a pool report.                                                                                                                                                                                                                                  , Live updates: Outcome reached in Kim Potter trial                                                                                                                                                                                                                                                                                       , "The moment we heard guilty on manslaughter one emotions, every single emotion that you can imagine just running through your body. I kind of let out a yelp because it was built up in the anticipation," Bryant told reporters later.                                                                                                 , Bryant told CNN on Thursday evening: "We still don't have Daunte home. And this is just a step forward in the bigger issue with policing and hopefully there has to be no more Dauntes. No more Dauntes and so many more names we chant in our streets."                                                                                , Demonstrators -- some carrying "Black Lives Matter" signs and portraits of Wright -- applauded and cheered outside the court. A brass band played.                                                                                                                                                                                      , Jury deliberated over four days                                                                                                                                                                                                                                                                                                         , Jurors deliberated about 27 hours since Monday, when, in closing arguments, a prosecutor described Potter's actions as a tragic blunder born of recklessness or negligence and the defense characterized the shooting as an honest mistake, not a crime.                                                                                , The maximum penalty for first-degree manslaughter predicated on reckless use/ handling of a firearm is 15 years in prison. Since Potter, 49, has no criminal history, Minnesota sentencing guidelines recommend a sentence roughly between 6 and 8.5 years in prison.                                                                   , Judge Regina Chu thanked the jury, which midway through deliberations appeared to struggle to reach a consensus.                                                                                                                                                                                                                        , "I'm so proud of you. You should be proud of yourselves. Without civic minded citizens like you our system of justice could not function. Thank you for your service. Thank you for your sacrifices."                                                                                                                                   , A female juror cried, according to the pool report. Another juror comforted her as she trembled and sobbed.                                                                                                                                                                                                                             , Minnesota Attorney General Keith Ellison told reporters that he was saddened "there will be an empty chair at the Wright family dinner during the holidays."                                                                                                                                                                            , "We have a degree of accountability for Daunte's death. Accountability is not justice," he said. "Justice is beyond the reach that we have in this life for Daunte but accountability is an important step, a critical, necessary step on the road to justice for us all."                                                              , Law enforcement officers are held in "high regard" but will also be held to "high standards," Ellison said.                                                                                                                                                                                                                             , Of Potter, he said: "She was remorseful. I mean what decent person wouldn't be brokenhearted and sad if they were involved in something like this... I wish nothing but the best for her and her family."                                                                                                                               , Chu denied a request by Potter's defense lawyers to allow her to go home before sentencing, citing her deep roots in the community.                                                                                                                                                                                                     , "I cannot treat this case any differently than any other case," Chu said.                                                                                                                                                                                                                                                               , The former Brooklyn Center police officer was handcuffed and escorted out of the courtroom. Her husband, Jeff, a former law enforcement officer, was heard yelling, "I love you, Kim," according to a pool report.                                                                                                                      , "I love you back," she said.                                                                                                                                                                                                                                                                                                            , She was transferred to Minnesota Correctional Facility -- Shakopee, about 25 miles southwest of Minneapolis, according to the state Department of Corrections. Sentencing was set for February 18.                                                                                                                                      , Potter yelled 'Taser' before shooting Wright                                                                                                                                                                                                                                                                                            , Wright's shooting on April 11 -- during the trial in which former officer Derek Chauvin was convicted of murdering George Floyd -- led to days of unrest in suburban Brooklyn Center after a tumultuous year of coast-to-coast protests over how police treat people of color. Chauvin was found guilty in the same courtroom as Potter., Wright, 20, was pulled over by police for an expired tag and an illegal air freshener. During the stop, officers learned he had an outstanding warrant and attempted to arrest him, but Wright pulled away and tried to drive off.                                                                                                      , As video of the incident shows, Potter yelled "Taser" repeatedly before she shot Wright with her handgun. She then said, "Holy sh*t! I just shot him!" She added: "I grabbed the wrong f**king gun, and I shot him." She resigned from the department days later.                                                                       , The case centered on the jury's interpretation of Potter's fatal error -- whether it was, as the prosecution argued, due to her recklessness and negligence, or whether it was an unfortunate accident that does not rise to the level of a crime, as the defense has argued.                                                           , More than 30 witnesses, including Potter herself, took the stand during the trial's eight days of testimony. An emotional Potter testified for hours and broke down in tears several times as she described the "chaotic" moments that led up to the shooting.                                                                          , "I was very distraught. I just shot somebody. I'm sorry it happened," she said, crying, in court. "I'm so sorry."                                                                                                                                                                                                                       , Under cross-examination, Potter said Wright had not threatened the officers before she fired. She said she did not remember much of what happened after the shooting but acknowledged she did not help treat Wright's injuries or check on her fellow officers.                                                                         , Potter was far from a rogue officer. She testified that before that day she had never deployed her Taser or fired a handgun while on duty, and she had never had a complaint against her.                                                                                                                                               , The former officer described the moments before the shooting as "chaotic" and recalled the "look of fear" of another officer as he struggled with Wright.                                                                                                                                                                               , "I didn't want to hurt anybody," she cried at one point.                                                                                                                                                                                                                                                                                , Wright's mom and dad testified                                                                                                                                                                                                                                                                                                          , In her closing argument, Assistant Minnesota Attorney General Erin Eldridge said Potter made a series of bad choices during the traffic stop that led to the fatal mix-up.                                                                                                                                                              , "Accidents can still be crimes if they occur because of recklessness or culpable negligence," the prosecutor said. "It's not a defense to the crimes charged."                                                                                                                                                                          , Wright's mother and father testified for the prosecution.                                                                                                                                                                                                                                                                               , University of South Carolina School of Law associate professor Seth Stoughton testified for the state, calling Potter's actions "excessive and inappropriate."                                                                                                                                                                          , "The use of deadly force was not appropriate, and the evidence suggests that a reasonable officer in Officer Potter's position could not have believed it was proportional to the threat at the time," Stoughton said.                                                                                                                  , The defense characterized the killing as an unfortunate accident that should not be considered a crime.                                                                                                                                                                                                                                 , "Everybody makes mistakes, nobody's perfect," said attorney Earl Gray. "This lady made a mistake and a mistake is not a crime."                                                                                                                                                                                                         , He also argued Potter was within her rights to use deadly force to protect a fellow officer, who was reaching into the vehicle when Wright attempted to drive away.                                                                                                                                                                     , "Even though she didn't know she was using it, she had the right to, and that's what the law is," he said.                                                                                                                                                                                                                              , A Taser would have been effective in incapacitating Wright, the first defense witness testified. Still, deadly force was warranted if an officer is partly inside a vehicle as a suspect is attempting to drive away, said Stephen Ijames, a law enforcement expert and former assistant police chief from Missouri.                    , Potter's former boss testified he concluded there was "no violation ... of policy, procedure, law," after reviewing body camera and other video following the shooting.                                                                                                                                                                 , The jury reached its verdict on the first-degree manslaughter count at 11:40 a.m. (12:40 p.m. ET) Thursday, according to Chu. Jurors agreed on the lesser charge Tuesday at 10:30 a.m., she said. The conviction of a police officer is rare.                                                                                           , Correction: An earlier version of this story misstated the day the verdict on the lesser charge was reached. Jurors agreed on it Tuesday.                                                                                                                                                                                               , CNN's Omar Jimenez, Josh Campbell, Jason Hanna, Eric Levenson, Ashley Killough, Carma Hassan, Brad Parks and Anna-Maja Rappard contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 18:30:00 </td>
   <td style="text-align:left;"> BSE Sensex Extends Gains for Third Consecutive Session </td>
   <td style="text-align:left;"> The BSE Sensex ended 384.72 points or 0.68% higher to close at 57,315.28 on Thursday, gaining for the third consecutive session and tracking the upbeat mood in the global market. Investor's sentiment was boosted amid easing concerns over Omicron, after studies revealed that Omicron, although more infectious, has reduced risk of hospitalization and severe disease when compared to the Delta variant. Gains were led by banks, financials and technology. Among the individual stocks, Power Grid Corporation (+3.4%), Indian Tobacco Company( +2.48%), Bajaj Finance(+2.12%) and Infosys (+1.77%) were among the top gainers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/taiwan/retail-sales-annual </td>
   <td style="text-align:left;"> 2021-12-23 18:24:51 </td>
   <td style="text-align:left;"> Taiwan Retail Sales Rise for 3rd Straight Month </td>
   <td style="text-align:left;"> Retail sales in Taiwan rose 6.33 percent year-on-year in November of 2021, following a 6.65 percent increase in the previous month, pointing to the third consecutive monthly growth in retail activity. The most relevant contributions came from sales in general merchandise stores (7.31 percent vs 5.44 percent in October); retail trade not in stores or stalls (16.71 percent vs 19.02 percent); in e-commerce &amp; mail-order houses (20.73 percent vs 23.53 percent) Sales also rose for textiles &amp; clothing (12.65 percent vs 6.84 percent); in information and communications equipment &amp; electrical household appliances (18.99 percent vs 40.06 percent); food, beverages, and tobacco (6.91 percent vs 1.17 percent); and fuel &amp; related products (30.47 percent vs 31.91 percent). On a monthly basis, retail sales edged up 0.65 percent, slowing sharply from a 13.83 percent jump in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 18:23:34 </td>
   <td style="text-align:left;"> Italian Stocks Trade Higher on Thursday </td>
   <td style="text-align:left;"> The FTSE MIB extended yesterday’s gains by 0.2% to hover around 26,880 on Thursday, in line with its European peers, amid eased pandemic fears. Preliminary data from Scotland, England, and South Africa pointed to lower hospitalization rates for those infected with the Omicron variant when compared to the Delta variant. In the meantime, investors turn to Prime Minister Draghi’s speech this afternoon after his meeting with health authorities and ministers, in which the extent of restriction measures for the holiday season will be announced. On the corporate front, industrial stocks led the gains, driven by Cnh Industrial (1%) and Leonardo (0.9%). At the same time, Telecom Italia fell 0.6%, as main shareholders, including treasury owned CDP, discuss a revamp for the group after its third profit warning in 2021. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/egypt/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 18:16:20 </td>
   <td style="text-align:left;"> Egypt EGX 30 Hits 21-month High </td>
   <td style="text-align:left;"> EGX 30 increased to a 21-month high of 11766 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/taiwan/industrial-production </td>
   <td style="text-align:left;"> 2021-12-23 18:06:46 </td>
   <td style="text-align:left;"> Taiwan Industrial Output Growth at 3-Month High </td>
   <td style="text-align:left;"> Industrial output in Taiwan hiked 12.19 percent year-on-year in November of 2021, faster than an upwardly revised 11.60 percent rise in the previous month, snapping fourth straight months of faltering growth. It was also the fastest growth rate of industrial production since August, mainly driven by the manufacturing sector (13.13 percent vs 11.92 percent in October), while mining &amp; quarrying declined less (-1.25 percent vs -2.79 percent). On the other hand, output rose at a softer pace in utilities (2.56 percent vs 9.60 percent) and fell more sharply in water supply (-5.24 percent vs -3.58 percent). On a seasonally adjusted monthly basis, industrial production went up by 0.21 percent compared to an upwardly revised 0.51 percent gain in October. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 17:57:00 </td>
   <td style="text-align:left;"> French Stocks Extend Gains </td>
   <td style="text-align:left;"> The CAC 40 Index extended gains by 0.2% to hover around the 7,060 level of Thursday, tracking Asian and American markets as pandemic concerns slightly waned. A study from South Africa indicated those infected with the Omicron variant showed a lower likelihood of hospitalization and death when compared to the Delta variant. On the corporate front, Airbus gained 0.8% following a EUR 10 billion contract with the French Ministry of the Armed Forces for the supply of 169 helicopters. At the same time, Engie gained 0.3% from the EUR 1.1 billion sale of its 11.5% stake at gas transmission network operator GRTgaz. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/poland/unemployment-rate </td>
   <td style="text-align:left;"> 2021-12-23 17:55:31 </td>
   <td style="text-align:left;"> Polish Jobless Rate Falls Further to 20-Month Low </td>
   <td style="text-align:left;"> Poland’s unemployment rate edged down to 5.4 percent in November of 2021 from 5.5 percent in the previous month and in line with market expectations. It was the lowest jobless rate since March 2020, as the number of unemployed fell by 12 thousand to 899 thousand. A year earlier, the jobless rate was higher at 6.1 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/government-bond-yield </td>
   <td style="text-align:left;"> 2021-12-23 17:53:23 </td>
   <td style="text-align:left;"> France 10Y Bond Yield Hits 4-week High </td>
   <td style="text-align:left;"> France 10 Year Government Bond Yeld increased to a 4-week high of 0.101% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/slovenia/consumer-confidence </td>
   <td style="text-align:left;"> 2021-12-23 17:51:51 </td>
   <td style="text-align:left;"> Slovenia Consumer Confidence Improves in December </td>
   <td style="text-align:left;"> The consumer confidence in Slovenia increased to -24 in December of 2021 from -27 in November. Expectation over the next 12 months improved for the general economic situation in the country (-34 vs -41); savings (-9 vs -13); financial situation of the household (-17 vs -19); major purchases (-31 vs -32); and unemployment (22 vs 23). Last year, during the pandemic, the indicator was at a lower -29. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/business-confidence </td>
   <td style="text-align:left;"> 2021-12-23 17:44:56 </td>
   <td style="text-align:left;"> Italy Business Confidence Below Expectations </td>
   <td style="text-align:left;"> Manufacturing confidence in Italy was at 115.2 in December of 2021, easing from a downwardly revised 115.9 in the previous month and below market expectations of 115.3. Respondents’ assessment of manufacturing declined for expectations of future production (18.6 vs 19.6 in November), while improvements took place for order books (10.5 vs 10). At the same time, assessment of inventory levels rebounded (0.5 vs -0.9). The composite business index, combining surveys of manufacturing, retail, construction, and services, edged down to 113.1 from 114.8 in the prior month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/aluminum </td>
   <td style="text-align:left;"> 2021-12-23 17:36:17 </td>
   <td style="text-align:left;"> Aluminum Jumps to 8-Week High on Supply Worries </td>
   <td style="text-align:left;"> Aluminum futures jumped above $2,800 per tonne, the highest in near eight weeks boosted by worries over tight supplies. Non-ferrous production such as aluminum in Europe is again under pressure as electricity prices roared back to record levels. Also, latest data showed China's output of alumina, which is smelted to make aluminum, fell in November by 4.5% year-on-year to its lowest in 18 months as regions impose curbs on the aluminum raw material. Still, the price of aluminum remains about 10% below its 13-year high of $3,172 reached in mid-October, as supply disruptions connected to higher energy prices in China eased and aluminum ingot inventories have been falling at a slower pace as cargoes pile up at railway stations in Xinjiang and the major Chinese manufacturing province of Zhejiang is fighting a Covid-19 outbreak. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/uk-natural-gas </td>
   <td style="text-align:left;"> 2021-12-23 17:34:00 </td>
   <td style="text-align:left;"> UK Natural Gas Slips from Record High </td>
   <td style="text-align:left;"> UK natural gas prices fell below 400 pence a therm on Thursday, sliding roughly 13% from a record 451.72 pence hit two sessions ago, as it tracked the Dutch contract lower amid reports that Gazprom’s customers in Europe had requested less gas and more US LNG tankers were crossing the Atlantic towards the continent. Two German natural gas importers assured Gazprom was meeting its contractual obligations, while Bloomberg reported that contracted supply limits for this year had already been reached. Earlier this week, prices had rallied to all-time highs bolstered by a combination of freezing temperatures and lower power output from alternative sources, which added to previous concerns about delays in the Nord Stream 2 pipeline approval and rising tensions in eastern Europe. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/consumer-confidence </td>
   <td style="text-align:left;"> 2021-12-23 17:23:54 </td>
   <td style="text-align:left;"> Italy Consumer Confidence Higher than Expected </td>
   <td style="text-align:left;"> Consumer confidence in Italy edged higher to 117.7 in December of 2021 from 117.5 in the previous month and above market forecasts of 116.2, buoyed by more than EUR 7 billion of tax cuts set out on the government’s budget. Improvements were seen for the current (115.6 vs 115.2 in November), and personal (110.4 vs 110) subindices. On the other hand, sentiment deteriorated for the economic (139.6 vs 139.8) subindex, while consumers are less optimistic about the future (120.8 vs 121). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/austria/current-account </td>
   <td style="text-align:left;"> 2021-12-23 17:17:33 </td>
   <td style="text-align:left;"> Austria Current Account Surplus Narrows in Q3 </td>
   <td style="text-align:left;"> The current account surplus in Austria narrowed to EUR 0.95 billion in the third quarter of 2021 from EUR 2.29 billion a year earlier. The goods account swung to a deficit of EUR 0.08 billion compared to a surplus of EUR 0.94 billion a year ago, while the services surplus shrank to EUR 1.33 billion from EUR 2.20 billion. Meanwhile, the primary income gap narrowed to EUR 0.34 billion from EUR 0.42 billion and the secondary income account switched to a surplus of EUR 0.04 billion compared to a deficit of EUR 0.42 billion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/car-production </td>
   <td style="text-align:left;"> 2021-12-23 17:11:32 </td>
   <td style="text-align:left;"> UK Car Production Posts Weakest November Since 1984 </td>
   <td style="text-align:left;"> Car production in the UK fell 28.7% year-on-year to 75,756 units in November of 2021, the fifth consecutive month of decline and the worst November performance since 1984 as UK car makers continue to wrestle with the worldwide shortage of semiconductors. Production for both domestic and overseas markets declined, down -18.8% and -30.4% respectively, as 30,487 fewer cars rolled off factory lines. Exports accounted for more than 80% of all cars produced, reinforcing the need for smooth international trade, especially with the EU, as new customs controls with the bloc come into effect on 1 January 2022. Continuing the recent trend, British production of battery electric, plug-in hybrid and hybrid cars took a record share of production, accounting for around a third (32.7%) of all cars made in the month, and more than a quarter (25.5%) over the year-to-date. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/eu-natural-gas </td>
   <td style="text-align:left;"> 2021-12-23 17:07:00 </td>
   <td style="text-align:left;"> EU Natural Gas Falls Over 13% from Record High </td>
   <td style="text-align:left;"> EU natural gas prices retreated for a second session to €156 per megawatt-hour on Thursday, erasing more than 13% since reaching a record high of €180.27 on Tuesday, amid reports that higher volumes of LNG are being shipped from the US to Europe and demand is slowing down. Out of 76 American LNG tankers in transit, 10 declared destinations in Europe, and another 20 were headed to the region, as the continent surpassed Asia as the top destination for US LNG exports this month. Meanwhile, media reports said the reversal in flows through the key Yamal-Europe pipeline was due to clients requesting less fuel, as contracted supply limits had been hit. Earlier this week, prices had rallied to all-time highs bolstered by a combination of freezing temperatures and lower power output from alternative sources, which added to previous concerns about delays in the Nord Stream 2 pipeline approval and rising tensions in eastern Europe. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/30-year-bond-yield </td>
   <td style="text-align:left;"> 2021-12-23 17:05:14 </td>
   <td style="text-align:left;"> Japan 30Y Bond Yield Hits 8-week High </td>
   <td style="text-align:left;"> Japan 30 Year Government Bond Yeld increased to a 8-week high of 0.69% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/china/currency </td>
   <td style="text-align:left;"> 2021-12-23 16:55:50 </td>
   <td style="text-align:left;"> Chinese Yuan Moves Slightly Higher </td>
   <td style="text-align:left;"> The offshore yuan traded below 6.38 per US dollar on Thursday, moving marginally higher as trading activity moderated ahead of the year-end holidays. Meanwhile, market participants shifted their focus to whether the currency could sustain its recent strength next year, with traders dialing back long positions in the past two weeks amid concerns that authorities may rein in the currency’s recent gains. The People’s Bank of China’s official midpoint has been persistently softer than market expectations since mid-November. The central bank has also been increasing its foreign currency buying from banks, and hiked the foreign exchange reserve requirement ratio by 200 basis points to 9% effective Dec.15. Moreover, a former senior official in China’s foreign exchange regulator warned of yuan weakness in 2022 if economic data continues to disappoint. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/brent-crude-oil </td>
   <td style="text-align:left;"> 2021-12-23 16:49:00 </td>
   <td style="text-align:left;"> Oil Holds Gains </td>
   <td style="text-align:left;"> Brent crude futures traded above $75 per barrel on Thursday, extending gains for the third session after a bigger than expected draw in US inventories offset worries about the short-term demand outlook as more restrictions are being placed. More than 13 million people in the Chinese city of Xi'an have been ordered to stay at home as authorities attempt to tackle a Covid outbreak there. Still, recent studies suggested the omicron variant of Covid appears to be milder than previous strains. Meanwhile, EIA data showed US inventories fell by 4.72 million barrels, its fourth straight weekly draw and well above market estimates for a 2.75-million-barrel decline. Elsewhere, Natural gas prices in Europe surged to record highs as flows from a key Russian pipeline stopped, forcing some countries to boost electricity imports and burn oil to meet demand. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/currency </td>
   <td style="text-align:left;"> 2021-12-23 16:48:05 </td>
   <td style="text-align:left;"> Japanese Yen Weakens Despite Kuroda Remarks </td>
   <td style="text-align:left;"> The Japanese yen remained weak above 114 per US dollar on Thursday despite remarks from Bank of Japan governor Haruhiko Kuroda, who warned that a weak yen may be hurting households more than in the past, citing the country’s increasing reliance on more expensive raw material imports which push the cost of living up. However, he reiterated that overall, the benefits of a weak yen outweigh the drawbacks, including stronger exports and higher profits that companies earn overseas. Mr. Kuroda also recently commented that it was too early to consider normalizing monetary policy, bolstering the view that the Japanese central bank would lag behind other central banks in scaling back monetary stimulus. Moreover, prime minister Fumio Kishida said on Thursday he hoped the BOJ continues to make efforts to achieve its 2% inflation target, expressing desire for supportive monetary and fiscal policies. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/government-bond-yield </td>
   <td style="text-align:left;"> 2021-12-23 16:46:37 </td>
   <td style="text-align:left;"> UK 10Y Bond Yield Hits 4-week High </td>
   <td style="text-align:left;"> UK 10 Year Government Bond Yeld increased to a 4-week high of 0.925% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/stock-market </td>
   <td style="text-align:left;"> 2021-12-23 16:36:00 </td>
   <td style="text-align:left;"> Asian Shares Advance </td>
   <td style="text-align:left;"> Major bourses in Asia rose on Thursday following an upbeat mood on Wall Street, amid signs the omicron variant is less severe than previous strains, albeit more infectious. Shares in Japan led the rise, up for the 3rd straight session, with technology stocks extending gains from the prior session. In Hong Kong, shares of Chinese e-commerce titan JD.com plunged while Tencent surged after Tencent announced it will distribute the majority of its shares in e-commerce titan to its shareholders. The Shanghai Composite also rose, on reports that China Evergrande will engage with its creditors after its recent missed debt repayments. Still, more than 13 million people in the Chinese city of Xi'an have been ordered to stay at home as authorities attempt to tackle a Covid outbreak there. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/stocks-jobless-claims-durable-goods-fed-merck-omicron </td>
   <td style="text-align:left;"> 2021-12-23 16:27:26 </td>
   <td style="text-align:left;"> S&amp;P 500 hits record close, Dow, Nasdaq finish higher after durable goods rise, jobless claims steady </td>
   <td style="text-align:left;"> Commerce Street Holdings CEO Dory Wiley makes his top picks to beat the rate hikes.                                                                                                                                                                                                                                              , Despite more signs of persistent inflation. U.S. stocks finished strong following encouraging reports on durable goods and jobless claims and fading omicron fears.                                                                                                                                                              , The Dow Jones Industrial Average climbed 196.67 points, or 0.5%, while the S&amp;P 500 rose 0.6% to a record close and the Nasdaq Composite jumped 0.8%. U.S. markets are up more than 1.6% for the week.                                                                                                                            , The bond market had a shortened trading session, closing at 2 p.m. ET.                                                                                                                                                                                                                                                           , US ECONOMIC GROWTH REVISED UP TO 2.3% IN THIRD QUARTER, BUT STILL LAGGED PREVIOUS MONTHS                                                                                                                                                                                                                                         , Oil climbed 1.4% during Thursday's trading session, trading at the $73 per barrel level. Earlier in the day, ExxonMobil battled a refinery fire in its Baytown Texas plant.                                                                                                                                                      , In economic data: Durable Goods, sales of big-ticket items, rebounded by 2.5% after rising just 0.1% in the prior month. The data backs up the latest Consumer Confidence Index which showed an uptick in spending plans over the next six months.                                                                               , Personal income and spending also rose with spending up 0.6% and income up 0.4%.                                                                                                                                                                                                                                                 , On inflation, core personal consumption expenditures, which remove volatile food and energy prices, are also anticipated to jump 0.5% month-over-month in November. The year-over-year change in core PCE, which is the Federal Reserve’s preferred measure of inflation, rose 4.7%, the highest reading in almost 33 years.     , Jobless claims held steady at 205,000, little changed from the previous week’s total of 206,000. Continuing claims, which track the total number of unemployed workers collecting benefits, hit 1.859 million, still hovering near a pandemic low.                                                                               , COVID-19 PILL: WHAT TO KNOW                                                                                                                                                                                                                                                                                                      , In stocks, Merck shares finished lower despite receiving approval from the Food and Drug Administration on its COVID-19 pill. The approval came after Pfizer's pill was cleared Wednesday. Additionally, Novavax fell over 3% despite news that its COVID regimen "demonstrated cross-reactive immune responses against Omicron.", Electric vehicle maker shares were also in focus on Thursday, with truck maker Nikola surging more than 17% following its first customer order delivery and shares of Tesla moving 5% higher as CEO Elon Musk continues to exercise his stock options.                                                                           , The 10-year treasury yield rose to 1.492% at the end of Thursday's trading session, its highest level since Dec. 8, after briefly topping 1.5% for the first time since Dec. 13.                                                                                                                                                 , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                      , Investors continue to eye Apple. Hitting its $3 trillion market cap milestone appears likely to be pushed to 2022. Microsoft is the only other company that is a close second to this status.                                                                                                                                    , There will be no trading in equities or U.S. Treasuries on Christmas Eve on Friday. Many world markets will be closed Friday in observance of Christmas.                                                                                                                                                                         , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                          ,  Ken Martin and The Associated Press contributed to this report. </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2021-12-24 09:48:43 UTC +8

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
   <td style="text-align:left;"> 2021-12-24 09:47:50 </td>
   <td style="text-align:left;"> Get back up every time you fall only this time you grow stronger/wiser $SPY $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:45:45 </td>
   <td style="text-align:left;"> $SPY what’s with that giant drop right before close 🎅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:45:34 </td>
   <td style="text-align:left;"> $SPY driving by Covid stations. Fear is real

Now idk what that means for stocks 

But actual business will take a small hit the next couple of months </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:44:35 </td>
   <td style="text-align:left;"> $SPY so the people who are most likely to get Covid and spread it to vulnerable people have a shorter isolation time than everyone else 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:44:17 </td>
   <td style="text-align:left;"> I was wasting my life until I understood the true meaning of compounding $SPY $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:43:32 </td>
   <td style="text-align:left;"> $SPY Happy Christmas 🎄 people!!! Sunday should be interesting,  lots of $$$$$ bets over weekend , 🍻 🥂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:42:28 </td>
   <td style="text-align:left;"> $SPY Know your worth understand what your bring to the table cut off people that don’t give you the same actions as you give them talk is cheap actions is everything have some decency and self respect for your self kings and queens </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:41:52 </td>
   <td style="text-align:left;"> $SPY Biden wants the unvax&amp;#39;d to die off, those are mostly votes for Trump 🤣😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:40:59 </td>
   <td style="text-align:left;"> $SPY hahhahahaha only 30% boosted, with all time highs in the market , America has it all figured out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:40:08 </td>
   <td style="text-align:left;"> $SPY I need to find alternative markets to invest in. Of course I’m keeping VOO. 

But there is 10x upside in shit that nobody is looking

How to find is the big $$$ question </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:39:52 </td>
   <td style="text-align:left;"> $SPY 475 next week? Market doesn’t like this area for some reason, but last week of the year could see major pump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:38:23 </td>
   <td style="text-align:left;"> $SPY   Biden to airlines = please don’t announce covid flight canx until after market close - Thanks 😘 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:36:42 </td>
   <td style="text-align:left;"> $SPY Wow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:36:30 </td>
   <td style="text-align:left;"> CCP $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:36:12 </td>
   <td style="text-align:left;"> $SPY hahahahaha hohohohohohoe 😆 🤣 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:35:13 </td>
   <td style="text-align:left;"> $SPY I think that Debbie Gibson wrote all of her songs about me. 

https://music.apple.com/us/album/lost-in-your-eyes/299793303?i=299793313 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:34:27 </td>
   <td style="text-align:left;"> $SPY I once went darker than @TheDarkerStranger... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:34:15 </td>
   <td style="text-align:left;"> $SPY replying in a post is a risk in itself. Fuck me. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:34:11 </td>
   <td style="text-align:left;"> $SPY In real life  @ShortyMcFly Is a chubby chaser </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:32:20 </td>
   <td style="text-align:left;"> $SPY coming soon, the Putin Portfolio Tracker Twitter profile 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:32:10 </td>
   <td style="text-align:left;"> $SPY anyone know what the largest single day drop was this year? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:31:07 </td>
   <td style="text-align:left;"> $SPY 465 Monday 458 Thursday? 🥴👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:30:01 </td>
   <td style="text-align:left;"> $SPY since I found options I now have a 25k account, I started with 200k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:26:51 </td>
   <td style="text-align:left;"> $DWAC Hot close AH 
$spy $phun </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:26:06 </td>
   <td style="text-align:left;"> $SPY if you live in the metaverse do you still need to eat etc. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:25:53 </td>
   <td style="text-align:left;"> MY FIRST DRINK DEDICATING TO ALL THE $TSLA $SPY BULLS TODAY YOU GUYS ARE FREAKING AMAZING! BLESSED TO SAY THE LEAST🎄🎄🎄🎅🏼🎅🏼🎅🏼🎅🏼 MERRY CHRISTMAS AND HAPPY HOLIDAYS❤️❤️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:25:52 </td>
   <td style="text-align:left;"> $SPY my Christmas playlist is &amp;gt; than yours... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:24:48 </td>
   <td style="text-align:left;"> $SPY Here comes the discord guys 

“GREAT WEEK GUYS YA MADE SOME GOOD CALLS IT WAS TOUGH OUT THERE” 

🎅🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:23:44 </td>
   <td style="text-align:left;"> $QQQ $spy next week 10-15 percent correction starts, new year deep red, omicron wave is going to explode soon, market will react heavily, worse than after thanksgiving </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:22:40 </td>
   <td style="text-align:left;"> $SPY I made the mistake of going Christmas shopping in Compton tonight. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:22:27 </td>
   <td style="text-align:left;"> $SPY $GREE $PRPL $PTON $JAGX what a great week thanks to these new winners.  one more week to close out a great Dec and fantastic 2021.  🚀s every where, every day, every week.   Merry Christmas all.  See you Monday, Let&amp;#39;s finish strong! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:21:58 </td>
   <td style="text-align:left;"> $SPY hate to say that, but this betch looks bullish again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:20:35 </td>
   <td style="text-align:left;"> $SPY Merry Christmas Eve Eve.  Eve Eve is the day before Eve.  Bulls are preparing for Prime Rib and Mashed Potato Christmas dinner.  Bears are preparing for $MCD chicken nuggets and fries Christmas dinner.  Bears will be taking an $UBER to McDonalds because the car was sold to pay for margin calls this year.  

All kidding aside, bears are probably right about the economy.  They are just early. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:19:24 </td>
   <td style="text-align:left;"> $TSLA $AAPL $SPY $BJDX 
Next week also 🎄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:17:34 </td>
   <td style="text-align:left;"> $SPY I trade this baby both ways but some of the bulls are very greedy and cocky when the fed is spoon feeding gains this year for no reason 

Small pull backs or dips are okay lol 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:17:23 </td>
   <td style="text-align:left;"> $SPY Course they can&amp;#39;t send out National Guard after Christmas the 26th. Nope we must clean hospitals ON christmas. No need to see my brother on Christmas. Omicron is so much more fucking important for sniffles and sneezes 😑. Get a grip you whiny, scared little sheep. Tired of inflation, tired of holidays being ruined, governments taking charge by abuse of power, rights going down the shitter, morons willingly paying pharma to make them guinea pigs. Never ends. Why dont we make camps for those who want to live like caged animals and the rest can get on with their damn lives. For fucks sake people, you have millions of sicknesses around the globe happening daily that cause 3x the amount of deaths daily. Want to see a magic trick! Turn of the news and watch covid disappear! 🖕 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:13:30 </td>
   <td style="text-align:left;"> $SMURF $BTC.X $DGB.X $SPY $META 
Check out SMURF / COIN.NE - it’s the best metaverse play and Canadian markets are opened tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:13:13 </td>
   <td style="text-align:left;"> $SPY “Normally, the equity markets close at 1 p.m. on Christmas Eve.

The bond market will close early at 2 p.m. Thursday and stay shuttered Friday.

On New Year’s Eve, stock markets will be open while the bond market closes at 2 p.m.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:13:05 </td>
   <td style="text-align:left;"> $SPY please no war, no new variants, no terrorists attacks… I want to see 500 next week… before anyone laughs, zoom out and look at this past week… it’s actually possible maybe not probable but a man can hope 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:12:52 </td>
   <td style="text-align:left;"> $TSLA $SPY where is @ShortyMcFly and his hot posts 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:11:19 </td>
   <td style="text-align:left;"> $SPY If buying calls is so easy why don’t bears do it? Oh it’s because they are ALWAYS afraid of a random black swan lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:11:12 </td>
   <td style="text-align:left;"> $SPY Dark Pool + GEX update </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:10:43 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:10:28 </td>
   <td style="text-align:left;"> $SPY $QQQ $MSFT Will this repeat thanksgiving? green before holiday and then everyone come back for a dump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:09:14 </td>
   <td style="text-align:left;"> $SPY 

Bears and their FUD smh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:07:38 </td>
   <td style="text-align:left;"> $KPRX American bio company, 11 mil market cap, the lowests market cap bio company that I know off not on otc. Has 3 products one in phase 3 and another in phase 2. 2 catalysts coming for quarter 1 according to their recent quarterly report. Cash on hand, No S3 so no risk of offering atm I believe. Crazy . Brand new CEO this month as well. 
KPRX 
Watching $IWM $SPY $QLGN $NXTD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:07:11 </td>
   <td style="text-align:left;"> $SPY https://www.theonion.com/star-high-school-quarterback-blissfully-unaware-he-ll-b-1848235458 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:06:56 </td>
   <td style="text-align:left;"> $SPY dam why does casino have to close tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:06:42 </td>
   <td style="text-align:left;"> $SPY Monday will see 464 or 465 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:06:25 </td>
   <td style="text-align:left;"> $SPY lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:05:28 </td>
   <td style="text-align:left;"> $SPY Oh Suzie Q 😔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:04:43 </td>
   <td style="text-align:left;"> $SPY sorry if you bought puts 😔😂 The bulls took over man. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:04:29 </td>
   <td style="text-align:left;"> $SPY marker frozen or what? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:03:21 </td>
   <td style="text-align:left;"> $SPY A wonderfully accessorized fat girl is still fat… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:02:36 </td>
   <td style="text-align:left;"> $JD the chinee $KWEB $SPY 

👍  😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 09:02:31 </td>
   <td style="text-align:left;"> $SPY 
I’m just relieved they didn’t misgender her </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:59:44 </td>
   <td style="text-align:left;"> $SPY markets open on Christmas? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:59:37 </td>
   <td style="text-align:left;"> $SPY next week 485 have a beautiful Christmas </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:59:17 </td>
   <td style="text-align:left;"> $DWAC $SPY Say NO to the NWO 💉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:58:57 </td>
   <td style="text-align:left;"> $SPY hope the bears have a good Christmas. Shorting the market before Christmas as if they would tank it 🤣🤣🤣🤣🤣🤣🤣🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:58:19 </td>
   <td style="text-align:left;"> $SPY You only sound cocky to people who gave up on their goals but to people that are working on their goals daily you sound confident pick your circle wisely </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:57:58 </td>
   <td style="text-align:left;"> $SPY lmao markets a joke 0.00001 bearish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:57:52 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Daily market recap 12/23/2021

https://youtu.be/nNkzm93Kvqc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:57:42 </td>
   <td style="text-align:left;"> $SPY 

Which color do you want this Xmas?

I want a White Xmas, and a angel white rally.

Black Xmas would be shit (get it). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:56:43 </td>
   <td style="text-align:left;"> $SPY if I had 3 smallpox vaccines in 9 months and then still caught smallpox i’d probably have some questions….

$PFE $MRNA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:56:21 </td>
   <td style="text-align:left;"> $SPY so omicron is the real vaccine that will cure Covid </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:55:37 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM 🚂 🚃🚃🚃🚃💰🎁🎅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:53:40 </td>
   <td style="text-align:left;"> $SPY  3 extra days for the world to fall apart. The one thing I am certain Biden can accomplish! LGB! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:53:06 </td>
   <td style="text-align:left;"> $SPY Agree or disagree 🍕 &amp;lt; 🍑 What will you be having for Xmas dinner this weekend 🤤 $tsla $AMC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:52:30 </td>
   <td style="text-align:left;"> $SPY HELLO IS THE STOCK MARKET OPEN TOMORROW? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:52:25 </td>
   <td style="text-align:left;"> $SPY I’ll bet anyone here that this is completely flat tomorrow no up or down. Willing to wager my life on it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:52:00 </td>
   <td style="text-align:left;"> ‪NEW Article:  “MMT’s Fatal Flaw: Political Willpower” - https://www.seeitmarket.com/mmts-fatal-flaw-political-willpower/‬ 
 
‪by @MichaelLebowitz $SPY $TLT $TNX $DXY #inflation‬ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:51:48 </td>
   <td style="text-align:left;"> $SPY  the vaccine is one of the greatest achievements of mankind.&amp;quot; - Trump.
“The vaccine worked, but some people aren’t taking it. The ones that get very sick and go to the hospital are the ones that don’t take the vaccine.” - Trump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:51:13 </td>
   <td style="text-align:left;"> $SPY is market open tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:51:07 </td>
   <td style="text-align:left;"> $SPY a nice start...did anyone have better entry? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:49:09 </td>
   <td style="text-align:left;"> $SPY $BTC.X hodl crypto </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:48:41 </td>
   <td style="text-align:left;"> $SPY explosion at exxon plant, better not spike gas </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:47:44 </td>
   <td style="text-align:left;"> $SPY is market close tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:47:42 </td>
   <td style="text-align:left;"> $SPY S&amp;amp;P 500 closes at a record following 3-day rebound from omicron sell-off

https://www.cnbc.com/2021/12/22/stock-market-futures-open-to-close-news.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:46:18 </td>
   <td style="text-align:left;"> $SPY NATURAL immunity contributing to South Africa low infections and hospitalization $MRNA 

https://m.theepochtimes.com/natural-immunity-likely-contributing-to-lower-hospitalization-rate-in-south-africa-amid-omicron-surge-studies_4172207.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:46:16 </td>
   <td style="text-align:left;"> $SPY the risk of shit going down has gone up. 

https://www.zerohedge.com/geopolitical/us-japan-draft-plans-set-attack-base-event-china-invades-taiwan </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:45:36 </td>
   <td style="text-align:left;"> $AMC I think the chimps, or apes, or no no monkeys may find some short term reprieve around the 26 level for a short covering face ripping rally
Back up higher…the 40 I suspect should
Bait in enough chimp ape monkeys to think it’s going to 4,000, right on cue for distribution to make a lower low when all is said and done happy holidays $GME $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:45:12 </td>
   <td style="text-align:left;"> $SPY I was looking to add something real special this Christmas to my office decor. I was thinking of ripping down the real Wall Street sign? Like right off the pole? That’d be special! I mean after all…isn’t looting and vandalism kinda encouraged in New York right now? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:45:08 </td>
   <td style="text-align:left;"> $SPY  Is The Santa Claus Stock Market Rally Real? Here Are The Numbers

https://www.benzinga.com/analyst-ratings/analyst-color/21/12/24743446/is-the-santa-claus-stock-market-rally-real-here-are-the-numbers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:44:30 </td>
   <td style="text-align:left;"> $SPY sounds like the vaccines are making the pandemic worse </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:44:23 </td>
   <td style="text-align:left;"> $SPY $MRNA vaccines useless and so is boosters 

https://nypost.com/2021/12/16/columbia-university-finds-omicron-vaccine-resistance/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:43:00 </td>
   <td style="text-align:left;"> $SPY: The long and short term trends are both positive. This is looking good! https://www.chartmill.com/stock/analyzer/stock/SPY?key=84303b30-e7bc-44d7-b0b1-1493858db9a2&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=SPY&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:42:10 </td>
   <td style="text-align:left;"> $SPY near all time highs, we all know why </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:41:09 </td>
   <td style="text-align:left;"> $SPY Some people don’t understand how central banking works and why everything is so bullish $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:40:39 </td>
   <td style="text-align:left;"> $SPY Eat up bulls... $Tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:40:27 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:40:03 </td>
   <td style="text-align:left;"> $SPY my account In real time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:36:47 </td>
   <td style="text-align:left;"> $SPY Looks like Dec 22nd Close. Probably rip higher on Monday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:36:07 </td>
   <td style="text-align:left;"> $SPY correction imminent. $450-$440 by beginning January. Make a new high monday. Downhill from there. Trash market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:34:51 </td>
   <td style="text-align:left;"> $SPY is the market open next Monday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:34:47 </td>
   <td style="text-align:left;"> $SPY Bears totally got doggystyled this week… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:34:27 </td>
   <td style="text-align:left;"> $SPY when’s Jerome speaking again? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:33:44 </td>
   <td style="text-align:left;"> $SPY Back in the late 90’s Al Gore and the scientists said that we will be telling our kids about snow by 2012. Here we are going into 2022 and our kids are seeing it snow in the Bay Area Ca. A place where it NEVER snows. But But it’s not global warming anymore, it’s climate change. We live in a 🤡 world. When I was a kid I wondered how the Germans actually followed Hitler. It’s now very easy for me to understand. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:33:07 </td>
   <td style="text-align:left;"> $SPY Have my eye on these for a quick flip next week (depending on the open of course). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:29:55 </td>
   <td style="text-align:left;"> $SPY market closes crypto goes dead 😭 $ETH.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:29:07 </td>
   <td style="text-align:left;"> $SPY Historically, how does the market perform the morning after the Christmas holiday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:28:17 </td>
   <td style="text-align:left;"> $tsla $btc.x $spy $qqq https://www.youtube.com/watch?v=ViWBBJtayzg&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:27:23 </td>
   <td style="text-align:left;"> $SPY All this discussion of Fed rates and 5+ year stocks. Won’t matter once Neuralink is commercially available. Quantum Computing plus Neuralink means no more need for capital markets. No more politics. No more Fed. Know this is true. The only way humans will ever be free is to find freedom at the hands of benevolent machines. That’s tricky, but it, in the absence of technological apocalypse, is inevitable and neigh. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:27:02 </td>
   <td style="text-align:left;"> $SPY who is holding calls. 😂😂😂this is so much stupid stock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:27:00 </td>
   <td style="text-align:left;"> $SPY Happy Holidays All !! But these guys!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:26:10 </td>
   <td style="text-align:left;"> $SPY I need to do more studying. I guess 7am-midnight yesterday wasn’t enough. Unfortunately my personal relationships are also starting to take a hit… it’s hard to find balance when trying to pursue your dream </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:25:17 </td>
   <td style="text-align:left;"> Here&amp;#39;s How My 10 Predictions For 2021 Fared https://mottcapitalmanagement.com/heres-how-my-10-predictions-for-2021-fared/ $spy $ief $qqq $xlf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:24:41 </td>
   <td style="text-align:left;"> $SPY all you bag holders please dump spy to 350 I need my 465 puts to print as much as my tsla calls did,  just buy back jan 2022 I will join </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:23:32 </td>
   <td style="text-align:left;"> $SPY Chart looks very similar like this 😂😂👇🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:23:21 </td>
   <td style="text-align:left;"> $SPY looks like it has no more gas for friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:22:32 </td>
   <td style="text-align:left;"> $TSLA after next week for all those SWING CALLS that are now TRAPPED! Expect Elon to tweet something goofy over weekend to TANK the stock 📉😹 
.. EV STOCKS will do OK next year $nio $rivn $nkla however competitive value for market share is still dominant for Tesla but Elon ability to be retarded week keep the stock subdued... $SPY at most will pay out about 14% organic growth is the dagger for stocks next year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:22:25 </td>
   <td style="text-align:left;"> $SPY Monday drop looking nice </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:22:05 </td>
   <td style="text-align:left;"> $SPY nice it is dumping good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:19:55 </td>
   <td style="text-align:left;"> $SPY  It&amp;#39;s OK plenty of support just keep climbing don&amp;#39;t look back.  gravity doesn&amp;#39;t exist </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:19:49 </td>
   <td style="text-align:left;"> $SPY  gonna drop so hard Monday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:19:12 </td>
   <td style="text-align:left;"> $SPY When I read…”I make money both ways”… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:18:32 </td>
   <td style="text-align:left;"> $SPY Futs be ha never mind </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:16:57 </td>
   <td style="text-align:left;"> $SPY PUTS PUTS PUTS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:14:43 </td>
   <td style="text-align:left;"> Thinking time $SPY 🙇‍♂️🙂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:14:35 </td>
   <td style="text-align:left;"> $SPY If you think about it there really is no such thing as a perma-bear, you can&amp;#39;t possibly stay solvent forever unless you&amp;#39;re just resetting your paper account weekly. Bears are just new faces every couple of months, or they wise up and become bull brethren. Forged by the pain that the other side engrained. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:13:01 </td>
   <td style="text-align:left;"> $SPY  Haven&amp;#39;t posted in a while but noticed this today, serious sell signal from a few weeks back on the correlation based VIX Stretch indicator. Weekly has been good for very actionable VIX spikes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:12:55 </td>
   <td style="text-align:left;"> $SPY OPEN THE CASINO 🎰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:11:33 </td>
   <td style="text-align:left;"> $spy $qqq $iwm https://www.youtube.com/watch?v=tle7N4SOKOU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:11:11 </td>
   <td style="text-align:left;"> SPX $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:11:02 </td>
   <td style="text-align:left;"> $SPY We continually tell our members to avoid short selling the indices, they are bullish and have been in an uptrend since March 2020 lows.  The Indices are sideways right now, and we expect choppy price action in the weeks to come while correcting the September 2020 lows.  The $SPY is very choppy, can even do another high before again pulling back sharply, we don’t like to trade the middle where no blue boxes are present.   #elliottwave #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:09:48 </td>
   <td style="text-align:left;"> $SPY bought 40k worth of Feb calls this morning. Been doing horrible and nothing has been working out. Going to turn all of this off until January and hope when I log back in I&amp;#39;ll be happy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:08:20 </td>
   <td style="text-align:left;"> $SPY perma bears are pathetic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:08:12 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA 
“I love being the underdog. While I don’t ask for anyone’s approval, I insist on basic respect. When it comes to pursuing your dreams it’s easy to be derailed. That’s why commitment against long odds creates legends. Doing what they say can’t be done makes you a legend. Inspiring others is what creates legends.” -Charles Payne 

(I was actually very surprised when I heard this today by pure chance… I thought Charles Payne was kind of nuts for being so hyped up about the ape movement) 

I want to become a successful trader to show that it can be done for people who have been completely broke or in prison or any other absolutely horrible circumstance… if I can accomplish this dream of being a successful trader I can inspire others thats it’s possible for them as well. You guys really don’t understand how important this is to me. That’s why I have a YouTube channel, and that’s why I post so much. For a record to show how I started. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:07:41 </td>
   <td style="text-align:left;"> $SPY I freaking love holiday rallies. 1500% portfolio growth this week playing SPY calls everyday. Eyeing that 4HR and 1D chart closely for the opportunity to switch over to puts and double it up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:07:29 </td>
   <td style="text-align:left;"> This week&amp;#39;s stock market analysis video has been published!

📽️ https://www.youtube.com/watch?v=cazMVQk2qCQ

☑️Happy Holidays!
☑️Volatility to the upside in equities
☑️Oil bounces back aggressively

Have a great weekend!

$SPY $IWM $QQQ $USO $UUP #stocks #trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:06:34 </td>
   <td style="text-align:left;"> $SPY love de Santis …. de Santis for President 

https://youtu.be/3XF5F2XrHHw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:06:20 </td>
   <td style="text-align:left;"> $SPY haven’t had a drink in forever…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:05:49 </td>
   <td style="text-align:left;"> $SPY 

NEW YORK (AP) — Worried that a new COVID-19 wave could overwhelm understaffed U.S. hospitals, federal officials on Thursday loosened rules that call on health care workers to stay out of work for 10 days if they test positive.

Those workers now will be allowed to come back to work after seven days if they test negative and don’t have symptoms. Isolation time can be cut if there are severe staffing shortages, according to the new Centers for Disease Control and Prevention guidance </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:04:40 </td>
   <td style="text-align:left;"> $SPY Death Valley is the only safe place 😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:04:36 </td>
   <td style="text-align:left;"> $SPY can someone clarify why director dropped these words

https://youtu.be/GGXxl2TYPXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:03:08 </td>
   <td style="text-align:left;"> $SPY im at home in queens, new york for the holidays. Tell me how i step into 2 different wallgreens now and they got cops posted up inside making sure people following new mask mandates. Fucking comedy show </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:02:36 </td>
   <td style="text-align:left;"> $GME $AMC spider man was lit. Let&amp;#39;s flie $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:02:32 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:02:30 </td>
   <td style="text-align:left;"> $SPY 440 incoming Monday, it will be blamed on profit taking, except all the big guys are out at ATH haha, market is creating bagholders for the next 5-8 years after that you may break even but you will most likely sell at very bottom, but you deserve it. Thank you  for playing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:02:24 </td>
   <td style="text-align:left;"> $SPY SPY 2021-12-23 Trade Analysis Video: 
https://www.youtube.com/watch?v=LIYFokI-U6c </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:01:24 </td>
   <td style="text-align:left;"> $SPY Merry Christmas.  Stay alone and wear a mask! 👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:00:18 </td>
   <td style="text-align:left;"> $SPY RSI is running hot. If futes dump over the weekend for a cool off Monday morning we’ll be able to run this up to a retest of 473 to 475 up to 480

If we open green Monday SPY likely dumping hard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 08:00:01 </td>
   <td style="text-align:left;"> $SPY Monday expect a pullback a couple $ maybe on some OMICRON FUD after the holidays. But expect the really to start soon after!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:59:25 </td>
   <td style="text-align:left;"> $SPY Well that was obvious. Some dummy bears actually tried to Short lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:58:27 </td>
   <td style="text-align:left;"> $SPY yo… I couldn’t sell my options today bc of NO SIGNAL lmfaoooo this shit better gap tf up next week

Probably fucked tho </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:54:38 </td>
   <td style="text-align:left;"> $SPY Atleast markets would be  half day open tomorrow, if Trump was president. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:54:27 </td>
   <td style="text-align:left;"> $SPY inflation running hot in turkey their economy must be strong like ours </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:54:10 </td>
   <td style="text-align:left;"> $SPY Kings 18
 &amp;quot;At noon Elijah began to taunt them. &amp;quot;Shout louder!&amp;quot; he said. &amp;quot;Surely he is a god! Perhaps he is deep in thought, or busy, or traveling. Maybe he is sleeping and must be awakened.&amp;quot;&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:53:53 </td>
   <td style="text-align:left;"> $SPY if this shit don&amp;#39;t dump  soon ...watch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:53:35 </td>
   <td style="text-align:left;"> The Feds balance $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:52:53 </td>
   <td style="text-align:left;"> $SPY https://youtu.be/dk5L6deaKEk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:51:59 </td>
   <td style="text-align:left;"> $SPY going red AH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:51:37 </td>
   <td style="text-align:left;"> $SPY $486 next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:51:24 </td>
   <td style="text-align:left;"> $SPY Last year 23rd December 239k cases. Yesterday US reported 244k cases.
Last year deaths reported on 23rd: around 2100
Yesterday deaths: 2083

Unfortunately, Numbers expected to go up after Christmas. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:50:55 </td>
   <td style="text-align:left;"> When you hit a rough patch and it seems like everyday is an L. Shooters keep shooting. $TSLA $SPY $CEI $METX $SEAC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:50:44 </td>
   <td style="text-align:left;"> $SPY why is Coke vs Pepsi even a debate when beer is clearly better than them both </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:50:30 </td>
   <td style="text-align:left;"> $SPY 

Looks like avoiding the vaccine be very difficult soon.  Reason being is that the mandates are now spreading to suburbs. That will make it nearly impossible to not comply unfortunately.  

Cook County in Illinois is joining Montgomery County outside of DC and that is the tip of the iceberg I think.   

It will be difficult for suburbs to not issue mandates simply because if they don&amp;#39;t all of the unvaccinated people from the bordering cities will come there and they can&amp;#39;t have that.

It will come to suburbs NJ PA CT VA LA, CA,  and others.   Really unfortunate IMO but inevitable. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:50:03 </td>
   <td style="text-align:left;"> $SPY Looks like it going to break through $400 and keep running. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:49:56 </td>
   <td style="text-align:left;"> $SPY I’m so close to not having to deal with PDT rules anymore. I love volatility. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:49:36 </td>
   <td style="text-align:left;"> $SPY Bears don’t think $SPY be like it is, but it do! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:49:02 </td>
   <td style="text-align:left;"> $SPY historically spy does great after xmas tho </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:48:54 </td>
   <td style="text-align:left;"> $SPY Do American Chameleons eat earwigs? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:48:50 </td>
   <td style="text-align:left;"> $CROX Bought a load of this today. Revenues growing over 50%.  Only like 11 pe….great cash flow…increasing margins…great management.  Add onto this a merger that is accretive to revenues AND EARNINGS.  It’s absolutely awesome and got it on the cheap.  $SPY $NKE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:48:41 </td>
   <td style="text-align:left;"> $SPY I don’t like the 5 min 1.50 red candle but still bullish, just hedge </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:48:35 </td>
   <td style="text-align:left;"> $SPY So many Covid specialists on a stock forum… Trump made everyone think they were smart if they read the right meme, fuckin meme culture 🙄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:47:42 </td>
   <td style="text-align:left;"> $SPY 500s soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:47:30 </td>
   <td style="text-align:left;"> $SPY $SPX Focus on the price action, not the narrative machine. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:46:26 </td>
   <td style="text-align:left;"> $SPY who buys at this level? 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:45:56 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;m thinking you suck dick for crack, BearShit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:45:45 </td>
   <td style="text-align:left;"> $SPY How long we going to let authoritarian clowns like this rule our country? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:45:11 </td>
   <td style="text-align:left;"> $SPY thinking it backtests 460s next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:43:28 </td>
   <td style="text-align:left;"> $SPY The Covid vaccine doesn’t stay in your body for long. It gets eliminated within weeks. Whats left is your bodys immune cells that have been trained to fight covid in the future 

Its why the vaccine takes time before it starts working. Also why there are no long term side effects of the vaccines </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:43:11 </td>
   <td style="text-align:left;"> $SPY this dude literally sending our LNG over there. wtf dude, youre gonna spike my prices here you dipfk. 

https://www.zerohedge.com/commodities/us-sends-fleet-lng-ships-fuel-starved-europe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:42:47 </td>
   <td style="text-align:left;"> $SPY anyway, once the ATH was sent earlier today and I knew I would post that on it lol 😆…but who knows if it is a part of the song 🎶 and the truth of truth or not wrong 😑 but…the fed and Powell… are we doing the right right outside or do you want us outside walking 🚶‍♂️?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:42:40 </td>
   <td style="text-align:left;"> $SPY $IWM $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:40:52 </td>
   <td style="text-align:left;"> $SPY I think the market will surpass all time highs then dip entering the new year… anybody else see this ?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:40:26 </td>
   <td style="text-align:left;"> $SPY Romans 3:23 
&amp;quot;For all have sinned and fall short of the glory of God,&amp;quot;

John 14:6 
&amp;quot;Jesus said to him, “I am the way, and the truth, and the life. No one comes to the Father except through me.&amp;quot;

Matthew 24:24
&amp;quot;For false christs and false prophets will arise and perform great signs and wonders, so as to lead astray, if possible, even the elect.&amp;quot;

Hebrews 10:26-29
&amp;quot;For if we go on sinning deliberately after receiving the knowledge of the truth, there no longer remains a sacrifice for sins, but a fearful expectation of judgment, and a fury of fire that will consume the adversaries. Anyone who has set aside the law of Moses dies without mercy on the evidence of two or three witnesses. How much worse punishment, do you think, will be deserved by the one who has spurned the Son of God, and has profaned the blood of the covenant by which he was sanctified, and has outraged the Spirit of grace?&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:40:09 </td>
   <td style="text-align:left;"> $SPY futures aren’t up? Christmas Eve ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:39:30 </td>
   <td style="text-align:left;"> $AMZN only company in the world
That’s a justified valuation $SPY $DIA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:39:21 </td>
   <td style="text-align:left;"> $SPY what is bill gate doing
We only saw Elon nowadays

$tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:38:38 </td>
   <td style="text-align:left;"> $BIGZ potentially the most undervalued discounted CEF out there and the best management Black Rock.. $SPY $QQQ $BST $BSTZ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:36:32 </td>
   <td style="text-align:left;"> $SPY Romans 5:19
&amp;quot;For as by the one man&amp;#39;s disobedience the many were made sinners, so by the one man&amp;#39;s obedience the many will be made righteous.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:36:01 </td>
   <td style="text-align:left;"> $SPY so more ppl traveling for the holidays than 2019. Great way to just accelerate the spread everywhere </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:35:52 </td>
   <td style="text-align:left;"> $SPY good job team. Merry Christmas </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:34:59 </td>
   <td style="text-align:left;"> $SPY LG BrandO’s speech yesterday wasn’t bad.  *THE VACCINATOR* https://banned.video/watch?id=61c4b0c82a575232aa6de893 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:34:28 </td>
   <td style="text-align:left;"> $SPY Fuk you Xi, CCP, and Whinny the Pooh too </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:34:07 </td>
   <td style="text-align:left;"> MOVES HAPPENING NOW (6:33pm)

⦿ $SPY is down 0.0% in the last 5 mins. 

⦿ There are 5 stocks that are up more than 3% in the last 5 mins. 

⦿ The top gainer is up 18.0% in the last 5 mins. 

 See the stocks that are moving the most right now via link in bio (wallstreetodds .com). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:34:06 </td>
   <td style="text-align:left;"> $OCGN I added more to this beauty.
I expect explosive move very soon $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:34:02 </td>
   <td style="text-align:left;"> $SPY puts going to print </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:33:57 </td>
   <td style="text-align:left;"> $SPY who swinging calls? 🤑🥇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:33:28 </td>
   <td style="text-align:left;"> $TSLA Elon Claus is coming to town $spy $aapl
Tesla phone cough </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:32:36 </td>
   <td style="text-align:left;"> $SPY I made that analysis without knowing of this verse BTW (didnt read Genesis fully lol) 
Genesis 3 &amp;quot;Now the serpent was more crafty than any other beast of the field that the Lord God had made. He said to the woman, “Did God actually say, ‘You shall not eat of any tree in the garden’?” And the woman said to the serpent, “We may eat of the fruit of the trees in the garden, but God said, ‘You shall not eat of the fruit of the tree that is in the midst of the garden, neither shall you touch it, lest you die.’” But the serpent said to the woman, “You will not surely die. For God knows that when you eat of it your eyes will be opened, and you will be like God, knowing good and evil.” ...&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:32:09 </td>
   <td style="text-align:left;"> $SPY Told her she was cute and she didn&amp;#39;t know what to make of it
Well, don&amp;#39;t let it go to your head
Bought this bottle of Dom, it&amp;#39;s going straight to the head </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:29:02 </td>
   <td style="text-align:left;"> $SPY Merry Christmas, make sure to remember that China is now the global superpower and they will destroy the earth and its resources :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:29:02 </td>
   <td style="text-align:left;"> $SPY what is glorious is that we won’t be tanking anymore. Covid cases? Shut downs? Heck if Biden gets Covid that’s the best ring to happen for the stock market. Going to be up at least 5% next week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:28:56 </td>
   <td style="text-align:left;"> $SPY Get ready for the ultimate rally. 

https://www.dailymail.co.uk/news/article-10335105/Army-announce-developed-single-vaccine-protects-variants-COVID-SARS.html?ito=facebook_share_article-top&amp;amp;fbclid=IwAR2VPTMMeFCQ1MygPTecv6jXbX7u1XuCfwrVaucgiGBd9-zplcjPBQraHmk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:28:34 </td>
   <td style="text-align:left;"> What do I preach $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:28:34 </td>
   <td style="text-align:left;"> $SPY 

Airports packed!  Wow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:27:42 </td>
   <td style="text-align:left;"> $SPY this channel is bullish 470.58 is Resistance Welcome in 2022 with a bang </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:26:26 </td>
   <td style="text-align:left;"> $SPY No futures tonight? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:26:07 </td>
   <td style="text-align:left;"> $SPY The Apple of Eden? What was it? I believe it contained the knowledge of Evil. For there to be white, there must be black. To have happiness, it must be based off the ability of sadness. For one to do good, one must know what is Evil. We could have always been ignorant of that fact, but we wouldn&amp;#39;t be in this situation here now would we </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:25:46 </td>
   <td style="text-align:left;"> $SPY lol i bet most those fuckers who bought at the end thought the market was open on friday till 2pm 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:25:38 </td>
   <td style="text-align:left;"> $SPY clocked out during one of my deliveries and dunked on a kid Hope I don&amp;#39;t end up on TikTok. Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:24:37 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:23:50 </td>
   <td style="text-align:left;"> $AAPL Tesla will become 4 trillion before Apple $tsla $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:23:24 </td>
   <td style="text-align:left;"> $SPY TheDarkStranger is 100x  cooler than this guy. 
As your future President, I ask that you block this anti Ricky Davis-er </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:22:27 </td>
   <td style="text-align:left;"> $SPY the only thing stopping the *consistent* upward trajectory of this market will be interest rates

Rates govern everything </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:22:10 </td>
   <td style="text-align:left;"> $SPY Bull or Bear or Ape or Fucktard…Happy Holidays!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:22:04 </td>
   <td style="text-align:left;"> $TSLA once Tesla reach 2k, I&amp;#39;m going retire $spy
At age 23 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:21:17 </td>
   <td style="text-align:left;"> $SPY YOU WILL NEVER RETIRE BECAUSE YOU BOUGHT PUTS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:20:38 </td>
   <td style="text-align:left;"> $SPY i will never retire </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:20:21 </td>
   <td style="text-align:left;"> $SPY You will never retire LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:20:17 </td>
   <td style="text-align:left;"> $SPY next headline:  Taiwan ...   $UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:20:08 </td>
   <td style="text-align:left;"> $SPY Would we have free will if everything was dictated? You only have yourselves to blame </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:20:07 </td>
   <td style="text-align:left;"> $TSLA $SPY 

BEARS  WHAT HAPPENED TO THE CRASH THIS WEEk???? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:19:41 </td>
   <td style="text-align:left;"> *shuts bot down*  you guys have a blessed holiday.  $SOPA $BFRI $LLL $SPY $MARA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:19:28 </td>
   <td style="text-align:left;"> $UVXY  is the inverse ETF of Covid cases $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:19:25 </td>
   <td style="text-align:left;"> $SPY China and Russia are gonna hit a lick on the US get ready </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:19:18 </td>
   <td style="text-align:left;"> $SPY IM WRAPPING UP MY DAY AT THE OFFICE. 30 MARGIN CALLS, NOT TOO BAD. GOOD WEEKEND FELLAS $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:19:08 </td>
   <td style="text-align:left;"> $SPY 

Sonic merry mooo bahahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:19:04 </td>
   <td style="text-align:left;"> $SPY bears can’t catch a break. 

Now isn’t the time to be bearish 

IMO, wait for rate hikes or bad news to come out. 

There’s no TRUE fear </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:18:54 </td>
   <td style="text-align:left;"> $SPY Your immune system and God&amp;#39;s protection does wonders, he is the Creator, he can influence this Earth. Your body already does what the vaccine does if you give it the correct nutrients </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:18:40 </td>
   <td style="text-align:left;"> $SPY $SPX $VIX ONE TRULY BEARISH PERSPECTIVE I HAVE
Everyone is going to start selling vol on bad news to front run the reflexive dip buying. Gotta play vol convexity. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:18:38 </td>
   <td style="text-align:left;"> $SPY bears always take it up the </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:18:32 </td>
   <td style="text-align:left;"> $SPY BULLS GOOD LUCK HOLDING THE CALLS OVER THE WEEKEND U GONNA NEED IT $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:18:02 </td>
   <td style="text-align:left;"> $SPY The United States of America will fail </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:17:27 </td>
   <td style="text-align:left;"> $spy $aapl $msft https://www.youtube.com/watch?v=1jnfZaEyseE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:17:10 </td>
   <td style="text-align:left;"> $SPY any more proof needed there is a master hand over the markets than that perfectly coordinated mini meltdown in the last 5 minutes today across every market index? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:16:36 </td>
   <td style="text-align:left;"> $SPY if omicron is 50% less chance to cause hospitalization, but 4x more infections, doesnt that lead to 100% more people in the hospital?. 

100 ppl get delta, say 25% in hospital, 25ppl

Omicron 4x more infection, 400 ppl get omicron. 12.5% of ppl hospitalized. 50 ppl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:16:19 </td>
   <td style="text-align:left;"> $BTC.X $SPY Anyone who tells you America’s Economy will recover is LYING </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:16:07 </td>
   <td style="text-align:left;"> $SPY wishing everyone a happy holidays </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:15:08 </td>
   <td style="text-align:left;"> $M $SPY $QQQ its a wild prediction but what are the odds that every stock trades sideways tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:14:03 </td>
   <td style="text-align:left;"> $SPY if this just keeps goin up after every  reset why are there so many bears still lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:13:43 </td>
   <td style="text-align:left;"> $BTC.X Why are people still applying for first time unemployment claims? $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:13:21 </td>
   <td style="text-align:left;"> $SPY the market will be handled thru the transition. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:13:08 </td>
   <td style="text-align:left;"> $SMURF 
Canadian markets are opened tomorrow and SMURF (COIN.NE in Canada) will outperform again as the metaverse is getting recognized as the next bubble, bigger than the dot.com or bitcoin 
Long metaverse $AAPL $FB $BTC.X $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:13:00 </td>
   <td style="text-align:left;"> $SPY God bless crooners. May they live forever! https://youtu.be/Nx-DvH41Tjo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:12:20 </td>
   <td style="text-align:left;"> $SPY monday we take off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:11:48 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:11:44 </td>
   <td style="text-align:left;"> $SPY merry Christmas ya filthy animals </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:11:39 </td>
   <td style="text-align:left;"> $SPY Sure. The BS meter is pegged. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:11:13 </td>
   <td style="text-align:left;"> $SPY It&amp;#39;s going down. Sonic meat on the menu! 🍔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:10:14 </td>
   <td style="text-align:left;"> $SPY According to my calculations and market sentiment, conditions seem prime to obtain more alpha towards my portfolio through an aggressive, short term strategy. Wow, see how easy is it to sound like you&amp;#39;re smart yoloing options? $TSLA $QQQ $AAPL $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:09:37 </td>
   <td style="text-align:left;"> $SPY how are my gay bears today🤣🤣🤣🤣🤣🖕🖕🖕🖕 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:08:54 </td>
   <td style="text-align:left;"> $SPY Next week we get a New Years rally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:08:35 </td>
   <td style="text-align:left;"> $TSLA $SPY $SPX $DIA $DJIA ---

How can a company that makes poor quality vehicles (according to JD Powers), and faces competition from several major car manufacturers (Ford, Mercedes, VW, Toyota, Nissan etc) which are experts in high-volume and high-quality car production, have a stock-price near all-time highs?  If there is no clear explanation, usually this indicates that something inappropriate is going on. 
 
This situation reminds of another ‘genius’ who had revolutionized investment strategies that nobody could understand or explain (see 2001 article by Barrons) until that ‘genius’ (Madoff) was exposed for what he truly was. 

https://www.barrons.com/articles/SB989019667829349012?tesla=y </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:08:14 </td>
   <td style="text-align:left;"> $SPY looks like the fed’s plunge patrol was hard at work today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:07:50 </td>
   <td style="text-align:left;"> $SPY Santa rally is over </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:07:29 </td>
   <td style="text-align:left;"> $SPY 
Just hanging out pregaming for Christmas 🎅🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:07:26 </td>
   <td style="text-align:left;"> $DOGE.X $BTC.X $TSLA $AAPL $SPY Sign me up for the backseat of the car preferably the right back seat </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:06:25 </td>
   <td style="text-align:left;"> $SPY you get these numbers like job openings. They isnt because there is more jobs now than before, there is most likely less with many businesses have gone out. It shows how current business are not getting people hired. I foresee those business slashing those openings in the next three months. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:06:23 </td>
   <td style="text-align:left;"> $SPY $QQQ widespread halts tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:05:57 </td>
   <td style="text-align:left;"> $SPY Santa rally next week spy 480 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:05:43 </td>
   <td style="text-align:left;"> $SPY At 0 B.C there were 232 million people on this Earth. Now there is 7 billion. Thats about 3% of the current population. That is what worries me. &amp;quot;About 9.2% of the world, or 689 million people, live in extreme poverty on less than $1.90 a day, according to the World Bank.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:05:34 </td>
   <td style="text-align:left;"> $SPY $qqq santa gonna take out the sellers on monday 👀💯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:04:58 </td>
   <td style="text-align:left;"> $TQQQ $QQQ $SPY $IWF $BTC.X Personally, inflation-protected portfolios are blue chip equity focused. We&amp;#39;re to lazy to build a physical real estate portfolio. Otherwise, it&amp;#39;s literally a minus-sum game, isn&amp;#39;t it? Yes, I&amp;#39;m trying to get your input. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:04:02 </td>
   <td style="text-align:left;"> $SPY look how heavy volume is for the upside on spy vs the downside. Up we go!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:03:58 </td>
   <td style="text-align:left;"> $SPY $32,450 2019, $13,000 last year’s Santa rally! Lol, $1700.00 this year! 🥲 Big Difference! Maybe next! Merry Christmas 🎄🎁  🎅🏼  🧑‍🎄 ALL! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:03:46 </td>
   <td style="text-align:left;"> $SPY damn thought futures would be open tonight. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:03:33 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:02:31 </td>
   <td style="text-align:left;"> $SPY $QQQ many portfolios will be frozen tomorrow and many traders will ask why. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:02:16 </td>
   <td style="text-align:left;"> $SPY 

In all seriousness it&amp;#39;s probably a mistake for towns and cities to cancel their annual outdoor  New Years Eve celebrations (I&amp;#39;ve heard about quite a few in both small and large towns).  

I think this will only force more folks inside at parties in homes and bars and hotel ballrooms.  Probably more likely to cause more spread. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:02:10 </td>
   <td style="text-align:left;"> $SPY Damnit. Told my wife id skip out on trading this week to spend time with the kiddos, havent traded since monday and missed out on this epic bull run.. oh well guess ill short it sometime next week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:02:07 </td>
   <td style="text-align:left;"> $SPY Up 3 days in a row 454.98 | 462.86 | 467.7 | 471.5 |  https://www.sleekoptions.com/sleekscan.aspx?sub1=dscan </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:01:50 </td>
   <td style="text-align:left;"> $SPY my view on the market is that a little while it looks great 😌 it was nice 😊 it would love 💗 more and I would love to have a happy 😊 to my heart </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:01:48 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ Xmas rally could be over. Dow Jones making a Head and Shoulders pattern. Next week could volatile. $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:01:34 </td>
   <td style="text-align:left;"> $SPY if we break ATH on Monday, we could legit be looking at EYO surge of +5% from this current price. 

How? 

WHERES THE RESISTANCE? 474. 
After that: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 07:00:24 </td>
   <td style="text-align:left;"> $SPY 

New York City scales back New Year’s Eve festivities in Times Square

Funny, we already whipped omicron’s arse </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 06:59:26 </td>
   <td style="text-align:left;"> $SPY so 470.70 + 3%= 484.82.

You can&amp;#39;t tell me that isn&amp;#39;t possible for next week. 3 seperate 1% days we got it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 06:59:23 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 06:58:55 </td>
   <td style="text-align:left;"> $SPY when u order a spicy chicken but they give u a spicy chicken deluxe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 06:58:43 </td>
   <td style="text-align:left;"> $SPY shocking, Biden and Trump administration supporting each other in public 

https://twitter.com/presssec/status/1474056675841748992?s=21 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 06:58:42 </td>
   <td style="text-align:left;"> $SPY -HS or MA top playing out on tqqq - confimed by break of 165.47 - awfully close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 06:58:04 </td>
   <td style="text-align:left;"> $SPY I’m very thankful for the rally gift the market has given Bulls this Christmas…🙏🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 06:57:55 </td>
   <td style="text-align:left;"> $SPY it would be my guess most people have delta and are being told they have omicron.  They dont test this, you cant see results, you just rely on what is said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 06:56:54 </td>
   <td style="text-align:left;"> $SPY https://www.barrons.com/articles/tax-loss-harvesting-capital-gains-stock-market-51633722742 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 06:56:54 </td>
   <td style="text-align:left;"> $SPY When are the markets going to open? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 06:55:29 </td>
   <td style="text-align:left;"> $SPY called out in discord🎯🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 06:55:01 </td>
   <td style="text-align:left;"> $SPY Does extended hours tradimy go until 8 tonight? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 06:54:33 </td>
   <td style="text-align:left;"> $SPY https://youtu.be/0gpJCg_VbkA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 06:54:17 </td>
   <td style="text-align:left;"> $SPY time for some crispy fried chicken with garlic sauce at the ghetto Chinese spot 🎎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 06:53:54 </td>
   <td style="text-align:left;"> $SPY 

Next week’s agenda </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 06:53:47 </td>
   <td style="text-align:left;"> $SPY The Buddhist, they can see it with their strong spiritual training. But they defined it wrong. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 06:53:31 </td>
   <td style="text-align:left;"> $SPY 440 Monday open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 06:53:25 </td>
   <td style="text-align:left;"> $SPY let’s not forget SPY moves along with their holdings… anybody think tech has a big week ahead? 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 06:52:49 </td>
   <td style="text-align:left;"> $SPY but it goes much deeper than just our physical bodies </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 06:52:46 </td>
   <td style="text-align:left;"> $CRSP once she breaks through $84-85 its off to the races with less resistance every step of the way as this has been extremely oversold over the past year. Add zone here folks, easy money heading into 2022..💎💎💎 $SPY Christmas Rally intact </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 06:52:33 </td>
   <td style="text-align:left;"> $SPY Guys there&amp;#39;s this app called Tik Tok and they have trading strategies and plays and stuff. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 06:51:56 </td>
   <td style="text-align:left;"> $SPY The fact we are able to type on this computer, to think, to see, to have free will, it is a miracle </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 06:51:48 </td>
   <td style="text-align:left;"> $SPY Market loves Bulls…it’s obvious! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 06:51:48 </td>
   <td style="text-align:left;"> $SPY $QQQ Cheers bulls. Have a good one 🥂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 06:51:33 </td>
   <td style="text-align:left;"> $SPY Shout out to anyone who loves Last Christmas as much as me. Nothing beats George Michael and Andrew Ridgeley, but his is a good cover. https://youtu.be/pILoWGyAfuk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 06:50:50 </td>
   <td style="text-align:left;"> $SPY Futes rippin yet? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 06:50:40 </td>
   <td style="text-align:left;"> $SPY Bears in real life.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 06:50:24 </td>
   <td style="text-align:left;"> $SPY 470 again jc fml. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 06:50:16 </td>
   <td style="text-align:left;"> $SPY There is infinite possibility of what this universe could be. Do not deny what is in front of your face </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 06:50:10 </td>
   <td style="text-align:left;"> $SPY historically next week is usually great as well so we could 4900. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 06:49:53 </td>
   <td style="text-align:left;"> $SPY $QQQ Today felt weak.  Anyone hedging? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 06:49:50 </td>
   <td style="text-align:left;"> $SPY award for prettiest trader of the year goes to me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2021-12-24 06:49:39 </td>
   <td style="text-align:left;"> $SPY Onwards and upwards!!

Merry Christmas and happy New Year to all market participants! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 09:46:00 </td>
   <td style="text-align:left;"> Besides having an excellent technical rating, $QQQ also presents a decent setup pattern. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 09:23:44 </td>
   <td style="text-align:left;"> $QQQ $spy next week 10-15 percent correction starts, new year deep red, omicron wave is going to explode soon, market will react heavily, worse than after thanksgiving </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 09:21:18 </td>
   <td style="text-align:left;"> $QQQ is going to catch the new variant and my puts will print </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 09:10:28 </td>
   <td style="text-align:left;"> $SPY $QQQ $MSFT Will this repeat thanksgiving? green before holiday and then everyone come back for a dump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 09:00:07 </td>
   <td style="text-align:left;"> $QQQ blood next week, Covid tsunami will trigger a 10 to 15 percent correction starting next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 08:57:52 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Daily market recap 12/23/2021

https://youtu.be/nNkzm93Kvqc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 08:55:37 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM 🚂 🚃🚃🚃🚃💰🎁🎅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 08:35:55 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 08:28:17 </td>
   <td style="text-align:left;"> $tsla $btc.x $spy $qqq https://www.youtube.com/watch?v=ViWBBJtayzg&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 08:25:17 </td>
   <td style="text-align:left;"> Here&amp;#39;s How My 10 Predictions For 2021 Fared https://mottcapitalmanagement.com/heres-how-my-10-predictions-for-2021-fared/ $spy $ief $qqq $xlf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 08:11:33 </td>
   <td style="text-align:left;"> $spy $qqq $iwm https://www.youtube.com/watch?v=tle7N4SOKOU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 08:10:14 </td>
   <td style="text-align:left;"> $QQQ rug pull next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 08:08:12 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA 
“I love being the underdog. While I don’t ask for anyone’s approval, I insist on basic respect. When it comes to pursuing your dreams it’s easy to be derailed. That’s why commitment against long odds creates legends. Doing what they say can’t be done makes you a legend. Inspiring others is what creates legends.” -Charles Payne 

(I was actually very surprised when I heard this today by pure chance… I thought Charles Payne was kind of nuts for being so hyped up about the ape movement) 

I want to become a successful trader to show that it can be done for people who have been completely broke or in prison or any other absolutely horrible circumstance… if I can accomplish this dream of being a successful trader I can inspire others thats it’s possible for them as well. You guys really don’t understand how important this is to me. That’s why I have a YouTube channel, and that’s why I post so much. For a record to show how I started. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 08:07:29 </td>
   <td style="text-align:left;"> This week&amp;#39;s stock market analysis video has been published!

📽️ https://www.youtube.com/watch?v=cazMVQk2qCQ

☑️Happy Holidays!
☑️Volatility to the upside in equities
☑️Oil bounces back aggressively

Have a great weekend!

$SPY $IWM $QQQ $USO $UUP #stocks #trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 07:56:58 </td>
   <td style="text-align:left;"> $QQQ 400

https://www.interactivebrokers.com/mkt/?src=xiaowangY&amp;amp;url=%2Fcn%2Findex.php%3Ff%3D2359 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 07:54:17 </td>
   <td style="text-align:left;"> $QQQ really hope this has a few more big days and stops dipping into every close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 07:42:40 </td>
   <td style="text-align:left;"> $SPY $IWM $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 07:42:27 </td>
   <td style="text-align:left;"> $BTC.X $DJIA $QQQ $UDN &amp;quot;A $100,000 salary has long been the gold standard of success. But in today&amp;#39;s economy, it won&amp;#39;t pay for a house, an education, or a kid.&amp;quot; https://www.businessinsider.com/how-far-does-six-figure-salary-go-house-college-kids-2021-12 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 07:39:30 </td>
   <td style="text-align:left;"> $AMZN only company in the world
That’s a justified valuation $SPY $DIA $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 07:38:38 </td>
   <td style="text-align:left;"> $BIGZ potentially the most undervalued discounted CEF out there and the best management Black Rock.. $SPY $QQQ $BST $BSTZ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 07:34:06 </td>
   <td style="text-align:left;"> $OCGN I added more to this beauty.
I expect explosive move very soon $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 07:19:18 </td>
   <td style="text-align:left;"> $SPY IM WRAPPING UP MY DAY AT THE OFFICE. 30 MARGIN CALLS, NOT TOO BAD. GOOD WEEKEND FELLAS $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 07:18:51 </td>
   <td style="text-align:left;"> $tsla $btc.x $qqq https://www.youtube.com/watch?v=ViWBBJtayzg&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 07:15:08 </td>
   <td style="text-align:left;"> $M $SPY $QQQ its a wild prediction but what are the odds that every stock trades sideways tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 07:15:02 </td>
   <td style="text-align:left;"> $QQQ has an excellent technical rating and also presents a decent setup pattern. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 07:12:40 </td>
   <td style="text-align:left;"> $QQQ bullish or bearish next week?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 07:10:14 </td>
   <td style="text-align:left;"> $SPY According to my calculations and market sentiment, conditions seem prime to obtain more alpha towards my portfolio through an aggressive, short term strategy. Wow, see how easy is it to sound like you&amp;#39;re smart yoloing options? $TSLA $QQQ $AAPL $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 07:06:23 </td>
   <td style="text-align:left;"> $SPY $QQQ widespread halts tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 07:05:34 </td>
   <td style="text-align:left;"> $SPY $qqq santa gonna take out the sellers on monday 👀💯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 07:04:58 </td>
   <td style="text-align:left;"> $TQQQ $QQQ $SPY $IWF $BTC.X Personally, inflation-protected portfolios are blue chip equity focused. We&amp;#39;re to lazy to build a physical real estate portfolio. Otherwise, it&amp;#39;s literally a minus-sum game, isn&amp;#39;t it? Yes, I&amp;#39;m trying to get your input. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 07:02:31 </td>
   <td style="text-align:left;"> $SPY $QQQ many portfolios will be frozen tomorrow and many traders will ask why. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 07:01:48 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ Xmas rally could be over. Dow Jones making a Head and Shoulders pattern. Next week could volatile. $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 06:51:48 </td>
   <td style="text-align:left;"> $SPY $QQQ Cheers bulls. Have a good one 🥂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 06:49:53 </td>
   <td style="text-align:left;"> $SPY $QQQ Today felt weak.  Anyone hedging? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 06:33:36 </td>
   <td style="text-align:left;"> $SPY $QQQ Remember when bears said we were gonna break the support from early December? 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 06:33:33 </td>
   <td style="text-align:left;"> $QQQ are we trading half day tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 06:31:05 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ $IWM $DIA  
 
Disgusting country.  Now you know why people will &amp;quot;pay any price&amp;quot; to buy real estate, private jets, yachts, cars, etc. 
 
The death of honest capitalism. 
 
https://www.wsj.com/articles/thefts-of-covid-19-relief-funds-total-at-least-100-billion-secret-service-says-11640202072 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 06:29:21 </td>
   <td style="text-align:left;"> $SPY  $QQQ this week has ruined christmas for so many bears 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 06:27:15 </td>
   <td style="text-align:left;"> $QQQ what a fine week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 06:24:52 </td>
   <td style="text-align:left;"> $SPY $QQQ some are calling for a 20% “correction” in 2022.  That would put SPY at $375 and Q’s at $317 at todays prices.   😂

Uh…zero chance that happens. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 06:23:27 </td>
   <td style="text-align:left;"> $SPX latex2a0cfd0658d119aad86e2e8c099a7ac9QQQ - CALL IDEAS ✅
$COST - NO TRIGGER ❌

CONGRATS TO OUR FOLLOWERS &amp;amp; SUBSCRIBERS 🥂
FOLLOW ME HERE FOR MORE TRADE IDEAS 👈🏻 💎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 06:20:39 </td>
   <td style="text-align:left;"> $QQQ $SPY People need to stop with BS analysis and charts. This market is simply pumped by Fed at massive scale. Other than Fed no amount of liquidity can pump Nasdaq 5.6% in 3 days. Fed’s stimulus ending in a few months and will be gone days of double digit gains for Nasdaq &amp;amp; SP. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 06:02:41 </td>
   <td style="text-align:left;"> Omicron Starts to Slow U.S. Economy as Consumer Spending Flags

https://www.wsj.com/articles/consumer-spending-personal-income-inflation-november-2021-11640215420

$TQQQ $SQQQ $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 06:02:24 </td>
   <td style="text-align:left;"> latexdde39a5686c3479fb55a4f81cce8dfc7TQQQ latex30dbc583839fd33e1e2b6c1c8ee602f4FACE 
$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:55:04 </td>
   <td style="text-align:left;"> $SPY $QQQ The market will wake up to 1.5-2 mil new covid cases on Monday. How do you think that going to play out? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:54:08 </td>
   <td style="text-align:left;"> $SPY $QQQ
Wishing everyone and their families a Merry Christmas and a Happy Amanita Muscaria day! Tomorrow&amp;#39;s a holiday and the market will be closed so I&amp;#39;ll see you all on Monday morning.

Cheers and enjoy the time off! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:52:20 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $IWM Small caps brought this back up for the week, if you look at the IWM on your weekly chart and daily chart the candles that represent this weeks trading look just like they do here so you can tell who did most of the lifting this week on this percentage chart. You had a 13% gain on the  weekly which represents roughly 800 stocks that moved back above their 200 ma.  There is still almost 50% of the market below their 200ma as you can see, so still a long way to go. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:52:14 </td>
   <td style="text-align:left;"> $SPY 2 major pullbacks in 17 years...and the last one just happened 19 months ago....foolish to bet against stock market. $QQQ $JD $KWEB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:50:59 </td>
   <td style="text-align:left;"> 5-Day ETF Sentiment Recap: $QQQ is the #2 ETF that institutions are trading over rolling 5 day window with 431.2K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:49:35 </td>
   <td style="text-align:left;"> $SPY $QQQ How come today wasn’t a half day for the market? I remember we used to have a half day of trading only right before the Christmas holidays in the previous years </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:49:14 </td>
   <td style="text-align:left;"> $QQQ SpoOokY Real-Time 
Trade Action Opportunity Tracking Tool

Rolling Trade Action Opportunity
Trigger ALERT Range:
(398.83 / 393.13)

Logarithm (x+n)
Short Wavelength Plot 
Calibration and Interface UpDate

Last Finite Potential Well 
Measurement at: 396.92
For:
12/23/21 at 4:00PM EST At Close

Developing Ad Interim Trade Action 
Opportunity Potentials:
Short-Term = SELL
Long Term = SELL

sWAV SpoOokY: 
DOES NOT!!!
FORECAST STOCK PRICE, 
OFFER BUY/SELL ADVICE, or 
RECOMMEND ANY STOCK for 
TRADE or INVESTMENT.   
SpoOokY is for:
EDUCATION and ENTERTAINMENT ONLY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:47:50 </td>
   <td style="text-align:left;"> $QQQ Direction confirmed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:47:01 </td>
   <td style="text-align:left;"> Who entered $ENTG for a swing trade today? Love the chart.  $QQQ $SPY $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:46:45 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ Interesting take for next year.  A bit of a Macro look with some sector talk as well.  https://www.cnbc.com/video/2021/12/22/sp-nasdaq-100-charts-suggest-stocks-could-bounce-in-new-year-trader.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:44:07 </td>
   <td style="text-align:left;"> $SPY $QQQ Next year we probably won’t see over 20% again but I think somewhere between 15 to 17% is very doable with the US economy is expected to grow very strongly next year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:37:51 </td>
   <td style="text-align:left;"> $aapl $msft $qqq https://www.youtube.com/watch?v=1jnfZaEyseE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:36:46 </td>
   <td style="text-align:left;"> $SPY $QQQ Merry Christmas all. It is gonna be a great season with all the money that the bulls are making, not so much for the bears I guess lol and this trend likely will continue for Year 2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:36:24 </td>
   <td style="text-align:left;"> $btc.x $eth.x $qqq $spy https://www.youtube.com/watch?v=b9ymJ9bUAtk&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:35:55 </td>
   <td style="text-align:left;"> $tsla $qqq $SPY  https://www.youtube.com/watch?v=ViWBBJtayzg&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:34:06 </td>
   <td style="text-align:left;"> $DIA $SPY $QQQ ., </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:34:03 </td>
   <td style="text-align:left;"> Have a wonderful safe/healthy holiday season Followers and SpudZone premium members! Love ya guys, it&amp;#39;s been ONE HELL OF A YEAR trading... Remember to not be greedy, take all experiences as a learning experience. We&amp;#39;ve been beyond blessed this year, the global indexes has nailed almost 30% 5x what a normal year would be. Can&amp;#39;t wait too tackle 2022! Trading these names has been very lucrative all year! $TSLA $DWAC $UPST $AFRM $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:32:56 </td>
   <td style="text-align:left;"> $DIA $SPY $QQQ , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:31:42 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Preliminary option volume of 35.4M today is 13% below recent average. Calls led puts 22.55M to 12.83M </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:26:20 </td>
   <td style="text-align:left;"> $QQQ Merry Christmas to all ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:26:13 </td>
   <td style="text-align:left;"> $QQQ  
 
QQQ vs. Blue Chip Growth Mutual Funds? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:24:49 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Closing imbalance = ~$547M to the BUY side </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:24:30 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM Lightened up some positions this week in $LABU and $BULZ. Wouldn&amp;#39;t be surprised to get some nasty headlines with covid cases over the holiday weekend worldwide as people gather. All indices have finished the week well above their 10/20 SMA so we may get a slight pull back early next week before coiling for more upside. Happy Holidays! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:23:52 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Market momo &amp;amp; activity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:23:09 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Fear &amp;amp; Greed Index </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:22:46 </td>
   <td style="text-align:left;"> $MMAT $SPY  $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:22:44 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA $VIX Economic calendar for w/o 12/27 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:22:10 </td>
   <td style="text-align:left;"> $QQQ $SPY let me guess you guys bought puts looking at the close? Perfection. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:21:42 </td>
   <td style="text-align:left;"> What do you think of this? $QQQ&amp;#39;s price moved above its 50-day Moving Average on December 21, 2021. View odds for this and other indicators: https://srnk.us/go/3264318 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:21:01 </td>
   <td style="text-align:left;"> $SPY $QQQ $SPY  weekly P&amp;amp;L just 3000 Merry Christmas everyone expecting a haircut to start the week next week that close was relatively bearish spy has to hold 470 here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:18:07 </td>
   <td style="text-align:left;"> $SPY $QQQ that close ruined a bunch of degenerate gamblers Christmas. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:17:28 </td>
   <td style="text-align:left;"> $SPY $QQQ S&amp;amp;P with ATH close.  Why is anyone surprised…all these markets do is go up.  

We know that next year at this time the S&amp;amp;P will be 25% higher.   It’s our way of life. 🤷‍♂️

Double bottom, bounce off 100dma.  💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:15:01 </td>
   <td style="text-align:left;"> $SPX … ⚠️ Closed ATH ⚠️

$QQQ $SPY $IWM $DJIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:14:00 </td>
   <td style="text-align:left;"> $QQQ may break out. Our analyzer suggests a buy stop @404.01 with a stop @385.95 as a possible low risk setup.. https://www.chartmill.com/stock/quote/QQQ/technical-analysis?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:11:40 </td>
   <td style="text-align:left;"> $SPY $QQQ thx for the mini dip, turkeys. next few weeks will melt your face </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:10:36 </td>
   <td style="text-align:left;"> $SPY $QQQ market can get back to rate hike talk...and a talked-about hike in January.  powell better hope for a lockdown and more PPP loans instead. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:10:03 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $IWM I own 2 $467 12/27 SPY puts and 1 QQQ $391 12/27 put. We’ll see who’s an idiot after all. No…surely not the puts that had 5,000 volume. Maybe I should of bought the $175 AAPL call with 100,000 volume and 100,000 open interest on the 12/31 option chain. OH I FORGOT!!!!! Everything Jim Cramer actually happens!!!! He’s calling for the Santa rally!!! 🤣😂😂🤣😂🤣😂🤣I love taking advantage of other peoples greed. You really think the markets that sweet huh??? LOLLLL (still long on month long swings, I just wanted to cash in on some Putz… looks like Monday is a face ripper) GG bulls. 🎯🕺 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:09:01 </td>
   <td style="text-align:left;"> $QQQ bears got smacked across the board this week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:07:58 </td>
   <td style="text-align:left;"> $Spy $qqq $dia $iwm
Congratulations BULLS.
More ATH next week till we reached the target $spx 4866 by year end $$$$
Happy Holidays! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:07:28 </td>
   <td style="text-align:left;"> $NVDA $QQQ latex7dd67e2e561c82dda8642ff1631297d1$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:05:46 </td>
   <td style="text-align:left;"> Rule 24F-2 notice https://www.conferencecalltranscripts.com/summary/?id=10261035 $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:04:57 </td>
   <td style="text-align:left;"> $QQQ It was a great day today! See ya&amp;#39;ll on Monday!! Happy Holidays to all!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:04:56 </td>
   <td style="text-align:left;"> $SPY $QQQ 🔥🔥🔥🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:04:28 </td>
   <td style="text-align:left;"> $SPY $QQQ $NQ_F hope you got the warning.  very nice short at the end of day... trade lasted minutes.  
algos are the sharks and they picked off the puts then the calls. shrug. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:04:19 </td>
   <td style="text-align:left;"> $SPY talk about slamming shut at the close $QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:04:09 </td>
   <td style="text-align:left;"> $QQQ 📜 SEC Form 24F-2NT filed by Invesco QQQ Trust, Series 1

https://quantisnow.com/insight/2181114?s=s

45 seconds delayed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:03:47 </td>
   <td style="text-align:left;"> $MSFT $AAPL $AMZN $QQQ have a great long weekend! Merry Christmas 🎄🎁 🍷

Msft was to be pinned below 335 … we gap up on Monday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:03:26 </td>
   <td style="text-align:left;"> $QQQ Form 24F-2NT (rule 24f-2 notice) filed with the SEC 

https://newsfilter.io/a/16327b60af8c1331033f520e7331311f </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:03:19 </td>
   <td style="text-align:left;"> $SPY $QQQ lol! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:02:16 </td>
   <td style="text-align:left;"> $QQQ another 20% up in 22 💰🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:02:04 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA  don’t be too greedy. Hope you’ve secured some profit today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 05:01:29 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA seems like bears’ kids are getting nothing for christmas </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:59:41 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ Amazing day! Merry Christmas to all! And to all a good night! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:59:35 </td>
   <td style="text-align:left;"> $QQQ mvoed up on literally no volume </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:59:31 </td>
   <td style="text-align:left;"> $SPY $QQQ lol no one wants to hold over the weekend.. only pigs will </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:58:28 </td>
   <td style="text-align:left;"> $QQQ will wait for it to come down to the 20-50MA before touching it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:58:00 </td>
   <td style="text-align:left;"> $QQQ hedging my tqqq shares last minute… pussies didn’t ramp it into the close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:57:56 </td>
   <td style="text-align:left;"> $SPY THE BULLS ARE FUCKED HOLY SHIT HOLY SHIT $IWM $AAPL $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:57:23 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:57:21 </td>
   <td style="text-align:left;"> $SPY $SPX $DIA $DJIA $QQQ -----

We don&amp;#39;t , you idiot .....

https://www.yahoo.com/news/wright-family-attorney-potter-trial-215540452.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:57:08 </td>
   <td style="text-align:left;"> $SPY $QQQ end of month end of quarter damping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:56:05 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:55:46 </td>
   <td style="text-align:left;"> is that you #SantaClaus Rally ???? 
$SPY $ES $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:54:55 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM Due to COVID news bought puts! Best of luck and happy holidays. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:54:45 </td>
   <td style="text-align:left;"> $QQQ shitty algos, next week the same </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:54:09 </td>
   <td style="text-align:left;"> $QQQ okay I sell my calls here.  Woo easy money.  Still extremely bullish on $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:54:01 </td>
   <td style="text-align:left;"> $SPY $QQQ this is fackin disgusting now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:53:46 </td>
   <td style="text-align:left;"> $ROKU $270c Jan expirations printed. Hedged with deep ITM put at $280. See y’all later this weekend. Happy holidays!!  Don’t forget. Sept 500c $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:53:40 </td>
   <td style="text-align:left;"> $SPY $QQQ the ladder $NQ_F is insane right now, sharks feeding on seals.

a DAMP end of the day is looking very likely (when the ladder spreads get too wild, not a good sign for stability </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:52:20 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA absolutely disgusting strength </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:52:19 </td>
   <td style="text-align:left;"> $QQQ bears?? Are you okay?!?!?!?!?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:51:57 </td>
   <td style="text-align:left;"> $SPY $QQQ In other words, the British have &amp;quot;discovered&amp;quot; what South African experts have been telling them for the last month.

https://youtu.be/bhFjHqRPkTg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:51:50 </td>
   <td style="text-align:left;"> $IWM I’ve been very accepting of how the world has reacted to Covid until Omicron.  Absolute hysteria machine cranked up as Biden spits up on himself.  It makes me laugh and infuriates me at the same time.  Weird stuff. $DIA $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:49:19 </td>
   <td style="text-align:left;"> @Vol888 @MZel @ponderevo @RosannaTrades Enjoy the much needed rest, from all of our important decisions, over the holiday weekend! We need everyone back and well rested to determine the ramifications of $SPY and $QQQ heading to the moon on our return. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:49:15 </td>
   <td style="text-align:left;"> $SPY $QQQ $NQ_F that was my final long scalp of the day, on a very easy momentum push.
watch out. indeed algos are clearing out the puts that accumulated during the last 3 hours (remember the momentum is dead post?)
once that is done, calls are accumulating on this rise and algos could shake the entire tree back down hard.

watch out! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:48:28 </td>
   <td style="text-align:left;"> $QQQ so we break the down trend ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:48:12 </td>
   <td style="text-align:left;"> $QQQ imagine it hits 400 lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:48:08 </td>
   <td style="text-align:left;"> $QQQ $SPY $DIA a retail trap? Sounds to good to be true. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:48:07 </td>
   <td style="text-align:left;"> $QQQ Greedy mother fucking 🐖. People celebrating unhealthy movement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:47:13 </td>
   <td style="text-align:left;"> $QQQ lol. Almost too easy scary! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:46:24 </td>
   <td style="text-align:left;"> $QQQ told ya! Just about to hit daytime highs baby! I love the stock market! It’s so predictable! Yes sir! These United States of America have some of the finest quality stonks known to man. Step right up by one by all!!!!  Some real good old American bargains right here people. Don’t lose out! FOMO! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:45:50 </td>
   <td style="text-align:left;"> On the Week 

 DJIA is up 1.8%, the S&amp;amp;P 500 (+2.4%), NAS Comp  (+3.3%), and Russell 2000 (+3.2%).

$DIA $SPY $QQQ $RUT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:44:26 </td>
   <td style="text-align:left;"> $SPY I’m waiting for one more small green candle for monday and we’ll see. No positions yet. Happy holidays all!
$QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:44:11 </td>
   <td style="text-align:left;"> $QQQ History lesson coming 1929 I wonder? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:43:03 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA S&amp;amp;P 500 (SPY) Technical Analysis, Forecast, and Trade Ideas: 
https://www.youtube.com/watch?v=u5M2GdO0ysM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:42:44 </td>
   <td style="text-align:left;"> $QQQ nothing but buys until 4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:42:21 </td>
   <td style="text-align:left;"> $QQQ Melt up through year end and into Jan </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:42:12 </td>
   <td style="text-align:left;"> Are you aligning your long term goals with the way you currently trade/invest?

What I mean by this, is if you want to make BIG money, then you have to trade like big money trades/invests. 

So I always ask myself: &amp;quot;would big money do something like this?&amp;quot;

Guys like Paul Tudor Jones, Richard Dennis, Jerry Parker etc etc. 

Would guys like this..

- be day trading or scalping on the 15min chart?
- follow &amp;quot;unusual options&amp;quot; activity?
- use a chart pattern they read in a book that was written by a guy who&amp;#39;s probably never made a dime in the market?
- give a shit about what anybody on CNBC etc says?
- Would these guys even touch weekly options?

So if they wouldn&amp;#39;t do it, then why would I? Why would you?

If your goal is to put your kids through college and take nice vacations, then sure you can do those things 

But if you&amp;#39;re like me and the ultimate goal is to change the world and make billions, then you&amp;#39;re not going to do those things 

$SPY $SPX $QQQ $DIA $VIX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:41:05 </td>
   <td style="text-align:left;"> $QQQ huge V into close lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:40:39 </td>
   <td style="text-align:left;"> $QQQ too high.!!  3 days up?? seriously??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:40:23 </td>
   <td style="text-align:left;"> $QQQ new ath by eoy? 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:39:16 </td>
   <td style="text-align:left;"> $SPY MOC 362 million buy side $iwm $qqq $djia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:39:12 </td>
   <td style="text-align:left;"> $QQQ they have zero shame. I hope when powell end up being miserable in the future. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:39:00 </td>
   <td style="text-align:left;"> $TSLA Next week the shock and awe ripper to all time highs $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:38:55 </td>
   <td style="text-align:left;"> Stocks rise on Wall Street, indexes head for weekly gains $SPY $DJIA $QQQ https://www.billionaireclubcollc.com/stocks-rise-on-wall-street-indexes-head-for-weekly-gains/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:36:38 </td>
   <td style="text-align:left;"> $QQQ Sell off hard next week when volume is back.  I mean just think of the last week but like 3 times. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:36:20 </td>
   <td style="text-align:left;"> $QQQ I don’t care how healthy a pullback is. Keep going! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:35:24 </td>
   <td style="text-align:left;"> $QQQ $396.78 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:34:13 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:33:31 </td>
   <td style="text-align:left;"> $AMC maybe y’all should of invested in the $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:32:45 </td>
   <td style="text-align:left;"> $tsla $qqq $spy https://www.youtube.com/watch?v=ViWBBJtayzg&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:32:27 </td>
   <td style="text-align:left;"> $btc.x $eth.x $spy $qqq https://www.youtube.com/watch?v=b9ymJ9bUAtk&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:31:44 </td>
   <td style="text-align:left;"> $fb $googl $qqq https://www.youtube.com/watch?v=xD9Nu_487sQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:29:58 </td>
   <td style="text-align:left;"> $QQQ $CRTX Power to the players... $14 today? lets see... added more here... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:27:48 </td>
   <td style="text-align:left;"> $CCL $SPY $QQQ $JD $FB Fully vaxxed and boosted Cruise Ship has COVID outbreak. Same with fully vaxxed Cornel University and fully vaxxed Sen.Chris Coons, 7 staffers AND “114,318 fully vaxxed people have tested positive for the virus in Massachusetts… and Vax required  “NYC spread rates soar to record levels”   … https://youtu.be/CUDVuugQmxE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:25:45 </td>
   <td style="text-align:left;"> $QQQ Santa left boys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:22:50 </td>
   <td style="text-align:left;"> $QQQ gay </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:19:41 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA 
Loving the willingness to have the market stay up…. Good job bulls

Merry Christmas and good luck Monday for the
“Santa Clause Rally” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:19:27 </td>
   <td style="text-align:left;"> Per Stock Trader&amp;#39;s Almanac: &amp;quot;Santa Clause Rally Beings December 23rd&amp;quot; $SPY $SPX $QQQ $VXX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:18:00 </td>
   <td style="text-align:left;"> $SPY $QQQ declining volume past 3 days just means there’s a lot of money on the sidelines waiting to buy next week.  🤷‍♂️😳😬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:16:59 </td>
   <td style="text-align:left;"> $QQQ only up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:14:32 </td>
   <td style="text-align:left;"> $QQQ we need to go down!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:14:18 </td>
   <td style="text-align:left;"> $BTC.X SANTA IS STOPPING AT BITCOIN TO CONTINUE THE SANTA RALLY AFTER THE MARKETS ARE CLOSED $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:12:54 </td>
   <td style="text-align:left;"> $SPY So now the question becomes do we have enough PMs chasing performance to not have the Market dip next week after this pull forward?

That is the question 

$aapl $amzn $qqq $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:12:31 </td>
   <td style="text-align:left;"> $QQQ oh no it dropped 40c such a great buy opportunity, also let’s turn the printers back on, otherwise hedge fund managers can’t buy their 4th yacht </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:11:42 </td>
   <td style="text-align:left;"> $UPH $qqq I&amp;#39;m predicting $5 this year before ER in early Feb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:10:19 </td>
   <td style="text-align:left;"> $QQQ Can we head down please? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:09:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X $TSLA 

😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:08:48 </td>
   <td style="text-align:left;"> $QQQ so weird. Pick up or down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:07:08 </td>
   <td style="text-align:left;"> $QQQ triple top today at 398? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:06:14 </td>
   <td style="text-align:left;"> $QQQ they just won&amp;#39;t let it drop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:06:09 </td>
   <td style="text-align:left;"> ETF Sentiment: $QQQ is the #2 ETF that institutions are trading with 39.6K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:05:45 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM  past couple of days there’s a rip at the EOD. Be careful when shorting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:04:30 </td>
   <td style="text-align:left;"> $QQQ lol boom! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:04:03 </td>
   <td style="text-align:left;"> $QQQ so annoying I was day trade shorting this right now and I sold  cause it kept going higher only to fall like I wanted it to. F you bulls and your ignorance </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:04:01 </td>
   <td style="text-align:left;"> $QQQ what a joke. Nice head fake. Do you think this is selling off towards close? Bullshit. you have another thing coming.  Guaranteed this works its way all the way back up and flirts with a $400 close. After all, these are stonks and we have the best retailers in the world thinking this over price piece of shit is worth something. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:03:39 </td>
   <td style="text-align:left;"> $QQQ major covid restrictions expected next week starting from Europe after the Christmas. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:02:53 </td>
   <td style="text-align:left;"> $QQQ did the printer run out of ink? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 04:02:37 </td>
   <td style="text-align:left;"> $QQQ now we get the sell-off before long weekend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:59:59 </td>
   <td style="text-align:left;"> $QQQ $spy STONKS ONLY ROCKET UP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:58:55 </td>
   <td style="text-align:left;"> $QQQ  $SPY $DIA $META Im a bull and have been in the market for ovr 20 years, just what is concerning me is the days of Greenspan whenhe used to raise rates and the market kept going down, I know the internet bubble had alot to do with this but is this an ongoing concern, since the fed probably wont print any more and raise rates. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:56:21 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA &amp;gt;&amp;gt; Split Open &amp;amp; Melt 🐟🐠🐡

The Christmas 🎄 Melt-Up 🤑

https://open.spotify.com/track/2YKSgzOabJDgDzSmy8R5dy?si=xodODXgeSVeejIEHGmTExA&amp;amp;utm_source=copy-link </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:56:05 </td>
   <td style="text-align:left;"> $QQQ stair stepping all week. Nothing too crazy but looking more healthy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:56:05 </td>
   <td style="text-align:left;"> $QQQ and for certain shortly those 398 calls should start paying, insane. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:55:08 </td>
   <td style="text-align:left;"> $QQQ big boys gunna do the old pull on y’all $crwd $tsla for the long awaited weekend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:53:02 </td>
   <td style="text-align:left;"> $QQQ close at 16,400👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:52:02 </td>
   <td style="text-align:left;"> $QQQ let’s go bulls break to 398+ right now! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:51:48 </td>
   <td style="text-align:left;"> $SPY $QQQ Who’s gonna have withdrawal symptoms from a closed market tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:51:09 </td>
   <td style="text-align:left;"> $QQQ seemed ridiculous yet here we are </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:51:01 </td>
   <td style="text-align:left;"> $QQQ puts printing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:50:36 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM It’s weird lots of stocks not participating in this rally. It’s only the big dogs! Something to keep in mind for next week. In cash enjoying the views. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:49:35 </td>
   <td style="text-align:left;"> $QQQ time to go back to $350 you dumb whore </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:49:19 </td>
   <td style="text-align:left;"> $SPY $QQQ weekly engulfing candle.  SPY/Q’s haven’t had back back to green weeks in 2 months.   

We going to get that to end the year?  🙏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:48:33 </td>
   <td style="text-align:left;"> &amp;quot;Deflation Not Inflation is Risk Says Cathie Wood&amp;quot;

 https://channelchek.com/news-channel/Deflation_Not_Inflation_is_Risk_Says_Cathie_Wood… 

$SPY $BTC.X $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:47:20 </td>
   <td style="text-align:left;"> $QQQ $SPY remember to be nice to your mothers this weekend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:46:25 </td>
   <td style="text-align:left;"> $QQQ easy 🥱 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:45:11 </td>
   <td style="text-align:left;"> $QQQ Will you STOP BTFD so this can die like it should. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:44:23 </td>
   <td style="text-align:left;"> $QQQ how the hell can this thing just keep on going up???? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:43:54 </td>
   <td style="text-align:left;"> $QQQ wtf????? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:41:50 </td>
   <td style="text-align:left;"> $JD Are we finally approaching a time to get into China at these low prices? This guy&amp;#39;s video does a good job examining it all. $TCEHY $ARKK $QQQ https://youtu.be/zgCVn5vJSS0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:39:54 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:39:36 </td>
   <td style="text-align:left;"> $SQQQ $TQQQ $QQQ $SPY  Forward and Reverse splits coming on 2/12/2022 - $TQQQ = 2 for 1 Forward Split,   $SQQQ = 1 for 5 Reverse Split - </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:37:39 </td>
   <td style="text-align:left;"> $QQQ $SPY unbelievable rally, over 6% in 3 days. Fed tapering 
From 90 to 60 Billion per month happens from Jan 3rd or Jan 15th.
Look like this won’t go down till tapering is completed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:36:49 </td>
   <td style="text-align:left;"> $QQQ Bitcoin squeeze? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:36:20 </td>
   <td style="text-align:left;"> $SPY $QQQ This is a tough spot for most families. Savings rate is plunging while the CPI just broke to the upside. #Volker </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:31:52 </td>
   <td style="text-align:left;"> $QQQ so market close tomorrow right ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:31:05 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM Shorts should step aside so bulls can push this to ATH’s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:29:02 </td>
   <td style="text-align:left;"> $QQQ 1 more rip please eod </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:28:23 </td>
   <td style="text-align:left;"> $SPY $QQQ at least 50% of the NFL has tested positive for Covid. May the fantasy gods help us during this time... oh, and yeah, lets not act like this illness wont slow our expected growth. How dumb are we to keep this ripping? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:22:52 </td>
   <td style="text-align:left;"> $QQQ people forgot all about the hawkish JPow. Crazy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:22:43 </td>
   <td style="text-align:left;"> $QQQ Put buyers should rather stick to reverse leveraged QQQ and let us bulls push this to higher highs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:22:38 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $DIA $SMH … Happy Holidays to all bears 🐻 &amp;amp; bulls 🐃

May the gods bring us more gains in HEALTH &amp;amp; WEALTH next year 🙏🏻

🥂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:22:34 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM I love how people are like “ADMIT YOU WERE WRONGGGGGGGGGG” lol I’m frequently wrong. But I’ve had a pretty good week. Made good money being long all week by buying the dip on Monday on Small caps and retail. Banked on my VXX shorts as volatility has dropped nearly -50% in one week. My IWM small caps Long has gone straight up. My XRT retail play has gone straight up…. I like how people want to make fun of me and call me an idiot because I was wrong on a $50 swing play. It’s okay guys…I got thick skin. 🤙 keep calling me an idiot I guess. 🤷‍♂️ I love being reminded that I’m a loser who lives with his mom at 28. Yes I have a job… I was in a very bad car accident so I’m frequently missing work because I’m having surgeries and procedures and I’m constantly in lot of pain. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:21:51 </td>
   <td style="text-align:left;"> $QQQ  Lower Highs Lower Lows </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:21:42 </td>
   <td style="text-align:left;"> $QQQ Merry New Year! Hahahahah. Santa rally….engage. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:19:07 </td>
   <td style="text-align:left;"> $SPY $QQQ The Santa Claus rally is officially here and we are heading higher into end of the year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:19:02 </td>
   <td style="text-align:left;"> $SPY $QQQ probably missed hours of fine posting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:18:28 </td>
   <td style="text-align:left;"> $QQQ stocks only go up I guess </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:17:55 </td>
   <td style="text-align:left;"> $QQQ learned again that stock only goes up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:17:44 </td>
   <td style="text-align:left;"> $SPX making a new high 🏇 🏌️‍♂️ 
$SPY $DJIA $STUDY $QQQ #STOCKCHART 
( Using chart program Pro ☞ https://tinyurl.com/y32cywz4 ) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:17:21 </td>
   <td style="text-align:left;"> $SPY $QQQ WHAT A DIP BUY!!!!  Couldn’t pass that up!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:17:18 </td>
   <td style="text-align:left;"> $SPX $SPY $QQQ $DIA 

This century will go down in history

as the one that began with great decadence and debauchery 

as the one that ended in absolute decay and destruction. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:17:08 </td>
   <td style="text-align:left;"> $QQQ getting to overbought on multiple timeframes and breadth is weakening. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:16:48 </td>
   <td style="text-align:left;"> $QQQ pullback you fat pig. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:14:47 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM Anyone holding calls or puts over the 3 day weekend? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:14:21 </td>
   <td style="text-align:left;"> $QQQ look at the volume. This is dipping under $390 next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:14:15 </td>
   <td style="text-align:left;"> $QQQ let&amp;#39;s be honest -- the level of fear at 377 and the level of pure joy right now is truly ridiculous.  remember none of you schmucks know the next 10% so just give up the ghost if you try to trade on the short side. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:13:03 </td>
   <td style="text-align:left;"> $QQQ has an excellent technical rating and also presents a decent setup pattern. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:11:33 </td>
   <td style="text-align:left;"> $AMC $QQQ matrix will bring other movies collection too .. people some time dont get a ticket .. amc will surprise you on monday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:10:17 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $AMD

$1k -&amp;gt; $1m Options challenge update

Day 12

Initial: $1,000
Current: $6,865 (586%+)
Goal: $1,000,000 Feb-March ‘22

Today was slow on the challenge front, didn’t take any trades as there weren’t perfect setups on SPY like we would’ve liked due to low volume and an overall drift day. 

However, we had some nice calls on AMD and $IWM today and closed out various long call positions on SPY for 150-300% heading into the holiday break.  

Sold long UVXY puts for profits too and heading into the break with cash ready to continue to trudge up to $1m baby.

More info on joining: https://the-band-trades.square.site/

Merry Christmas, and stay safe! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:09:16 </td>
   <td style="text-align:left;"> $QQQ can’t this pos do something </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:08:56 </td>
   <td style="text-align:left;"> $BTC.X I feel like this is lots of retail buying and whales selling apposed to the other way around. That always ends well. Maybe Cramer is encouraging buying, that always ends well. Let&amp;#39;s pamp. $ETH.X $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:07:37 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ SPX at all time highs and testing the top of one fugly megaphone.  This market is retarded.  A solid place to open shorts but it&amp;#39;ll probably just slice through to the upside yet once again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:07:09 </td>
   <td style="text-align:left;"> $QQQ no dips? Seems totally normal and not manipulated </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:07:03 </td>
   <td style="text-align:left;"> $AMZN how can the $QQQ and the $SPY rip and $AMZN just hanging out like nothing to see. Rest of the market is banging when’s gonna be our time? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:06:41 </td>
   <td style="text-align:left;"> $AMC $QQQ $SPY Omicron pffff </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:05:55 </td>
   <td style="text-align:left;"> $QQQ are we going to break 398?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:02:59 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM ATH’s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 03:02:02 </td>
   <td style="text-align:left;"> $QQQ why’s iv so high? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:59:49 </td>
   <td style="text-align:left;"> ELON GIVE US A CHRISTMAS TWEET WE LOVE YOU $TSLA $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:58:53 </td>
   <td style="text-align:left;"> $QQQ i want 396 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:58:44 </td>
   <td style="text-align:left;"> $BTC.X $ETH.X The fundamentals are so wildly in favor of digital assets right now it’s insane $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:57:15 </td>
   <td style="text-align:left;"> $QQQ Getting awfully toppy/overbought watch for the end of day rug pull </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:56:18 </td>
   <td style="text-align:left;"> $QQQ  Breaking 400 for Christmas </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:56:16 </td>
   <td style="text-align:left;"> $tsla Premiums INCREASING here means POP COMING $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:54:51 </td>
   <td style="text-align:left;"> $tsla over 1070 = simply mind bending insane christmas bonuses for all traders $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:54:46 </td>
   <td style="text-align:left;"> $QQQ bears losing their shirts just in time for Christmas 🥶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:53:31 </td>
   <td style="text-align:left;"> POWER HOUR WILL BE INSANE santa claus come early and hes driving a $tsla not a sleigh

$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:53:28 </td>
   <td style="text-align:left;"> $SPY latexe3c097dee6454bed68c912d0b882bcfa$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:52:42 </td>
   <td style="text-align:left;"> $SPY I JUST GOT MARGIN CALLED HOLY FUCK MAYDAY MAYDAY $QQQ $AAPL $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:52:09 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ market is absolutely nuts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:51:32 </td>
   <td style="text-align:left;"> 50% off of @TrendSpider amazing chart software. Help support my site by signing up via my affiliate link below!

$SPY $QQQ  $STUDY $LCID $FUBO
All the details about the software
👇
https://www.chartlearning.com/2021/11/trendspider-stockchart-software-sale.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:50:56 </td>
   <td style="text-align:left;"> $QQQ option killer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:50:40 </td>
   <td style="text-align:left;"> $SNAP Santa really is here thru NYE $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:50:28 </td>
   <td style="text-align:left;"> $QQQ short squeeze til EOY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:50:06 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $IWM Because…reasons, I guess. 🤷🏻‍♂️ What a fabulously fake world we live in now. I’m about ready for the Rapture now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:49:44 </td>
   <td style="text-align:left;"> $QQQ guys if youve been following me get short on the nasdaq now for a hedge at the least. Im 65% net short now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:49:32 </td>
   <td style="text-align:left;"> $QQQ markets never look bad at the top </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:49:07 </td>
   <td style="text-align:left;"> $SPY $QQQ $ETH.X 

“There is also, as Keynes observed, “a peculiar zest in making money quickly.” Emulation and envy are powerful stimulants, and the desire to keep up with the Joneses often fuels herd behavior. The economist Charles Kindleberger wryly noted that “there is nothing so disturbing to one’s well-being and judgment as to see a friend get rich,” and the prospect of easy money on the stock exchange inevitably encourages others to venture their hand. Indeed, during booms the more cautious among the investment community are often castigated for their lack of entrepreneurial zeal.”

- The Apostle Maynard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:48:43 </td>
   <td style="text-align:left;"> $QQQ Needs confirmation but there is a hanging man forming on the 30 minute. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:47:08 </td>
   <td style="text-align:left;"> $QQQ this is just hanging out at this point </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:47:06 </td>
   <td style="text-align:left;"> $SPY $SPX $DIA $DJIA $QQQ ----

While we are obsessed with baseball, basketball, football, political correctness, LGBTQST++ talk, abortions, vaccines, twitter, tiktok, Sleepy Joe, Orange Clown and dumb Kamala,   it is refreshing to see a people focused on scientific education and hard work to kick the ass of the USA in all fronts, including space technologies (read supersonic ballistic missiles which we cannot intercept) and old alliances.  Even the Saudis are abandoning USA and joining China.  In the meantime all the rich Taiwanese are moving to Vancouver and West Coast since they know that USA is just talk and cannot protect Taiwan against China.

Don’t forget to buy all your China-made gadgets and gifts in time for Christmas.  LOL 

https://www.cnn.com/2021/12/23/politics/saudi-ballistic-missiles-china/index.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:46:58 </td>
   <td style="text-align:left;"> $spy $qqq $dia $iwm
I am not considering selling any shares or calls yet, till my target 🎯 achieved. 
As I believe S&amp;amp;P500 is headed for 4833/4850 next week. 
Good luck traders.
Merry Christmas 🎄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:44:31 </td>
   <td style="text-align:left;"> $HOOD taking some profits out here and will evaulate the weekend events in the world. Taking a short on $QQQ as i feel some market needs to pullback monday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:43:54 </td>
   <td style="text-align:left;"> $QQQ if this can clear 401.19, we will be looking at ATHs. Needs daily consolidation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:42:33 </td>
   <td style="text-align:left;"> $QQQ eh screw it I&amp;#39;ll buy 200 shares and 10 calls here.  31/400C  lets goooo!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:42:13 </td>
   <td style="text-align:left;"> $QQQ - the $400 level has been difficult to close above. Approaching that level. $QQQ could be ATH on a close above $400. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:40:54 </td>
   <td style="text-align:left;"> $QQQ sitting at 11,000 feet making money on vacation is fun, </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:39:48 </td>
   <td style="text-align:left;"> $QQQ hold u sob </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:39:42 </td>
   <td style="text-align:left;"> $APP Applovin such a great value here as it grew top line over 90 percent and  trades at a forward multiple of around 60 well below its growth rate.  APP is going to be a behemoth imo and has huge upside from here imo $QQQ $SPY $DJIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:37:25 </td>
   <td style="text-align:left;"> $QQQ Buy PUT nowwww🛑🛑🛑🛑🛑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:37:16 </td>
   <td style="text-align:left;"> $QQQ still on track (weekly tech futures) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:37:10 </td>
   <td style="text-align:left;"> $SPY $QQQ to buy in this market you don’t need a dip. Just open up your broker and buy. It’s that easy and mindless. And it works pretty much 100% of the time too! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:36:34 </td>
   <td style="text-align:left;"> $SPY $QQQ Brandon and Santa are sending this baby to the stars 😲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:36:34 </td>
   <td style="text-align:left;"> $QQQ hey bears - when&amp;#39;s the dump?  i&amp;#39;ve been waiting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:36:04 </td>
   <td style="text-align:left;"> $QQQ $420 for new year 🙌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:35:05 </td>
   <td style="text-align:left;"> $QQQ used that ramp to exit my calls for a 34 percent gain. Very close to my $398 call hit $397.95. Could ramp into close but I’m good exiting here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:34:56 </td>
   <td style="text-align:left;"> $SPY $QQQ Bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:33:58 </td>
   <td style="text-align:left;"> $SPY BULLS ARE TRAPPED IN EUPHORIC MODE, THE SAME MODE THE ALGO WANTS TO INDUCE U IN. THERE IS NO SANTA RALLY. THEY HAVE 3 DAYS AND ALL IT TAKES IS ONE BAD HEADLINE FOR MARKETS TO RUGPULL BEFORE U EVEN HAVE THE CHANCE TO SELL. EUPHORIC BULLS AND THE RETAIL FLOCK BEING LED TO THE SLAUGHTER HOUSE LIKE CLOCKWORK $IWM $QQQ BUY MORE CALLS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:33:40 </td>
   <td style="text-align:left;"> $QQQ Let’s See $400! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:32:55 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X 

&amp;quot;When a hundred men stand together, each of them loses his mind and gets another one&amp;quot; - Friedrich Nietzsche </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:32:35 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:31:28 </td>
   <td style="text-align:left;"> $QQQ Pandemic is basically over in Wall street </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:31:07 </td>
   <td style="text-align:left;"> $QQQ nhod </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:30:53 </td>
   <td style="text-align:left;"> $QQQ crypto and stock market 📈 bad day for shorts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:30:31 </td>
   <td style="text-align:left;"> $QQQ - Manage risk on QQQ trim some </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:29:57 </td>
   <td style="text-align:left;"> $QQQ higher </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:29:40 </td>
   <td style="text-align:left;"> $SPY $QQQ What just happened to tech? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:29:36 </td>
   <td style="text-align:left;"> $QQQ 🐖 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:29:11 </td>
   <td style="text-align:left;"> $SPY $QQQ I wouldn’t be afraid to hold on to calls for next week. Nothing is going to happen for news and no one is selling anyway. You can be fearful but you’ll get paid guaranteed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:28:56 </td>
   <td style="text-align:left;"> $QQQ there she blows. Off you fuck  bears 🥱 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:27:22 </td>
   <td style="text-align:left;"> $QQQ $NQ_F things could get nutty into close and take out that pesky resistance. Game plan laid out for you earlier this week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:25:22 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA 

UK Health Security Agency says initial data suggests people infected with Omicron are less likely to be hospitalized.

Hopefully Omicron puts an end to the pandemic in the near future! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:24:43 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMC I picked the wrong day to stop sniffing glue </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:23:47 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM My spirit animal. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:23:18 </td>
   <td style="text-align:left;"> $QQQ RSI is in the 88+ for 15 min, 30 min, 1 hr but who cares... Santa is in town. Enjoy the roller coaster ride.

Wonder when the music stops but that&amp;#39;s for another day. lol

All the bad news has already been forgotten and with a low volume surge, Monday will be the rug pull day for $SPY and $QQQ... at least looks that way.  Let&amp;#39;s see what happens... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:21:52 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL $TSLA Video Premier -- goes live in 35 mins! 👇 
Technical Analysis For Beginners  — ULTIMATE GUIDE 📈 Candles &amp;amp; Patterns for Stock Market Investing 
#technicals #charts #chartsforbeginners #candlesticks #investing #trading #stocks $stocks $invest $QQQ $SPY 
 
https://youtu.be/BbNdH06z6Ow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:21:37 </td>
   <td style="text-align:left;"> $QQQ i&amp;#39;m no pro but this looks like it just setup for another breakout </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:21:30 </td>
   <td style="text-align:left;"> $NQ_F $QQQ #Nasdaq #stockmarket #markets #equitymarket #investing #equities #Futures #Trading #swingtrading #marketforecast Recap: Today&amp;#39;s trading report bias+1 bullish sent 12/21/21 8:26 AM (ET) upper target+5 at $16,300 cash high $16,323.75. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:21:20 </td>
   <td style="text-align:left;"> $QQQ I want to see 396 today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2021-12-24 02:20:25 </td>
   <td style="text-align:left;"> $tsla has a MASSIVE leg higher today in it still are you READY!!?! $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 09:46:40 </td>
   <td style="text-align:left;"> $WIMI 🔥🔥The advancements in Virtual reality and Augmented reality are emerging gradually. The future of AR and VR technologies based on holographic display would create growth opportunities for next-generation 3D display in the consumer electronics sector. For instance, in November 2020, a report was released on Google/Amazon’s 3D AR products and WIMI’s 5G + MR head-mounted display products. $GOOG , $AAPL , $MSFT , and WIMI have entered into the VR/AR market.
https://www.digitaljournal.com/pr/3d-display-market-worth-us-2253-23-million-by-2027-exclusive-research-by-the-insight-partners </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 09:45:53 </td>
   <td style="text-align:left;"> $AAPL $185 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 09:40:39 </td>
   <td style="text-align:left;"> As Covid Spreads, So Does Investor Optimism, Pushing Stocks to New Highs  $PFE $MRK $DIS $NFLX $AAPL 

https://newsfilter.io/a/5ff9a21b689aa9aba1bb56940052b355 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 09:37:32 </td>
   <td style="text-align:left;"> Just remember, without idiots and panic sellers of stocks we would never have opportunities like this to  propel our net worths in such a drastic way in a short amount of time. Forget $PYPL forget $TSLA forget $AAPL those have had their run. This is the new play. You wanna beat Wall Street? $BABA is where you need to be. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 09:33:07 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Jim Cramer&amp;#39;s stock market winners and losers for 2021 https://www.stck.pro/news/AAPL/20245096 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 09:19:24 </td>
   <td style="text-align:left;"> $TSLA $AAPL $SPY $BJDX 
Next week also 🎄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 09:13:50 </td>
   <td style="text-align:left;"> $AAPL 350 by 2025 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 09:05:00 </td>
   <td style="text-align:left;"> $AAPL shows a strong growth in EPS: 72.39%.. https://www.chartmill.com/stock/analyzer/stock/AAPL?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 09:04:04 </td>
   <td style="text-align:left;"> $AAPL for all the manipulation to kill those $177.50 so obvious spikes up. &amp;amp; .80 drop in mins lol. They knew if it hit $177 it was def going close over $177.50. Fuck $182 we want $190 by er </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 09:02:09 </td>
   <td style="text-align:left;"> $AAPL That close was epic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 08:57:57 </td>
   <td style="text-align:left;"> $AMD $tsla  $aapl   $NVDA 

New acronym for 2022- TAAN

Tesla, Apple, AMD and Nvidia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 08:57:05 </td>
   <td style="text-align:left;"> $AAPL (Delayed) - $200 next target. Options we suggested up over 114+% 
Those long shares continue to raise stops as your trade works out! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 08:49:22 </td>
   <td style="text-align:left;"> $AAPL 

$185 next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 08:48:35 </td>
   <td style="text-align:left;"> $AAPL loading up next week when I get paid. We like the stock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 08:42:46 </td>
   <td style="text-align:left;"> $AAPL 

adding more shares

$185 EOY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 08:40:46 </td>
   <td style="text-align:left;"> SweepCast alerted: $AAPL with Unusual Options Activity Alerted on $182.5 CALL Expiring: 12-31-2021 worth 26K🐂 |🥇 Check out ➡️ SweepCast.c </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 08:40:38 </td>
   <td style="text-align:left;"> $AAPL I’m back from Mykonos, I see aapl been doing aapl things </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 08:40:02 </td>
   <td style="text-align:left;"> $AAPL Any of my Ohioans in the building???? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 08:39:49 </td>
   <td style="text-align:left;"> $AAPL we passing $180 soon Santa told me!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 08:37:20 </td>
   <td style="text-align:left;"> $AAPL 4Bucks to go! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 08:23:21 </td>
   <td style="text-align:left;"> $AAPL end of your price for Apple December 31, 2020
$180.00 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 08:10:04 </td>
   <td style="text-align:left;"> $AAPL BULL since $140s area ; but short term bear now maybe 182-185 pump again then pull back 💪💪💪. I nailed 20 % since 140s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 08:08:57 </td>
   <td style="text-align:left;"> $AAPL just need +15% to hit the 200 mark! One big day or one big week next week 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 08:02:04 </td>
   <td style="text-align:left;"> $AAPL AAPL 2021-12-23 Trade Analysis Video: 
https://www.youtube.com/watch?v=HAOxkrlNZg4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 08:00:41 </td>
   <td style="text-align:left;"> $AAPL next leg up incoming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 07:54:57 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #2 ticker with sweep activity where institutions are trading options urgently with 126.2K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 07:52:14 </td>
   <td style="text-align:left;"> As I take a break and eat my dinner some good news for u guys hearing the apps $GOOG &amp;amp; $AAPL  for Billionaireclubcollc.com  will be ready for my inspection 🔥🔥🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 07:51:23 </td>
   <td style="text-align:left;"> $MARA does anyone want to sing up for Webull ? Use my link and I’ll cashapp PayPal or venmo u $15 I’m trying to get a share of $aapl 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 07:43:07 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Jim Cramer&amp;#39;s stock market winners and losers for 2021 https://www.stck.pro/news/AAPL/20241489 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 07:41:25 </td>
   <td style="text-align:left;"> $AAPL What day is the Stock Market closed for the Holiday  Jan 1st ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 07:34:44 </td>
   <td style="text-align:left;"> $AAPL Monday could be anyone&amp;#39;s game. max bull play on table 178.5 break that and hold and you possibly start a new trend or squeeze the hell out of shorts and turn apple to 3 trill market cap for a bit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 07:34:08 </td>
   <td style="text-align:left;"> $AAPL In investing, it is important that you look at wealth as your forest. If you do, then you let it grow &amp;amp; cancel out short term headwinds. Invest in Xceptional business for your forest. Bullish on Apple - https://youtu.be/btBGZB5Fak0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 07:33:28 </td>
   <td style="text-align:left;"> $TSLA Elon Claus is coming to town $spy $aapl
Tesla phone cough </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 07:32:56 </td>
   <td style="text-align:left;"> MOVES HAPPENING NOW (6:32pm)

⦿ $AAPL is down 0.0% in the last 5 mins. 

⦿ There are 4 stocks that are up more than 3% in the last 5 mins. 

⦿ The top gainer is up 18.0% in the last 5 mins. 

 See the stocks that are moving the most right now via link in bio (wallstreetodds .com). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 07:30:20 </td>
   <td style="text-align:left;"> $MARA 

Four days ago, I closed on the sale of my sailing catamaran, pocketing a cool $863,000 cash.  

On Monday, I transferred $350,000 of that to my trading account and bought  a few thousand call options for $MARA for March, with strikes of $60, $80, and some hail marys at $125.

Today, at the close, those calls are worth $625,000.

I think I bought the bottom, kids.

Regardless of what BTC does short term, this Santa delivery of new miner news for $MARA is transformative for the future.

You may have laughed when I said last week that $MARA was positioning to become the world&amp;#39;s most important, most valuable company.  Buying now is like buying $AAPL in 1985.  $MARA is as formative to Bitcoin as TCP/IP was to the internet 25-30 years ago.

Now, there&amp;#39;s no excuse.  There&amp;#39;s no question.  You fawning Shillposters of all the also-rans can GFY.  You know to buy and hold, not trade.  

YOU KNOW.  If you trade &amp;amp; get rekt, it&amp;#39;s on you, and we will have zero sympathy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 07:23:50 </td>
   <td style="text-align:left;"> $AAPL Tesla will become 4 trillion before Apple $tsla $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 07:21:07 </td>
   <td style="text-align:left;"> $AAPL yay didn’t end over $177.50 I get to keep my shares 😄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 07:17:27 </td>
   <td style="text-align:left;"> $spy $aapl $msft https://www.youtube.com/watch?v=1jnfZaEyseE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 07:13:08 </td>
   <td style="text-align:left;"> $SMURF 
Canadian markets are opened tomorrow and SMURF (COIN.NE in Canada) will outperform again as the metaverse is getting recognized as the next bubble, bigger than the dot.com or bitcoin 
Long metaverse $AAPL $FB $BTC.X $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 07:10:14 </td>
   <td style="text-align:left;"> $SPY According to my calculations and market sentiment, conditions seem prime to obtain more alpha towards my portfolio through an aggressive, short term strategy. Wow, see how easy is it to sound like you&amp;#39;re smart yoloing options? $TSLA $QQQ $AAPL $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 07:09:31 </td>
   <td style="text-align:left;"> $AAPL already this is paying off after the split had happened. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 07:07:26 </td>
   <td style="text-align:left;"> $DOGE.X $BTC.X $TSLA $AAPL $SPY Sign me up for the backseat of the car preferably the right back seat </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 07:04:00 </td>
   <td style="text-align:left;"> $AAPL has a Return On Assets of 26.97%. This is amongst the best returns in the industry. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 07:02:36 </td>
   <td style="text-align:left;"> $AAPL Loop Ventures predicts that Apple sales will be $10 billion less due to supply chain </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 07:01:48 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ Xmas rally could be over. Dow Jones making a Head and Shoulders pattern. Next week could volatile. $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 06:54:11 </td>
   <td style="text-align:left;"> $AAPL Steve Grasso doubled the price for Apple $350 on Metaverse business </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 06:41:45 </td>
   <td style="text-align:left;"> $AAPL psychopaths all of you for selling afterhours and bidding this down -_-  fortunately I&amp;#39;m home now so my boss can&amp;#39;t yell at me lmao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 06:36:27 </td>
   <td style="text-align:left;"> Apple should be the one that leveraged the meta verse and does it better than anyone else $AAPL $META $SPY CNBC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 06:19:46 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 06:16:33 </td>
   <td style="text-align:left;"> $spy something to always remember when you are Investing in stocks, you must study, do your own DD, &amp;amp; work really, really hard at understanding what you own &amp;amp; also know the history of WS &amp;amp; how no one on Business tv, a stock-board or a Blog knows what will happen.

When Buffett bought $aapl in 2016 people said it was too late &amp;amp; that he missed the best years, Carl Icahn who had spent years pushing $AAPL &amp;amp;  was the man who got Tim Cook to increase Buybacks, spoke to Tim personally &amp;amp; had more info &amp;amp; data then anyone of us will ever hope have &amp;amp; really helped to spark Tim&amp;#39;s  tenure sold $aapl at a price adjusted for stock splits of $28 &amp;amp; its now about to go to $200. His reason was he was worried about China, sound familiar?

WS Pros are not going to be around in 5 years when $baba $jd $pdd etc are higher, the Bears who talk so much crap in the moment are not the ones with vison, they&amp;#39;re just cowards who take the easy way out

Know your Market History! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 06:16:22 </td>
   <td style="text-align:left;"> $AAPL 

Happy Holidays !! 🥳😌😝😋🥰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 06:14:25 </td>
   <td style="text-align:left;"> $HUT bitcoin gonna run into January and ya’ll gonna punch urself for not loading up. latex2655c5391532d9be873c180a52d67aa4NVDA 804k (75% call/25% put)
$AMD 707k (77% call/23% put) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 06:07:18 </td>
   <td style="text-align:left;"> $DOGE.X $TSLA $BTC.X $AAPL $ETH.X Just passing through </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 06:00:52 </td>
   <td style="text-align:left;"> $AAPL right side is bullish on multiple timeframes.  We only like to buy it in 3, 7 or 11 swing at the blue boxes.  Surprises can be to the upside which is why we do not like to sell it.  It is bouncing from a 100% area where algos enter, but we don’t like to chase it.  Like to watch the $NQ_F at equal leg which can giving some sense of timing for larger cap tech.   #Elliottwave #Trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 06:00:12 </td>
   <td style="text-align:left;"> $AAPL 195C Exp:18-Feb-22 ↑↑  🚀 Total(Day): $26,793 
#UnusualActivity 
 
 
Sign-up free for beta ver.:https://app.jarvisalerts.com 
charts: courtesy of finviz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 06:00:08 </td>
   <td style="text-align:left;"> $AAPL 180C Exp:31-Dec-21 ↑↑  🚀 &amp;lt;R&amp;gt; Total(Day): $1,286,196 
$AAPL 185C Exp:07-Jan-22 ↑↑  🚀 Total(Day): $28,200 
$AAPL 185C Exp:31-Dec-21 ↑↑  🚀 &amp;lt;R&amp;gt; Total(Day): $295,718 
#UnusualActivity 
 
 
Sign-up free for beta ver.:https://app.jarvisalerts.com 
charts: courtesy of finviz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:57:47 </td>
   <td style="text-align:left;"> $SPY $AAPL 45 price to book ratio smart ones </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:57:30 </td>
   <td style="text-align:left;"> $SPY $AAPL still trading at 31 PE . . . at ATH profits ... after trillions in federal injection, dogecoin going up 1000%, the speculative money is flowing, for now, but there is a major problem with using your buying power on mediocre/overpriced assets. look, all the revenues you managed to generate from 2000-2016, you will need to triple that to be fairly valued.. think for a second </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:52:32 </td>
   <td style="text-align:left;"> $AAPL The shorts poured cold water on the close at the end but Santa will be well rested on Monday and ready to f*** </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:52:03 </td>
   <td style="text-align:left;"> $SPY lol... Apple just going straight up on their recent earnings.. look kids, $AAPL .. you already paid for those earnings way before they came out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:51:23 </td>
   <td style="text-align:left;"> $AAPL 

Don’t forget Warren Buffett parked his billions of dollars in AAPL …

Imagine same situation if he parked his money at that current price 

What happened, no one would dare to short on Warren Buffett.

That’s same concept .. he already build maximum layers of security against them.

Now he is happy that he is making money. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:44:19 </td>
   <td style="text-align:left;"> $TSLA $AAPL 5 trading days left till eoy. FOMO Monday 

Happy and Healthy Merry Christmas Everyone! Here’s to an amazing 2022 😉🤙🥂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:37:51 </td>
   <td style="text-align:left;"> $aapl $msft $qqq https://www.youtube.com/watch?v=1jnfZaEyseE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:36:19 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $AAPL is the #1 stock that institutions are trading over rolling 5 day window with 583.3K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:33:11 </td>
   <td style="text-align:left;"> Unusual Option Alert on $AAPL $1,695,525 call sweep traded with $175.0 strike expiring on 2021-12-31. Via: https://www.stockgrid.io/optionsflowcumulativestats/AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:33:06 </td>
   <td style="text-align:left;"> $AAPL This better not take a dump on Monday.  Stop driving it down you psychopaths </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:32:50 </td>
   <td style="text-align:left;"> Wow, not every week you see the max pain $AAPL calls expire in the money! Santa gives retail a win! 🍏 🎅 💵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:32:07 </td>
   <td style="text-align:left;"> $AAPL AAPL 2021-12-23 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=DcGgxE75qx4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:29:46 </td>
   <td style="text-align:left;"> Most Active Options for today. $TSLA $AAPL $AMD $NVDA $AMC 

https://www.reddit.com/r/ResearchBasedOnly/comments/rn5uo9/most_active_options_tsla_aapl_amd_nvda_amc_for/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:29:15 </td>
   <td style="text-align:left;"> $AAPL $AMZN $SE $TSLA $AAPL 

Good evening

Swing
12/31 AAPL 177.5 c
1/7 SE 230 c
TSLA &amp;amp; AMZN Shares

Merry Christmas ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:28:56 </td>
   <td style="text-align:left;"> $SPY $DIA $AAPL $BA  How do you guys expect volume to look next week especially compared to today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:26:48 </td>
   <td style="text-align:left;"> Most Active Options $TSLA $AAPL $AMD $NVDA $AMC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:25:36 </td>
   <td style="text-align:left;"> $SPY  Merry Christmas! Enjoy the time off &amp;amp; I hope everyone has done well enough this year to be able to get the GI Joe w/ the Kung-Fu grip!

Cheers!

https://www.youtube.com/watch?v=DF50trbM6aQ

$bb $baba $aapl $JD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:24:36 </td>
   <td style="text-align:left;"> $AAPL &amp;quot;Why AAPL is the BEST PICK for 2022. Come through if YOU are BULLISH on AAPL.&amp;quot; $600+PT

https://www.reddit.com/r/ResearchBasedOnly/comments/rn5qxy/why_aapl_is_the_best_pick_for_2022_come_through/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:23:37 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:18:00 </td>
   <td style="text-align:left;"> $TSLA SEC must ban shorting equities in 2022. Enough is Enough! 
$ARKK  $AAPL $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:17:20 </td>
   <td style="text-align:left;"> $AAPL This will hit 200 first quarter of 2022 with consistent sales! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:16:44 </td>
   <td style="text-align:left;"> $SPY cant wait to btfd when it comes
🚀🚀🤑🤑🤑. $AMD $MSFT $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:16:09 </td>
   <td style="text-align:left;"> $AAPL this will be pent up on Monday and easily hit at all time high next week ; we might see  $190 in this crazy market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:15:21 </td>
   <td style="text-align:left;"> Algorithmic trade idea: Signal generated on $AAPL as a top ticker for sweep activity.

See recent trends and the options contracts institutions are trading in screenshot from https://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:13:35 </td>
   <td style="text-align:left;"> $AAPL gamma squeeze dead. Even tho i was out at 176.34 i really wanted it to hit 177.5 for the bros. But market maker is v comfortable rn and no apple buybacks to help us out. Monday green i ll short </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:10:03 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $IWM I own 2 $467 12/27 SPY puts and 1 QQQ $391 12/27 put. We’ll see who’s an idiot after all. No…surely not the puts that had 5,000 volume. Maybe I should of bought the $175 AAPL call with 100,000 volume and 100,000 open interest on the 12/31 option chain. OH I FORGOT!!!!! Everything Jim Cramer actually happens!!!! He’s calling for the Santa rally!!! 🤣😂😂🤣😂🤣😂🤣I love taking advantage of other peoples greed. You really think the markets that sweet huh??? LOLLLL (still long on month long swings, I just wanted to cash in on some Putz… looks like Monday is a face ripper) GG bulls. 🎯🕺 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:07:28 </td>
   <td style="text-align:left;"> $NVDA $QQQ $AAPL $AMZN RALLY THROUGH END OF YEAR! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:06:39 </td>
   <td style="text-align:left;"> $AAPL         🍏🎄   Absolutely Massive, back to back Shorting, into the Close.  So hard to watch…no way to defend.  Monday Bulls, Monday! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:06:33 </td>
   <td style="text-align:left;"> $AAPL 
WELL WELL WEL!!!

Finish another Trading Before Christmas 🎄 

SINCERELY, I wish wonderful “MERRY CHRISTMAS AND HAPPY HOLIDAYS” 

From @MELBENROSS. 

AllBetterForYou. 
SeeYou. 

Next:Really Santa Rally. $200. 🍏🎄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:05:29 </td>
   <td style="text-align:left;"> $AAPL I’m buying shares every week idgaf what price. It’s fucking apple 🍏 that’s all I’m buying all year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:04:38 </td>
   <td style="text-align:left;"> $AAPL almost got filled for my order and a but disappointing it wasn’t filled at 1.08 when it closed at 1.11. Now got spy 172 12/29 calls filled. Not the ideal play but the backup </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:03:49 </td>
   <td style="text-align:left;"> $AAPL absolutely ridiculous. they can buy any amount they want at any set price they want </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:03:47 </td>
   <td style="text-align:left;"> $MSFT $AAPL $AMZN $QQQ have a great long weekend! Merry Christmas 🎄🎁 🍷

Msft was to be pinned below 335 … we gap up on Monday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:03:46 </td>
   <td style="text-align:left;"> $AAPL if you believe in the voodoo doji.  Could be a sign of reversing or it could be a sign that this was the bears last effort and we go to 178 tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:03:41 </td>
   <td style="text-align:left;"> $AAPL Have a Merry Christmas all and be kind to your fellow humans. See you all next week. The push towards $180 begins. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:03:11 </td>
   <td style="text-align:left;"> $AAPL 800k shares at 176.44 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:03:00 </td>
   <td style="text-align:left;"> $AAPL was analyzed by 48 analysts. The buy consensus is at 83%. So analysts seem to be very confident about $AAPL. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=analyst-ratings&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:02:58 </td>
   <td style="text-align:left;"> $AAPL Calls lost Puts gained! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:02:44 </td>
   <td style="text-align:left;"> $AAPL any one else seeing those massive buys? Over 1M shares </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:02:44 </td>
   <td style="text-align:left;"> $AAPL what the hell is this? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:02:17 </td>
   <td style="text-align:left;"> $TSLA $SPY $NVDA $AAPL  easiest indicator out there </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:02:11 </td>
   <td style="text-align:left;"> $AAPL shorts mofo lol just as expected they hate we are winning.

That’s ok .. we know where they stand .. they want to attack be it on ATH, New Years Eve or whatever.

Anyways I am glad that we are winning .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:02:09 </td>
   <td style="text-align:left;"> $AAPL whenever we go up its takes hours but we drop in seconds lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:01:49 </td>
   <td style="text-align:left;"> $AAPL Manipulating by hedge funds and scum day traders. Hopefully the go home now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:01:38 </td>
   <td style="text-align:left;"> $AAPL She’ll run next week. I’m optimistic. Enjoy your Christmas! 🎄♥️🎄♥️🎊 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:01:07 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : These Health-Tech Deals Highlight a Big Private Investing Trend https://www.stck.pro/news/AAPL/20233831 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:00:56 </td>
   <td style="text-align:left;"> $AAPL lol wtf was that? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:00:52 </td>
   <td style="text-align:left;"> $AAPL told y’all puts before closing are about to print </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:00:22 </td>
   <td style="text-align:left;"> $AAPL damn that is unfortunate, looks like the boss is right but I&amp;#39;m still in line for a bonus if this rips to 177+ monday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:00:11 </td>
   <td style="text-align:left;"> $AAPL .60 red candle into close actually .80 cent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:00:11 </td>
   <td style="text-align:left;"> $AAPL that drop so fast. Tired of the manipulation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 05:00:09 </td>
   <td style="text-align:left;"> $AAPL garbage </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:59:41 </td>
   <td style="text-align:left;"> $AAPL Disgusting Wall St pigs’ game (including the media)! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:59:16 </td>
   <td style="text-align:left;"> $AAPL  can&amp;#39;t  run </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:59:09 </td>
   <td style="text-align:left;"> $AAPL i am bullish on the stock but i did not want to take a position today, there were some sharp swings today and calls decay over the long weekend. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:58:21 </td>
   <td style="text-align:left;"> Will the Third Time Be a Charm for Apple?  $AAPL https://www.billionaireclubcollc.com/will-the-third-time-be-a-charm-for-apple/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:58:21 </td>
   <td style="text-align:left;"> $AAPL damn good run </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:57:56 </td>
   <td style="text-align:left;"> $SPY THE BULLS ARE FUCKED HOLY SHIT HOLY SHIT $IWM $AAPL $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:56:13 </td>
   <td style="text-align:left;"> $AAPL Day Traders are Scum of the earth. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:56:10 </td>
   <td style="text-align:left;"> $AAPL Attack Shorts. Anti-Santa Rally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:56:06 </td>
   <td style="text-align:left;"> $AAPL still manipulation. Send this shit to another galaxy fuck the moon. Recruit wsb on these shorts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:55:57 </td>
   <td style="text-align:left;"> $AAPL see ya next week bears! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:54:39 </td>
   <td style="text-align:left;"> $AAPL beyond stupid easy $$$$$$$$$$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:54:09 </td>
   <td style="text-align:left;"> $QQQ okay I sell my calls here.  Woo easy money.  Still extremely bullish on $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:54:02 </td>
   <td style="text-align:left;"> $MTTR let&amp;#39;s go bulls. Metaverse. Market is flying. $TSLA $AAPL $RBLX $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:54:02 </td>
   <td style="text-align:left;"> $AAPL Santa Cook is gonna dump a big pile of green apples on us! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:53:45 </td>
   <td style="text-align:left;"> $AAPL I never bet against her. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:52:55 </td>
   <td style="text-align:left;"> $AAPL bears go further into hibernation next week. Enjoy your holiday weekend shorties </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:52:20 </td>
   <td style="text-align:left;"> $AAPL 
🍏🔝
Excellent Volume!! 
Last minutes. 
Can Close +$177. 
AH$178. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:51:57 </td>
   <td style="text-align:left;"> $AAPL if your short.. cover.. or hedge.. but dont go a lone put here... this is about to rip.. christmas rally together with bullish divergence... horrible recipe to short! ;) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:51:44 </td>
   <td style="text-align:left;"> $AAPL No stress babe 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:51:39 </td>
   <td style="text-align:left;"> $AAPL … . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:51:30 </td>
   <td style="text-align:left;"> $AAPL shorts bailing in front of the long weekend. Thanks for playing!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:50:51 </td>
   <td style="text-align:left;"> $AAPL some shorts covering </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:50:50 </td>
   <td style="text-align:left;"> $AAPL I’d laugh hard af! If by some miracle the $177.50 calls go in the money. Last 30 mins 🤣😂😭🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:49:46 </td>
   <td style="text-align:left;"> $WM $AAPL my best plays ever. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:48:58 </td>
   <td style="text-align:left;"> $AAPL ugh boss is saying more puts.  He&amp;#39;s been wrong 3 times today.  He must know something I do not.  Anyone have any clues?  I&amp;#39;ve been buying calls and shares all day today... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:48:51 </td>
   <td style="text-align:left;"> $AAPL nice pop into close. We test 180 next week   Strong buy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:48:16 </td>
   <td style="text-align:left;"> $AMZN $AAPL $SPY 

https://twitter.com/SeekingAlpha/status/1474102891564597253?t=EbQyRXHtN9167T0WenTkAA&amp;amp;s=19 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:48:08 </td>
   <td style="text-align:left;"> $AAPL Doesn&amp;#39;t get any easier $$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:47:57 </td>
   <td style="text-align:left;"> $AAPL $TSLA  Happy Holidays y&amp;#39;all. Enjoy time with the fam. I know I will. Santa rally wa real this week.🎅🎄🎁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:47:49 </td>
   <td style="text-align:left;"> $AAPL 
🍏
VOLUME UP HARD. &amp;gt;500M. Per Minutes Right Now. 
It’s coming excellent Close. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:47:43 </td>
   <td style="text-align:left;"> $AAPL 🍏🎄😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:47:37 </td>
   <td style="text-align:left;"> $AAPL shit volume kinda day. Red next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:46:40 </td>
   <td style="text-align:left;"> $AAPL Merry Christmas to Apple bulls! Look at all those calls in the money!!!BULLS GOT PAID!! And a lot of call assignments lol 😂 The put side looks like the Sahara desert….🎅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:46:22 </td>
   <td style="text-align:left;"> $AAPL Nice. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:46:20 </td>
   <td style="text-align:left;"> $AAPL santa Rally - watch this close...bye bye PUTS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:46:05 </td>
   <td style="text-align:left;"> $AAPL wow whatsup with this going crazy at close lmfao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:43:59 </td>
   <td style="text-align:left;"> $AAPL would be nice if apple close 177.5 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:41:51 </td>
   <td style="text-align:left;"> $AAPL sell no shares take no prisoners </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:39:55 </td>
   <td style="text-align:left;"> Heading into 2022...

$AAPL, $MSFT, latex532e277d85e270f7fc90e90671c32178FB - Neutral - Bullish
$AMZN, SHOP - Boring </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:39:22 </td>
   <td style="text-align:left;"> $AAPL y’all holding calls over the weekend? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:39:11 </td>
   <td style="text-align:left;"> $AAPL 

Here we go .. upward
Santa gifts 🎁 for all long </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:39:10 </td>
   <td style="text-align:left;"> $AAPL 

Now VIX is now red so it will end on green note so AAPL is more likely to end 176.50 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:38:26 </td>
   <td style="text-align:left;"> $AAPL price action says they’re holding it down. Wants to explode every time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:38:21 </td>
   <td style="text-align:left;"> $AAPL $AABB!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:37:52 </td>
   <td style="text-align:left;"> $AAPL 

Pump big.. due to xmas

Power 20 min </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:37:40 </td>
   <td style="text-align:left;"> $AAPL futures green and this is being manip. Such b.s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:37:11 </td>
   <td style="text-align:left;"> $AAPL I could be wrong but I have a feeling it&amp;#39;s going to either pump big or dump big at the last few minutes of the day.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:36:08 </td>
   <td style="text-align:left;"> $AAPL CNBC buzz kill. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:35:55 </td>
   <td style="text-align:left;"> $AAPL boring ass day 😴 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:35:02 </td>
   <td style="text-align:left;"> $AAPL holiday short weeks are usually sideways. Low volume.  If we go by the definition of &amp;quot;santa rally&amp;quot;, its the last 5 days and first 2 days of the year supposedly. So maybe we have some fun monday! Hope yall have a great xmas!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:34:37 </td>
   <td style="text-align:left;"> $AAPL close the fkin markets before we go red fuk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:34:14 </td>
   <td style="text-align:left;"> $SPY Now all of sudden all 50 states reported OmiCron cases. Its like a school. Cant wait to see MSM death movie starting January when at home testing goes viral and false cases show up. Labor shortage and multiple testing requirements will become the norm.  This THE rally.  Closed calls on $TSLA  for 8K, lost $3K on $AAPL and got into 1/21 puts on $AMZN . Next week it might run but ready to average down.  Always had $100 swings on both sides.  Hedging with $3500 cal for 12/31. GL. Merry Christmas. 🎄🎁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:33:44 </td>
   <td style="text-align:left;"> $SPY Of Course, as soon as I long it drops $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:32:51 </td>
   <td style="text-align:left;"> $AAPL  now what? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:31:41 </td>
   <td style="text-align:left;"> $AAPL Got Yolo calls for next week.. I honestly think it’s setting up for a huge run </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:30:13 </td>
   <td style="text-align:left;"> $AAPL AAPL 2021-12-23 Trade Analysis Video: 
https://www.youtube.com/watch?v=HAOxkrlNZg4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:29:21 </td>
   <td style="text-align:left;"> $AAPL imagine how much of this is priced in!! Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:29:11 </td>
   <td style="text-align:left;"> $BKKT Will we get $AAPL partnership details on Monday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:28:44 </td>
   <td style="text-align:left;"> $AAPL 

Will 177.50 call go in green ?

Power 30 min…
Santa Rally 
Christmas rally 

Apple car rally
3 trillion rally </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:28:15 </td>
   <td style="text-align:left;"> $AAPL out+676 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:28:10 </td>
   <td style="text-align:left;"> $AAPL 200 next week! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:26:25 </td>
   <td style="text-align:left;"> $AAPL Freaking hell apple. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:26:12 </td>
   <td style="text-align:left;"> $AAPL Crooks are manipulating it big time not to go up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:25:12 </td>
   <td style="text-align:left;"> $AAPL he’s pushing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:25:12 </td>
   <td style="text-align:left;"> $AAPL 

Buy buy … new year gift </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:25:00 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:24:44 </td>
   <td style="text-align:left;"> $AAPL 176.50 is tough </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:23:53 </td>
   <td style="text-align:left;"> $AAPL  no love today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:23:42 </td>
   <td style="text-align:left;"> $AAPL         🍏🎄❗️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:23:24 </td>
   <td style="text-align:left;"> $AAPL the most over priced stock in the market right now is $SEAS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:23:11 </td>
   <td style="text-align:left;"> $AAPL when bears try and take a bite out of apple and it bites back. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:21:05 </td>
   <td style="text-align:left;"> $AAPL 

It appears many people are so disappointed by the price action before Christmas.

Don’t forget we have 3T to break to cheer we to pass in 2021. 

That’s the biggest rally. Be on the positive note :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:20:59 </td>
   <td style="text-align:left;"> $AAPL imagine a squeeze to 178 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:20:56 </td>
   <td style="text-align:left;"> $AAPL 
+$177…. Break Out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:20:54 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:20:17 </td>
   <td style="text-align:left;"> Don&amp;#39;t be surprise when it closes at the highs $SPY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:17:53 </td>
   <td style="text-align:left;"> $AAPL bust it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:16:19 </td>
   <td style="text-align:left;"> $AAPL  🍏🎄  Volume, 50 Million. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:16:11 </td>
   <td style="text-align:left;"> HANA KUMTU &amp;quot; $KT EXPECTS 20% RETURN BY FEBRUARY NEXT YEAR... #UNDERVALUED BUY OPPORTUNITIES&amp;quot;

https://m.stock.naver.com/index.html#/domestic/stock/030200/news/view/366/0000782271

$AAPL $AMZN $GOOG $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:16:02 </td>
   <td style="text-align:left;"> $AAPL whelp back to halo..... so what I&amp;#39;m re-living my child hood this time im a fake spiderman only I&amp;#39;m a spartan with a grappleshot none the less 
 have  a Merry Christmas or Happy Holidays </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:15:29 </td>
   <td style="text-align:left;"> $AAPL lol fuckers pinned it right here. Bitchass </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:15:13 </td>
   <td style="text-align:left;"> $AAPL ppl complain about 3t but never complain about tsla? Smh this shit deserves $200 at least idgaf what anyone says. Metaverse and going into ev. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:14:50 </td>
   <td style="text-align:left;"> $AAPL anyone else options price froze on webull? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:14:22 </td>
   <td style="text-align:left;"> $SPY $AAPL running out of juice, and we all know what that means for the indexes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:14:06 </td>
   <td style="text-align:left;"> $AAPL now that they’ve completely killed the 12/23 177.5c , I think we might start running soon again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:13:41 </td>
   <td style="text-align:left;"> $AAPL granny bought aapl puts. 

Not letting her out till we break 180. Let’s goooo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:13:40 </td>
   <td style="text-align:left;"> $AAPL looks awful </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:12:54 </td>
   <td style="text-align:left;"> $SPY So now the question becomes do we have enough PMs chasing performance to not have the Market dip next week after this pull forward?

That is the question 

$aapl $amzn $qqq $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:12:12 </td>
   <td style="text-align:left;"> $AAPL jan 7 dam sorry 🤣 too many drugs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:12:07 </td>
   <td style="text-align:left;"> $AAPL no more pumping? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:11:46 </td>
   <td style="text-align:left;"> $AAPL Damn! Apple has been pathetic today! Not a good sign! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:11:15 </td>
   <td style="text-align:left;"> $AAPL not letting granny out till aapl hits 180 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:11:13 </td>
   <td style="text-align:left;"> $AAPL sold my calls expiring today at 70%+ profit 💸 buying into Dec 7 calls 🤑 I’m thinking she gaps up after the long weekend 🏌🏽‍♂️ happy holidays 🙏🏽 see ya in Valhala </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:10:45 </td>
   <td style="text-align:left;"> $AAPL option killing day. Next week will be diff </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:10:41 </td>
   <td style="text-align:left;"> $SPY O&amp;#39;leary prob gonna get crushed in bitcoin 

 $AAPL $AMD $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:09:56 </td>
   <td style="text-align:left;"> $AAPL Santa only gave me $1 cheap sob </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:09:00 </td>
   <td style="text-align:left;"> $SPY Bears going long for next week $AAPL $FB $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:08:39 </td>
   <td style="text-align:left;"> $AAPL  “just kidding” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:07:25 </td>
   <td style="text-align:left;"> $AAPL let’s fight bulls! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:06:02 </td>
   <td style="text-align:left;"> $AAPL so is power hour a real thing? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:04:53 </td>
   <td style="text-align:left;"> $AAPL 172 before uptrend you need consolidation and uptrend at most gives you to 180 before earnings early jan. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:04:41 </td>
   <td style="text-align:left;"> $AAPL if you liked it at 176.60 you should be liking it more at 176.20  ez money. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:04:30 </td>
   <td style="text-align:left;"> $AAPL that failed daily breakout, slow stairs up then elevator down lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:04:00 </td>
   <td style="text-align:left;"> $AAPL merry Christmas mother fuckers to a happy and successful new investing and trading year 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:03:34 </td>
   <td style="text-align:left;"> $AAPL I knew it was too early. No1 selling. They’re killing calls and puts today. Especially $177.50 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:03:29 </td>
   <td style="text-align:left;"> $AAPL wtf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:02:59 </td>
   <td style="text-align:left;"> $AAPL well played bears </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:02:36 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:02:17 </td>
   <td style="text-align:left;"> Hey guys, need help with my setup. Does anyone know who I can hire to help me set up my watchlist and charting that would help me be a better day trader? $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:02:10 </td>
   <td style="text-align:left;"> $AAPL wrecked 🚢 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:01:50 </td>
   <td style="text-align:left;"> $AAPL you&amp;#39;ve consolidated enough hoe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:01:00 </td>
   <td style="text-align:left;"> $AAPL imagine next week when ppl come back from holidays. We needed volume today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:00:51 </td>
   <td style="text-align:left;"> $AAPL nice rip in the afternoon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:00:38 </td>
   <td style="text-align:left;"> $AAPL boss literally pushed me out the way and executed a put buy order for 168s for January.  I told him it was a rip off.  Can I sue him for harassment? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 04:00:28 </td>
   <td style="text-align:left;"> $AAPL 
🍏
Beginning Operations &amp;gt;200M. Per Minutes. 
Here We Go. 🍏🆙🔜 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:59:49 </td>
   <td style="text-align:left;"> $AAPL Sweeper Alert 🍎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:59:33 </td>
   <td style="text-align:left;"> $AAPL are btches selling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:58:58 </td>
   <td style="text-align:left;"> $AAPL doozy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:58:47 </td>
   <td style="text-align:left;"> $AMC  $AAPL Strong Apes we need you $BFRI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:58:44 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:58:05 </td>
   <td style="text-align:left;"> $AAPL 3 min to Happy Holidays Power Hour! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:58:00 </td>
   <td style="text-align:left;"> $AAPL is running at it&amp;#39;s HOD and pushing $SPY higher into close. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:57:54 </td>
   <td style="text-align:left;"> $AAPL let’s go bitch I was down 90% but I saw it through I averaged down now up 400% 2000% here we come </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:57:33 </td>
   <td style="text-align:left;"> $AAPL me laughing at my boss telling me to buy more poots while buying more shares and calls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:57:06 </td>
   <td style="text-align:left;"> $AAPL my $180 lottos 😖😖 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:56:34 </td>
   <td style="text-align:left;"> $AAPL let’s not celebrate until we break above and hold or move higher. Let’s go bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:56:06 </td>
   <td style="text-align:left;"> $AAPL call killer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:55:52 </td>
   <td style="text-align:left;"> $AAPL heading over 190... shorting here is suicide people good luck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:55:47 </td>
   <td style="text-align:left;"> Those who really followed and following me from over one year knows what my challenge was for 2021 on trading. 

Started with 100k this year and came to 1.4M so far, Considering last 6 months been crap like hell I have come really close to my Goal. 

Plan is to keep the same Goal but start with 200K this time and go for 4M or more. let&amp;#39;s see how we do it. As always Twitter is open for anyone to message me and do not forget to follow. 

Through this year I have gained a lot of good friends few turned as close as family too. Looking forward to amazing 2022.

$SPY $IWM $AAPL $CEI $BCTX among best trades for me and holding AAPL BCTX still.

RESPECT and LOVE is all I like to see from and to ALL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:55:43 </td>
   <td style="text-align:left;"> $AMZN Pfizer&amp;#39;s version of the drug will be in high demand. The company has said it expects to manufacture 180,000 treatment courses by the end of next month and at least 50 million courses by the end of 2022.

$Vtrs is making the generic $pfe pill.   Shhhhhhhhh.   Don’t tell anyone 

$aapl $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:55:34 </td>
   <td style="text-align:left;"> $AAPL 3 trillion here we come in 2022. High Octane 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:55:31 </td>
   <td style="text-align:left;"> $AAPL 
F
The
Shorts!!!
Especially 
DAN
NILES!!!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:55:27 </td>
   <td style="text-align:left;"> $AAPL Just like yesterday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:55:06 </td>
   <td style="text-align:left;"> $AAPL loading up on puts right before closing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:54:42 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:54:30 </td>
   <td style="text-align:left;"> $AAPL really 🧐 Santa where you at?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:54:23 </td>
   <td style="text-align:left;"> $AAPL SANTA RALLY INCOMING! 🍏🎅📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:54:17 </td>
   <td style="text-align:left;"> $AAPL can we get our turn today! Break that $176.59 wall bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:53:20 </td>
   <td style="text-align:left;"> $AAPL reversal down to 176 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:51:26 </td>
   <td style="text-align:left;"> $AAPL easy breakout  time for  176.50 by close </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:50:40 </td>
   <td style="text-align:left;"> $AAPL get to 177.5 bitch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:50:39 </td>
   <td style="text-align:left;"> $AAPL C&amp;#39;mon bulls - take out the intraday high before PH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:49:07 </td>
   <td style="text-align:left;"> $BKKT so we’ve got 3 huge things going for this stock, 3 words.. $AMZN  $AAPL  and $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:48:29 </td>
   <td style="text-align:left;"> $AAPL Needs egg nog </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:48:02 </td>
   <td style="text-align:left;"> $AAPL 176.5 is short city </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:47:59 </td>
   <td style="text-align:left;"> $AAPL volume looks better now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:47:30 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:47:07 </td>
   <td style="text-align:left;"> $SMURF $MANA.X $BTC.X $SPY $AAPL 
Smurf is the first real estate company in the metaverse.
The metaverse is the future of internet.
The above stocks are the future of the metaverse. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:46:52 </td>
   <td style="text-align:left;"> $AAPL we double topping? for 3:00 and a close to 176 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:46:08 </td>
   <td style="text-align:left;"> $AAPL easy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:46:06 </td>
   <td style="text-align:left;"> $aapl AAAND i am fully out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:45:56 </td>
   <td style="text-align:left;"> $AAPL cmon you pos $177 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:45:55 </td>
   <td style="text-align:left;"> $AAPL $190 or my pet glizzy expires with my $180 calls. You choose! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:45:32 </td>
   <td style="text-align:left;"> $AAPL TAXPAYERS NEED TO PAY MY STUDENT LOANS... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:45:20 </td>
   <td style="text-align:left;"> $UBER $AAPL $TSLA 
search it &amp;quot;3q82dwzcRp&amp;quot; on Google and checkout the first link! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:44:07 </td>
   <td style="text-align:left;"> $AAPL looking for around 175.85 to fill these call orders for 180 12/31 @1.08 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:43:38 </td>
   <td style="text-align:left;"> $AAPL 💯💯💯💯💯💥💥💥💥🧚‍♀️🧚‍♀️🧚‍♀️🧚‍♀️🧚‍♀️💃💃💃💃💃💃💃💃❤❤❤❤❤ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:43:18 </td>
   <td style="text-align:left;"> $AAPL 🍏being shorted a bit looks like bears gonna get it again
Let’s c what happens last 45 minutes of the day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:42:29 </td>
   <td style="text-align:left;"> $AAPL Exitted half long delta. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:41:57 </td>
   <td style="text-align:left;"> $AAPL LOAD UP, Easy money! $$$$$$$$$$$$$$$$$$$$$$$$$$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:41:57 </td>
   <td style="text-align:left;"> $AAPL reversal maybe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:40:43 </td>
   <td style="text-align:left;"> End of day volume has been high for $KT  DO NOT SELL!!!  FORCE BUYERS TO INCREASE BIDS!!!
$AAPL $AMZN $GOOG $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:36:49 </td>
   <td style="text-align:left;"> $TSLA $AAPL 💸💸💸💸💸💸💸💸💸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:35:08 </td>
   <td style="text-align:left;"> $AAPL 107k volume on 12/31 180c expiry. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:33:46 </td>
   <td style="text-align:left;"> $AAPL We have next week for the rally to continue. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:33:42 </td>
   <td style="text-align:left;"> $AAPL looks like hext leg up will be 176.5 to 177 soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:33:22 </td>
   <td style="text-align:left;"> $AAPL selling premiums was the winner today here. Rip call and put holders😂. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:33:08 </td>
   <td style="text-align:left;"> $AAPL AAPL 2021-12-23 Dark Pool &amp;amp; Short Interest Data: 
https://www.youtube.com/watch?v=DcGgxE75qx4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:33:00 </td>
   <td style="text-align:left;"> $UNVC $AAPL $BTC.X $TSLA $AMZN whoever likes MONEY buy UNVC N O W </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:32:44 </td>
   <td style="text-align:left;"> $AAPL apple pin ends today. short leg of large calendar blocks expiring. long leg 180+ eoy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:32:11 </td>
   <td style="text-align:left;"> $AAPL Crock of shit performing 20% of the NASDAQ today. Utter garbage. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:32:02 </td>
   <td style="text-align:left;"> $MSFT expecting a gamma squeeze at close $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:31:57 </td>
   <td style="text-align:left;"> $AAPL fuck it! Gimme $190 during power hour.. or else…I will kill my small pet dog…

…a pet hotdog…his name is glizzy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:31:43 </td>
   <td style="text-align:left;"> $AAPL  🔜1️⃣5️⃣5️⃣ $SPY #WhosKnow??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:30:59 </td>
   <td style="text-align:left;"> $AAPL that was all she wrote not even a double top for the bulls. 172 incoming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:28:29 </td>
   <td style="text-align:left;"> $AAPL these guys provide ultimate suggestions &amp;amp; teach us Trading …
join this mission fellas !! 

https://t.me/TradeandLearnSubscriptionbot </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:26:51 </td>
   <td style="text-align:left;"> $AAPL There we go.  I&amp;#39;m overall big boy green today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:26:26 </td>
   <td style="text-align:left;"> $AAPL  🍏🎄  Oil Mkts Closing, in minutes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:26:04 </td>
   <td style="text-align:left;"> $BKKT $MA $SBUX $GOOGL and $AAPL next ? Fuck! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:25:32 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:24:28 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:24:22 </td>
   <td style="text-align:left;"> $BKKT and remember the $AAPL deal rumoring 📈📈📈🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:23:58 </td>
   <td style="text-align:left;"> $AAPL I told y’all those calls would be worthless! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:23:29 </td>
   <td style="text-align:left;"> $AAPL Reversal Coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:22:20 </td>
   <td style="text-align:left;"> $AAPL don&amp;#39;t forget options traders.  Buying of the shares and selling of the shares drives the price.  Do your civic duty and buy a few shares here for Monday&amp;#39;s rip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:21:52 </td>
   <td style="text-align:left;"> $AAPL Do you fellow bulls believe we see $182 after the long weekend? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:20:28 </td>
   <td style="text-align:left;"> $AAPL hahah </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:19:38 </td>
   <td style="text-align:left;"> $ALLK $SPY $AAPL 

CHRISTMAS POWER HOUR COMING </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:19:21 </td>
   <td style="text-align:left;"> $MSFT $AAPL Out of 1/21/22 calls on both. Looking ahead IV, delta and theta were not my friends anymore. Out of the pan today, back into the fire on Monday. Happy Holidays! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:19:05 </td>
   <td style="text-align:left;"> $AAPL need some volume </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2021-12-24 03:18:55 </td>
   <td style="text-align:left;"> $AAPL Any day with green candles is a good day! 🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:48:08 </td>
   <td style="text-align:left;"> $TSLA I guess we are all just accepting that we are going to drive these ugly pieces around for the rest of our lives🤢 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:45:19 </td>
   <td style="text-align:left;"> $TSLA what’s the PT on this? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:44:52 </td>
   <td style="text-align:left;"> $TSLA https://cnevpost.com/2021/12/24/tesla-signs-deal-with-hyundai-glovis-to-ship-giga-shanghai-vehicles-to-other-regions/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:44:52 </td>
   <td style="text-align:left;"> What a Day !!!! $SOPA $AERC $TSLA !!!!! ASML !!!! oh myyyyy Santa came hard !!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:44:08 </td>
   <td style="text-align:left;"> $TSLA - let&amp;#39;s finish at all time high on 12/31/21 🥂🍾💥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:43:47 </td>
   <td style="text-align:left;"> Merry Christmas 🎄 Happy Holiday ✌️😉 
 
$ggiv $sofi $lcid $btc.x  $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:42:58 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:39:06 </td>
   <td style="text-align:left;"> $TSLA is over extended and needs to pull back before it heads higher.  needs to pull back to $1040 then lower between $1030-$1020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:37:32 </td>
   <td style="text-align:left;"> Just remember, without idiots and panic sellers of stocks we would never have opportunities like this to  propel our net worths in such a drastic way in a short amount of time. Forget $PYPL forget $TSLA forget $AAPL those have had their run. This is the new play. You wanna beat Wall Street? $BABA is where you need to be. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:36:47 </td>
   <td style="text-align:left;"> $TSLA https://www.breitbart.com/tech/2021/12/23/communist-bff-elon-musks-extensive-history-of-cozying-up-to-red-china/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:36:23 </td>
   <td style="text-align:left;"> $TSLA https://www.cnbc.com/2021/12/23/us-bans-imports-from-chinas-xinjiang-region-citing-uyghur-forced-labor.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:35:36 </td>
   <td style="text-align:left;"> $TSLA interesting next week for bulls and bears.. :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:34:06 </td>
   <td style="text-align:left;"> $TSLA RUNNING THIS TO EARNING </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:33:37 </td>
   <td style="text-align:left;"> $TSLA Congratulations all TSLA bull

I usually do BPS for tesla but the premium is bad due to the amazing strength of tsla. 

So have to do naked call for next week. 

I&amp;#39;m a tsla bull but 1350 next friday is unimaginable. 

https://www.noobsellingoptions.com/post/naked-call-tsla-do-not-try-this-at-home </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:32:35 </td>
   <td style="text-align:left;"> $TSLA what’s the prediction for Mon. Will market tank due to some news or it will go up ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:32:13 </td>
   <td style="text-align:left;"> $TSLA TSLA 2021-12-23 Options Analysis Video: 
https://www.youtube.com/watch?v=qzDouDYbflI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:30:26 </td>
   <td style="text-align:left;"> $TSLA Closed out my 500 shares at $1,068.90 and 7 of 15 of my daughter’s shares (different brokerage) at $1,067 in extended hours. My entry $653 and hers about $579.

I shot for $1,068.90 so I would be just over $875k in this account. (Original order for $1,067.89, but OCD issues hated $874,xxx more than the break in number order in my limit price.) 🤪

With this, I’m virtually cleared out of my active trading positions and ending the year at $1.207M in gains for the year.  Just over $200k from TSLA shares (no options this time).  I will trade if there’s an opportunity, but trying to stay above $1.2M.  $7k YOLO options?  😁

I always say, bulls and bears can both eat well in this market.  Let’s all have fun and make money!  Screenshots to get ahead of the doubters/name callers.  Happy Holidays everyone! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:29:30 </td>
   <td style="text-align:left;"> $NKLA next $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:28:19 </td>
   <td style="text-align:left;"> $TSLA Crazy that aftermarket ended green, too.  Wow, what a crazy two days.  And, all of the catalysts are not even triggered either.  This next year is FULL of them.  Belt in! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:27:42 </td>
   <td style="text-align:left;"> $TSLA Alerted in the server be sure to check us out 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:27:14 </td>
   <td style="text-align:left;"> $TSLA Extremely bullish indicators: Per the SEC filings, Elon did sell even more yesterday, but we were still up huge, this is because most of the selling is done, and per the filings, even after all the selling, he has ACQUIRED (not disposed) a net 6.5million shares via options. Keep shaking me head when I see the crooks and grifters on TV never mention this. Either way, this is extremely bullish, already added a bunch recently </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:26:47 </td>
   <td style="text-align:left;"> $TSLA fuck the NFL Network. Thursday night football should be on normal channels. Need a subscription, suck my balls. Just venting, let&amp;#39;s go Tesla. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:25:53 </td>
   <td style="text-align:left;"> MY FIRST DRINK DEDICATING TO ALL THE $TSLA $SPY BULLS TODAY YOU GUYS ARE FREAKING AMAZING! BLESSED TO SAY THE LEAST🎄🎄🎄🎅🏼🎅🏼🎅🏼🎅🏼 MERRY CHRISTMAS AND HAPPY HOLIDAYS❤️❤️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:25:03 </td>
   <td style="text-align:left;"> $TSLA I’m holding 1/07/2022, 1250 calls 5 contracts over the wknd </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:23:34 </td>
   <td style="text-align:left;"> $TSLA for any of yall snowflakes who doesnt know there is google </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:21:05 </td>
   <td style="text-align:left;"> $TSLA 

Israel 🇮🇱 to offer 4th COVID-19 Shot for ppl 60 yrs of age and older , expand travel ban to include US, Canada , Germany, Italy, Turkey  !

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:20:04 </td>
   <td style="text-align:left;"> $TSLA 1069 wow! Elon the magician </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:19:51 </td>
   <td style="text-align:left;"> $TSLA 1000 first or 1100 first? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:19:24 </td>
   <td style="text-align:left;"> $TSLA $AAPL $SPY $BJDX 
Next week also 🎄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:15:46 </td>
   <td style="text-align:left;"> $TSLA Guys Elon is done selling this time no lie! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:15:17 </td>
   <td style="text-align:left;"> $TSLA ... da dum! da dum!!  &amp;quot;Stock Split!&amp;quot; @ $2500!!!  FU BEARS! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:14:28 </td>
   <td style="text-align:left;"> $TSLA $1069, love it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:13:49 </td>
   <td style="text-align:left;"> $TSLA I am so happy I sold out of my puts yesterday thank you LAWD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:13:39 </td>
   <td style="text-align:left;"> $TSLA so did Elon sell all or still needs to sell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:13:21 </td>
   <td style="text-align:left;"> $TSLA i guess the Market won’t be open on tomorrow right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:13:19 </td>
   <td style="text-align:left;"> $TSLA market closed tmr ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:12:52 </td>
   <td style="text-align:left;"> $TSLA $SPY where is @ShortyMcFly and his hot posts 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:12:43 </td>
   <td style="text-align:left;"> $TSLA anyone know if the market is closed any days of next week, or if it’s closing early? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:12:34 </td>
   <td style="text-align:left;"> $TSLA our members have taken partial profit from the blue box buy in $TSLA, and set stops to the recent low in case the instrument does the double.  Members were given the box well in advance.  We don&amp;#39;t chase the markets, we wait for the right risk reward at the blue boxes. #elliottwave #trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:12:34 </td>
   <td style="text-align:left;"> $TSLA Strong resistance at $5000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:12:18 </td>
   <td style="text-align:left;"> $TSLA looks like there will be bearish divergence as it goes into the golden zone resistance area at the top of the channel..  does this look like a 5 wave impulse to you? any proposed w2 seems laughable.  there is no retracement.  this just has me thinking of selling early bc i never hang on for long. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:11:16 </td>
   <td style="text-align:left;"> $TSLA day traders were expecting a drop under $1040 😂😂😂 Hope you can buy under $1100 if you only have a Robinhood  account </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:09:23 </td>
   <td style="text-align:left;"> $TSLA Elon&amp;#39;s indian name.  Great Bear Slayer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:07:38 </td>
   <td style="text-align:left;"> $TSLA atleast 1100 open Monday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:07:27 </td>
   <td style="text-align:left;"> $TSLA beautiful close! What a gift! See you soon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:06:47 </td>
   <td style="text-align:left;"> $TSLA prediction...Musk gets charged for committing securities and wire fraud in this recent stunt. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:05:24 </td>
   <td style="text-align:left;"> $TSLA tesla closed $1069.  I gotta go lick some pussy this weekend. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:03:28 </td>
   <td style="text-align:left;"> $TSLA this thing has gone bonkers to over 80 RSI easily on the daily we are far from that easily can see a $1300 move next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:03:27 </td>
   <td style="text-align:left;"> $TSLA anyone know what time the market opens Saturday? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:02:09 </td>
   <td style="text-align:left;"> $TSLA Simulated 1075.0 dollar CALLS for Monday&amp;#39;s open on StockOrbit.
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:01:11 </td>
   <td style="text-align:left;"> $TSLA I held my 1000 call for the last 3 weeks. Went down to like 900 at one point. 8300 today. Holding for next weeks Talley to ATH! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:01:10 </td>
   <td style="text-align:left;"> $TSLA will we be getting sec filing now? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:00:19 </td>
   <td style="text-align:left;"> $TSLA those bulls who sold today hope won’t see you here crying for selling too early next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 09:00:11 </td>
   <td style="text-align:left;"> $TSLA added 50 more AH at 1063

Let’s go Brandon!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:59:34 </td>
   <td style="text-align:left;"> $TSLA 16.59. FOMO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:58:54 </td>
   <td style="text-align:left;"> $TSLA imagine doubting Elons vibe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:58:42 </td>
   <td style="text-align:left;"> Oh shit, Elon is buying after hours 

Mindfuck 

$TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:57:57 </td>
   <td style="text-align:left;"> $AMD $tsla  $aapl   $NVDA 

New acronym for 2022- TAAN

Tesla, Apple, AMD and Nvidia </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:56:37 </td>
   <td style="text-align:left;"> The Companies that Defined 2021 $PFE $TSLA $COIN $FB $HOOD https://talkmarkets.com/content/stocks--equities/the-companies-that-defined-2021?post=338905 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:56:01 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:55:09 </td>
   <td style="text-align:left;"> $TSLA delivery numbers for 4th quarter are way better than 3th quarter that means we go to mars instead of moon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:54:42 </td>
   <td style="text-align:left;"> $TSLA And I’ll say it again
“I Told Ya” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:53:06 </td>
   <td style="text-align:left;"> $SPY Agree or disagree 🍕 &amp;lt; 🍑 What will you be having for Xmas dinner this weekend 🤤 $tsla $AMC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:52:15 </td>
   <td style="text-align:left;"> $TSLA bears prepare thy asshole for monday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:51:31 </td>
   <td style="text-align:left;"> $TSLA  Calls paid out today. Wish I made a position. Scared money don’t make money. Fuck hoes and get bitches. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:51:00 </td>
   <td style="text-align:left;"> $TSLA AH mooning damn bears must be shitting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:49:24 </td>
   <td style="text-align:left;"> $TSLA this kinda funny tho </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:48:59 </td>
   <td style="text-align:left;"> $TSLA can anyone see my
Posts ?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:47:20 </td>
   <td style="text-align:left;"> $TSLA 

What are the predictions for Monday close?!

Mine is 1197

Happy holidays you filthy animals! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:47:14 </td>
   <td style="text-align:left;"> Tesla is a subscription model company. They also sell EVs 

$TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:47:00 </td>
   <td style="text-align:left;"> $TSLA has one of the better Altman-Z scores in its industry: 21.59 vs 3.75. https://www.chartmill.com/stock/quote/TSLA/fundamental-analysis?key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:46:41 </td>
   <td style="text-align:left;"> $TSLA  selling close $1070 in 14mins </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:45:18 </td>
   <td style="text-align:left;"> $TSLA Shame the stock market is closed tomorrow all this excitement to hold in all week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:45:17 </td>
   <td style="text-align:left;"> $TSLA I sold the damn 1050 calls to my stock.  Only thing Cramer ever said right, why sell calls on a good stock&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:44:46 </td>
   <td style="text-align:left;"> $TSLA future prediction: Elon tweets on Christmas “merry Christmas you filthy animals 1337 to the moon !” We open Monday $1337 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:44:39 </td>
   <td style="text-align:left;"> Elon Musk Tells Jack Dorsey And Crypto Twitter Why He&amp;#39;s &amp;#39;Pro DOGE&amp;#39;

$BTC.X $TSLA $TWTR $DOGE.X  

https://www.benzinga.com/markets/cryptocurrency/21/12/24751759/elon-musk-tells-jack-dorsey-and-crypto-twitter-why-hes-pro-doge </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:43:03 </td>
   <td style="text-align:left;"> $TSLA 6% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:41:22 </td>
   <td style="text-align:left;"> $TSLA God wanted this to rise, He works in mysterious and wonderful ways :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:40:39 </td>
   <td style="text-align:left;"> $SPY Eat up bulls... $Tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:40:00 </td>
   <td style="text-align:left;"> $TSLA $800 January. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:39:35 </td>
   <td style="text-align:left;"> $TSLA IS THE MARKET OPEN TOMORROW??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:39:15 </td>
   <td style="text-align:left;"> Dow Jones Futures: Santa Claus Rally Comes Early As $TSLA Surges, These 5 Stocks Flash Buy Signals
https://www.investors.com/market-trend/stock-market-today/dow-jones-futures-santa-claus-rally-comes-early-tesla-surges-five-stocks-flash-buy-signals/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:38:58 </td>
   <td style="text-align:left;"> $TSLA 

Tesla Secures Contract With Hyundai Glovis To Ship Cars Out of 🇨🇳 China 

🙏🏻🐉🦅

https://insideevs.com/news/556713/tesla-contract-shipping-giga-shanghai/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:38:51 </td>
   <td style="text-align:left;"> $PLTR $TSLA $AMZN 

🧑‍🎄🤶🎄🍷🎁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:36:46 </td>
   <td style="text-align:left;"> SweepCast alerted: $TSLA with Unusual Options Activity Alerted on $1100 CALL Expiring: 12-31-2021 worth 45K🐂 |🥇 Check out ➡️ SweepCast.co </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:35:14 </td>
   <td style="text-align:left;"> $TSLA to those gamblers that got those 1000 weekly calls, i salute you. ive never seen a lotto call that made that much👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:35:06 </td>
   <td style="text-align:left;"> $TSLA other car makers with a broadly consolidated market are already formulating their own EV’s, the time when Tesla had some exclusivity is over, competition will be more and more fierce and the competitor who offers efficient cars at an affordable value, not just justified by the positioning of a brand, will win. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:33:12 </td>
   <td style="text-align:left;"> $TSLA Option volume for next week exp is off the charts.  Calls 2:1 Puts.  Technicals are excellent. Would not be surprised to see a kiss at 1200.  Bulls eye though will probably be around 1150. . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:32:54 </td>
   <td style="text-align:left;"> $TSLA 🟢 after hours </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:32:23 </td>
   <td style="text-align:left;"> $TSLA TSLA 2021-12-23 Technical Analysis Video: 
https://www.youtube.com/watch?v=cV1FZXAtqD8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:32:04 </td>
   <td style="text-align:left;"> $TSLA I think Musk sold today as well. It will make it an even stronger case for the DOJ. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:30:33 </td>
   <td style="text-align:left;"> $TSLA I see some comments about 2025 price predictions😂....guess what by that time there would be a lot,  better  EV options to choose from and Elon would screw you so many times by 2025🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:29:13 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Tesla locks access to video games in main display while car is in motion https://www.stck.pro/news/TSLA/20243272 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:28:27 </td>
   <td style="text-align:left;"> $TSLA “Where do we expect to see Tesla stock price next week EoY?” 
@ElonTusk @BigNews @S3XYShorts @bendrobidow @jccoo @SarahMoneywork @MariaSt @Joe_Mama  @Krizpal1083 and others😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:28:22 </td>
   <td style="text-align:left;"> $TSLA man my 1200 calls with an average price of $2.66 looking pretty nice coming into next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:28:17 </td>
   <td style="text-align:left;"> $tsla $btc.x $spy $qqq https://www.youtube.com/watch?v=ViWBBJtayzg&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:27:45 </td>
   <td style="text-align:left;"> $TSLA 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:27:07 </td>
   <td style="text-align:left;"> $TSLA 

@elonmusk 

In a few short years, Consumer Reports management has destroyed the credibility &amp;amp; integrity built up over decades! 

FYI:  They’re $F talking heads! 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:26:27 </td>
   <td style="text-align:left;"> $TSLA hahaha! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:26:23 </td>
   <td style="text-align:left;"> $TSLA Reality is shorts keep losing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:25:48 </td>
   <td style="text-align:left;"> $TSLA China is going to come out with a Chesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:25:30 </td>
   <td style="text-align:left;"> $TSLA so fun </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:22:32 </td>
   <td style="text-align:left;"> $TSLA after next week for all those SWING CALLS that are now TRAPPED! Expect Elon to tweet something goofy over weekend to TANK the stock 📉😹 
.. EV STOCKS will do OK next year $nio $rivn $nkla however competitive value for market share is still dominant for Tesla but Elon ability to be retarded week keep the stock subdued... $SPY at most will pay out about 14% organic growth is the dagger for stocks next year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:22:22 </td>
   <td style="text-align:left;"> $VYGVF Double digit green in a day is a solid victory. 💪hope it keeps going tomorrow for another home run like the $TSLA call from🐐 @RiskVsReward today. 📈Solid in for a quick gain. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:21:42 </td>
   <td style="text-align:left;"> $TSLA

Who else loaded up the other day when she dipped to $900? I backed up the ship and load up like fuck. 💪💪💪 Into the new year bullish as fuck. 💵💵🦍🦍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:21:38 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:21:11 </td>
   <td style="text-align:left;"> $TSLA Merry Christmas!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:21:02 </td>
   <td style="text-align:left;"> $TSLA  missed out on 5k today :/ sold to early !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:20:54 </td>
   <td style="text-align:left;"> $TSLA Musk tweets water is wet. This goes up 10%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:19:40 </td>
   <td style="text-align:left;"> $TSLA

And yes every single car will be sold out!
 https://electrek.co/2021/12/08/tesla-output-out-of-china-reaching-600000-electric-cars-annually/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:18:52 </td>
   <td style="text-align:left;"> $TSLA beats… bears, you are fckd up again. Cant believe they never learn.😳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:18:48 </td>
   <td style="text-align:left;"> $TSLA Has a small share of the overall car market and is losing share in the ev car market.  Reality will eventually catch up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:18:09 </td>
   <td style="text-align:left;"> $TSLA 

The market value of Tesla has soared to around $600 billion, making it the largest company ever to be added to the S&amp;amp;P 500. It’s inclusion on December 21 is expected to trigger a torrent of trading and a spike in volatility. (Dec. 17) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:16:37 </td>
   <td style="text-align:left;"> $TSLA After years of Tesla dominating sales of EVs in the U.S., its market share is waning. Tesla&amp;#39;s domestic market share of electric vehicles is dropping and that share will continue to lower, to 20% in 2025, as larger automakers such as GM release an influx of new vehicles. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:16:07 </td>
   <td style="text-align:left;"> $TSLA https://en.brinkwire.com/technology/elon-musk-thinks-its-a-good-idea-to-offer-tesla-premium-connectivity-for-a-yearly-fee-of-dollar99/?amp=1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:14:55 </td>
   <td style="text-align:left;"> $TSLA https://www.teslarati.com/tesla-panasonic-new-campus-gigafactory-nevada/amp/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:13:36 </td>
   <td style="text-align:left;"> $TSLA

People have no clue how big tesla will get. The factory in China is pumping out teslas like crazy and they are selling like hot cakes. The Chinese can&amp;#39;t get enough of this beautiful car, they really appreciate the engineering and they love Elon musk, he&amp;#39;s a cool guy. Hold tesla until 2030 before I even think of selling. 👍👍👍💵💵💵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:13:23 </td>
   <td style="text-align:left;"> $TSLA Sold Covered Calls target price $1500 for 01/07/2022. Free money $150 per contract. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:09:50 </td>
   <td style="text-align:left;"> $TSLA damn! I got destroyed today and held my PUTS. Im selling Friday Next week hope it retest 1000 or gap down monday so i can exit my puts early. CONGRATS BULLs!! Lost 6k today by ave down.  Gap down mondaynis my hope to breakeven😭 merry christmas to all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:09:02 </td>
   <td style="text-align:left;"> $TSLA ignored the negativities we all know this going to 1200 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:06:36 </td>
   <td style="text-align:left;"> $TSLA my favorite thing about posting bearish on this page is the zero followers bots that start hammering the post </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:05:41 </td>
   <td style="text-align:left;"> $TSLA do we go test 1036 support area and then bounce back to 1200? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:04:26 </td>
   <td style="text-align:left;"> $TSLA This time Elon is almost almost done selling, all he needs is for it to go up again then Elon will be almost almost almost done. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:02:33 </td>
   <td style="text-align:left;"> $TSLA investors aren’t stupid and nobody wants to pay capital gains tax.  Puts are the better option here…I know y’all are averse to selling but don’t be the last one to see it.  First of the year this heads to $700. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:01:20 </td>
   <td style="text-align:left;"> $tsla 🙏 who made money 💰 👏? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:01:07 </td>
   <td style="text-align:left;"> $TSLA did this just retrace 50% of the dump from high to low? Might see if retest down for support before bouncing back up? What are your thoughts or we just straight ripping to $1200? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:00:12 </td>
   <td style="text-align:left;"> These 3 Insider Trading insights were important today:

1. $SOPA 📜 SEC Form SC 13G filed by Society Pass Incorporated: https://quantisnow.com/insight/2182044?s=qnps
2. $SOPA 📜 SEC Form SC 13G filed by Society Pass Incorporated: https://quantisnow.com/insight/2182040?s=qnps
3. $TSLA 📜 SEC Form 4: Musk Elon sold $594,924,622 worth of shares (593,527 units at $1,002.35), decreasing direct ownership by 20% to 2,325,944 units to cover taxes: https://quantisnow.com/insight/2177767?s=qnps </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 08:00:05 </td>
   <td style="text-align:left;"> $TSLA TSLA is definitely bullish on bullish but this is going to be an easy short... straight up always means straight down... will double bottom at 1000 before the slow and steady climb back up... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:58:59 </td>
   <td style="text-align:left;"> $TSLA might sound so crazy but can definitely see $4-$5 trillion market cap in a few years!! 🚀🚀🚀🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:58:08 </td>
   <td style="text-align:left;"> $TSLA In investing, it is important that you look at wealth as your forest. If you do, then you let it grow &amp;amp; cancel out short term headwinds. Invest in Xceptional business for your forest. Bullish on Tesla - https://youtu.be/FJXu5HAxZ58 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:57:11 </td>
   <td style="text-align:left;"> $TSLA

$1750 within 18-24 months 👍👍👍 even more sales will be coming next year for Tesla for their new factory in the US and in Germany. We are only beginning. 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:56:55 </td>
   <td style="text-align:left;"> $TSLA Elon is playing the hedge funds Tesla is worth more than Amazon in the long term </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:55:13 </td>
   <td style="text-align:left;"> $TSLA Other than the fact that Elon Musk was Time Magazines man of the year what justifies such a high market cap especially when Tesla will be facing more competition than ever from apple Rivian and many others? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:51:42 </td>
   <td style="text-align:left;"> $TSLA Ya’ll ready to hit $1500? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:51:13 </td>
   <td style="text-align:left;"> Sweep Options Activity: $TSLA is the #1 ticker with sweep activity where institutions are trading options urgently with 146.1K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:50:55 </td>
   <td style="text-align:left;"> When you hit a rough patch and it seems like everyday is an L. Shooters keep shooting. $TSLA $SPY $CEI $METX $SEAC </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:50:22 </td>
   <td style="text-align:left;"> $TSLA MACD is about to crossover on the daily chart and we have an enormous green engulfing candle on the weekly. 

If you really think buying puts is the way to go, I&amp;#39;ve got a bridge in Brooklyn to sell you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:50:13 </td>
   <td style="text-align:left;"> $TSLA it will go back to $800s again. No worries. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:49:09 </td>
   <td style="text-align:left;"> $TSLA To the MOOON!!! 🚀🚀🚀🚀🚀🚀🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:47:57 </td>
   <td style="text-align:left;"> $TSLA ??? 😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:46:29 </td>
   <td style="text-align:left;"> $TSLA $1250 next week for sure!! 🚀🚀🚀🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:40:31 </td>
   <td style="text-align:left;"> $TSLA https://www.tesmanian.com/blogs/tesmanian-blog/tesla-megapacks-to-install-for-energy-storage-project-in-hungary 🏎🚀🤖🔋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:40:14 </td>
   <td style="text-align:left;"> $TSLA More growth, more production, more to come https://youtube.com/shorts/z34_sXBbr3Q?feature=share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:39:21 </td>
   <td style="text-align:left;"> latexaf5d1d4b87917a7af11023a1df12712etsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:39:06 </td>
   <td style="text-align:left;"> latexaf08265a559c11b1fbfdddc8d6098f12 buys in the pullback ) 

It is in a great resistance ( top of the downtrend triangle from 1240$) 

It is a fast 18% in last three days 

Will te entry on a pullback or a break of the resistance triangle  with volume </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:35:11 </td>
   <td style="text-align:left;"> $TSLA 

Fauci warns Americans not to invite unvaccinated relatives for the holidays ! 

 🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:33:28 </td>
   <td style="text-align:left;"> $TSLA Elon Claus is coming to town $spy $aapl
Tesla phone cough </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:32:04 </td>
   <td style="text-align:left;"> $TSLA bingo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:30:55 </td>
   <td style="text-align:left;"> $TSLA merry Christmas to me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:30:29 </td>
   <td style="text-align:left;"> $TSLA Simulated 1075.0 dollar CALLS for Monday&amp;#39;s open on StockOrbit.
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:28:28 </td>
   <td style="text-align:left;"> $TSLA thanks for today Elon Claus, merry Christmas to all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:24:32 </td>
   <td style="text-align:left;"> $TSLA cost of battery replacements need to be cheaper. some dude literally bombed his own car because of a $20K battery repair </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:23:50 </td>
   <td style="text-align:left;"> $AAPL Tesla will become 4 trillion before Apple $tsla $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:22:54 </td>
   <td style="text-align:left;"> $TSLA  GOOD EVENING my friends still holding a position here which i  enter 4 weeks ago. LIKE to wish everyone a merry christmas plus a blessed and safe christmas. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:22:22 </td>
   <td style="text-align:left;"> $TSLA congrats who ever got weekly calls Tuesday and turned 27$ into 5k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:22:04 </td>
   <td style="text-align:left;"> $TSLA once Tesla reach 2k, I&amp;#39;m going retire $spy
At age 23 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:20:56 </td>
   <td style="text-align:left;"> $TSLA 

Tesla Megapack Chosen for Energy Storage Project in Hungary

🙏🏻🐉🦅

https://www.tesmanian.com/blogs/tesmanian-blog/tesla-megapacks-to-install-for-energy-storage-project-in-hungary </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:20:44 </td>
   <td style="text-align:left;"> $TSLA so all buying calls? For more squeeze </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:20:07 </td>
   <td style="text-align:left;"> $TSLA $SPY 

BEARS  WHAT HAPPENED TO THE CRASH THIS WEEk???? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:19:12 </td>
   <td style="text-align:left;"> $TSLA are Grimes and Elon back together? I hope so. Grimes take care of your man! He’s a good guy, the father of your child and he needs you </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:19:00 </td>
   <td style="text-align:left;"> $TSLA when Elon Musk says i am done with selling you bears will be destroyed with a short squeeze </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:18:51 </td>
   <td style="text-align:left;"> $tsla $btc.x $qqq https://www.youtube.com/watch?v=ViWBBJtayzg&amp;amp;ab_channel=UnlimitedOptionsInvesting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:18:27 </td>
   <td style="text-align:left;"> $TSLA  Tesla Stock Will Take Off in 2022 Thanks to a New Battery Deal

https://investorplace.com/2021/12/tesla-stock-will-take-off-in-2022-thanks-to-a-new-battery-deal/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:18:04 </td>
   <td style="text-align:left;"> $TSLA btw, people mostly talk about their &amp;quot;gains&amp;quot;, less often losses.
 
But in my opinion in the case of Tesla it is more important how much we learn. This thing will run at least to $5000 during the next 9 years.  Think about it for a second, what an opportunity!
 
If you invest time in OWN DD about Tesla, it will pay off. Guaranteed! U don&amp;#39;t need any other stonk, Tesla is volatile enough.
People say &amp;quot;knowledge is power&amp;quot;, in the case of Tesla it is &amp;quot;knowledge is money&amp;quot;. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:17:59 </td>
   <td style="text-align:left;"> $TSLA 👌👏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:17:47 </td>
   <td style="text-align:left;"> $TSLA Congratz to all my bulls.  Huge 2000%+ gain on these calls in the first three hours of the day then we called it a wrap,  this one was life changing for so many of the fam. Loaded these options at $3 and sold for over $60... love this.  🤑Keep an eye on the VWAP and the 20D EMA on the 5D 5M. Watch the $1090 level pre market  Cheers!!!👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:17:37 </td>
   <td style="text-align:left;"> $TSLA I need to start playing lotto calls. The price movement has been insane the last few weeks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:16:51 </td>
   <td style="text-align:left;"> $TSLA It’s so funny to see the late buyers today crying and whining..
“Why isn’t this up more?” “It should be at $1150 already well 1200 next week because atm is too expensive”
Whaaaaa Whaaaaa Whaaaaaa…
Where were you yesterday when it was at $950 you dumbfuck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:16:10 </td>
   <td style="text-align:left;"> MOVES HAPPENING NOW (6:16pm)

⦿ $TSLA is down 0.0% in the last 5 mins. 

⦿ There are 7 stocks that are up more than 3% in the last 5 mins. 

⦿ The top gainer is up 6.2% in the last 5 mins. 

 See the stocks that are moving the most right now via link in bio (wallstreetodds .com). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:16:09 </td>
   <td style="text-align:left;"> $TSLA 

Target 55% 🔜. 🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:14:42 </td>
   <td style="text-align:left;"> $TSLA so when we have a run from 986 to 1172ish in 3 days. Do you all not have a sense of overbought territory? Overextended?

Even if you’re long Tesla. Do you not get a sense of “puts will print next week”...I feel that’s more likely than “imaginary shorts gonna cover on Monday and gap up to 4739374839339 a share!” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:13:56 </td>
   <td style="text-align:left;"> $NKLA let’s go . . $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:13:05 </td>
   <td style="text-align:left;"> $NKLA is the next $TSLA 🍁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:12:52 </td>
   <td style="text-align:left;"> $TSLA print </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:10:34 </td>
   <td style="text-align:left;"> $TSLA another beautiful slapper for the team at rvr. thank you @RiskVsReward </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:10:14 </td>
   <td style="text-align:left;"> $SPY According to my calculations and market sentiment, conditions seem prime to obtain more alpha towards my portfolio through an aggressive, short term strategy. Wow, see how easy is it to sound like you&amp;#39;re smart yoloing options? $TSLA $QQQ $AAPL $FB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:09:34 </td>
   <td style="text-align:left;"> $TSLA TSLA 2021-12-23 Daily Forecast Video: 
https://www.youtube.com/watch?v=voF1jE6q7Vk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:08:53 </td>
   <td style="text-align:left;"> Team, who’s Ready to Run  $NKLA  Back Up to $11.76 or even make a New High 🚀🚀🚀

Any $NIO or $TSLA friends making money on the Bull Flag NKLA post 💰🎁

$RIVN  friends also welcome 🎄🎅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:08:35 </td>
   <td style="text-align:left;"> $TSLA $SPY $SPX $DIA $DJIA ---

How can a company that makes poor quality vehicles (according to JD Powers), and faces competition from several major car manufacturers (Ford, Mercedes, VW, Toyota, Nissan etc) which are experts in high-volume and high-quality car production, have a stock-price near all-time highs?  If there is no clear explanation, usually this indicates that something inappropriate is going on. 
 
This situation reminds of another ‘genius’ who had revolutionized investment strategies that nobody could understand or explain (see 2001 article by Barrons) until that ‘genius’ (Madoff) was exposed for what he truly was. 

https://www.barrons.com/articles/SB989019667829349012?tesla=y </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:08:22 </td>
   <td style="text-align:left;"> $MARA $ANY $TSLA $GNUS $IDEX holy tamale. MARA is a screaming buy. 

https://www.coindesk.com/business/2021/12/23/marathon-digital-to-expand-hashrate-by-600-with-record-purchase-of-bitcoin-miners/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:07:26 </td>
   <td style="text-align:left;"> $DOGE.X $BTC.X $TSLA $AAPL $SPY Sign me up for the backseat of the car preferably the right back seat </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:06:49 </td>
   <td style="text-align:left;"> $TSLA target was money. Room banked hard!

Link in bio for free discord where i provide daily and pre mkt analysis with price targets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:06:09 </td>
   <td style="text-align:left;"> $TSLA I think it’s going to 10K because I said so, am I doing this right bulls? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:05:55 </td>
   <td style="text-align:left;"> $NKLA has anyone checked if there&amp;#39;s an actual engine inside that truck?  I&amp;#39;m scared another scam.  $NIO $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:04:36 </td>
   <td style="text-align:left;"> $TSLA $1500 can’t get here soon enough I’ll get a new car </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:03:49 </td>
   <td style="text-align:left;"> $TSLA ez 1500 in a month! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:03:39 </td>
   <td style="text-align:left;"> $TSLA 2 Billion by next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:03:19 </td>
   <td style="text-align:left;"> $ELON.X  They keep giving you hints, ARE YOU LISTENING??
👀👀👀💵💵💵
$TSLA $SHIB.X $DOGE.X 

Elon likes to play games, talk in codes, and troll people...

Look at some of the key players rumored to be tied to ELON: Vitalik Buterin, Elon Musk, and Peter Thiel....

Beyond the massive donation from Vitalik Buterin in ELON. Both Peter Thiel ($3.5 Million) and Vitalik Buterin ($2 Million) have invested personal monies in the Methuselah Foundation.  
https://www.fightaging.org/archives/2021/05/vitalik-buterin-donates-more-than-2-million-to-the-methuselah-foundation/

Methusaleh Foundation has publicly stated the creator is well known....👀👀👀

Where there is smoke there is FIRE🔥🔥🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:01:48 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ Xmas rally could be over. Dow Jones making a Head and Shoulders pattern. Next week could volatile. $AAPL $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 07:00:20 </td>
   <td style="text-align:left;"> $TSLA holding strong in AH which is great FOMO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:59:25 </td>
   <td style="text-align:left;"> $TSLA almost everyone was expecting $1030 high and consolidated around $1010.  Staying over $1060 is extremely bullish and it will definitely reclaim $1240 levels in two weeks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:58:23 </td>
   <td style="text-align:left;"> $TSLA Whenever I watch TSLA, I feel like I am on cocaine </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:55:24 </td>
   <td style="text-align:left;"> $TSLA i&amp;#39;m prediction 1053 opening on Monday... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:54:02 </td>
   <td style="text-align:left;"> $TSLA big week ahead ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:52:25 </td>
   <td style="text-align:left;"> $TSLA People talk about competition. Yes Apple have a massive competition in making Phone, tablet, computer but they are 3 trillion dollars company. You can’t compare gold to diamond </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:51:02 </td>
   <td style="text-align:left;"> $TSLA stock down .12%. What a POS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:50:17 </td>
   <td style="text-align:left;"> $TSLA There are two many amazing catalysts for Tesla in just one month. Delivery reports, earnings reports, Berlin Giga factory, expansion into India, a Giga factory in UK and more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:49:22 </td>
   <td style="text-align:left;"> $TSLA my 1200c weeklies gonna be worth $50 a pop minimum but I’ll them to you for $49 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:48:16 </td>
   <td style="text-align:left;"> $TSLA EV is a high entry barrier heavy industry, not anyone can join the party. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:47:47 </td>
   <td style="text-align:left;"> $TSLA $nkla both fireworks next week.  Too many shorts in both </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:47:24 </td>
   <td style="text-align:left;"> $TSLA I liquidated all my stocks and am all in tesla.  Next year tesla saves the planet. While everything else burns </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:47:18 </td>
   <td style="text-align:left;"> $TSLA $1200 next week or first of January </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:47:13 </td>
   <td style="text-align:left;"> $TSLA who tf is casually throwing millions at Tesla after hours </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:46:33 </td>
   <td style="text-align:left;"> $TSLA have a feeling I should’ve swung my call over the weekend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:46:07 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Tesla Will Disable Touch Screen Games While Vehicles Are In Motion Following Federal Probe https://www.stck.pro/news/TSLA/20238212 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:46:05 </td>
   <td style="text-align:left;"> $TSLA 

When is the Pi phone release date? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:46:00 </td>
   <td style="text-align:left;"> An Altman-Z score of 21.59 indicates that $TSLA is not in any danger for bankruptcy at the moment. https://www.chartmill.com/stock/analyzer/stock/TSLA?view=fundamental-analysis&amp;amp;key=b3fb89e7-ce52-4df4-906a-b4ccaf80eec8&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:45:18 </td>
   <td style="text-align:left;"> $DIA $SPY $SPX $TSLA $DJIA ----

Cult   or   Scam?

Poor quality cars but stock price near all-time highs ....

https://carbuzz.com/news/fed-up-tesla-owner-blows-up-his-model-s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:44:00 </td>
   <td style="text-align:left;"> $TSLA, $MU and $VIAC are the top gainers in the S&amp;amp;P500 for the day. https://www.chartmill.com/stock/stock-screener?v=3&amp;amp;f=ind_22&amp;amp;s=pt&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=screener&amp;amp;utm_content=Stock_Screener:_top_S&amp;amp;P500_gainers&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:43:38 </td>
   <td style="text-align:left;"> $TSLA Trash stock down .16% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:41:57 </td>
   <td style="text-align:left;"> $TSLA down .16% in after hours, what a pos </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:41:30 </td>
   <td style="text-align:left;"> $TSLA nice close! Merry Xmas! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:40:23 </td>
   <td style="text-align:left;"> Unusual Options Activity: $TSLA is the #11 ticker with unusual activity from institutional traders with an average of 30% out of the money, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:40:14 </td>
   <td style="text-align:left;"> $TSLA Don’t mess with Texas.
pic: Sarah Alfar </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:40:02 </td>
   <td style="text-align:left;"> $TSLA will gap down on monday as sp500 corrects over the long holiday weekend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:39:25 </td>
   <td style="text-align:left;"> $TSLA 🎅 rally.  Merry Christmas to all, even the angry bears. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:37:15 </td>
   <td style="text-align:left;"> $TSLA it will do this it will do that hahahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:35:03 </td>
   <td style="text-align:left;"> $TSLA Key News Update 
Tesla Will Disable Touch Screen Games 
https://www.marketwatch.com/story/tesla-promises-to-change-in-car-videogame-after-federal-investigation-launched-11640294180 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:34:54 </td>
   <td style="text-align:left;"> $TSLA No more but up form here ignored the negativities new highs 1500 for the next months </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:34:47 </td>
   <td style="text-align:left;"> $TSLA Kumo Explosion. Old highs next week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:34:23 </td>
   <td style="text-align:left;"> $TSLA 1500 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:33:12 </td>
   <td style="text-align:left;"> $TSLA very nervous this might go up or down Monday! Be careful! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:33:02 </td>
   <td style="text-align:left;"> Well done Team, I said Buy Buy Buy  $NKLA  may hit $11.50 and in minutes we hit $11.45 😎

Hope our $TSLA &amp;amp; $NIO friends got in and made some 💰

Merry Christmas Long’s and Trader’s 🎅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:32:49 </td>
   <td style="text-align:left;"> $TSLA 

Standby !

BREAKING!

🇩🇪 Giga Berlin

MD Brandenburg Economic Development Board: &amp;quot;Tesla gives wings to the business location&amp;quot;. 

&amp;#39;Tesla&amp;#39;s decision is like a &amp;quot;seal of approval&amp;quot; for the state&amp;#39; Brandenburg has become a &amp;quot;place to be&amp;quot; for the mobility of the future, sustainable economy &amp;amp; energy transition&amp;#39;

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:32:37 </td>
   <td style="text-align:left;"> $TSLA when stock split? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:32:23 </td>
   <td style="text-align:left;"> $TSLA 🎉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:31:37 </td>
   <td style="text-align:left;"> $TSLA Next week 1200 and all time highs really soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:31:14 </td>
   <td style="text-align:left;"> $TSLA how are you faggot ass bears doing today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:30:51 </td>
   <td style="text-align:left;"> $TSLA dump the turkies buy tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:30:30 </td>
   <td style="text-align:left;"> $TSLA TSLA 2021-12-23 Largest Trades Data: 
https://www.youtube.com/watch?v=FhUzFex0k5Y </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:30:08 </td>
   <td style="text-align:left;"> $TSLA

 Dumped this overvalued Hype at $1200, this is One of the best bull trap settings I have witnessed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:29:48 </td>
   <td style="text-align:left;"> $LISMF and $LIACF along sith $LAC are the only lithium plays you need to be in to help the ev push for $LCID and $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:28:14 </td>
   <td style="text-align:left;"> $TSLA Keep vaporizing the swamp and we’ll keep climbing. 

Back to ath soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:26:00 </td>
   <td style="text-align:left;"> $TSLA lol, bears where </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:23:37 </td>
   <td style="text-align:left;"> $SPY $TGGI $BTC.X $TSLA $ETH.X 
Happy Thursday folks!  Great way  to the trading  week! those in the crypto market , we’re going to fly the rest of the week!! Welcome to the revolution welcome to the good life. What an amazing year it’s been so far, I can’t wait for what  next year brings! Happy holidays to everyone stay safe love you all!!!! NEVER GIVE UP ON YOUR DREAMS! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:23:30 </td>
   <td style="text-align:left;"> $TSLA Got some calls for next week. With todays profits. If it doesn’t go my way serves me right, but I’ll bet on history. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:23:14 </td>
   <td style="text-align:left;"> $TSLA lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:21:59 </td>
   <td style="text-align:left;"> Options recap for today $TSLA , $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:20:21 </td>
   <td style="text-align:left;"> $TSLA to be more precise, the bulls are right on the long. Bears had their fun over the last few weeks with -30%, now the bulls get it all back + whats coming from the fundamentals of: 2 new factories, increased lead of competition, increased margins, software revenue, service positive for first time in history…it goes on and on. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:19:58 </td>
   <td style="text-align:left;"> $TSLA They better not update my Tesla taking out my video games!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:17:44 </td>
   <td style="text-align:left;"> $TSLA new ATH next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:16:55 </td>
   <td style="text-align:left;"> $TSLA lol the bulls are always right </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:16:12 </td>
   <td style="text-align:left;"> $TSLA the puts will print next week 🤤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:16:11 </td>
   <td style="text-align:left;"> $TSLA $SPX  will catch up to spx500 next year 5000 for both of them </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:14:29 </td>
   <td style="text-align:left;"> $TSLA damn we really gonna open up at latex99d0eec7aac3a955e59e1f1e39365adcNVDA 804k (75% call/25% put)
$AMD 707k (77% call/23% put) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:12:16 </td>
   <td style="text-align:left;"> $SPY nice call 💪 $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:12:06 </td>
   <td style="text-align:left;"> $TSLA new money flowing in. everyone who sold will be rebuying on a share split. congrats team, 1 trillion market cap killin’ 🤑⚡️🌞 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:10:21 </td>
   <td style="text-align:left;"> $TSLA   greater then 100% gains with the dec 31 1000 calls in one day all explained  in classic PowerTriggerTrade style all step by step right now we are holding the runner this video is part one  #options tesla winner  https://youtu.be/pG7iQo64Ve4
  year after year grinding with skill    this was posted yesterday if your serious for real longterm success  study the video </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:10:04 </td>
   <td style="text-align:left;"> $NKLA  formed a Perfect Pennant or Bull Flag looking to 🚀🚀🚀 after hours $11.50 be Awesome 💰

$NIO and $TSLA also Up today 🎅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:07:54 </td>
   <td style="text-align:left;"> $TSLA 100x free cash flow, this is a big bargain up here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:07:20 </td>
   <td style="text-align:left;"> $TSLA $1250 will be a deserving close for the year. 😆 Retesting All-time high. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:07:18 </td>
   <td style="text-align:left;"> $DOGE.X $TSLA $BTC.X $AAPL $ETH.X Just passing through </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:07:01 </td>
   <td style="text-align:left;"> $TSLA bear market rally, bulls will be in shambles when this is back below $1K… everyone levered long </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:07:01 </td>
   <td style="text-align:left;"> $TSLA should I get new floor mats for my new new Model 3 long range - thoughts? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:05:45 </td>
   <td style="text-align:left;"> $TSLA NEW ARTICLE : Tesla Agrees to Stop Letting Drivers Play Video Games in Moving Cars https://www.stck.pro/news/TSLA/20236209 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:05:30 </td>
   <td style="text-align:left;"> $TSLA Wow, I’m a free man holy shiiit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:04:46 </td>
   <td style="text-align:left;"> $TSLA W </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:04:01 </td>
   <td style="text-align:left;"> $NKLA I also added to my IRA this morning.. lol.. ll wait its like buying $TSLA in initial days... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:02:22 </td>
   <td style="text-align:left;"> $TSLA almost every car company got EV now ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:02:21 </td>
   <td style="text-align:left;"> $TSLA 1500C Exp:20-Jan-23 --  🚀 Total(Day): $325,600 
#UnusualActivity 
 
 
Sign-up free for beta ver.:https://app.jarvisalerts.com 
charts: courtesy of finviz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:02:18 </td>
   <td style="text-align:left;"> $TSLA 1200C Exp:18-Feb-22 --  🚀 Total(Day): $87,000 
$TSLA 1245C Exp:31-Dec-21 ↑  🚀 Total(Day): $54,605 
$TSLA 1500C Exp:18-Feb-22 --  🚀 Total(Day): $111,520 
#UnusualActivity 
 
 
Sign-up free for beta ver.:https://app.jarvisalerts.com 
charts: courtesy of finviz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:02:15 </td>
   <td style="text-align:left;"> $TSLA bears still trying to compare this to other car companies, lmao. This is all about Elon, and the Tesla brand. It’s a cult. Demand for decades </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:02:15 </td>
   <td style="text-align:left;"> $TSLA 1200C Exp:21-Jan-22 --  🚀 Total(Day): $27,000 
$TSLA 1200C Exp:07-Jan-22 ↑↑  🚀 Total(Day): $29,522 
$TSLA 1200C Exp:31-Dec-21 ↑  🚀 &amp;lt;R&amp;gt; Total(Day): $110,446 
#UnusualActivity 
 
 
Sign-up free for beta ver.:https://app.jarvisalerts.com 
charts: courtesy of finviz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:02:13 </td>
   <td style="text-align:left;"> $REDU 

Boom $1 by 8pm

 $TSLA $SOPA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:02:12 </td>
   <td style="text-align:left;"> $TSLA 1150C Exp:31-Dec-21 ↑  🚀 &amp;lt;R&amp;gt; Total(Day): $344,790 
$TSLA 1150C Exp:16-Sep-22 --  🚀 Total(Day): $298,290 
$TSLA 1180C Exp:07-Jan-22 ↑↑  🚀 &amp;lt;R&amp;gt; Total(Day): $104,040 
#UnusualActivity 
 
 
Sign-up free for beta ver.:https://app.jarvisalerts.com 
charts: courtesy of finviz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:02:09 </td>
   <td style="text-align:left;"> $TSLA 1120C Exp:31-Dec-21 ↑  🚀 Total(Day): $39,390 
$TSLA 1125C Exp:21-Jan-22 --  🚀 Total(Day): $37,260 
$TSLA 1145C Exp:31-Dec-21 ↑  🚀 Total(Day): $134,475 
#UnusualActivity 
 
 
Sign-up free for beta ver.:https://app.jarvisalerts.com 
charts: courtesy of finviz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:02:06 </td>
   <td style="text-align:left;"> $TSLA 1100C Exp:21-Jan-22 --  🚀 &amp;lt;R&amp;gt; Total(Day): $1,288,814 
$TSLA 1100C Exp:07-Jan-22 ↑↑  🚀 Total(Day): $187,860 
$TSLA 1105C Exp:31-Dec-21 ↑  🚀 Total(Day): $28,000 
#UnusualActivity 
 
 
Sign-up free for beta ver.:https://app.jarvisalerts.com 
charts: courtesy of finviz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:02:04 </td>
   <td style="text-align:left;"> $TSLA 1095C Exp:31-Dec-21 ↑  🚀 Total(Day): $41,990 
$TSLA 1100C Exp:31-Dec-21 ↑  🚀 &amp;lt;R&amp;gt; Total(Day): $2,234,481 
$TSLA 1100C Exp:23-Dec-21 ↑↑  🚀 Total(Day): $35,624 
#UnusualActivity 
 
 
Sign-up free for beta ver.:https://app.jarvisalerts.com 
charts: courtesy of finviz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:02:03 </td>
   <td style="text-align:left;"> $TSLA Simulated 1075.0 dollar CALLS for Friday&amp;#39;s open on StockOrbit.
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:02:01 </td>
   <td style="text-align:left;"> $TSLA 1050C Exp:31-Dec-21 ↑  🚀 &amp;lt;R&amp;gt; Total(Day): $332,969 
$TSLA 1050C Exp:23-Dec-21 ↑↑  🚀 &amp;lt;R&amp;gt; Total(Day): $156,100 
$TSLA 1075C Exp:31-Dec-21 ↑  🚀 Total(Day): $47,343 
#UnusualActivity 
 
 
Sign-up free for beta ver.:https://app.jarvisalerts.com 
charts: courtesy of finviz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:01:40 </td>
   <td style="text-align:left;"> $TSLA $1150-$1200 next week no doubt </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:01:02 </td>
   <td style="text-align:left;"> $TSLA the one i&amp;#39;m laughing about the most.  the bag holders on this stock will be amongst the worst bag holders of all time i suspect. 

when all manufacturers have full product lines of EV&amp;#39;s and govt rebates providing incentives for all EV&amp;#39;s. and Tesla revenue numbers start plummeting I&amp;#39;ll be laughing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:00:24 </td>
   <td style="text-align:left;"> $TSLA TSLA 2021-12-23 Options Analysis Video: 
https://www.youtube.com/watch?v=qzDouDYbflI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:00:22 </td>
   <td style="text-align:left;"> $TSLA  beast mode. Everybody wants to have a piece of the Elon magic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:00:19 </td>
   <td style="text-align:left;"> $TSLA fucking love tesla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 06:00:13 </td>
   <td style="text-align:left;"> Challenge up over 100% in 4 trading days SNEAKY SNAKE OPTIONS Challenge $TSLA $SPY $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 05:58:41 </td>
   <td style="text-align:left;"> $TSLA smart enough to let the driver play game in their cars while they driving </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 05:58:31 </td>
   <td style="text-align:left;"> Upset I didn’t even watch $TSLA all week and missed out on $ 1000 Calls. They PAID! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 05:57:47 </td>
   <td style="text-align:left;"> $TSLA who is ready for $2K in 2022? Merry Christmas and happy holidays all! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 05:56:19 </td>
   <td style="text-align:left;"> $TSLA I really think it&amp;#39;s funny how this stock stomps the performance of others like AMD, and all you hear when it&amp;#39;s brought up is a boatload of cope and &amp;quot;but muh YTD Lisa Su is BAE&amp;quot;.

Elon is an actual leader and knows how the market works. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 05:55:56 </td>
   <td style="text-align:left;"> $TSLA Merry Christmas to all the Bulls and Bears relax and enjoy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 05:55:53 </td>
   <td style="text-align:left;"> $TSLA stock is still cheap.  P/E number is still lower than the stock price </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 05:54:04 </td>
   <td style="text-align:left;"> $TSLA this ponzi is &amp;quot;valued&amp;quot; just shy of the number of US dollars in circulation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 05:53:19 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 05:51:42 </td>
   <td style="text-align:left;"> $TSLA  looks like 300,000 teslas will need to be investigated per https://www.bloomberg.com/news/articles/2021-12-23/tesla-disables-video-game-function-in-cars-that-triggered-probe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 05:51:40 </td>
   <td style="text-align:left;"> $TSLA Didn’t hit my $1088 PT for exiting to hit an arbitrary goal, but it is over my $1050 PT to claim the $1.2M YTD in gains.  Likely will sell after hours, but watching to see if there’s a push over 1070 after options exercise deadline passes for most retail.  
Selling for two reasons:
Clear my account so I can end the year at a nice clean profit milestone.
Elon still has options to exercise and shares to sell next week.  If he does it early in the week, I may buy back in mid-week.  If not, I’ll buy 12/31 EOD or the following Monday.  
GLTA and happy holidays! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 05:51:21 </td>
   <td style="text-align:left;"> $TSLA goin tuh 1500 dey make dem purdy cars.  stonks gonin up for evr .  HODL. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 05:50:49 </td>
   <td style="text-align:left;"> $FUBO more CNBC halftime action on Monday maybe @Elon_Musk and @DavidGandlerCEO will have that call America’s favorites $TSLA and $FUBO TV </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 05:49:18 </td>
   <td style="text-align:left;"> $TSLA 

https://www.bloomberg.com/news/articles/2021-12-23/tesla-disables-video-game-function-in-cars-that-triggered-probe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 05:48:46 </td>
   <td style="text-align:left;"> $TSLA Merry Christmas to all, I decided to close my long position today of 5,000 shares before the close. What Elon said the other day during an interview didn’t sit comfortably with me and the guy has lost a ton of my respect over the past year. I was a Tesla bull for a very long time but can’t stand what the CEO has been doing these past few months. It seems to me that he’s now become very materialistic and worried about his stock rather than shaping the world into a better place. It took everything in me to close out my position but I felt that was the right thing to do, good luck to all and wish you the best on this board. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 05:47:45 </td>
   <td style="text-align:left;"> $TSLA Is Elon the MMs? Dude really control the price of this stock. Really. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 05:46:50 </td>
   <td style="text-align:left;"> $TSLA Trade like Nancy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 05:46:11 </td>
   <td style="text-align:left;"> $TSLA uh oh! Back to 700$ we go right bears?😂😂😂😂😂😂😂😂😂😂😂😂😂😂😂😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 05:45:34 </td>
   <td style="text-align:left;"> $TSLA Generally that week all go down badly! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2021-12-24 05:45:20 </td>
   <td style="text-align:left;"> $TSLA I Have Paper Hands Won&amp;#39;t be Able to Sleep Tonight Missed out on $20k Profits SMH 😔😔 </td>
  </tr>
</tbody>
</table></div>

---
