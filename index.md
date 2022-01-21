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



Last Updated: 2022-01-21 09:35:40 UTC +8

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
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-01-21 09:19:00 </td>
   <td style="text-align:left;"> US Futures Fall After Netflix’s Earnings Disappoint </td>
   <td style="text-align:left;"> US stock futures fell on Friday following a disappointing earnings report from Netflix, extending the major averages' losses from the previous session. Dow futures shed 0.2%, while S&amp;P 500 and Nasdaq 100 futures dropped 0.5% and 0.9%, respectively. Losses were triggered after Netflix tumbled 20% on after-hours trading as the company’s fourth-quarter earnings report showed a slowdown in subscriber growth. Peloton also plunged 23.93% in the regular session after CNBC reported the company is temporarily halting production of its fitness products. During regular trading on Thursday, the three indices gave up early gains and fell precipitously into the close, as the selling pressure on technology and other growth stocks continued on prospects of higher interest rates. Thursday’s decline puts the Nasdaq Composite further in correction territory at 12.7% below its November peak. The Dow and S&amp;P 500, meanwhile, are at least 6% below their recent peaks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-01-21 09:10:04 </td>
   <td style="text-align:left;"> Crude Oil traded above 83 USD/Bbl </td>
   <td style="text-align:left;"> Crude Oil WTI rose above 83, according to trading on a contract for difference (CFD). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60063606?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-21 09:00:14 </td>
   <td style="text-align:left;"> Covid test firm urges end to tests for travellers </td>
   <td style="text-align:left;"> Covid tests for travellers arriving in the UK should be scrapped, one of the big testing firms has said.                                                                                                                                                  , Simon Worrell, global medical director of Collinson - which also runs airport lounges - said: "As soon as we can drop it, we will be delighted."                                                                                                          , At present, all those aged five and over arriving in England must take a test within 48 hours of arriving.                                                                                                                                                , Prime Minister Boris Johnson said on Wednesday the government was reviewing testing arrangements for travel.                                                                                                                                              , He said the Health Secretary Sajid Javid would announce the outcome of the review in the coming days.                                                                                                                                                     , Mr Worrell said Collinson, which has a large travel business that includes running customer services in airports, launched its testing sites early in the pandemic in a bid to prop up the travel industry, which a large part of his business depends on., But now, with more people able to return to the skies, the requirement for people to test on arrival has become more of a hindrance to the business, because it may put them off travelling.                                                              , The travel industry has continually voiced its objection to testing. Manchester Airports Group and Airlines UK on Friday renewed their calls for testing rules to become a thing of the past for fully vaccinated travellers.                             , But virologists have expressed caution. Dr Stephen Griffin from the University of Leeds said: "You have a moral responsibility to monitor and to know if you're infectious. It is a good idea to test."                                                   , Collinson was one of the first operators to run Covid testing stations at airports and also distributes tests through the post. It partners with a number of UK airlines and travel operators.                                                            , Mr Worrell said: "Airport testing was only ever supposed to be a band-aid, a temporary solution to get trade and tourism staggering whilst we build up immunity and we are able to fight the virus by ourselves. We are at that point now.                , "The link between getting infected and hospitalisation has been broken. We are in a fantastic place - the envy of the world, I think."                                                                                                                    , Covid testing for travellers has been controversial and the government has faced criticism over its regulation of the sector.                                                                                                                             , Consumer rights groups said the Department for Health and Social Care had not done enough to protect consumers from what was called a "predictable Covid rip-off".                                                                                        , The government did launch an investigation to remove operators who were selling tests that, in some instances, were too cheap or not available at the price advertised.                                                                                   , But those in the medical community are alarmed that testing for those arriving back in the UK could be removed.                                                                                                                                           , Dr Eleanor Gaunt, who investigates the genetic coding of viruses at the University of Edinburgh, said: "I fully agree that this needs to happen, but the timing is premature.                                                                             , "It is entirely possible that Omicron will be succeeded by a new variant and possibly one that can circumvent immunity provided by vaccination and previous infection.                                                                                    , "Therefore we need eyes on what viruses are moving where, until the virus becomes more predictable and endemic."                                                                                                                                          , Yet not everyone in the scientific community believes testing for travellers arriving into the UK should remain.                                                                                                                                          , Dr Bharat Pankhania, from the University of Exeter Medical School, believes that it is time for travel tests to end, as long as community testing remains in place to identify variants of concern.                                                       , Go behind the scenes at London's Corinthia Hotel                                                                                                                                                                                                          , Hidden Assets: A gritty Irish crime thriller on BBC iPlayer                                                                                                                                                                                               , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-21/more-advisers-eyed-bond-rally-peters-out-evergrande-update?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-21 08:41:21 </td>
   <td style="text-align:left;"> More Advisers Eyed; Bond Rally Peters Out: Evergrande Update </td>
   <td style="text-align:left;"> Unfinished apartment buildings at the construction site of a China Evergrande Group development in Beijing.                                                                                                                                                                                         , Hong Shen                                                                                                                                                                                                                                                                                           , China Evergrande Group’s risk management committee plans to hire additional financial and legal advisers to help the embattled developer deal with its debt stress and respond to creditors’ demands.                                                                                               , The announcement came a day after a bondholder group said Evergrande had failed to substantially engage with it on restructuring efforts. The group said it will “seriously consider enforcement actions” to protect investors’ interests and wants to be consulted before any more assets are sold. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/food-inflation </td>
   <td style="text-align:left;"> 2022-01-21 08:29:00 </td>
   <td style="text-align:left;"> Japan Food Inflation Rate at 16-Month High </td>
   <td style="text-align:left;"> Food prices in Japan increased by 2.1 percent year-on-year in December 2021, the most since August 2020 and after a 1.4 percent gain in the previous month. The latest reading also pointed to the fourth straight month of rises in cost of food, with main upward pressure largely coming from fresh food (8% vs 3.1% in November), fish &amp; seafood (6.3% vs 5.2%), fresh vegetables (6.6% vs -1.4%), meats (1.9% vs 1.8%), fresh fruits (9.1% vs 6.4%), cakes &amp; candies (1.9% vs 1.5%), oils, fats (2.3% vs 2.6%), beverages (2.4% vs 2.5%), meals outside the home (0.9% vs 0.9%), and cooked food (1.6% vs 1.7%). In contrast, prices declined further for cereal (-1.3% vs -0.9%) and alcoholic beverages (-0.5% vs -0.5%), with cost of dairy products falling for the first time in six months (-0.1% vs 0.3%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/consumer-confidence </td>
   <td style="text-align:left;"> 2022-01-21 08:24:00 </td>
   <td style="text-align:left;"> UK Consumer Confidence Drops to 11-Month Low </td>
   <td style="text-align:left;"> The GfK Consumer Confidence indicator in the United Kingdom dropped to its lowest level in 11 months at minus 19 in January 2022, as consumer mood was dampened by persistently high inflation, suggesting that rising living costs will slow the household spending recovery. This followed a reading of minus 15 in December 2021 and logged below analyst expectations of no change from the previous month. Joe Staton, client strategy director at GfK, said that “despite some good news about the easing of Covid restrictions, consumers are clearly bracing themselves for surging inflation, rising fuel bills and the prospect of interest rate rises." All components of the index deteriorated, with measures that look at how people see the coming year in terms of personal financial situation and in making big purchases falling sharply and pointing to concerning personal spending patterns. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-21/ex-daimler-boss-tapped-for-new-kensington-auto-focused-spac?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-21 08:22:37 </td>
   <td style="text-align:left;"> Ex-Daimler Boss Tapped for New Kensington Auto-Focused SPAC </td>
   <td style="text-align:left;"> Dieter Zetsche                                                                                                                                                                                                                                         , Edward Ludlow                                                                                                                                                                                                                                          , Kensington Capital, whose blank-check firms have already taken public QuantumScape Corp. and Wallbox NV, has tapped former Daimler AG chief Dieter Zetsche as vice chairman for a fourth automotive-focused special purpose acquisition company.       , Its latest SPAC, Kensington Capital Acquisition Corp IV, filed Thursday to raise $200 million in an initial public offering. The company said it will focus on acquiring a business “operating in the global automotive and automotive-related sector.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-21/japan-s-topix-falls-1-8-takes-drop-from-september-peak-to-10?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-21 08:10:22 </td>
   <td style="text-align:left;"> Japan’s Topix Falls 1.8%, Takes Drop From September Peak to 10% </td>
   <td style="text-align:left;"> Min Jeong Lee                                                                                                                                                                                                                                            , Japan’s Topix index is set to follow the technology-heavy Nasdaq 100 into a correction amid concerns over the potential for monetary policy tightening in the U.S. and the global struggle to contain the pandemic.                                      , The Topix fell as much as 1.8% on Friday, extending its decline to 10% from a 31-year high marked in September. The Nasdaq 100 erased a near 2% rally before ending in the red on Thursday, while the S&amp;P 500 remained more than 5% off its January high. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-21/evergrande-to-hire-advisers-on-debt-risks-creditor-demands?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-21 08:09:14 </td>
   <td style="text-align:left;"> Evergrande to Hire Advisers on Debt Risks, Creditor Demands </td>
   <td style="text-align:left;"> Unfinished apartment buildings at the construction site of a China Evergrande Group development in Wuhan, China.                                                                                                                , Russell Ward                                                                                                                                                                                                                    , China Evergrande Group’s risk management committee plans to hire additional financial and legal advisers to help the embattled developer deal with its debt stress and respond to creditors’ demands.                           , The panel proposes to engage China International Capital Corp. and BOCI Asia Ltd. as financial advisers, and Zhong Lun Law Firm LLP as a legal adviser, the company said Friday in a statement to the Hong Kong stock exchange.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/inflation-cpi </td>
   <td style="text-align:left;"> 2022-01-21 08:09:00 </td>
   <td style="text-align:left;"> Japan Consumer Prices Rise the Most in 2 Year </td>
   <td style="text-align:left;"> Japan's consumer prices rose by 0.8% yoy in December 2021, accelerating from a 0.6% gain a month earlier and pointing to the 4th straight month of increase.  The latest figure was also the highest annual inflation rate since December 2019, boosted by a sharp pickup in food prices and a further rise in housing cost. Food prices went up 2.1% yoy, the most since August 2020, after a 1.4 percent gain in November. Additional upward pressure also came from housing (0.7% vs 0.7% in November), fuel, light and water charges (11.2% vs 9.2%), clothes &amp; footwear (0.3% vs 0.1%), education (1.2% vs 1.2%), culture &amp; recreation (3.9% vs 4.3%), and miscellaneous (1.3% vs 1.2%). In contrast, cost fell further for transport (-7.5% vs -6.9%), medical care (-0.1% vs -0.2%), and furniture and household utensils (-0.8% vs 0.4%). Core consumer prices gained 0.5% yoy, the same as in November, staying at their highest in almost 2 years amid high energy prices while remaining well below the BoJ’s 2% target. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.marketwatch.com/story/good-luck-well-all-need-it-u-s-market-approaches-end-of-superbubble-says-jeremy-grantham-11642723516 </td>
   <td style="text-align:left;"> 2022-01-21 08:05:00 </td>
   <td style="text-align:left;"> ‘Good luck! We’ll all need it’: U.S. market approaches end of ‘superbubble,’ says Jeremy Grantham - MarketWatch </td>
   <td style="text-align:left;"> The U.S. is approaching the end of a “superbubble” spanning across stocks, bonds, real estate and commodities following massive stimulus during the COVID pandemic, potentially leading to the largest markdown of wealth in its history once pessimism returns to rule markets, according to legendary investor Jeremy Grantham.                                                                                                                      , “For the first time in the U.S. we have simultaneous bubbles across all major asset classes,” said Grantham, co-founder of investment firm GMO, in a paper Thursday. He estimated wealth losses could total $35 trillion in the U.S. should valuations across major asset classes return two-thirds of the way to historical norms.                                                                                                                    , “One of the main reasons I deplore superbubbles — and resent the Fed and other financial authorities for allowing and facilitating them — is the underrecognized damage that bubbles cause as they deflate,” said Grantham.                                                                                                                                                                                                                            , The Federal Reserve doesn’t seem to “get” asset bubbles, said Grantham, pointing to the “ineffably massive stimulus for COVID” (some of which he said was necessary) that followed stimulus to recover from the bust of the 2006 housing bubble. “The only ‘lesson’ that the economic establishment appears to have learned from the rubble of 2009 is that we didn’t address it with enough stimulus,” he said.                                       , Equity bubbles tend to begin to deflate from the riskiest parts of the market first — as the one that Grantham is warning about has been doing since February 2021, according to his paper. “So, good luck!” he wrote. “We’ll all need it.”                                                                                                                                                                                                            , While the S&amp;P 500 index 
        SPX,
        -1.10%
       and Dow Jones Industrial Average 
        DJIA,
        -0.89%
       each notched all-time closing peaks in early January, they’ve since fallen into a slump, along with the Nasdaq Composite Index 
        COMP,
        -1.30%,
       as investors anticipate the Fed will end quantitative easing and begin raising interest rates to combat high inflation later this year., Read: Why 2022 appears ‘a perfect negative storm’ for tech stocks, according to Deutsche Bank                                                                                                                                                                                                                                                                                                                                                          , The technology-laden Nasdaq has seen the biggest decline among the three major stock benchmarks in 2022, tumbling into correction territory after reaching a record high in November, according to FactSet data.                                                                                                                                                                                                                                       , “We are in what I think of as the vampire phase of the bull market, where you throw everything you have at it,” Grantham wrote. “You stab it with COVID, you shoot it with the end of QE and the promise of higher rates, and you poison it with unexpected inflation – which has always killed P/E ratios before, but quite uniquely, not this time yet – and still the creature flies.”                                                              , That is “until, just as you’re beginning to think the thing is completely immortal, it finally, and perhaps a little anticlimactically, keels over and dies,” said Grantham. “The sooner the better for everyone.”                                                                                                                                                                                                                                     , The Nasdaq has dropped 9.5% this month, through Thursday, exceeding the S&amp;P 500’s nearly 6% slide and a 4.5% loss for the Dow, according to FactSet data.                                                                                                                                                                                                                                                                                              , As for GMO’s investment recommendations, Grantham summarized them as avoiding U.S. equities while emphasizing value stocks in emerging markets and cheaper developed countries, “most notably Japan.” On a personal note, he said, “I also like some cash for flexibility, some resources for inflation protection, as well as a little gold 
        GC00,
        -0.23%
       and silver.”                                                      , Beyond the recent record highs of the U.S. stock market and “crazy” investor behavior that has accompanied its rise, Grantham warned that “we are indeed participating in the broadest and most extreme global real-estate bubble in history.”  He said that houses in the U.S. are at “the highest multiple of family income ever, after a record 20% gain last year.”                                                                                , Plus, said Grantham, “we also have the highest-priced bond markets in the U.S. and most other countries around the world, and the lowest rates, of course, that go with them, that human history has ever seen.”                                                                                                                                                                                                                                       , And then there’s the “incipient bubble in commodities,” he added. Oil 
        CL00,
        -2.84%
       and most of the “important metals” are among commodities priced broadly “above trend,” while the “U.N.’s index of global food prices is around its all-time high,” according to his paper.                                                                                                                                               , “The combination, which we saw in 2008, of still-rising commodity prices with a deflating asset price bubble is the ultimate pincer attack on the economy and is all but guaranteed to lead to major economic pain,” he wrote.                                                                                                                                                                                                                         , Grantham also considered how wealth compounds more slowly at “bubble pricing,” while making it hard for people to afford their first house or to build an investment portfolio.                                                                                                                                                                                                                                                                        , “There is the terrible increase in inequality that goes with higher prices of assets, which many simply do not own, and  ‘many’ applies these days up to the median family or beyond,” he wrote. “They have been let down, know it, and increasingly (and understandably) resent it. And it absolutely hurts our economy.”                                                                                                                             ,                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Tech stocks are sensitive to bond yields, and the yield on the benchmark 10-year U.S. Treasury note is at its highest level in two years.                                                                                                                                                                                                                                                                                                              ,                                                                                                                                                                                                                                                                                                                                                                                                                                                        , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/japan/stock-market </td>
   <td style="text-align:left;"> 2022-01-21 08:03:20 </td>
   <td style="text-align:left;"> Nikkei 225 is down by 2.07% </td>
   <td style="text-align:left;"> Nikkei 225 decreased 2.07% to 27199 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60069429?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-21 08:01:02 </td>
   <td style="text-align:left;"> Trains told to get rid of torrent of 'Tannoy spam' </td>
   <td style="text-align:left;"> If you're a commuter returning to the office after a long period of working from home, you may soon notice a subtle difference on your morning train.                                                                                             , In the next few months, rail chiefs will be getting rid of unnecessary announcements to make journeys quieter.                                                                                                                                    , Examples of so-called "Tannoy spam" include telling passengers to have their tickets ready and, ironically, to keep the noise down.                                                                                                               , But the Department for Transport (DfT) said key safety messages would remain.                                                                                                                                                                     , That probably means a reprieve for the British Transport Police's "See it. Say it. Sorted" announcement, branded "the most annoying slogan of the century".                                                                                       , The DfT said it would be working closely with the Rail Delivery Group and passenger groups such as Transport Focus, as well as train operators, to identify how the "vast number" of announcements could be cut or reduced.                       , "The review will take place over the course of this year, with redundant messages identified and starting to be removed in the coming months," it added.                                                                                          , The announcement comes as many office workers are preparing to resume regular journeys to their workplace, after the government scrapped its work-from-home guidance for England with immediate effect.                                           , "As passengers come back to the railways, the DfT will continue to ensure journeys are more comfortable to all users, and that passengers continue to receive the important information that they need about their journey," the department said. , "Officials will work with accessibility groups to ensure that access for all is maintained."                                                                                                                                                      , Transport Secretary Grant Shapps said train passengers were all too often "plagued by an endless torrent of repeated and unnecessary announcements".                                                                                              , "In line with the passenger improvements we are rolling out with our Plan for Rail, we want to see improvements to the railways for those who use them day-in day-out," he added.                                                                 , "That's why I'm calling for a bonfire of the banalities to bring down the number of announcements passengers are forced to sit through and make their journey that little bit more peaceful."                                                     , The move was welcomed by Transport Focus and the Rail Delivery Group.                                                                                                                                                                             , Go behind the scenes at London's Corinthia Hotel                                                                                                                                                                                                  , Hidden Assets: A gritty Irish crime thriller on BBC iPlayer                                                                                                                                                                                       , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/kudlow-radical-transformation-behemoth-government </td>
   <td style="text-align:left;"> 2022-01-21 07:57:00 </td>
   <td style="text-align:left;"> Kudlow: Voters do not want a radical transformation toward behemoth government </td>
   <td style="text-align:left;"> ‘Kudlow’ breaks down Biden’s dropping approval ratings one year into his presidency.                                                                                                                                                                                                                                                                                                                        , So, no reset or midcourse changes for President Joe Biden. That's what we learned in yesterday's presser. Big government socialist policies are alive and well. In fact, he's doubling down.                                                                                                                                                                                                                , According to Mr. Biden the polls are wrong, you see, the country really loves him and his policies. So his job is to travel around and better communicate his achievements and his goals to the American people. That's basically how I read yesterday's performance.                                                                                                                                       , Trouble is for Uncle Joe, the public actually knows full well what his so-called achievements and policies are. Voters are smarter than the radical left thinks. Polling is as much art as science, but seldom have I seen as much unanimity.                                                                                                                                                               , BIDEN'S FIRST YEAR: TRACKING THE US ECONOMY'S RECOVERY FROM THE PANDEMIC                                                                                                                                                                                                                                                                                                                                    , From Byron York's column yesterday, the Gallup poll shows a remarkable swing from a year ago, when 49% considered themselves Democrats against 40% Republicans. Now it's just 42% Democrats against 47% Republicans. That's a net 14-point swing over just one year. Unprecedented.                                                                                                                         , Basically, Mr. Biden is selling a product that voters do not want to buy. The CBS and other polls show that voters are worried about inflation, COVID, crime, groceries on the shelf and gasoline at the pump, and illegal immigration.                                                                                                                                                                     , Biden's been on the wrong side of every one of these issues. That includes the racially divisive pitch to federalize voting procedures, which fortunately failed last night.                                                                                                                                                                                                                                , Real Clear Politics' average of polls has Biden at 41.8% approval, and 52.6% disapproval.                                                                                                                                                                                                                                                                                                                   , On handling the economy, the CBS poll has 38% Biden approval, and 62% disapproval. On inflation, he's underwater 30 to 70%. On crime, 39 to 61%. On immigration, 36 to 64%. Remarkable.                                                                                                                                                                                                                     , Yesterday, the President said he does not believe the polls. Well, ok, sir, but you do so at your own peril. The country is not with you. It does not want a radical transformation toward behemoth government, confiscatory taxes, a command and control regulatory state, skyrocketing energy prices, substituting government for family and parents, and a radical decline in American prestige overseas., OIL NEARS $87 AFTER KEYSTONE PIPELINE CANCELED ONE YEAR AGO                                                                                                                                                                                                                                                                                                                                                 , First the Afghanistan catastrophe, and now there could be a complete mess with Putin in Ukraine. All of which emboldens China.                                                                                                                                                                                                                                                                              , Regarding so-called "Build Back Better" we have saved America, and we have killed the bill. Yesterday, Mr. Biden said he's going to break it up into many smaller 'chunks'. As in, Build Back Smaller. But these chunks mean abandoning reconciliation because the chunks won't pass as stand-alones.                                                                                                       , Nancy Pelosi is smarter, because she doesn't like chunks, she prefers reconciliation. Biden and his advisors look half-baked on this, and haven't figured out the chocolate sauce that can pull it all together.                                                                                                                                                                                            , As usual, Joe Manchin has the story right. Once again, he declared his prior budget talks are now off the table, and to get anything done they'll now have to start over.                                                                                                                                                                                                                                   , I think the whole Biden agenda is a fiasco, and he is the only person in America that spending another $5 trillion will actually reduce inflation. Or that adding $3 trillion in debt is a pay-for. Or that higher taxes at the same time the Fed is tightening money is pro-growth.                                                                                                                        , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                 , It's not. Tax hikes and tighter money is like a root canal without Novocaine. You want to boost the dollar and curb inflation? Then cut taxes and regulations, don't raise them.                                                                                                                                                                                                                            , Anyway, yesterday was not a great success for our President. The American people are saying no, while he is still saying yes.                                                                                                                                                                                                                                                                               , The people are going to win, he's going to lose, and I'm saying...it's over, it's over. Save America, kill the bill. And that's my riff.                                                                                                                                                                                                                                                                    , This article is adapted from Larry Kudlow's opening commentary on the January 20, 2022, edition of "Kudlow."  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/el:us </td>
   <td style="text-align:left;"> 2022-01-21 07:56:17 </td>
   <td style="text-align:left;"> Estée Lauder earnings below expectations at 2.62 USD </td>
   <td style="text-align:left;"> Estée Lauder (EL) released earnings per share at 2.62 USD, compared to market expectations of 2.64 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-21 07:49:28 </td>
   <td style="text-align:left;"> US 10Y traded above 1.8 percent </td>
   <td style="text-align:left;"> US 10 Year Note Bond Yield rose above 1.8, according to over-the-counter interbank yield quotes for this government bond maturity. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-20/oil-extends-drop-from-seven-year-high-as-u-s-stockpiles-expand?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-21 07:45:21 </td>
   <td style="text-align:left;"> Oil Extends Drop From Seven-Year High as U.S. Stockpiles Expand </td>
   <td style="text-align:left;"> Elizabeth Low                                                                                                                                                                                                                                                                                                                                                                             , Oil extended its decline from the highest level since 2014 -- following a decline in U.S. stocks -- after a surprise gain in American crude inventories and a larger than expected increase in gasoline supplies.                                                                                                                                                                         , Futures in New York fell more than 3% in early Asian trading to below $83 a barrel. Crude stockpiles rose for the first time in eight weeks, while gasoline supplies expanded by more than double the median forecast in a Bloomberg survey, according to government data. The White House also said it can work to accelerate the release of strategic oil reserves after prices rallied. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/20/stock-market-futures-open-to-close-news.html </td>
   <td style="text-align:left;"> 2022-01-21 07:08:31 </td>
   <td style="text-align:left;"> Nasdaq 100 futures fall after Netflix's earnings disappoint </td>
   <td style="text-align:left;"> , U.S. stock index futures were lower during overnight trading Thursday following a disappointing earnings report from Netflix, building on the major averages' declines during regular trading.                                                                                                                                                                                                                , Futures contracts tied to the Dow Jones Industrial Average shed 14 points. S&amp;P 500 futures were down 0.24%, while Nasdaq 100 futures declined 0.6%.                                                                                                                                                                                                                                                           , Shares of Netflix tumbled 19% during extended trading on Thursday after the company's fourth-quarter earnings report showed a slowdown in subscriber growth. Peloton, meantime, plunged 23.9% during regular trading after CNBC reported that the company is temporarily halting production of its fitness products.                                                                                          , During regular trading, the Dow shed 313 points, or 0.89%. At one point during the session, the 30-stock benchmark was up more than 450 points. A similar reversal played out for the other major averages. The S&amp;P declined 1.1% after earlier advancing 1.53%. The Nasdaq Composite ended the day with a loss of 1.3%, reversing a prior move that had the tech-heavy index up 2.1%.                        , "The market has been flashing faulty signals for the past few weeks and it seems as if the broader indices are finally breaking down," said Scott Redler of T3 Live. The S&amp;P 500 closed below 4,500 on Thursday for the first time since October 18, which Redler said is important from a technical standpoint and "opens the door for a targeted move to at least 4,320, which would take the S&amp;P down 10%.", Thursday's slide puts the Nasdaq Composite further in correction territory — more than 10% below its November record — as rising rates pressure technology stocks since future profits begin to look less attractive.                                                                                                                                                                                         , Jeremy Grantham says the end of 'bubble extravaganza' is coming, calls for stocks to drop 45%                                                                                                                                                                                                                                                                                                                 , These 8 stocks are set to outperform as inflation mounts, HSBC says                                                                                                                                                                                                                                                                                                                                           , Failed market rally signals more trouble ahead for stocks                                                                                                                                                                                                                                                                                                                                                     , The yield on the benchmark 10-year Treasury touched 1.87% Thursday, ahead of the Federal Reserve's two-day meeting next week.                                                                                                                                                                                                                                                                                 , "While a handful of rate hikes over the next year or two would represent a shift in Fed policy, we wouldn't consider policy restrictive and we don't expect the initial rate increase to derail the economic recovery," said Scott Wren, senior global market strategist at Wells Fargo Investment Institute. However, he added that rate hikes will inject volatility into the market.                       , Both the Dow and S&amp;P 500 are on track for a third straight week of losses. The Nasdaq Composite is down nearly 5% on the week, putting it on track for its fourth-straight losing week and largest weekly loss since Oct. 2020. Small caps have also been hit hard, and the Russell 2000 is on track for its worst week since June 2020.                                                                      , Amid the sell-off in technology names, some believe there's value to be had in select stocks.                                                                                                                                                                                                                                                                                                                 , "With the broader Nasdaq in correction territory, we see opportunities in specific areas of the tech sector, such as semiconductors, cloud stocks and mega-cap stocks," said Robert Schein, chief investment officer at Blanke Schein Wealth Management. But he was quick to note that he does not see the pullback as a "widespread buy the dip moment."                                                     , On the earnings front, Schlumberger will post results before the market opens on Friday.                                                                                                                                                                                                                                                                                                                      , - CNBC's Patti Domm contributed reporting.                                                                                                                                                                                                                                                                                                                                                                    , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                        , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                        , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                              , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                              , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                            , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60077485?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-21 06:54:59 </td>
   <td style="text-align:left;"> Netflix faces rocky road after pandemic wins </td>
   <td style="text-align:left;"> The number of Netflix subscribers grew to 222 million last year, but the streaming firm is facing a rocky road ahead as the surge of interest it saw during the pandemic fades.                                                                                                                                             , Overall, Netflix added 18.2 million members last year - roughly half the number who subscribed in 2020.                                                                                                                                                                                                                     , Investors had hoped that pace would start to pick up again.                                                                                                                                                                                                                                                                 , But the firm's 2022 forecast brought bad news, sending shares down almost 20% in after-hours trade.                                                                                                                                                                                                                         , The firm said it expected to add just 2.5 million members in the three months to March - far lower than analysts had expected.                                                                                                                                                                                              , "While retention and engagement remain healthy, acquisition growth has not yet re-accelerated to pre-Covid levels," Netflix said, pointing to "Covid overhang and macro-economic hardship" in parts of the world like Latin America.                                                                                        , Netflix, which added 8.3 million subscribers in the last three months of 2021, maintained that there is room to grow, as more and more people switch away from traditional television.                                                                                                                                      , But it admitted that new competition from the likes of Disney, Apple, Amazon and HBO was starting to have an impact.                                                                                                                                                                                                        , "Consumers have always had many choices when it comes to their entertainment time - competition that has only intensified over the last 24 months as entertainment companies all around the world develop their own streaming offering," the firm said.                                                                     , "While this added competition may be affecting our marginal growth some, we continue to grow in every country and region in which these new streaming alternatives have launched."                                                                                                                                          , Netflix is spending billions of dollars on content to keep viewers interested. Hits during the last three months of the year included a new season of The Witcher fantasy television series and the satire Don't Look Up - which has already become the second most popular film ever for the company.                      , But the firm, which recently raised prices in the US and Canada, is facing rising costs and other challenges - the strengthening of the dollar will cost the firm $1bn alone, it said.                                                                                                                                      , "Squid Games creator Netflix has gone from a fairytale to some difficult viewing when it comes to subscriber forecasts - the most important metric for streaming services," said Laura Hoy, an equity analyst at Hargreaves Lansdown.                                                                                       , "The group's forecast for new subscriptions in the current period came in at just over half of last year's figure," she said. "Management blamed a back-loaded content schedule that will see several big releases come out at the end of the quarter, but investors were undeniably spooked by the slower growth forecast.", Revenue increased by 16% for October, November and December, compared to the same period a year earlier, hitting $7.7bn. Quarterly profits increased 12% to $607m.                                                                                                                                                          , For the year, profits jumped from $2.7bn to $5.1bn, while revenue grew by 19% to $26.7bn.                                                                                                                                                                                                                                   , Go behind the scenes at London's Corinthia Hotel                                                                                                                                                                                                                                                                            , Hidden Assets: A gritty Irish crime thriller on BBC iPlayer                                                                                                                                                                                                                                                                 , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/20/business/media/sean-hannity-donald-trump-january-6.html </td>
   <td style="text-align:left;"> 2022-01-21 06:47:06 </td>
   <td style="text-align:left;"> Sean Hannity Told Trump After Jan. 6: ‘No More Stolen Election Talk’ - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , By Michael M. Grynbaum                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , The Fox News host Sean Hannity had some blunt advice for President Donald J. Trump on Jan. 7, 2021: “No more stolen election talk.”                                                                                                                                                                                                                                                                                                                                                              , His guidance did not take. But documents disclosed on Thursday showed in vivid detail just how closely Mr. Hannity had worked with White House aides in a fervent, if brief, effort to persuade Mr. Trump to abandon his false claims about voter fraud after the Jan. 6 attack on the Capitol.                                                                                                                                                                                                  , One day after the attack, Mr. Hannity sent a text message to Kayleigh McEnany, then the White House press secretary, describing a five-point plan for approaching conversations with the president, according to documents released by the House committee investigating the Jan. 6 riot.                                                                                                                                                                                                        , After urging Ms. McEnany to avoid discussion of a “stolen election,” Mr. Hannity proffered another talking point to use with Mr. Trump: “Yes, impeachment and 25th amendment are real, and many people will quit …”                                                                                                                                                                                                                                                                              , Mr. Hannity appeared to be referring to the possibilities that Mr. Trump could be impeached, face mass resignations from his staff or be temporarily removed from office by a group of his cabinet secretaries invoking the 25th Amendment.                                                                                                                                                                                                                                                      , Ms. McEnany replied: “Love that. Thank you. That is the playbook. I will help reinforce.”                                                                                                                                                                                                                                                                                                                                                                                                        , Fox News, where Ms. McEnany is now a commentator and a co-host of a weekday program, declined to comment on Thursday.                                                                                                                                                                                                                                                                                                                                                                            , In public, Mr. Hannity and Ms. McEnany remain lock-step supporters of Mr. Trump and his worldview. But their private exchanges show the level of alarm among even the president’s closest allies after the Jan. 6 riot, as Mr. Trump persisted in his false claims that the election had been stolen from him and his political future appeared deeply precarious.                                                                                                                               , The exchanges were included in a letter sent by the House committee to Ivanka Trump, Mr. Trump’s daughter and one of his senior advisers. The committee is seeking Ms. Trump’s cooperation as it tries to piece together a scramble inside the White House to persuade Mr. Trump to denounce the attackers at the Capitol.                                                                                                                                                                       , In another exchange included in the letter, Mr. Hannity urged Ms. McEnany to keep the president away from certain advisers. “Key now. No more crazy people,” Mr. Hannity wrote. Ms. McEnany replied: “Yes 100%.”                                                                                                                                                                                                                                                                                 , This month, the House committee asked Mr. Hannity to cooperate and answer questions about his communications with Mr. Trump and his aides in the days surrounding the riot. At the time, the committee disclosed messages in which Mr. Hannity advised Mark Meadows, then the White House chief of staff, on the president’s political future. “He can’t mention the election again. Ever,” Mr. Hannity wrote on Jan. 10, 2021, to Mr. Meadows and Representative Jim Jordan, an Ohio Republican., A lawyer for Mr. Hannity, Jay Sekulow, has said the committee’s request to interview Mr. Hannity raises “First Amendment concerns regarding freedom of the press.”                                                                                                                                                                                                                                                                                                                               , Luke Broadwater contributed reporting.                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-20/tech-led-u-s-stock-reversal-to-pressure-asia-open-markets-wrap </td>
   <td style="text-align:left;"> 2022-01-21 06:22:20 </td>
   <td style="text-align:left;"> Stocks, U.S. Futures Drop; Treasury Yields Decline: Markets Wrap </td>
   <td style="text-align:left;"> Sunil Jagtiani                                                                                                                                                                                                                           , U.S. equity futures declined and Asian stocks fell Friday after a late-day reversal on Wall Street that pushed the technology-heavy Nasdaq 100 into a correction.                                                                        , S&amp;P 500 and Nasdaq 100 contracts retreated, with the latter underperforming. The tech gauge erased a near 2% rally Thursday before ending in the red, while the S&amp;P 500 also surrendered gains and is more than 5% off its January high.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/new-zealand/tourist-arrivals </td>
   <td style="text-align:left;"> 2022-01-21 06:05:44 </td>
   <td style="text-align:left;"> New Zealand Tourist Arrivals Rise </td>
   <td style="text-align:left;"> The number of visitor arrivals in New Zealand rose by 3.8 percent year-on-year in November of 2021, as pandemic-related travel restrictions started to ease allowing a rebound in the tourism sector, coinciding with the opening of quarantine-free travel from New Zealand to Australia on 1 November 2021. Historically, travel numbers tend to increase toward the end of the year, and provisional data for December 2021 shows a further increase in the number of border crossings, although levels overall are well below those before the COVID-19 pandemic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/intuitive-surgical-stock-falls-after/story.aspx?guid={AEB00768-5EF1-4475-A964-544C26BC2646}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-21 05:58:17 </td>
   <td style="text-align:left;"> Intuitive Surgical stock falls after company earnings hurt by fewer procedures - MarketWatch </td>
   <td style="text-align:left;"> Shares of Intuitive Surgical Inc. 
        ISRG,
        -0.25%
       fell more than 4% in the extended session Thursday after the health care company reported fourth-quarter earnings and sales slightly above expectations but said the pandemic continues to lead to fewer procedures done with its main robotic surgical system. Intuitive said it earned $381 million, or $1.04 a share, in the quarter, compared with $365 million, or $1.01 a share, in the fourth quarter of 2020. Adjusted for one-time items, the company earned $1.30 a share. Sales rose 17% to $1.55 billion, the company said. Analysts polled by FactSet expected Intuitive to report an adjusted EPS of $1.28 a share on sales of $1.52 billion. "During 2021, COVID-19 resurgences continued to impact da Vinci procedure volumes," the company said in a statement. "COVID-19 has had, and will likely continue to have, an adverse impact on the company's procedure volumes." Shares of Intuitive ended the regular trading day down 0.3%., Get ready for the action drama 'Reacher,' a new season of 'The Marvelous Mrs. Maisel' and much more                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/yellen-says-she-expects-inflation/story.aspx?guid={94480BD5-650F-4D22-8E54-A2F9E98EFA76}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-21 05:52:47 </td>
   <td style="text-align:left;"> Yellen says she expects inflation to ease this year if U.S. controls pandemic - MarketWatch </td>
   <td style="text-align:left;"> Treasury Secretary Janet Yellen said Thursday she expects inflation to "diminish over the course of the year" if the U.S. is successful in controlling the COVID-19 pandemic. In an interview on CNBC, Yellen said she hopes inflation would get back to around 2% by the end of the year. The treasury chief said the Biden administration is "doing all the things that we can to deal with supply chain issues that are pushing prices up" and said inflation rose more than most economists, including herself, expected.     , FBI agents searched near the Texas home of U.S. Rep. Henry Cuellar on Wednesday as they conducted what an agency spokeswoman called “court-authorized law enforcement activity.”                                                                                                                                                                                                                                                                                                                                                  ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Robert Schroeder is the Washington bureau chief for MarketWatch. Follow him on Twitter @mktwrobs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/20/stocks-making-the-biggest-moves-after-hours-netflix-csx-more.html </td>
   <td style="text-align:left;"> 2022-01-21 05:44:49 </td>
   <td style="text-align:left;"> Stocks making the biggest moves after hours: Netflix, CSX &amp; more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Check out the companies making headlines in after-hours trading:                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Netflix — Netflix shares dropped 19% in extended trading after the company's quarterly report showed slowing subscriber growth. The streaming giant added 8.28 million global paid net subscribers during the fourth quarter, which was ahead of Wall Street's expectations for 8.19 million, according to estimates from StreetAccount. But the number declined year over year. Netflix beat EPS estimates for the period, earning $1.33 per share compared with the 82 cents analysts surveyed by Refinitiv were expecting. Revenue came in at $7.71 billion, in line with expectations., CSX — Shares of the rail company declined 2% despite top- and bottom-line beats for the fourth quarter. CSX earned 42 cents per share on $3.43 billion in revenue, ahead of the 41 cents and $3.32 billion in revenue analysts surveyed by Refinitiv were expecting.                                                                                                                                                                                                                                                                                                                      , Intuitive Surgical — Intuitive Surgical shares dipped 2% despite the company's latest earnings report, which topped estimates. The medical company earned $1.30 per share, excluding items, on $1.55 billion in revenue. Analysts surveyed by Refinitiv were expecting $1.28 per share on $1.52 billion in revenue.                                                                                                                                                                                                                                                                       , PPG Industries — Shares of the paint company slid 3% during extended trading. PPG earned $1.26 per share, excluding items, during the fourth quarter on $4.19 billion in revenue. Wall Street was expecting $1.18 per share on $4.04 billion in revenue, according to estimates from StreetAccount.                                                                                                                                                                                                                                                                                       , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                                                                                                                                                        , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ppg:us </td>
   <td style="text-align:left;"> 2022-01-21 05:41:19 </td>
   <td style="text-align:left;"> PPG Industries earnings above expectations at 1.26 USD </td>
   <td style="text-align:left;"> PPG Industries (PPG) released earnings per share at 1.26 USD, compared to market expectations of 1.18 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/sivb:us </td>
   <td style="text-align:left;"> 2022-01-21 05:41:12 </td>
   <td style="text-align:left;"> SVB Financial earnings below expectations at 6.22 USD </td>
   <td style="text-align:left;"> SVB Financial (SIVB) released earnings per share at 6.22 USD, compared to market expectations of 6.52 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/csx:us </td>
   <td style="text-align:left;"> 2022-01-21 05:41:05 </td>
   <td style="text-align:left;"> CSX earnings above expectations at 0.42 USD </td>
   <td style="text-align:left;"> CSX (CSX) released earnings per share at 0.42 USD, compared to market expectations of 0.41 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/isrg:us </td>
   <td style="text-align:left;"> 2022-01-21 05:40:56 </td>
   <td style="text-align:left;"> Intuitive Surgical earnings above expectations at 1.30 USD </td>
   <td style="text-align:left;"> Intuitive Surgical (ISRG) released earnings per share at 1.30 USD, compared to market expectations of 1.28 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/nflx:us </td>
   <td style="text-align:left;"> 2022-01-21 05:40:46 </td>
   <td style="text-align:left;"> Netflix earnings above expectations at 1.33 USD </td>
   <td style="text-align:left;"> Netflix (NFLX) released earnings per share at 1.33 USD, compared to market expectations of 0.85 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/netflix-earnings </td>
   <td style="text-align:left;"> 2022-01-21 05:35:45 </td>
   <td style="text-align:left;"> Netflix falls short of subscriber target </td>
   <td style="text-align:left;"> Jeff Sica of Circle Squared Alternative Investments on Netflix planning to raise monthly streaming prices.                                                                                                                                                                                                                                                                               , Netflix welcomed 8.3 million new subscribers during the fourth quarter of 2021, falling just shy of the 8.5 million the streaming giant had expected to bring in despite rolling out its two biggest releases ever, "Red Notice" and "Don't Look Up," during the time period.                                                                                                            , DON'T LOOK UP, LEONARDO DICAPRIO as DR. RANDALL MINDY. Cr. NIKO TAVERNISE/NETFLIX © 2021 (Netflix)                                                                                                                                                                                                                                                                                       , NETFLIX'S DON'T LOOK UP' BREAKS RECORD FOR MOST HOURS VIEWED IN A SINGLE WEEK                                                                                                                                                                                                                                                                                                            , The largest streaming service in the world still boasted 221.8 million subscribers globally at the end of 2021, but forecasted bringing in only another 2.5 million more in the current quarter. That's down from 4 million the same period a year ago.                                                                                                                                  , The company's stock dropped more than 15% in after-hours trading following the report.                                                                                                                                                                                                                                                                                                   , The Netflix logo is seen on the Netflix, Inc. building on Sunset Boulevard in Los Angeles, California on October 19, 2021.  (ROBYN BECK/AFP via Getty Images / Getty Images)                                                                                                                                                                                                             , Netflix has been fighting off increasing competition from other services such as Walt Disney Co's Disney+, AT&amp;T's HBO Max, and Amazon's Prime, all of which are building on their offerings.                                                                                                                                                                                             , "Even in a world of uncertainty and increasing competition, we’re optimistic about our long-term growth prospects as streaming supplants linear entertainment around the world," Netflix said in a letter to shareholders release with its earnings. "We're continually improving Netflix so that we can please our members, grow our share of leisure time and lead in this transition.", Netflix CEO Reed Hastings. (Getty Images / Getty Images)                                                                                                                                                                                                                                                                                                                                 , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                  , Last week Netflix raised its prices for subscriptions in the U.S. and Canada, which together make up the company's largest customer base at 73 million. But last month, the company cut its prices in India, looking to remain competitive in the growing market according to The Wall Street Journal.                                                                                   , Netflix saw revenue growth of 16% to $7.71 billion in Q4, meeting Wall Street's expectations of $7.71 billion.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/ppg-stock-falls-3-paint/story.aspx?guid={BE44951F-9048-4921-9754-78DB4F5660A2}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-21 05:31:40 </td>
   <td style="text-align:left;"> PPG stock falls 3% as paint maker to raise prices to ease inflation pressure - MarketWatch </td>
   <td style="text-align:left;"> Shares of PPG Industries Inc. 
        PPG,
        -1.15%
       fell nearly 3% in the extended session Thursday after the paint and coatings maker reported fourth-quarter profit and sales above Wall Street expectations but said pandemic-related "disruptions" continue to impact production and sales, and it will increase prices to mitigate soaring costs. PPG said it earned $267 million, or $1.12 a share, in the quarter, compared with $272 million, or $1.14 a share, in the year-ago period. Adjusted for one-time items, PPG earned $1.26 a share. Sales rose 12% to $4.2 billion. Analysts polled by FactSet expected adjusted EPS of $1.18 on sales of $4 billion. "Looking ahead, while demand for PPG products remains strong, the heightened supply and COVID-related disruptions experienced in the fourth quarter are expected to continue in the first quarter of the year impacting our ability to manufacture and deliver product," the company said in a statement. "We expect raw-material costs to remain at an elevated level and we are experiencing additional inflation in other cost areas, including logistics and labor." PPG said it will raise prices in all business lines "to mitigate the incremental inflation, and we continue to aggressively manage all aspects of our cost structure, including actions to minimize the cost impacts of the current supply challenges." Shares of PPG ended the regular trading day down 1.2%. , Tesla Inc. is scheduled to report fourth-quarter earnings next Wednesday, as investors expect a return of Chief Executive Elon Musk to the post-results call and brace for what could be worrying news for the Cybertruck and supply-chain snags.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60077335?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-21 05:21:48 </td>
   <td style="text-align:left;"> Peloton shares dive on report of production pause </td>
   <td style="text-align:left;"> Peloton shares have plummeted following a report that it plans to temporarily stop production of its pricey exercise machines.                                                                                                                                                                                         , The company, which saw demand soar during the pandemic, is now stuck with a glut of bikes and treadmills, CNBC reported, citing internal documents.                                                                                                                                                                    , Investors sold off shares at the sign of waning popularity, forcing the firm's stock price down more than 20%.                                                                                                                                                                                                         , Peloton did not immediately respond to a request for comment from the BBC.                                                                                                                                                                                                                                             , The firm, which pairs its equipment with streaming and live exercise classes, had struggled to keep up with orders at the start of the pandemic, as gyms shut their doors.                                                                                                                                             , More recently, however, appetite has dwindled for its bikes and treadmills, which start at nearly $1,500 (£1,100).                                                                                                                                                                                                     , The firm was hit last year after the death of a child in a treadmill accident led to a recall and government safety investigation. It also cut prices as people started to return to pre-pandemic exercise habits.                                                                                                     , In November, the firm told investors it had experienced "softer than anticipated" sales and was lowering its expectations for the year.                                                                                                                                                                                , CNBC reported that Peloton was halting production of its most expensive expensive bike from December until June and its most expensive treadmill for all of its 2022 financial year, which runs through June. It is also pausing production of its standard bike in February and March and its treadmill for six weeks., CNBC, which also reported that the firm is considering job cuts, said the presentation blamed increased competition and price sensitivity for a "significant reduction" in demand.                                                                                                                                     , The news sent the price of Peloton shares below $29, which is below what they fetched when the loss-making firm floated on the stock market in 2019. The value of the shares are down roughly 80% over the last 12 months.                                                                                             , At the time, analysts said it was not clear how big the market for Peloton machines was given their cost. The firm also makes money from people who subscribe for classes via its app.                                                                                                                                 , Go behind the scenes at London's Corinthia Hotel                                                                                                                                                                                                                                                                       , Hidden Assets: A gritty Irish crime thriller on BBC iPlayer                                                                                                                                                                                                                                                            , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-20/chipmakers-tumble-again-in-biggest-weekly-drop-since-march-2020?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-21 05:17:51 </td>
   <td style="text-align:left;"> Chipmakers Tumble Again in Biggest Weekly Drop Since March 2020 </td>
   <td style="text-align:left;"> Ryan Vlastelica                                                                                                                                                                                                                                                                     , Shares of semiconductor companies fell on Thursday, with the group participating in a widespread late selloff for technology stocks that pushed the Nasdaq 100 Index into correction territory.                                                                                     , The Philadelphia Stock Exchange Semiconductor Index fell 3.3%, ending at its lowest since late October. The index has dropped more than 10% thus far this week, which would represent its biggest one-week percentage drop since March 2020. It is now down 13% off a December peak. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/csx-q4-sales-rise-21/story.aspx?guid={744E0A28-5813-4FA5-9355-3E3E0EB984DD}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-21 05:17:22 </td>
   <td style="text-align:left;"> CSX Q4 sales rise 21% as 'all lines of business' grew, rail operator says - MarketWatch </td>
   <td style="text-align:left;"> Shares of CSX Corp. 
        CSX,
        -0.03%
       fell in the extended session Thursday after the rail operator reported fourth-quarter results that met Wall Street expectations. CSX said it earned $934 million, or 42 cents a share, in the fourth quarter, compared with $760 million, or 33 cents a share, in the year-ago period. Sales rose 21% to $3.43 billion, thanks to "growth across all major lines of business," the company said. Analysts polled by FactSet expected earnings of 42 cents a share on sales of $3.3 billion. "As we enter 2022, we remain committed to providing our customers high-quality service and creating additional capacity to help them address current supply-chain challenges through the increased use of rail," CSX Chief Executive James Foote said in a statement. Shares of CSX ended the regular trading day down less than 0.1%, Netflix Inc. brought in more than 8 million new subscribers in the holiday quarter, but executives predicted that growth would suffer much more than expected at the beginning of 2022, sending shares screaming lower in after-hours trading.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-01-21 05:15:51 </td>
   <td style="text-align:left;"> Canada Stocks Erase Gains to Fall for 3rd Session </td>
   <td style="text-align:left;"> The S&amp;P/TSX Composite index shed 0.7% to close at 21,058 on Thursday, extending losses for a third consecutive session as mining and consumer discretionary plunged 1.8% and 2.4%, respectively, while consumer staples dropped 1.5%. Meanwhile, investors continued to anticipate an interest rate hike from the Bank of Canada in its meeting next week. Despite eased bond yields in North America, Scotiabank said on a note to its investors that it expects the BoC to raise its key overnight rate by 25bps to 0.5% on January 26th. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-20/a-year-s-worth-of-nasdaq-tumult-was-condensed-in-three-weeks?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-21 05:15:38 </td>
   <td style="text-align:left;"> A Year’s Worth of Nasdaq Tumult Gets Jammed Into Three Weeks </td>
   <td style="text-align:left;"> The Nasdaq MarketSite in New York.                                                                                                                                                                                                                                                                                                                                              , Photographer: Seth Wenig/AP Photo                                                                                                                                                                                                                                                                                                                                               , Lu Wang                                                                                                                                                                                                                                                                                                                                                                         ,  and Vildana Hajric                                                                                                                                                                                                                                                                                                                                                             , Many ways exist to chart shakiness in the stock market. There’s options-derived volatility indexes, price relative to moving averages and maximum drawdowns, to name a few.                                                                                                                                                                                                     , Then there’s the type of whole-cloth vanishing act the Nasdaq 100 has been staging in recent weeks, sessions in which the index appears headed for resounding gains or declines -- before the whole thing goes poof in a matter of minutes. It happened again Thursday, when the tech-heavy gauge erased a 2% rally and kept falling in its worst bearish reversal in 17 months. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-01-21 05:11:52 </td>
   <td style="text-align:left;"> Brazilian Equities at 3-Month High </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Bovespa, jumped 1.1% to close at 109,132 on Thursday, extending gains for a third straight session to a level not seen since October 20th 2021, taking advantage of the slight drop in Treasury yields and as the focus turns to the US earnings season and prospects of recovery. On the domestic front, President Jair Bolsonaro said in an interview on Wednesday that the adjustment promised by the government to the federal police in 2022 is suspended and that federal civil servants, currently with frozen salaries, can be contemplated with an adjustment in the 2023 Budget. The president is expected to sign the 2022 budget approved at the end of last year by Congress on January 21st. Among single stocks, Banco Inter and Meliuz were the top performers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/01/20/politics/trump-campaign-officials-rudy-giuliani-fake-electors/index.html </td>
   <td style="text-align:left;"> 2022-01-21 05:09:03 </td>
   <td style="text-align:left;"> Trump campaign officials, led by Rudy Giuliani, oversaw fake electors plot in 7 states - CNNPolitics </td>
   <td style="text-align:left;"> Washington (CNN)Trump campaign officials, led by Rudy Giuliani, oversaw efforts in December 2020 to put forward illegitimate electors from seven states that Trump lost, according to three sources with direct knowledge of the scheme.                                                                                                                                                                                                                                                                                                                            , The sources said members of former President Donald Trump's campaign team were far more involved than previously known in the plan, a core tenet of the broader plot to overturn President Joe Biden's victory when Congress counted the electoral votes on January 6.                                                                                                                                                                                                                                                                                              , Giuliani and his allies coordinated the nuts-and-bolts of the process on a state-by-state level, the sources told CNN. One source said there were multiple planning calls between Trump campaign officials and GOP state operatives, and that Giuliani participated in at least one call. The source also said the Trump campaign lined up supporters to fill elector slots, secured meeting rooms in statehouses for the fake electors to meet on December 14, 2020, and circulated drafts of fake certificates that were ultimately sent to the National Archives., Trump and some of his top advisers publicly encouraged the "alternate electors" scheme in Pennsylvania, Georgia, Michigan, Arizona, Wisconsin, Nevada and New Mexico. But behind the scenes, Giuliani and Trump campaign officials actively choreographed the process, the sources said.                                                                                                                                                                                                                                                                            , One fake elector from Michigan boasted at a recent event hosted by a local Republican organization that the Trump campaign directed the entire operation.                                                                                                                                                                                                                                                                                                                                                                                                           , "We fought to seat the electors. The Trump campaign asked us to do that," Meshawn Maddock, co-chair of the Michigan Republican Party, said at a public event last week that was organized by the conservative group Stand Up Michigan, according to a recording obtained by CNN.                                                                                                                                                                                                                                                                                    , Maddock was also one of the 16 Trump supporters from Michigan who served as fake electors and signed the illegitimate certificate that was sent to the National Archives.                                                                                                                                                                                                                                                                                                                                                                                           , "It was Rudy and these misfit characters who started calling the shots," a former Trump campaign staffer said. "The campaign was throwing enough sh*t at the wall to see what would stick."                                                                                                                                                                                                                                                                                                                                                                         , Integral to the Jan 6 plan                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , The scheme was integral to Trump's plan to get then-Vice President Mike Pence to throw out Biden's electors and replace them with the GOP electors on January 6 when Congress counted the electoral votes. It has also come under renewed scrutiny by the January 6 select committee and state attorneys general, raising questions about the involvement of Trump's campaign and whether any laws were broken.                                                                                                                                                     , Committee chairman Rep. Bennie Thompson of Mississippi told reporters Thursday the panel is looking into whether there was a broader conspiracy or involvement from the Trump White House in the creation or submission of these fake electors.                                                                                                                                                                                                                                                                                                                     , "That's a concern" Thompson said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , In its subpoena letter sent to Giuliani on Tuesday, the House committee specifically references his efforts to convince state legislatures to overturn election results. The document cites Giuliani's comments from December 2020 in which he publicly urged lawmakers in Michigan to award the state's electoral votes to Trump.                                                                                                                                                                                                                                  , One of the pro-Trump electors from Pennsylvania, Sam DeMarco, told CNN there was a last-minute dispute, where the state's GOP electors pushed Trump campaign officials to add legal caveats to the fake certificate to say they were only electors-in-waiting, if Trump's legal challenges prevailed.                                                                                                                                                                                                                                                               , The fake documents from Pennsylvania and New Mexico ultimately contained these caveats, but the documents from the other five states explicitly claimed, falsely, that the pro-Trump electors were the rightful electors.                                                                                                                                                                                                                                                                                                                                           , It's not clear that any of the fake electors themselves participated in strategy sessions with top Trump campaign brass. But both Maddock from Michigan and DeMarco from Pennsylvania have said they were in direct contact with members of the Trump campaign.                                                                                                                                                                                                                                                                                                     , Many of the players involved in the scheme, including Maddock, stand by their actions and are still pushing the lie that the 2020 election was stolen. Giuliani, a Trump spokesperson and a representative from Stand Up Michigan did not respond to CNN's requests for comment.                                                                                                                                                                                                                                                                                    , Advancing the lie that the election was stolen                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , After Trump failed to stop battleground states from certifying Biden's victory, Trump campaign officials, led by Giuliani, launched its parallel effort to disrupt and undermine the Electoral College process. This included publicly promoting false claims of fraud, while quietly exploring the fast-diminishing avenues to overturn the results.                                                                                                                                                                                                               , Trump hoped Republican legislators from the seven battleground states would replace Biden's authentic electors with the rogue GOP slate, and that Pence would seat those electors during the joint session of Congress on January 6.                                                                                                                                                                                                                                                                                                                                ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , A source familiar with the situation told CNN that Pence was concerned about the possibility of "alternate electors," and his team carefully worded what he said that day during the Electoral College certification to recognize only the legitimate electors.                                                                                                                                                                                                                                                                                                     , One of the sources with direct knowledge of the scheme, a former Trump campaign staffer, told CNN that Giuliani worked closely on the seven-state stunt with Christina Bobb, a correspondent for the pro-Trump propaganda network One America News.                                                                                                                                                                                                                                                                                                                 , Many of Giuliani's unhinged conspiracies about the 2020 election found a home at OAN. And in a deposition last year as part of a civil lawsuit, Giuliani said Bobb was "very active in gathering evidence" as "part of the legal team" working for Trump's campaign during the presidential transition.                                                                                                                                                                                                                                                             , Bobb reached out to a top Arizona legislator about supposed voter fraud, according to emails obtained by the government oversight group American Oversight through a public records request. In the December 4, 2020, email Bobb said she was sending the message on Giuliani's behalf. The emails flesh out how Trump's team was trying to press state legislatures to overturn the results.                                                                                                                                                                       , Bobb didn't respond to messages seeking comment about the pro-Trump electors.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , "They were all working together. Rudy, John Eastman, and Christina Bobb, in tandem, to create this coverage for OAN, to advance the Big Lie," the former Trump campaign staffer told CNN.                                                                                                                                                                                                                                                                                                                                                                           , While mainstream news outlets covered the Electoral College proceedings, which cemented Biden's position as President-elect, OAN focused on the rogue electors and voter fraud myths.                                                                                                                                                                                                                                                                                                                                                                               , The Washington Post first reported new details about the role of Giuliani and Bobb.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Battleground Michigan                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Republicans in Michigan were central to the effort to try and overturn the election results and Meshawn Maddock -- along with her husband State Rep. Matt Maddock -- were instrumental to the effort inside the state.                                                                                                                                                                                                                                                                                                                                              , The Maddocks have deep ties to Trump. The former president has endorsed Matt Maddock in his bid to be Michigan House leader. Maddock tweeted a photo last year of an article written about his campaign that Trump had signed, and added, "Matt, I am with you all the way."                                                                                                                                                                                                                                                                                        , In the months leading up to January 6, Matt Maddock consistently pushed Trump's lie about the election. In early December 2020, Matt Maddock and other state GOP lawmakers in Michigan held a series of hearings seeking to validate unfounded claims of widespread voter fraud -- prompting a personal visit from Giuliani.                                                                                                                                                                                                                                        , When the effort to convince state legislators in Michigan to block Biden's electors ultimately failed, Maddock was among the GOP lawmakers from five states who sent a letter to Pence on January 5, urging him to delay certification of the electoral votes. Pence refused to go along with the plan.                                                                                                                                                                                                                                                             , Meshawn Maddock is equally close to Trump and is still peddling the lie that the election was stolen.                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Along with being an elector, she also helped organize buses to take GOP activists to Washington for protests around January 6 and took part in the march to the US Capitol. She later disavowed the violence that came after the march.                                                                                                                                                                                                                                                                                                                             , Maddock was named co-chair of the Michigan Republican Party one month after January 6. But as she is gaining prominence, her role as a fake elector is also attracting legal scrutiny.                                                                                                                                                                                                                                                                                                                                                                              ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , "Under state law, I think clearly you have forgery of a public record, which is a 14-year offense, and election law forgery, which is a five-year offense," Michigan Attorney general Dana Nessel, a Democrat, told MSNBC last week, about the fake certificates signed by pro-Trump electors.                                                                                                                                                                                                                                                                      , No one, including Meshawn Maddock, has been charged with any crimes related to the scheme.                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , "This is nothing more than political prosecution of convenience led by Dana Nessel," said Gustavo Portela, MIGOP Communications Director, when asked about Maddock's comments and role as a fake elector.                                                                                                                                                                                                                                                                                                                                                           , Hedged language in Pennsylvania                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , The documents from Georgia, Arizona, Michigan, Wisconsin and Nevada explicitly stated, falsely, that the GOP electors were the rightful electors, representing 59 electoral votes.                                                                                                                                                                                                                                                                                                                                                                                  , But the documents from Pennsylvania and New Mexico contained clauses saying that the Trump supporters were electors-in-waiting, in case a court or some other proceeding later ruled that they were the "duly elected and qualified electors."                                                                                                                                                                                                                                                                                                                      , If anything, this provided a veneer of legal protection for Trump supporters who were trying to exploit the Electoral College process to overturn an election.                                                                                                                                                                                                                                                                                                                                                                                                      , Demarco, who was one of the state's pro-Trump electors, and is the chairman of the Allegheny County Republican Committee, told CNN he and other alternate electors signed the certificate at the Trump campaign's request but first demanded the language be changed to make clear it was not intended to contest the will of voters in that state who voted for Biden.                                                                                                                                                                                             , The hedging language was included at the last moment as the Trump campaign had concerns, and questioned whether the change was appropriate in the immediate lead-up to December 14, according to a Trump campaign staffer with knowledge of the matter.                                                                                                                                                                                                                                                                                                             , Ultimately the Trump campaign acquiesced. But the internal debate shows that even some of Trump's strongest allies were concerned about the attempts to overturn the 2020 election.                                                                                                                                                                                                                                                                                                                                                                                 ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , The office of Pennsylvania Attorney General Josh Shapiro, a Democrat, said in a statement that they looked into the matter but concluded that the fake certificate was not an illegal forgery.                                                                                                                                                                                                                                                                                                                                                                      , "These 'fake ballots' included a conditional clause that they were only to be used if a court overturned the results in Pennsylvania, which did not happen," the statement said. "Though their rhetoric and policy were intentionally misleading and purposefully damaging to our democracy, based on our initial review, our office does not believe this meets the legal standards for forgery."                                                                                                                                                                  , Concerns about democracy                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Democratic lawmakers, state officials, and Biden himself have roundly condemned the fake electors plot. Biden brought it up at a news conference Wednesday when asked about his stalled voting-rights bills in Congress.                                                                                                                                                                                                                                                                                                                                            , "I never thought we would get into a place where we were talking about... what they tried to do this last time out -- Send different electors to the state legislative bodies to represent who won the election, saying that I didn't win but the Republican candidate won," Biden said. "I doubt that anyone thought that would happen in America in the 21st century, but it is happening."                                                                                                                                                                       ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , The coordinated nature of these fake elector efforts and the rising power of Big Lie-promoters in Republican circles has concerned voting rights organizations across the country.                                                                                                                                                                                                                                                                                                                                                                                  , Nancy Wang, executive director of the Michigan-based Voters Not Politicians, said her group was founded in 2016   to address redistricting and voting access, but Trump's attempt to overturn the 2020 election spurred her group to focus on countering anti-democratic efforts at large.                                                                                                                                                                                                                                                                          , "This is existential. This about the very fundamental institutions of our government - whether we can vote at all, whether we have any power whatsoever," Wang said. "It is a completely different time that we are facing in 2020 and 2022. It really feels urgent. It is a battle of a completely different kind. It is massive, it is coordinated at a national level. It is much more threatening."                                                                                                                                                             , CNN's Pamela Brown and Annie Grayer contributed reporting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/dow-posts-5th-straight-loss/story.aspx?guid={012AC92C-A6A8-4DD1-963C-FDBCF1DDAED9}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-21 05:04:35 </td>
   <td style="text-align:left;"> Dow posts 5th straight loss as stock-market bounce runs out of steam - MarketWatch </td>
   <td style="text-align:left;"> Stocks ended lower Thursday, giving up early gains as investors appeared unable to shake off worries over a rising interest-rate environment. The Dow Jones Industrial Average 
        djia
       fell around 313 points, or 0.9%, to close near 34,715, according to preliminary figures, extending its losing streak to five sessions, the longest since September. The S&amp;P 500 
        comp
       declined around 50 points, or 1.1%, to finish near 4,483, while the Nasdaq Composite 
        comp
       dropped around 186 points, or 1.3%, to end near 14,154. The tech-heavy Nasdaq on Wednesday entered correction territory, having fallen more than 10% from a record high set in November. Analysts have tied stock-market weakness to begin the new year to expectations the Federal Reserve will be much more aggressive than previously expected in raising interest rates and otherwise tightening monetary policy in an effort to rein in persistently high inflation., The yield-sensitive Nasdaq Composite Index on Wednesday logs its first close in correction territory since March. Here's what history says happens next.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , William Watts is MarketWatch’s senior markets writer. Based in New York, Watts writes about stocks, bonds, currencies and commodities, including oil. He also writes about global macro issues and trading strategies. Before moving to New York, he reported for MarketWatch from Frankfurt, London and Washington, D.C. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-20/gm-labor-vote-in-mexico-raises-red-flags-for-unifor-afl-cio?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-21 05:03:26 </td>
   <td style="text-align:left;"> GM Labor Vote in Mexico Raises Red Flags for Unifor, AFL-CIO </td>
   <td style="text-align:left;"> Andrea Navarro                                                                                                                                                                                                                                                                                                  ,  and David Welch                                                                                                                                                                                                                                                                                                , The largest unions in the U.S. and Canada are raising questions about the fairness of a worker vote that’s set to take place at General Motors Co.’s truck plant in Mexico.                                                                                                                                     , There are “substantial reasons to doubt” the vote set for Feb. 1-2 will be free and fair as workers choose between four unions, Canada’s Unifor said in a Jan. 18 letter to Mexican authorities. The AFL-CIO said separately it’s “concerned by the lack of protection for workers’ rights inside the GM plant.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-01-21 05:01:00 </td>
   <td style="text-align:left;"> Wall Steet Gives Up Gains to Close Sharply Lower </td>
   <td style="text-align:left;"> The US stocks closed lower on Thursday after keeping gains for most of the session as the rebound in tech stocks eased. The Dow Jones fell as much as 320 points after adding more than 450 points earlier, the S&amp;P 500 dopped 1.1%, and the Nasdaq Composite plunged 1.3% after booking gains of 2%. The sell-off started after it was reported that Peloton Interactive Inc. was halting some production, dragging the company stocks to a 24% dop. In addition, investors remain concerned about rise in borrowing cost despite treasury yields retreating for a second day from recent 2-year highs. Meanwhile, earnings from Travelers Companies and American Airlines topped estimates while United Airlines lowered its 2022 growth forecast due to the spread of the omicron variant. On the data front, initial claims were the highest in 3 months while the Philly Fed manufacturing index came better-than-expected sending mixed signals about economic recovery. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-20/nasdaq-100-enters-correction-as-tech-stocks-resume-slide?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-21 04:53:37 </td>
   <td style="text-align:left;"> Nasdaq 100 Enters Correction as Tech Stocks Resume Slide </td>
   <td style="text-align:left;"> Jess Menton                                                                                                                                                                                                                                                                                                                                                                            , The technology-focused Nasdaq 100 fell into a correction on Thursday, a swift reversal after touching an all-time high in November as a surge in U.S. Treasury yields has dented the allure for high-flying growth shares.                                                                                                                                                             , The Nasdaq 100 dropped 1.3% to close at 14,846.46, pulling it down more than 10% from its Nov. 19 closing record. Big swings in growth stocks continued Thursday, with the tech-heavy index turning sharply lower in the final hour of trading after earlier rising as much as 2%. On Wednesday, the broader Nasdaq Composite Index fell over the threshold into correction territory.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/google-appeals-27-billion-eu/story.aspx?guid={9A638A60-085F-4F07-A96F-DB9BF3DF6E31}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-21 04:42:40 </td>
   <td style="text-align:left;"> Google appeals $2.7 billion EU antitrust fine - MarketWatch </td>
   <td style="text-align:left;"> Google parent Alphabet Inc. on Thursday said it filed a final appeal of a $2.7 billion European Union antitrust fine to the EU's Court of Justice, its highest court. The latest appeal to overturn a 2017 fine linked to its shopping-ads service contends the General Court pushed beyond EU legal precedents and revised the reasoning of the underlying EU antitrust decision. "We feel there are areas that require legal clarification from the European Court of Justice," a Google spokeswoman said., Tesla Inc. is scheduled to report fourth-quarter earnings next Wednesday, as investors expect a return of Chief Executive Elon Musk to the post-results call and brace for what could be worrying news for the Cybertruck and supply-chain snags.                                                                                                                                                                                                                                                           , Jon Swartz is a senior reporter for MarketWatch in San Francisco, covering many of the biggest players in tech, including Netflix, Facebook and Google. Jon has covered technology for more than 20 years, and previously worked for Barron's and USA Today. Follow him on Twitter @jswartz. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/currency </td>
   <td style="text-align:left;"> 2022-01-21 04:38:19 </td>
   <td style="text-align:left;"> British Pound traded above 1.36 </td>
   <td style="text-align:left;"> The British Pound exchange rate rose above 1.36 US Dollars in the foreign exchange interbank market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-01-21 04:14:36 </td>
   <td style="text-align:left;"> FTSE 100 above 7550 </td>
   <td style="text-align:left;"> FTSE 100 rose above 7550 points. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/oil-prices-settle-lower-february/story.aspx?guid={CCC2CDF4-C152-4B66-81BD-9ED514027F37}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-21 03:43:38 </td>
   <td style="text-align:left;"> Oil prices settle lower as February WTI contracts expire - MarketWatch </td>
   <td style="text-align:left;"> Oil prices finished with a loss on Thursday after the Energy Information Administration reported an unexpected weekly rise in U.S. crude inventories. However, concerns over potential disruptions to global crude supplies, particularly as the market weighs the possibility of a Russian invasion of Ukraine, helped to limit price losses. February West Texas Intermediate crude 
        CLG22,
        -0.77%
       fell 6 cents, or nearly 0.1%, to settle at $86.90 a barrel on the New York Mercantile Exchange. The contract, which expired at the end of the session, finished Wednesday at the highest since October 2014. March WTI oil 
        CLH22,
        -2.84%,
       which is now the front-month contract, settled at $85.55, down 25 cents, or 0.3%.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , With several electric vehicles coming to the market by legacy and new auto makers soon, analysts at B. of A. Securities expect that a "tipping point" for EVs will happen this year, although higher prices would remain a constraint. The year 2022 "marks the start of commercialization for electric vehicles ... with many of start-up EV automakers launching/ramping new product and many of the incumbent automakers also beginning their product launch onslaught," the analysts said in a note Wednesday. B. of A. analysts said they expects about 1 million EVs sold in 2022, rising to about 1.8  million in 2023 and 3 million in 2024, implying EV penetration of around 6% this year, 11% in 2023, and 16% in 2024. Tesla Inc. undefined EV market share could fall to 19% by 2024, from 69% in 2021. Among "incumbent" auto makers in the U.S., Ford Motor Co. undefined and General Motors Co. undefined "appear to be the biggest share gainers in the EV market," the analysts said, both increasing their share from mid-single digits to mid-double digits over the period. Moreover, 2022 will be characterized by the production ad sales ramp of Lucid Group Inc.'s undefined Air sedan and Rivian Automotive Inc.'s undefined R1T pickup truck, R1S SUV, and the electric commercial van. It also could see the launch of Fisker Inc.'s undefined Ocean SUV, Canoo Inc. undefined Lifestyle Vehicle, and Lordstown Motors Corp.'s undefined Endurance pickup, the analysts said. , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-01-21 03:33:03 </td>
   <td style="text-align:left;"> WTI Crude Eases from Over 7-Year Highs </td>
   <td style="text-align:left;"> WTI crude futures slipped towards $86 per barrel on Thursday, easing from an over seven-year high of $87.9 touched on Wednesday, as investors paused for breath following a recent rally. Still, prices should remain close to their highest since 2014, supported by ongoing supply concerns and prospects of strong demand. The International Energy Agency (IEA) on Wednesday said that OPEC+ produced about 800,000 barrels per day (bpd) below its production targets in December, and that the oil market could be in a significant surplus in the first quarter of this year. In addition, heightened geopolitical tensions following an attack by Yemen's Houthis on the United Arab Emirates have also provided some support. On the data front, both the API and EIA reports showed US crude stocks unexpectedly rose last week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/20/here-are-3-things-to-know-about-unemployment-claims.html </td>
   <td style="text-align:left;"> 2022-01-21 03:26:51 </td>
   <td style="text-align:left;"> Here are 3 things to know about unemployment claims </td>
   <td style="text-align:left;"> , The number of people filing for unemployment benefits jumped last week to the highest level since October, the Labor Department said Thursday.                                                                                                                            , That may signal a troubling rebound, after claims hit recent lows unseen in over 50 years. But the one-week bump may not portend an ugly trend for the labor market, according to economists.                                                                             , Here's what to know.                                                                                                                                                                                                                                                      , A recent surge in Covid cases, fueled by the highly contagious omicron variant, likely contributed to the spike in claims last week, economists said. But the extent of that impact is unclear.                                                                           , Average daily U.S. Covid cases hit a recent peak of almost 798,000 on Jan. 15 — nearly double the tally from the beginning of the year and roughly eight times that of early December, according to Centers for Disease Control and Prevention data.                      , Meanwhile, initial claims for unemployment benefits (a proxy for applications) hit 286,000 the week ended Jan. 15, according to the Labor Department. That's an increase of 55,000, or 24%, from the prior week.                                                          , A decline in consumer demand amid rising caseloads may have led businesses to furlough workers. Others may have shut their doors temporarily if too many staff members were ill or exposed to the virus.                                                                  , "People are losing paychecks to omicron," Diane Swonk, the chief economist at Grant Thornton, said in a tweet. "The losses are large enough to apply for [unemployment insurance], which means layoffs being triggered by workers out ill and people's fear of contagion.", About 8.8 million workers said they were out sick with the virus or caring for an ill family member between Dec. 29 and Jan. 10 — a pandemic-era record, according to federal data.                                                                                       , (A quirk in unemployment rules disallows benefits for workers who test positive for Covid; but someone who's exposed or who loses hours due to a business shutdown may be eligible.)                                                                                      , However, elevated caseloads likely aren't the only factor at play, according to economists.                                                                                                                                                                               , January is normally a volatile time of year for jobless claims.                                                                                                                                                                                                           , That's largely due to seasonal labor patterns — layoffs of temporary holiday workers, construction projects affected by winter weather, people delaying a claim for benefits until after the holidays are over.                                                           , "It's pretty normal to see a spike in claims in January," according to Daniel Zhao, a senior economist at the career site Glassdoor.                                                                                                                                      , More from Personal Finance:Medicare doesn't cover at-home Covid testsWhy your 401(k) employer match may not be yours just yetNew program giving some mothers $1,000 a month                                                                                               , The Labor Department adjusts its weekly unemployment data to account for these seasonal patterns. But pandemic-era distortions to the labor market make it more difficult to control for those factors.                                                                   , "Seasonality in the best of times can be tricky to interpret, especially during a pandemic when everything is upside down and really wacky," according to AnnElizabeth Konkel, an economist at job site Indeed.                                                           , It's therefore hard to assess the impact of rising Covid cases on layoffs and furloughs relative to the typical winter reasons.                                                                                                                                           , That said, average unemployment claims have risen modestly, suggesting a slight upward trend. (The four- week average was up by 20,000 last week.)                                                                                                                        , "We are starting to see something. Maybe it's just a little blip, and hopefully not a longer multi-week trend," Konkel said. "My suspicion is this is the economic impact of the surge showing up in data."                                                               , Despite last week's pop, unemployment claims are still relatively low by historical standards. And layoffs aren't likely to surge to levels from earlier in the pandemic, economists said.                                                                                , Initial claims for benefits hovered around 215,000 in mid-January 2019 and 2020; 286,000 claims were filed last week.                                                                                                                                                     , "Initial claims are still fairly low, still close to pre-pandemic levels," Zhao said. "And the labor market was very strong before the pandemic."                                                                                                                         , Economists also don't expect layoffs (and hence jobless claims) to jump to levels seen earlier in the pandemic.                                                                                                                                                           , That's due largely to the current high demand for workers. Job openings are near record levels and a record 4.5 million people quit their jobs in November.                                                                                                               , "I don't think we'll see a repeat of massive layoffs we saw in early 2020," Konkel said. "[Businesses] are struggling to get workers in the first place, so they will think long and hard about layoffs."                                                                 , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                    , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                    , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                          , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                          , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                        , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/20/fed-releases-long-awaited-study-on-a-digital-dollar-but-doesnt-take-a-position-yet-on-creating-one.html </td>
   <td style="text-align:left;"> 2022-01-21 03:15:02 </td>
   <td style="text-align:left;"> Fed releases long-awaited study on a digital dollar but doesn't take a position yet on creating one </td>
   <td style="text-align:left;"> , The Federal Reserve on Thursday released its long-awaited study of a digital dollar, exploring the pros and cons of the much-debated issue and soliciting public comment.                                                                                                                                                                                                                 , Billed as "the first step in a public discussion between the Federal Reserve and stakeholders about central bank digital currencies," the 40-page paper shies away from any conclusions about a central bank digital currency, or CBDC. The report originally was expected in the summer of 2021 but had been delayed.                                                                    , Instead, it provides an exhaustive look at benefits such as speeding up the electronic payments system at a time when financial transactions around the world already are highly digitized. Some of the downside issues the report discusses are financial stability risks and privacy protection while guarding against fraud and other illegal issues.                                  , "A CBDC could fundamentally change the structure of the U.S. financial system, altering the roles and responsibilities of the private sector and the central bank," the report says.                                                                                                                                                                                                      , Fed Chairman Jerome Powell has been largely noncommittal in his public comments on the CBDC. The concept's biggest advocate is Fed Governor Lael Brainard, who has been nominated to be vice chair of the policymaking Federal Open Market Committee.                                                                                                                                     , Several other Fed officials have voiced skepticism over the digital dollar, saying the benefits are not obvious.                                                                                                                                                                                                                                                                          , One primary difference between the Fed's dollar and other digital transactions is that current digital money is a liability of commercial banks, whereas the CBDC would be a Fed liability. Among other things, that would mean the Fed wouldn't pay interest on money stored with it, though because it is riskless some depositors may prefer to keep their money with the central bank., The paper lists a checklist of 22 different items for which it is soliciting public feedback. There will be a 120-day comment period. Fed officials say the report is the first step in an extensive process but there is no timetable on when it will be wrapped up.                                                                                                                     , "We look forward to engaging with the public, elected representatives, and a broad range of stakeholders as we examine the positives and negatives of a central bank digital currency in the United States," Powell said in a statement.                                                                                                                                                  , The paper released Thursday notes that the Fed's "initial analysis suggests that a potential U.S. CBDC, if one were created, would best serve the needs of the United States by being privacy-protected, intermediated, widely transferable, and identity-verified."                                                                                                                      , However, the report also states that it "is not intended to advance a specific policy outcome and takes no position on the ultimate desirability of" the digital dollar.                                                                                                                                                                                                                  , Some of the most noted benefits are the speed of a Fed-controlled system in the case of, say, a need such as the beginning of the Covid pandemic to get stimulus payments to people quickly. Providing financial services to the unbanked also has been cited as an asset.                                                                                                                , However, the Fed already is in the midst of developing what it touts as a "round-the-clock payment and settlement service" called Fed Now that is expected to come online in 2023.                                                                                                                                                                                                        , Advocates of the digital dollar, though, worry that the Fed's delay in implementing a central bank currency will put it behind global competitors, specifically China, which already has moved forward with its own product. There have been suggestions that China's lead in the space ultimately could threaten the U.S. dollar hegemony as the world's reserve currency.               , However, Powell and other Fed officials say they are unconcerned with the speed of the project, stressing the need to get it right.                                                                                                                                                                                                                                                       , "The introduction of a CBDC would represent a highly significant innovation in American money," the report says. "Accordingly, broad consultation with the general public and key stakeholders is essential. This paper is the first step in such a conversation."                                                                                                                        , The Fed also said that it will not proceed without a clear mandate from Congress, preferably in the form of "a specific authorizing law."                                                                                                                                                                                                                                                 , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                    , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                    , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                          , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                          , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                        , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/argentina/balance-of-trade </td>
   <td style="text-align:left;"> 2022-01-21 03:13:14 </td>
   <td style="text-align:left;"> Argentina Balance of Trade Swings to Surplus </td>
   <td style="text-align:left;"> Argentina's trade balance recorded a surplus of USD 371 million in December 2021, swinging from USD 364 million deficit one year earlier. Exports surged 85.9% to USD 6.587 million, boosted by sales of agroindustrial (35.5 percent), industrial manufacturing (29.1 percent), primary goods (26.9 percent), and fuels &amp; energy (8.5 percent). Meanwhile, imports advanced 59.1 percent to USD 6,216 million, sustained by higher purchases of intermediate products (36.9 percent), capital goods (18.8 percent), parts &amp; accessories for capital goods (18.1 percent), and consumer goods (11.9 percent), while the purchase of passenger motor vehicles plunged (-27.8 percent). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/jb-hunt-stock-jumps-after/story.aspx?guid={884F7CB4-1703-4C7A-A299-47908BBC7668}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-21 03:06:13 </td>
   <td style="text-align:left;"> J.B. Hunt stock jumps after dividend raised by 33% - MarketWatch </td>
   <td style="text-align:left;"> Shares of J.B. Hunt Transport Services Inc. 
        JBHT,
        -0.12%
       rallied 1.8% in afternoon trading, after the trucking company said it raised its quarterly dividend by 33%, to 40 cents a share from 30 cents. The company said the new dividend will be payable Feb. 18 to shareholders of record on Feb. 4. Based on the current stock price, the new annual dividend rate implies a dividend yield of 0.78%, compared with the implied yield for the S&amp;P 500 
        SPX,
        -1.10%
       of 1.35%. J.B. Hunt's stock has now rallied 36.2% over the past 12 months, while the Dow Jones Transportation Average 
        DJT,
        -0.43%
       has advanced 20.9% and the S&amp;P 500 has gained 189%., A study of some of the first breakthrough cases of COVID-19 caused by the highly infectious omicron variant found that booster shots of the mRNA vaccines failed to block that strain, although the infections involved only mild or moderate symptoms, confirming they are effective in preventing serious illness and death.                                                                                                                                                                                                                                                                                                                                                                                                             , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60073252?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-21 02:50:30 </td>
   <td style="text-align:left;"> Carhartt facing calls for boycott over vaccine mandates </td>
   <td style="text-align:left;"> Carhartt, the work wear and outdoor gear maker, is facing calls for a boycott among conservatives opposed to its vaccine mandate for staff.                                                                                                                                                                 , The outcry comes amid fierce debate in the US over Covid-19 jabs.                                                                                                                                                                                                                                           , This month, the US Supreme Court said the government could not force large employers to make Covid-19 vaccination or weekly testing mandatory.                                                                                                                                                              , Companies including the coffee chain Starbucks have since reversed their plans for such rules.                                                                                                                                                                                                              , But in a recent memo to staff, Carhartt leaders said the Supreme Court decision had not changed company requirements, which went into effect for much of their staff in early January.                                                                                                                      , "We put workplace safety at the very top of our priority list and the Supreme Court's recent  ruling doesn't impact that core value," wrote Carhartt's chief executive Mark Valade, a descendant of the company's founder.                                                                                  , "While we appreciate that there may be differing views, workplace safety is an area where we and the union that represents our associates cannot compromise.  An unvaccinated workforce is both a people and business risk that our company is unwilling to take. "                                         , After copies of the message were circulated on social media, prominent conservatives and Republican figures weighed in.                                                                                                                                                                                     , "Well Carhartt has labelled the unvaccinated dangerous and implemented a vaccine mandate," conservative attorney Molly McCann wrote on Twitter.                                                                                                                                                             , "Pretty rich from a company sustained by the ranchers, farmers, labourers, etc. who make this country great and celebrate her values of freedom and liberty."                                                                                                                                               , "Boycott Carhartt until they break," she said.                                                                                                                                                                                                                                                              , Founded in 1889, Carhartt employs more than 5,500 people globally. It is privately-owned and based in Michigan, a state in the middle of the US that is fiercely divided between Republicans and Democrats.                                                                                                 , Self-promoted as a brand for "hard-working" people, Carhartt made its name supplying labourers and farm workers. But it has also been embraced by fashionistas in Europe, where it has a longstanding "Work in Progress" design line.                                                                       , In recent years, which the firm has described as a "growth period", Carhartt caps and coats have turned up everywhere from playgrounds to the Golden Globes. A 2017 article in men's magazine Esquire described it as one of the rare brands able to transcend America's political divide - at least so far., "Regardless of the boycott, when you think about core American fashion brands, people always mention Ralph Lauren and Levi, but Carhartt is also on that list," said Jeff Carvalho, co-founder of men's fashion site Highsnobiety. "They're just quite important."                                          , Mr Carvalho, a collector of vintage Carhartt gear, said conservatives represent an important consumer base for the brand, but he believes it will survive the current firestorm, noting that buyers have few alternatives. He asked: "Who are they going to turn to otherwise?"                             , "It is the uniform, or tuxedo of American industry."                                                                                                                                                                                                                                                        , Carhartt, which has factories in Kentucky and Tennessee as well as Mexico, said the "vast majority" of its staff are fully vaccinated or in the process of getting their jabs. It also granted "a number" of religious and medical exemption requests.                                                      , A spokeswoman for the company said: "Carhartt fully understands and respects the varying opinions on this topic, and we are aware some of our associates do not support this policy.                                                                                                                        , "However, we stand behind our decision because we believe vaccines are necessary to protect our workforce."                                                                                                                                                                                                 , Just over a third of US workers are now covered by vaccine mandates, according to a Gallup poll in December.                                                                                                                                                                                                , While the Supreme Court struck down the national requirement, courts have been more open to states and companies setting their own policies.                                                                                                                                                                , Investment bank Citigroup and United Airlines are among the firms that have moved forward with vaccine mandates. United Airlines's boss Scott Kirby recently told staff that the policy had saved lives.                                                                                                    , Other firms have wavered in the face of opposition.                                                                                                                                                                                                                                                         , About 55% of US workers support vaccination requirements at work, a Gallup poll found in December. But more than a third were strongly opposed. Divide over the issue is linked to politics, with Republicans leading the opposition.                                                                       , Business groups say companies are worried about compliance costs and staff recruitment. About 63% of Americans are fully vaccinated but that number varies significantly depending on location.                                                                                                             , Go behind the scenes at London's Corinthia Hotel                                                                                                                                                                                                                                                            , Hidden Assets: A gritty Irish crime thriller on BBC iPlayer                                                                                                                                                                                                                                                 , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/20/business/mazda-miatas-driving.html </td>
   <td style="text-align:left;"> 2022-01-21 02:41:33 </td>
   <td style="text-align:left;"> They’ve Driven Everything, but the Miata Keeps Them Smiling - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Wheels                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Auto industry people have a special affection for Mazda’s petite (and affordable) roadster.                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                                                                                                               , By Jim Motavalli                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Emme Hall, an auto journalist, loves to go off-roading, and she also loves Buddy, her 2001 Mazda MX-5 Miata sports car.                                                                                                                                                                                                                                                                                                                                                                                                                      , Normally these two loves would be star-crossed, but not in Ms. Hall’s case. The Miata (one of two she owns) is happiest away from the pavement: It’s lifted to give the normally low-slung roadster 10 inches of ground clearance, and has a beefed-up radiator to cope with hot trail days, a skid plate to protect the vulnerable undercarriage, a row of rally lights, a skimpy bikini top for sun protection and huge 27-inch tires. Despite the stock 1.8-liter engine, producing a modest 142 horsepower, it can and does get airborne., Buddy has more than 130,000 miles on the odometer. Ms. Hall’s day job includes racing in events like the Baja 1000 and Mint 400 (as well as the Rebelle and Gazelle rallies), then writing about the experience in outlets like CNET Roadshow.                                                                                                                                                                                                                                                                                               , Taking Buddy off the beaten path, even if it results in broken axles, is what she does for fun. Ms. Hall, who lives in Yucca Valley, Calif., is one of a large group of auto industry people — executives, analysts and journalists — who, having driven everything else, buy and enjoy Mazda Miatas.                                                                                                                                                                                                                                        , The little cars combine affordability with clever engineering, dependability and driving fun, they say — even at low speeds. Miata values have been rising, too — especially for the first, so-called NA generation of the model years 1990 to 1998 — but hardly into Porsche or Ferrari territory. Hagerty estimates that a fully restored 1990 Miata is worth $29,800.                                                                                                                                                                     , “The best part of Buddy is that he makes everyone smile — they leave notes on him when I go for gas,” said Ms. Hall, who also has a 178-horsepower 2004 NB (second-generation) Mazdaspeed Miata with a turbocharger.                                                                                                                                                                                                                                                                                                                         , “Miatas are simple, even the new ones,” she said. “There’s not a lot to interfere with your driving. I can wind my Miata out just going from one traffic light to another. Plus, they’re cheap — I don’t like spending a lot of money on a car.”                                                                                                                                                                                                                                                                                             , McKeel Hagerty, chief executive at the classic-car insurer Hagerty, explained the appeal. “The Miata is the signature car in the recent evolution of the car world,” he said.                                                                                                                                                                                                                                                                                                                                                                , “More than one million have been built, and you can track them or just cruise,” he added. “Miatas offer the best way into vintage racing. They’re incredibly reliable, and they hold value well.”                                                                                                                                                                                                                                                                                                                                            , Gregor Hembrough, the head of Polestar North America, chose a 2002 Miata as daily transportation when he worked for Volvo in Goteborg, Sweden, in the early 2000s.                                                                                                                                                                                                                                                                                                                                                                           , “An MX-5 isn’t the obvious choice as a daily driver for someone residing in Sweden,” Mr. Hembrough acknowledged. “However, for me, the lure of a pure sports car was too strong to overcome. For autumn and winter, the car had heated seats, a limited slip differential, a removable hardtop and studded snow tires.”                                                                                                                                                                                                                      , He added: “For spring and summer, I enjoyed countless long evenings with the top down and the music up. It was a sad day when I returned to the U.S. and the car went on to a new home.”                                                                                                                                                                                                                                                                                                                                                     , Owners tend to drive their Miatas, rather than merely admire them as garage ornaments. Mr. Hembrough put 19,000 miles on his over three years of ownership.                                                                                                                                                                                                                                                                                                                                                                                  , To relax, Sam Abuelsamid, principal analyst for e-mobility at Guidehouse Insights in Detroit, regularly takes out his 1990 Miata — a very early model built in October 1989. “My dog, Rosie, likes riding in it,” Mr. Abuelsamid said. “She’s tall enough to stick her head out.”                                                                                                                                                                                                                                                            , He added, “The Miata is the definitive example of why it can be more fun to drive a slow car fast than a fast car slow. Behind the wheel, the Miata is like an extension of my hands — I can explore its limits and not be at speeds that will get me thrown in jail.”                                                                                                                                                                                                                                                                       , Mr. Abuelsamid covers electric, autonomous and connected cars, and he road-tests the latest models. To unwind, however, he goes old school, putting the top down and driving to nowhere in particular for a couple of hours.                                                                                                                                                                                                                                                                                                                 , Stephanie Brinley, principal analyst for the Americas in IHS Markit’s automotive division, is on her second Miata in Troy, Mich. To tackle Michigan winters, she throws snow tires on — even putting the top down sometimes if the sun is out.                                                                                                                                                                                                                                                                                               , “My first Miata was a 1998 I bought gently used with only 1,500 miles on the odometer,” Ms. Brinley said. “I was replacing an Acura Integra GS-R, which is a pretty sporty car, and I wanted something that would be just as much fun but still in a reasonable price range. After 15 years I got tired of having to take the Miata’s hardtop on and off every year, and bought a 2012 NC with the power retractable hardtop.”                                                                                                               , “It remains the best bang for your buck,” she added. “The new Corvette is a wonderful machine, but it’s bigger and more expensive and not as good as the Miata to use as an everyday car. I always smile when I drive my Miata, even after owning it for years. It’s such a well-balanced little thing.”                                                                                                                                                                                                                                     , Chris Nelson, a former senior editor at Automobile Magazine who now edits Drool (for dog owners) and Iron &amp; Air (about motorcycles), is an ex-Miata owner. But he made sure his separation from Gracie, the silver 1991 car he inherited from his father, was as dramatic as possible.                                                                                                                                                                                                                                                       , “It was a nice car, with the speakers in the headrests that let me listen to books on tape, and I drove it for 15 years,” said Mr. Nelson, who lives in Long Beach, Calif. “I loved that car, but I was doing a lot with motorcycles, and I needed a truck.                                                                                                                                                                                                                                                                                  , “After my father died, my mom was having a hard time, so when she turned 60 I took her on a 2,000-mile road trip in the Miata around California, from Hermosa Beach up through Big Sur,” he continued. “Then I pulled off the right front fender and sent it to a jewelry maker — who made a bracelet and a ring as remembrances for my mother. Then, in 2018, I found another fender and sold the car.”                                                                                                                                     , Mr. Nelson said the key to the Miata “is the simplicity — cars are so complicated now.”                                                                                                                                                                                                                                                                                                                                                                                                                                                      , “The NA epitomized Japanese design, with minimal obstructions to the sightlines. In the Midwest, where I’m from, they make fun of the Miata, but they just don’t understand what makes it great.” While he was at Automobile, a half dozen other employees owned Miatas, he said.                                                                                                                                                                                                                                                            , Despite liking the car in bone-stock form, Mr. Nelson said the ultimate iteration was a conversion sporting a small-block V-8 engine, such as a General Motors LS1. “That’s my dream car,” he said. “It’s the best to drive, and the bigger engine upsets the weight balance only a little bit.”                                                                                                                                                                                                                                             , Perry Stern, formerly an editor at MSN Autos and now at AutoNXT, decided he had to own a Miata after attending the press introduction of the third-generation NC.                                                                                                                                                                                                                                                                                                                                                                            , “Ultimately,” he said, “I convinced my wife I needed something more fuel-efficient than the 2004 Ford Explorer I was driving. I found a used 2006 Miata — the first year of the NC — with only 47,000 miles in 2014.”                                                                                                                                                                                                                                                                                                                        , Mr. Stern, who lives in Sammamish, Wash., drives the car sparingly (it’s at 58,700 now), but — you guessed it — “it still brings a smile every time I take it out for a drive,” he said. “Even if I’m not driving it, it makes me happy to look in the garage and see it there. I expect to own it until the day I die.”                                                                                                                                                                                                                     , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/u-s-dismisses-criminal-charges-mit-professor-accused-hiding-china-ties </td>
   <td style="text-align:left;"> 2022-01-21 02:30:56 </td>
   <td style="text-align:left;"> US dismisses criminal charges against MIT professor accused of hiding China ties </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.
                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Federal prosecutors dropped criminal charges against a Massachusetts Institute of Technology mechanical engineering professor accused of hiding his China ties, saying in a Thursday filing that the government no longer believed it could prove its case at trial.                                                                                                                                                                                                                                  , Gang Chen was arrested last January on charges of concealing posts he held in China in a grant application he had made to the U.S. Department of Energy in 2017. The Wall Street Journal reported last week that prosecutors had recommended that the Justice Department drop the case, based in part on witness testimony that investigators obtained since his arrest, citing people familiar with the matter.                                                                                      , One of those people included an Energy Department official who told prosecutors in recent weeks that the agency didn’t believe Mr. Chen had an obligation to disclose the posts at the time, and didn’t believe the department would have withheld the grant if officials had known about them. The Energy Department in 2017 started asking researchers for more information about their foreign connections.                                                                                        , "As a result of our continued investigation, the government obtained additional information bearing on the materiality of the defendant’s alleged omissions," prosecutors wrote. "Having assessed the evidence as a whole in light of that information, the government can no longer meet its burden of proof at trial."                                                                                                                                                                              , Gang Chen, a professor at the Massachusetts Institute of Technology (Wen Zeng/MIT/Handout via Reuters / Reuters)                                                                                                                                                                                                                                                                                                                                                                                      , CHINA'S ECONOMY LOSES STEAM AS COVID-19 ERUPTS, CENTRAL BANK CUTS RATES                                                                                                                                                                                                                                                                                                                                                                                                                               , The judge overseeing the case, U.S. District Judge Patti Saris, signed off on the dismissal, but could ask the government for more information about its decision.                                                                                                                                                                                                                                                                                                                                    , In a statement, Mr. Chen’s lawyer, Rob Fisher, said: "The government finally acknowledged what we have said all along: Professor Gang Chen is an innocent man." Mr. Fisher added that Mr. Chen was never in a Chinese government talent recruitment program and never served as an overseas strategic scientist for Beijing, as prosecutors had initially alleged.                                                                                                                                    , In a December article, the Journal reported on how U.S. government investigators pursued Mr. Chen on suspicions that he had forged a collaboration between MIT and a university in Shenzhen to benefit China, though the collaboration had the support of MIT. Some of the posts Mr. Chen was accused of hiding, the Journal reported, were either connected to his relationships through MIT or those he wasn’t paid for, and Justice Department officials had discussed dropping his case last year., Students walk past the "Great Dome" atop Building 10 on the Massachusetts Institute of Technology campus, April 3, 2017, in Cambridge, Massachusetts. (AP Photo/Charles Krupa, File / AP Newsroom)                                                                                                                                                                                                                                                                                                    , TESLA INKS DEAL TO GET KEY BATTERY COMPONENT OUTSIDE CHINA                                                                                                                                                                                                                                                                                                                                                                                                                                            , The U.S. Attorney in Boston, Rachael Rollins—who was sworn in to the post last week after Vice President Kamala Harris broke a tie on her confirmation—said in a statement that prosecutors had an obligation "to continually examine the facts while being open to receiving and uncovering new information."                                                                                                                                                                                        , "Today’s dismissal is a result of that process and is in the interests of justice," Ms. Rollins said.                                                                                                                                                                                                                                                                                                                                                                                                 , MIT had supported Mr. Chen since his arrest and continued to pay his legal bills. After prosecutors’ Thursday filing, MIT President Rafael Reif posted a letter to the MIT community saying, "Having had faith in Gang from the beginning, we can all be grateful that a just outcome of a damaging process is on the horizon. We are eager for his full return to our community."                                                                                                                    , Mr. Chen was one of around two dozen academics charged since 2019 with allegedly lying about their affiliations, in attention-grabbing cases brought by the Justice Department to address suspicions that the Chinese government was exploiting academic ties to engage in technological espionage.                                                                                                                                                                                                   , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Some of the cases have been successful for the U.S. government. A jury convicted Harvard University chemistry professor Charles Lieber in December 2021, for example, of lying to Defense Department investigators and others about his participation in the Chinese government’s Thousand Talents program aimed at wooing foreign experts.                                                                                                                                                           , But another case, the first to go to trial, ended in an acquittal in September after a judge said that prosecutors had provided no evidence that the professor intended to deceive the government, and prosecutors have dropped several other cases.                                                                                                                                                                                                                                                  , Attorney General Merrick Garland said in October that he would task the Justice Department’s assistant attorney general for national security, Matt Olsen, with reviewing the department’s approach to countering threats posed by the Chinese government. The Justice Department is expected to provide more information about the results of that review in the coming weeks, a spokesman has said.                                                                                                 , Click here to read more on the Wall Street Journal. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/peloton-stock-price-bike-tread-production-halt </td>
   <td style="text-align:left;"> 2022-01-21 02:19:26 </td>
   <td style="text-align:left;"> Peloton stock tanks on bike production halt report </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.
                                                                                                                                                                                                                                             , Peloton shares got pummeled on reports it is pausing bike production.                                                                                                                                                                                                                         , Shares fell 23.9% to $24.22, a two-year low.                                                                                                                                                                                                                                                  , The move comes as demand wanes and costs rise, according to CNBC, which cited an internal memo. Additionally, another report said the company will delay opening its new factory in Troy Township, Ohio until 2024, according to the New York Post, which cited sources close to the company. , FOX Business' inquires to the company were not immediately returned.                                                                                                                                                                                                                          , The fitness-tech company recently announced price hikes for its original Bike and Tread products that will take place at the end of the month.                                                                                                                                                , INSIDE A YEAR AT PELOTON: FROM PANDEMIC WINNER TO HBO PUNCHLINE                                                                                                                                                                                                                               , Beginning Jan. 31, Peloton will charge a $250 delivery and setup fee for its original Bike and a $350 delivery and setup fee for its original Tread, according to a banner on its website. The delivery and setup fees were previously included with the purchase of the machines.            , The increases will bring the costs of the machines to $1,745 and $2,845, respectively. Financing options will be available for eligible customers starting as low as $67 per month over 43 months at 0% APR. Additional delivery fees may apply outside the continental U.S.                  , FOX Business' Lucas Manfredi contributed to this report.    </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/pelosi-congressional-trade-stock-bans </td>
   <td style="text-align:left;"> 2022-01-21 02:01:38 </td>
   <td style="text-align:left;"> Pelosi reverses course, signals openness to banning congressional stock trades </td>
   <td style="text-align:left;"> Seaport Securities founder Teddy Weisberg and The Price Futures Group energy analyst Phil Flynn discuss value in a 'choppy' market on 'The Claman Countdown.'                                                                                                                                                                                                                                                                                                                        , House Speaker Nancy Pelosi on Thursday suggested that she will consider proposals banning members of Congress from trading stocks while in elective office, a sharp reversal from just a month ago when she adamantly defended the practice.                                                                                                                                                                                                                                         , "I've said to the House Administration Committee, review all the bills that are coming in and see which ones — where the support is in our caucus," Pelosi said Thursday. "If members want to do that, I'm OK with that."                                                                                                                                                                                                                                                            , ELIZABETH WARREN DEMANDS POWELL RELEASE MORE DETAILS ABOUT FED TRADING SCANDAL                                                                                                                                                                                                                                                                                                                                                                                                       , The about-face comes after weeks of pressure from Democrats and Republicans, with lawmakers on both sides of the political aisle introducing legislation that would prohibit, or limit, members of Congress and their spouses in some cases, from trading stocks while in office. The stock-ban bills have come from a number of lawmakers, including Sens. Jon Ossoff, D-Ga., Mark Kelly, D-Ariz., Josh Hawley, R-Miss., and Reps. Abigail Spanberger, D-Va., and Chip Roy, R-Texas., Speaker of the House Nancy Pelosi, D-Calif., meets with reporters at the Capitol in Washington, Wednesday, Sept. 8, 2021.  (AP Photo/J. Scott Applewhite / AP Newsroom)                                                                                                                                                                                                                                                                                                              , Still, Pelosi did not fully backtrack, defending her previous comments and saying that she has "great confidence in the integrity" of her colleagues.                                                                                                                                                                                                                                                                                                                                , "They are remarkable," she said. "So when people talk about well, somebody might do this, and somebody, I trust them. If in fact we should have severer penalties for delays in reporting on the STOCK Act, then do that."                                                                                                                                                                                                                                                           , Those comments closely track with her previous statement in December, when she told reporters that lawmakers should be allowed to trade stocks if they choose to do so.                                                                                                                                                                                                                                                                                                              , "We are a free market economy. They should be able to participate in that," Pelosi told reporters on Dec. 15 when asked about the subject.                                                                                                                                                                                                                                                                                                                                           , Pelosi does not own any stock herself, but her husband holds tens of millions of dollars worth of stocks and options in companies like Apple, Disney, Amazon and Google. Lawmakers' spouses are allowed to trade in companies or industries that their partner may help regulate.                                                                                                                                                                                                    , But under the STOCK Act, passed in 2012, it's illegal for members of Congress and their families to profit from inside information and it requires lawmakers to report stock trades to Congress within 45 days. In some recent cases, lawmakers have failed to report their trades altogether.                                                                                                                                                                                       , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                          , "We have a responsibility to report," Pelosi said last month. "If people aren’t reporting they should be."                                                                                                                                                                                                                                                                                                                                                                           , Pelosi is worth an estimated $114 million, according to her 2018 personal financial disclosure, making her the sixth-richest member of the House and the 10th richest member of Congress, according to data tracked by the Center for Responsive Politics.                                                                                                                                                                                                                           , Other Democrats, such as Rep. Alexandria Ocasio-Cortez, D-N.Y., and Sen. Elizabeth Warren, D-Mass., have voiced support for banning trading among members of Congress.                                                                                                                                                                                                                                                                                                               , Former President Trump recently slammed Pelosi for her family's stock trades, saying "it's not fair to the rest of the country." House Minority Leader Kevin McCarthy has also floated the possibility of a ban or fresh trading limits if Republicans win the majority in November.                                                                                                                                                                                                 , Although Pelosi opened the door to a House vote on a potential ban, she said the Supreme Court should also enact some measures to disclose stock trades.                                                                                                                                                                                                                                                                                                                             , "I don't think that the court should be let off the hook," Pelosi said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/20/stocks-making-the-biggest-moves-midday-marriott-mastercard-casper-etsy-and-more.html </td>
   <td style="text-align:left;"> 2022-01-21 01:27:19 </td>
   <td style="text-align:left;"> Stocks making the biggest moves midday: Marriott, Mastercard, Casper, Etsy and more </td>
   <td style="text-align:left;"> , Check out the companies making headlines in midday trading.                                                                                                                                                                                                                                                                                                                     , Peloton — The at-home fitness company's shares tumbled 23.93% after the stationary bike maker announced it will temporarily halt production of its bikes and treadmills due to waning demand as it tries to control costs. The news comes as about $40 billion has been shaved off Peloton's market cap over the past year.                                                     , Marriott International — Shares of the hotel chain 1.6% after the company provided an update on its development process in 2021. Marriott said it added more than 86,000 rooms on a gross basis, growing the system 3.9%, including room deletions of 2.1%. It also said that by the end of the year it had the largest global development pipeline, with roughly 485,000 rooms., Baker Hughes — The energy tech company's shares gained 1.6% after it reported strong quarterly earnings. Reported revenue of $5.5 billion beat FactSet estimates of $5.4 billion. Adjusted EBITDA came in at $844 million, compared to estimates of $787.2 million.                                                                                                             , Travelers Companies — The insurance stock popped 3.1% on Thursday after Travelers blew past estimates for earnings and revenue for the fourth quarter. The company reported $5.20 in earnings per share on $8 billion in revenue, with net premiums written rising 10% year over year. Analysts surveyed by Refinitiv had projected $3.86 per share on $7.71 billion of revenue., Regions Financial — The bank's stock slid 5.2% after the company reported quarterly earnings that were lower than expected by 6 cents per share, as well as revenue that matched analyst estimates.                                                                                                                                                                             , M&amp;T Bank — Shares of the regional bank fell 5.4% after the company reporter lower-than-expected earnings for the most recent quarter. Interest margins were also lower than expected at 2.58%, compared to estimates of 2.67%.                                                                                                                                                  , International Flavors &amp; Fragrances — Shares of the New York-based fragrance company increased 1.1% after CNBC's David Faber reported that longtime activist investor Carl Icahn took a 4% stake in the company. Separately, International Flavors &amp; Fragrances named Frank Clyburn chief executive officer effective Feb. 14.                                                   , Casper Sleep — Shares of the mattress company surged 9.7% after Casper announced that its board had approved a takeover offer from private equity firm Durational Capital Management. The deal values Casper at $6.90 per share.                                                                                                                                                , Mastercard — The card giant saw shares rise almost 1% after it launched a virtual card solution that will allow for instant business-to-business payments. The news follows more new product announcements from Wednesday, including a cobranded credit card with Instacart and an NFT partnership with Coinbase.                                                               , Signet Jewelers — Shares fell 9.6% after the jewelry retailer said holiday sales rose 30.4% from year prior. Same-store sales also jumped more than 25%, the company said.                                                                                                                                                                                                      , Etsy — The online marketplace saw its shares rise 2.3% after the stock received an upgrade from KeyBanc to overweight from sector weight. The firm's price target of $200, implies about 22% upside.                                                                                                                                                                            ,  — CNBC's Jesse Pound, Hannah Miao and Yun Li contributed reporting                                                                                                                                                                                                                                                                                                             , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                          , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                          , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                              , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/wells-fargo-wins-termination-2015/story.aspx?guid={43EE51AF-1917-46C9-B9A3-7C73786EEE32}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-21 01:23:59 </td>
   <td style="text-align:left;"> Wells Fargo wins termination of 2015 regulatory order - MarketWatch </td>
   <td style="text-align:left;"> Wells Fargo &amp; Co. 
        WFC,
        -1.03%
       on Thursday confirmed that the Office of the Comptroller of the Currency (OCC) terminated a consent order from 2015 stemming from billing and marketing practices on identity and debt cancellation products offered by the bank. "The OCC believes that the safety and soundness of the bank and its compliance with laws and regulations does not require the continued existence of the order," the federal regulatory agency said in a legal document posted on its website. The OCC had charged the bank in 2015 with deficiencies in the bank's practices and issued a cease and desist order. Wells Fargo said the termination of the 2015 OCC order fits its "top priority" to build a risk and control infrastructure that's "appropriate for its size and complexity." Shares of Wells Fargo rose 0.6% on Thursday after gaining 16.5% so far in 2022. The stock is up 72.1% in the past year, ahead of the 19% gain by the S&amp;P 500 
        SPX,
        -1.10%.
      
, Here's what the chief executive of ARK Invest had to say.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Steve Gelsi covers banking and cannabis as a Senior Reporter for MarketWatch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-01-21 01:16:00 </td>
   <td style="text-align:left;"> South African Stocks End at New Record High </td>
   <td style="text-align:left;"> The FTSE/JSE All Share Index closed marginally higher at a fresh record high of 76,233 on Thursday, as strength in miners amid higher precious metal prices was countered by losses in banks, industrials and real estate. At the same time, investors continued to weigh the implications of a tighter monetary policy against a strong US earnings season and prospects of recovery, while welcoming more monetary stimulus from China. Domestically, South Africa has declared a national disaster after torrential rains in several parts of the country resulted in deaths, flooding and damage to property and infrastructure. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/omicron-worker-shortage-disrupts-us-manufacturing </td>
   <td style="text-align:left;"> 2022-01-21 01:04:36 </td>
   <td style="text-align:left;"> Omicron, worker shortage disrupts US manufacturing </td>
   <td style="text-align:left;"> Generac Power Systems CEO Aaron Jagdfeld outlines the problems his company is facing, including more than 200 open positions and the need to increase wages.                                                                                                                                                                                                                                       , A generator manufacturer in Wisconsin is trying to balance more than 200 open positions and rising input costs as demand for its products continues to soar.                                                                                                                                                                                                                                       , Generac Power Systems CEO Aaron Jagdfeld provided the insight during a live interview on "Varney &amp; Co." and outlined the challenges his company has been faced with amid supply chain disruptions coupled with the "incredibly disruptive" surge in omicron cases, which he noted significantly interfered with the manufacturing process.                                                         , Jagdfeld said his absenteeism rate increased 15% for a period of time at the peak because his employees were either isolating due to contracting COVID-19 or getting exposed.                                                                                                                                                                                                                      , "Since the end of December to today it’s just been interrupting our operations pretty severely," he told FOX Business’s Grady Trimble, speaking from his factory in Whitewater.                                                                                                                                                                                                                    , Jagdfeld explained that he was able to navigate the situation by being "nimble" and "flexible."                                                                                                                                                                                                                                                                                                    , He said he "moved a lot of people around" when possible, however noted that the situation limited how much the company could produce during that time.                                                                                                                                                                                                                                             , Strong consumer demand for goods and continued port congestion in America as well as shortages of truck drivers and elevated global freight rates continue to hang over any supply chain recovery, the Wall Street Journal reported, citing executives and economists. On top of labor shortages, weather interruptions and raging omicron cases also threaten to clog up supply chains.           , Chris Spear, president and CEO of the American Trucking Associations argues the slow return to work is 'exacerbating the supply chain's ability to meet demand,' noting that truckers are moving more with less people.                                                                                                                                                                            , On Tuesday, American Trucking Associations President and CEO Chris Spear explained on "Mornings with Maria" the impact on the supply chain due to the "chronic shortage of talent," which has led to cargo sitting unused and unloaded at U.S. ports.                                                                                                                                              , He also noted that now truckers are moving more with fewer people and "even less equipment in many instances."                                                                                                                                                                                                                                                                                     , "I think we are at the edge of a cliff right now," Spear told host Maria Bartiromo, noting that the trucking industry is "short 81,000 drivers."                                                                                                                                                                                                                                                   , Earlier this month it was revealed that the latest JOLTS report on job openings sits at 10.6 million in November after hitting a record 11.03 million the month before.                                                                                                                                                                                                                            , Jagdfeld noted that he had to increase worker wages in an attempt to retain the people currently employed at his company.                                                                                                                                                                                                                                                                          , He said that because he is having to raise wages and is dealing with higher costs for materials as well as logistics, he has been forced to increase prices for his products.                                                                                                                                                                                                                      , INFLATION CALCULATOR: SEE HOW HIGHER PRICES ARE HITTING YOUR WALLET                                                                                                                                                                                                                                                                                                                                , "All of those costs are up for us, so prices have gone up," Jagdfeld stressed.                                                                                                                                                                                                                                                                                                                     , Former McDonald's USA CEO Ed Rensi warns Americans are feeling the labor shortage 'big time' amid a confluence of events, calling it a 'nightmare.'                                                                                                                                                                                                                                                , As a result of all the challenges presented, Jagdfeld warned on Thursday that inflation is "definitely" here to stay and is not transitory as the Federal Reserve initially claimed.                                                                                                                                                                                                               , "I think we’ve been seeing this over the last year for what it is," he stressed. "I mean as wages go up, very rarely do wages come back down."                                                                                                                                                                                                                                                     , Jagdfeld provided the insight one week after it was revealed inflation rose at the fastest pace in nearly four decades in December, as rapid price gains fueled consumer fears about the economy.                                                                                                                                                                                                  , The consumer price index rose 7% in December from a year ago, according to a new Labor Department report released last Wednesday, marking the fastest increase since June 1982, when inflation hit 7.1%. The CPI – which measures a bevy of goods ranging from gasoline and health care to groceries and rents – jumped 0.5% in the one-month period from November.                                , Economists expected the index to show that prices surged 7% in December from the year-ago period and 0.4% from the previous month.                                                                                                                                                                                                                                                                 , Biden and Harris meet with Infrastructure Implementation Task Force to discuss 'delivering results'                                                                                                                                                                                                                                                                                                , President Biden on Thursday pointed to the Federal Reserve as holding the key responsibility for addressing soaring inflation in the U.S.                                                                                                                                                                                                                                                          , The president acknowledged during a White House media conference that rising prices are a problem for Americans and that "we need to get inflation under control," saying that the coronavirus pandemic "created a lot of economic complications, including rapid price increases across the world economy."                                                                                       , "So here's what we're going to do," Biden said. "A critical job in making sure that the elevated prices don't become entrenched rests with the Federal Reserve, which has a dual mandate: full employment and stable prices."                                                                                                                                                                      , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                        , Fed Chairman Jerome Powell has already signaled the U.S. central bank may speed up its withdrawal of pandemic support for the U.S. economy in order to combat inflation, which has been higher and longer-lasting than policymakers initially expected. That could mean the Fed's bond-buying program ends sooner than expected, potentially leading to a faster-than-expected interest rate hike. , "At this point, the economy is very strong, and inflationary pressures are high," Powell recently said while testifying on Capitol Hill. "It is therefore appropriate in my view to consider wrapping up the taper of our asset purchases, which we actually announced at our November meeting, perhaps a few months sooner."                                                                      , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                            , FOX Business’ Megan Henney and Breck Dumas contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-01-21 01:02:54 </td>
   <td style="text-align:left;"> French Stocks Extend Gains </td>
   <td style="text-align:left;"> The CAC 40 Index recovered from early losses to close 0.3% higher at 7,194 on Thursday, extending last session’s 0.6% gain, supported by healthcare and utilities shares although investors continue to weigh on inflationary pressure. While the euro area’s inflation rate was confirmed at a record high of 5% and policymakers noted prices could stay higher for longer than expected, ECB President Lagarde reiterated that interest rate hikes should not be rushed. On the corporate front, healthcare stocks jumped 1.2%, driven by a surge in Valneva shares (19.8%) after preliminary data suggested that three doses of the biotech’s new Covid vaccine can neutralize the Omicron variant. At the same time, Vivendi gained 1.5% after Goldman Sachs raised the company’s recommendation to “buy”. Engie (1.7%) and Veolia Environmental (2.2%) also closed on the green. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/hunter-biden-aide-invested-chinese-company-communist-party </td>
   <td style="text-align:left;"> 2022-01-21 01:00:50 </td>
   <td style="text-align:left;"> Hunter Biden, former Biden aide invested in Chinese company tied to Communist Party, NBA China </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , EXCLUSIVE: As recently as March 2017, Hunter Biden's private equity firm held a stake in a company run by a Chinese executive with ties to officials at some of the highest levels of the Communist Party of China, according to emails reviewed by FOX Business.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Hunter Biden’s longtime business partner, Eric Schwerin, sent him an email in March 2017 breaking down the ownership interests of Rosemont Seneca Advisors, which included a 5% stake in Harves Amusement Parks and ownership in Harves Sports and Entertainment.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Biden's introduction to the Harves Group came about two years earlier, when Francis Person, who served as an adviser to then-Vice President Biden from 2009 to 2014 and was a "special assistant" to Biden in the Senate, sent an email to Hunter Biden in July 2015 inviting him to China the following month to meet his business partner, Bo Zhang, and his family.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , "Bo Zhang and his family would host us. They are a great family with great respect and relationships in China. Bo graduated from American Univ and is in his late 20’s, and his parents own Harves Century Group of Shenyang - which is a top tier private chinese real estate development firm," Person wrote. "His mom is actually the Chairman of the company, which is unique in China. They are very private, and wouldn’t tell anyone about you coming. Bo's father-in-law is actually the Governor of Hainan (Chinese Hawaii), which he doesn’t advertise at all."                                                                                                                                                                                                                                                                                                  , Harves Century Group, which has backing from the state-owned China Development Bank, is headquartered in Shenyang, China, and is the parent company of multiple U.S.-based Harves affiliates, including Harves Investment Group (HIG), Harves Global Entertainment, and Harves Sports. Harves Century's website says the chairwoman is Jenglan Shao, which is revealed to be Zhang's mother according to Person's 2015 email to Hunter Biden. It is unclear what her background is or whether she is an American citizen, but her name comes up on the Federal Election Commission (FEC) website as a maxed-out donor to Person's failed 2016 campaign against then-Rep. Mick Mulvaney, R-S.C. Zhang also was a maxed-out donor to Person’s campaign. Schwerin and Hunter Biden both donated $2,700.                                                                       , PSAKI WON'T SAY WHETHER HUNTER BIDEN HAS DIVESTED FROM CHINESE PRIVATE EQUITY FIRM                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Person's email went on to say that Zhang is "being groomed to take over his family’s dynasty" and that the trip wasn’t about selling Biden on anything, but more about "grow[ing] that relationship," adding that "there will be plenty of big things that come down the road that we can work on." Person added that Harves was partnering with NBA stars Magic Johnson and LeBron James in 2016 to "host an NBA Global Game in China."                                                                                                                                                                                                                                                                                                                                                                                                                                   , The longtime Biden aide, who traveled with Vice President Biden to 49 of the 50 countries he visited through mid-2014, including China, and was described by then-second lady Jill Biden as "like a son to Joe and me" and someone who "will always be a part of our family," was tapped to be the president of Harves in January 2015, less than six months after he left the White House. According to Linkedin, Person "[h]elped guide the formation of the Harves Group headquartered in Washington DC, serving as the U.S. affiliate of Harves [Century Group]."                                                                                                                                                                                                                                                                                                      , It does not appear that Biden was able to make the China trip during the specific week that Person pitched in the email, but multiple emails reviewed by FOX Business show that Person and Zhang met with Biden and Schwerin in Washington on multiple occasions and emailed back-and-forth coordinating potential Harves-related business deals. In one 2016 email, Biden calls Zhang his "good friend and business colleague." One of the names cc'd on the email was James Bulger, who appeared to help Biden get a Chinese business license for his uncle's telemedicine company a couple of years earlier.                                                                                                                                                                                                                                                            , One of the emails was from Schwerin to Zhang, Biden, Person, an assistant, and Tara Greco, a former director of communications for the union that represents NBA players. The April 2016 email, which was directed at Zhang, said Greco had learned that the Anschutz Entertainment Group (AEG) had a deal with the NBA to "build NBA branded stadiums around China," but said it appeared the project was "stalled" after only two stadiums were built, prompting Schwerin to say, "If Liaoning can get one of these stadiums that would be a big help in your efforts to get more NBA related content in Liaoning." After listing off several questions he had for Zhang, Schwerin concluded the email by saying they could discuss when they met the following week.                                                                                                    , HUNTER BIDEN'S ART DEALER SAID HE WANTED TO BE THE 'LEAD GUY IN CHINA' IN 2015                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , In November 2020, a joint press release announced that Harves was partnering with NBA China, a company that was formed in 2008 to conduct the NBA’s business throughout China and develop NBA-themed entertainment centers. Zhang was quoted in the press release as saying, the centers "furthers our mission to provide best-in-class global entertainment experiences to local populations." In May of this year, the eastern city of Suzhou is expected to open its first experience center. Zhang said, "We hope to grow it into a landmark project in the sports industry."                                                                                                                                                                                                                                                                                          , "As part of the partnership, Harves, plans to open six NBA-themed entertainment centers across China, with the first opening by 2022," the press release said. "These entertainment centers will bring together fans and families to experience the excitement of the NBA through a variety of new activities and offerings, including cutting-edge, interactive digital games, NBA-themed dining and more."                                                                                                                                                                                                                                                                                                                                                                                                                                                               , In addition to being the co-founder and CEO of Harves Global Entertainment, Person is the co-founder and CEO of DreamCube Innovations, a company that Fast Company described as an "enticing new technology and brand that’s already signed deals with the NBA as well as with the Manchester United soccer club" that is set up "across China."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Los Angeles Lakers' LeBron James in action during a match against Brooklyn Nets at the NBA China Games 2019 in Shenzhen in south China's Guangdong province on Saturday, Oct. 12, 2019 (Color China Photo via AP) (Color China Photo via AP)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , "It’s humbling to work with incredibly creative, talented, and passionate people to push technology and immersive experiences to another level," Person wrote on his Facebook, sharing the Fast Company article. "We’re living through tough times, but our future is lined with infinite possibilities."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , FOX Business reached out to Person and Zhang to inquire about the relationship between Harves and the Chinese government and whether they have played a role in approving any of their business contracts along with a series of other questions, but neither of them responded. In Person's 2015 email to Hunter Biden, he revealed that Zhang’s father-in-law was the governor of Hainan at the time. A timeline shows that Liu Cigui was the governor in 2015 and according to The Diplomat, Cigui was considered to be a "Xi loyalist."                                                                                                                                                                                                                                                                                                                                , Cigui went straight to public service at the age of 20 going "through various levels of Chinese Communist Party (CCP) organs in Fujian, first via the Communist Youth League and then as spatial party secretaries, eventually of prefecture-level Putian, a coastal city of 2 million along the Xiamen-Quanzhou-Putian-Fuzhou coastal axis," The Diplomat reported. According to China Vitae, Cigui has been a member of the CCP Central Committee, which is the party’s "highest organ of authority," since 2012. Additionally, Liu was a member of the Central Commission for Discipline Inspection from 2012 to 2017, which, according to The Washington Post, is "a secretive, powerful agency in charge of investigating the Communist Party’s own members for corruption," was "the main weapon in Xi Jinping’s rapid consolidation of power as China’s new leader.", President Biden hugs his wife Jill Biden and children Hunter and Ashley Biden after he is sworn in as the 46th president of the United States, Jan. 20, 2021, at the U.S. Capitol in Washington. (Caroline Brehman/Pool Photo via AP)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Another tie that Zhang has to the CCP was revealed in a December 2013 Foreign Agents Registration Act (FARA) filing with the Justice Department, listing Zhang as the "Foreign Principal."                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , "Although the Foreign Principal is a private individual, because of his relationship with a Chinese Government Official, Liu Guoqiang, a Vice Chairman Liaoning Committee of the Chinese People's Political Conservative [sic] Conference (CPPCC) People's Republic of China, the foreign principal proposes to seek assistance from the Registrant [Patton Boggs LLP] to provide Congressional outreach on behalf of the Vice Chairman in relation to setting up meetings with Congressional officials, when the Vice Chairman and his delegation visit the United States which is expected to occur in 2014," the filing reads.                                                                                                                                                                                                                                          , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , According to the U.S.-China Economic and Security Review Commission, the CPPCC is a "critical coordinating body that brings together representatives of China’s other interest groups and is led by a member of China’s highest-level decision-making authority, the CCP’s Politburo Standing Committee." The Diplomat reports that the CPPCC is a "key part" of China’s "United Front" work and that it is "designed to liaise with non-Communist Party members – and ultimately see them work with the CCP to advance its interests" and target prominent figures like athletes, businesspeople, and politicians.                                                                                                                                                                                                                                                        , Hunter Biden's attorney and Schwerin did not respond to a series of questions or say whether Hunter still had a stake in Harves. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/biden-says-russian-move-across/story.aspx?guid={5FB16200-391B-4AB9-9CEC-4BE154576674}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-21 00:57:38 </td>
   <td style="text-align:left;"> Biden says Russian move across Ukraine border would be 'invasion,' walking back 'minor incursion' comment - MarketWatch </td>
   <td style="text-align:left;"> President Joe Biden on Thursday made an effort to walk back a much-criticized comment that he made the prior day about Russian President Vladimir Putin potentially launching a "minor incursion" targeting Ukraine. "If any assembled Russian units move across the Ukrainian border, that is an invasion," Biden said Thursday ahead of a meeting on infrastructure. "If Putin makes this choice, Russia will pay a heavy price." During a news conference on Wednesday, Biden made a comment that could be interpreted as giving Putin permission to make a minor incursion into Ukraine., One year in, the Biden administration remains unable to articulate a coherent China policy.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Victor Reklaitis is MarketWatch's Money &amp; Politics reporter and is based in Washington, D.C. Prior to joining MarketWatch, he served as an assistant editor and reporter at Investor's Business Daily. Before IBD, he worked for several newspapers in Virginia. Follow Victor on Twitter at: @vicrek. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/20/tudor-portfolio-manager-on-where-shes-finding-alpha-in-the-tech-sector-with-rising-rates.html </td>
   <td style="text-align:left;"> 2022-01-21 00:56:42 </td>
   <td style="text-align:left;"> Tudor portfolio manager on where she's finding alpha in the tech sector with rising rates </td>
   <td style="text-align:left;"> , (Click here to subscribe to the new Delivering Alpha newsletter.)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , With the prospect of higher interest rates looming, 2022 has already been a tough year for the tech sector. The Invesco QQQ ETF has fallen sharply year-to-date but one tech investor is braving the turbulence.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Ulrike Hoffmann-Burchardi recently launched a new strategy within Tudor Investment Corp. called T++ with a specific focus on technology stocks. She sat down with Delivering Alpha to discuss her current hedging strategy along with where she's finding alpha in the technology sector.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , (The below has been edited for length and clarity. See above for full video.)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Leslie Picker: What's it like being a tech investor right now, given this whole regime change that's really gone on in the market?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Ulrike Hoffmann-Burchardi: We have this exciting step of a next generation of digital transformation, one that is fueled by data. We predict that data is going to grow more than 100 times over the next 10 years. And this gives rise to tremendous investing opportunities in data infrastructure, in semiconductors, but also in digital and data-first businesses. So lots to be excited about. And then to the second part of your question, what is going on right now? It's less to do with the prospects of these new technologies but the fact that we have come up with unprecedented levels of fiscal and monetary stimulus. And that has led to inflationary pressures in our economy that now the Fed seeks to rein in with higher rates.                                                                                                                        , And so with that backdrop, everything else being equal, this means low equity valuations. So we are discounting future cash flows with higher discount rates. But I think one thing that's important to recognize is that this tide of fiscal and monetary stimulus has lifted all boats, not just technology. And it's interesting to see what is still floating when this tide recedes. And here's who I still see standing: those companies with stronger secular tailwinds, the best business models, and world class leadership. And I think it's hard to find another sector that has so much of all of these. So maybe another way to put it is that the Fed can change the discount rate, but not a digital inflection of our economy.                                                                                                                                 , Picker: As you see these valuations come down pretty sharply, at least in the near term, does that concern you? Are you seeing that as more of a buying opportunity?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Hoffmann-Burchardi: If you actually look at these sharp asset price corrections that we have seen, you can look at them and try to invert what these different asset classes price in, in terms of future rate hikes. And so if you look at high-growth software in particular, this now prices in a one percent increase in the 10-year rate, whereas if you look at the Dow Jones, it is still at a zero percent rate hike. So it does look like there's at least some diversity of risk being priced in. And it sounds like right now, maybe the sharp corrections in high-growth software have, at least in the short term, more to do with positioning and flows than actual fundamentals.                                                                                                                                                                                , Picker: Paul Tudor Jones of your firm recently said that the things that have performed the best since March 2020, are probably going to perform the worst as we go through this tightening cycle. By and large, that's been high-growth technology where you spend the most of your time and look into these areas. So do you agree with that? And does that kind of concern you on the long side?                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Hoffmann-Burchardi: We have to prepare ourselves for an environment with higher rates. And as you mentioned, those stocks that have cash flows that are further out into the future are more vulnerable than the ones with near-term cash flows. So with that backdrop, you have to adjust your playbook. And I do think in technology and equity investing in particular, there are still opportunities to make profitable investments in individual companies. Even if valuations are coming down, if companies outperform their growth rates, they can offset that multiple compression. And there's particular companies that are indexed to the amount of data growth. It's not that data is going to stop growing, just because the Fed stops growing its balance sheet.                                                                                                 , And then secondly, as I just alluded to, there could be tactical opportunities when certain asset classes overreact in the short term. And then lastly, the data also shows that it's actually sharp increases in rates that are more harmful to equities than higher rates overall. So now that we are pricing in four rate hikes this year, at least the pace of increases in interest rates should start to slow down for the rest of the year. So I would summarize that there's still two opportunities to deliver Alpha: one is stock selection and then the second one is technically adjusting your hedges when things over or underreact in the short term.                                                                                                                                                                                                           , Picker: So given that backdrop that you described, what does that mean about whether technology is currently sitting at its fundamental basis? And does that give you more confidence to be a buyer in this market?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Hoffmann-Burchardi: As fundamental investors with a long term horizon our first premise is to stay invested in the companies that we believe are going to be the winners of this age of data and digital. So it's all about hedging. And, you know, hedge funds tend to get a bad rap because they're so short term-focused. But in fact, hedging can allow you to have staying power in your investments for the long term. And so in this environment, if you want to hedge out the duration risk of your cash flows, the easiest way is to offset your long term investments with maybe a basket of stocks that have similar duration of cash flows.                                                                                                                                                                                                                        , However, having said that, I think the risk reward of hedging these high-growth names with other high-growth names probably has come down considerably, given that we have seen one of the largest and most furious corrections in high-growth software over the last 20 years. So it's more about then tactically adjusting your hedges, if you believe that certain assets may have overshot in this environment when others have not appropriately reacted.                                                                                                                                                                                                                                                                                                                                                                                                                 , Picker: What sectors are you interested in on the longer side and what sectors on the short side?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Hoffmann-Burchardi: On our long term thesis on data and digital, which we're still very early in this new era of transformation, there are really two sectors that are very interesting. One is data infrastructure, and the other one is semiconductors. And, you know, in a sense, this is very much the picks and shovels strategy of the digital age, very much like in the Gold Rush of the 1840s. And it's all about software and hardware to translate data into insights. And so for semiconductors, which is a very interesting industry, they're the digital engine room of our economy, the digital economy, and it has an industry structure that is very benign, actually has gotten better over the years. Actually, the number of publicly traded semiconductor companies has come down over the last 10 years.                                                 , And the barriers to entry in semiconductors have increased across the whole value chain. But even the design of a chip, if you go from 10 nanometers to five nanometers, it has increased by three times. So very benign competitive framework against an end demand that is now accelerating. Even if you look at, for instance, the automotive industry, they are going to see semi content increasing by more than five times over the next 10 years. And then on the data infrastructure side, it's also very interesting. It's a very nascent market. Only about 10% of software is currently data infrastructure software. And as companies have to deal with new and large amounts of varied data, they will have to overhaul the data infrastructure. And it's incredibly sticky. It's like building a foundation of a house. Very difficult to rip out once installed., Picker: And how about on the short side? How do you see the best way to hedge what's going on right now  in the market?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Hoffmann-Burchardi: I think it's more hedging the risk of higher interest rates as opposed to hedge out fundamentals. And so it's just about matching cash flow duration patterns. But again, I think at this point, we're probably overdone on some of the growth software sell-off. And it's more about going into hedges that now help you price in maybe an overall slowdown on the index level, much more so than in those particular areas of technology.                                                                                                                                                                                                                                                                                                                                                                                                                , Picker: Interesting, so hedging indexes, perhaps just as a way to protect the downside of the longer bets that you're doing.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Hoffmann-Burchardi: Yeah, at least in the short term. Where we have seen most of the carnage in some pockets of the markets, but others have not really reacted to this higher rate environment.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-01-21 00:56:21 </td>
   <td style="text-align:left;"> European Equities Rebound to Close Mostly Higher </td>
   <td style="text-align:left;"> Most European stock indexes bounced back in afternoon trading on Thursday, with Frankfurt's DAX 30 adding 0.6% at 15,902 and markets in Paris, Milan and Madrid gaining between 0.3% and 0.5%. Investors welcomed upbeat earnings reports, while concerns over rising inflation and a quicker pace of interest rate hikes in 2022 continued to weigh on sentiment. German sportswear maker Puma rose 1.2% after posting stronger-than-expected preliminary quarterly sales and core profit. Deliveroo jumped 2.5% after saying the gross value of orders on its platform rose 36% year-on-year in the fourth quarter, while Unilever fell 0.5% after abandoning plans to buy GlaxoSmithKline's consumer healthcare business. On the economic data front, German producer price inflation jumped to an all-time high of 24.2% in December on higher energy cost. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/brent-crude-oil </td>
   <td style="text-align:left;"> 2022-01-21 00:51:18 </td>
   <td style="text-align:left;"> Brent Crude Breaks Above $89 </td>
   <td style="text-align:left;"> Brent crude futures extended gains for the fifth straight session to around $89 per barrel on Thursday, hovering at seven-year highs, supported by ongoing supply concerns and prospects of strong demand. The International Energy Agency (IEA) on Wednesday said that OPEC+ produced about 800,000 barrels per day (bpd) below its production targets in December, and that the oil market could be in a significant surplus in the first quarter of this year. In addition, heightened geopolitical tensions following an attack by Yemen's Houthis on the United Arab Emirates have also provided some support. On the data front, both the API and EIA reports showed US crude stocks unexpectedly rose last week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-01-21 00:48:04 </td>
   <td style="text-align:left;"> UK Stocks Slightly Lower </td>
   <td style="text-align:left;"> The FTSE 100 closed 0.1% lower at 7,579 on Thursday, as investors continued to worry about high inflation, slow growth, and rising interest rates. GlaxoSmithKline was among the worst performers after Unilever effectively abandoned its plans to buy the consumer healthcare business. Meanwhile, Primark owner Associated British Foods also dragged down the index after it said the spread of the Omicron coronavirus variant dented shopper numbers in December even though it reported post-Christmas trading up 36% from the previous year and its operating profit margin was ahead of its expectations. On the other hand, food delivery company Deliveroo climbed on strong quarterly order value growth. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-01-21 00:48:00 </td>
   <td style="text-align:left;"> Italian Shares Rebound on Thursday </td>
   <td style="text-align:left;"> The FTSE MIB Index closed 0.7% higher at 27,570 on Thursday, rebounding from a 0.4% decline in the previous session, as gains in the utilities and healthcare sectors offset lingering concerns of inflation. Enel closed 2.8% higher, as investors bet that the Italian government shall pass a bill securing up to EUR 10 billion to subsidize the distribution and storing of natural gas to relief households of soaring utility bills. A2a (2.2%) and Hera (1.7%) also advanced. Healthcare shares gained 1.5%, led by pharmaceutical DiaSorin (1.3%) and biotech Amplifon (1.6%). Meanwhile, Telecom Italia rebounded 3.3%, after falling over 9% this week, after reports stated the telecom’s boardroom were pleased with the preliminary strategies of spinning off the firm’s assets, despite lowering the odds of the EUR 33 billion takeover by KKR &amp; Co. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-01-21 00:47:12 </td>
   <td style="text-align:left;"> The DAX Index increased 0.51% </td>
   <td style="text-align:left;"> Germany Stock Market went up by 81 points. The rise was driven by HelloFresh (5.49%), Merck (2.55%) and RWE (2.15%). Biggest losses came from Covestro (-3.37%), Continental (-2.08%) and Daimler (-1.91%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/crude-oil </td>
   <td style="text-align:left;"> 2022-01-21 00:46:00 </td>
   <td style="text-align:left;"> WTI Crude Extends Gains for 5th Day </td>
   <td style="text-align:left;"> WTI crude futures extended gains for the fifth straight session to above $87.5 per barrel on Thursday, hovering at seven-year highs, supported by ongoing supply concerns and prospects of strong demand. The International Energy Agency (IEA) on Wednesday said that OPEC+ produced about 800,000 barrels per day (bpd) below its production targets in December, and that the oil market could be in a significant surplus in the first quarter of this year. In addition, heightened geopolitical tensions following an attack by Yemen's Houthis on the United Arab Emirates have also provided some support. On the data front, both the API and EIA reports showed US crude stocks unexpectedly rose last week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/20/record-ipo-rush-of-2021-led-to-historically-dismal-returns-for-investors-with-no-relief-in-sight.html </td>
   <td style="text-align:left;"> 2022-01-21 00:36:02 </td>
   <td style="text-align:left;"> Record IPO rush of 2021 led to historically dismal returns for investors with no relief in sight </td>
   <td style="text-align:left;"> , IPO investors in a record-breaking issuance rush in 2021 have so far been disappointed by dismal returns, and the outlook for the once-booming market is only getting worse with rising rates and insider selling on the horizon.                                                                    , Last year, the number of U.S. traditional IPOs climbed to the highest levels since the late 1990s and deal value hit record levels, according to Dealogic. So far performance from these public debuts has been lagging their historical average significantly.                                      , 2021 deals have fallen 14% on average in the six-month post-IPO period, compared to a historical average of a 14% gain, according to Bank of America.                                                                                                                                                , "High IPO supply, the anticipation of higher Fed Funds rates, a historically extreme proportion of early-stage/non-earning companies, plus perhaps some investor fatigue around learning so many new companies took a toll," Thomas Thornton, a managing director at Bank of America, said in a note., Amid expectations for higher interest rates and a return of volatility, the market swiftly rotated away from risky, growth-oriented companies, especially hurting small-cap IPOs and those that have a long roadmap to profitability.                                                                , Electric pickup maker Rivian Automotive was one of the biggest IPOs of 2021 with its market cap briefly topping traditional automakers like Ford and General Motors. However, the stock has wiped out all the post-debut pop, trading about 12% below its IPO price.                                 , "I think there's no doubt that the IPO market will slow down this year," said Ulrike Hoffmann-Burchardi, portfolio manager at Tudor Investment Corp. "We have seen, especially in software, which is probably 90% of the tech IPO pipeline, now a drastic reset in valuations."                      , Tech stocks are seen as sensitive to rising yields because increased debt costs can hinder their growth and can make their future cash flows appear less valuable.                                                                                                                                   , "We have to see rates stabilize," Hoffmann-Burchardi said. "When the volatility and interest rate move is that large, it's going to be very hard for valuations to find and recalibrate itself."                                                                                                     , Meanwhile, many IPOs done in the second half of 2021 will experience lockup expiration sometime in the next six months. An IPO lock-up period is typically 180 days where company insiders can't sell their shares.                                                                                  , — CNBC's Leslie Picker contributed reporting.                                                                                                                                                                                                                                                        , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                               , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                               , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                     , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                     , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                   , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/01/20/antony-blinken-vladimir-putin-russia-ukraine-tension-ctw-intl-vpx.cnn </td>
   <td style="text-align:left;"> 2022-01-21 00:19:56 </td>
   <td style="text-align:left;"> Hear Blinken lay out case for why world should care about Ukraine - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/crude-oil-stocks-change </td>
   <td style="text-align:left;"> 2022-01-21 00:06:00 </td>
   <td style="text-align:left;"> US Crude Inventories Unexpectedly Rise: EIA </td>
   <td style="text-align:left;"> US crude oil inventories increased by 0.515 million barrels in the week ending January 14th, the first increase since November and compared to market forecasts of a 0.938 million drop, data from the EIA Petroleum Status Report showed. Meanwhile, gasoline inventories rose by 5.873 million barrels, more than an expected 2.634 million increase. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/malta/inflation-cpi </td>
   <td style="text-align:left;"> 2022-01-21 00:03:34 </td>
   <td style="text-align:left;"> Malta Inflation Rate at 9-Year High </td>
   <td style="text-align:left;"> Malta’s annual inflation rate rose to 2.6 percent in December of 2021 from 2.4 percent in the previous month. Although closing the year as the EU member state with the lowest inflation rate, December's reading was the highest reading since 2012, as prices accelerated for food and non-alcoholic beverages (4.9 percent vs 4 percent in November), restaurants and hotels (3.6 percent vs 3.2 percent), and furnishing and household maintenance (2 percent vs 1.7 percent). On the other hand, prices rose at a steady rate for recreation and culture (at 5.1 percent), while inflation slowed for housing and utilities (2.5 percent vs 2.7 percent) and clothing and footwear (0.4 percent vs 1.8 percent). On a monthly basis, consumer prices remained unchanged, following a 2.4 percent decrease in the prior month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/varney-biden-bold-face-failing-year </td>
   <td style="text-align:left;"> 2022-01-21 00:00:21 </td>
   <td style="text-align:left;"> Varney: Biden tried to put a bold face on a year of failure </td>
   <td style="text-align:left;"> FOX Business' Stuart Varney blasts Biden’s first-year failures and argues the Democrats ‘rejected’ the Build Back Better agenda.                                                                                                                                                                                 , FOX Business' Stuart Varney, during his latest "My Take" on "Varney &amp; Co.," argued Biden attempted to put on a "bold face" for his long list of failures during his first year in office, from inflation to his Build Back Better agenda.BIDEN'S FIRST YEAR: TRACKING THE US ECONOMY'S RECOVERY FROM THE PANDEMIC, STUART VARNEY: I’m going to sum up the president's news conference like this:                                                                                                                                                                                                                                    , I'm making 'enormous progress,' I'm not going to change course. The Republicans block everything.                                                                                                                                                                                                                , I'd call that combative defiance in the face of grim reality.                                                                                                                                                                                                                                                    , What is this ‘enormous progress?' Those were his words.                                                                                                                                                                                                                                                          , Joe Biden speaks to a crowd at the Atlanta University Center Consortium on January 11, 2022 in Atlanta, Georgia.  ( Megan Varner/Getty Images / Getty Images)                                                                                                                                                    , Inflation: 1.6% when he took office – 7% now. I see no progress.                                                                                                                                                                                                                                                 , The border: 200,000 a month coming across, way up – no progress there.                                                                                                                                                                                                                                           , COVID: The president said 'I think we've done remarkably well!'                                                                                                                                                                                                                                                  , What? We're firing the unvaxxed because they won't get a jab that doesn't work and we might get testing kits, just as the omicron surge passes.                                                                                                                                                                  , On every issue, he tried to put a bold face on a year of failure.                                                                                                                                                                                                                                                , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                      , So where does he want to take the country in his second year? What's next?                                                                                                                                                                                                                                       , More of the same.                                                                                                                                                                                                                                                                                                , He's not pivoting. No change of course.                                                                                                                                                                                                                                                                          , He's still pushing Build Back Better. He's still trying to cripple energy companies, and when he blamed Republicans for blocking everything, he lost touch with reality.                                                                                                                                         , It was Democrats who killed voting reform. It was Democrats who rejected Build Back Better. It’s the division in his own party that helped mess up his first year!                                                                                                                                               , However, there's one thing he can claim as a win: he lasted two hours without looking frail or losing focus, and that’s a good thing when Kamala Harris is waiting in the wings.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/currency </td>
   <td style="text-align:left;"> 2022-01-20 23:58:55 </td>
   <td style="text-align:left;"> Canadian Dollar at Near 10-Week High </td>
   <td style="text-align:left;"> The Canadian dollar traded near 1.245, the highest since November 9th, amid higher oil prices and after consumer prices data showed that inflation rose to a 30-year high in December, strengthening the appeal for higher rates from the BoC. Despite the increasing number of Covid-19 cases slowing the economic activity growth, investors are betting that the BoC will raise the rates already in its next monetary policy meeting, with a 70% chance already priced. Canada’s headline inflation rate accelerated to 4.8% in December of 2021 from 4.7% in November and October, matching market expectations. That was the steepest inflation rate since September of 1991, amid ongoing supply disruptions and low base year effects. Also, and more important for the BoC decision, the core measure excluding energy prices rose to 3.8%, accelerating from the 3.3% increase in November. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60065207?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-20 23:56:51 </td>
   <td style="text-align:left;"> Bankers told to return to desks as restrictions end </td>
   <td style="text-align:left;"> Big banks, advertising firms and insurers have announced plans to return to the office after the government scrapped its work-from-home guidance for England with immediate effect.                                                                          , However, most said flexible working arrangements would remain in place.                                                                                                                                                                                      , Some have questioned whether the move is premature and could worsen already-high staff absences.                                                                                                                                                             , But others said city centres hit hard by Omicron would get a much needed boost as commuters returned.                                                                                                                                                        , Banking group HSBC said its staff started returning to the office on Thursday, while Standard Chartered has asked employees to come in from Monday - although both lenders have flexible working arrangements in place.                                      , Citigroup and Goldman Sachs also plan to resume office working.                                                                                                                                                                                              , Meanwhile Havas, a French advertising agency with 11,500 staff worldwide, told the BBC it would "fully reopen" its London office from Monday after more than a month of employees working from home.                                                         , Latest figures suggest that 37% of working UK adults did at least some work from home in 2020, up from 27% the previous year.                                                                                                                                , The government introduced its Plan B restrictions in December to battle the Omicron variant, but on Wednesday eased them saying infections had peaked nationally.                                                                                            , Along with the end of working-from guidance, the requirement in England for mandatory face coverings in public places and Covid passports will both be ditched from next Thursday.                                                                           , Chris Hirst, global head of creative at Havas, told the BBC's Today programme: "Many of our employees really do want to come back into the office, but there are some people who are nervous and we don't have a one-size-fits-all approach to that.         , "We'll be talking to those people individually and finding solutions that work for them."                                                                                                                                                                    , Insurance firm Zurich, which employs 4,500 in the UK, said it was "excited" to welcome staff back to its offices but most would continue on a hybrid basis.                                                                                                  , "We had a flexible working policy prior to the pandemic, but [Covid] meant suddenly everybody was experiencing the benefits and some of the downfalls and we've learnt a lot," chief operating officer John Keppel told the BBC's Wake up to Money programme., Alex, 28, says he can't wait for people at his law firm to go back to the office in the next month.                                                                                                                                                          , He joined the company in November, when it was working on a hybrid basis, but virtually all staff have been working from home since mid December.                                                                                                            , "I'm a new joiner and just getting started," he told the BBC. "But it's been really difficult to learn about the company culture, make new connections and make an impression."                                                                              , However, he does appreciate the flexibility of being able to work from home, and supports his firm's goal of moving to a 60:40 split between office and home working.                                                                                        , "Working from home can be more productive. Although now people have got used to doing it full time, I think some will be loath to give it up."                                                                                                               , Network Rail said the number of people using its stations between 6:00 and 10.30 GMT on Thursday was up 10% compared with the same period last week.                                                                                                         , But the statistics show daily passenger numbers had been increasing even before the guidance to work from home in England was lifted yesterday afternoon.                                                                                                    , Thursday's figure was just 1% higher compared with Wednesday.                                                                                                                                                                                                , Business groups have broadly welcomed the easing of Plan B restrictions in England, with the CBI calling for "greater consistency in how we live with the virus in the longer term".                                                                         , Lord Stuart Rose, chairman of Asda and former boss of Marks and Spencer and Argos, hailed the decision to scrap the guidance.                                                                                                                                , "I cannot believe we have a nation sitting at home now cowered by this government, because they are fearful of this virus," he said.                                                                                                                         , "It is something we have to now live with."                                                                                                                                                                                                                  , According to the Times newspaper, the government has asked civil servants to go back to their desks as an example to other employers.                                                                                                                        , But some have questioned the safety of the move at time when the NHS remains under pressure.                                                                                                                                                                 , The British Chambers of Commerce also urged the government to improve access to rapid testing so firms could bring staff back to workplaces with confidence.                                                                                                 , "With infection rates still high, many firms are experiencing significant staff absences and will be cautious about teams rushing back to the office when that could result in further absences," BCC director general Shevaun Haviland said.                , "Maintenance of testing capacity must also be a priority for government, with reports still reaching us of firms unable to access rapid testing at times when they need it."                                                                                 , Unions also said employers had to ensure a safe return to work, and provide flexible working when staff wanted it.                                                                                                                                           , The TUC called for a better sick pay offer from government amid concerns that many workers will be infected and have to take time off on statutory sick pay.                                                                                                 , Others, however, said the change in guidance was overdue for city centre retailers, which rely on commuter trade that has dried up over the last few months.                                                                                                 , On Thursday, the City Pub Group, which has 46 sites, said it expected "consumer confidence and consequently demand" to grow once office workers return to work.                                                                                              , And the Gym Group said demand was returning after a slow December, and would "show further improvement" due to the end of work from home guidance.                                                                                                           , Matthew Fell, the CBI's chief policy director said: "Blanket work-from-home guidance has had significant downsides for city centre trade in sectors such as hospitality and retail."                                                                         , According to BBC research in September, most people do not believe workers will return to the office full-time after the coronavirus pandemic.                                                                                                               , A total of 70% of 1,684 people polled predicted that workers would "never return to offices at the same rate".                                                                                                                                               , Go behind the scenes at London's Corinthia Hotel                                                                                                                                                                                                             , Hidden Assets: A gritty Irish crime thriller on BBC iPlayer                                                                                                                                                                                                  , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/20/business/economy/inflation-questions-consumers.html </td>
   <td style="text-align:left;"> 2022-01-20 23:42:48 </td>
   <td style="text-align:left;"> Your Inflation Questions, Answered  - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , The New York Times asked readers to send questions about inflation. Economists at the Federal Reserve, the White House and Wall Street weighed in.                                                                                                                                                                                                                                                                                                                                                                                                                                          , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , By Jeanna Smialek                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Inflation is high and has been for months. It's weighing on consumer confidence, making policymakers nervous and threatening to eat away at household paychecks well into 2022.                                                                                                                                                                                                                                                                                                                                                                                                             , This is the first time many adults have experienced meaningful inflation: Price gains had been largely quiescent since the late 1980s. When the Consumer Price Index climbed 7 percent in the year through December, it was the fastest pace since 1982.                                                                                                                                                                                                                                                                                                                                    , Naturally, people have questions about what this will mean for their pocketbooks, their finances and their economic futures.                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Closely intertwined with price worries are concerns about interest rates: The Federal Reserve is poised to raise borrowing costs to try to slow down demand and keep the situation under control.                                                                                                                                                                                                                                                                                                                                                                                           , To bring some clarity to a complicated situation, we collected more than 600 reader questions, narrowed them down to a handful that reflected common themes, and asked top economists and experts — from the White House, the Federal Reserve, Wall Street, academia and financial advisory firms — to weigh in. Here is what they had to say.                                                                                                                                                                                                                                              , What would cause prices to keep increasing vs. staying at their current level? Why wouldn’t competition keep prices in check? — Nick Altmann, Chicago                                                                                                                                                                                                                                                                                                                                                                                                                                       , Prices have been rising for two basic reasons: Consumers are buying a lot of goods and services, and supply is limited.                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Consumer demand is the easier part of that equation to explain. Households saved money during long months of lockdown in 2020, often helped by repeated government stimulus checks and other payments. Some saw their wealth further buoyed by a rising stock market and soaring home prices. Now, jobs are plentiful and wages are rising, further shoring up many families’ finances. People have money, and they want to spend it on services and, more than usual, on goods like furniture and camping gear.                                                                            , That rapid consumption is running up against constrained supply. Factories shut down early in the pandemic, and in parts of Asia, they continue to do so as Omicron cases surge. There aren’t enough containers to ship all of the goods people want to buy, and ports have become clogged trying to process so many imports.                                                                                                                                                                                                                                                               , As companies have struggled to get their hands on enough goods to go around, many have raised prices, in many cases to cover their own climbing costs. Some, noticing that they and their competitors were able to charge more without crushing consumer demand, have tested how far they can push up prices — expanding their profits.                                                                                                                                                                                                                                                     , In theory, competition should eat away at extra earnings over time. New firms should jump into the market to sell that same products for less and steal away the customer. Existing competitors should ramp up production to meet demand.                                                                                                                                                                                                                                                                                                                                                   , But this may be a unappealing time for new firms to enter the market. Established companies may be hesitant to expand production if doing so involved a lot of investment, because it is not clear how long today’s strong demand will last.                                                                                                                                                                                                                                                                                                                                                , “It is a very uncertain environment,” said Matthew Luzzetti, chief U.S. economist at Deutsche Bank. “A new firm stepping in is a lot of investment, with a lot of financial risk.”                                                                                                                                                                                                                                                                                                                                                                                                          , Until companies can produce and transport enough of a given product to go around — as long as shortages remain — companies will be able to raise prices without running much risk of losing customers to a competitor.                                                                                                                                                                                                                                                                                                                                                                      , In past periods of inflation, do employers typically increase wages or award higher-than-average yearly increases to help employees offset inflation? If so, in what industries is this practice most common? — Annmarie Kutz, Erie, Pa.                                                                                                                                                                                                                                                                                                                                                    , There is no standard historical experience with wages and inflation, Mary C. Daly, president of the Federal Reserve Bank of San Francisco, said during an interview with The New York Times on Twitter Spaces last week.                                                                                                                                                                                                                                                                                                                                                                    , Wages did increase sharply alongside inflation in the 1970s and 1980s, but in the decades since, pay has struggled to keep pace with price increases. Factors like unionization, worker bargaining power and the state of the labor market all affect whether companies pay more. Those can vary quite a bit by sector. For instance, lower-wage service industries have been competing mightily for workers in recent months, and pay is climbing faster there.                                                                                                                            , “The history isn’t so clear that cost of living translates into higher wages, but that’s largely because inflation has been low and stable for a very long time,” Ms. Daly said.                                                                                                                                                                                                                                                                                                                                                                                                            , Is inflation a valid reason for asking for a raise (or a larger raise than I would otherwise receive)? In addition to other merits (work performance, role change, etc.), does my reduced purchasing power due to inflation give me ground to stand on when negotiating my new salary? — Deirdre Kennedy, St Paul, Minn.                                                                                                                                                                                                                                                                    , Several economists and advisers agreed: Higher prices can be a valid reason to ask for a raise.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , “Absolutely sit down with your boss and say, ‘I’m a great performer, I do this work, I want to stay with the company but it’s been harder and harder to make ends meet and I would like to talk about some compensation to make that easier,’” Ms. Daly said last week.                                                                                                                                                                                                                                                                                                                     , I’m 55 and on track to have put aside enough for a modest but workable retirement in 10-15 years. How much less might my savings and investments be worth in the face of current trends? I’m concerned I won’t have enough time to bounce back if it gets really bad and that higher prices will eat up my resources long before I die. — Jon Willow, Interlochen, Mich.                                                                                                                                                                                                                    , There’s good news here: Hardly any economists or policymakers expect today’s inflation to last. Fed officials in December projected that price gains will drop back below 3 percent by the end of the year, and will level off to normal levels over the longer term.                                                                                                                                                                                                                                                                                                                       , That’s a reason to avoid reacting too swiftly, advisers said. But if you do worry inflation will last, there are a few ways to assess how it might affect your savings, said Christine Benz, Morningstar’s director of personal finance.                                                                                                                                                                                                                                                                                                                                                    , What is inflation? Inflation is a loss of purchasing power over time, meaning your dollar will not go as far tomorrow as it did today. It is typically expressed as the annual change in prices for everyday goods and services such as food, furniture, apparel, transportation costs and toys.                                                                                                                                                                                                                                                                                            , What causes inflation? It can be the result of rising consumer demand. But inflation can also rise and fall based on developments that have little to do with economic conditions, such as limited oil production and supply chain problems.                                                                                                                                                                                                                                                                                                                                                , Where is inflation headed? Officials say they do not yet see evidence that rapid inflation is turning into a permanent feature of the economic landscape, even as prices rise very quickly. There are plenty of reasons to believe the price burst will fade, but some concerning signs suggest it could last.                                                                                                                                                                                                                                                                              , Is inflation bad? It depends on the circumstances. Fast price increases spell trouble, but moderate price gains could also lead to higher wages and job growth.                                                                                                                                                                                                                                                                                                                                                                                                                             , How does inflation affect the poor? Inflation can be especially hard to shoulder for poor households because they spend a bigger chunk of their budgets on necessities — food, housing and especially gas.                                                                                                                                                                                                                                                                                                                                                                                  , Can inflation affect the stock market? Rapid inflation typically spells trouble for stocks. Financial assets in general have historically fared badly during inflation booms, while tangible assets like houses have held their value better.                                                                                                                                                                                                                                                                                                                                               , She recommended that investors take a look at their sources of income. Social Security and many government pensions are adjusted for inflation, so those should keep pace with price gains. Bonds that pay back fixed rates do less well during periods of inflation, while stock investments — though riskier — tend to rise more quickly than consumer prices. Ms. Benz recommends holding assets across an array of securities, potentially including inflation-protected securities such as some exchange-traded funds or Treasury Inflation Protected Securities, commonly called TIPS., “It argues against having too much in cash,” Ms. Benz said. “That’s too much dead money.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , We currently have low unemployment, strong wage growth (largely through attrition / voluntary retirements), easy monetary policy and now rising inflation. What are other periods of time when the United States had these conditions? How did things work out then? — Harshal Patel, Moorestown, N.J.                                                                                                                                                                                                                                                                                      , Jared Bernstein, a member of the White House Council of Economic Advisers, pointed to the post-World War II period as a reference point for the present moment.                                                                                                                                                                                                                                                                                                                                                                                                                             , “Demand was strong, and supply was constrained,” he said in an interview. “That’s a very instructive path for us.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , The good news about that example is that supply eventually caught up, and prices came down without spurring any greater crisis.                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Other, more worried commentators have drawn parallels between now and the 1970s, when the Fed was slow to raise rates as unemployment fell and prices rose — and inflation jumped out of control. But many economists have argued that important differences separate that period from this one: Workers were more heavily unionized and may have had more bargaining power to push for higher wages back then, and the Fed was slow to react for years on end. This time, it’s already gearing up to respond.                                                                              , Why are price controls thought to be a highly disfavored response to inflation? — Jim Moher, San Leandro, Calif.                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , In the 1970s, former President Richard Nixon tried wage and price controls — which put a cap on how much pay can rise — to control inflation. The freezes worked for a time, but prices rocketed up when they were lifted, and they got a bad rap among economists. That reputation has haunted them ever since. We asked experts about price controls in a recent article, and vocal minority think the 1970s experience unfairly tarnished the idea and that it might be worthwhile to reopen the debate.                                                                                 , “This is a great suppressed topic,” said James K. Galbraith, an economist at the University of Texas. “It was absolutely mainstream from the start of World War II until the Reagan administration.”                                                                                                                                                                                                                                                                                                                                                                                        , If inflation is being caused by supply chain problems, how will raising interest rates help? — Larry Harris, Ventura, Calif.                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Kristin J. Forbes, an economist at the Massachusetts Institute of Technology, said that a big part of today’s inflation ties to roiled supply chains, which monetary policy can’t do much to fix.                                                                                                                                                                                                                                                                                                                                                                                           , But trade is actually happening at elevated levels even amid the disruptions. Factories are producing, ships are shipping, and consumers are buying at a rapid clip. It is just that supply is not keeping up with that booming demand. Higher interest rates can relieve pressure on demand, making it more expensive to buy a boat or a car, cooling off the housing market and slowing business investment.                                                                                                                                                                              , “A good part of the supply chain problems, you can’t do anything about,” Ms. Forbes said. “But you can affect demand. And it is the combination of the two which determines inflation.”                                                                                                                                                                                                                                                                                                                                                                                                     ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/people-fleeing-california-for-idaho-record-tax-relief-investments </td>
   <td style="text-align:left;"> 2022-01-20 23:41:37 </td>
   <td style="text-align:left;"> People 'fleeing' California for record tax relief, investments in Idaho </td>
   <td style="text-align:left;"> Idaho Gov. Brad Little on the state's jobs recovery and Democratic voters fleeing blue states.                                                                                                                                                                          , Gov. Brad Little joined "Varney &amp; Co." Thursday to tout the "incredible, organic growth" that has propelled Idaho’s economy as the country grapples with the unanticipated economic disruptions from the COVID-19 pandemic.                                             , The Republican governor tells FOX Business that the state’s "record tax relief and investments" has boosted Idaho’s popularity among businesses and those relocating to the state, notably from Washington, California and Oregon.                                      , There are new businesses "moving in" and "expanding," Gov. Little told host Stuart Varney.                                                                                                                                                                              , CALIFORNIA WEIGHING PROPOSAL THAT COULD DOUBLE ITS TAXES                                                                                                                                                                                                                , Black and tan horse on an Idaho farm with a wooden barn (iStock / iStock)                                                                                                                                                                                               , The GOP governor attributed the surging success to the expanding business landscape. He acknowledged the blossoming partnership between employers and employees, as well as new opportunities within the tech space that are available.                                 , "Idaho was an agrarian state with agriculture, mining and the timber industry, and now we’re a high-tech state," Gov. Little said.                                                                                                                                      , WHICH STATES HAVE THE HIGHEST, LOWEST TAX BURDEN?                                                                                                                                                                                                                       , Idaho, like many other states, experienced low economic volume due to uncertainties related to the pandemic. Despite the turbulent past few years, though, the state saw a 12 percent job increase - smashing its pre-pandemic lows, according to Gov. Little.          , Idaho’s current economic standing isn’t the only upside attracting new residents. It’s also known to be the least regulated in the nation, an eye-popping perk for businesses.                                                                                          , A West Coast exodus from high-tax states is fueling Idaho's real estate industry. FOX Business' Connell McShane with more.                                                                                                                                              , "We've embedded in our state agencies and with the help of the legislature, a process to where we call it zero-based regulation and on a rolling basis: three, four or five years. We bring all the rules up and say, ‘do we need any of those?’" Gov. Little explained., The uptick in growth is generating positive buzz around the state. GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                          , However, the idea of Democratic politics following Idaho’s newest residents may pose as an unforeseen challenge for the Gem State.                                                                                                                                      , "They always want us to change a little something here, a little something there. You know, it [Idaho] was pretty good when you got here," Gov. Little told Varney. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/croatia/unemployment-rate </td>
   <td style="text-align:left;"> 2022-01-20 23:28:04 </td>
   <td style="text-align:left;"> Croatia Jobless Rate Falls to 7.4% in December </td>
   <td style="text-align:left;"> The unemployment rate fell to 7.4 percent in December of 2021 from 9.5 percent in the corresponding month of the previous year, amid the ongoing labor market recovery. The number of unemployed slumped 21.4 percent to 125.7 thousand people, while the number of employed edged 3 percent higher to 1,572 million people. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/home-sales-hit-16-year-high </td>
   <td style="text-align:left;"> 2022-01-20 23:27:34 </td>
   <td style="text-align:left;"> Home sales hit 16-year high </td>
   <td style="text-align:left;"> Douglas Elliman chairman discusses how the Fed could impact real estate investment on 'The Claman Countdown.'                                                                                                                                                                                                                                             , The housing market hasn't been this hot since 2006.                                                                                                                                                                                                                                                                                                       , Sales of existing homes rose 8.5% in 2021, totaling 6.12 million, the National Association of Realtors reported. This as inventory levels fell to an all-time low of 910,000.                                                                                                                                                                             , JOBLESS CLAIMS SURPRISINGLY JUMP                                                                                                                                                                                                                                                                                                                          , House hunters have enjoyed near-record low mortgage rates as they look to trade up or become first-time homebuyers. The fixed rate for a 30-year mortgage has ticked up to 3.56% from 2.77% a year ago but remains attractive. The average loan size of a mortgage hit a new record last week of $418,500, according to the Mortgage Bankers Association. , HOUSING EXEC WARNS OF 'SUPER STORM'                                                                                                                                                                                                                                                                                                                       , Although sales in December cooled, falling 4.6% to 6.18 million, the market remains tight with 30% of sales driven by first-time homebuyers.                                                                                                                                                                                                              , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                   , "December saw sales retreat, but the pullback was more a sign of supply constraints than an indication of a weakened demand for housing," said Lawrence Yun, NAR's chief economist.                                                                                                                                                                       ,  Las Vegas +32.4%                                                                                                                                                                                                                                                                                                                                         ,  Austin +28.8%                                                                                                                                                                                                                                                                                                                                            ,  Tampa +25.4%                                                                                                                                                                                                                                                                                                                                             , Source: NAR/December 2021                                                                                                                                                                                                                                                                                                                                 , The average sales price for all homes was $358,000 in December, up nearly 16% from the same period a year ago, the 118th straight month of year-over-year increases, the longest-running streak on record, NAR stated.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/existing-home-sales </td>
   <td style="text-align:left;"> 2022-01-20 23:08:00 </td>
   <td style="text-align:left;"> US Existing Home Sales Fall in December </td>
   <td style="text-align:left;"> Existing-home sales in the US fell 4.6% to a seasonally adjusted annual rate of 6.18 million in December of 2021, the lowest in 4 months and below market forecasts of 6.44 million mostly due to low inventory. Each of the four major US regions witnessed sales fall in the last month of 2021. Total housing inventory fell 18% to 910K units and the median existing-home price for all housing types was $358,000, up 15.8% from last year. Considering full 2021 however, sales increased 8.5% to 6.12 million, the highest since 2006. "December saw sales retreat, but the pullback was more a sign of supply constraints than an indication of a weakened demand for housing. This year, consumers should prepare to endure some increases in mortgage rates. I also expect home prices to grow more moderately by 3% to 5% in 2022, and then similarly in 2023 as more supply reaches the market", said Lawrence Yun, NAR's chief economist. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/retail/retail-expert-warns-rise-in-crime-could-catalyze-the-next-recession </td>
   <td style="text-align:left;"> 2022-01-20 22:57:52 </td>
   <td style="text-align:left;"> Retail expert warns rise in crime could 'catalyze the next recession' </td>
   <td style="text-align:left;"> Strategic Resource Group managing director Burt Flickinger argues the consumer will be compromised by 'higher retail prices and massive out of stocks' due to a rise in thefts.                                                                                                                                                                               , Strategic Resource Group managing director Burt Flickinger warned on Thursday that rising retail crime "is going to compromise the supply chain, crush the economy and catalyze the next recession."                                                                                                                                                          , Flickinger argued on "Mornings with Maria" on Thursday that thefts lead to "higher retail prices and massive out of stocks, which compromise the consumer and the economy concomitantly."                                                                                                                                                                     , He made the comments in response to railroad company Union Pacific (UP) saying it has experienced a 160% increase in criminal rail theft in Los Angeles County over the past year. The company estimates more than 90 packages are compromised per day.                                                                                                       , "In several months during that period, the increase from the previous year surpassed 200%. In October 2021 alone, the increase was 356% over compared to October 2020," UP's state director of public affairs, Adrian Guerrero, noted.                                                                                                                        , The thefts amounted to more than $5 million in damages to UP alone, which does not include damages to customers or consumers.                                                                                                                                                                                                                                 , Los Angeles photojournalist John Schreiber shared footage of train tracks belonging to UP in the Lincoln Heights neighborhood of Los Angeles and described "looted packages as far as the eye can see," including "Amazon packages, UPS boxes, unused COVID tests, fishing lures, epi pens," he said in a tweet last Thursday.                                , Also plaguing the retail sector, the surge in smash-and-grab robberies that have been on the rise throughout the United States in recent months and years.                                                                                                                                                                                                    , SMASH-AND-GRAB CRIME WAVE DISRUPTING RETAIL AHEAD OF BUSY SHOPPING SEASON                                                                                                                                                                                                                                                                                     , More than half of retailers nationwide, 57%, said that there has been more organized retail crime since the pandemic began, according to a survey conducted last year by the National Retail Federation.                                                                                                                                                      , On Thursday, Flickinger also weighed in on rising oil prices and its added impact on the retail sector.                                                                                                                                                                                                                                                       , "Higher oil prices are already affecting consumer confidence and spending," he told host Maria Bartiromo, noting that the University of Michigan’s Index of Consumer Sentiment posted a 2.5% loss this month compared to the month before, falling to 68.8, the second-lowest level in a decade.                                                              , On Thursday, benchmark U.S. crude lost 28 cents, dropping to $86.68 per barrel in electronic trading on the New York Mercantile Exchange, but is still up by more than 60% from the same time last year.                                                                                                                                                      , Kickz Inc. owner Danny Ryan shares why he closed his store amid the surging crime waves in San Jose on 'Fox Business Tonight.'                                                                                                                                                                                                                                , Goldman Sachs is now forecasting oil prices will rise above $100 per barrel later this year, signaling higher gas prices are on the horizon, Reuters reported.                                                                                                                                                                                                , "Consumers are cutting back because of inflation," Flickinger argued. "They’re having trouble feeding their families, getting gas and paying their rent, so rising prices are really going to affect the economy [and] affect retail."                                                                                                                        , He then warned that retailers have been forced to "pass along inflation" to consumers and that rising prices are "really going to put a rain cloud over the economy for the foreseeable future."                                                                                                                                                              , Flickinger provided the insight one week after it was revealed inflation rose at the fastest pace in nearly four decades in December, as rapid price gains fueled consumer fears about the economy.                                                                                                                                                           , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                   , The consumer price index rose 7% in December from a year ago, according to a new Labor Department report released Wednesday, marking the fastest increase since June 1982, when inflation hit 7.1%. The CPI – which measures a bevy of goods ranging from gasoline and health care to groceries and rents – jumped 0.5% in the one-month period from November., Economists expected the index to show that prices surged 7% in December from the year-ago period and 0.4% from the previous month.                                                                                                                                                                                                                            , Strategic Resource Group managing director Burt Flickinger argues crime 'is going to compromise the supply chain, crush the economy and catalyze the next recession because it also catalyzes higher retail prices and massive out of stocks.'                                                                                                                , Price increases were widespread. Although energy prices fell 1.1% in December from the previous month, they're still up 29.3% from last year. Gasoline, on average, costs 49.6% more than it did last year. Food prices have also climbed 6.3% higher over the year.                                                                                          , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                       , FOX Business’ Megan Henney, Paul Best and Audrey Conklin contributed to this report. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-01-20 22:54:28 </td>
   <td style="text-align:left;"> Canada Stocks Rebound </td>
   <td style="text-align:left;"> The S&amp;P/TSX Composite index was 0.4% higher at the 21,300 level on Thursday, rebounding from last session’s 0.3% loss, as tech and healthcare stocks offset the declines in the energy sector while investors anticipate an interest rate hike from the Bank of Canada in its meeting next week. Despite eased bond yields in North America, Scotiabank said on a note to its investors that it expects the BoC to raise its key overnight rate by 25bps to 0.5% on January 26th. On the corporate front, tech shares jumped 2.1%, led by Shopify (3.6%) and Descartes Systems (3%), while healthcare stocks rose 1.2% on the back of cannabis growers. Further gains were capped by losses in the energy sector, pressured by lower oil and gas prices. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/baltic </td>
   <td style="text-align:left;"> 2022-01-20 22:52:00 </td>
   <td style="text-align:left;"> Baltic Exchange Dry Index Falls for 10th Day </td>
   <td style="text-align:left;"> The Baltic Exchange Dry Index slipped 6.1% to 1,474 on Thursday, its lowest since February 2021, extending losses for a tenth straight session, amid weaker seasonal demand across all vessel segments. "Big ships are still suffering from the typical January dip after a very brutal start to the year. Also, the lack of coal exports from Indonesia continued to impact the market in the week to January 20.", shipbroker Fearnleys said. The capesize index, which tracks iron ore and coal cargos of 150,000-tonnes, plunged 15.9% to 1,031, its lowest since February last year; and the panamax index which tracks cargoes of about 60,000 to 70,000 tonnes of coal and grains, declined 3.4%, to its lowest since April at 2,024. Among smaller vessels, the supramax index shed 39 points to 1,773. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2022-01-20 22:40:00 </td>
   <td style="text-align:left;"> Natural Gas Falls to 2-Week Low </td>
   <td style="text-align:left;"> US natural gas futures declined to below $3.9 per million British thermal units, the lowest in two weeks dragged down by expectations of lower heating demand amid forecasts for less cold over the next two weeks. Still, US gas demand will likely hit a record high on Friday due to colder than normal weather this week. On the production side, daily output on Thursday was on track to drop to 92.4 bcfd, the lowest in since September as wells remained frozen in Texas and other producing states, according to preliminary data from Refinitiv. At the same time, demand for US LNG continues to be strong as utilities around the world scramble for LNG cargoes to replenish low stockpiles in Europe and meet surging demand in Asia. Meanwhile, the latest storage report showed US utilities pulled 206 billion cubic feet of gas from storage during the week ended January 14th, compared with a decline of 179 bcf in the same week last year and a five-year average decline of 167 bcf. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-01-20 22:35:00 </td>
   <td style="text-align:left;"> US Stocks Rebound, Nasdaq Up 2% </td>
   <td style="text-align:left;"> US stocks rebounded on Thursday, with the Dow Jones adding more than 400 points, the S&amp;P 500 rising more than 1%, and the Nasdaq surging 2%. Treasury yields retreated for a second day from recent 2-year highs and traders shifted their focus to corporate results. Earnings from Travelers Companies and American Airlines topped estimates while United Airlines lowered its 2022 growth forecast due to the spread of the omicron variant. Netflix and PPG Industries are due to report today after the closing bell. Meanwhile, initial claims were the highest in 3 months while the Philly Fed manufacturing index came better-than-expected sending mixed signals about economic recovery. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/unp:us </td>
   <td style="text-align:left;"> 2022-01-20 22:33:40 </td>
   <td style="text-align:left;"> Union Pacific earnings above expectations at 2.66 USD </td>
   <td style="text-align:left;"> Union Pacific (UNP) released earnings per share at 2.66 USD, compared to market expectations of 2.62 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/20/business/media/robert-costa-cbs.html </td>
   <td style="text-align:left;"> 2022-01-20 21:45:56 </td>
   <td style="text-align:left;"> Robert Costa, a Noted Political Reporter, Is Joining CBS News - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                         , Supported by                                                                                                                                                                                                                                                                                                                                                                                          , The longtime Washington Post political reporter will take an on-air role covering campaigns and elections.                                                                                                                                                                                                                                                                                            , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                               , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                        , By Michael M. Grynbaum                                                                                                                                                                                                                                                                                                                                                                                , Robert Costa, the high-profile political reporter, is leaving his longtime home at The Washington Post to become a full-time television journalist at CBS News, where he will serve as the network’s chief election and campaign correspondent.                                                                                                                                                       , The move, announced on Thursday, is notable as much for Mr. Costa’s stature as a sought-after chronicler of national politics as it is for his decision to depart one of the more prominent roles in print journalism. Mr. Costa, 36, gained attention for his congressional coverage at the right-leaning National Review magazine before joining The Post in 2014.                                  , He is also the second well-known correspondent to exit The Post in recent days. David Fahrenthold, a 21-year veteran of the paper and a Pulitzer Prize winner for his investigations into the Trump family’s charitable donations, joined The New York Times this month.                                                                                                                              , Mr. Costa, who wrote the book “Peril” with Bob Woodward last year, has plenty of experience in television news. He served as the moderator of “Washington Week” on PBS from 2017 to 2020, and was a regular presence from 2015 to 2020 on MSNBC and NBC News programs, where he was a political analyst.                                                                                              , “I’ve worked across platforms for much of my career, and I believe it’s a vital time for me to grow as a storyteller, and to build my muscle as a reporter on the television front,” Mr. Costa said in an interview. “That excites me as a new challenge.”                                                                                                                                            , Mr. Costa is a major hire by Neeraj Khemlani, the executive who took charge of CBS News last spring. Mr. Khemlani was an unexpected pick for the role who went to CBS from Hearst, a company best known as a magazine publisher. He has been focused on reimagining a storied news division — the former home of Edward R. Murrow — that has struggled in recent years to compete against ABC and NBC., In the interview, Mr. Costa said he and Mr. Khemlani began discussing a possible role at the network in November. “It started as casual conversations about the future of American democracy and how important the coming years will be,” Mr. Costa said. He said the two men had “built a bond.”                                                                                                     , Mr. Costa said his arrangement with CBS would allow him to continue collaborating on some reporting projects with The Post.                                                                                                                                                                                                                                                                           , “I am lucky to call Sally Buzbee and Fred Ryan friends,” Mr. Costa said, referring to the newspaper’s executive editor and publisher. “These are people I’ve worked closely with, and I appreciate their support for this decision.”                                                                                                                                                                  , CBS News has filled several big roles this year. Mark X. Lima, formerly the network’s West Coast bureau chief, is now the Washington bureau chief. Anthony Galloway, the chief content officer at The Wall Street Journal, is joining CBS to oversee its streaming news programming.                                                                                                                  , There are no plans for Mr. Costa to host his own show. He is expected to appear on news programs across CBS’s broadcast and streaming platforms and play a major role in the network’s coverage of the 2022 midterms and 2024 presidential race.                                                                                                                                                      , Mr. Costa, who grew up in Pennsylvania, interned with the famed TV anchors George Stephanopoulos and Charlie Rose early in his career. He made a name for himself on the national stage with a string of scoops about the 2013 Republican-led shutdown of the federal government, earning a profile in New York magazine that declared him “the golden boy of the government shutdown.”               , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/philadelphia-fed-manufacturing-index </td>
   <td style="text-align:left;"> 2022-01-20 21:43:00 </td>
   <td style="text-align:left;"> Factory Activity in Philadelphia Above Forecasts </td>
   <td style="text-align:left;"> The Philadelphia Fed Manufacturing Index in the US increased to 23.2 in January of 2022 from a 1-year low of 15.4 in December and above market expectations of 20. The survey’s indicators for general activity, shipments, and new orders posted modest increases after falling sharply last month. The employment index remained positive but decreased. The price indexes remained elevated. Responding firms remained generally optimistic about growth over the next six months. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/jobless-claims </td>
   <td style="text-align:left;"> 2022-01-20 21:37:00 </td>
   <td style="text-align:left;"> US Weekly Jobless Claims Hit 3-Month High </td>
   <td style="text-align:left;"> The number of Americans filing new claims for unemployment benefits rose by 55 thousand from the previous period to 286 thousand in the week ending January 15th, the highest level since mid-October and well above market expectations of 220 thousand. It was also the largest weekly increase in claims since mid-July, as a surge in COVID-19 cases driven by the Omicron variant disrupted business activity and as employers continued to have difficulty retaining workers amid record rises in job quits. On a non-seasonally adjusted basis, initial claims slumped by 83 thousand to 337 thousand, with notable decreases being recorded in New York (-14.0 thousand), Missouri (-7.5 thousand) and Texas (-6.1 thousand). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ukraine/interest-rate </td>
   <td style="text-align:left;"> 2022-01-20 21:32:00 </td>
   <td style="text-align:left;"> Ukraine Hikes Key Policy Rate to 10%, Above Expectations </td>
   <td style="text-align:left;"> The National Bank of Ukraine hiked its policy rate by 100bps to 10% during its January 20th meeting, above market expectations of 9.5%, while announcing it expects to further increase the rate to 11% in 2022 before seeing it back below 10% in 2023. The central bank stated that many pro-inflationary risks have materialized and the decline in prices in the end of 2021 were slower than expected, hence tighter monetary policy is needed to ensure steady disinflation toward the target of 5%. Policymakers also noted that increased geopolitical tensions with Russia in the coming months should push prices higher and hamper growth, revising 2022 inflation expectations to 7.7% from 5% and GDP growth projections from 3.8% to 3.4%. Lastly, the NBU will continue to intervene on the foreign exchange market to smooth excessive currency fluctuation but will refrain from daily purchases on the interbank foreign exchange market to replenish reserves. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/live/2022/01/20/business/stock-market-economy-news </td>
   <td style="text-align:left;"> 2022-01-20 21:25:41 </td>
   <td style="text-align:left;"> Stocks sink for a third day as Wall Street’s rebound fades. - The New York Times </td>
   <td style="text-align:left;"> The S&amp;P 500 fell 1.1 percent, after earlier climbing more than 1 percent, while the Nasdaq composite dropped 1.3 percent.                                                                                                                                                                                                                                                                                                                                                                                                                 , Follow our latest coverage of business, markets and economy.                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , By Coral Murphy Marcos                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Data delayed at least 15 minutes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Source: FactSet                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , By: Ella Koeze                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Stocks fell on Thursday, a third-consecutive decline for Wall Street, with the tech-heavy Nasdaq composite sinking deeper into a correction after a rally faded late in the day.                                                                                                                                                                                                                                                                                                                                                          , The S&amp;P 500 fell 1.1 percent, after earlier climbing more than 1 percent, while the Nasdaq composite dropped 1.3 percent. Both benchmarks are on track for a third week of losses, with the S&amp;P 500 on track for its worst week in more than a year.                                                                                                                                                                                                                                                                                      , The market’s recent slump has come as investors parse signals from the Federal Reserve that interest rate increases are coming in 2022. The central bank is seeking to cool down inflation, with consumer prices increasing at the fastest pace in 40 years.                                                                                                                                                                                                                                                                              , A closely watched measure of investor expectations, the yield on 10-year Treasury notes, climbed as high as 1.88 percent on Tuesday, its highest level since January 2020, before falling back to 1.83 percent on Thursday, which is still sharply higher than it was at the start of the year. The Fed has been telegraphing its plans to remove support for the economy since late last year, but Wall Street’s view on how quickly and aggressively that will happen has shifted this month, weighing on stocks.                       , “We’re talking about markets that have become very accustomed to extensive support from central banks and very gentle unwinding when appropriate,” Craig Erlam, senior market analyst at OANDA, wrote in a note to clients on Wednesday. “This is quite a shock to the system. And so far earnings season is not providing investors the comfort they were hoping for.”                                                                                                                                                                   , Investor sentiment has also been hurt lately by earnings reports that have fallen short of expectations. On Thursday, American Airlines reported a $931 million loss in the final three months of last year, when the Omicron variant of the coronavirus forced airline workers to call in sick at record rates and problems caused by winter storms contributed to cancellations during the holiday season. The airline’s shares closed more than 3 percent lower.                                                                       , Banks have also come under pressure in recent days, as major lenders including Citigroup, Goldman Sachs and JPMorgan Chase reported lower profits for the fourth quarter. Shares of all three fell this week.                                                                                                                                                                                                                                                                                                                             , Consumer-facing companies like Procter &amp; Gamble and Bed Bath &amp; Beyond have also said they are facing supply chain disruptions and higher labor and freight costs. Procter &amp; Gamble announced on Wednesday that consumers should expect more price increases in 2022. Investors are questioning how much longer companies will be able to pass on these costs to their consumers as inflationary pressures persist.                                                                                                                        , But, broadly speaking, technology stocks have served as a key measure of changing investor attitudes toward stocks this month. The Nasdaq composite ended Wednesday down more than 10 percent from its November record, a decline that’s called a correction on Wall Street and serves as a marker of sorts of a shift in sentiment.                                                                                                                                                                                                      , The retreat is attributed, in part, to the expectation that interest rates will climb —  something that could prompt investors to rethink how much risk they’re willing to take, especially with tech stocks.                                                                                                                                                                                                                                                                                                                             , “What people are paying for these companies right now are the expectations that there will be strong cash flow in the future,” said Anu Gaggar, global investment strategist for Commonwealth Financial Network. “But when you discount these expectations at much higher interest rates, that lowers the current value.”                                                                                                                                                                                                                 , The drop follows a big rally for tech stocks: In 2021, the Nasdaq composite rose 21.4 percent, its third-consecutive year of double-digit gains. In those three years, the index climbed 136 percent, with some of the largest technology companies, like Apple and Amazon, soaring to astronomical values.                                                                                                                                                                                                                               , The index has been trading below its record since November, but the obvious shift in investor sentiment toward tech stocks came this month, with the index down 9.5 percent since the start of the year.                                                                                                                                                                                                                                                                                                                                  , The S&amp;P 500 hasn’t fallen quite as far. It is down 6.5 percent from its high, which it reached on Jan. 3. That was after a gain of nearly 27 percent for 2021.                                                                                                                                                                                                                                                                                                                                                                            , By Michael M. Grynbaum                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , The Fox News host Sean Hannity had some blunt advice for President Donald J. Trump on Jan. 7, 2021: “No more stolen election talk.”                                                                                                                                                                                                                                                                                                                                                                                                       , His guidance did not take. But documents disclosed on Thursday showed in vivid detail just how closely Mr. Hannity had worked with White House aides in a fervent, if brief, effort to persuade Mr. Trump to abandon his false claims about voter fraud after the Jan. 6 attack on the Capitol.                                                                                                                                                                                                                                           , One day after the attack, Mr. Hannity sent a text message to Kayleigh McEnany, then the White House press secretary, describing a five-point plan for approaching conversations with the president, according to documents released by the House committee investigating the Jan. 6 riot.                                                                                                                                                                                                                                                 , After urging Ms. McEnany to avoid discussion of a “stolen election,” Mr. Hannity proffered another talking point to use with Mr. Trump: “Yes, impeachment and 25th amendment are real, and many people will quit …”                                                                                                                                                                                                                                                                                                                       , Mr. Hannity appeared to be referring to the possibilities that Mr. Trump could be impeached, face mass resignations from his staff or be temporarily removed from office by a group of his cabinet secretaries invoking the 25th Amendment.                                                                                                                                                                                                                                                                                               , Ms. McEnany replied: “Love that. Thank you. That is the playbook. I will help reinforce.”                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Fox News, where Ms. McEnany is now a commentator and a co-host of a weekday program, declined to comment on Thursday.                                                                                                                                                                                                                                                                                                                                                                                                                     , In public, Mr. Hannity and Ms. McEnany remain lock-step supporters of Mr. Trump and his worldview. But their private exchanges show the level of alarm among even the president’s closest allies after the Jan. 6 riot, as Mr. Trump persisted in his false claims that the election had been stolen from him and his political future appeared deeply precarious.                                                                                                                                                                        , The exchanges were included in a letter sent by the House committee to Ivanka Trump, Mr. Trump’s daughter and one of his senior advisers. The committee is seeking Ms. Trump’s cooperation as it tries to piece together a scramble inside the White House to persuade Mr. Trump to denounce the attackers at the Capitol.                                                                                                                                                                                                                , In another exchange included in the letter, Mr. Hannity urged Ms. McEnany to keep the president away from certain advisers. “Key now. No more crazy people,” Mr. Hannity wrote. Ms. McEnany replied: “Yes 100%.”                                                                                                                                                                                                                                                                                                                          , This month, the House committee asked Mr. Hannity to cooperate and answer questions about his communications with Mr. Trump and his aides in the days surrounding the riot. At the time, the committee disclosed messages in which Mr. Hannity advised Mark Meadows, then the White House chief of staff, on the president’s political future. “He can’t mention the election again. Ever,” Mr. Hannity wrote on Jan. 10, 2021, to Mr. Meadows and Representative Jim Jordan, an Ohio Republican.                                         , A lawyer for Mr. Hannity, Jay Sekulow, has said the committee’s request to interview Mr. Hannity raises “First Amendment concerns regarding freedom of the press.”                                                                                                                                                                                                                                                                                                                                                                        , Luke Broadwater contributed reporting.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , By Lananh Nguyen                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , JPMorgan Chase, coming off a record year for profits, gave its chief executive, Jamie Dimon, a raise of almost 10 percent just days after he said the bank had to spend more to retain top performers.                                                                                                                                                                                                                                                                                                                                    , Mr. Dimon’s 2021 compensation was $34.5 million, the company said in a filing on Thursday. That’s $3 million more than a year earlier, when he received no raise — but did get a midyear bonus in the form of stock options he can exercise in 2026.                                                                                                                                                                                                                                                                                      , For 2021, Mr. Dimon’s pay included a base salary of $1.5 million, a cash bonus of $5 million and $28 million in restricted stock that is linked to company performance, the company said.                                                                                                                                                                                                                                                                                                                                                 , “Under Mr. Dimon’s stewardship, the firm continued to serve its clients and customers around the world during a time of unprecedented business demands,” the bank said in the filing.                                                                                                                                                                                                                                                                                                                                                     , JPMorgan, the country’s largest bank by assets, posted a record $48.3 billion in profit in 2021, according to results announced Friday. It was the first of several banking giants to report blockbuster profits for the year, fueled by a hot market for corporate deal-making and trading activity from volatile financial markets in 2021.                                                                                                                                                                                             , But big profits across Wall Street have also given rise to big payouts to employees. In earnings calls, executives from JPMorgan, Citigroup, Goldman Sachs and Bank of America all cited pressure to increase compensation in a war for talent — part of a trend across the economy as workers get pay bumps from employers struggling to fill positions.                                                                                                                                                                                 , “We want to be very, very competitive on pay,” Mr. Dimon told analysts on a conference call on Friday. “There’s a lot more compensation for top bankers and traders and managers, who I should say, by the way, did an extraordinary job in the last couple years.”                                                                                                                                                                                                                                                                       , By Nicole Sperling                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Netflix added 8.3 million subscribers in the fourth quarter, raising its worldwide subscriber base to 222 million, but the company said on Thursday that it expected growth to slow in the opening months of 2022.                                                                                                                                                                                                                                                                                                                        , That news, in the company’s earnings release, prompted the stock to drop nearly 20 percent in after-hours trading. For the first quarter of this year, Netflix forecast an additional 2.5 million subscribers, down from the four million it added during the same quarter of 2021. That would be one of the streaming giant’s slowest opening quarters in years.                                                                                                                                                                         , The number of subscribers added in the fourth quarter was slightly off the 8.5 million that Netflix had forecast, but the 1.2 million added from the United States and Canada region reflected its strongest quarter there since the beginning of the pandemic. Most of the growth came outside the United States, as has been the case for the last few quarters.                                                                                                                                                                        , Netflix’s co-chief executive Reed Hastings admitted during an investor conference call on Thursday that he was frustrated by the slower growth in subscriptions. “We are staying calm and trying to figure it out,” he said.                                                                                                                                                                                                                                                                                                              , He added: “It could well be Covid effects. It could be we are pushing on a smaller market than we thought. But I’m not sure why.”                                                                                                                                                                                                                                                                                                                                                                                                         , Netflix’s competition has increased significantly in the last few years, with Disney+ and HBO Max making significant strides in streaming. This month, Warner Media announced that HBO Max had exceeded its subscriber estimates, growing to 73.8 million customers by year’s end.                                                                                                                                                                                                                                                        , Yet Mr. Hastings discounted the idea that competition could be driving the slowdown. “There’s more competition than there’s ever been,” he said, “but, you know, we’ve had Hulu and Amazon for 14 years, so it doesn’t feel like any qualitative change there.”                                                                                                                                                                                                                                                                           , Last week, Netflix said it was raising the monthly prices for all of its U.S. subscription plans, with the basic service increasing to $9.99 and the standard plan to $15.49. (The basic plans allows the user to stream on one device in standard resolution, while the standard plan allows for two in high definition.)                                                                                                                                                                                                                , “It’s a bit of an admission that they may be hitting the ceiling for growth in the U.S. and Canada,” said Berna Barshay, an analyst with Empire Financial Research. “For the U.S. and Canada at least, the growth is probably going to come from price and not volume.”                                                                                                                                                                                                                                                                   , The company last raised rates in October 2020, and its subscriber base continued to grow. This time, analysts expect the price increase will result in more cancellations but higher revenue.                                                                                                                                                                                                                                                                                                                                             , “I do think that they have permission to take this price increase,” Ms. Barshay said. “At $15.49 they are only 49 cents above HBO Max. There’s no reason they shouldn’t be the leader. Their quality at the top end is as good as anybody’s, and their quantity just outdoes anybody.”                                                                                                                                                                                                                                                    , Netflix said one reason for its depressed first-quarter forecast was that many new releases were scheduled for the end of the period. It noted that two of its most highly anticipated projects — the second season of “Bridgerton” and “The Adam Project,” a film starring Ryan Reynolds — will debut at the end of the first quarter in March.                                                                                                                                                                                          , The growth in the fourth quarter was fueled by a strong content at the end of 2021. Films like “Red Notice” and “Don’t Look Up” became the most-watched movies in the company’s history, according to Netflix, and returning shows like “Cobra Kai” and “The Witcher” attracted viewers as well. “Squid Game,” which was released near the end of the third quarter, broke through globally in the fourth quarter. Netflix said it had accounted for 1.65 billion hours of viewing time.                                                  , Ted Sarandos, Netflix’s other co-chief executive, was more sanguine about the business.                                                                                                                                                                                                                                                                                                                                                                                                                                                   , “What’s really been great about 2021, even through all those conditions, is we were able to prove two theses that we bet on years ago,” he said. “One big one is around our investment in international programming.”                                                                                                                                                                                                                                                                                                                     , Referring to shows like “Squid Game,” “Call My Agent” and “La Casa de Papel,” he added, “And we were betting that you could take films and series from anywhere in the world and entertain the entire world.”                                                                                                                                                                                                                                                                                                                             , The company made $607 million in profit on $7.7 billion in fourth-quarter sales. Investors had been expecting $379 million in profit and $7.7 billion in revenue, according to S&amp;P Capital IQ.                                                                                                                                                                                                                                                                                                                                            , By Daisuke Wakabayashi and Cade Metz                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Mustafa Suleyman, a pioneer in the field of artificial intelligence, is leaving Google to join the venture capital firm Greylock Partners.                                                                                                                                                                                                                                                                                                                                                                                                , The departure of Mr. Suleyman, who was Google’s vice president of product management and policy for artificial intelligence, closes a tumultuous tenure at the company. He joined Google in 2014 when the search giant acquired DeepMind, a cutting-edge artificial intelligence research lab, in a deal valued at $650 million.                                                                                                                                                                                                          , The deal demonstrated the value of companies that specialized in “deep learning,” a form of artificial intelligence that became more important in the early part of the last decade. In just a few years, DeepMind had hired many of the leading researchers in the field.                                                                                                                                                                                                                                                                , Mr. Suleyman, known to friends and colleagues as Moose, was not an A.I. researcher by training. But he led the company into an important area of research: health care. He also became a key voice in DeepMind’s efforts to ensure that its technologies would not be used for military applications, which led to a clash with Google when the company joined a flagship A.I. project with the Defense Department. (Google eventually pulled out of the project.)                                                                        , While at Google, Mr. Suleyman was stripped of some management responsibilities at DeepMind after the company received complaints that he bullied subordinates. On Thursday, in a question-and-answer session with a Greylock partner, Reid Hoffman, Mr. Suleyman acknowledged the complaints.                                                                                                                                                                                                                                             , “I really screwed up,” he said. “I remain very sorry about the impact that that caused people and the hurt that people felt there.”                                                                                                                                                                                                                                                                                                                                                                                                       , By Sapna Maheshwari                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Amazon, which has posed formidable challenges to booksellers, big-box chains and grocers, has a new kind of retailer in its sights: physical clothing stores.                                                                                                                                                                                                                                                                                                                                                                             , The company said on Thursday that it planned to open a clothing store called Amazon Style this year in Glendale, Calif., at a shopping center called The Americana at Brand. Renderings of Amazon Style shared by the company call to mind a department-store chain like Nordstrom or an off-price chain like T.J. Maxx.                                                                                                                                                                                                                  , Items will range in price from $10 to $400, the company said in an email, and the store will be about 30,000 square feet, which is several times larger than a typical specialty mall store. The shopping complex also has an Amazon 4-Star store and a Nordstrom, along with other clothing chains like Anthropologie, Lululemon and Tory Burch.                                                                                                                                                                                         , Amazon said store customers would be able to use an Amazon Shopping app to send items to a fitting room or the pickup counter. They will also be able to scan an item’s QR code to see additional sizes, colors and customer ratings. Amazon said it planned to provide real-time recommendations to customers as they shopped, incorporating their physical browsing behavior and preferences on the Amazon Shopping app.                                                                                                                , Amazon also said it would have new technology in fitting rooms. Customers will find additional recommendations in fitting rooms once they are ready to try on garments — something that sales associates usually do in most clothing stores. Using technology from Amazon fulfillment centers, shoppers will also be able to request additional styles and recommendations, which will arrive in “minutes,” the company said.                                                                                                             , Thirty-four percent of millennial consumers surveyed by Cowen analysts last year said they had begun with Amazon when shopping for clothing. About 17 percent said they had started their search in multi-line stores like department store chains or warehouse clubs, while 15 percent started on Google. The analysts noted that Generation Z and millennial consumers remained reliant on Amazon last year even as traditional retailers reopened.                                                                                     , The pandemic upended the apparel industry and shopping centers, making Amazon’s move particularly timely. Amazon, which is populated with many private label clothing brands, did not specify the names of labels it plans to carry in the store.                                                                                                                                                                                                                                                                                         , By Jeanna Smialek                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , The Federal Reserve took its first step toward more seriously examining issuing a central bank digital currency, releasing a report on Thursday that examines the idea’s potential costs and benefits and opening the door for public comment.                                                                                                                                                                                                                                                                                            , In a long-awaited report, the Fed avoided taking sides and set out a list of arguments for and against a digital currency, and posed questions that will shape the debate.                                                                                                                                                                                                                                                                                                                                                                , “We look forward to engaging with the public, elected representatives and a broad range of stakeholders as we examine the positives and negatives of a central bank digital currency in the United States,” Jerome H. Powell, the Fed chair, said in a statement. Mr. Powell had previewed that a report would be forthcoming in May 2021.                                                                                                                                                                                                , Central banks from the Bahamas to Sweden and China are experimenting with digital currency offerings, fueling concerns on Capitol Hill that the Fed might fall behind the competition. Breakneck innovation in the private sector has suggested that the Fed, a key financial regulator, needs to understand budding private digital payment technologies.                                                                                                                                                                                , A central bank digital retail currency would, basically, be electronic cash. While consumers already use digital money when swiping a credit card or making online purchases, that money is actually backed by the banking sector. A Fed version would be backed by America’s central bank, just like a U.S. dollar bill.                                                                                                                                                                                                                 , Given the U.S. currency’s dominant position in global finance, the Fed has been clear that it is moving slowly and carefully as it weighs a digital dollar. And officials have emphasized that they would not move forward without congressional approval.                                                                                                                                                                                                                                                                                , “The Federal Reserve does not intend to proceed with issuance of a C.B.D.C. without clear support from the executive branch and from Congress, ideally in the form of a specific authorizing law,” the report noted.                                                                                                                                                                                                                                                                                                                      , Researchers from the central bank outlined how a digital currency could offer benefits and entail risks.                                                                                                                                                                                                                                                                                                                                                                                                                                  , Such a currency “could provide a safe, digital payment option for households and businesses as the payments system continues to evolve, and may result in faster payment options between countries,” the Fed release accompanying the discussion paper stated.                                                                                                                                                                                                                                                                            , But the paper also noted that a central bank digital currency would raise policy questions, including about its effect on the financial sector, the cost and availability of credit, the safety and stability of the financial system and the efficacy of monetary policy.                                                                                                                                                                                                                                                                , The Fed paper also seemed to slam the door on several possibilities — including the idea that a central bank digital currency could be created alongside consumer bank accounts at the Fed, something Democrats and proponents of broader financial inclusion have at times suggested.                                                                                                                                                                                                                                                    , The law behind the Fed “does not authorize direct Federal Reserve accounts for individuals, and such accounts would represent a significant expansion” of the central bank’s role, the paper said, suggesting that such accounts would need to be operated by banks and other service providers.                                                                                                                                                                                                                                          , Commercial banks, for their part, have been worried that the creation of a central bank digital currency and Fed accounts could take away their deposit base and upend their business model. The paper probably does not address all their concerns, but may serve to calm worries that consumers could fully leapfrog the traditional banking system.                                                                                                                                                                                    , The Fed’s paper pointed out that a potential bank currency could be designed in a way that would mitigate disruption to the banking system.                                                                                                                                                                                                                                                                                                                                                                                               , “A C.B.D.C. could spur innovation by banks and other actors and would be a safer deposit substitute than many other products, including stablecoins and other types of nonbank money,” the paper said. “These forms of nonbank money could cause a shift in deposits away from banks even without a C.B.D.C.”                                                                                                                                                                                                                             , The Fed is asking for public comment on more than 20 questions about central bank digital currencies, and is accepting responses for the next 120 days.                                                                                                                                                                                                                                                                                                                                                                                   , By Niraj Chokshi                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , American Airlines lost $931 million in the final three months of last year, as the Omicron variant of the coronavirus has pushed back the industry’s rebound, the company said on Thursday.                                                                                                                                                                                                                                                                                                                                               , After a year of recovery punctuated by setbacks, airlines are now focused on returning to profitability in 2022. Industry executives are hoping for a robust spring and summer driven by rebounds in corporate and international travel.                                                                                                                                                                                                                                                                                                  , “Over the past year, we have experienced periods of high travel demand countered by periods of decreased demand due to new Covid-19 variants,” American’s chief executive, Doug Parker, said in a statement on Thursday. “This volatility has created the most challenging planning environment in the history of commercial aviation.”                                                                                                                                                                                                   , Omicron forced airline workers to call in sick at record rates over the holidays, compounding problems caused by winter storms and contributing to tens of thousands of cancellations during one of the year’s busiest travel periods. But American notably performed better over that period than its peers.                                                                                                                                                                                                                             , Over the two weeks starting on Dec. 25, American canceled just under 1,500 flights, compared with more than 4,300 at Southwest Airlines, more than 2,500 for United Airlines and more than 2,000 for Delta Air Lines. The cancellations represented 4 percent of American’s schedule, versus 9 percent for Southwest, 8 percent for United and 5 percent for Delta.                                                                                                                                                                       , Omicron will continue to weigh on demand in January and February, American said. The airline expects capacity, as measured by seats sold and distance flown, to be about 8 to 10 percent less in the first three months of this year than in the same period in 2019. Revenue is expected to be down 20 to 22 percent.                                                                                                                                                                                                                    , American is more optimistic about the rest of the year, expecting capacity to be down only about 5 percent in 2022 from 2019. The airline also hopes to start turning profits again this year.                                                                                                                                                                                                                                                                                                                                            , The company said domestic and short-distance international travel had nearly recovered to prepandemic levels, while corporate travel within the United States was about 70 percent restored. Long-distance international travel continues to lag behind but is expected to improve as Omicron infections decline and vaccines are distributed abroad.                                                                                                                                                                                     , American said on Thursday that capacity was down about 13 percent in the final three months of last year from the same period in 2019, with revenue down about 17 percent. The company lost nearly $2 billion in 2021, an improvement over its nearly $9 billion loss in 2020; both losses were offset by billions of dollars in federal aid to pay workers. The airline ended last year with about $15.8 billion in cash on hand.                                                                                                        , The airline had spent the pandemic simplifying its fleet, replacing older, expensive planes with newer, more efficient ones. As a result, American’s capital spending in 2022 and 2023 is expected to be about half of what it was in the years leading up to the pandemic, it said.                                                                                                                                                                                                                                                      , The virus isn’t the only recent threat to airlines. After recovering from the holiday mess last week, the industry faced another potentially major disruption this week: an expansion of 5G cellular service that airlines warned could interfere with flight safety devices. The crisis was averted when wireless carriers agreed not to deploy 5G near some airports at the industry’s request.                                                                                                                                         , By Stephen Gandel                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , AT&amp;T and Verizon’s expansion of nationwide 5G service, which was delayed for months because of concerns about airplane safety, kicked off on Wednesday without the travel chaos that airline executives had warned about.                                                                                                                                                                                                                                                                                                                 , A last-minute deal to restrict the high-speed cellular service near airports avoided mass cancellations, and the Federal Aviation Administration expanded the list of planes approved to land in low-visibility conditions at airports where 5G service is deployed, the focus of airlines’ concerns.                                                                                                                                                                                                                                     , But the 5G issues for both airlines and wireless carriers are still far from resolved.                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Radio altimeters, which were developed in the 1920s and help pilots determine a jet’s altitude and its distance from other objects, use frequencies closer to the ones used by American cellular carriers’ 5G services than earlier generations. Aviation experts warned that 5G interference could have rare but catastrophic consequences for air travel, as some planes may not be able to land at airports near 5G towers.                                                                                                            , But the Federal Communications Commission and the wireless carriers largely dismissed those concerns. AT&amp;T and Verizon last year collectively paid more than $80 billion for 5G spectrum licenses.                                                                                                                                                                                                                                                                                                                                        , AT&amp;T and Verizon agreed on Tuesday to temporarily restrict 5G in a two-mile buffer zone around a number of large airports, which degrades speeds for users in those areas. On Thursday, the F.A.A. said it had approved an estimated 78 percent of the U.S. commercial fleet of planes to safely land at airports where 5G is deployed and visibility is limited. It is working to approve more, but said that some combinations of planes and altimeters will probably be unable to land safely at those airports under those conditions., For airlines, the biggest issue is how altimeters interact with automated systems. Boeing 787s, for instance, use altimeters to control when reverse thrusters fire on landing. Last week, the F.A.A. said that it had detected “anomalies” of the 787 that could cause 5G interference to affect automated systems, including “degraded deceleration performance, increased landing distance and runway excursion.”                                                                                                                      , The airline industry has been working on new standards for altimeters, but they are not scheduled to be released for review until October. The most likely solution is to spend hundreds of millions of dollars, or perhaps billions, to fix airplane altimeters and reprogram automatic flight systems.                                                                                                                                                                                                                                  , The big question is who pays: airlines or wireless carriers?                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , “The problem here is because the F.A.A. didn’t have a handle on the extent of the problem until last week, it is going to cost someone a boatload of money,” said Harold Feld, a senior vice president at Public Knowledge, a research and advocacy group that has received funding from AT&amp;T and Verizon.                                                                                                                                                                                                                                , Niraj Chokshi contributed reporting.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , By Melissa Eddy                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , BERLIN — Employees at Tesla’s new assembly plant outside Berlin will elect a works council next month, the latest indication that the factory could soon begin operation after months of setbacks and delays.                                                                                                                                                                                                                                                                                                                             , Elon Musk, Tesla’s chief executive, had hoped the facility, the company’s first assembly plant in Europe, would have been completed by the end of last year. But Germany’s cumbersome bureaucracy, combined with a flurry of lawsuits from local environmental groups, has pushed back the opening by several months.                                                                                                                                                                                                                     , Birgit Dietze, the regional leader for the IG Metall union, which represents autoworkers in Germany, said on Thursday that a vote for 19 representatives to serve on the works council had been scheduled for Feb. 28.                                                                                                                                                                                                                                                                                                                    , Works councils, committees that represent employees in helping to set factory policies, are standard in German companies. Although union members can serve on the councils, the bodies are not organized by or directly affiliated with the unions.                                                                                                                                                                                                                                                                                       , Members of the state government in Brandenburg, which has not yet granted final approval for the $7 billion plant, said earlier this month that all of the necessary paperwork had been received in late December and the process was in its final stages. They also indicated that settlement of a pending lawsuit over water use would not affect the timeline.                                                                                                                                                                         , “We are on what we hope are the last steps as far as the whole issue of permits for the factory,” Jörg Steinbach, Brandenburg’s minister for the economy, said last week. But he declined to speculate exactly when the plant would receive its final approval to begin production.                                                                                                                                                                                                                                                       , IG Metall said it was concerned that the works council vote had been scheduled even though roughly only one in six of the estimated 12,000 people who are expected to work at the plant have been hired so far. Most companies hire managers and engineers first, before filling in the lower ranks of blue-collar workers, who will make up the majority of the workers, said Ms. Dietze. That raises the prospect that a works council vote in February may not represent the work force when full production begins.                   , “With a works council, the work force is given a voice and can bring in and assert its interests,” said Ms. Dietze on Thursday. “In order to play this role, however, it is a prerequisite that a works council actually represents the work force and that’s where it’s important to look closely at Tesla.”                                                                                                                                                                                                                             , Although Tesla has opposed unions at its plants in the United States, Germany has a strong tradition of unionization, and IG Metall recently opened an office near the plant and has been answering questions from workers and those applying for jobs. Ms. Dietze declined to say how many union members were already working at the facility, or whether they were among those running for positions on the works council.                                                                                                              , In Germany, individual workers join unions and if enough of them do so, use their leverage to get employers to agree to a union contract, which is negotiated between workers and management for entire industries.                                                                                                                                                                                                                                                                                                                       , The plant, where Tesla expects to eventually produce 500,000 Model Y sport utility vehicles a year, has begun turning out cars, but they are prototypes that cannot be sold. Pending approval of the final steps, the Brandenburg authorities granted the company the right to produce an additional 2,000 prototypes of its Model Y cars, after Tesla said that its initial run of 250 of the electric vehicles revealed points in the production that needed additional fine-tuning.                                                    , Still, speculation in Germany about a possible opening date has been fueled by reports of the prototypes vehicle, optimism from government officials that a final approval is nearing, and word from Mr. Musk that he would be making his way to Germany.                                                                                                                                                                                                                                                                                 , Earlier this week, Mr. Musk told his followers on social media that he would be headed to Berlin in “mid Feb.”                                                                                                                                                                                                                                                                                                                                                                                                                            , An earlier version of this article mistated the cost of a Tesla plant being built outside of Berlin. It is $7 billion, not $7 million.                                                                                                                                                                                                                                                                                                                                                                                                    , By David W. Chen                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Live from Stamford, Connecticut, it’s the 2022 Beijing Olympics!                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Or so NBC could say about its play-by-play teams for the upcoming Winter Games, following word that all of its sports announcers will call the action from the network’s studios rather than on-site because of concerns about the Omicron variant of the coronavirus and restrictions in place in China for those covering the Olympics.                                                                                                                                                                                                 , The news, first reported by USA Today and confirmed by NBC on Thursday, was not exactly a surprise, since the vast majority of NBC’s announcing teams for sports other than the marquee ones of figure skating and Alpine skiing were already planning to work remotely.                                                                                                                                                                                                                                                                  , ESPN also announced on Thursday that the company will not be sending any news personnel to the Winter Olympics and will instead focus on remote coverage.                                                                                                                                                                                                                                                                                                                                                                                 , Indeed, many other recent major sporting events, including last summer’s Tokyo Games, have featured announcers who are hundreds or even thousands of miles away from the games. Still, the announcements offer the latest reminder of how fluid and unpredictable even the most highly choreographed of events have been in the pandemic era.                                                                                                                                                                                             , Case in point: NBC’s Olympic host, Mike Tirico, will be in Beijing for the Feb. 4 opening ceremony and the first few days of the Winter Games. He will then leave to cover the Feb. 13 Super Bowl outside Los Angeles, and it is unclear whether he will return to Beijing for the closing ceremony on Feb. 20.                                                                                                                                                                                                                           , “We’re going to continue to adjust our plans as the situation warrants,” said Greg Hughes, senior vice president of communications for NBC Sports.                                                                                                                                                                                                                                                                                                                                                                                        , About 250 NBC personnel are already in Beijing to work the games. NBC had also hoped to send a broadcasting crew of less than 10, and a couple of dozen support staff, to cover figure skating, Alpine skiing and snowboarding.                                                                                                                                                                                                                                                                                                           , But now those personnel will join more than 1,000 people who will be working in Stamford, around the clock, to broadcast the games, just as they did during the 2018 Winter Games in Pyeongchang, Korea.                                                                                                                                                                                                                                                                                                                                  , Even in the run-up to the games, the prospect of being in Beijing had worried some prominent athletes. Tara Lipinski, the former Olympic figure skating champion who has become one of NBC’s best-known commentators, told an interviewer that “I would feel very nervous” if she had been an athlete preparing for Beijing because of Covid-19.                                                                                                                                                                                          , “It’s even being worried about getting there, as you mentioned, because I have holed myself up in this house,” Lipinski said. “If I test positive, I can’t go to nationals, I can’t go to the Olympics. But imagine what’s at stake for these athletes that have worked their whole life for this moment.”                                                                                                                                                                                                                                , Employees returning to the office in the midst of the pandemic are bound to arrive with questions. To ease their adjustment, office managers are using mobile apps that offer the answers that workers seek.                                                                                                                                                                                                                                                                                                                              , Building apps are customizable and designed to connect office workers to maintenance, security and logistics systems and community-building programs, Julie Weed reports for The New York Times.                                                                                                                                                                                                                                                                                                                                          , Employees can use the app to enter a building, reserve conference rooms or request maintenance like getting a light bulb changed or a copier unjammed.                                                                                                                                                                                                                                                                                                                                                                                    , Safety information, such as in a building emergency or a natural disaster, can be disseminated quickly.                                                                                                                                                                                                                                                                                                                                                                                                                                   , Building managers can monitor the use of workrooms and other locations.                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , In the pandemic, the apps can also help the office feel safer by communicating building-wide health information and reducing physical interactions. Coronavirus protocols, contact tracing information and emergency alerts can be disseminated via an app.                                                                                                                                                                                                                                                                               , Rosalyn Griffin, an office manager for Rothschild &amp; Company, an investment bank, uses the TranswesternHub app in her office at 77 West Wacker in Chicago for simple tasks like submitting repair orders.                                                                                                                                                                                                                                                                                                                                  , One of her favorite features is calling for the elevator from the app. “You turn the corner and it’s there,” she said. “It’s super easy.”                                                                                                                                                                                                                                                                                                                                                                                                 , But because these apps monitor employee movements in the office, they have raised some concerns over privacy.                                                                                                                                                                                                                                                                                                                                                                                                                             , These apps “take employee surveillance to a new level,” said Lorrie Faith Cranor, an engineering and public policy professor at Carnegie Mellon University and director of the CyLab Usable Privacy and Security Laboratory.                                                                                                                                                                                                                                                                                                              , Companies should be transparent about what information they are tracking, how they are using it, who will have access to it and why, Dr. Cranor said. It’s also important to anonymize the data whenever possible.                                                                                                                                                                                                                                                                                                                        , Millions of Americans are voluntarily leaving their jobs. Much of the turnover has been in hospitality, retail and other lower-wage jobs, but the desire to move on cuts across industries, Tara Siegel Bernard writes for The New York Times.                                                                                                                                                                                                                                                                                            , Here are some things to think about to achieve a graceful exit — without leaving money on the table:                                                                                                                                                                                                                                                                                                                                                                                                                                      , Ask yourself what’s motivating you to leave and what you think you need to thrive.                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Figure out how much it costs you to live.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Be sure to use the money you’ve set aside in your flexible spending accounts and work out how other perks, including bonuses, may be paid out.                                                                                                                                                                                                                                                                                                                                                                                            , It may make sense to book medical appointments before you start over with new health care coverage.                                                                                                                                                                                                                                                                                                                                                                                                                                       , Switching jobs can secure a raise or more rewarding work, but rushing down that road could lead to poor decisions. READ THE FULL ARTICLE →                                                                                                                                                                                                                                                                                                                                                                                                , A booming ecosystem of highly valued, cash-rich start-ups in Silicon Valley and beyond are expanding at breakneck speed and trying to unseat stalwart companies in all kinds of fields. And few in the industry see a limit to the growth, Erin Griffith reports for The New York Times.                                                                                                                                                                                                                                                  , The funding frenzy follows nearly two years of a pandemic when people and businesses increasingly relied on tech, creating bottomless opportunities for start-ups to exploit. There are now more than 900 tech start-ups each worth more than $1 billion. In 2015, 80 seemed like a lot.                                                                                                                                                                                                                                                  , The activity has crossed into even frothier territory in recent months, as tech start-ups offering food delivery, remote-work software and telehealth services realized that they not only would survive the pandemic but were in higher demand than ever. The money hit a fever pitch in the final months of 2021 as investors chased a limited pool of start-ups and as tech stocks like Apple, which topped a valuation of $3 trillion, reached new heights.                                                                           , The big-money headlines have carried into this year. Over a few days this month, three private start-ups hit eye-popping valuations: Miro, a digital whiteboard company, was valued at $17.75 billion; Checkout.com, a payments company, was valued at $40 billion; and OpenSea, a 90-person start-up that lets people buy and sell nonfungible tokens, known as NFTs, was valued at $13.3 billion.                                                                                                                                       , “The pot of gold at the end of the rainbow has become bigger than ever,” said Mike Ghaffary, an investor at Canvas Ventures. “You can invest in a company that could one day be a trillion-dollar company.”                                                                                                                                                                                                                                                                                                                               , There’s more money and more bubbly behavior. Investors insist it’s rational. READ THE ARTICLE →                                                                                                                                                                                                                                                                                                                                                                                                                                           , By John Yoon                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , An American Airlines flight to London from Miami turned around about an hour into its journey on Wednesday night because of a passenger who refused to wear a mask, the airline said.                                                                                                                                                                                                                                                                                                                                                     , Police officers met Flight AAL38 at Miami International Airport when it returned, and escorted a woman in her 40s off the plane, said Lea Gonzalez, a public information officer for the Miami-Dade Police Department. She was not arrested, Ms. Gonzalez said.                                                                                                                                                                                                                                                                           , The Boeing 777, carrying 129 passengers and 14 crew members, was about 500 miles into its 4,400-mile flight when it reversed course off the coast of North Carolina, flight trackers show.                                                                                                                                                                                                                                                                                                                                                , American Airlines said in a statement that the flight had been diverted because of “a disruptive customer refusing to comply with the federal mask requirement.”                                                                                                                                                                                                                                                                                                                                                                          , The episode was another in a long list of midair mask disputes that have erupted during the pandemic.                                                                                                                                                                                                                                                                                                                                                                                                                                     , In October, a passenger was accused of punching an American Airlines flight attendant in her nose, giving her a concussion, after a mask dispute. The airline’s chief executive called the violent encounter on the California-bound flight from New York “one of the worst displays of unruly behavior we’ve ever witnessed.”                                                                                                                                                                                                            , In May, a California woman on a Southwest Airlines flight repeatedly punched a flight attendant, bloodying her face and chipping three teeth, after she was asked to buckle her seatbelt, put up her tray table and “wear her face mask properly.”                                                                                                                                                                                                                                                                                        , Thousands of other episodes involving unruly passengers have taken place in recent years, according to the Federal Aviation Administration. As of Tuesday, the agency said, it had received 151 reports of unruly passengers, 92 related to face masks, since Jan. 1. Last year, it received 5,981 reports of unruly passengers and 4,290 mask-related incidents.                                                                                                                                                                         , Andrés R. Martínez contributed reporting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/20/technology/big-tech-senate-bill.html </td>
   <td style="text-align:left;"> 2022-01-20 21:22:11 </td>
   <td style="text-align:left;"> Will Congress Pass New Regulation on Big Tech? Time May Be Running Out. - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , With midterm elections approaching, a vote taken on Thursday could be the first of several that Congress takes on bills aimed at the industry.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , By Cecilia Kang and David McCabe                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Cecilia Kang and David McCabe cover tech policy from Washington.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Lawmakers on Capitol Hill are readying a major push on bills aimed at restraining the power of the country’s biggest tech companies, as they see the window of opportunity closing quickly ahead of the midterm elections.                                                                                                                                                                                                                                                                                                                                                                                                                        , In a significant step forward, a Senate committee voted on Thursday to advance a bill that would prohibit companies like Amazon, Apple and Google from promoting their own products over those of competitors. Many House lawmakers are pressing a suite of antitrust bills that would make it easier to break up tech giants. And some are making last-ditch efforts to pass bills meant to strengthen privacy, protect children online, curb misinformation, restrain targeted advertising and regulate artificial intelligence and cryptocurrencies.                                                                                           , Most of the proposals before Congress are long shots. President Biden and top Democrats in Congress have said addressing the industry’s power is a high priority, but numerous other issues rank even higher on their list. These include passing voting rights legislation, correcting labor and supply chain constraints, enacting a social services package and steering the nation out of the Covid-19 pandemic.                                                                                                                                                                                                                              , Still, the next few months are probably the last best chance for a while. After that, attention will turn to the midterm elections, and Democrats, who support the efforts aimed at tech in far greater numbers than Republicans, could lose control of Congress.                                                                                                                                                                                                                                                                                                                                                                                 , “This is a problem that has been brewing for a long time, and it’s become pretty obvious to everyone,” said Senator Amy Klobuchar, Democrat of Minnesota, who has led the push for tougher laws on the tech companies. “But when you get to the fall, it will be very difficult to get things done because everything is about the election.”                                                                                                                                                                                                                                                                                                     , Congress has unified around a growing concern about the technology giants over the last several years. Still, dozens of bills have failed to pass, even as many other countries have beefed up their regulations for the industry.                                                                                                                                                                                                                                                                                                                                                                                                                , When Mr. Biden took office last year, he promised to inject more competition into the economy, particularly in the tech sector. He appointed vocal tech critics to lead antitrust agencies, and this month, his press secretary said the president was “encouraged to see bipartisan interest in Congress in passing legislation to address the power of tech platforms through antitrust legislation.”                                                                                                                                                                                                                                           , Bruce Reed, the White House deputy chief of staff, and Brian Deese, the director of the National Economic Council, met on Wednesday with executives from companies including Yelp and Sonos, which have lobbied for antitrust action against the tech giants. They discussed the difficulties that “entrepreneurs, brick-and-mortar retailers, and other businesses face competing in sectors dominated by a few large platforms,” White House officials said. The administration said it anticipated working with Congress, but has not endorsed any of the specific legislation aimed at the companies.                                         , Complicating matters is that even though the two parties widely agree that Congress should do something, they often disagree on what that should be.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , In the past few years, dozens of privacy, speech, security and antitrust bills have withered amid disagreements over how to balance protecting consumers while encouraging the growth of Silicon Valley. Some bills, like those that address online content moderation, are especially polarizing: Democrats have called for measures that would push the companies to remove from their sites more misinformation and content that contributed to real world harm. Republicans have backed laws to force the companies to leave more content up.                                                                                                 , “Everyone has a bone to pick with Big Tech, but when it comes to doing something that’s when bipartisanship falls apart,” said Rebecca Allensworth, a Vanderbilt Law School professor who specializes in antitrust law.                                                                                                                                                                                                                                                                                                                                                                                                                           , “At the end of day, regulation is regulation,” she said, “so you will have a hard time bringing a lot of Republicans on board for a bill viewed as a heavy-handed aggressive takedown through regulation of Big Tech.”                                                                                                                                                                                                                                                                                                                                                                                                                            , The bill that the Senate Judiciary Committee advanced on Thursday, for instance, could prevent Amazon from steering shoppers to its Amazon-branded toilet paper and socks while making it harder to find comparisons for those products from other brands. It could force Apple to allow alternatives to Apple Pay within iPhone apps. And it could prevent Google from putting its own services like travel prices, restaurant reviews and shopping results at the top of search results.                                                                                                                                                        , Introduced by Ms. Klobuchar and Senator Charles E. Grassley, Republican of Iowa, the legislation aims to address concerns that a handful of tech giants act as gatekeepers to digital goods and services. Alphabet, Amazon, Apple, Facebook and Microsoft have a combined market capitalization of more than $9 trillion. Several Republicans voted in favor of the bill, which passed 16 to 6. Though Senator Mike Lee, Republican of Utah, repeated a consistent party talking point of “unintended consequences” to future businesses that could be swept under the law, others said the threats posed by tech giants outweighed those worries., Senator Ted Cruz, Republican of Texas, voted in favor of the bill and emphasized that his greatest concern was how giant social media companies moderated content. He and other Republicans on the committee said they believe companies like Apple, Google and Facebook censored conservative voices by banning apps like Parler, a right-wing site, and by taking down accounts of conservative figures.                                                                                                                                                                                                                                        , “It would provide protections to content providers that are discriminated against for the content they produce,” Mr. Cruz said. “I think that that is a meaningful step forward.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Ms. Klobuchar described the vote as “a historic and important moment,” as the first antitrust bill aimed at tech to advance out of the committee.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , “As dominant digital platforms — some of the biggest companies our world has ever seen — increasingly give preference to their own products and services, we must put policies in place to ensure small businesses and entrepreneurs still have the opportunity to succeed in the digital marketplace,” she said.                                                                                                                                                                                                                                                                                                                                 , But she acknowledged there was much work ahead for her and Mr. Grassley to persuade congressional leadership to support final passage.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Consumer groups and a coalition of dozens of tech start-ups back the bill. Some consumer advocates have compared the legislation to a law that forced monopoly TV providers to offer all networks access to cable customers. That action, they say, did not lead to the demise of the cable television business, but kept monopoly providers from shutting out competition.                                                                                                                                                                                                                                                                       , “Consumers will benefit from this bill by making it easier to install, choose and use alternative apps and online services,” said Sumit Sharma, a senior researcher for tech competition at Consumer Reports, “enabling both consumers and small businesses to more easily switch between ecosystems by mixing and matching services from different providers.”                                                                                                                                                                                                                                                                                   , Silicon Valley lobbyists have fought the bill in published opinion pieces, ad campaigns and one-on-one appeals. Sundar Pichai, the chief executive of Google’s parent company, Alphabet, and Tim Cook, the chief executive of Apple, have called lawmakers to oppose the bill.                                                                                                                                                                                                                                                                                                                                                                    , The companies’ lobbyists have argued that the legislation could make it harder to ward off malware and bugs in devices and could make their services less useful. In a blog post on Tuesday, Google’s chief legal officer, Kent Walker, painted a dire vision of the effects that it and other bills could have: The company may have to stop including a map of vaccination sites in search results if the law passes, he said. It may have to stop blocking spam in Gmail. It may not be able to show someone searching for medical help “clear information” and “instead be required to direct you to a mix of low quality results.”           , The companies have also said the proposals — focused on their bigness — would hurt small businesses. In recent months, Amazon has urged the merchants who sell products through its marketplace to contact lawmakers with concerns about the bills.                                                                                                                                                                                                                                                                                                                                                                                               , Brian Huseman, the company’s vice president of public policy, said in a statement that the legislation could imperil Amazon’s ability to offer Prime shipping benefits to those sellers or allow them onto its platform at all.                                                                                                                                                                                                                                                                                                                                                                                                                   , Ms. Klobuchar’s bill in particular targets a growing business for Amazon: competing directly with those outside merchants by offering its own products, like its Amazon Basics line.                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Amazon argues that many major retailers, like Costco and Walmart, do the same thing. “The bill’s authors are targeting common retail practices and, troublingly, appear to single out Amazon while giving preferential treatment to other large retailers that engage in the same practices,” Mr. Huseman said. Senators Dianne Feinstein and Alex Padilla, two Democrats from California, repeated the companies’ arguments, saying the Silicon Valley giants were being unfairly targeted by a bill that could help rivals in China like TikTok and Tencent.                                                                                    , Ms. Klobuchar said tech companies had lobbed misleading attacks. “They don’t like our bill,” she said. “You can see the ads on TV.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Before Thursday’s session, Ms. Klobuchar and Mr. Grassley proposed changes that they said would address concerns about user privacy and hindering subscription services like Amazon Prime. The new version also appeared likely to cover TikTok.                                                                                                                                                                                                                                                                                                                                                                                                  , Even though Ms. Klobuchar’s bill moved beyond the Judiciary Committee on Thursday, its sponsors face the steeper challenge of getting 60 senators to support it. In the House, advocates of the antitrust bills also need to get enough Republicans on board to account for Democrats who oppose the proposals.                                                                                                                                                                                                                                                                                                                                   , “They’ve talked about the cascade of legislative possibilities,” said William E. Kovacic, a former chair of the Federal Trade Commission. “None of it has happened. And the clock is running.”                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/euro-area/interest-rate </td>
   <td style="text-align:left;"> 2022-01-20 21:16:46 </td>
   <td style="text-align:left;"> Euro Area Inflation Could Stay High for Longer: ECB </td>
   <td style="text-align:left;"> ECB policymakers noted that the recent and projected increase in inflation was largely driven by temporary factors that were expected to ease in 2022 but warned that a “higher for longer” inflation scenario could not be ruled out, accounts from its December 2021 meeting showed. For 2023 and 2024, inflation is projected relatively close to 2% but considering the upside risks, could easily turn out above 2%. At the same time, the central bank reiterated net purchases under the PEPP could be scaled down and discontinued at the end of March but noted that substantial monetary policy support was still needed, thus an interest rate hike this year is highly unlikely. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/brent-crude-oil </td>
   <td style="text-align:left;"> 2022-01-20 21:12:53 </td>
   <td style="text-align:left;"> Brent Crude Halts 4-Day Run </td>
   <td style="text-align:left;"> Brent crude futures fell more than 0.5% to below $87 a barrel on Thursday, pausing a four-day rally that pushed prices to a fresh 7-year high of $89.2 as traders mulled US president Joe Biden’s pledge to continue trying to lower prices and an industry report that pointed to an increase in US crude stockpiles. API numbers showed that US crude inventories increased by 1.4 million barrels and gasoline inventories rose by 3.46 million barrels last week. Oil has rallied around 30% since the end of November as strong demand and supply constraints significantly tightened the market. Goldman Sachs is forecasting a return to $100 crude in the 3rd quarter, and the IEA said in a report on Wednesday that demand is on track to hit pre-pandemic levels. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/20/stocks-making-the-biggest-moves-premarket-travelers-american-airlines-signet-jewelers-and-more.html </td>
   <td style="text-align:left;"> 2022-01-20 21:05:17 </td>
   <td style="text-align:left;"> Stocks making the biggest moves premarket: Travelers, American Airlines, Signet Jewelers and more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                              , Check out the companies making headlines before the bell:                                                                                                                                                                                                                                                                                                    , Travelers (TRV) – The insurance company reported a quarterly profit of $5.20 per share, well above the $3.86 consensus estimate, with revenue also beating analyst forecasts. Travelers benefited from stronger results in investment income and underwriting, and its stock added 2.5% in the premarket.                                                    , American Airlines (AAL) – American gained 1.3% in premarket trading after it reported a quarterly loss of $1.42 per share, 6 cents narrower than anticipated. The airline also reported better-than-expected revenue as American's results were helped by strong holiday demand.                                                                             , Signet Jewelers (SIG) – The jewelry retailer saw its stock surge 5.9% in the premarket after it said total holiday season sales rose 30.4% and same-store sales jumped 25.2%.                                                                                                                                                                                , United Airlines (UAL) – United Airlines lost $1.60 per share for the fourth quarter, narrower than the $2.11 loss that analysts were anticipating. Revenue topped forecasts, and United said the spread of the omicron Covid-19 variant hurt short-term bookings, yet it expects that negative impact to be temporary. United fell 1.4% in premarket trading., Ford (F) – Ford lost 2% in the premarket after Jefferies downgraded the automaker's stock to "hold" from "buy." Jefferies said the optimism over Ford's electric vehicle plans drove the stock higher than was justified and left very little potential upside.                                                                                              , Regions Financial (RF) – The bank's stock tumbled 4.9% in premarket trading after it reported lower-than-expected quarterly earnings, with revenue matching analyst estimates.                                                                                                                                                                               , Electronic Arts (EA) – Electronic Arts could be the next attractive target in the gaming sector following Microsoft's (MSFT) deal to buy Activision Blizzard (ATVI), according to a column in today's Financial Times. Electronic Arts rose 1% in the premarket.                                                                                             , Discover Financial Services (DFS) – Discover reported a quarterly profit of $3.64 per share, 5 cents below estimates, with revenue also falling short of analyst forecasts. The stock fell 3% in premarket action.                                                                                                                                           , Alcoa (AA) – Alcoa reported adjusted quarterly earnings of $2.50 per share, beating the $1.90 consensus estimate, with revenue essentially in line with expectations. Alcoa benefited from rising aluminum prices, and its stock added 1.9% in the premarket.                                                                                                , Casper Sleep (CSPR) – Casper Sleep surged 12.9% in premarket trading after shareholders approved a deal to take the mattress company private. The transaction is expected to be completed next week.                                                                                                                                                         , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                       , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                       , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                             , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                             , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                           , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-01-20 20:25:00 </td>
   <td style="text-align:left;"> US Futures Recover </td>
   <td style="text-align:left;"> Stock futures in the US were higher on Thursday, with contracts on the Dow Jones rising more than 100 points while the S&amp;P 500 added 0.5% and the Nasdaq gained almost 1% after sliding into correction territory. Treasury yields retreated for a second day from recent 2-year highs and traders shifted their focus to corporate results. Earnings from Travelers Companies and  American Airlines topped forecasts while United Airlines was down around 1% in premarket trading after the company lowered its 2022 growth forecast due to the spread of the omicron variant. Netflix and PPG Industries are due to report today after the closing bell. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/01/20/europe/prince-andrew-social-media-gbr-scli-intl/index.html </td>
   <td style="text-align:left;"> 2022-01-20 20:14:59 </td>
   <td style="text-align:left;"> Prince Andrew's Twitter account deleted, days after royal loses military titles and charities - CNN </td>
   <td style="text-align:left;"> London (CNN)Prince Andrew's Twitter account has been deleted, days after the Queen stripped him of his honorary military titles and charities.                                                                                                                                                                                                                                                                                , Visitors to the prince's official Twitter page, @TheDukeofYork, which has previously been tagged in posts by the official royal family Twitter handle, are now met with a blank page and a message stating "this account doesn't exist."                                                                                                                                                                                      , The bio on the page used to read "The Official Twitter Account for The Duke of York" and his own tweets were signed off with "AY," according to PA Media news agency. An account on YouTube is also no longer available, PA Media reports.                                                                                                                                                                                    , The prince still appears to have an official Instagram account, though this has recently been made private, meaning followers must request access to the page.                                                                                                                                                                                                                                                                , Buckingham Palace has also updated its official website to reflect moves taken by the royal family to distance themselves from the Duke of York, who is facing a civil sexual assault trial in the US.                                                                                                                                                                                                                        , When contacted by CNN Thursday, Buckingham Palace said in a statement: "Changes have been made to reflect the recent statement from Buckingham Palace regarding The Duke of York."                                                                                                                                                                                                                                            , On the British monarchy's official website, the Queen's second son still has a page reflecting his dukedom. However, at the top of the Duke of York page, it now refers to the Queen's January 13 statement announcing his loss of titles and patronages.                                                                                                                                                                     , "Prior to stepping back from public life, The Duke of York undertook a wide range of public work, with a strong economic and business focus," a statement on Prince Andrew's page now reads.                                                                                                                                                                                                                                  , On a separate subhead, titled "Supporting the Queen," Andrew's former duties are detailed in the past tense. For example, it states: "An important part of The Duke of York's role was to support The Queen's work as Head of State. He did this through representing Her Majesty at events and visits in the UK and abroad; receiving Heads of State and Government officials, and attending state and ceremonial occasions.", Last week, a New York judged ruled against a motion by Andrew's legal team to dismiss a civil lawsuit brought against him by Virginia Giuffre, who alleges she was trafficked by disgraced financier Jeffrey Epstein and forced to perform sex acts with the prince at the age of 17. Andrew has vigorously denied those claims.                                                                                              , Sign up to CNN's Royal News, a weekly dispatch bringing you the inside track on the royal family, what they are up to in public and what's happening behind palace walls.                                                                                                                                                                                                                                                     , </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2022-01-21 09:35:57 UTC +8

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
   <td style="text-align:left;"> 2022-01-21 09:35:38 </td>
   <td style="text-align:left;"> $SPY you too can do it

Hourofcode.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:35:27 </td>
   <td style="text-align:left;"> $SPY Twitter down. Russia most likely 

https://downdetector.com/status/twitter/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:35:23 </td>
   <td style="text-align:left;"> $SPY aww man I hope it opens high and dump let me load more fucking puts please </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:35:05 </td>
   <td style="text-align:left;"> $SPY 

\        /
  \    /
    \/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:35:04 </td>
   <td style="text-align:left;"> $SPY how is it always pumped after market closes but barely before weird </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:35:01 </td>
   <td style="text-align:left;"> $SPY next person to ask me to wear a mask or if I&amp;#39;m vaccinated will get the question from me, &amp;quot;has your doctor shoved his or her fist up your ass this year??&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:35:01 </td>
   <td style="text-align:left;"> $SPY  
My pimples are so juicy and tasty. Love the crunch and custard puss </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:35:00 </td>
   <td style="text-align:left;"> $SPY puts all day tomorrow, US economy in shambles, no one is able to afford food, gas, utilities… we can’t even afford to buy clothes anymore. Everyone is getting laid off in tech, heard $AAPL sales are slowing dramatically similar to $NFLX. Vegas is empty af because of inflation and bond. $300 PT in two months </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:34:57 </td>
   <td style="text-align:left;"> $SPY Vlad not playing around…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:34:46 </td>
   <td style="text-align:left;"> $PTON $SPY told ya </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:34:44 </td>
   <td style="text-align:left;"> The lower $SPY goes, the dumber this board gets. I swear there&amp;#39;s a strong correlation between stupidity and fear.

It&amp;#39;s the yearly opex this week,  not the end of the he world. Every dip including every crash crash has paid off big time later on. I&amp;#39;d bet 90% of the bears here didn&amp;#39;t buy the covid crash because &amp;quot;zomg the market is over for real this time!!!&amp;quot;

Always tune those people out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:34:38 </td>
   <td style="text-align:left;"> $SPY going below 200 MA tomorrow and that’s a fucking fact </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:34:29 </td>
   <td style="text-align:left;"> $SPY she said she loved me in a text, that bitch getting blocked @PurpleReign8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:34:28 </td>
   <td style="text-align:left;"> $SPY hey guys don&amp;#39;t worry about Russia Canada&amp;#39;s sent there special forces over👇 😉🤣🙃 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:34:23 </td>
   <td style="text-align:left;"> $SPY did Russia just take Twitter down? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:34:20 </td>
   <td style="text-align:left;"> $SPY Never fear bulls! I am your president </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:34:12 </td>
   <td style="text-align:left;"> $SPY $SPX In my honest opinion taking 0 DTE 4500 puts  tomorrow after am pump. Friday is normally selloffs peeps. don&amp;#39;t get stuck. 
Might do a strangle. Any opinions would be appreciated. 
 
Not dumbass buy the dippers. need intellectuals in this thread thanks. 
 
Btw $4500p today for 1/21 went from .90 -&amp;gt; 35.00 today in a few hours </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:34:07 </td>
   <td style="text-align:left;"> $AMZN $SPY $QQQ The past few times Amazon has done the $2900 test (and hard bounce) were all FRIDAYS: July 24, 2020; Sept 18, 2020; March 5, 2021. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:33:59 </td>
   <td style="text-align:left;"> $SPY nobody knows what the hell they talkin bout in here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:33:59 </td>
   <td style="text-align:left;"> $SPY $TWTR down?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:33:57 </td>
   <td style="text-align:left;"> $SPY  bring back Trump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:33:50 </td>
   <td style="text-align:left;"> $SPY $QQQ According to the Doomsday clock, we are the closest to midnight then ever before since 1946. Just some food for thought. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:33:49 </td>
   <td style="text-align:left;"> $SPY car companies sending marketing emails again lol

No more easy buyers. Easy money gone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:33:42 </td>
   <td style="text-align:left;"> Markets closed now Twitter down 🤔 $nflx $tsla $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:33:30 </td>
   <td style="text-align:left;"> $SPY Witching hour tomorrow means this could be an epic fight for 440 or an absolute bloodbath. Either way I&amp;#39;m holding SPY 460 Puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:33:24 </td>
   <td style="text-align:left;"> $SPY &amp;quot;hope it holds&amp;quot;....listen. Nothing is holding. Shot is going to tank hard. NOBODY holding into the weekend. Buy PUTIN PUTS ASAP! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:33:23 </td>
   <td style="text-align:left;"> $SPY ive never seen futes so volatile. Something very strange is happening tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:33:17 </td>
   <td style="text-align:left;"> $SPY Damn. These Futes are extra liquid tonight. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:33:11 </td>
   <td style="text-align:left;"> $SPY $DWAC I demand anyone who likes/comment/shares my posts to be FULLY VACCINATED first! Respect my health! ✊ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:33:00 </td>
   <td style="text-align:left;"> $SPY $QQQ FUTURES RIPPING EXCEPT FINALLY IN THE RIGHT DIRECTION
TOMORROW WILL SUCK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:32:57 </td>
   <td style="text-align:left;"> $DPZ $NFLX $SPY $TSLA 
It’s over </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:32:55 </td>
   <td style="text-align:left;"> $SPY I expected to sell off today again before close but I wasn&amp;#39;t expecting that ugly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:32:51 </td>
   <td style="text-align:left;"> $SPY How bout them futes bulls?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:32:48 </td>
   <td style="text-align:left;"> $SPY DeSantis2024 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:32:18 </td>
   <td style="text-align:left;"> $ES_F: Fugly. Closed under the 21 ema for the first time since October. If we cannot reclaim above 4457, look for 4440 to be next major support. If we don&amp;#39;t hold that, it just gets uglier. If we defend 4457, look for 4470, 4500, and then 4520 to be resistance. 
$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:32:17 </td>
   <td style="text-align:left;"> $SPY some more days of this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:32:06 </td>
   <td style="text-align:left;"> $SPY idk maybe I should buy some es calls back ratio </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:32:03 </td>
   <td style="text-align:left;"> $SPY market is 💩💩💩🤦‍♂️🤦‍♂️🤦‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:32:02 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $NFLX literally me reading the comments on ST 🤭😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:32:02 </td>
   <td style="text-align:left;"> $SPY testing one bottom here hopefully it holds </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:31:58 </td>
   <td style="text-align:left;"> $SPY I have another idea to fix our country. Stop letting the dam lobbyists control our politicians who we the people supposedly hired. 
 
The same dam lobbyists that somehow convinced our &amp;#39;leaders&amp;#39; that keeping liquor stores open during the shutdown was necessary. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:31:50 </td>
   <td style="text-align:left;"> $SPY $QQQ $ARKK $IWM  
 
Reposting this, as it&amp;#39;s the most important factor affecting markets this week: 
 
https://heisenbergreport.com/2022/01/20/the-case-for-a-counter-trend-stock-rally/ 
 
Today&amp;#39;s rally got &amp;quot;snuffed out&amp;quot; too, for arguably the same reasons.  Let&amp;#39;s hope the squeeze materializes tomorrow for longer than it did today.  See replies for the important screengrabs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:31:39 </td>
   <td style="text-align:left;"> $SPY is Twitter down? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:31:37 </td>
   <td style="text-align:left;"> $SPY 380 coming ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:31:37 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA 
Tomorrow will be fun </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:31:35 </td>
   <td style="text-align:left;"> $SPY  ok. I’ll tell you the truth. I’m pissed with my manager. Last 10 days has been an insane run of 750k. And I always ended the day with a position for the next day. Usually a call because it seems to get pumped in the morning.

But my fucking manager wanted to share with me my comp raise and scheduled the meeting at the market close, fucking 3% raise and cost me atleast 30k. Now I have no position for tomorrow 

Ducking livid </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:31:33 </td>
   <td style="text-align:left;"> $SPY how futes lookin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:31:29 </td>
   <td style="text-align:left;"> $SPY already down 0.7% on futures. 430s tomorrow ez </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:31:16 </td>
   <td style="text-align:left;"> $SPY 10 yr falling. May help the markets tomorrow. Biden is weak </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:31:14 </td>
   <td style="text-align:left;"> $SPY here comes the PPT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:31:14 </td>
   <td style="text-align:left;"> $SPY is the fed #fakemoneysupply
and
$XBI is the #fakehealthcare index </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:30:52 </td>
   <td style="text-align:left;"> $SPY what is the market looking like for next week? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:30:44 </td>
   <td style="text-align:left;"> $SPY is anybody even buying calls for June? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:30:39 </td>
   <td style="text-align:left;"> $SPY $QQQ $GME $BTC.X $NFLX greedy bulls. They&amp;#39;re always bashing bears and ignoring facts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:30:30 </td>
   <td style="text-align:left;"> $SPY sleepy joe fuckhead needs to go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:30:26 </td>
   <td style="text-align:left;"> $BTC.X $SPY  Even in Russian language we understand the word” Raus de Market” screamed  in German </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:30:11 </td>
   <td style="text-align:left;"> $SPY 9 put of 10 stocks has the same pattern for the last 12 months.... down. Im not disappointed in myself. I&amp;#39;m disappointed in everyone that voted for Biden. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:30:07 </td>
   <td style="text-align:left;"> $SPY Indexes are red because of NFLX. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:29:55 </td>
   <td style="text-align:left;"> $SPY $QQQ okay bullish / bearish opinions aside , how we making money in this turbulence friends ? Puts on open spikes , calls on open dips sell each at 11am - 12pm? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:29:47 </td>
   <td style="text-align:left;"> $SPY ppt since 1987 shoukdndo there job and keep buying  seriously Larry fink needs to do his job </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:29:44 </td>
   <td style="text-align:left;"> $QQQ $spy $iwm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:29:39 </td>
   <td style="text-align:left;"> $SPY as expected nothing unusual with the pump </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:29:14 </td>
   <td style="text-align:left;"> $SPY circuit breakers on. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:29:13 </td>
   <td style="text-align:left;"> $SPY most bears will get greedy and not sell their puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:29:12 </td>
   <td style="text-align:left;"> $SPY bulls, how you doing? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:29:12 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM
Not hard to a see a 2022 corrective reversion back to the pre-Covid, pre-stimulus slope.  Let’s hope it ends there. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:29:03 </td>
   <td style="text-align:left;"> $SPY https://www.bloomberg.com/news/articles/2021-09-15/how-opex-is-shaking-up-the-third-week-of-the-month-quicktake </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:28:57 </td>
   <td style="text-align:left;"> $SPY futes rippin! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:28:56 </td>
   <td style="text-align:left;"> $SPY $PTON $NFLX $AMZN $TSLA  R.I.P 

You all will be remembered!  3-6 mafia   🧞‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:28:54 </td>
   <td style="text-align:left;"> $SPY the only thing that can save this market is if crossingtrends comes with super bearish chart </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:28:52 </td>
   <td style="text-align:left;"> $SPY 426 seems legit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:28:50 </td>
   <td style="text-align:left;"> $SPY 

Been reducing my exposure the last week and a half … good luck all. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:28:49 </td>
   <td style="text-align:left;"> $SPY No Bounce tomorrow
OPEX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:28:33 </td>
   <td style="text-align:left;"> $SPY Big bounce! Screw it I’m going to buy some MES here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:28:24 </td>
   <td style="text-align:left;"> $SPY I thos the start of ppt showing up? Ffs rally this until fcuking open so I can sellcash out with profit bad enough I gave back all gains today because I didn&amp;#39;t cash out at open like.the idiot I am </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:28:22 </td>
   <td style="text-align:left;"> $SPY we’re testing Oct 2021 lows … charts so broken I can’t even do much until the first 30 mins prints tomorrow… insane </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:28:21 </td>
   <td style="text-align:left;"> $SPY Dont Fight the FED..Short The Pops. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:28:17 </td>
   <td style="text-align:left;"> $SPY Hmmmmm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:28:13 </td>
   <td style="text-align:left;"> $SPY possible outside quarter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:28:09 </td>
   <td style="text-align:left;"> $SPY  PRESS RELEASE: Health professionals call for urgent investigation into deaths in young males
https://www.hartgroup.org/press-release/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:28:08 </td>
   <td style="text-align:left;"> $SPY VERY NICE DOUBLE BOTTOM THERE

I THINK SELLOFF OVER !!!!

🙂🙂📈👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:28:05 </td>
   <td style="text-align:left;"> $SPY not even down 10% yet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:28:00 </td>
   <td style="text-align:left;"> $SPY big boys been getting out since august and leave these ridiculous pt’s to bait retail into thinking their buying the dip on overvalued trash hype stocks valuations matter fundamentals matter but this time is different 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:27:52 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ we might see a quick flash in the morning and then rip back up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:27:48 </td>
   <td style="text-align:left;"> $SPY green by morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:27:47 </td>
   <td style="text-align:left;"> $SPY It’s nothing unless those MAs invert. Lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:27:47 </td>
   <td style="text-align:left;"> $SPY everytime bulls check futures.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:27:46 </td>
   <td style="text-align:left;"> $SPY the more I read all these bearish posts the more I think the market rips tomorrow - it’s always the same game </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:27:45 </td>
   <td style="text-align:left;"> $SPY Sometimes experience and tactics trump &amp;quot;superior &amp;quot; intellect 💣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:27:44 </td>
   <td style="text-align:left;"> $SPY Good for futures to be red early..good for a potential green Friday.  Lets see... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:27:22 </td>
   <td style="text-align:left;"> Thought it would be worth reposting this from last year about macro technical levels on the indexes, as we’ve hit that point of the 200 day moving average crossings $SPY  $QQQ  $DJIA  $IWM 

https://optimizedvalue.xyz/breaking-down-how-last-springs-quick-recovery-may-pose-a-longer-term-problem-for-major-stock-indexes/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:27:22 </td>
   <td style="text-align:left;"> $SPY Long term trend line broken. At 200dmvg. Dead cat bounce? Strategy: short the rallies. Next support level 427ish $QQQ $IWM $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:27:08 </td>
   <td style="text-align:left;"> $SPY Id guess you have a red open but with HUGE OPEX tomorrow Id expect some covering and maybe tenuous holding to FOMC next week. If it pops GTFO if youre long and the rest of you add to shorts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:27:07 </td>
   <td style="text-align:left;"> $SPY 400 or less by the end of the month bulls… Biden back Powell’s QT lmao

https://www.cnbc.com/amp/2022/01/19/biden-backs-federal-reserve-chair-jerome-powell-policy-tightening-plan.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:27:06 </td>
   <td style="text-align:left;"> $SPY nah nah idc bear or bull this ain’t good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:27:00 </td>
   <td style="text-align:left;"> $SPY ak47 are probably x10 right now in Ukraine. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:26:56 </td>
   <td style="text-align:left;"> $SPY Does stonktwits stop changing the AH price at 8pm? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:26:55 </td>
   <td style="text-align:left;"> $SPY PRAYIN these calls don’t eat my ass </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:26:49 </td>
   <td style="text-align:left;"> $SPY not sure if outs are a good idea for tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:26:48 </td>
   <td style="text-align:left;"> $SPY I’m optimistic! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:26:47 </td>
   <td style="text-align:left;"> $SPY $QQQ The QQQ&amp;#39;s closed below their 200-day MA, I think tomorrow&amp;#39;s gonna be gap down in the morning followed by a rally to the upside </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:26:46 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:26:46 </td>
   <td style="text-align:left;"> $SPY buy calls tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:26:38 </td>
   <td style="text-align:left;"> $IWM 175-185 demand zone $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:26:32 </td>
   <td style="text-align:left;"> $SPY Is it really that difficult to greatly ease inflation in the US? I have 2 ideas. (1) End mandates for everyone and focus on them on the elderly and stop restricting early outpatient therapies. 
(2) Reverse your battle on oil, maybe consider it takes place over decades, not with a nuke bomb that was never realistic: 
https://www.bbc.com/news/world-us-canada-55709261 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:26:18 </td>
   <td style="text-align:left;"> $SPY have a feeling Powell will be dovish on Wednesday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:25:58 </td>
   <td style="text-align:left;"> $SPY tomorrow will be blood red no one going into weekend long . Putin will invade this weekend. I feel really bad for Ukrainians that will die or loss family .Joe Biden will do nothing to save them. He has already gave Putin green light . Biden will cut off arms shipments as soon as Putin enters . So I suspect we have a huge sell off tomorrow. Monday will be another-one . Dead cat bounce Tuesday and continue bleeding and recession . That 2022 in a nutshell. EOY -30 % on spy . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:25:57 </td>
   <td style="text-align:left;"> $SPY $QQQ i love y’all but we are going to eat shit this year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:25:43 </td>
   <td style="text-align:left;"> $BTC.X $SPY Sounds about right. Personally only been investing actively since 2017, but welcome to the hurt new investors from 2021. How many of those YouTube gurus are hiding in shame at this point?

https://markets.businessinsider.com/news/stocks/stock-market-outlook-jeremy-grantham-sp500-crashing-superbubble-gmo-50-2022-1?amp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:25:43 </td>
   <td style="text-align:left;"> $SPY it&amp;#39;s making a strong come back!! No raised interest rate..fresh off the 1984 telesceeen. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:25:43 </td>
   <td style="text-align:left;"> $SPY FUCK BRANDON </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:25:40 </td>
   <td style="text-align:left;"> $SPY $nflx CNBC BREAKING NEWS: Apple to purchase Netflix at $200 per share. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:25:37 </td>
   <td style="text-align:left;"> $amc $gme $bbig and all the others. 
Shorting wasn’t enough, we’ve just watched the Market Makers tank the $spy and the Q’s to keep the massive amount of calls out of the money. You have just been robbed, do not be quiet about it! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:25:35 </td>
   <td style="text-align:left;"> $SPY lol bears trying to bring down the market with their comments 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:25:31 </td>
   <td style="text-align:left;"> $IQ last time Nasdaq was this low October 11. This stock was $9. $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:25:25 </td>
   <td style="text-align:left;"> $SPY wtf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:25:22 </td>
   <td style="text-align:left;"> $QQQ (Right) has already filled the gap from Oct 14th, based on price action it’s likely $SPY continues lower to also fill the gap from October. In my opinion any upside we see in $SPY is just a short lived move that will be sold off. Once the gap is filled then the possibility of a reversal opens up. There’s still Tech earnings, Fed interest decision and FOMC next week. Volatility isn’t over just yet. $SPY has lost support at $450 (all levels of support since reaching $479.98) might as well just get the sell off over with before FOMC…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:25:21 </td>
   <td style="text-align:left;"> $SPY   For my Aces who used to Rock Green 

   $AMZN $TSLA $NFLX $PTON </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:25:16 </td>
   <td style="text-align:left;"> $SPY 

The worst part about today, VIX isn’t even that high! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:25:16 </td>
   <td style="text-align:left;"> $SPY I will admit, Putin has balls. On the verge of invading a European country without giving any fucks. I don’t condone it and hope it doesn’t happen, but the fact that he doesn’t care is interesting to say the least. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:25:15 </td>
   <td style="text-align:left;"> $WTRH Growth money is going to move to value now. We are sitting as good or better than anyone. $SPY $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:25:13 </td>
   <td style="text-align:left;"> $SPY &amp;quot;lol futes&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:25:10 </td>
   <td style="text-align:left;"> $SPY Markets suck </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:25:09 </td>
   <td style="text-align:left;"> $SPY first dip, spy to $425 at open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:25:08 </td>
   <td style="text-align:left;"> $SPY if Putin rolls into Ukraine your gonna have a scenario where March 2020 and December 2018 had a baby and it was xxx 2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:24:58 </td>
   <td style="text-align:left;"> $SPY I had a guy go back and forth about dark pool prints blah blah and we’re going back to 470 lmao probably blew his portfolio up today 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:24:57 </td>
   <td style="text-align:left;"> $SPY looks like he found printer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:24:51 </td>
   <td style="text-align:left;"> $SPY $BABA Down 5% in HongKong... lol😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:24:40 </td>
   <td style="text-align:left;"> $SPY wow... Dumping harder on futures than today&amp;#39;s session 😳$QQQ $NASDAQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:24:36 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:24:32 </td>
   <td style="text-align:left;"> $SPY even bear feels sorry for themselves. Softest shit I&amp;#39;ve ever seen </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:24:26 </td>
   <td style="text-align:left;"> $SPY Thanks Brandon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:24:21 </td>
   <td style="text-align:left;"> $SPY 10Y falling bc it can’t even believe how terrible our economy is. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:24:12 </td>
   <td style="text-align:left;"> $SPY If it gaps down I&amp;#39;m ready to buy tomorrow. Would love to see open around 443. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:24:11 </td>
   <td style="text-align:left;"> $SPY nowhere near bottom. #dotheopposite </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:24:04 </td>
   <td style="text-align:left;"> $SPY crash you bitch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:24:03 </td>
   <td style="text-align:left;"> $DWAC market down 2% this thing fucking bold green. BULLISH AF 🚀🚀🚀🚀 $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:23:59 </td>
   <td style="text-align:left;"> $SPY who else scoopin more puts after tomorrow’s failed pump from “dip” buyers? 🙋‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:23:58 </td>
   <td style="text-align:left;"> $SPY .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:23:57 </td>
   <td style="text-align:left;"> $SPY 200 sma on futes is around 4425 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:23:56 </td>
   <td style="text-align:left;"> $SPY short story is over with this double bottom, we will have a blue sky breakout tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:23:49 </td>
   <td style="text-align:left;"> $SPY  time to buy the dip.boyz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:23:47 </td>
   <td style="text-align:left;"> $SPY so this is how it all ends… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:23:42 </td>
   <td style="text-align:left;"> $SPY Yes it&amp;#39;s really that bad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:23:31 </td>
   <td style="text-align:left;"> $SPY $BTC.X Bitty is on the edge 🐻🚩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:23:26 </td>
   <td style="text-align:left;"> $SPY  you can still get Netflix 480p real cheap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:23:21 </td>
   <td style="text-align:left;"> $SPY More fuckery tomorrow ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:23:02 </td>
   <td style="text-align:left;"> $SPY $TSLA looking at the futes 🥴 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:23:01 </td>
   <td style="text-align:left;"> $SPY at least 10 year going back down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:22:45 </td>
   <td style="text-align:left;"> $SPY           $QQQ           $NDX 

          $PTON          $NFLX               .🧞‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:22:41 </td>
   <td style="text-align:left;"> $SPY this is going dowwwnnnn townnnn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:22:33 </td>
   <td style="text-align:left;"> $SPY Brace futes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:22:31 </td>
   <td style="text-align:left;"> $SPY How many stocks at or near 52wk lows…rhetoric question 🙄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:22:25 </td>
   <td style="text-align:left;"> $SPY I said it 10 days ago </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:22:25 </td>
   <td style="text-align:left;"> $SPY 4,060 futures all hut a certainty at this point.

Crude will be $60’ish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:22:23 </td>
   <td style="text-align:left;"> $SPY 200 dma is gonna get bombed hard asf tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:22:22 </td>
   <td style="text-align:left;"> $SPY I covered all my short Netflix shares before 8… maybe I shouldn’t have. Looks like it wants to go below 400 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:22:11 </td>
   <td style="text-align:left;"> $SPY @OldFngGuy Say Market Crash three times in the bathroom mirror with the lights out. You won&amp;#39;t bears. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:22:05 </td>
   <td style="text-align:left;"> $SPY Find who came up with the word Transitory;  Tar &amp;amp; Feather them </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:22:05 </td>
   <td style="text-align:left;"> $SPY just simply not buyable </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:21:51 </td>
   <td style="text-align:left;"> Dark pool after hours activity in: 
 
$QQQ - $119M print 
$SPY - $367M print 
$AAPL - $337M print 
$EEM - $109M print 
 
#darkpool </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:21:51 </td>
   <td style="text-align:left;"> $SPY People buying this dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:21:48 </td>
   <td style="text-align:left;"> $SPY I have a feeling tomorrow will be the buy of the year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:21:44 </td>
   <td style="text-align:left;"> $SPY Love this video. If you guys trade this market, watch Jim literally time the perfect and flat out play by play the market. @jlebenthal 
 
https://www.youtube.com/watch?v=ulRoTspyQRs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:21:43 </td>
   <td style="text-align:left;"> $SPY 10 year is retreating which could be a good sign but to be honest after seeing what they did to Netflix I’m kinda lost all hope to be honest 🥲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:21:39 </td>
   <td style="text-align:left;"> $ROKU $SQ $MRNA Right now market renames “GROWTH” stocks as “————-“ what do you want name it..? $AMC $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:21:35 </td>
   <td style="text-align:left;"> $SPY Whatever, went 3/3 today for some solid gains. I can accept an L on my bull put spread. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:21:33 </td>
   <td style="text-align:left;"> $SPY let see a resistant at 440. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:21:27 </td>
   <td style="text-align:left;"> Now this $nflx $aapl $tsla $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:21:25 </td>
   <td style="text-align:left;"> $SPY who needs cardio when you&amp;#39;ve got the stock market... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:21:13 </td>
   <td style="text-align:left;"> $SPY  SMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:21:07 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X yep. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:21:03 </td>
   <td style="text-align:left;"> $SPY Double bottom confirmed!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:21:00 </td>
   <td style="text-align:left;"> $SPY we are already in a recession

Recession is psychological. It’s a way of thinking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:20:59 </td>
   <td style="text-align:left;"> $SPY $GME $WKHS $NKLA Could get interesting in highly shorted names. Almost all hedge funds do long short trades so if the whole market starts to sell off they will be forced to cover there shorts to balance their portfolio. This could cascade into massive short squeezes like GME. And GME may squeeze again. Seems short volume has skyrocketed all over the market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:20:52 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:20:48 </td>
   <td style="text-align:left;"> $SPY bull fag </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:20:40 </td>
   <td style="text-align:left;"> $SPY  okay another 101. 
 
when it comes to options buying puts or calls is a long position. Buy low sell high. So ducking stop staring at the stock price and look at the option price. We are all bulls one way or the other </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:20:34 </td>
   <td style="text-align:left;"> $SPY Welp, $ROPE is my next investment! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:20:34 </td>
   <td style="text-align:left;"> $SPY  Can nobody tell me nothing 🧞‍♂️

          $SPX          $DJIA          $NASDAQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:20:34 </td>
   <td style="text-align:left;"> $SPY forex is worse than crypto, just so ya know. $DOGE.X   🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:20:32 </td>
   <td style="text-align:left;"> $SPY Who needs sports when you have futures? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:20:20 </td>
   <td style="text-align:left;"> $SPY Trade talks going well </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:20:08 </td>
   <td style="text-align:left;"> $SPY retail retards need to feel this pain, long overdue </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:20:03 </td>
   <td style="text-align:left;"> $SPY futures🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:19:55 </td>
   <td style="text-align:left;"> $SPY You know who you are. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:19:45 </td>
   <td style="text-align:left;"> $SPY the news article still says $NFLX results beat in Q4. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:19:42 </td>
   <td style="text-align:left;"> $SPY imagine being 65, ready for retirement banking on your 401k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:19:39 </td>
   <td style="text-align:left;"> $SPY only poor people aren’t buying this dip - only 1/3 of what we’re pushing back into the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:19:29 </td>
   <td style="text-align:left;"> $SPY This is just fear rates need to chill out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:19:25 </td>
   <td style="text-align:left;"> $SPY  I tell you when it’s time Btch  

                          🧞‍♂️ organized run off </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:19:23 </td>
   <td style="text-align:left;"> $SPY she only fcks with Put buyers sorry bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:19:20 </td>
   <td style="text-align:left;"> $QQQ $SPY When you buy the dip and it dips more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:19:13 </td>
   <td style="text-align:left;"> $SPY VIX is more important to spy than the options </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:19:13 </td>
   <td style="text-align:left;"> $SPY green tomorrow!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:19:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA Jim Cramer says he&amp;#39;s more confident that the market&amp;#39;s approaching a bottom </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:19:05 </td>
   <td style="text-align:left;"> $SPY I bought everything and will continue doing so </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:18:59 </td>
   <td style="text-align:left;"> $SPY $TSLA Elon&amp;#39;s one tweet away from saying &amp;quot;recession&amp;quot; again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:18:59 </td>
   <td style="text-align:left;"> $SPY apple ER is going to be a huge disaster next week 🤣🤣🤣

https://www.macrumors.com/2022/01/04/q1-2022-earnings-january-27/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:18:56 </td>
   <td style="text-align:left;"> $SPY 201k will look sweet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:18:48 </td>
   <td style="text-align:left;"> $SPY this is a correction folks

But it’s happening slowly, and painfully lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:18:47 </td>
   <td style="text-align:left;"> $SPY Even 10y getting smoked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:18:47 </td>
   <td style="text-align:left;"> $SPY The odds are still higher to be a Bull because it has always been FIXED just saying </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:18:40 </td>
   <td style="text-align:left;"> $SPY Putin interview on June 8, 2021: &amp;quot;You know what the problem is? I will tell you as a former citizen of the former Soviet Union. The problem of empires is that they think they are so powerful that they can make small errors and mistakes. Thinking they will buy these people, bully those people, make a deal with those, give some necklaces to some, threaten others with battleships. And this will solve all problems....        But, problems accumulate, and there comes a time when they can no longer be dealth with..  And the United States with great determination, is following right in the Soviet Union&amp;#39;s footsteps.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:18:37 </td>
   <td style="text-align:left;"> $SPY where are you @OldFngGuy? The buying machines are broken </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:18:36 </td>
   <td style="text-align:left;"> $SPY It’s choppy season. Expect heightened volatility and scattered portfolios throughout the day with a dash of deflation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:18:29 </td>
   <td style="text-align:left;"> $SPY DED </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:18:26 </td>
   <td style="text-align:left;"> $SPY buy into weakness sell into  retard strength </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:18:24 </td>
   <td style="text-align:left;"> $SPY Jesus Christ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:18:19 </td>
   <td style="text-align:left;"> $SPY $QQQ VIX futures on a damn rampage tonight. Kinda wondering if VIX can hit 30 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:18:15 </td>
   <td style="text-align:left;"> $SPY $NASDAQ $DJIA Seriously does anyone still approve of Joe Biden and the progressive left? If so, please state your reasoning. All I can think of is pride. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:18:12 </td>
   <td style="text-align:left;"> $spy why can’t bulls see the red candles ? Because it’s up their ass and they are sitting on it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:18:07 </td>
   <td style="text-align:left;"> $SPY is this bc of COVID or bc we have an inept leader ???  And the market knows it. 

I’m gonna keep buying puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:18:04 </td>
   <td style="text-align:left;"> $SPY Put a fork in her she done.... Dead bitch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:18:03 </td>
   <td style="text-align:left;"> $SPY Is tomorrow the day? 🔻🔻 🤢 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:18:03 </td>
   <td style="text-align:left;"> $SPY feel bad for those poor bastards worked 40 years for retirement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:17:52 </td>
   <td style="text-align:left;"> $SPY to be honest. I hope the market does crash. I really do. I have money to put to work. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:17:52 </td>
   <td style="text-align:left;"> $SPY do the politicians have protective puts? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:17:50 </td>
   <td style="text-align:left;"> $SPY circuit breakers tomorrow ??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:17:50 </td>
   <td style="text-align:left;"> $SPY 

Here’s a quick financial advice, yes I said it.. financial advice, before you buy anything from now on, look at the all time low, if current price is above, don’t buy it, if current price is indeed the all time low, buy puts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:17:50 </td>
   <td style="text-align:left;"> $SPY I tell you when is the bottom Btch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:17:44 </td>
   <td style="text-align:left;"> $SPY bears are anti American </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:17:42 </td>
   <td style="text-align:left;"> $SPY  
 
Why has Jpow&amp;#39;s dog been limping the last few days? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:17:36 </td>
   <td style="text-align:left;"> $SPY Even us retard traders knew to shift defensive ,🤡🤡🤡🤡didn&amp;#39;t listen,itchy butthole stinky finger in your general direction 💥💥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:17:35 </td>
   <td style="text-align:left;"> $SPY futes shittin boys. My 435 lotto puts for tomorrow may just end up in the money. Fed may be entering a new correction without restocking their ammo after the last one. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:17:33 </td>
   <td style="text-align:left;"> $SPY so you’re saying all of these politicians lost too — all down 15% YTD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:17:31 </td>
   <td style="text-align:left;"> $SPY loaded puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:17:29 </td>
   <td style="text-align:left;"> $SPY $QQQ CRUDE dying </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:17:24 </td>
   <td style="text-align:left;"> $SPY the people who bought calls at the close thinking they’re smart … what the hell were y’all thinking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:17:12 </td>
   <td style="text-align:left;"> $SPY Fed will not let it crash. This is a fake managed market and Brandon is pumping on tv. If they let it go it’s over for everyone. Game over. DOW $8,000 $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:17:12 </td>
   <td style="text-align:left;"> $SPY $NFLX $AAPL $GOOG $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:17:01 </td>
   <td style="text-align:left;"> $SPY I have a short strike at $440. I can accept max loss, but I will not like it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:16:53 </td>
   <td style="text-align:left;"> $SPY           🩸. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:16:46 </td>
   <td style="text-align:left;"> $SPY that was the bottom. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:16:45 </td>
   <td style="text-align:left;"> $SPY people actually saw todays action as a BTD opportunity lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:16:39 </td>
   <td style="text-align:left;"> $SPY $QQQ So my prediction for WW3 is US + NATO vs. Russia + China + Africa + Middle East. Taking bets on who wins! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:16:36 </td>
   <td style="text-align:left;"> $SPY hope premarket is bloody. My small caps don&amp;#39;t move out of regular trading hours 

G O C O GoHealth 🌙 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:16:30 </td>
   <td style="text-align:left;"> $SPY        🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:16:25 </td>
   <td style="text-align:left;"> $SPY looking at a huge sell off going into the weekend. I will be SICK tomorrow so I can make some money on this Volatility </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:16:20 </td>
   <td style="text-align:left;"> $SPY  11k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:16:15 </td>
   <td style="text-align:left;"> $SPY “Alexa, play Raining Blood by Slayer 🩸” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:16:03 </td>
   <td style="text-align:left;"> $SPY $460 calls doomed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:16:00 </td>
   <td style="text-align:left;"> $SPY BTFD was a thing because of the fed backing.. that is disappearing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:15:53 </td>
   <td style="text-align:left;"> $SPY speech time? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:15:49 </td>
   <td style="text-align:left;"> $AAPL everybody is bearish, I bet this bounces next week.imagine if aapl fell 20% like Netflix, sndp500 $SPY  Nasdaq would be decimated as well, we will be facing recession. Hopefully that does not happen, have seen how bad 2008 was and generation of graduates won’t find jobs for 3 years and their careers will be hampered. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:15:48 </td>
   <td style="text-align:left;"> $SPY Oh wow! $PTON CEO just said they DID NOT halt production!!  cc $AFRM 

https://www.onepeloton.com/press/articles/a-note-from-john-foley-co-founder-and-ceo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:15:47 </td>
   <td style="text-align:left;"> $SPY Biden’s fault </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:15:46 </td>
   <td style="text-align:left;"> $SPY Just hoping $BTC.X can recover so I can buy some $BITO puts at open. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:15:32 </td>
   <td style="text-align:left;"> $tsla $qqq $spy $fb $snap 😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:15:26 </td>
   <td style="text-align:left;"> $SPY   Bring it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:15:24 </td>
   <td style="text-align:left;"> $SPY with 200sma in view, failed the 50ema harddddddddddddddddddddddddddddd </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:15:23 </td>
   <td style="text-align:left;"> $SPY poop on my chest this is going to be fun </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:15:19 </td>
   <td style="text-align:left;"> $SPY  I’m selling 480p  $NFLX  account for just 3.99$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:15:17 </td>
   <td style="text-align:left;"> $SPY I bet Jill is very disappointed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:15:16 </td>
   <td style="text-align:left;"> $SPY still in 60% cash 

Buying a little more every now and then 

However I think that big tech sells off after earnings, regardless of beat or not </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:15:15 </td>
   <td style="text-align:left;"> $SPY Bidens accomplished this in 1 imagine 4! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:15:13 </td>
   <td style="text-align:left;"> $SPY Near 400 by EOM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:15:10 </td>
   <td style="text-align:left;"> $SPY futures are ripping!!! Amirite??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:15:04 </td>
   <td style="text-align:left;"> $SPY $SPX  
 
Do you guys remember this chart?! Daily view updated. 
 
I had told you she had lost it this week hehe! 
 
Original chart: 
https://stocktwits.com/FPL/message/428181183 
-------- </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:15:03 </td>
   <td style="text-align:left;"> $spy $qqq by Monday close we should be 4-6% lower than now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:15:02 </td>
   <td style="text-align:left;"> $SPY wow futures. Is he watching? He better resign. Useless </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:14:59 </td>
   <td style="text-align:left;"> $SPY $QQQ $GLD $USO $TYX 
Correlation tightens in drawdowns.☝️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:14:59 </td>
   <td style="text-align:left;"> $BTC.X $SPY With Bitcoin trading near $40,000, which comes first? VOTE HERE &amp;gt;&amp;gt;&amp;gt;&amp;gt; https://twitter.com/Robertlesnicki/status/1484333244325584899?s=20 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:14:59 </td>
   <td style="text-align:left;"> $SPY too red, too early </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:14:51 </td>
   <td style="text-align:left;"> $SPY I feel bad for the people who only started in this market past year or so bud think those green V moves were normal lol. That was the fed unprecedented stimulus allowing big buys from institutions etc but now the fed is gone you won’t see those moves. Don’t be fooled people the market was up a staggering 30% last year and now you have no fed help and fear of inflation and rates. A long way to go before it settles and from there it’s your normal 3-9% per year not 2% per day green. If u adjust you can do well playing both sides but if u randomly buy blind calls every dip you won’t be happy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:14:50 </td>
   <td style="text-align:left;"> $SPY   Anyone want to bang anymore 

                            🧞‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:14:38 </td>
   <td style="text-align:left;"> $SPY 441 up next big support level there. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:14:37 </td>
   <td style="text-align:left;"> $SPY okay... can we bring politics into this now? Its only fair. America is looking weak and war is about to break out. Etc etc. Democrats got us here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:14:35 </td>
   <td style="text-align:left;"> $SPY bulls on st still haven’t learned 🤣🤣🤣 BTFD if you hate money fr fr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:14:32 </td>
   <td style="text-align:left;"> $SPY I would say get to a red state. But what do I know. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:14:26 </td>
   <td style="text-align:left;"> $SPY Market is damaged. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:14:25 </td>
   <td style="text-align:left;"> $SPY Went from $459 to $443 almost a 16 PT drop. I am going to say that has never been done before in a day. Just the range was insane never felt this volatility before. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:14:21 </td>
   <td style="text-align:left;"> $SPY dude my puts are going to f&amp;#39;in print tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:14:03 </td>
   <td style="text-align:left;"> $SPY So basically it&amp;#39;s all these countries vs Russia... And why would Russia do this again...? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:14:00 </td>
   <td style="text-align:left;"> $SPY Damn, bulls couldn&amp;#39;t even let me use my new meme for the V. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:14:00 </td>
   <td style="text-align:left;"> $SPY is currently trading in the upper part of its 52 week range, which is inline with the index. https://www.chartmill.com/stock/quote/SPY/technical-analysis?key=84303b30-e7bc-44d7-b0b1-1493858db9a2&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=SPY&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:13:55 </td>
   <td style="text-align:left;"> $SPY well that sucks no ppt tonight but to cut loss and be done til fomc market is a fraud t I guess they done pumping it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:13:55 </td>
   <td style="text-align:left;"> $SPY greed index is neutral lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:13:53 </td>
   <td style="text-align:left;"> $SPY the 200 at at like 4420 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:13:51 </td>
   <td style="text-align:left;"> $SPY   Call Kamala she throw you to jail 2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:13:49 </td>
   <td style="text-align:left;"> $SPY is this what Biden meant by over achieving? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:13:46 </td>
   <td style="text-align:left;"> $SPY uh oh. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:13:43 </td>
   <td style="text-align:left;"> $SPY 440 is her sweet spot, grab by the pssy once she&amp;#39;s there </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:13:41 </td>
   <td style="text-align:left;"> $SPY .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:13:31 </td>
   <td style="text-align:left;"> $SPY indexes look set to open in oversold territory if this movement holds. Still don’t see anything worth buying right now if this is a real downtrend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:13:27 </td>
   <td style="text-align:left;"> $SPY Yeah it’s fucked. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:13:15 </td>
   <td style="text-align:left;"> $SPY LOL futures trippin!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:13:14 </td>
   <td style="text-align:left;"> $SPY tomorrow should be fun </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:13:13 </td>
   <td style="text-align:left;"> $SPY long way to oversold on the Monthly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:13:08 </td>
   <td style="text-align:left;"> $SPY 🚨 who voted for this beauty? $OCGN $CLSK $DKNG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:13:07 </td>
   <td style="text-align:left;"> $SPY HOLY CRAP FUTURES ARE RIPPING TO 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:13:00 </td>
   <td style="text-align:left;"> $SPY Never hold calls when vix ends at HOD like the last two days.   Really think Wall Street took out a decent amount retail here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:12:59 </td>
   <td style="text-align:left;"> $SPY PPT tampon and maxipad won’t stop the 🩸. Damn. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:12:59 </td>
   <td style="text-align:left;"> $SPY During his marathon press conference, Biden sparked an international firestorm as critics accused him of providing a &amp;quot;green light&amp;quot; for Russian President Vladimir Putin to begin an invasion in Ukraine. 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:12:45 </td>
   <td style="text-align:left;"> $SPY our country is broke, how are we going to fight Putin? 🌷 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:12:41 </td>
   <td style="text-align:left;"> $SPY China and Russia teaming up . Houston we have a problem . The leadership has broken. . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:12:36 </td>
   <td style="text-align:left;"> $3.3T of options notional is set to expire tomorrow - Read more about the large OpEx and gamma roll-off implications here: https://opinicusholdings.com/options-trading-blog/market-maker-gamma-exposure

$SPY $QQQ $DIA $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:12:36 </td>
   <td style="text-align:left;"> $SPY  A wise man once said, never sit on a red candle it will burn your ass 7 ways, </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:12:34 </td>
   <td style="text-align:left;"> $SPY  
 
I think I still have a few physical Netflix dvds that I never mailed back. Probably should return them to help the cause </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-21 09:12:32 </td>
   <td style="text-align:left;"> $SPY If this market was a text convo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:34:07 </td>
   <td style="text-align:left;"> $AMZN $SPY $QQQ The past few times Amazon has done the $2900 test (and hard bounce) were all FRIDAYS: July 24, 2020; Sept 18, 2020; March 5, 2021. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:33:50 </td>
   <td style="text-align:left;"> $SPY $QQQ According to the Doomsday clock, we are the closest to midnight then ever before since 1946. Just some food for thought. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:33:00 </td>
   <td style="text-align:left;"> $SPY $QQQ FUTURES RIPPING EXCEPT FINALLY IN THE RIGHT DIRECTION
TOMORROW WILL SUCK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:32:02 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $NFLX literally me reading the comments on ST 🤭😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:31:50 </td>
   <td style="text-align:left;"> $SPY $QQQ $ARKK $IWM  
 
Reposting this, as it&amp;#39;s the most important factor affecting markets this week: 
 
https://heisenbergreport.com/2022/01/20/the-case-for-a-counter-trend-stock-rally/ 
 
Today&amp;#39;s rally got &amp;quot;snuffed out&amp;quot; too, for arguably the same reasons.  Let&amp;#39;s hope the squeeze materializes tomorrow for longer than it did today.  See replies for the important screengrabs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:31:37 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA 
Tomorrow will be fun </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:31:10 </td>
   <td style="text-align:left;"> $QQQ was there a news event that triggered something? Asian shares still did well </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:30:39 </td>
   <td style="text-align:left;"> $SPY $QQQ $GME $BTC.X $NFLX greedy bulls. They&amp;#39;re always bashing bears and ignoring facts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:29:55 </td>
   <td style="text-align:left;"> $SPY $QQQ okay bullish / bearish opinions aside , how we making money in this turbulence friends ? Puts on open spikes , calls on open dips sell each at 11am - 12pm? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:29:44 </td>
   <td style="text-align:left;"> $QQQ $spy $iwm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:29:12 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM
Not hard to a see a 2022 corrective reversion back to the pre-Covid, pre-stimulus slope.  Let’s hope it ends there. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:28:44 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:27:52 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ we might see a quick flash in the morning and then rip back up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:27:22 </td>
   <td style="text-align:left;"> Thought it would be worth reposting this from last year about macro technical levels on the indexes, as we’ve hit that point of the 200 day moving average crossings $SPY  $QQQ  $DJIA  $IWM 

https://optimizedvalue.xyz/breaking-down-how-last-springs-quick-recovery-may-pose-a-longer-term-problem-for-major-stock-indexes/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:27:22 </td>
   <td style="text-align:left;"> $SPY Long term trend line broken. At 200dmvg. Dead cat bounce? Strategy: short the rallies. Next support level 427ish $QQQ $IWM $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:27:06 </td>
   <td style="text-align:left;"> $QQQ tumbling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:26:47 </td>
   <td style="text-align:left;"> $SPY $QQQ The QQQ&amp;#39;s closed below their 200-day MA, I think tomorrow&amp;#39;s gonna be gap down in the morning followed by a rally to the upside </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:26:19 </td>
   <td style="text-align:left;"> $QQQ https://finance.yahoo.com/news/jeremy-grantham-doubles-down-crash-161247192.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:25:57 </td>
   <td style="text-align:left;"> $SPY $QQQ i love y’all but we are going to eat shit this year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:25:42 </td>
   <td style="text-align:left;"> $QQQ currently 11.5% off all time highs....close to being done or nah? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:25:31 </td>
   <td style="text-align:left;"> $IQ last time Nasdaq was this low October 11. This stock was $9. $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:25:22 </td>
   <td style="text-align:left;"> $QQQ (Right) has already filled the gap from Oct 14th, based on price action it’s likely $SPY continues lower to also fill the gap from October. In my opinion any upside we see in $SPY is just a short lived move that will be sold off. Once the gap is filled then the possibility of a reversal opens up. There’s still Tech earnings, Fed interest decision and FOMC next week. Volatility isn’t over just yet. $SPY has lost support at $450 (all levels of support since reaching $479.98) might as well just get the sell off over with before FOMC…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:24:58 </td>
   <td style="text-align:left;"> $QQQ Crude down, 10yr up and futes red… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:24:43 </td>
   <td style="text-align:left;"> $QQQ It&amp;#39;s possible for this to be green in the premarket or light red. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:24:03 </td>
   <td style="text-align:left;"> $DWAC market down 2% this thing fucking bold green. BULLISH AF 🚀🚀🚀🚀 $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:22:52 </td>
   <td style="text-align:left;"> $QQQ cathie woodshed has to be having a bad day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:22:45 </td>
   <td style="text-align:left;"> $SPY           $QQQ           $NDX 

          $PTON          $NFLX               .🧞‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:21:51 </td>
   <td style="text-align:left;"> Dark pool after hours activity in: 
 
$QQQ - $119M print 
$SPY - $367M print 
$AAPL - $337M print 
$EEM - $109M print 
 
#darkpool </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:21:07 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X yep. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:20:57 </td>
   <td style="text-align:left;"> $QQQ limit down tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:20:52 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:19:40 </td>
   <td style="text-align:left;"> $QQQ  when do I get my participation trophy ? I at least deserve that, don’t ya think ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:19:20 </td>
   <td style="text-align:left;"> $QQQ $SPY When you buy the dip and it dips more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:19:11 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA Jim Cramer says he&amp;#39;s more confident that the market&amp;#39;s approaching a bottom </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:18:43 </td>
   <td style="text-align:left;"> $QQQ I bought the dip!!!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:18:19 </td>
   <td style="text-align:left;"> $SPY $QQQ VIX futures on a damn rampage tonight. Kinda wondering if VIX can hit 30 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:17:29 </td>
   <td style="text-align:left;"> $SPY $QQQ CRUDE dying </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:17:06 </td>
   <td style="text-align:left;"> $QQQ probably gonna see $330 eventually </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:16:39 </td>
   <td style="text-align:left;"> $SPY $QQQ So my prediction for WW3 is US + NATO vs. Russia + China + Africa + Middle East. Taking bets on who wins! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:15:58 </td>
   <td style="text-align:left;"> $QQQ Total fucking clown market. Could go to $400 or $300 within a month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:15:32 </td>
   <td style="text-align:left;"> $tsla $qqq $spy $fb $snap 😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:15:03 </td>
   <td style="text-align:left;"> $spy $qqq by Monday close we should be 4-6% lower than now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:14:59 </td>
   <td style="text-align:left;"> $SPY $QQQ $GLD $USO $TYX 
Correlation tightens in drawdowns.☝️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:14:50 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:13:11 </td>
   <td style="text-align:left;"> Pretty important level of supporting coming up in the $QQQ.  Usually we find a bounce on the first touch.  No guarantees. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:12:36 </td>
   <td style="text-align:left;"> $3.3T of options notional is set to expire tomorrow - Read more about the large OpEx and gamma roll-off implications here: https://opinicusholdings.com/options-trading-blog/market-maker-gamma-exposure

$SPY $QQQ $DIA $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:12:31 </td>
   <td style="text-align:left;"> $QQQ $SPY aint gonna be no gross injection of cash to save it this round. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:12:19 </td>
   <td style="text-align:left;"> $SPY  Don’t forget to take money out to pay the tax man in the next week 
M

   $ndx $nasdaq $qqq $spx  🧞‍♂️ Just reminder </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:12:18 </td>
   <td style="text-align:left;"> $QQQ $AMD $SPY No signs of it stopping. Play or get played </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:12:14 </td>
   <td style="text-align:left;"> $QQQ Futures are ripping!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:12:04 </td>
   <td style="text-align:left;"> $QQQ Putin playing sleepy Joe like a fiddle </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:11:58 </td>
   <td style="text-align:left;"> latexc4b6ddb8ffd4be5f5e8df2878c32afcfNVDA goes lower with others 
$AAPL $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:11:30 </td>
   <td style="text-align:left;"> $QQQ $TQQ feel bad for those who made money in 2021 and sold before year end to pay taxes and bought back in. Then now selling at a loss. All those gains they still have to pay taxes for, gone. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:11:11 </td>
   <td style="text-align:left;"> $SPY      Phat Roll’s     $QQQ   🧞‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:11:05 </td>
   <td style="text-align:left;"> $SPY $QQQ Whew, looking at that monthly candle on NDX busting through the 10 MMA...looks like I&amp;#39;ll have to pull the bollinger bands out to find support. Hard to believe $13.5K is in play, at the 20 MMA. You would think the Fed would say something before the FOMC announcement. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:10:47 </td>
   <td style="text-align:left;"> $BTC.X $QQQ &amp;quot;Bitcoin is a store of value &amp;amp; is an uncorrelated asset....&amp;quot; Bitcoin down -12.5% in 2022, while the Nasdaq 100 is down  -9.95%..... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:10:43 </td>
   <td style="text-align:left;"> $SPY $QQQ Be patient. Let it do it’s thing. This is very bearish action. Needs to be more bloody. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:10:39 </td>
   <td style="text-align:left;"> $NDX $qqq $tqqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:09:46 </td>
   <td style="text-align:left;"> $SPY $VTI $QQQ $QYLD
My GOD when will this nightmare end. Just look at this Jan chart. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:09:40 </td>
   <td style="text-align:left;"> $QQQ that a boy Futes.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:09:07 </td>
   <td style="text-align:left;"> $QQQ bye bye 14700 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:08:48 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $SPX 
Here’s how I would crash the market: 

I would first get a green screen and a custom suit. I would hire the best “deep fake” expert and use state of the art software. 

I would make myself look and sound like Jerome Powell. Then call into CNBC and a couple other news outlets from a random line saying “Jerome Powell is going to make a statement.” 

Then, I would have pre recorded a deep fake and play it. Saying “we’re experiencing a lot of inflation and need to dramatically raise rates.” 

Then I would sell my outs for a massive gain. Throw away the phone I used to call in. Burn all the equipment. Pay the expert his cut. Then relax on a beach somewhere as they chase down the man who pulled the greatest heist in history. Cheers 🥂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:08:46 </td>
   <td style="text-align:left;"> $F $QQQ $spy $BTC Crap….Futures are down, again…. I think we’re going to hit a recession thanks to inflation. Companies that gave billions in bonuses ( $HPE ) will wish they kept their money. This may get ugly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:08:03 </td>
   <td style="text-align:left;"> $SPY  Let’s all get Slaughtered 

   🧞‍♂️ $ES_F $SPX $QQQ $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:08:01 </td>
   <td style="text-align:left;"> $QQQ make your own judgment </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:07:58 </td>
   <td style="text-align:left;"> $SPY $QQQ future don’t matter at this point it always turns green at open then just tank </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:07:54 </td>
   <td style="text-align:left;"> $QQQ I hope everyone lightened their exposure to tech today. No doubt the Q’s test the 354 level tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:07:49 </td>
   <td style="text-align:left;"> $QQQ Bran spilled the beans yesterday that they have already decided how 🇺🇦 is going to be divided . Maybe a Kiev wall this time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:07:20 </td>
   <td style="text-align:left;"> $SPY $QQQ Has anyone tried unplugging it and plugging it back in yet? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:07:06 </td>
   <td style="text-align:left;"> $SPY  Anyone know why this so high? 🧞‍♂️

Thx just asking for my friends 

   🧞‍♂️ $DJIA $NASDAQ $QQQ $SPX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:07:02 </td>
   <td style="text-align:left;"> $QQQ honestly Nflx has a very bad earning. it&amp;#39;s a bad sentiment for the whole market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:06:21 </td>
   <td style="text-align:left;"> Check out the Top Analysts of 2021 via @TipRank giving their insight 4 2022. 
 
Gr8 way 2 get investing ideas to buy the current $SPY $QQQ dip! 
 
$VIX $STUDY $DIA 
 
https://www.youtube.com/watch?v=xULNMx-otMo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:05:14 </td>
   <td style="text-align:left;"> $SPY Brandon Russia + China = 

  $dia $djia $qqq $spx 🧞‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:04:52 </td>
   <td style="text-align:left;"> 95% of COVID rich traders will be broke by year end and fighting each other for subs on OnlyFans.   $SPY $IWM $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:04:32 </td>
   <td style="text-align:left;"> $MKFG I have found that so many newly listed (de-spac) companies are struggling to achieve a decent gross margin, heavily sold off.  Markforged has improved gross margin massively from 48% to 58% before IPO !!!  
 
The CEO mentioned that he actually reduced the number of channel partners from 200 to 100 with the addition of “storing partners”  i.e.  Go To Market Optimization.  Markforged has an innovative Digital Forge Platform. This company has been ready to go !  
 
This is not only about disruptive technology, but also about business management and executing business plan.  It sounds crazy but I actually feel that investing Markforged is VERY CONSERVATIVE….   
 
Markforged :  24th Annual Needham Growth Conference 
https://wsw.com/webcast/needham116/markf/2421034 
 
$SPY $QQQ $IWM all weak now, so this would be a great chance to  buy the dip for long term investment.  Happy printing ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:02:26 </td>
   <td style="text-align:left;"> $SPY $QQQ By tomorrow morning people would realize how silly it is to sell stocks just based on one $NFLX earnings report lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:02:11 </td>
   <td style="text-align:left;"> $SPY $QQQ fed on next Wednesday big yikes… netflix down bad… next is apple amazon AMD nvda tesla📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:02:11 </td>
   <td style="text-align:left;"> $SPY @corruptmarket @OldFngGuy ..yikes! Anyone can make it look easy when the fed is printing an unprecedented amount of dollars and stimulus but anyone and everyone should have understood after a market up 30% and the fed pulling out and raising rates that this would occur. Maybe he was clear enough to his followers to not just blindly “buy the dip” but to understand a 7-11% correction was near and to wait for it. I have a feeling many of his followers blindly jumped in calls after every drop and got hit big $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:02:05 </td>
   <td style="text-align:left;"> $QQQ I will play puts at every rip your face off rally top, or nearto it, this is an opportunity that the millenials are shitting thier pants in ... after easy money from 2020 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:02:04 </td>
   <td style="text-align:left;"> $QQQ puts trade </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:01:52 </td>
   <td style="text-align:left;"> $QQQ Simulated Weekly $360.0 PUTS for Friday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:01:27 </td>
   <td style="text-align:left;"> $spy $qqq $soxl $fas $oih 
Nothing is gonna stop this market from crashing. It’s gonna continue to get bad bad bad. More crash coming. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:00:20 </td>
   <td style="text-align:left;"> More evidence that the bull is coming to its execution. $QQQ $TSLA $IWM $DIA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:00:04 </td>
   <td style="text-align:left;"> $QQQ Sell sell sell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 09:00:02 </td>
   <td style="text-align:left;"> $SPY $QQQ $NDX $DIA $SPX 

      🧞‍♂️ It’s Just Organic  🧞‍♂️

What you know about this rolling deep </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:59:38 </td>
   <td style="text-align:left;"> $QQQ $SPY  
Yellen sees path to slower inflation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:59:09 </td>
   <td style="text-align:left;"> $SPY $QQQ So who leaked $NFLX’s earnings/guidance in the final hour of trading today? Show yourself. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:58:54 </td>
   <td style="text-align:left;"> $SPY $QQQ everyone ready to be poor? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:58:48 </td>
   <td style="text-align:left;"> $QQQ where is bottom? If we see $350 the fucking whales are coming out of the woods for a ride in the spacex Amazon rocket ship </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:58:26 </td>
   <td style="text-align:left;"> $QQQ Cathie expects this to tank, uh oh bears lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:57:53 </td>
   <td style="text-align:left;"> Don’t forget about this. $QQQ $TSLA $SPY $IWM $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:56:14 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA AWWWWWWW LAWWWWWD YARRRRRRR BIGLY HIDE YO CANOES 🛶🛶🛶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:56:03 </td>
   <td style="text-align:left;"> $QQQ entering a bearish time not because of inflation but because of rate hikes and deflation that follows. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:55:24 </td>
   <td style="text-align:left;"> $QQQ futures ripping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:55:05 </td>
   <td style="text-align:left;"> $SOFI think this is bad, wait until we see 20% down on $QQQ!!! sub-10 then!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:55:00 </td>
   <td style="text-align:left;"> The technical rating of $QQQ is bad and it also does not present a quality setup at the moment. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:54:47 </td>
   <td style="text-align:left;"> $SPY $QQQ 

10 years 1.77 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:54:24 </td>
   <td style="text-align:left;"> $SPY rotate into biotech!!! $NASDAQ $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:54:10 </td>
   <td style="text-align:left;"> $QQQ buy the fuckin doink st $350 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:53:46 </td>
   <td style="text-align:left;"> We finally got the breakdown below $209 that we have been looking for in the small cap index on the 1 year {P&amp;amp;F} chart. Looks like the bull market is finally over folks. Good luck everyone. $IWM $QQQ $SPY $DIA $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:53:38 </td>
   <td style="text-align:left;"> $QQQ inflation is fake news. We will be deflating before the first rate hike even comes. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:53:16 </td>
   <td style="text-align:left;"> $QQQ who’s excited for Brandon next 3 years?????!!!!! FJBLGB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:52:51 </td>
   <td style="text-align:left;"> $QQQ Why would everyone think that NFLX, is to blame for this drop.
ER was released after market close.
The rest of the day was fine up until the last hour. I&amp;#39;m just surprised some bs headline wasn&amp;#39;t released. Too much uncertainty here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:52:39 </td>
   <td style="text-align:left;"> Here&amp;#39;s what makes our software shine like no other: Monthly Hedge Pressure. I tweeted about it this morning. What it shows is that if 455 is broken from above, it&amp;#39;s a gamma squeeze/crash. Worse: opening below it tomorrow + rejecting it there is no support until 431. This makes me very nervous. 
 
$SPY $ES_F latex13d7887da681233a7fa6c2e0e77f60f4CSX ▽ -2.04%      
$NVDA ▽ -2.02% 
     
Learn more: https://www.finscreener.org/screener/stock-screener </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:51:23 </td>
   <td style="text-align:left;"> $QQQ $FUBO $ROKU Start trading over 5 month ago and i lost all of money, Now I&amp;#39;ve made over 147K+ profits after join their chat room and using their alerts.  
Highly recommended! It&amp;#39;s free joining! discord.io/fBGVa29wnf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:50:21 </td>
   <td style="text-align:left;"> “Retail investor net sold $53mm, with $400mm coming in the last 2 hours. This is notable as it is the first time retail investors have net sold since December 6th ..  Since 12/6, the retail investor had been net buying, on average, more than $800mm per day”
— JPM Quant desk 

$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:50:17 </td>
   <td style="text-align:left;"> $QQQ 3 questions to ask 1- what’s markets response to Russian invasion, 2 what does interest rate hike do, it’s coming 4-6. 3 is the tapering complete (I don’t think it’s completely done) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:50:11 </td>
   <td style="text-align:left;"> $SOFI $QQQ 

Gainz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:49:54 </td>
   <td style="text-align:left;"> $QQQ 10 year yield goes up market panics and sells off every tech growth out there. 10 year goes down a lot market still selling off same stocks. It tells us some scum bags rich players are working together to cause this on ordinary people. You need to stop selling your tech growth stocks every time these suckers come at you with their narratives </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:49:46 </td>
   <td style="text-align:left;"> $QQQ FED members too busy selling thier shares they are panicking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:49:25 </td>
   <td style="text-align:left;"> Today $QQQ shows SELL signal (TA) for short term. Technical analysis source: https://stockinvest.us/stock/QQQ?utm_source=stocktwits&amp;amp;utm_medium=autopost </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:49:11 </td>
   <td style="text-align:left;"> $SPY $QQQ A bloodbath, but I&amp;#39;d be genuinely surprised if we didn&amp;#39;t see a bounce tomorrow. The /ES sits just above the 200ma on the Daily, and the /NQ sits right at its 50ma on the weekly. Two fairly critical supports. 
 
Ooooorrrr maybe we&amp;#39;ll just continue into the abyss because stock market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:49:01 </td>
   <td style="text-align:left;"> $QQQ tomorrow open 380 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:48:28 </td>
   <td style="text-align:left;"> $SPY $QQQ if you don’t trade futures tonight good luck forcing gains tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:48:22 </td>
   <td style="text-align:left;"> $QQQ futures not looking good adding more tomorrow $SQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:46:25 </td>
   <td style="text-align:left;"> The difference between dot com bubble and today’s market is back in 1999 there was only stock bubble, now it’s crypto, housing, equity, NFTs etc. Eventually every bubble bursts. $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:45:44 </td>
   <td style="text-align:left;"> SweepCast alerted: $QQQ with Unusual Options Activity Alerted on $369 CALL Expiring: 01-28-2022 worth 60K🐂 |🥇 Check out SweepCast.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:45:35 </td>
   <td style="text-align:left;"> $QQQ Sprung bull traps three days in a row and closed at the low again. Let&amp;#39;s see what Friday brings. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:43:25 </td>
   <td style="text-align:left;"> $SPY markets will recover tomorrow. But next week is a question? $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:42:54 </td>
   <td style="text-align:left;"> $SPY $QQQ how to spell capitalism…

W-E-A-L-T-H-F-A-R-E

- Jerome Powell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:42:54 </td>
   <td style="text-align:left;"> $QQQ $240 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:42:02 </td>
   <td style="text-align:left;"> $QQQ the blue effect baby </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:41:36 </td>
   <td style="text-align:left;"> $QQQ Out of control </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:41:16 </td>
   <td style="text-align:left;"> $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:40:52 </td>
   <td style="text-align:left;"> $AMD Bulls Chasing AMD Breakout can be very Dangerous to your Capital.  Consequently leaving you with 💼 Bags. 
This bad buying stocks at the wrong time results in losing money .
$AAPL $QQQ $NVDA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:40:07 </td>
   <td style="text-align:left;"> $xbi $spy $qqq $amzn $aapl dems and GOP both hate big tech. At least they agree on something. Dr J streams live tomorrow at 11:30 on YouTube. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:39:24 </td>
   <td style="text-align:left;"> Jan 20, 2022: Market fake out led to reversal of gains and a sharp drop for stocks across the board. Consumer discretionary hardest hit, down 2% on the day. Price action likely to continue volatility into tomorrow to close out the week. $SPY $QQQ $DIA $XLY $XLU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:39:24 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL 

Think what will happen when apple breaks the almighty 50MA at $160 lol 🤪🤪🤣🤣

Slippery slope on spy 430, 410 ??? 
QQQ 330, 300???? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:39:03 </td>
   <td style="text-align:left;"> $QQQ sleep with one eye open tonight.  Hope you all have stops </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:38:56 </td>
   <td style="text-align:left;"> $SPY $QQQ Already dropping hard before the exchanges officially close hasn&amp;#39;t been like this in a while. Another major drop coming before premarket. $4400 open </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:37:29 </td>
   <td style="text-align:left;"> $QQQ does inflation mean we spend a couple months down here like trade war/covid, or do we V back up like usual? beyond me. 
 
2018 midterm year pattern copied to 2022 as a roadmap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:36:58 </td>
   <td style="text-align:left;"> $NFLX $PTON $SPY $QQQ Are you going to buy this dip? YA RIGHT! https://youtu.be/QLZlNnqXwEU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:36:18 </td>
   <td style="text-align:left;"> $NVDA Correction in full force! 20%? 40%? $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:35:42 </td>
   <td style="text-align:left;"> November 2020 to February 2021 feels like 10 years ago. It was so easy. So fun.   
$QQQ $SPY $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:34:02 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:33:57 </td>
   <td style="text-align:left;"> $SPY $QQQ  anyone read this before </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:33:41 </td>
   <td style="text-align:left;"> $QQQ $SPY $ARKK $SOFI https://youtu.be/JZNuDK9-ejg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:33:35 </td>
   <td style="text-align:left;"> $QQQ how many points will nflx contribute for the drop today!?🙈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:33:15 </td>
   <td style="text-align:left;"> Charts and data coming later tonight folks

Was busy enjoying the 🌞 playing an epic 3 setter 🎾 

Now off to get mildly drunk

Life is good

$SPY $QQQ $BTC.X $GDX $AMD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:33:05 </td>
   <td style="text-align:left;"> $SPY $QQQ puts... end of story. Lots of panic. It is all over guys.  Stock markets to 0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:31:57 </td>
   <td style="text-align:left;"> $ARKK $QQQ $SPY $SPY  $AMC 
What if someone created a Market where only individuals could invest (No Hedgies)
No shorting, only buying and selling
No options and no margin. 
No companies with stock options 

Just a place to invest your money in companies you believe in and want to be a part of (kinda like the Green Bay packers). 

If Crypto can exist, why can’t this? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:31:39 </td>
   <td style="text-align:left;"> $DOY $QQQ $USO Failed breakout on the Daily in crude. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:31:36 </td>
   <td style="text-align:left;"> $QQQ If 358 doesn&amp;#39;t hold we may be looking at a market crash </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:31:26 </td>
   <td style="text-align:left;"> $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:30:36 </td>
   <td style="text-align:left;"> $QQQ , 340 should be a bottom area </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:30:25 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Last time Nasdaq entered in correction zone was March 8th,2021. It stayed there overnight &amp;amp; came back in bull market from next day. 

History repeats itself. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:29:50 </td>
   <td style="text-align:left;"> $SPY $QQQ Cramer says buy guys. He has been saying bottom and buy the past 2 weeks. Then goes in the morning and says sell everything. Then promotes Etherium on the street. People are evil. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:29:08 </td>
   <td style="text-align:left;"> $QQQ $SPY $RUA yields go up 1-3%=crater growth stocks and significant sell off in blue chip tech stocks, yields drop 5.5%=an even bigger selloff 🤣 even the “fundamental” based selling is irrational. Why on earth are people bending over to get assfucked by hedge funds? I would call it rape, but it’s consensual rape… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:27:51 </td>
   <td style="text-align:left;"> $QQQ Biden has finally accepted he&amp;#39;s not getting re-elected. This is the F YOU to everyone from the puppet in the ivory tower </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:27:25 </td>
   <td style="text-align:left;"> $QQQ 6 month lows </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:26:38 </td>
   <td style="text-align:left;"> $COMPQ $IWM $QQQ $SPY Despite the carnage in the underlings, $VIX has yet to test the December highs. Implies more liquidation coming our way. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:26:36 </td>
   <td style="text-align:left;"> Nasdaq 100 futures fall after Netflix’s earnings disappoint

$ND_F $NFLX $QQQ

https://www.cnbc.com/2022/01/20/stock-market-futures-open-to-close-news.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:26:22 </td>
   <td style="text-align:left;"> $QQQ I want to see Cramer and CNBC crying over 5 stocks tomorrow while the entire 90% broader market short squuzes to hell for loosing 80% on year and back in 2017. I want to see chasing, tears, and bridges lined up with suits and a megaphone on saying when to jump. But that&amp;#39;s just me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:25:43 </td>
   <td style="text-align:left;"> Biden Vs. Trump: How Did Stock Market Returns Compare After Their First Year As President?

$SPX $SPY $DJIA $QQQ

https://m.benzinga.com/article/25137004 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:25:28 </td>
   <td style="text-align:left;"> $SKLZ fed will see whats happening to the markets. Nasdaq in severe correction. Dow and sp not far behind. All in 3 weeks. The fed knows they can’t just crash for the sake of rates and they dont want to through interest on their 9 trillion. Inflation is real but a portion for sure is supply. Like in cars and building materials. That can turn around quick and i think will. 

2 rate hikes early this year and thats it. 

Bond market should fall. People need to get a grip on reality. Interest going from basically zero to a touch more is still a discount. Wake up. 

$arkk $dow $qqq $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:25:17 </td>
   <td style="text-align:left;"> $QQQ interesting divergence between tech and 10Yr bond yields. 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:24:37 </td>
   <td style="text-align:left;"> $QQQ they scare u first, they enter at low and made you to chase later </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:24:35 </td>
   <td style="text-align:left;"> $QQQ who is QQQing tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:23:45 </td>
   <td style="text-align:left;"> $SPY $QQQ red to green tomorrow morning. . Patience folks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:23:39 </td>
   <td style="text-align:left;"> $QQQ. Look chucko nflx missing estimates caused a 3% correction intraday. After 4 down days . sure drop 7% at open good bet. All aboard the grreat idea </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:23:28 </td>
   <td style="text-align:left;"> $BTC.X $SPY $QQQ $IWM $DWAC Biden needs to call a real President to solve this!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:22:59 </td>
   <td style="text-align:left;"> $BTC.X $SPY $QQQ 

I wonder if there will ever be a day when we can just give the largest middle finger to China and Russia…a day where we manufacture our own products. 

It’s wishful thinking but I don’t understand how we will move forward otherwise… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:20:59 </td>
   <td style="text-align:left;"> $QQQ  $SPY below the 200 dma.  Not good.  Let&amp;#39;s see how the mkt shakes out next week with Big Tech eps on deck.  Buckle up - keep some powder dry to buy.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:20:08 </td>
   <td style="text-align:left;"> $QQQ $SPY Putin invading this weekend or on the New Moon on Feb 1? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:19:27 </td>
   <td style="text-align:left;"> $SPY $SRNE $QQQ this week has been straight Bedlam.  Absolutely insane.  Been quite the sight to see </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:19:22 </td>
   <td style="text-align:left;"> $QQQ 358… holy shit. Houston we have a problem. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:18:58 </td>
   <td style="text-align:left;"> $PLTR https://seekingalpha.com/article/4480316-palantir-big-short-squeeze $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:18:46 </td>
   <td style="text-align:left;"> $SOXL 42.5 and $SMH 269. xx look interesting. $SPY and $QQQ reversal  is prob more relevant tho </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:18:17 </td>
   <td style="text-align:left;"> $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:18:10 </td>
   <td style="text-align:left;"> $QQQ $TNX $SPY $IWM : Without fail ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:18:07 </td>
   <td style="text-align:left;"> $QQQ I really need a +3.63% day tomorrow……. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:17:56 </td>
   <td style="text-align:left;"> $SPY Wow...this looks like a &amp;quot;recession levels.&amp;quot;  It looks like the market is pricing in a recession. 
 
https://twitter.com/ElkanTrades/status/1484218482145181698?s=20 
 
$QQQ $FB $AAPL $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:17:48 </td>
   <td style="text-align:left;"> $COIN no matter how good you think the idea is, loss mitigation is key. Being DEFIANT and posting im not selling gifs aint gonna keep yo brokeass from losing more. 

$spy $nflx $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:17:42 </td>
   <td style="text-align:left;"> $SPY $QQQ ger ready for big pump tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:16:45 </td>
   <td style="text-align:left;"> $SPY  $QQQ $IWM with the mid-term elections around the corner.. seems like bot / fake accounts are just taking over .. @Stocktwits  @StocktwitsHelp  so are you guys gonna do something about it or we&amp;#39;re going to be subjected to propaganda for the next 10 months? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:16:31 </td>
   <td style="text-align:left;"> $QQQ Cramer saying buy Netflix! Fuck you. Buy $NIO and the rest of the hyper growth stocks down 60% on year while your 5 piece of shit stocks pumped to ridiculous valuations and we in 2017. Let th suits chase the rotation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:16:27 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA ABANDON HOPE MOVE UNDER A BRIDGE 🥤🐻🍿 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:15:57 </td>
   <td style="text-align:left;"> $QQQ guess who&amp;#39;s back...back again...brandon&amp;#39;s back, fuck a friend. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:15:49 </td>
   <td style="text-align:left;"> $SPY green tomorrow $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:15:46 </td>
   <td style="text-align:left;"> $QQQ $SPY it’s looking like we might get the next leg up on the 3 support line  . Because the 8 EMA line looks like it will cross the 200 EmA for the first time since March 2020 which I’m thinking might drag it lower 😩 . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:15:42 </td>
   <td style="text-align:left;"> $QQQ 340 then 325 by March 19, 2022 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:15:02 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

Short any pop you see across the board tomorrow bears, it’s time we lock this market down and make it our playground like it’s 1929. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:14:58 </td>
   <td style="text-align:left;"> $QQQ $SPY 
 
I will say this ....behind all this pain lies an opportunity.  
 
When that opportunity comes, you just need to be ready.  
 
Unfortunately, 2021 scarred enough people that may not really know what to do in 2022. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:14:57 </td>
   <td style="text-align:left;"> $QQQ stock analysis based on today&amp;#39;s closing price. Full analysis is available on youtube at 

https://youtu.be/EUeUT3PWka0

Here is snapshot of $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:14:47 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ 
When your puts printed again❗ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:14:33 </td>
   <td style="text-align:left;"> $SPY $QQQ who snatched calls before close? I positioned the size for a final correction tomorrow. RSI is 30 on both we know that doesn&amp;#39;t last long, final correction tomorrow or bounces within the next few sessions. If you missed calls before close you may have an opportunity tomorrow at open. Wishing all the best! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:14:30 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures are green right now to give you hope, as soon as after hours trading closes they&amp;#39;re going right back into the dumpster 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:14:15 </td>
   <td style="text-align:left;"> $SPY $QQQ I mean there’s no way tech can recover tomorrow after Netflix....absolutely not a chance in hell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:14:11 </td>
   <td style="text-align:left;"> $QQQ this is it. Down she goes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:14:09 </td>
   <td style="text-align:left;"> $QQQ this should be down 3% AH. That Netflix report was an absolute nuke to what is about to happen due to inflation. Idk how people don’t see it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:13:06 </td>
   <td style="text-align:left;"> $SPY $QQQ  you in the morning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:11:58 </td>
   <td style="text-align:left;"> $SPY $QQQ if we somehow gap up, short with every penny you have </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:11:20 </td>
   <td style="text-align:left;"> $QQQ The weeks ahead are going to be bloody.  I&amp;#39;m getting ready for a repeat of March 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:10:57 </td>
   <td style="text-align:left;"> $SPY $QQQ 

Stretched down more than enough in very short time. 

Very risky to be a short for tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:10:44 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ 
There is no catalyst or news tomorrow that will save the market. $NFLX and $DIS missing earnings is just more fuel to the fire. Don&amp;#39;t be a retarded Bull and buy puts. 🤷‍♂️🤷‍♂️🤷‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:10:01 </td>
   <td style="text-align:left;"> $QQQ $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:08:59 </td>
   <td style="text-align:left;"> Today&amp;#39;s sell off triggered a bunch of oversold price &amp;amp; breadth signals that have been great entries during this bull market. $NDX $QQQ here in the chart with some of the mentioned signals. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:08:41 </td>
   <td style="text-align:left;"> $SPY ……..This will be a major correction, regardless of the smokescreen BS you are seeing on CNBC. 

They told you to buy, when they were selling. Enough said!

$QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:08:19 </td>
   <td style="text-align:left;"> $QQQ due for a red to 2+% green session tomorrow? Exactly opposite of today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:08:08 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA okay 1 more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:08:07 </td>
   <td style="text-align:left;"> $QQQ got damn it just get the bear market over with </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:07:20 </td>
   <td style="text-align:left;"> $UVXY $QQQ $SPY The respected #Senators and #Fed have cashed out, ladies and gentlemen.. this is not over </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:07:12 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $BTC.X This country needs a savior!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:06:24 </td>
   <td style="text-align:left;"> $QQQ 

Problem is people like Jamie Dimon stating there will be 7 or 8 rate hikes this year. We all know this government funded economy and runaway inflation cannot support it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:05:56 </td>
   <td style="text-align:left;"> $ROKU $QQQ $NFLX $SPY $ARKK https://www.cnbc.com/2022/01/20/netflix-quietly-admits-streaming-competition-is-eating-into-growth.html  Roku earring away NFLX lunch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:05:50 </td>
   <td style="text-align:left;"> $DIA $SPY $QQQ  lets go Brandon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:05:33 </td>
   <td style="text-align:left;"> $SPY I hope other options traders can relate. $TSLA $NFLX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:05:08 </td>
   <td style="text-align:left;"> $SPY latex80958e9a2107f9fd319c1ed3b1c90516QQQ  
$XBI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:04:09 </td>
   <td style="text-align:left;"> $QQQ $spy  
 
I AM A DEDICATED FED HEAD  
 
Jpow gonna wreck puts soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:03:56 </td>
   <td style="text-align:left;"> $SPY $QQQ 
 
For the first time in a long time I had to switch my stance.  
 
For now - we&amp;#39;re on defensive mode till further notice.  
 
Hopefully not for long. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:03:34 </td>
   <td style="text-align:left;"> $QQQ hey guys, I ran out of lube.. any one got some spare for tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:03:10 </td>
   <td style="text-align:left;"> $QQQ does lowering rates mean a bounce is coming $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:02:58 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM When we are in a bull market, buy the dips (as bull flag turns up) i.e:   sell at the  top of  a run. then wait for next dip to buy 
 
In a bear market the reverse, short at the top of the rally  cover at the bottom of  the  sustained move down. 
 
The rips up in bull market  are great, the pullbacks are just the market taking a breath.  
 
In a bear market, the rallies are short and weak, followed by a bigger move down. 
 
This is what we just had happen and caught the traders still thinking it&amp;#39;s a bull market  buying the dip in (a bear trap). 
 
If you want to do well you have to reverse your mindset and be nimble as we pivot from one market to the other and not let the previous trend dictate your strategy. There obviously more to it like rotating from growth to  value but you get my drift. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:02:27 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-01-20 Trade Analysis Video: 
https://www.youtube.com/watch?v=XF7dwkpHpzg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:01:38 </td>
   <td style="text-align:left;"> $QQQ https://www.reuters.com/world/middle-east/russia-ukraine-warm-turkey-helping-ease-tensions-turkish-sources-2022-01-20/?taid=61e9f661eaf39e00015f4061&amp;amp;utm_campaign=trueAnthem:+Trending+Content&amp;amp;utm_medium=trueAnthem&amp;amp;utm_source=twitter </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:01:16 </td>
   <td style="text-align:left;"> $QQQ  
 
Whales bought the dip in tech today and they will def load the dip on Netflix tomorrow imo 
 
Market needs a true catalyst to drop this hard and we didn&amp;#39;t really get it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:01:13 </td>
   <td style="text-align:left;"> $QQQ undoubtedly headed back into the exponential channel where it has remained within since the Great Recession. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 08:01:00 </td>
   <td style="text-align:left;"> $QQQ Yer killing it hoser. 2 mofe years, oH YaY! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:59:52 </td>
   <td style="text-align:left;"> $SPY $QQQ Drop the $4400 before any possible bounce back up. Target latex491eed48168116d5c0b51508ab0e4537UVXY  
$NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:57:51 </td>
   <td style="text-align:left;"> $QQQ Watching my puts print is a delight. Thanks suckers!! 🍌💦 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:56:10 </td>
   <td style="text-align:left;"> Some folks here could stand to read this: “The main thing that I learned about conspiracy theory, is that conspiracy theorists believe in a conspiracy because that is more comforting. The truth of the world is that it is actually chaotic. The truth is that it is not The Iluminati, or The Jewish Banking Conspiracy, or the Gray Alien Theory. 

The truth is far more frightening - Nobody is in control.” -Alan Moore

The world is rudderless.” $SPY $DWAC $QQQ $PTON </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:55:35 </td>
   <td style="text-align:left;"> Btw, it&amp;#39;s possible we see some culling in some of these beaten down tech IPOs. We saw that in Dot Com v1.0, and we&amp;#39;ll probably see it in Dot Com v2.0 as well. 
 
Hopefully on the other end, fewer, but stronger companies emerge. 
 
$QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:55:27 </td>
   <td style="text-align:left;"> $QQQ $SPY $NFLX yup load up folks enjoy those losses while you can 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:55:07 </td>
   <td style="text-align:left;"> $QQQ hahaha, YUSSSSSSS! Bought $380 puts when this was $410. The market is tanking almost as fast as Joe&amp;#39;s approval rating. Don&amp;#39;t blame me. I voted for Trump and saw the artificially inflated market. The wise get richer. Don&amp;#39;t worry Biden Voters, I&amp;#39;m sure they&amp;#39;ll expand the welfare program and you&amp;#39;ll all be on UBI. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:53:45 </td>
   <td style="text-align:left;"> $SPY $QQQ  Let&amp;#39;s talk the market crash 
https://youtu.be/YNeNukwPAkc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:53:43 </td>
   <td style="text-align:left;"> $QQQ $SPY 

Put holders and shorts! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:53:42 </td>
   <td style="text-align:left;"> $SPY $QQQ $NFLX $PTON $CLSK 

This market is a total 🤡 show. 
Who is to blame for this? 
How do we make consistent money? 

I’m not going short, but god damn is staying long hurting. 

Where is everyone “buying the dip”? 
Where is the “rebound”? 

F*** </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:53:16 </td>
   <td style="text-align:left;"> $QQQ is this all from Dems? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:52:23 </td>
   <td style="text-align:left;"> $QQQ BURN IT ALL DOWN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:52:03 </td>
   <td style="text-align:left;"> $NNDM I bet all those blue chip $QQQ flow into growth </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:51:52 </td>
   <td style="text-align:left;"> $QQQ $SPY $NFLX $DOCU $SQ nasdaq ki maa chod dee gayee hai……  ab behen ki baari hai :-( </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:51:29 </td>
   <td style="text-align:left;"> Hi Traders! New market analysis video has been uploaded. You can find it here - https://www.youtube.com/watch?v=lPgKbqEUgUw Stay green my friends! #trading #stockmarket #options #trader $SPX $SPY $QQQ $VIX $GLD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:51:24 </td>
   <td style="text-align:left;"> $SPY This selloff is identical to the beginning of 2008 
$QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:50:37 </td>
   <td style="text-align:left;"> $QQQ the fed just shaved trillions from bond and stock markets. Any further sell off will cause hard recession. So they will pause. It will stabilize. Chillax </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:50:36 </td>
   <td style="text-align:left;"> $SPY Bounce tomorrow?  
 
I bought a $QQQ call at close. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:49:30 </td>
   <td style="text-align:left;"> $NQ_F $QQQ futures not looking good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:49:04 </td>
   <td style="text-align:left;"> $QQQ I heard there is a difference between a correction and a crash.  The small and mid caps are already down 50-80% so what is it then? $SPY $IWN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:48:35 </td>
   <td style="text-align:left;"> $QQQ $SPY cramer is a clown once your account is near zero he’ll tell you that he was wrong and should have sat on the sidelines </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:48:21 </td>
   <td style="text-align:left;"> $IWM $QQQ $SPY $TSLA Curious why stocks always seem to be dumped at the same time? Or why fundamentals haven&amp;#39;t matched valuations in 3 years? Or why volatility in the markets keeps increasing? 
 
Algorithmic trading needs to be slowed down. Retail investors are being hurt. 
 
https://youtu.be/FKh1kK6M9Yw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:48:19 </td>
   <td style="text-align:left;"> $DIA $QQQ $SPY and to think.... we havent even gotten to the ugly part yet. 😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:48:18 </td>
   <td style="text-align:left;"> $QQQ $SPY the inexperienced trader has had to have gotten their ass handed to them today. I expected a pullback but nothing like we saw today. Prolly go further tomorrow  guess I be in bear mode til we recover. Good luck all!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:47:25 </td>
   <td style="text-align:left;"> $SPY $QQQ $PLTN 
My vote for joke post of the day. ✔️👌👍🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:47:14 </td>
   <td style="text-align:left;"> $QQQ Is now a value stock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:46:40 </td>
   <td style="text-align:left;"> Today $QQQ shows SELL signal (TA) for short term. Technical analysis source: https://stockinvest.us/stock/QQQ?utm_source=stocktwits&amp;amp;utm_medium=autopost </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:46:40 </td>
   <td style="text-align:left;"> $QQQ If I need to lose 45% of my already 40% loss on stocks just to make the average American see, that voting for Biden/Harris was the worst thing to do. I&amp;#39;m happy to lose it all.

You guys never should have voted away a pure business man and a realist. The orange guy wasn&amp;#39;t so bad eh? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:46:22 </td>
   <td style="text-align:left;"> $SPY $QQQ $TLT $UUP

Daily Market Recap for Thursday 1/20/2022 for #Stocks #Bitcoin #Gold and #Silver
https://youtu.be/YhWopXB1DkI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:46:00 </td>
   <td style="text-align:left;"> $SPY $QQQ the bleeding will stop on Feb 3 when FAANG are done with earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:45:53 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA $IWM 

Will buy the gap down tomorrow. With leverage. Ready to lose 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:45:31 </td>
   <td style="text-align:left;"> $SPY $QQQ If tomorrow is another big red day then just buy a little bit again, we might need to hear from the FED next Wednesday before this market bottoming out and heading higher for rest of the year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:44:52 </td>
   <td style="text-align:left;"> $QQQ buckle up!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:44:28 </td>
   <td style="text-align:left;"> $NFLX Guys, I got a $390 strike Put expiring tomorrow for $25. How much do you think I will profit on this move down if it’s near $390 tomorrow morning? I remember seeing someone make 100k percent on a same day option. $SPY $QQQ $DIS $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:44:19 </td>
   <td style="text-align:left;"> $QQQ $SPY dont let yields make you buy. Yields also drop when market corrects </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:44:03 </td>
   <td style="text-align:left;"> $MNMD super bullish here. Psychedelics are the future of mental health medicine. I’m a buyer at any price $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:43:47 </td>
   <td style="text-align:left;"> $SPY $QQQ LOL! What the F wrong with Pajama traders. Are they trying to rally Futures again like yesterday?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:43:37 </td>
   <td style="text-align:left;"> $QQQ  Intraday reversal leads to further selling in large cap tech stocks (QQQ -1.3%). Closed below 200 day MA.  #IBDPartner  
 
@InvestorsBusinessDaily @MarketSmith </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:42:55 </td>
   <td style="text-align:left;"> $SPY $QQQ I’ve said it all week and I’ll say it again…11:00am is the pivot point of the last three weeks. Whatever it does at 11:00 bet against it. Look at my trading posts. I buy around 11:00 and I sell at 3:58. This is too predictable. I turned $3000 into almost $12,000 in 3 days and posted it all in real time. Get you some! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:42:15 </td>
   <td style="text-align:left;"> $QQQ tomorrow 6+ down again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:42:02 </td>
   <td style="text-align:left;"> $QQQ Netflix was a precursor I think to what’s to come. Investors might panic sell so they don’t get destroyed at earnings. This week Might get a lot worse </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:41:36 </td>
   <td style="text-align:left;"> $QQQ $SPY started dropping hard when Biden Admin said they preparing for China Okincrom disruptions </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:40:55 </td>
   <td style="text-align:left;"> $QQQ interesting 10 yr yield falling fast </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:40:40 </td>
   <td style="text-align:left;"> $NVDA this will be sub 200 by time the trends change in $QQQ or $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:40:27 </td>
   <td style="text-align:left;"> $SPY $QQQ $DWAC one year in </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:40:14 </td>
   <td style="text-align:left;"> $QQQ $BTC.X $ETH.X Im torn between blaming Biden for the collapse or thanking Biden for the opportunity to buy the dip in a few weeks/months. Either way, I definitely wont take any personal responsibility for my choices unless the prove to be profitable, you can bet on that! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:40:14 </td>
   <td style="text-align:left;"> $QQQ while I wasn&amp;#39;t all the surprised we turned red today I also won&amp;#39;t be surprised if futes trun green by the open. Lots of fear brewing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:40:07 </td>
   <td style="text-align:left;"> $SPY

 &amp;quot;Bears get rare wins a few times lately&amp;quot; --some bull 

Get ready for &amp;quot;rare&amp;quot; a whole lot more.

#BearMarket

#Inflation

#TechWreck

$MSFT $AAPL $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:39:57 </td>
   <td style="text-align:left;"> $QQQ I don’t think people realise once this market corrects it’s not going to reach the COVID highs ever again. Where is the money going to come from? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:39:03 </td>
   <td style="text-align:left;"> $NDX $qqq $TQQQ looking for a bounce at some point
Will be driven by apple Fb msft googl amzn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:39:03 </td>
   <td style="text-align:left;"> $QQQ keep in perspective... on Jan 21st, the day after Joe was sworn into office, the price of QQQ was 325.15. It is now $358.58 in afterhours. This means we&amp;#39;re still up 10% in 1 year which is not bad. So yeah, it&amp;#39;s way down from the highs, but on a year over year basis, it&amp;#39;s still good. I do expect it to continue down though. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:39:02 </td>
   <td style="text-align:left;"> $QQQ well I thought we’d get a bounce that would be meaningful played a big straddle trade to perfection today proved exactly where this market is heading if your still a bull your in full denial </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:39:00 </td>
   <td style="text-align:left;"> $SPY  $QQQ $DIA There’s a time to long and a time to short .  If you’re caught on the wrong side , keep losses to a minimum if you want to survive these market conditions.  Trade smart! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:38:19 </td>
   <td style="text-align:left;"> $NQ_F Resting on the weekly  50 day moving average.  Needs to hold here.  $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:37:55 </td>
   <td style="text-align:left;"> $TQQQ $SPY $QQQ &amp;quot;We&amp;#39;ve made great progress&amp;quot; - End of Quote </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:37:30 </td>
   <td style="text-align:left;"> $QQQ $SPY 20% stocks and other assets, 40% cash, 40% real estate.

Bite me ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:37:21 </td>
   <td style="text-align:left;"> $QQQ $SPY for the most part everyone knows the market will correct besides some retards. But what will catch people off guard will be how far it will go. Everyone is expecting the 5-10% and most already think it’s over. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:37:08 </td>
   <td style="text-align:left;"> $SPY $QQQ I dunno about you but today was a rerun. I made $6439.90 today. No excuses on yet another rerun of the day before. This is all very predictable and repeatable. Recognize it for what it is and play the game. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:36:25 </td>
   <td style="text-align:left;"> $QQQ stock analysis based on today&amp;#39;s closing price 

https://youtu.be/EUeUT3PWka0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:36:22 </td>
   <td style="text-align:left;"> $QQQ tomorrow looks like a bloodbath. Who’s prepared to brave this storm. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:36:13 </td>
   <td style="text-align:left;"> $QQQ Don’t fight the Fed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:35:45 </td>
   <td style="text-align:left;"> $QQQ I bought 368C 1/21 at close… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:35:03 </td>
   <td style="text-align:left;"> $SPY $QQQ  the 10 year is just hella down now. Everything down. Doesn’t matter what just red </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:34:48 </td>
   <td style="text-align:left;"> $QQQ  $SPY  $NASDAQ  Well capitalized companies have gotta be thinking about buying high Beta growth on the cheap, in all industries I </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:34:01 </td>
   <td style="text-align:left;"> $QQQ shouldve bought those puts but i didnt want to sell and make a day trade cus of the pdt!! Couldve made my account so much bigger if pdt wasnt a thing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:33:57 </td>
   <td style="text-align:left;"> $PTON https://www.smarteranalyst.com/yahoo/peloton-stock-to-exit-nasdaq-100-on-jan-24/ Three days until $QQQ 100 expulsion </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:33:35 </td>
   <td style="text-align:left;"> Stocks Sink On January 20 As REAL Rates Rise Again https://mottcapitalmanagement.com/stocks-sink-on-january-20-as-real-rates-rise-again/ $amzn $nvda $nflx $spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:33:34 </td>
   <td style="text-align:left;"> $SPY $QQQ #GEX printed -7.5B, the lowest ever. #DIX didnt drop much and still at 43.5; Expect some huge volitility tomorrow. Negative GEX usually marks short term bottoms. While the trend looks bearish, expect a decent bounce soon, as early as next week. GL. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:33:21 </td>
   <td style="text-align:left;"> It is true that this crash could just have began…. Feels way more painful than it looks 
 
$spy $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:33:18 </td>
   <td style="text-align:left;"> $SPY don’t forget the theme of 2022 folks $QQQ 

Your crappy stocks go lower and your electric bill doubles </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:32:42 </td>
   <td style="text-align:left;"> $SPY HOLY GEX WOW

$QQQ $STUDY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:32:36 </td>
   <td style="text-align:left;"> $QQQ lots of margin calls hopefully we will soon see an end </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:32:36 </td>
   <td style="text-align:left;"> $SPY $QQQ Futures probably overreacting to the numbers from $NFLX, the market is way oversold and we should see a bounce tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:32:13 </td>
   <td style="text-align:left;"> $QQQ Sweet baby rays </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:31:38 </td>
   <td style="text-align:left;"> $QQQ confidence is everything in the markets. Clearly there’s no confidence in the economy if indexes fail to reclaim support levels…. Could be a negative market year and wipe out 2021 gains. Already almost half way there </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:31:17 </td>
   <td style="text-align:left;"> $spy $qqq $btc.x $dwac

Why did the market sell off at end of the day?

Biden open his mouth? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:30:14 </td>
   <td style="text-align:left;"> $QQQ  $SPY  $NASDAQ  which big bank will be the first to;start buying cheaper fintech ? And…..which fintech ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-21 07:29:53 </td>
   <td style="text-align:left;"> $QQQ calls paid nothing today even with the huge jump in the morning but the puts paid BIG the same day. Bears are making bank right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 09:35:01 </td>
   <td style="text-align:left;"> $AAPL earlier than I thought. lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 09:35:00 </td>
   <td style="text-align:left;"> $SPY puts all day tomorrow, US economy in shambles, no one is able to afford food, gas, utilities… we can’t even afford to buy clothes anymore. Everyone is getting laid off in tech, heard $AAPL sales are slowing dramatically similar to $NFLX. Vegas is empty af because of inflation and bond. $300 PT in two months </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 09:32:37 </td>
   <td style="text-align:left;"> $AAPL guess it’s about time to load the boat. Easy money when it’s on sale. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 09:31:05 </td>
   <td style="text-align:left;"> $AAPL can’t win without big buyers, question is what price they feel comfortable to get back in. They may think this can go lower. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 09:29:17 </td>
   <td style="text-align:left;"> $AAPL HarmonicSwings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 09:28:18 </td>
   <td style="text-align:left;"> $AAPL 150 tomorrow? Any chance? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 09:26:54 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 09:21:51 </td>
   <td style="text-align:left;"> Dark pool after hours activity in: 
 
$QQQ - $119M print 
$SPY - $367M print 
$AAPL - $337M print 
$EEM - $109M print 
 
#darkpool </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 09:21:30 </td>
   <td style="text-align:left;"> $AAPL PELOSI SOLD HER APPLE STOCK AT THE END OF DECEMBER. YOU ALL SHOULD HAVE FOLLOWED SUIT WITH THAT PIECE OF SHIT DEMOCRAT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 09:21:27 </td>
   <td style="text-align:left;"> Now this $nflx $aapl $tsla $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 09:20:58 </td>
   <td style="text-align:left;"> $AAPL ppl
Is getting scare .. time
To sell but smart ppl is buying these dip 😂 bet we see all time highs sooner or later </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 09:20:18 </td>
   <td style="text-align:left;"> $AAPL When this market goes down it&amp;#39;s going to be nasty! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 09:19:30 </td>
   <td style="text-align:left;"> $AAPL U.K. consumer confidence drops to nearly a year-low on inflation, omicron worries https://www.marketwatch.com/story/uk-consumer-confidence-drops-to-a-near-year-low-on-inflation-omicron-worries-271642723267?mod=mw_latestnews </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 09:19:24 </td>
   <td style="text-align:left;"> $AAPL 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 09:17:37 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 09:17:12 </td>
   <td style="text-align:left;"> $SPY $NFLX $AAPL $GOOG $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 09:15:49 </td>
   <td style="text-align:left;"> $AAPL everybody is bearish, I bet this bounces next week.imagine if aapl fell 20% like Netflix, sndp500 $SPY  Nasdaq would be decimated as well, we will be facing recession. Hopefully that does not happen, have seen how bad 2008 was and generation of graduates won’t find jobs for 3 years and their careers will be hampered. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 09:15:00 </td>
   <td style="text-align:left;"> $AAPL has a Return On Assets of 26.97%. This is amongst the best returns in the industry. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=fundamental-analysis&amp;amp;key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 09:14:53 </td>
   <td style="text-align:left;"> $AAPL There will be blood tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 09:14:07 </td>
   <td style="text-align:left;"> $AAPL    🍏: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 09:12:44 </td>
   <td style="text-align:left;"> $AAPL Wayy overdone! Congrats to the hegies and the manips. Just join the party </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 09:11:58 </td>
   <td style="text-align:left;"> latexc4b6ddb8ffd4be5f5e8df2878c32afcfNVDA goes lower with others 
$AAPL $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 09:09:22 </td>
   <td style="text-align:left;"> $AAPL I&amp;#39;d say there is still some downside left, but how much is the question. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 09:09:01 </td>
   <td style="text-align:left;"> $PTON My #1 buyout candidate for 2022 is $PTON
Peloton.
$PTON sells at just 2.5 x revenue which is extremely cheap for fit-tech  $LULU $AAPL $NKE are the likely buyers.
Peloton hired McKinsey to clean up their books for a sale imo.
PT $50 to $55 on a buyout. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 09:04:16 </td>
   <td style="text-align:left;"> $SPX $SPY $AMZN  $AAPL $TSLA From the beginning of 2020 rally this is the first biggest red candle in SPX. Do you think it will stop with just one red candle? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 09:03:58 </td>
   <td style="text-align:left;"> $AAPL $157.86 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 09:02:34 </td>
   <td style="text-align:left;"> $AAPL Simulated Weekly $160.0 PUTS for Friday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:57:17 </td>
   <td style="text-align:left;"> $AAPL NFLX down 102 aftermarket. Guess who’s next? 🍎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:52:34 </td>
   <td style="text-align:left;"> $AAPL come on $145 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:51:28 </td>
   <td style="text-align:left;"> $AAPL Called 165 all week long. Apple likely 160s to 162 tomorrow according  my chart unless..?@#$% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:50:20 </td>
   <td style="text-align:left;"> $AAPL $10 by end of march </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:50:05 </td>
   <td style="text-align:left;"> $AAPL pro tip…. sell covered calls and collect premium to lessen the blow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:49:54 </td>
   <td style="text-align:left;"> $AAPL 159 if Dow opens -500 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:47:31 </td>
   <td style="text-align:left;"> $AAPL 🚨 DEMOCRATS SUPPORT TURNING YOUR KID INTO A TRANSEXUAL. YOU SCUM BAGS VOTED FOR THIS WHEN YOU SELECTED JOEY BIDEN https://time.com/5909306/transhood-documentary-hbo/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:46:45 </td>
   <td style="text-align:left;"> $AAPL $SPY $MSFT $AMZN $TSLA 

&amp;quot;Apple shares are up 19% since the October 4 low (vs. 5% for the S&amp;amp;P 500) suggesting December quarter upside is largely priced in,&amp;quot; warned Morgan Stanley tech analyst Katy Huberty in a new research note Thursday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:44:00 </td>
   <td style="text-align:left;"> $AAPL $MSFT open the dam market I want more!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:43:44 </td>
   <td style="text-align:left;"> $AAPL honestly, i think even $nflx will not be below $400 tomorrow. This is overdone selling on little volume. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:40:52 </td>
   <td style="text-align:left;"> $AMD Bulls Chasing AMD Breakout can be very Dangerous to your Capital.  Consequently leaving you with 💼 Bags. 
This bad buying stocks at the wrong time results in losing money .
$AAPL $QQQ $NVDA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:40:45 </td>
   <td style="text-align:left;"> $AAPL DCA DCA 

Very important now more than ever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:40:26 </td>
   <td style="text-align:left;"> $AAPL Netflix losing market share … Apple must be taking some of its share $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:40:07 </td>
   <td style="text-align:left;"> $xbi $spy $qqq $amzn $aapl dems and GOP both hate big tech. At least they agree on something. Dr J streams live tomorrow at 11:30 on YouTube. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:39:24 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL 

Think what will happen when apple breaks the almighty 50MA at $160 lol 🤪🤪🤣🤣

Slippery slope on spy 430, 410 ??? 
QQQ 330, 300???? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:34:13 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $MARA $AMZN 

My thoughts on the mkt action today ... 

Did I call the exact top on the mkt intraday today? Just about. At 458 on the SPY I sent an email alert out to my members that I would sell the mkt as I still believe we are in a correction. A correction I believed predicted would occur to begin 2022 - and in which I posted here on ST (SEE BELOW). 

I mentioned yesterday on ST that the mkt wouldn&amp;#39;t put in a tradeable bottom until three things occurred - AAPL back to $160, TSLA closing back under $1000, and Bitcoin(MARA) going back under 40K.  We are getting close as Bitcoin is now pressing that 40K level, TSLA closed under $1000, and AAPL is falling to $160. 

The mkt does a really good job of trapping the most leaning one way. And as I warned yesterday on ST, the &amp;quot;dip buyers&amp;quot; who are new to trading the past couple of years are getting a painful lesson. 

My alerts go out daily. If interested, feel free to reach out at 

jessielivermore1929@gmail.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:34:04 </td>
   <td style="text-align:left;"> $SPY $AAPL $FB AMZN $NFLX The problem with America today, and the reason why most people can’t be successful in the market is we can’t admit when we are wrong… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:32:05 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-01-20 Technical Analysis Video: 
https://www.youtube.com/watch?v=2plaZHSr3ds </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:28:24 </td>
   <td style="text-align:left;"> $AAPL needs to open red by at least 1% for the puts not to get theta Burn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:28:03 </td>
   <td style="text-align:left;"> $AAPL stock analysis based on today&amp;#39;s closing price.  Full analysis is available on youtube 

https://youtu.be/-sf10f2v62E </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:24:07 </td>
   <td style="text-align:left;"> $AAPL In the recent reporting quarter: 23 institutions initiated a position, while 5 completely liquidated https://insider-analysis.com/search_whales.php?ticker=TABLE_AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:23:09 </td>
   <td style="text-align:left;"> $AAPL who tf doubts apple?? Wtf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:22:58 </td>
   <td style="text-align:left;"> $AAPL when the icar comes y’all gonna wish you bought </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:22:15 </td>
   <td style="text-align:left;"> $AAPL Perfect short  setup | SHORT Entry Alerted: $169.19  and then the Exit on alert at: $163.66 😁| Solid info for daily gains </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:19:42 </td>
   <td style="text-align:left;"> $AAPL  soon will do NFLX style 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:19:10 </td>
   <td style="text-align:left;"> $AAPL nasdaq futures inching higher </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:17:56 </td>
   <td style="text-align:left;"> $SPY Wow...this looks like a &amp;quot;recession levels.&amp;quot;  It looks like the market is pricing in a recession. 
 
https://twitter.com/ElkanTrades/status/1484218482145181698?s=20 
 
$QQQ $FB $AAPL $MSFT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:16:55 </td>
   <td style="text-align:left;"> $AAPL hasn’t even dropped that much. Will be fun to see that tidal wave on the market if it decides to join the party. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:15:02 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

Short any pop you see across the board tomorrow bears, it’s time we lock this market down and make it our playground like it’s 1929. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:14:34 </td>
   <td style="text-align:left;"> $AAPL $SPY not a Biden/Obama nor Trump fan here, but you do know why stock prices went up during Trump&amp;#39;s era, right? Trump cut the corporate tax and interest rates, pushing money into the market. market got fed and grew into a monster bubble! now the current administration has to raise interest rates , slow down the economy OR the people will DIE of INFLATION. you&amp;#39;re mistaken if you think Trump did a good job for you.. NO, he did help the HFs pump it. and now, Biden has to dump it to bagholders. hahaha goodluck with that! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:10:07 </td>
   <td style="text-align:left;"> $AAPL This is a great opportunity to buy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:07:10 </td>
   <td style="text-align:left;"> $AAPL Don’t let bears scare you into thinking the sky is falling. Market also ate shit early on last year. Now is the time to accumulate. 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:05:07 </td>
   <td style="text-align:left;"> $AAPL please tank more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:04:09 </td>
   <td style="text-align:left;"> $AAPL $MSFT $TSLA $UWA welcome to Joe Biden’s America where markets crash and he divides our country - only the beginning - good luck to all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:02:57 </td>
   <td style="text-align:left;"> $NFLX I can see $AAPL buy out for $700 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 08:01:37 </td>
   <td style="text-align:left;"> $AAPL buy the dip tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:59:01 </td>
   <td style="text-align:left;"> $AMZN $AAPL $TSLA $SPY $BA ??? Yes we do dad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:57:57 </td>
   <td style="text-align:left;"> 5 Blue-Chip Stocks Likely to Gain on Earnings Next Week. $BA $AAPL $CVX $CAT $AXP https://www.zacks.com/stock/news/1854482/5-blue-chip-stocks-likely-to-gain-on-earnings-next-week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:56:50 </td>
   <td style="text-align:left;"> $AAPL 

Anyone see that? Went green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:55:27 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #2 ticker with sweep activity where institutions are trading options urgently with 53.5K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:55:22 </td>
   <td style="text-align:left;"> $SPY $AMZN $FB $AAPL The Great Depression began in 1929… 10 years after the Spanish flu… I can imagine how it slid in the 10 years after that pandemic… will never happen (hopefully) but interesting to think of and fingers crossed we don’t see history repeat itself for our own kids sake </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:55:13 </td>
   <td style="text-align:left;"> $AAPL weekly looks  doom though </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:54:47 </td>
   <td style="text-align:left;"> $AAPL buy the dip .. if u short the dip that’s high risk lol 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:53:59 </td>
   <td style="text-align:left;"> $AAPL if price is low enough should buy $NFLX $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:51:07 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : The first big tech antitrust bill lumbers toward reality https://www.stck.pro/news/AAPL/21666777 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:47:41 </td>
   <td style="text-align:left;"> $AAPL buy the dip .. and it keep dipping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:47:32 </td>
   <td style="text-align:left;"> $AAPL that’s a big dip .. loading calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:45:40 </td>
   <td style="text-align:left;"> $AAPL watch put lock there gains tomrrow 😂, can’t blame them it’s be up 500% + for some of y’all . I will be there to load calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:45:31 </td>
   <td style="text-align:left;"> $AAPL those puts printed today. sold half! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:42:16 </td>
   <td style="text-align:left;"> $AAPL   FUCK....... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:40:07 </td>
   <td style="text-align:left;"> $SPY

 &amp;quot;Bears get rare wins a few times lately&amp;quot; --some bull 

Get ready for &amp;quot;rare&amp;quot; a whole lot more.

#BearMarket

#Inflation

#TechWreck

$MSFT $AAPL $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:38:36 </td>
   <td style="text-align:left;"> $AAPL are we entering a long term bear market? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:38:29 </td>
   <td style="text-align:left;"> $SPY  Yellen on tmr. She is a shill. Don&amp;#39;t trust anything she says. She takes money to show up and say what others pay her to. Becareful $TSLA $AAPL $MSFT $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:37:14 </td>
   <td style="text-align:left;"> $AAPL are futes ripping yet. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:35:33 </td>
   <td style="text-align:left;"> $VIAC 6.3x pe !!!! Cmon $AAPL or $CMCSA or $SONY is buying  Viacom out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:35:05 </td>
   <td style="text-align:left;"> $AAPL heading to 125 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:32:09 </td>
   <td style="text-align:left;"> $AAPL technical analysis for tomorrow. 
 
https://youtu.be/YKzM7YxvNCk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:31:40 </td>
   <td style="text-align:left;"> $BTC.X so crypto &amp;amp; stocks $aapl $msft all moving down while small &amp;amp; mid caps getting shorted to oblivion all by Tutes &amp;amp; HFs lol but there&amp;#39;s no evidence of collusion </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:30:37 </td>
   <td style="text-align:left;"> $AAPL $CRM $AMZN $NVDA depressing… at least Netflix set the bar low. Added and entered, hoping for a bottom soon and settling of this market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:26:34 </td>
   <td style="text-align:left;"> $AAPL this will be up Monday, buy the dip tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:25:12 </td>
   <td style="text-align:left;"> $AAPL 

Woo hoo I expect the quicker recovery soon !! Expect relief rally soon on Feb! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:24:46 </td>
   <td style="text-align:left;"> $SAVA Don&amp;#39;t expect any PR from Remi.  With the SEC reviewing all his shenanigans for the past 6 months he knows to keep quite.  Besides he made 10s of millions off investors, probably invested in $AAPL or $MFST in his hidden account in the Bahamas worth  a lot more than more than everyone on this channel  have lost. 
 
What a great guy, fuckin scammer, yeah Elon?  wouldn&amp;#39;t let him wash toilets. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:23:59 </td>
   <td style="text-align:left;"> $NFLX this dropped $100 on one earnings.  This is like $AMZN dropping $1000 in 30 minutes.  Isn&amp;#39;t this by definition a market crash?  $SPY $AAPL $GOOG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:23:18 </td>
   <td style="text-align:left;"> $AAPL Miracle Mile Advisors, Llc increased their holdings by 2,410%, one of the largest institutional increases this quarter https://insider-analysis.com/search_whales.php?ticker=TABLE_AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:22:40 </td>
   <td style="text-align:left;"> $AAPL If you think apple is going to miss because of Netflix your truly Brain dead. Apple will be crushing! Earnings! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:21:46 </td>
   <td style="text-align:left;"> $AAPL is next and could lose a trillion in market cap. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:21:44 </td>
   <td style="text-align:left;"> $AAPL any reason this is dumping? Not even ER yet wtf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:20:53 </td>
   <td style="text-align:left;"> $NFLX $AAPL $TSLA $AMZN finaly these overinflated stocks started to crunch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:20:24 </td>
   <td style="text-align:left;"> $AAPL Simulated Weekly 160.0 PUTS for Friday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:20:13 </td>
   <td style="text-align:left;"> $AAPL hahahaha, you , you don&amp;#39;t believe it.  you need to stop investing in stocks. house are manipulating :) making people loose! hahahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:20:13 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA We&amp;#39;re in for a chop or a mild correction in the main index until Fed signals a slowing in tightening schedule. If buying dips be patient, don&amp;#39;t expect slingshot back to new highs, though always expect the unexpected. A 10 percent correction warrants the beginning of light bargain hunting. &amp;quot;Patience&amp;quot; as the inexperienced troll babies sardonically spout. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:19:56 </td>
   <td style="text-align:left;"> $SPY $AAPL and $MSFT are next 🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:17:53 </td>
   <td style="text-align:left;"> $AAPL wow the market will keep crashing until want aug? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:17:50 </td>
   <td style="text-align:left;"> $AAPL The advisor to the president went on tv and said negative things about the market. He then turns around and puts his money on the market to go down and makes millions of our money for his profits. He did the same thing in March of 2020 and made millions then too. He should be arrested for his actions. The government are crooks, they could care less about the people  who work hard for there money. Sorry but that&amp;#39;s how I feel. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:16:25 </td>
   <td style="text-align:left;"> $AAPL Right back at the breakout levels. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:14:00 </td>
   <td style="text-align:left;"> $AAPL has a Return On Assets of 26.97%. This is amongst the best returns in the industry. https://www.chartmill.com/stock/quote/AAPL/fundamental-analysis?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:11:58 </td>
   <td style="text-align:left;"> $NFLX damn, imagine how hard will $AAPL miss, with strong dollar, supply chains problems and overall weak christmas sales </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:11:14 </td>
   <td style="text-align:left;"> $AAPL stay disciplined. I called this in December. It will pass in a couple of months. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:11:03 </td>
   <td style="text-align:left;"> $AAPL Follow me 😉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:09:18 </td>
   <td style="text-align:left;"> $AAPL 140 incoming?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:08:49 </td>
   <td style="text-align:left;"> $MSFT load load load... sold one of my rental today... money will be wired first thing tomorrow to add huge on $MSFT $AAPL and $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:08:27 </td>
   <td style="text-align:left;"> $AAPL IS THIS THE BOTTOM? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:08:21 </td>
   <td style="text-align:left;"> $VIAC when the market overreacts, this is where you buy. $NFLX suffering means one thing: $amzn $aapl $viac $disca benefit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:08:11 </td>
   <td style="text-align:left;"> $AAPL Damn sold to soon now im going bullish for next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:05:03 </td>
   <td style="text-align:left;"> $AAPL $GOOG $GOOGL $FB $AMZN Key News Update 
US lawmakers advance Big Tech competition bill 
https://www.marketwatch.com/story/senate-panel-approves-antitrust-bill-targeting-apple-google-and-amazon-11642705698 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:01:31 </td>
   <td style="text-align:left;"> $PTON is this now attractive to $nke and $lulu $aapl now as acquisition target.  Don’t mind a 30-40% premium </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 07:00:45 </td>
   <td style="text-align:left;"> $AMD The Baltic Dry Index’s Imperfect Message for Stocks -Tom McClellan
Chart In Focus
Here’s the long term view and BDI is falling off a cliff. Economic Growth slowing while inflation remains excessively high. 

When BDI falls so does the Market. 
$AAPL $QQQ $SPY $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:57:16 </td>
   <td style="text-align:left;"> $AMZN tomorrow $aapl $amzn will follow $NFLX , we are done </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:55:06 </td>
   <td style="text-align:left;"> $SPY so.... I&amp;#39;m guessing someone knows or heard something? No fkn way this dump was just due to a correction. What do you guys think?
$AAPL $QQQ $TSLA latexa69ca82055841520ae5450ab78c3b298AAPL  
$ALB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:50:57 </td>
   <td style="text-align:left;"> $AAPL I have 25 puts, but are these your calls bulls? I love making $$ from call credit spreads. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:49:40 </td>
   <td style="text-align:left;"> $NFLX $AAPL Is next mark my word buy long term puts!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:49:31 </td>
   <td style="text-align:left;"> $SPY Fun fact of the day: 

This morning SPY up 19 right close to when markets premarket session opened.

Now, Espy close to down 19 pts in futures 

$QQQ $NDX $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:48:26 </td>
   <td style="text-align:left;"> $AAPL $MSFT load up!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:47:53 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:47:42 </td>
   <td style="text-align:left;"> $VIAC competition cuts into growth - all streamers effected but this forces big players’ hands. Especially $NFLX as they are light years behind movie studios in quality production. They NEED quality IP movies and shows and live tv/sports. My bet was $AAPL buys VIAC but looks like NFLX is in dire need.. if only Sheri didnt sign a deal with comcast last year… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:47:14 </td>
   <td style="text-align:left;"> $AAPL Great time to block unhinged idiots. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:47:14 </td>
   <td style="text-align:left;"> $AAPL I&amp;#39;m up so big here that I&amp;#39;m tempted to sell, toss my gains into $VTI and look for a re entry point. This market is insane right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:47:02 </td>
   <td style="text-align:left;"> $AAPL remember when Jim Cramer told you all to just buy  U.S tech 😂 stocks when prices was already stretch. That loser never gets held accountable. Asia and South America is the pivot folks thank me later </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:46:24 </td>
   <td style="text-align:left;"> Senate Panel Advances Antitrust Bill Aimed at Apple, Amazon, and Google  $AAPL $AMZN $FB 

https://newsfilter.io/a/6a4735865a5cf5d6ca7e8ac375a137c1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:46:12 </td>
   <td style="text-align:left;"> $AAPL if   my money is not safe in aapl, where is it safe? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:43:55 </td>
   <td style="text-align:left;"> $AAPL Apple is the safe haven … it’s a cash making machine ….. $NFLX $AMD $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:42:41 </td>
   <td style="text-align:left;"> $INDI + $AAPL a boy can dream </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:40:53 </td>
   <td style="text-align:left;"> $NFLX Life time opportunity for $AAPL to buy this. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:40:49 </td>
   <td style="text-align:left;"> $QQQ wouldn’t surprise to see $AAPL in $120’s and $AMZN around $2000 when dust settles.  That is unless Fed says something dovish which is very possible $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:40:12 </td>
   <td style="text-align:left;"> @GoodieGood do y’all think Trump would let Russia invade Ukrainian borders? $amzn $tsla $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:38:07 </td>
   <td style="text-align:left;"> $NFLX $PTON $AAPL We continue to STACK GAINS and stay out of harms way! It’s what we do! Been at this longer than ANYONE here on ST…. Are you ready for the next OP Alert play?
Love seeing new members reaction to what we do!😇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:38:02 </td>
   <td style="text-align:left;"> $TSLA $NVDA $AMD $AAPL Markets correcting thanks to the MMs manipulating the markets to make it happen unfortunately .. called this weeks ago </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:36:24 </td>
   <td style="text-align:left;"> $AAPL fuck MLK’s son </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:35:48 </td>
   <td style="text-align:left;"> $AAPL dead 💀.. now that is dead, watch tomrrow pop 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:35:05 </td>
   <td style="text-align:left;"> $AAPL 
3 weeks ago I predicted tech would not bottom until NVDA hit 250, msft 300 and aapl 160. Now NVDA is below 250, msft is almost 300 and aapl is near 160 target too. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:34:10 </td>
   <td style="text-align:left;"> $AAPL No brainer </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:34:03 </td>
   <td style="text-align:left;"> $AAPL should’ve held my puts jeezus </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:33:42 </td>
   <td style="text-align:left;"> $AAPL 

Tmw I’m going to close my eyes and swallow the max pain …

I will be surprised if it turned green EOW! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:33:07 </td>
   <td style="text-align:left;"> $SPY $AAPL $AMZN what are the odds that any Fed president confirms that they&amp;#39;re not going to shock us with 50 bps hikes on top of the accelerated tapering? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:32:35 </td>
   <td style="text-align:left;"> $AAPL total shit show </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:31:31 </td>
   <td style="text-align:left;"> $AAPL should buy $PTON </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:31:30 </td>
   <td style="text-align:left;"> $AAPL lmao i sold 50 167.5 puts for 1.00 today…. They’d be worth like 20k right now, kill me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:31:14 </td>
   <td style="text-align:left;"> $NFLX wow, another pandemic darling going to shit $AMZN $SPY whos next?  $AAPL ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:30:41 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:30:08 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-01-20 Largest Trades Data: 
https://www.youtube.com/watch?v=Fy1PSVuF1zw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:29:42 </td>
   <td style="text-align:left;"> $AAPL nflx earnings giving a prelude on whats going to happen of apple misses or guides lower or cites supply chain issue or decrease in margins! Gosh… too much to take risk… am bull turned bear now ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:29:32 </td>
   <td style="text-align:left;"> $AAPL the amount of 1 and 2 shares in buys and sells is doing my heading 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:28:37 </td>
   <td style="text-align:left;"> $PTON 

“The $AAPL of clothes hangers”

😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:28:37 </td>
   <td style="text-align:left;"> Now I defs don’t trust bulls &amp;amp; bears who say TA don’t work. True that it can’t be 100% accurate and there are other variables to look at but at least it does provide with high probability set ups that doesn’t just come from random hopes and dreams 👀

$spy $arkk $tsla $aapl $btc.x </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:27:57 </td>
   <td style="text-align:left;"> $AAPL yo someone tell @fillyg97 to unblock me so i can come skull fuck his mother, </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:27:42 </td>
   <td style="text-align:left;"> $AAPL Just waiting. Everything so weak that even the rallies are short lived. This is on my very close watch list and I&amp;#39;m looking at under 130, maybe down to 110.  Yes, that would be a crazy drop but we lived through some crazy times recently and even 75 is a possibility. This is a tough one, I hope everyone makes money one way or the other. BOLTE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:24:44 </td>
   <td style="text-align:left;"> $AAPL drop it like it’s hot 🔥 

#AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:24:24 </td>
   <td style="text-align:left;"> $AAPL double bearish divergence on 2 major timeframes, be smart </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:23:35 </td>
   <td style="text-align:left;"> $AAPL market hudge just bouts 1.8 millions shares while everyone we’re selling 📣💁 they know what is coming next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:23:08 </td>
   <td style="text-align:left;"> $AMZN no doubt this will be down another 20% by the time the market‘s most overvalued pigs $AAPL $MSFT are down a mere 10% from current levels. The cheapest stocks always get hammered the hardest. Watch Amazon rebound to $4000 by 2023. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:22:43 </td>
   <td style="text-align:left;"> $AMD people are calling 2k NQ on other forums - $AAPL will drop to $15 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:21:57 </td>
   <td style="text-align:left;"> $AAPL While everyone was selling half an hour ago someone just absorbed 1.84 millions of Apple stocks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:20:35 </td>
   <td style="text-align:left;"> $AAPL remember there is no real connection to each of FAANG + M. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:19:16 </td>
   <td style="text-align:left;"> $AAPL russia touches 1 so much of an inch of Ukraine and the nasdaq drops 3000 points in 2 hours </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:18:51 </td>
   <td style="text-align:left;"> $QQQ $TSLA $AAPL $FB  who is going to save us from the 20% drop??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:18:40 </td>
   <td style="text-align:left;"> $NFLX $GOOGL $GOOG $AAPL $FB who&amp;#39;s the next to report in faang ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:18:24 </td>
   <td style="text-align:left;"> $AAPL Simulated 160.0P for Friday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:17:42 </td>
   <td style="text-align:left;"> $AAPL monthly and weakly bearish divergence lolol get out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:17:12 </td>
   <td style="text-align:left;"> $SPY $ES_F $AMZN $GOOGL $AAPL 

This would have been a perfectly drawn Fib Retracement from the JAN 3 ATH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:16:00 </td>
   <td style="text-align:left;"> $SPY $AAPL too much doom and gloom. Here’s a unicorn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:15:59 </td>
   <td style="text-align:left;"> $AAPL latex8ad77922128fcbeae91cdb6e518b2a83AAPL diversified their revenue stream to add significant revenue to services - including streaming - very durable and growing.  App Store sales have been strong, as well. 
 
$TSLA in an EV market where EVs only have 3-5% of the market - so a lot of growth expected ahead AND $TSLA exceeded the number of cars built for 2021 and gigafactories about to spin up.  Other EV manufacturers are just building their first cars. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:15:00 </td>
   <td style="text-align:left;"> $VIAC LOL, GUY ON CNBC SAID $AAPL SHOULD BUY $NFLX.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:14:29 </td>
   <td style="text-align:left;"> $AAPL  
https://www.dailymail.co.uk/sciencetech/article-10423211/Apple-working-fix-bug-Safari-exposes-users-internet-activity-personal-data.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:14:01 </td>
   <td style="text-align:left;"> $AAPL isn&amp;#39;t going to buy $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:13:32 </td>
   <td style="text-align:left;"> Senate panel approves antitrust bill targeting Apple, Google and Amazon

$AAPL $GOOG $AMZN

https://www.marketwatch.com/story/senate-panel-approves-antitrust-bill-targeting-apple-google-and-amazon-11642705698?mod=home-page </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:13:01 </td>
   <td style="text-align:left;"> $AAPL $PINS This felt like a margin call dump after the last couple days of declines.  People shouldn’t use money they don’t have! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:12:16 </td>
   <td style="text-align:left;"> $AAPL Netflix really holds the market as a predictor of future earnings. Not surprising their number growth was low with people looking to go out and spend rather than watch and spend. The stay at home pandemic stocks are going to tank while tangible goods and services will see an uptick but it’s all contingent upon forecast. Could do phenomenal but if forecasts are bearish, it’ll tank absolutely. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:11:17 </td>
   <td style="text-align:left;"> $AAPL which company is #2 on your list after appl? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:11:16 </td>
   <td style="text-align:left;"> $AAPL HFs raise prices during low volume future trading then splatter their cums on bull&amp;#39;s faces during trading hours. - short for distribution. hahahahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:11:16 </td>
   <td style="text-align:left;"> $AAPL this shit hasn’t fallen enough.. 130s coming.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:09:18 </td>
   <td style="text-align:left;"> $AAPL all the analysts lately have been really bullish on Apple… for the markets sake I hope they are right. A miss seems to be brutal selling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:09:14 </td>
   <td style="text-align:left;"> $NFLX This is a  epic Build Back BETTER speech got the.market in a FUNK.. $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:08:36 </td>
   <td style="text-align:left;"> $AAPL 

I’m sensing they are working to get all
1 YR oversold to cross on all indexes ..

It’s approaching very soon in few days more likely within AAPL earnings and FOMC meeting.

I expect Jerome Powell will delay the decision due to heavy routing !! They will listen and help to rescue the economy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:08:18 </td>
   <td style="text-align:left;"> $AMZN $AAPL $TSLA $SPY $GOOGL 
Look Amazon. 
It’s already below $3,000 😱 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:07:37 </td>
   <td style="text-align:left;"> $AAPL Rate hike? Cash is king. Just buy the richest company when they&amp;#39;re on discount. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:07:29 </td>
   <td style="text-align:left;"> $SPY If Growth days are over on megatech could nasdaq correct 40%? I don&amp;#39;t think it&amp;#39;s out of the realm of possibility seeing how expensive they trade currently....$qqq $amzn $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:06:21 </td>
   <td style="text-align:left;"> $AAPL everything down but apple is still holding solid </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:06:05 </td>
   <td style="text-align:left;"> $AAPL what&amp;#39;s happening to $NFLX right now is the same thing that&amp;#39;s going to happen to $AAPL - they may beat both top and bottom, but their guidance will drag them down. This will drop to the 100 dma prior to earnings. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:05:51 </td>
   <td style="text-align:left;"> $PLTR $ABNB $AAPL $SPY $NFLX 
At #5 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:03:27 </td>
   <td style="text-align:left;"> $NFLX Streaming wars winner will be one with the most mass hits, biggest set of IP: 

Perfect time for $AAPL or $AMZN to take the lead and buy out $VIAC 

Viacom has an absolute treasure trove of content going back decades.  

https://www.cnbc.com/video/2021/12/16/streaming-wars-winner-will-be-one-with-most-mass-hits-biggest-ip-viacom-cbs-exec.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:02:25 </td>
   <td style="text-align:left;"> $AAPL been holding up well in my opinion. First buy down at 158, then 149.60 but not sure it&amp;#39;ll get that low </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:01:47 </td>
   <td style="text-align:left;"> $SPY $NFLX $AAPL $MSFT $TSLA 
👇 Tomorrow 💯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:01:40 </td>
   <td style="text-align:left;"> $AAPL Every year I’m wondering what Netflix, FB, Amazon and Microsoft profits has to do with Apple?? 
Same silly thing every year! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:01:16 </td>
   <td style="text-align:left;"> $AAPL apple is next! Jheez when this falls to 150 real quick! Let’s be honest we’re all on apple devices rn they’re the best. But come on this markets over and appple is the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:00:43 </td>
   <td style="text-align:left;"> $AAPL Will AppleTV+ have a subscriber slowdown like Netflix ?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:00:26 </td>
   <td style="text-align:left;"> $AAPL 155P Exp:20-Jan-23 ↓  🔥 Total(Day): $116,850 
$AAPL 160P Exp:18-Feb-22 ↑  🔥🔥 Total(Day): $54,924 
#UnusualActivity 
 
 
Sign-up free for beta ver.:https://app.jarvisalerts.com 
charts: courtesy of finviz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 06:00:18 </td>
   <td style="text-align:left;"> $AAPL 140P Exp:16-Sep-22 ↑  🔥 Total(Day): $37,210 
$AAPL 150P Exp:19-Jan-24 ↓  🔥 Total(Day): $44,000 
$AAPL 155P Exp:18-Feb-22 ↑  🔥🔥 Total(Day): $56,750 
#UnusualActivity 
 
 
Sign-up free for beta ver.:https://app.jarvisalerts.com 
charts: courtesy of finviz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:59:47 </td>
   <td style="text-align:left;"> $SPY $AAPL $MSFT $TSLA $NFLX 
👇 This is a joke anyways 🤷🏻‍♀️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:58:48 </td>
   <td style="text-align:left;"> $AAPL whatever.  Can&amp;#39;t go wrong with this thing. I&amp;#39;ll be ready to add some more soon. This is my retirement stock in 28 years. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:57:56 </td>
   <td style="text-align:left;"> $NFLX $DIS  $AMZN $AAPL 
LETS GO BRANDON!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:55:54 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:55:22 </td>
   <td style="text-align:left;"> $AAPL A couple little gaps to fill then BOOYAH! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:54:16 </td>
   <td style="text-align:left;"> $SNAP $rblx $twtr $AAPL  
all down like crazy... do not listen to stupid bears.. 
 
we will bounce very soon!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:54:15 </td>
   <td style="text-align:left;"> $AAPL you stupid bears 🐻 this Apple 🍎 stock go away 
Biggest earning in Apple history is next week so enjoy your short position and puts while you can 📈📈📈🐂🐂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:52:34 </td>
   <td style="text-align:left;"> $NFLX Man if people aren’t signing up for $15 I can’t wait to see what they think about paying $1200 for a phone from $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:52:33 </td>
   <td style="text-align:left;"> Next market drama is probably gonna be recession themed due to high global inflation

High inflation= reduced purchasing power so ppl spend less

Businesses lose revenue so they cut costs by reducing staff= less jobs in the market +increase in unemployment rate

Result= RECESSION 🍿👀

$SPY $ARKK $AAPL $TSLA $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:52:27 </td>
   <td style="text-align:left;"> $AAPL Can get uglier ... see $NFLX for reference </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:52:03 </td>
   <td style="text-align:left;"> $AAPL LOTTOS TOMORROW!! I bought each option for .27. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:51:58 </td>
   <td style="text-align:left;"> $SPY if $AAPL and $GOOGL can go down 20% 
 
I will deploy more capital </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:51:45 </td>
   <td style="text-align:left;"> $AAPL im a simple man. If apple goes into correction territory then i start buying </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:51:11 </td>
   <td style="text-align:left;"> $NFLX Guidance is all fcked up!! Wallstreet uses this mania to Clobber $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:50:50 </td>
   <td style="text-align:left;"> $AAPL so apple pulling back on Netflix print is dumb. Also $NFLX is now looking attractive. Will look to play options tomorrow if this pullback holds up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:50:26 </td>
   <td style="text-align:left;"> $AAPL can someone pls tell the news </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:50:09 </td>
   <td style="text-align:left;"> $AAPL y? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:49:25 </td>
   <td style="text-align:left;"> $AAPL get ready foe this bear trap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:49:12 </td>
   <td style="text-align:left;"> $AAPL $SPY gap down tomorrow seems most appropriate. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:48:29 </td>
   <td style="text-align:left;"> $NFLX dragging down $FB, $MSFT, $AAPL in AH as well. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:48:22 </td>
   <td style="text-align:left;"> $NFLX $SPY $FB $AAPL $TSLA everything is Failing knife 🔪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:48:08 </td>
   <td style="text-align:left;"> $NFLX  $AAPL  $SPY  $QQQ  About to break that 50mda in afterhours. Fun might be just starting... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:47:22 </td>
   <td style="text-align:left;"> $AAPL $MSFT $SPY well we had a good run! Gonna be a boring next 10 years of no gains </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:47:17 </td>
   <td style="text-align:left;"> $AAPL 
Now what they have the sell Apple 
What f </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:46:54 </td>
   <td style="text-align:left;"> $AAPL this is next $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:45:58 </td>
   <td style="text-align:left;"> $AAPL well, should have held my 165 puts overnight and not swung a few 167 calls for a quick pop in the morning. This is a rough ah. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:45:18 </td>
   <td style="text-align:left;"> $AAPL went from $170 to $162 in a matter of 3 hours.  scary times..... $FORD $SOFI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:45:11 </td>
   <td style="text-align:left;"> $AAPL lol I can&amp;#39;t believe I bought the 1DTE 165P for 0.26 earlier today. Should&amp;#39;ve bought like a thousand of those. Dammit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:45:08 </td>
   <td style="text-align:left;"> $AAPL is going down to $1 because all Apple subscribers are burning their iphones and casting themselves into the sea.  Or not. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:44:53 </td>
   <td style="text-align:left;"> $AAPL So apple will never make a new high ever again.... LOL Congrats if this is your first apple stock purchase and you hold it . Always keep some powder in the keg for days like these. I`ll be back WHEN we make a new high. Just as I`ve done .CYA!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:44:25 </td>
   <td style="text-align:left;"> $AAPL couldn&amp;#39;t catch support. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:43:57 </td>
   <td style="text-align:left;"> $AAPL glad I took profits at $176.00! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:43:19 </td>
   <td style="text-align:left;"> $AMC $AAPL Bluechips are also getting hit. Here is he apple chart. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:43:17 </td>
   <td style="text-align:left;"> $AAPL AH ripping bulls! come on, say it bulls! hahahahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:43:00 </td>
   <td style="text-align:left;"> $AAPL just purchased a little more so I’ll go into the morning with a half position. Thanks!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:42:53 </td>
   <td style="text-align:left;"> $AAPL ok we can stop dropping now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:42:50 </td>
   <td style="text-align:left;"> $SPY $AAPL $AMZN $GOOG $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:42:28 </td>
   <td style="text-align:left;"> Once $aapl gets the $nflx treatment we have a fun market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:42:25 </td>
   <td style="text-align:left;"> $DIS markets will get crushed $AAPL $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:42:19 </td>
   <td style="text-align:left;"> $NFLX Thank you Biden and JPOW for this red day.  No more cheap money left to pump this back up. death to FAANG stocks now.  $AMZN $FB $GOOG $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:41:56 </td>
   <td style="text-align:left;"> $AAPL 🩸🩸🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:41:54 </td>
   <td style="text-align:left;"> $SPY $SPX $AAPL $NVDA look at that strong boner VIX has today! looks looks like roid rage on viagra! hahahaha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:40:46 </td>
   <td style="text-align:left;"> $AAPL $MSFT  Back to 15 PE for both.  Don&amp;#39;t buy until then. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:39:48 </td>
   <td style="text-align:left;"> $AAPL so buy the dip? Asking for a friend? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:39:27 </td>
   <td style="text-align:left;"> latexe7893c388f15ca50e8f68db085e5bd02TSLA 1.191m (54% call/46% put)
$SOFI 1.177m (71% call/29% put)

Lynk in bayo for option trading ideas </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:37:21 </td>
   <td style="text-align:left;"> $AAPL latex2c0dead3bc822b451889d3511536ef2bMSFT testing 298 and 292 / 200 sma

$NFLX killing the spirit… when they announced the hike it should have been understood that they are not getting growth.

Msft is the golden goose! 

Nothing is safe!  Tomorrow I am going to buy the dip in msft for day trade in the pre markets. Sure it is gapping down! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:36:56 </td>
   <td style="text-align:left;"> $AAPL $tsla  just a thought if russia indeed does invade ukraine then Market fuked without lube right?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:36:30 </td>
   <td style="text-align:left;"> 5-Day Equity Sentiment Recap: $AAPL is the #1 stock that institutions are trading over rolling 5 day window with 267.4K options contracts.

Market analysis included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:36:26 </td>
   <td style="text-align:left;"> $AAPL $62 puts you at pre-pandemic high. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:36:24 </td>
   <td style="text-align:left;"> Most Traded Contracts 

$AAPL January $165 Put
$AAPL January $167.50 Put
$AAPL January $167.50 Call
$F February $28 Call
$F February $28 Put
$AAPL January $170 Put
$AMD January $125 Put
$F January $22 Put
$TSLA January $1100 Put
$AAPL January $160 Put </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:36:21 </td>
   <td style="text-align:left;"> $NFLX another large cap BITES THE DUST... Scary scary scary too watch folks. CASH IS KING FOR ME! Will refuse to give back the tons of $$ we made 2020-2022. $SPY $QQQ $AAPL $AMZN... Lets stay safe and keep focused on crushing the downside </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:36:06 </td>
   <td style="text-align:left;"> $VIAC When the dust settles and the facts come out $NFLX $ROKU $DIS $AAPL going to see the value here and we are going to rocket.  Hold tight its coming. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:35:06 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : Apple&amp;#39;s Tim Cook, Alphabet&amp;#39;s Sundar Pichai personally lobbied against Big Tech bill https://www.stck.pro/news/AAPL/21661137 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:35:01 </td>
   <td style="text-align:left;"> $AAPL This is the stock that&amp;#39;s held my whole portfolio together, this and $BRK.B .  
 
Thank you for that little favor in life Apple. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:34:43 </td>
   <td style="text-align:left;"> $AAPL $SPY Apple levy showing signs of weakness, she breaks..look out below </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:34:31 </td>
   <td style="text-align:left;"> $SPY $PTON $NFLX $LCID $AAPL - -  &amp;quot;how low can it go?&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:34:08 </td>
   <td style="text-align:left;"> $AAPL Meh, im so happy that im all in shares :) this are tough times for the stocks... Netflix ... Jesus </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:33:34 </td>
   <td style="text-align:left;"> $AAPL 150 by earning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:33:25 </td>
   <td style="text-align:left;"> $AAPL Bailing of AAPL has started ... might hit 150&amp;#39;s AH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:32:38 </td>
   <td style="text-align:left;"> $AAPL damn sold my puts too early oh well 🤷‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:32:35 </td>
   <td style="text-align:left;"> $SPY is it down because of Netflix? 😲I wonder how $AAPL earnings will take this to 420 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:31:58 </td>
   <td style="text-align:left;"> $AAPL who ever is selling pre market on netflix news is getting shaken out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:31:48 </td>
   <td style="text-align:left;"> $AAPL $160 then $154 TP. H&amp;amp;S broken + scandals + tapering + this is the only one carrying QQQ. i dont mind holding my puts for the next 4 weeks. lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:31:02 </td>
   <td style="text-align:left;"> $SPY HOLY $HIT, I just shorted the SPY early this morning through Feb, $TSLA and $AAPL tomorrow is building up to be a circuit breaker downwards....and housing rates MASSIVE HIKE.  Can we see a 1500 down down Friday?  TGIF! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:30:42 </td>
   <td style="text-align:left;"> $AAPL NFLX down 17% AH ... and the still beat on earnings numbers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:30:21 </td>
   <td style="text-align:left;"> $AAPL a buy at 135! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:30:06 </td>
   <td style="text-align:left;"> $AAPL dont buy till 155 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:29:22 </td>
   <td style="text-align:left;"> $AAPL  
. 
The 165puts speak for themselves. 
. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:29:21 </td>
   <td style="text-align:left;"> $NFLX this is overkill $AAPL missed earnings and was brought back up to 180 and made a new ATH while Netflix is getting sold like its worthless </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:28:52 </td>
   <td style="text-align:left;"> $AAPL In the recent reporting quarter: 23 institutions initiated a position, while 5 completely liquidated https://insider-analysis.com/search_whales.php?ticker=TABLE_AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:28:45 </td>
   <td style="text-align:left;"> $AAPL You guys realize this is Apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:28:09 </td>
   <td style="text-align:left;"> $AAPL 
😂 when people panic you buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:28:05 </td>
   <td style="text-align:left;"> $AMZN $NFLX $AAPL which is the next fat pig to short </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:27:48 </td>
   <td style="text-align:left;"> $AAPL $AMZN $GOOGL $SPY $DJIA the market tomorrow is going to have a historic correction. Itll gonna be nasty! Protect yourselves. See you all on the other side. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:27:17 </td>
   <td style="text-align:left;"> $AAPL this might hit 140 this market is reminding of 2018 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:27:15 </td>
   <td style="text-align:left;"> $QQQ $NFLX $TSLA $AAPL $AMZN this earnings season is going to be lit! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:27:10 </td>
   <td style="text-align:left;"> $AUTO 
Lots of money coming with this Program.

Autonomy Launches Tesla Model 3 EV Subscription Program
  https://news-static.webullfintech.com/us/news-html/20220120/48458563.html?theme=1&amp;amp;color=2&amp;amp;hl=en&amp;amp;android_sdk_int=30&amp;amp;canary-version=&amp;amp;_v=1&amp;amp;sp=1&amp;amp;statusBarHeight=75&amp;amp;tickerId=913253656&amp;amp;disSymbol=AUTO&amp;amp;isSubsNews=false

$TSLA $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:26:52 </td>
   <td style="text-align:left;"> $AAPL market breakdown </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:26:24 </td>
   <td style="text-align:left;"> $AAPL $QQQ $AMZN $NFLX $NASDAQ man this could be the end of the market we know 😐🐻🐂📈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:26:05 </td>
   <td style="text-align:left;"> $AAPL so happy I have options expiring Friday (sike) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:25:47 </td>
   <td style="text-align:left;"> $NFLX This was at 700 just 2 months ago. 430 is almost a 40% drop.  June 2018/May 2020 levels. I&amp;#39;d say once this settles, expect the buying to start again. Short term pain, but if you got caught holding calls -- I hope they were at least March calls... $SPY $AAPL $QQQ $ROKU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:25:22 </td>
   <td style="text-align:left;"> $AAPL my limit order for Apple just took, had it here since December. It’s OK I’m bullish. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:25:02 </td>
   <td style="text-align:left;"> $AAPL Warren Buffett

“If you aren’t thinking about owning a stock for 10 years, don’t even think about owning it for 10 minutes.” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:24:52 </td>
   <td style="text-align:left;"> $AAPL Fellow bulls this January gonna be rough 🥲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:24:48 </td>
   <td style="text-align:left;"> $AAPL $NFLX .. pretty scary ... AAPL could touch 150&amp;#39;s tomorrow. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:24:45 </td>
   <td style="text-align:left;"> $AAPL remember in bull market Friday is always the red day but in bear market tommorow we go sky high </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:24:32 </td>
   <td style="text-align:left;"> $AAPL where $150 at </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:23:45 </td>
   <td style="text-align:left;"> $AAPL Strong guidance strong earnings and share buybacks plus dividend raise ☝️🦯 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:23:10 </td>
   <td style="text-align:left;"> $CDEV $QQQ $AAPL $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:23:03 </td>
   <td style="text-align:left;"> $AAPL damn thanks for the cheap calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:22:52 </td>
   <td style="text-align:left;"> $AAPL What is going on!!??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:21:51 </td>
   <td style="text-align:left;"> $NFLX Ouchhhh What happen to the bull market.. $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:21:43 </td>
   <td style="text-align:left;"> $NFLX this pos no longer to compete with Paramount Plus of $VIAC, Peacock, $AAPL TV Apple One! It gave a try with games tho lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:20:25 </td>
   <td style="text-align:left;"> $AAPL $MSFT $AMZN $SPY $NFLX 

Keep investing… Keep compounding. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:20:17 </td>
   <td style="text-align:left;"> $SPY $LCID $AAPL $NFLX $PTON TODAYS SUMMARY: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:20:07 </td>
   <td style="text-align:left;"> $AAPL  
J the dog powell is the main culprit in all these ugly declines in red, he needs to do something to keep stocks from falling further. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:19:57 </td>
   <td style="text-align:left;"> $FUBO maybe $NFLX should buyout Fubo then and start working on their sports audience before $AAPL starts their sports push </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:19:31 </td>
   <td style="text-align:left;"> $QQQ $SPY $TSLA $AAPL $350 support on Nasdaq seems inevitable but will market makers fuck over you greedy bears tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:19:21 </td>
   <td style="text-align:left;"> $AMD The problem is AMD Valuation is excessively Expensive
From 2020 it was easy to throw money at anything in the Market and it went up because of The Fed providing massive amounts of money liquidity in the Market 

Consequently in this Cyclical Bear Market there will be a lot of loses because of the above indiscriminate reckless behavior.
💼💼💼💼💼💼💼💼💼💼💼

$AAPL $NVDA $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-21 05:19:16 </td>
   <td style="text-align:left;"> $PTON I bet someone could be starting to eye an acquisition of PTON. Great product, terrible management. $NKE or $AAPL could afford it . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:35:38 </td>
   <td style="text-align:left;"> On the street. We had another method for determining tops and bottoms. We called them an “interval investment thesis”

For similar companies with particular segments or profiles, we would mark dates for major milestones and identify price points. 

For example. $NFLX experienced a huge dump after hours. And currently sitting at a price point not reached since April 19.

Now if we were to look at the price points for $NVDA and $TSLA on those dates, we get $150 and $750 respectively. 

This would help us to determine fully realized risk in the event that either company demonstrated surprise weakness in upcoming earnings releases. 

Now the challenge is determining which companies are coupled as comparison companies. But sometimes it’s not very difficult to determine if you analyze multiple charts side by side. 

If either $NVDA or $TSLA disappoint in q1. Max pain has been established. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:33:42 </td>
   <td style="text-align:left;"> Markets closed now Twitter down 🤔 $nflx $tsla $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:32:57 </td>
   <td style="text-align:left;"> $DPZ $NFLX $SPY $TSLA 
It’s over </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:32:14 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-20 Options Analysis Video: 
https://www.youtube.com/watch?v=52-qgpEeWSA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:32:02 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA $NFLX literally me reading the comments on ST 🤭😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:31:49 </td>
   <td style="text-align:left;"> $TSLA 
When insiders are selling, you&amp;#39;re suppose to sell. Not buy more. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:31:23 </td>
   <td style="text-align:left;"> $TSLA 
Cathie Wood &amp;amp; Elon Musk literally sold at the top you morons. What don&amp;#39;t you get??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:31:01 </td>
   <td style="text-align:left;"> $TSLA $1000 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:30:09 </td>
   <td style="text-align:left;"> $TSLA $950 tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:28:56 </td>
   <td style="text-align:left;"> $SPY $PTON $NFLX $AMZN $TSLA  R.I.P 

You all will be remembered!  3-6 mafia   🧞‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:28:05 </td>
   <td style="text-align:left;"> $TSLA added 💰 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:28:02 </td>
   <td style="text-align:left;"> $TSLA 700 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:27:52 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ we might see a quick flash in the morning and then rip back up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:27:45 </td>
   <td style="text-align:left;"> $TSLA Bye to all the bulls tomorrow! All your calls will be worthless. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:27:04 </td>
   <td style="text-align:left;"> $TSLA says a lot about TESLA stock and how’s its holding up through all this mess </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:26:33 </td>
   <td style="text-align:left;"> $TSLA where are the fElon fanboys at? Futes lookn sexee </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:25:35 </td>
   <td style="text-align:left;"> $TSLA once 985 is gone, I think 800s will come
Pretty fast </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:25:21 </td>
   <td style="text-align:left;"> $SPY   For my Aces who used to Rock Green 

   $AMZN $TSLA $NFLX $PTON </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:23:13 </td>
   <td style="text-align:left;"> $TSLA 3rd day in a row of $50 range. They are burning long option (call and put) to a crisp. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:23:02 </td>
   <td style="text-align:left;"> $SPY $TSLA looking at the futes 🥴 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:22:52 </td>
   <td style="text-align:left;"> $TSLA cant wait for this bloated piece of overpriced turd to bust 😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:22:34 </td>
   <td style="text-align:left;"> $TSLA the new Tesla self driving model </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:22:17 </td>
   <td style="text-align:left;"> $TSLA burn fukn burn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:21:27 </td>
   <td style="text-align:left;"> Now this $nflx $aapl $tsla $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:20:43 </td>
   <td style="text-align:left;"> $TSLA  10Y and 2Y yeildd down big time, but Nasdaq futures r still tanking
Go figure </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:18:59 </td>
   <td style="text-align:left;"> $SPY $TSLA Elon&amp;#39;s one tweet away from saying &amp;quot;recession&amp;quot; again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:17:48 </td>
   <td style="text-align:left;"> $TSLA after some nasty bull trap caveouts this week....would not be surprised to see the bottom give out tomorrow to 930....950 more likely...less chase money out there after getting roasted so many times. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:16:58 </td>
   <td style="text-align:left;"> $TSLA easy hold I’m ready for more dips </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:16:51 </td>
   <td style="text-align:left;"> $TSLA Looks like it wants to draw down to the 200 Day, about another 15% from here. Would be great entry if it occurred prior to earnings . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:15:32 </td>
   <td style="text-align:left;"> $tsla $qqq $spy $fb $snap 😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:15:16 </td>
   <td style="text-align:left;"> $TSLA under $150 by end of year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:15:07 </td>
   <td style="text-align:left;"> $TSLA tomorrow whole
Market is going down looks like </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:14:46 </td>
   <td style="text-align:left;"> $TSLA can we see $1000 Pre-Market??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:13:42 </td>
   <td style="text-align:left;"> $TSLA what if.... hmm what if tesla rebounds to $1100 😆 🤣 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:13:27 </td>
   <td style="text-align:left;"> $TSLA Biden destroying the country and market along with it. 3 more years, we’re in serious trouble </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:12:10 </td>
   <td style="text-align:left;"> $TSLA Are we going to be down more than 20% after ER? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:12:08 </td>
   <td style="text-align:left;"> $RIVN is the REAL $TSLA killer. Mark my words. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:11:18 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:10:32 </td>
   <td style="text-align:left;"> $TSLA the earnings coming up are nothing, this company is way overpriced, do you not think blowout earnings are already priced in? This will be a sell the news event and the line of bag holders go on for miles.  Tesla market cap eclipses that of top 5 rival carmakers combined. Get it together people ! See your at 500, and I’m being generous </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:10:25 </td>
   <td style="text-align:left;"> $TSLA will be adding calls first thing tomorrow morning. Bring it bears. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:10:18 </td>
   <td style="text-align:left;"> $TSLA Elon sold high who would have guessed </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:06:28 </td>
   <td style="text-align:left;"> $TSLA big tech getting the Fruit Ninja treatment.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:06:12 </td>
   <td style="text-align:left;"> $TSLA Considering the panic and blood that&amp;#39;s all around, this is holding well </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:05:31 </td>
   <td style="text-align:left;"> $TSLA moon is coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:05:21 </td>
   <td style="text-align:left;"> $TSLA no cap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:05:16 </td>
   <td style="text-align:left;"> $TSLA 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:04:23 </td>
   <td style="text-align:left;"> $TSLA wooo shorts. If we break 995 at the bell you’re fucked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:04:16 </td>
   <td style="text-align:left;"> $SPX $SPY $AMZN  $AAPL $TSLA From the beginning of 2020 rally this is the first biggest red candle in SPX. Do you think it will stop with just one red candle? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:02:40 </td>
   <td style="text-align:left;"> $TSLA Simulated Weekly $990.0 PUTS for Friday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:02:20 </td>
   <td style="text-align:left;"> $TSLA As much as it sucked losing all the gains of the day, we still ended up in the green, no matter how small, the market collapsed, tesla stood strong and has a lot of great things coming our way, 1400 withen a few weeks....Texas and Germany will be awesome! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:01:33 </td>
   <td style="text-align:left;"> $LWLG I don&amp;#39;t give a damn.
 I would have shorted in  the great depression had I been alive back in those days. 

Markets are extremely dislocated from reality. 
We live in a Financial dystopia. 

The real world is getting tougher and tougher while Wallstreet is being subsidized through monetary stimulus. 

Time to join the masses in suffering. 

Let the stocks collapse. 

Probably time to short $TSLA!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:01:25 </td>
   <td style="text-align:left;"> $TSLA  PT $67 by GJ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:01:00 </td>
   <td style="text-align:left;"> $TSLA  The most popular stock in the world can withstand this sh*t market.  Record earnings report January 26 🚀 Ready to roll. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:00:20 </td>
   <td style="text-align:left;"> More evidence that the bull is coming to its execution. $QQQ $TSLA $IWM $DIA $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:00:14 </td>
   <td style="text-align:left;"> $TSLA remember fun ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 09:00:05 </td>
   <td style="text-align:left;"> $TSLA fund fact I have this in my long portfolio at $71 a share. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:59:49 </td>
   <td style="text-align:left;"> $TSLA tesla is a growth get out and have fun play </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:59:28 </td>
   <td style="text-align:left;"> $TSLA it was obvious Netflix would go lower.  It’s a pandemic play. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:59:00 </td>
   <td style="text-align:left;"> $TSLA was analyzed by 47 analysts. The buy consensus is at 69%. So analysts seem to be mildly confident about $TSLA. https://www.chartmill.com/stock/quote/TSLA/analyst-ratings?utm_source=stocktwits&amp;amp;utm_medium=ANALYST&amp;amp;utm_content=TSLA&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:58:55 </td>
   <td style="text-align:left;"> $TSLA So GM, Honda, Hyundai, Ride - Foxconn and pretty much every other auto OEM has investment and relationships with next generation Lithium batteries from ion to Lithium - metal backed - less expensive, charge 85% in 15 minutes, 1,000 mile range- look for SPAC IPO early February Lithium - metal backed batteries </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:58:39 </td>
   <td style="text-align:left;"> $TSLA what&amp;#39;s awesome about tesla. Is no one has a clue about tomorrow 😈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:57:54 </td>
   <td style="text-align:left;"> $NFLX should merge with $TSLA to survive </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:57:53 </td>
   <td style="text-align:left;"> Don’t forget about this. $QQQ $TSLA $SPY $IWM $DIA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:57:39 </td>
   <td style="text-align:left;"> $TSLA As always expect MM to neutralize weekly options contracts (calls and puts) with maximum gains, lock in profits when possible. Those miracle algo runs on low volume are brutal. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:57:00 </td>
   <td style="text-align:left;"> $TSLA  $555 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:56:25 </td>
   <td style="text-align:left;"> $TSLA Netflix getting smacked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:56:11 </td>
   <td style="text-align:left;"> $TSLA  I believe Tesla is already priced in &amp;amp; even with a good earning it can go either way. Might have to wait after to see how it unfolds. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:55:56 </td>
   <td style="text-align:left;"> $TSLA here comes $500 Backtesting 🧞‍♂️🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:55:39 </td>
   <td style="text-align:left;"> $TSLA 😟 https://www.google.com/amp/s/www.businessinsider.com/employee-died-tesla-factory-hub-fremont-california-2022-1%3famp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:55:29 </td>
   <td style="text-align:left;"> $TSLA  
 
Here is Tesla on an inverse chart (down is up and up is down). I have labelled all matching areas and there is an overall good trend forming so long as we can hold the RS1 region.  
 
Obviously the overall market is doing poorly at the moment and it was expected. We also have upcoming earnings so anything can go here. But I am bullish in this region.  
 
In addition, we ended the day on a nice divergence. 
 
To conclude, I would say we found bottom for now and will work our way closer to 1100-1200 in the coming days. Take this information with a grain of salt. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:55:11 </td>
   <td style="text-align:left;"> $TSLA $800 tomorrow boys and girls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:54:00 </td>
   <td style="text-align:left;"> @Innodim1 $TSLA  bottomed out here at 982 holding support and on fib golden zone. Breaking downtrend line Looking for buying potentials </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:53:46 </td>
   <td style="text-align:left;"> We finally got the breakdown below $209 that we have been looking for in the small cap index on the 1 year {P&amp;amp;F} chart. Looks like the bull market is finally over folks. Good luck everyone. $IWM $QQQ $SPY $DIA $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:52:51 </td>
   <td style="text-align:left;"> $TSLA by the time earnings come all the correction s will time out perfect for it to blow past all time highs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:52:08 </td>
   <td style="text-align:left;"> $TSLA @989 $CASI $RCON </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:51:56 </td>
   <td style="text-align:left;"> $TSLA this is a perfect storm wow. You have to be nuts to short this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:50:46 </td>
   <td style="text-align:left;"> Tesla Motors&amp;#39;s Chief Financial Officer just disposed of 1,250 shares  https://www.conferencecalltranscripts.com/summary/?id=10339172 $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:50:36 </td>
   <td style="text-align:left;"> $TSLA ...may I remind everyone of the following: 
1. Megafactory in Lathrop, CA, nearly completed 
2. Berlin Giga near completion and entering production soon 
3. Cybertruck....it&amp;#39;s coming little delayed...but it&amp;#39;s coming 
4. Earning Report in a few days...it will be glorious 
5. Austin Giga nearing completion and begin of production 
6. Tesla Big Rig...yeah, check, it&amp;#39;s coming... 
7. Long term benefits for moving the business to Texas... 
8. The TESLA phone....oh yeah.... 
9. Tesla cannot, quite literally, it cannot keep up with worldwide demand for their cars... 
10. etc etc etc etc etc  
 
So many and so many more to come...buy the dip, hold, hold long and rejoice in the wealth you gain from it. Thank you, Elon!!! (Just my opinion.... ;) ) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:50:29 </td>
   <td style="text-align:left;"> $TSLA Bulls splurging, buying 1 shares at a time, don&amp;#39;t be shy😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:49:53 </td>
   <td style="text-align:left;"> $CLEU maybe cleu can get involved with $tsla in China so musk can tweet about cleu </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:47:50 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:47:38 </td>
   <td style="text-align:left;"> $TSLA Money on the way down … Money on the way up … </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:47:07 </td>
   <td style="text-align:left;"> $TSLA [15s. delayed] filed SEC form 4: Chief Financial Officer Kirkhorn Zachary: 
Disposed 1,250 of Common Stock at price $1,026.75 on 202 https://s.flashalert.me/dWM0ya </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:46:45 </td>
   <td style="text-align:left;"> $AAPL $SPY $MSFT $AMZN $TSLA 

&amp;quot;Apple shares are up 19% since the October 4 low (vs. 5% for the S&amp;amp;P 500) suggesting December quarter upside is largely priced in,&amp;quot; warned Morgan Stanley tech analyst Katy Huberty in a new research note Thursday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:46:14 </td>
   <td style="text-align:left;"> $TSLA Tesla Option Alert: Fri $1000 Puts Sweep (3) near the Bid: 16 vs 27680 OI; Earnings 1/26 After Close 🐻 |🥇 Learn more and get details on  ➡️ SweepCast.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:45:02 </td>
   <td style="text-align:left;"> $TSLA This is going to crater after earnings.  Yikes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:44:34 </td>
   <td style="text-align:left;"> $TSLA $F Will leave it here. Meeting Demand is BIG deal ..THIS year

https://stocktwits.com/BullishMan1/message/428746347 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:42:28 </td>
   <td style="text-align:left;"> Good example of a vulgar display of power from the market makers  $tsla </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:42:22 </td>
   <td style="text-align:left;"> $SPY $TSLA Turns out Elon must have took a few classes in high school after all 😆 
https://interestingengineering.com/elon-musk-says-all-species-on-earth-will-die-when-the-sun-expands </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:40:33 </td>
   <td style="text-align:left;"> $TSLA $NFLX I&amp;#39;m not even invested in the Flix but imagine being dumb enough to let hedgies try to intimidate you on a 60% EPS beat based on projections that don&amp;#39;t meet their estimates (keeping in mind their estimates are usually way off) and then more unbelievably selling Tesla based on this. Hopefully humanity isn&amp;#39;t that stupid!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:40:28 </td>
   <td style="text-align:left;"> $TSLA 📜 SEC Form 4: Kirkhorn Zachary sold $1,283,438 worth of shares (1,250 units at $1,026.75) as part of a pre-agreed trading plan, decreasing direct ownership by 2% to 57,334 units

https://quantisnow.com/insight/2281374?s=s

45 seconds delayed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:39:51 </td>
   <td style="text-align:left;"> $TSLA trillion dollar electric car company…wonder how that’s gonna do in a bear market ???? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:39:51 </td>
   <td style="text-align:left;"> Insider Zachary Kirkhorn reports selling 1,250 shares of $TSLA for a total cost of $1,283,437.50 https://fintel.io/n/us/tsla/kirkhorn-zachary?utm_source=stocktwits.com&amp;amp;utm_medium=Referral&amp;amp;utm_campaign=insider </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:39:43 </td>
   <td style="text-align:left;"> $TSLA $1,283,437.50 of shares sold by Kirkhorn Zachary (Chief Financial Officer), reported in a new form 4 filed with the SEC  

https://newsfilter.io/a/72085adbd3b8dbda86f37d8040764dea </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:39:38 </td>
   <td style="text-align:left;"> $TSLA this is going rally 1020 then end the day round 917 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:39:04 </td>
   <td style="text-align:left;"> $TSLA the only way this will go to 1050 is if i load puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:38:54 </td>
   <td style="text-align:left;"> $TSLA $X $CLF 
Nasdaq down 10%
Dow down 5%
S&amp;amp;P down 6%

All in 20 days🤣🤣🤣🤣🤣

Bear market coming for all, play it!!
LET’S GO BRANDON!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:37:10 </td>
   <td style="text-align:left;"> $TSLA 
Let me educate you. Yes you…
Inflation is real. Needs to come down. ( mostly ship port congestion ) Fed policy will not help that but anywhoo… you still have morons like Jamie Diamond forecasting 7 rate hikes …lol hmmm, I wonder why he’d like 7 rate hike go figure …
Big $ is shorting market. 
Big $ is spreading more FUD in media… reports just today of a hedge fund manager expecting stocks to fall 45% … yeah ok fuckhead .  Pandemic caused a 35% drop ..
 So this is supposed to be worse .? Gimme a break. 
The ONLY reason this market is down is due to FED policy uncertainty. Yes there are other reasons that slightly influence markets but it all comes down to the FED and inflation.
Once inflation data shows a decrease … it’s back to bull markets . ..this will take till end of 2022.  In the meantime , load up on favorite growth names like Tesla
Tesla earnings will continue to increase and stock is on sale ..
Oh and side note …
Bears are full of shit and have always been full of shit . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:34:23 </td>
   <td style="text-align:left;"> $TSLA wtf an employee died at work??! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:34:13 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $MARA $AMZN 

My thoughts on the mkt action today ... 

Did I call the exact top on the mkt intraday today? Just about. At 458 on the SPY I sent an email alert out to my members that I would sell the mkt as I still believe we are in a correction. A correction I believed predicted would occur to begin 2022 - and in which I posted here on ST (SEE BELOW). 

I mentioned yesterday on ST that the mkt wouldn&amp;#39;t put in a tradeable bottom until three things occurred - AAPL back to $160, TSLA closing back under $1000, and Bitcoin(MARA) going back under 40K.  We are getting close as Bitcoin is now pressing that 40K level, TSLA closed under $1000, and AAPL is falling to $160. 

The mkt does a really good job of trapping the most leaning one way. And as I warned yesterday on ST, the &amp;quot;dip buyers&amp;quot; who are new to trading the past couple of years are getting a painful lesson. 

My alerts go out daily. If interested, feel free to reach out at 

jessielivermore1929@gmail.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:33:52 </td>
   <td style="text-align:left;"> $TSLA This shit will go down to $700 and Elon will run to the moon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:33:01 </td>
   <td style="text-align:left;"> $TSLA  last half hour 🙌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:32:58 </td>
   <td style="text-align:left;"> $TSLA who is laughing now? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:32:24 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-20 Technical Analysis Video: 
https://www.youtube.com/watch?v=-aVK61weG-I </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:28:17 </td>
   <td style="text-align:left;"> $TSLA https://youtube.com/shorts/xl1d2Ups07w?feature=share lmfao </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:27:49 </td>
   <td style="text-align:left;"> $TSLA  I shouldn’t have sold those 995p 1/21 I bought 20 minutes before market close! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:26:30 </td>
   <td style="text-align:left;"> $TSLA Ask Elon to put a $RDBX  kiosk on mars so we can tap into the extraterrestrial market and stop the bleeding </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:25:17 </td>
   <td style="text-align:left;"> Sweep Options Activity: $TSLA is the #10 ticker with sweep activity where institutions are trading options urgently with 17.2K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:23:51 </td>
   <td style="text-align:left;"> $TSLA If Tesla stonk starts correcting more n more, will Musk resort back to his reliable tweeting strategy to reverse course and go back up to $1250 ??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:23:20 </td>
   <td style="text-align:left;"> $TSLA has very low SI. A lot of these “bears” are hired goons by big $$$ to shake weak hands. With so many catalysts, they want cheap shares to load up on. Don’t listen to fud and do some DD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:22:38 </td>
   <td style="text-align:left;"> $AMD $AMZN $TSLA $DKNG not looking good tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:21:15 </td>
   <td style="text-align:left;"> $TSLA WE ARE RESPECTED WE&amp;#39;RE NOT FUCKING AFFIRM OR MATTERPORT. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:21:08 </td>
   <td style="text-align:left;"> $TSLA can we fill the 930 gap in my butthole </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:20:27 </td>
   <td style="text-align:left;"> $TSLA OMG THIS IS BAD DIP ALL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:19:48 </td>
   <td style="text-align:left;"> $SPY $NFLX $$DIS $TSLA 
No more stimulus.
Powell asking for money back.
Stocks are over valued and missing earnings.
What more do you need to know that this Year is fucked? 🤷‍♂️🤷‍♂️🤷‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:19:07 </td>
   <td style="text-align:left;"> $TSLA $ARKK $SQ Live: https://youtu.be/KDoDJtaY5yQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:19:05 </td>
   <td style="text-align:left;"> $TSLA Tomorrow should be a great buying opportunity. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:18:43 </td>
   <td style="text-align:left;"> $ARKK $BTC.X  $TSLA $SQ Cathy, Elon and Jack are doing a special live on crypto right now !

https://youtu.be/KDoDJtaY5yQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:18:13 </td>
   <td style="text-align:left;"> $TSLA Wall Street is a very tricky game . That’s why it’s the best too buy the nets companies and add the dips . Been here for years . When you least expect it you will be rewarded . It’s night like this when the market reversed and futures look bad and the shorts are happy. I’ve see the craziest of bounces over the years after days like today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:17:09 </td>
   <td style="text-align:left;"> $TSLA 

Bears are Blah blah blah!

Tesla is: we sold record cars in 2021. Ramping up production in three facilities. Order book is full. 

Oh! and six Governors from India called Elon begging him to open up in their district. Elons response: gotta work out the bugs. Sound familiar? China

Oh! Did I tell you about what the bears say: Blah blah blah blah!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:16:20 </td>
   <td style="text-align:left;"> Fact is I love dead shit to short for profits at bulls expense  ... thanks long  bulls .... enjoy the Armageddon Depression at your expense  $pton $tsla $f $gm $TM et al 😈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:15:02 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

Short any pop you see across the board tomorrow bears, it’s time we lock this market down and make it our playground like it’s 1929. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:14:47 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ 
When your puts printed again❗ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:13:52 </td>
   <td style="text-align:left;"> $TSLA Bear or bull watch those margins </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:13:42 </td>
   <td style="text-align:left;"> $TSLA worker died </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:13:25 </td>
   <td style="text-align:left;"> $TSLA with nasdaq and s&amp;amp;p being down so much, we held a lot better let&amp;#39;s shoot for 1050 tomorrow again 🙌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:12:30 </td>
   <td style="text-align:left;"> $TSLA When is the ER date for Tesla ?? How many cars 🚗 sold for the quarter the expected consensus??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:12:20 </td>
   <td style="text-align:left;"> $TSLA a priced in forever moment, wave farewell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:12:18 </td>
   <td style="text-align:left;"> $TSLA tesla is a safe money stock. That’s why it’s holding up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:11:49 </td>
   <td style="text-align:left;"> $TSLA honestly, if you look at the market and all the stocks, TESLA held very well. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:11:13 </td>
   <td style="text-align:left;"> $TSLA any negatives any at ER  you’ll see a 100 point drop and 750 by feb 15th. 
They are punishing these overvalued stocks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:10:44 </td>
   <td style="text-align:left;"> $SPY $TSLA $QQQ 
There is no catalyst or news tomorrow that will save the market. $NFLX and $DIS missing earnings is just more fuel to the fire. Don&amp;#39;t be a retarded Bull and buy puts. 🤷‍♂️🤷‍♂️🤷‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:10:04 </td>
   <td style="text-align:left;"> $TSLA surprised this isn’t trending </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:09:32 </td>
   <td style="text-align:left;"> $TSLA c’mon tessy I wanna see 1050 tommz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:09:21 </td>
   <td style="text-align:left;"> $TSLA @988 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:08:34 </td>
   <td style="text-align:left;"> $ROKU https://www.cnbc.com/2022/01/20/netflix-quietly-admits-streaming-competition-is-eating-into-growth.html $TSLA $SHOP $FB $ZM Roku eating away Netflix lunch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:08:08 </td>
   <td style="text-align:left;"> $SPY $QQQ $TSLA okay 1 more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:07:53 </td>
   <td style="text-align:left;"> $TSLA Tesla is the supreme ninja </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:07:15 </td>
   <td style="text-align:left;"> $TSLA will we get the gap fill tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:05:33 </td>
   <td style="text-align:left;"> $SPY I hope other options traders can relate. $TSLA $NFLX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:04:44 </td>
   <td style="text-align:left;"> $TSLA 
Gap fill at $940 then $1,200 🙂
Bearish &amp;amp; Bullish 🚀🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:04:09 </td>
   <td style="text-align:left;"> $AAPL $MSFT $TSLA $UWA welcome to Joe Biden’s America where markets crash and he divides our country - only the beginning - good luck to all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:03:43 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-20 Trade Analysis Video: 
https://www.youtube.com/watch?v=DWFCNotz118 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:03:32 </td>
   <td style="text-align:left;"> $TSLA  Next week TSLA back to $1200.
Zen as fuck. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:03:25 </td>
   <td style="text-align:left;"> $TSLA shocked this is still 1000$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:03:24 </td>
   <td style="text-align:left;"> $TSLA $500, then OK. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:03:11 </td>
   <td style="text-align:left;"> $DOGE.X I guess Elon has his own problems right now ( $TSLA ) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:02:36 </td>
   <td style="text-align:left;"> $TSLA 
Futures make you think it’s recovering then boom! 8pm rug pull &amp;amp; reverse </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:02:30 </td>
   <td style="text-align:left;"> $TSLA Why the fuck would this lose all its gains every single fucking day this week? Fucking sick of this market. When is Biden getting voted out? Piece of shit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:02:29 </td>
   <td style="text-align:left;"> My wife tells me sell my $AMZN to buy more $NCT.X but my boyfriend says $TSLA is the best I personally think $BTC.X is great </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:02:28 </td>
   <td style="text-align:left;"> $TSLA that is what you would call a giant butt fuck, still can&amp;#39;t sit. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:02:27 </td>
   <td style="text-align:left;"> $TSLA Futes are getting wrekt already </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:01:17 </td>
   <td style="text-align:left;"> $NIO $AMD $PLTR $SOFI $TSLA 
cramer &amp;amp; fauci would look cute in jail together </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:01:14 </td>
   <td style="text-align:left;"> $TSLA it&amp;#39;s easy to lowball PT&amp;#39;s when the whole market is deep red. Come back and give those PT&amp;#39;s again when we&amp;#39;re deep green. I&amp;#39;m here on both red days and green days. Bullish af, here&amp;#39;s my PT 1200 by EOM, let it be recorded. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:01:08 </td>
   <td style="text-align:left;"> $tsla hate it at 40.  Love it at 1200!!  🍿

❤️🐒🍌.  🖕🐑

❤️👑🌈🦄

ObviousFOOKingly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:00:42 </td>
   <td style="text-align:left;"> $TSLA Never hedge with Tesla puts  lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 08:00:08 </td>
   <td style="text-align:left;"> $TSLA lol got blocked for saying the value here is speculative.  In a bear market that will have a tough time to hold up.  Use your fn brains. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:59:44 </td>
   <td style="text-align:left;"> $TSLA nailed it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:59:33 </td>
   <td style="text-align:left;"> $TSLA 149% TODAY on my $1040 PUTS ❗️😂⬇️💰💲💰⬇️😂❗️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:59:01 </td>
   <td style="text-align:left;"> $AMZN $AAPL $TSLA $SPY $BA ??? Yes we do dad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:58:56 </td>
   <td style="text-align:left;"> $SPY $DJIA $NFLX $PTON $TSLA 

Hard to have a FED-sponsored bull market without the FED!

LOL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:58:31 </td>
   <td style="text-align:left;"> $TSLA cash when you can this one will be down tomorrow 👃 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:58:20 </td>
   <td style="text-align:left;"> $TSLA lucid all the way. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:57:22 </td>
   <td style="text-align:left;"> $TSLA 850 next week . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:56:50 </td>
   <td style="text-align:left;"> $TSLA 700s end of month </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:56:17 </td>
   <td style="text-align:left;"> $SHOP I remember when this was $1,000 and $TSLA was $1,000 (pre-split)

Here we are about a year later &amp;amp; Tesla is $1,000 and this is $1,000… only Tesla did a 5/1 split lol. 

Just shows how far Tesla can drop. If it followed Shopify it would be at $200 rn. 

Investments man. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:55:56 </td>
   <td style="text-align:left;"> $TSLA bottom tomorrow… $3 EPS, higher margins, higher cash on hand, guidance for 2022 will be insanely good, Elon will announce the opening of giga Texas and give a nice roadmap, Tesla will be the game changer in this pullback in the market 1300-1400 next Friday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:55:45 </td>
   <td style="text-align:left;"> $TSLA ok bears , let’s see what you got. You have 3 days .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:55:23 </td>
   <td style="text-align:left;"> $NFLX  LOL. he done done it again! #CramerForPrison $NIO $AMD $PLTR $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:54:53 </td>
   <td style="text-align:left;"> $TSLA 

This is trading now at  25 P/E 2025 !!  50% discounted ! 

FYI !
In 2019 Hedge Garbage Funds traded this down to 3 multiple 
P/E  till it blowup in their faces and lost 40B !! 

When I say it’ll be a show to remember - I mean literally every word !! 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:54:41 </td>
   <td style="text-align:left;"> $TSLA Been buying since I sold last week. From 1222 to 994.. Up to 100 shares. Holding this bag till ER. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:54:40 </td>
   <td style="text-align:left;"> $NFLX $F $TSLA When CRAMER says buy.. ? Hmm I wait.. what would u do? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:53:22 </td>
   <td style="text-align:left;"> $TSLA sweet 

https://insideevs.com/features/562111/tesla-modelx-plaid-review-quickest/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:52:39 </td>
   <td style="text-align:left;"> $TSLA tomorrow will be a breeze </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:52:17 </td>
   <td style="text-align:left;"> $TSLA tomorrow will be bloody as hell...!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:52:01 </td>
   <td style="text-align:left;"> $SPY  $amzn &amp;lt;$3000 $TSLA &amp;lt;$1000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:51:56 </td>
   <td style="text-align:left;"> $TSLA $880 is the true double bottom ... see you there </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:51:00 </td>
   <td style="text-align:left;"> $TSLA 

Everything is dumping.  
Crypto is dumping. 

Let it all dump and load up. 

If you are on margin that’s a tough one. 

I own my Tesla shares outright. 
Holding them tight. 

Tesla will recover. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:48:38 </td>
   <td style="text-align:left;"> $TSLA Going lower. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:48:21 </td>
   <td style="text-align:left;"> $IWM $QQQ $SPY $TSLA Curious why stocks always seem to be dumped at the same time? Or why fundamentals haven&amp;#39;t matched valuations in 3 years? Or why volatility in the markets keeps increasing? 
 
Algorithmic trading needs to be slowed down. Retail investors are being hurt. 
 
https://youtu.be/FKh1kK6M9Yw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:47:48 </td>
   <td style="text-align:left;"> $TSLA NFLX retail going to flock to this to get back their gains for ER coming up? ☺️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:46:36 </td>
   <td style="text-align:left;"> $TSLA I would buy 1000 shares a $400 PS until then I’m short </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:46:11 </td>
   <td style="text-align:left;"> $TSLA --&amp;gt;Netflix shares fell in extended trading after reporting that it expects to add just 2.5 million subscribers this quarter, falling short of Wall Street’s estimates https://www.bloomberg.com/news/articles/2022-01-20/netflix-subscriber-forecast-misses-estimates-sending-stock-down?sref=pHyhiApD via @markets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:45:17 </td>
   <td style="text-align:left;"> $TSLA so many poor bear souls will get cooked in Elon&amp;#39;s oven again 🤣😂
 Gready scavengers marching on the sound of despair and  destruction  but instead of feast, after a single bite you become dinner yourselves as there is no corpse but a predator far superior to you waiting alive and well for you to check his mouth for pulse. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:45:01 </td>
   <td style="text-align:left;"> $TSLA prepare for the shit tomorrow dip guys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:44:35 </td>
   <td style="text-align:left;"> $TSLA this is really bad </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:43:28 </td>
   <td style="text-align:left;"> $SOFI With the only stock still Green is a good sign to go long on this dip!! This was the second chance we have to back the truck up to load on some more as people rotate from Tech and old Brick Banks to the Future of Fintech Banking, $SOFI! $NFLX latexf8b500e60d492738dc9b9617ed768f3eTSLA -20% since they smashed delivery record
$SOFI it&amp;#39;s a bank now! wake up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:43:23 </td>
   <td style="text-align:left;"> $TSLA $1400 after earnings? 😆Let’s do it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:43:07 </td>
   <td style="text-align:left;"> $TSLA just spoke to elon he said stock price is too high </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:43:05 </td>
   <td style="text-align:left;"> $nflx $spy $amzn $TSLA  
Account Challenge Update:~  
Start Date: Nov 2, 2021  
Starting Balance: $1,500  
Current Balance: $96,959  
Goal: $150,000 by end of January. 
✅ Expert Alerts  
Strategy: Swing Trade Options, Stocks  
  
Watch out for next play👓  discord.io/azQekkXp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:42:48 </td>
   <td style="text-align:left;"> $ARKK At least she dropped $TSLA 

Tesla is next in the list.
It&amp;#39;s going to be worse than $NFLX 

Buy $HOOD </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:41:36 </td>
   <td style="text-align:left;"> $TSLA 

Just in. 

Tesla to buy peloton and Netflix. 

Next they are planning an entrance into the Metaverse. 

Stand by. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:41:32 </td>
   <td style="text-align:left;"> $SLV $GLD $TSLA Just for the record for anybody who thinks he&amp;#39;s something special: Elon Musk is nothing but a grant-harvesting parasite who markets himself as a visionary with economically-sound ideas. Take away the counterfeited government paper stream and he and Tesla are nothing.  
  
Where is your food and housing inflation coming from? Counterfeited Fed paper printed from nothing given out to chumps like this with the pinch passed off to those who will never have a Tesla. 
 
Clownworld. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:40:44 </td>
   <td style="text-align:left;"> $TSLA 900 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:40:24 </td>
   <td style="text-align:left;"> $TSLA calls or puts tomorrow? Im thinking puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:40:23 </td>
   <td style="text-align:left;"> $TSLA https://www.etsy.com/listing/1159194621/tesla-uv-rated-decal?ref=shop_home_active_2&amp;amp;frs=1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:39:50 </td>
   <td style="text-align:left;"> $TSLA musk knew this baby was way overvalued </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:39:00 </td>
   <td style="text-align:left;"> $TSLA is not peloton or Netflix! Buy the car! The feeling is a little different then using a peloton device or watching Netflix </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:38:50 </td>
   <td style="text-align:left;"> $TSLA let’s make a put / short group just like they did with apes for calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:38:29 </td>
   <td style="text-align:left;"> $SPY  Yellen on tmr. She is a shill. Don&amp;#39;t trust anything she says. She takes money to show up and say what others pay her to. Becareful $TSLA $AAPL $MSFT $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:37:29 </td>
   <td style="text-align:left;"> $TSLA Betting on destruction and gloating about it. yep. very impressive character. smh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:36:32 </td>
   <td style="text-align:left;"> $TSLA You are the Next now…
#NFLX #AMZN #NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:35:47 </td>
   <td style="text-align:left;"> $TSLA fucking idiots feel like you are mooning? Hahaha. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:35:40 </td>
   <td style="text-align:left;"> $TSLA 1050 indefinite by noon 🦾🦾.. two red days not in this book </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:35:31 </td>
   <td style="text-align:left;"> $TSLA seen it to many times before </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:34:57 </td>
   <td style="text-align:left;"> $TSLA my 1100 calls are cooked. ..15k down the drain fml </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:34:38 </td>
   <td style="text-align:left;"> $TSLA this will be done going down when the Elon simps have thrown in the towel and disappear from here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:34:36 </td>
   <td style="text-align:left;"> $TSLA #AMZN #NVDA # NFLX and Next is your turn #TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:34:32 </td>
   <td style="text-align:left;"> $TSLA musk trapping as many bears as possible before earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:32:36 </td>
   <td style="text-align:left;"> $TSLA it’s on tomorrow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:32:30 </td>
   <td style="text-align:left;"> $TSLA back to $550-600…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:32:22 </td>
   <td style="text-align:left;"> $TSLA can’t wait for this to fall harder than $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:31:09 </td>
   <td style="text-align:left;"> $TSLA Bears coming out hard tomorrow! EVERYWHERE! Gap down pm 950 then we going to not cover and short even more down to 900! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:30:05 </td>
   <td style="text-align:left;"> $GOOG  $TSLA an actual good idea out of CA!!   1 every 20 yrs. 
California program offers  
$10K 
 in tuition assistance in exchange for community service  - 450 hrs, so $22 an hr.    
no freebies, make em earn it!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:29:30 </td>
   <td style="text-align:left;"> $TSLA technical analysis for tomorrow. 
 
https://youtu.be/60M3RNLU1jk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:29:25 </td>
   <td style="text-align:left;"> $TSLA all lines matter… until they don’t 😜
Step right up place your bets the house always wins. Buy and hold is easy but boy oh boy 🎲 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:29:09 </td>
   <td style="text-align:left;"> $TSLA $888 first stop, $600 followingthats bot even bottom </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:28:11 </td>
   <td style="text-align:left;"> $TSLA welcome to a q/e cycle </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:27:30 </td>
   <td style="text-align:left;"> $NFLX Shorted all the way back to pre-Covid levels. 
 
Pay attention to what&amp;#39;s happening if you&amp;#39;re holding tech long. 
 
$MSFT $FB $TSLA $SNAP </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:27:15 </td>
   <td style="text-align:left;"> $TSLA next like $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:26:45 </td>
   <td style="text-align:left;"> $TSLA in at 690 for more like last March </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:26:27 </td>
   <td style="text-align:left;"> $TSLA Can we please just get this bubble stock out of SPY already? Doesn&amp;#39;t belong. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:25:24 </td>
   <td style="text-align:left;"> $RIVN $TSLA $AMZN taking a shit in afterhours bulls better do something quick </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:24:43 </td>
   <td style="text-align:left;"> $TSLA Might be time for a call for run up into earnings. Can&amp;#39;t stand this company but money is money on a scalp. 
Maybe... It&amp;#39;s a maybe </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:24:20 </td>
   <td style="text-align:left;"> $TSLA $NASDAQ $DJIA Market spooked by a possible war with Russia? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:23:39 </td>
   <td style="text-align:left;"> $TSLA Need 100$ up day tomorrow

Papa musk please tweet something </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:22:58 </td>
   <td style="text-align:left;"> $TSLA  split this shit come onnnn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:22:57 </td>
   <td style="text-align:left;"> $TSLA if this keep going 950, 900 lotto puts can work wonders .... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:22:16 </td>
   <td style="text-align:left;"> $TSLA Market is sick. Short selling must be banned. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:21:46 </td>
   <td style="text-align:left;"> $TSLA mother fuckers  this goes up 200.00 after earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:20:53 </td>
   <td style="text-align:left;"> $NFLX $AAPL $TSLA $AMZN finaly these overinflated stocks started to crunch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:20:36 </td>
   <td style="text-align:left;"> $TSLA everyone thank this piece of shit president biden for what&amp;#39;s going on </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:20:29 </td>
   <td style="text-align:left;"> $TSLA Simulated Weekly 990.0 PUTS for Friday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:20:19 </td>
   <td style="text-align:left;"> MOVES HAPPENING NOW (6:20pm)

⦿ $TSLA is down 0.1% in the last 5 mins. 

⦿ There are 9 stocks that are up more than 3% in the last 5 mins. 

⦿ The top gainer is up 9.0% in the last 5 mins. 

 See the stocks that are moving the most right now via link in bio (wallstreetodds .com). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:20:13 </td>
   <td style="text-align:left;"> $SPY $AAPL $TSLA We&amp;#39;re in for a chop or a mild correction in the main index until Fed signals a slowing in tightening schedule. If buying dips be patient, don&amp;#39;t expect slingshot back to new highs, though always expect the unexpected. A 10 percent correction warrants the beginning of light bargain hunting. &amp;quot;Patience&amp;quot; as the inexperienced troll babies sardonically spout. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:20:12 </td>
   <td style="text-align:left;"> $TSLA 

This is going to end really bad and ugly for hedge garbage funds !

I’ll remind y’all !

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:20:11 </td>
   <td style="text-align:left;"> $TSLA @wallstreethottie anyone seen this clown lately?  Probably one of the biggest retards on this board.  Apparently all of the sudden is MIA. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:20:04 </td>
   <td style="text-align:left;"> $TSLA futures are bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:19:14 </td>
   <td style="text-align:left;"> $TSLA gap fill to 938 then light the rockets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:18:23 </td>
   <td style="text-align:left;"> $TSLA This is gonna be in the toilet tomorrow.. Netflix is gonna pull NASDAQ down badly </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:18:00 </td>
   <td style="text-align:left;"> Buy $TSLA and be part of  Tesla family.
Plenty of cake for anyone who wants sweet future 😊 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:17:52 </td>
   <td style="text-align:left;"> $TSLA Neflix is meaningless. Just make a simple mental experiment. Imagine, that Netlix goes BK tomorrow and shuts down it&amp;#39;s services. What does it change in the world? Absolutely nothing! Already during the same day everyone swtitches to another sreaming provider with about the same content and quality. 
 
Nobody really needs Netflix. I&amp;#39;m sorry, but it is the sad truth.  
Netlix is different to Tesla, Apple, Amazon. They can&amp;#39;t be replaced so easily and they really create something material and something very important. 
 
That is why stonk market always ignores the crazy volatility of Netflix (extended hours don&amp;#39;t matter) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:17:31 </td>
   <td style="text-align:left;"> $TSLA this is going to follow $ROKU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:17:28 </td>
   <td style="text-align:left;"> $TSLA you bulls..Netflix was just a warning </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:17:27 </td>
   <td style="text-align:left;"> $TSLA $QQQ Coca cola now has higher PE than $GOOG. The hedgies have gone full 🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:16:32 </td>
   <td style="text-align:left;"> $TSLA only down 5.5% YTD When rest of tech is down 15%+ .. this is due for a beating $950? $900? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:16:11 </td>
   <td style="text-align:left;"> $TSLA will tesla moon or do that netflix thing this Monday ?🤔🤧😩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:15:46 </td>
   <td style="text-align:left;"> $TSLA We all know how this is going to turn out. Bears, thank you for the cheap shares. This is going to run hard soon enough. We all know it. Bears, you are just taking credit for the job done by algos. Bunch of cowards, I love you still. 
 
Everybody stays calm and funny, we got this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:15:10 </td>
   <td style="text-align:left;"> $TSLA hope you don’t lose all your savings for this shorty stock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:14:58 </td>
   <td style="text-align:left;"> $SPY $TSLA $AMZN well shit.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:14:51 </td>
   <td style="text-align:left;"> $TSLA Off to a good start for tomorrow!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:14:32 </td>
   <td style="text-align:left;"> $TSLA I may be in trouble if this doesn&amp;#39;t go back up by the beginning of February. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:14:32 </td>
   <td style="text-align:left;"> $TSLA THE BIG SPLIT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:14:30 </td>
   <td style="text-align:left;"> $TSLA Off to a good start for tomorrow! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:14:27 </td>
   <td style="text-align:left;"> Unusual Options Activity: $TSLA is the #20 ticker with unusual activity from institutional traders with an average of 17% out of the money, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:13:48 </td>
   <td style="text-align:left;"> $TSLA 

When is this fat pig gonna drop like $PTON? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:13:29 </td>
   <td style="text-align:left;"> $TSLA Love to hate Elon MusKKK and his cult. Shorting this down to $700 stop if you can! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:12:53 </td>
   <td style="text-align:left;"> $TSLA .. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:12:50 </td>
   <td style="text-align:left;"> $TSLA she bought short of her own fund. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:12:42 </td>
   <td style="text-align:left;"> $TSLA OMG DIP OR LOSE ALL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:12:21 </td>
   <td style="text-align:left;"> $TSLA she bought short of her fund today unbelievable.😂😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:12:08 </td>
   <td style="text-align:left;"> $TSLA  fukkk the fagggg bears. Eat a 🥒 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:11:14 </td>
   <td style="text-align:left;"> $TSLA Biden economy will only make things worse. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:10:45 </td>
   <td style="text-align:left;"> $TSLA prepa for big hurriAbe. No1 can save us dips or lose all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:10:31 </td>
   <td style="text-align:left;"> $TSLA 3.1 Trillion in OPEX tomorrow. We could see a 10-20% move here easily. It will recover, but when it bottoms it’s gonna bottom hard. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:10:16 </td>
   <td style="text-align:left;"> $TSLA Oh boy, boy oh boy, when this will hit $700 and Elon Musk cult will go bankrupt, I will throw party to all my friends and family at my newly bought cottage! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:10:15 </td>
   <td style="text-align:left;"> $TSLA have you seen the market and this stock stays around 1k …. If you’re still a tsla bear you are delusional </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:09:38 </td>
   <td style="text-align:left;"> $TSLA lmao bears are spreading fears, these hand are diamonds 💎 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:09:03 </td>
   <td style="text-align:left;"> $TSLA wait what why </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:08:55 </td>
   <td style="text-align:left;"> $TSLA $BTC.X $SPY $QQQ 

bulls are in for a good humbling </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:08:18 </td>
   <td style="text-align:left;"> $TSLA  People blame &amp;quot;the suits&amp;quot; when overpriced stocks fall. If the suits are so powerful why is Tesla still at $1000? Because they don&amp;#39;t! Fair value is around $600 yet while other overpriced stocks are experiencing a correction that was long overdue, Tesla is still near ATH. The only explanation for this is the huge number of HODLers and Tesla/Elon Musk fans that don&amp;#39;t want to sell. It&amp;#39;s weird and rare to be honest but a correction will come one day, and the later the more violent it will be </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:07:45 </td>
   <td style="text-align:left;"> $TSLA Elon say something dude, </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:07:30 </td>
   <td style="text-align:left;"> $AMC $GME $NFLX $AMZN $TSLA Gary Gensler congratulations you are officially the Black Swan Captain retail is done. Guessing some hedge funds will follow soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:06:30 </td>
   <td style="text-align:left;"> $TSLA 1003 breakout tomorrow will be gorgeous. 1041 high today was the move. I LOVE THE PRICE RIGHT MEOW WOOOOOO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:06:11 </td>
   <td style="text-align:left;"> $BB don’t know how to execute positive news. They just can’t. 0 hopes while Chen is in charge. If he was a CEO of $TSLA then their stock would be $100, not $1000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:05:10 </td>
   <td style="text-align:left;"> $AMZN Aggressively bearish here, $2500 puts for this PoS because love to hate Jeff bezos. 
$TSLA $700 puts for this azzzzhole, again because love to hate this MF and his cult like gang! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:04:54 </td>
   <td style="text-align:left;"> $TSLA not looking so good right now! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:04:54 </td>
   <td style="text-align:left;"> $NFLX $TSLA 

If competition eating into Nflx growth, imagine what will happen to TSLA 🥴🤣🤣, </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:04:43 </td>
   <td style="text-align:left;"> $TSLA earnings will blow away. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:04:41 </td>
   <td style="text-align:left;"> $TSLA $950 tomorrow? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:04:28 </td>
   <td style="text-align:left;"> $TSLA 
$950 is almost certain </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:04:01 </td>
   <td style="text-align:left;"> $TSLA I’m convinced this is funding illegal activities. At this point there is no explanation for this lack of decline. This is the biggest bubble maybe of all time &amp;amp; they only reason anyone is invested is due to mass psychosis from the media saying it’s worth “$3,000 per share”. 

This should be in the $200’s at the high. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:03:37 </td>
   <td style="text-align:left;"> $TSLA To all You Biden Voters, Ya happy? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:03:20 </td>
   <td style="text-align:left;"> $TSLA if there is bad earnings this ps going 700$ Lito ticket to the big league </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:03:19 </td>
   <td style="text-align:left;"> $TSLA interest rate rise is not good for govt debt. I can do better job than Powell. 😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:02:58 </td>
   <td style="text-align:left;"> $TSLA 1050 lotto call for $160. Why not I&amp;#39;ll buy a bunch of those . Tomorrow they will be worth $400 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:02:47 </td>
   <td style="text-align:left;"> $TSLA remember when Jim Cramer told you all to just buy  U.S tech 😂 stocks when prices was already stretch. That loser never gets held accountable. Asia and South America is the  pivot folks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:02:47 </td>
   <td style="text-align:left;"> $TSLA oui kankir polara ki korse market. Madar chud. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:02:44 </td>
   <td style="text-align:left;"> $TSLA 🔥🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:02:02 </td>
   <td style="text-align:left;"> $TSLA what is going on with market? any type of event causing this? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:01:53 </td>
   <td style="text-align:left;"> $TSLA fake out before Q4 earnings 🥱 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:01:37 </td>
   <td style="text-align:left;"> $TSLA what the fuck happened today?
Holding 1100 calls and burnt </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:01:34 </td>
   <td style="text-align:left;"> $TSLA valuation reset incoming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:01:34 </td>
   <td style="text-align:left;"> $TSLA earnings next week going to be crazy in this market. Just look 👀 at $NFLX today. Good thing we have a strong guidance this year but going to be tough in this market to stay green. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:01:29 </td>
   <td style="text-align:left;"> $TSLA market feels crashy and Brandon is still sleeping We need Jesus to take the wheel to save us all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:00:59 </td>
   <td style="text-align:left;"> $TSLA the question one must is why did it go so high this morning? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:00:55 </td>
   <td style="text-align:left;"> $TSLA breaking down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:00:38 </td>
   <td style="text-align:left;"> $TSLA last time they raised cash was 2020. They’re due. 

Also, if this breaks $980, cya. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-21 07:00:22 </td>
   <td style="text-align:left;"> $TSLA I hope black swan event gap down tomorrow would love it if we do below 900 but under 950 LFG </td>
  </tr>
</tbody>
</table></div>

---
