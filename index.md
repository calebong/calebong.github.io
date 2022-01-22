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



Last Updated: 2022-01-22 09:42:08 UTC +8

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
   <td style="text-align:left;"> https://tradingeconomics.com/calendar?article=29130&amp;g=top&amp;importance=2&amp;startdate=2022-01-22 </td>
   <td style="text-align:left;"> 2022-01-22 09:11:08 </td>
   <td style="text-align:left;"> Week Ahead </td>
   <td style="text-align:left;"> The earnings season enters one of its busiest phases in the coming week, with Apple and Microsoft reporting quarterly results, while central banks in the US and Canada will be deciding on monetary policy. Elsewhere, flash PMI surveys for the US, UK, Eurozone, Japan and Australia will be keenly watched, as well as Q4 GDP updates from the US, Germany, France, Spain, South Korea, the Philippines, Hong Kong and Taiwan. Other key data to follow include US PCE prices, personal income and outlays; Eurozone business survey; China industrial profits; and Australia and New Zealand Q4 inflation data. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-22/the-fed-might-end-up-needing-to-actually-sell-some-of-its-bonds?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-22 08:40:58 </td>
   <td style="text-align:left;"> The Fed Might End Up Needing to Actually Sell Some of Its Bonds </td>
   <td style="text-align:left;"> The Marriner S. Eccles Federal Reserve building in Washington, D.C.                                                                                                                                                                                               , Benjamin Purvis                                                                                                                                                                                                                                                   , The process by which the Federal Reserve ultimately shrinks its balance sheet in the coming months or years will be different from the last time officials embarked on so-called quantitative tightening and could include outright sales from its bond portfolio., That’s the view of Credit Suisse Group AG strategist Zoltan Pozsar, who said that because any prospective QT now is about “keeping inflation and exuberance at bay,” then outright asset sales “are not at all unlikely” if circumstances dictate. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/01/21/world/russian-missile-test-debris-chinese-satellite-intl/index.html </td>
   <td style="text-align:left;"> 2022-01-22 08:22:44 </td>
   <td style="text-align:left;"> Debris from Russian missile test nearly strikes a Chinese satellite in  - CNN </td>
   <td style="text-align:left;"> (CNN)A piece of debris created by Russia's recent anti-satellite test came within striking distance of a Chinese satellite Tuesday, in an encounter the Chinese government has called "extremely dangerous."        , The Russian debris came as close as 14.5 meters (approximately 48 feet) from the satellite, according to the Space Debris Monitoring and Application Center of the China National Space Administration.              , If a collision did occur, it could've caused a "hypersonic shockwave," said Jonathan McDowell of the Harvard-Smithsonian Center for Astrophysics, who explained "it came close enough that it easily could have hit.", "A piece big enough to be tracked like this, it hits at 12,000 miles per hour, and you get a hypersonic shockwave going through the satellite that reduces it to shrapnel, to confetti," he said.                    , McDowell however, describes China's assertion the two objects came within such a specific distance as "nonsense because there's no way they can know it that accurately."                                            , Based on publicly available US space tracking data, McDowell says the two objects could have come within anywhere from a few hundred yards to a few inches of colliding.                                             , "The fact that it's still there means it didn't hit, but that's the only way you know that," McDowell said.                                                                                                          , Russia destroyed one of its own satellites last November in a direct-ascent anti-satellite missile test which has been condemned by US President Joe Biden's administration as dangerous and irresponsible.          , At the time, US Space Command said the test generated "more than 1,500 pieces of trackable orbital debris and will likely generate hundreds of thousands of pieces of smaller orbital debris."                       , CNN's Philip Wang contributed reporting. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/21/us/politics/biden-intel-semiconductors-china.html </td>
   <td style="text-align:left;"> 2022-01-22 08:12:41 </td>
   <td style="text-align:left;"> Biden Looks to Intel’s U.S. Investment to Buoy His China Agenda - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , The president said passage of a China competition bill was needed “for the sake of our economic competitiveness and our national security.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , transcript                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , This historic investment for Ohio, one of the largest investments in semiconductor manufacturing in American history: a brand new $20 billion campus outside of Columbus, Ohio. Semiconductors are small computer chips that power virtually everything in our lives — your phone, your car, your refrigerator, your washing machine. America invented these chips. Today, we barely produce 10 percent of the computer chips despite being the leader in chip design and research. We don’t have the ability to make the most advanced chips now — right now. But today, 75 percent of the production takes place in East Asia, 90 percent of the most advanced chips are made in Taiwan. China is doing everything it can to take over the global market. I want other cities and states to be able to make an announcement like the one being made here today, and that’s why I want to see Congress pass this bill right away and get it to my desk. Let’s get another historic piece of bipartisan legislation done. Let’s do it for the sake of our economic competitiveness and our national security., By David E. Sanger and Ana Swanson                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , WASHINGTON — In celebrating a $20 billion investment by Intel in a new semiconductor plant in Ohio, President Biden sought on Friday to jump-start a stalled element of his economic and national security agenda: a huge federal investment in manufacturing, research and development in technologies that China is also seeking to dominate.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , With two other major legislative priorities sitting moribund in Congress — the Build Back Better Act and legislation to protect voting rights — Mr. Biden moved to press for another bill, and one that has significant bipartisan support.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , But he has lost seven critical months since the Senate passed the measure, a sprawling China competition bill that would devote nearly a quarter of a trillion dollars to domestic chip manufacturing, artificial intelligence research, robotics, quantum computing and a range of other technologies. The bill amounts to the most expansive industrial policy legislation in U.S. history.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Speaking at the White House, Mr. Biden said that America was in a “stiff economic and technological competition” with China. He chose the words deliberately, knowing that while it sounds obvious to American ears, Chinese officials in recent months have protested the use of the word “competition,” declaring that it has echoes of a Cold War-like contest.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , “We’re going to insist everyone, including China, play by the same rules,” Mr. Biden continued. “We’re going to invest whatever it takes in America, in American innovation, in American communities, in American workers.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , He argued that the initiative would be a long-term solution to supply chain disruptions and rising inflation and would free American weapons systems from depending on foreign parts.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , After months in which he rarely mentioned the China competition bill so that he did not lose focus on other elements of his agenda, Mr. Biden said on Friday that its passage was needed “for the sake of our economic competitiveness and our national security.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , “Today, we barely produce 10 percent of the computer chips despite being the leader in chip design and research,” he said. “We don’t have the ability to make the most advanced chips now, right now.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Pervasive shortages of chips, which are needed to power everything from cars and washing machines to medical equipment and electrical grids, have forced some factories to shutter their production lines and knocked a full percentage point off U.S. growth last year, according to some estimates.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , While the Biden administration has billed Intel’s new investment near Columbus, Ohio, as a partial remedy for supply chain disruptions that have led to global chip shortages and spurred inflation, the project would do little to resolve any economic problems in the short term. The Ohio plant, the first phase of what Intel said could be an investment of up to $100 billion, is not expected to begin operation until 2025, and many analysts have forecast chip shortages to begin to abate later this year.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , But in addition to providing positive headlines for a beleaguered White House, Intel’s plans may help build momentum for a key element of Mr. Biden’s agenda that was set aside as lawmakers contended with ambitious bills on infrastructure, social spending and voting rights. Speaker Nancy Pelosi indicated on Thursday that House committees would soon turn to negotiations with the Senate to move the China competition legislation toward a vote.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , When the bill passed the Senate by a wide margin in June, it was sold in part as a jobs plan and in part as a move to avoid leaving the United States perilously dependent on its biggest geopolitical adversary.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , China is not yet a major producer of the world’s most advanced chips, and it does not have the capability to make semiconductors with the smallest circuits — in part because the United States and its allies have blocked it from purchasing lithography equipment needed to make those chips.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , But Beijing is pumping vast amounts of government funding into developing the sector, and it is also flexing its military reach over Taiwan, one of the largest manufacturers of advanced chips. China accounted for 9 percent of global chip sales in 2020, barely trailing the global market share of Japan and the European Union, according to the Semiconductor Industry Association. That was up from only 3.8 percent of global chip sales five years ago.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , At the World Economic Forum this week, Ursula von der Leyen, the president of the European Commission, announced plans for Europe to propose its own legislation early next month to promote the development of the semiconductor industry and to anticipate shortages.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , John Neuffer, the chief executive of the Semiconductor Industry Association, said Japan, South Korea, India and other countries were also introducing their own incentives in a bid to attract a strategically important industry.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , “The clock is ticking,” Mr. Neuffer said. “None of us are working in a vacuum. This is a global industry.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Mr. Biden’s push to enact the China competition bill comes amid growing frustration in corporate circles with his economic policies toward the country. Executives have complained that the administration still has not clarified whether it will lift any of the tariffs that President Donald J. Trump placed on China or how it will press Beijing for further trade concessions.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , The pandemic sparked the problem. The highly intricate and interconnected global supply chain is in upheaval. Much of the crisis can be traced to the outbreak of Covid-19, which triggered an economic slowdown, mass layoffs and a halt to production. Here’s what happened next:                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , A reduction in shipping. With fewer goods being made and fewer people with paychecks to spend at the start of the pandemic, manufacturers and shipping companies assumed that demand would drop sharply. But that proved to be a mistake, as demand for some items would surge.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Demand for protective gear spiked. In early 2020, the entire planet suddenly needed surgical masks and gowns. Most of these goods were made in China. As Chinese factories ramped up production, cargo vessels began delivering gear around the globe.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Then, a shipping container shortage. Shipping containers piled up in many parts of the world after they were emptied. The result was a shortage of containers in the one country that needed them the most: China, where factories would begin pumping out goods in record volumes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Demand for durable goods increased. The pandemic shifted Americans’ spending from eating out and attending events to office furniture, electronics and kitchen appliances – mostly purchased online. The spending was also encouraged by government stimulus programs.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Strained supply chains. Factory goods swiftly overwhelmed U.S. ports. Swelling orders further outstripped the availability of shipping containers, and the cost of shipping a container from Shanghai to Los Angeles skyrocketed tenfold.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Labor shortages. Businesses across the economy, meanwhile, struggled to hire workers, including the truck drivers needed to haul cargo to warehouses. Even as employers resorted to lifting wages, labor shortages persisted, worsening the scarcity of goods.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Component shortages. Shortages of one thing turned into shortages of others. A dearth of computer chips, for example, forced major automakers to slash production, while even delaying the manufacture of medical devices.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , A lasting problem. Businesses and consumers reacted to shortages by ordering earlier and extra, especially ahead of the holidays, but that has placed more strain on the system. These issues are a key factor in rising inflation and are likely to last for months — if not longer.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , The bill that passed the Senate, known as the U.S. Innovation and Competition Act, contains a range of provisions aimed at spurring the U.S. economy to take on China, but its centerpiece is $52 billion in federal investments to encourage chip research, design and manufacturing in the United States.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , The chip funding itself has broad bipartisan support and could be passed into law as soon as the next few months, supporters say; the question is whether other measures that have been tucked in the package will sink its prospects. The Senate bill includes a number of trade-related provisions that some House Democrats may oppose, including an investigation into foreign digital trade practices.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , The global shortage of chips and the pernicious inflation that has accompanied it have spurred more interest in enticing semiconductor manufacturing to the United States. But whether Congress approves billions of dollars in new funding — and how the Biden administration decides to distribute it — appears likely to determine whether an investment like Intel’s is a one-time occurrence or a trend.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Companies including Taiwan Semiconductor Manufacturing Company, Texas Instruments, Micron Technology and SK Group have all announced recent expansions in the United States. Samsung has promised a $17 billion facility in Texas, while GlobalFoundries has committed to a second factory in New York.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , But the center of gravity for the global industry is still in East Asia. While the United States accounts for much cutting-edge research and design in the chip industry, it has gone from being the world’s largest producer of semiconductors several decades ago to mostly outsourcing production to Asian factories.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , That has proved to be a vulnerability as pandemic-related shutdowns left companies around the world short of workers and raw materials, leading to shortages and spiraling prices for a variety of goods, especially semiconductors. Automakers in particular have been affected, with almost every major carmaker forced to curtail production last year.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , Chip shortages have also become one of the largest single factors stoking inflation, now a key gripe among American voters as the midterm elections approach. Inflation hit a 40-year high in December, buoyed by a 37 percent increase in the price of used cars.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , In an effort to ease the chip shortages, the Biden administration has convened gatherings with semiconductor executives, established a global alert system to identify shortages and requested vast amounts of information from chip companies on potential bottlenecks. The Commerce Department is expected to release some of that information publicly before the end of the month.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Gina Raimondo, the commerce secretary, said in a statement on Friday that Intel’s investment was a win for the company, for American manufacturing and for “American consumers who can look forward to lower prices as we bring home production of the semiconductors that keep our economy running.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , But analysts say the administration has little control over any short-term trends in the industry, given the long lead times necessary to build semiconductor facilities.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Mr. Neuffer said his industry applauded the attention the White House was giving to the sector, including encouraging companies to share more information. “But the reality is, there’s only so much government can do,” he said. “These are very complicated, deep global supply chains, and the market is just going to have to work through this.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Catie Edmondson contributed reporting.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/01/21/asia/thich-nhat-hanh-death-intl/index.html </td>
   <td style="text-align:left;"> 2022-01-22 08:12:39 </td>
   <td style="text-align:left;"> Buddhist monk and peace activist Thich Nhat Hanh dead - CNN </td>
   <td style="text-align:left;"> (CNN)Thich Nhat Hanh, a prominent Vietnamese Buddhist monk, peace activist and leading voice in opposition to the Vietnam War, has died at Tu Hieu Temple in Hue, Vietnam. He was 95.                                                                                                              , The monastic organization that he founded, Plum Village, announced the news on their website.                                                                                                                                                                                                       , Plum Village said Thich Nhat Hanh passed away "peacefully" on Saturday morning local time.                                                                                                                                                                                                          , "Thay [Thich Nhat Hanh] has been the most extraordinary teacher, whose peace, tender compassion, and bright wisdom has touched the lives of millions," the Plum Village statement said.                                                                                                             , "Whether we have encountered him on retreats, at public talks, or through his books and online teachings -- or simply through the story of his incredible life -- we can see that Thay [Thich Nhat Hanh] has been a true bodhisattva, an immense force for peace and healing in the world," it said., Thich Nhat Hanh traveled to the US in 1961 to teach comparative religion at Princeton University. Later that decade, he lectured at Cornell and Columbia University, where he continued to spread a message of peace and lobbied Western leaders to end the Vietnam War, Plum Village said.         , In 1967, Dr. Martin Luther King, Jr. nominated Thich Nhat Hanh for the Nobel Peace Prize, calling him "an Apostle of peace and nonviolence." However, no Nobel Peace Prize was awarded that year.                                                                                                   , Thich Nhat Hanh's mission of opposing the war led to both North Vietnam and South Vietnam denying him to the right to return to either nation for decades.                                                                                                                                          , He was exiled for 39 years and was only given the permission to return to his homeland in 2005.                                                                                                                                                                                                     , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-22/london-leads-record-jump-in-u-k-first-time-house-buyers?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-22 08:01:00 </td>
   <td style="text-align:left;"> London Leads Record Jump in U.K. First-Time House Buyers </td>
   <td style="text-align:left;"> Residential houses in London.                                                                                                                                                                                                                            , David Goodman                                                                                                                                                                                                                                            , London led a record increase in the number of first-time home buyers in the U.K. last year, as a flurry of market activity caused by the stamp duty cut freed up space at the bottom of the property ladder.                                             , The number of people buying their first home increased to 409,370 last year, the mortgage lender Halifax said in a report Saturday. That’s up 35% from the level of 2020 when lockdowns choked back activity. The capital alone saw a jump of almost 50%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-22/china-s-wild-markets-raise-stakes-for-traders-buying-into-rally?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-22 08:00:00 </td>
   <td style="text-align:left;"> China’s Wild Markets Raise Stakes for Traders Buying Into Rally </td>
   <td style="text-align:left;"> Sofia Horta e Costa                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     ,  and Rebecca Choong Wilkins                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , The battle between fear and greed is wreaking havoc in Chinese financial markets.                                                                                                                                                                                                                                                                                                                                                                                                                       , While China bulls are finally getting some vindication as the nation’s stocks and bonds rally, the past week shows investors need to be prepared for violent swings. Take Country Garden Holdings Co., the nation’s largest developer. On Monday, its 2024 bond plunged 10 cents on the dollar to trade like a stressed asset, only to surge by a record 14 cents two days later. The Hang Seng China Enterprises Index was down for five straight days before rallying the most since July on Thursday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/01/21/south-africa-omicron-covid-mckenzie-pkg-lead-vpx.cnn </td>
   <td style="text-align:left;"> 2022-01-22 07:40:12 </td>
   <td style="text-align:left;"> What life looks like on other side of the Omicron surge - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-21/peru-groups-agree-to-services-deal-with-mmg-mine-after-protests?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-22 07:16:51 </td>
   <td style="text-align:left;"> Peru Groups Agree to Services Deal With MMG Mine After Protests </td>
   <td style="text-align:left;"> Maria Cervantes                                                                                                                                                                                                                                                                                                                                                  , Community groups in Peru agreed to provide trucking services to MMG Ltd.’s Las Bambas copper mine in a deal hammered out after tensions led to protests and blockades near the site last month.                                                                                                                                                                  , Las Bambas will provide the Chumbivilcas communities with technical assistance, legal advice and business training, Carlos Castro, manager of corporate affairs at MMG’s Las Bambas, said in an interview. The goal in the medium and long term is to enable the community companies to grow and provide the services to other mining companies as well, he said. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-21/microstrategy-plummets-as-sec-rejects-its-bitcoin-accounting?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-22 07:03:41 </td>
   <td style="text-align:left;"> MicroStrategy Plummets as SEC Rejects Its Bitcoin Accounting </td>
   <td style="text-align:left;"> Nicola Raghunathan                                                                                                                                                                                                                                                        , MicroStrategy Inc. can’t strip out Bitcoin’s wild swings from the unofficial accounting measures it touts to investors, the SEC said.                                                                                                                                     , Bad news for the MicroStrategy was compounded as the company’s shares fell as much as 20% Friday, the biggest intraday collapse since Feb. 23. Its stock closed at $375.89, down nearly 18%. Bitcoin also tumbled, and was down more than 7% around 4:15 p.m. in New York. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/01/21/europe/gallery/ukraine-russia-fadek/index.html </td>
   <td style="text-align:left;"> 2022-01-22 06:56:22 </td>
   <td style="text-align:left;"> Photos: On the front lines, Ukrainians brace for possible attack </td>
   <td style="text-align:left;"> About 500 yards away from Russian-backed separatists, a group of Ukrainian soldiers waits for a fight it's sure is coming.                                                                                                                                                                                                                                                                                                                                                  , And the men are strangely relaxed about it all, according to photographer Timothy Fadek, who spent time with the soldiers Friday on the front lines in Ukraine's eastern Luhansk region.                                                                                                                                                                                                                                                                                    , "They have embraced the inevitability," Fadek said. "I was talking to one of the soldiers and he said: 'It's inevitable. We've accepted this inevitability of an attack.' And then there was a little bit of an argument between two soldiers. One said, 'The Russians will not come across the border, they will attack from the sea,' meaning the Sea of Azov. Another soldier disagreed with both those assessments and said, 'No, the attack will come from Belarus.' " , But while they might not agree with where an attack will come from, they are all 100% convinced it is going to happen.                                                                                                                                                                                                                                                                                                                                                      , "They've resigned themselves," Fadek said. "But they're extremely relaxed. There is not a hint of nervousness in their faces. They're ready to fight. They've been ready for many years now. They don't want to. I asked them, 'Do you want this war?' And they're like, 'Of course not.' "                                                                                                                                                                                 , Tensions between Ukraine and Russia are at their highest in years, with a Russian troop buildup near the border spurring fears that Moscow could soon launch an invasion. The Kremlin has denied it is planning to attack, arguing that NATO support for Ukraine constitutes a growing threat on Russia's western flank.                                                                                                                                                    , In Muratova, a Ukrainian town about a 20-minute drive from the front lines, people are much more nervous than the soldiers, Fadek said. But they, too, seem to be resigned to their fate.                                                                                                                                                                                                                                                                                   , When asked what he thinks about the possibility of an attack, one farmer shrugged his shoulders.                                                                                                                                                                                                                                                                                                                                                                            , "It will happen," he said, "but there's nothing anyone can do to stop it." </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/live/2022/01/21/business/stock-market-economy-news/citigroup-will-bring-nyc-area-workers-back-to-the-office-starting-feb-7 </td>
   <td style="text-align:left;"> 2022-01-22 06:37:12 </td>
   <td style="text-align:left;"> Stocks drop again, dragging the S&amp;P 500 to its biggest weekly loss in nearly two years. - The New York Times </td>
   <td style="text-align:left;"> Follow our latest coverage of business, markets and economy.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , By Coral Murphy Marcos                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Data delayed at least 15 minutes                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Source: FactSet                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , By: Ella Koeze                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Stocks fell for a fourth day in a row on Friday, adding to a stretch of losses that has come as investors worried about corporate profits and rising interest rates and pushing the S&amp;P 500 to its worst week since the early days of the pandemic.                                                                                                                                                                                                                                                                                                                    , The S&amp;P 500 fell 1.9 percent on Friday, and 5.7 percent for the week — its sharpest weekly drop since March 2020, when markets plunged as countries started to impose lockdowns and businesses closed down.                                                                                                                                                                                                                                                                                                                                                            , Since the start of the year, investors have been concerned that fast rising interest rates might hurt corporate profits and dampen demand for risky investments like stocks. A string of disappointing earnings reports recently from companies as varied as Netflix, American Airlines and Goldman Sachs only made matters worse.                                                                                                                                                                                                                                     , “The sell-off appears to be driven by the earnings stories that are coming out,” said Anu Gaggar, global investment strategist for Commonwealth Financial Network. “The guidance seems to be less upbeat. When they start looking into 2022, they talk about growth slowing.”                                                                                                                                                                                                                                                                                          , Late Thursday, for example, the streaming giant Netflix delivered a less-than-optimistic forecast, saying it expected subscriber growth to slow in the opening months of 2022. Its shares slid 21.8 percent on Friday.                                                                                                                                                                                                                                                                                                                                                 , Netflix was a favorite of investors early in the pandemic, rising 67 percent in 2020 as lockdowns prompted a surge of subscriptions. Its growth is slowing as the world reopens and people head outdoors again, and as it faces a number of strong streaming competitors from Disney+ to HBO Max.                                                                                                                                                                                                                                                                      , Shares of pandemic-era darlings, including Peloton, Zoom and Etsy, have also suffered sharp declines. Peloton said on Thursday that it was considering layoffs and changes to its production as demand slowed. Its shares rose 11.7 percent on Friday but were still down 13.6 percent this week.                                                                                                                                                                                                                                                                      , Zoom was down more than 7 percent this week and Etsy dropped about 9 percent.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Wall Street’s big banks have warned that rising wages for their workers could affect profits, while airlines earnings were hammered by the Omicron variant of the coronavirus.                                                                                                                                                                                                                                                                                                                                                                                         , Separately, concerns over higher interest rate have hit technology stocks particularly hard, pulling the Nasdaq composite down 7.6 percent for the week, and about 12 percent since the start of the year. The index fell 2.7 percent on Friday.                                                                                                                                                                                                                                                                                                                       , The decline began early in the month as the Federal Reserve began to signal that it would move aggressively to raise interest rates this year as it tries to control rising prices. Higher rates can discourage investment in riskier assets and raise the cost of borrowing for fast-growing companies, both of which can hurt technology stocks.                                                                                                                                                                                                                     , The central bank will meet next week, its first meeting of the year, giving officials a chance to offer more guidance on their thinking about rate increases to come in 2022.                                                                                                                                                                                                                                                                                                                                                                                          , “The key question for the markets is: Will the Fed give them a breather or keep moving?” Ethan S. Harris, an economist at Bank of America Global Research, wrote in a note on Friday. “We tend to lean toward the latter. The Fed was clearly caught wrong footed in the second half of last year and rather than do a 180 degree policy turn in one go, we see them moving in stages.”                                                                                                                                                                                , Cryptocurrencies are also getting pummeled this week. Bitcoin, the largest cryptocurrency, is hovering slightly above $38,000, according to CoinDesk, and down more than 10 percent from Thursday. The cryptoasset has faced a huge sell-off since it reached its high of $68,000 in November.                                                                                                                                                                                                                                                                         , The digital currency is also facing headwinds overseas. Russia’s central bank proposed on Thursday a ban on the use of cryptocurrencies in the country, pointing to its volatility and ties to illegal activities. Also, in early January, violent protests against the government in Kazakhstan led to intermittent internet shutdowns, disrupting large cryptocurrency mining operations in the country.                                                                                                                                                             , Shares of Coinbase, a cryptocurrency exchange platform, fell 13.4 percent on Friday. Shares of the electric vehicle maker Tesla, which purchased $1.5 billion in Bitcoin last year, were down 5.3 percent.                                                                                                                                                                                                                                                                                                                                                             , By Lananh Nguyen                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , As the threat of the Omicron variant of the coronavirus shows signs of fading in New York, Wall Street banks are preparing to bring their workers back.                                                                                                                                                                                                                                                                                                                                                                                                                , Citigroup told employees in the metropolitan area that they should be ready to return to the office from Feb. 7, according to a person familiar with the policy who spoke on condition of anonymity to discuss personnel matters. Those workers will be expected to come in at least two days a week, although those in other parts of the country are still being asked to work remotely, the person said.                                                                                                                                                            , Wall Street banks postponed their return-to-office plans — in some cases, more than once — around the holidays as virus cases surged. But major financial firms have coalesced around early-February targets to bring staff members back, with Goldman Sachs and JPMorgan Chase both planning for Feb. 1.                                                                                                                                                                                                                                                              , While Citigroup is giving employees a little more time, it said earlier this month that it would dismiss any employees who remained unvaccinated by the end of January. The bank said the policy prompted a flurry of vaccinations.                                                                                                                                                                                                                                                                                                                                    , Bank executives have been cheerleaders for in-office working during much of the pandemic, particularly after vaccines became widely available last year. But the surge in cases from the Omicron variant upended return-to-office plans for big companies in Manhattan. Almost a quarter of big employers surveyed recently by the Partnership for New York City, a business advocacy group, said they could not estimate when their offices would reach even half capacity.                                                                                           , By Lananh Nguyen                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Morgan Stanley awarded its chief executive, James Gorman, a 6 percent raise, maintaining his position as the highest-paid head of a U.S. bank — for now.                                                                                                                                                                                                                                                                                                                                                                                                               , Mr. Gorman’s 2021 compensation was $35 million, up $2 million from a year earlier, the bank said in a filing on Friday. The pay bump came after the investment bank reported $15 billion in profit last year, the highest in its history.                                                                                                                                                                                                                                                                                                                              , In raising his pay, Morgan Stanley’s board cited Mr. Gorman’s “outstanding individual performance,” that steered the firm to record earnings and helped it meet or exceed two-year targets. His pay package comprised a base salary of $1.5 million, a cash bonus of $8.4 million and the rest in deferred or performance-linked stock.                                                                                                                                                                                                                                , That puts Mr. Gorman just ahead of JPMorgan Chase’s chief, Jamie Dimon, who on Thursday received a raise of almost 10 percent, taking his compensation to $34.5 million. JPMorgan’s board similarly cited Mr. Dimon’s performance after a year of record profit.                                                                                                                                                                                                                                                                                                       , Other Wall Street firms are expected to provide updates on their leaders’ compensation later this month. Top bankers have said their firms are having to increase pay because of intense competition for talent.                                                                                                                                                                                                                                                                                                                                                       , By Niraj Chokshi                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , The Biden administration said on Friday that it would suspend 44 flights from the United States to China operated by Chinese airlines in retaliation for China’s imposing similar restrictions on American companies in recent weeks.                                                                                                                                                                                                                                                                                                                                  , The Chinese government has canceled the flights, operated by American Airlines, Delta Air Lines and United Airlines, after passengers on their planes tested positive for the virus after arriving in China. The passengers had tested negative before getting on their planes.                                                                                                                                                                                                                                                                                        , In the order on Friday, the U.S. Transportation Department described the suspensions by China, which run through early March, as punitive and unfair.                                                                                                                                                                                                                                                                                                                                                                                                                  , China’s aviation authority canceled the flights using a “circuit breaker” provision intended to allow the country to limit the spread of the virus. According to the U.S. order, China’s policies allow airlines that deliver passengers who later test positive for the virus to choose either a two-week suspension of the offending flight or a four-week limit on the number of passengers on that flight. The U.S. companies were never given that choice, and were denied the four-week notice promised under Chinese policy, the Transportation Department said., “The Chinese government individually clears each and every potential traveler for travel to China prior to their departure from the United States, after verifying predeparture test results and other required documentation,” Carol A. Petsonk, a top aviation official in the department, wrote in the order. “U.S. carriers, who are following all relevant Chinese regulations with respect to predeparture and in-flight protocols, should not be penalized if passengers, postarrival, later test positive for Covid-19.”                                       , The order suspends 44 flights from the United States to China scheduled from Jan. 30 to March 29. The affected flights are operated by Air China, China Eastern Airlines, China Southern Airlines and Xiamen Airlines. Most were scheduled to depart from Los Angeles, with the others departing from New York. France and Germany have taken similar actions in response to China’s use of the circuit breaker policy.                                                                                                                                                , Early in the pandemic, Chinese officials barred U.S. airlines from operating passenger flights into their country, prompting the Trump administration to retaliate. The dispute eventually subsided, and limited flights between the countries resumed more than a year ago.                                                                                                                                                                                                                                                                                           , Delta and United did not immediately respond to requests for comment. American deferred to Airlines for America, a trade group, which said in a statement that it was “supportive of the actions taken by the Department of Transportation to ensure the fair treatment of U.S. airlines in the Chinese market.” The Civil Aviation Administration of China, the country’s aviation authority, could not immediately be reached for comment.                                                                                                                           , By David McCabe                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Google asked a federal court on Friday to dismiss an antitrust lawsuit led by the State of Texas, the first time it has sought to have one of the government competition cases against it thrown out in the United States.                                                                                                                                                                                                                                                                                                                                             , In a filing, Google said the state had failed to show that it engaged in anticompetitive behavior and hadn’t proved that an agreement between Facebook and Google, a core part of the case, violated the law.                                                                                                                                                                                                                                                                                                                                                          , “We’re confident that this case is wrong on the facts and the law, and should be dismissed,” said Adam Cohen, the company’s director of economic policy.                                                                                                                                                                                                                                                                                                                                                                                                               , The Texas lawsuit argues that Google has obtained and abused a monopoly over the labyrinthine set of systems that allow publishers to auction off ad space to marketers. The states argue that Google misled publishers and advertisers about the nature of the ad auctions, allowing it to pocket more of the money flowing through its ad systems. And they say the company used a deal with Facebook to maintain its dominance when the publishers tried to develop an alternative system.                                                                          , “Despite amassing a lengthy collection of grievances, each one comes down to a plea for Google to share its data or to design its products in ways that would help its rivals,” Google said in its filing.                                                                                                                                                                                                                                                                                                                                                             , Texas’ attorney general, Ken Paxton, said in a statement: “Google’s motion attributes their monopoly status to pure success on the merits. The company whose motto was once ‘Don’t Be Evil’ now asks the world to examine their egregious monopoly abuses and see no evil, hear no evil, and speak no evil.”                                                                                                                                                                                                                                                           , Google faces pressure from governments around the world. In addition to the lawsuit from Texas and more than a dozen other states, the federal government and a different group of states have sued the company, arguing it has abused a monopoly over online search. On Thursday, a Senate committee endorsed an antitrust law meant to crack down on some of its practices — along with Amazon’s and Apple’s — and European lawmakers in Brussels are considering their own new digital antitrust rules.                                                             , Google is also not the first tech giant to try to get a recent government antitrust case dismissed. Last year, Facebook asked a federal court to throw out lawsuits filed against it by the Federal Trade Commission and a collection of states. The judge in the case initially agreed. But the F.T.C. refiled its lawsuit, and the judge said this month that it could move forward. The states have appealed.                                                                                                                                                       , By Mark Miller                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , The national network of Social Security customer service offices, which were closed nearly two years ago at the start of the pandemic, is on track to reopen on March 30.                                                                                                                                                                                                                                                                                                                                                                                              , The Social Security Administration and unions representing the agency’s work force agreed this week to reopen more than 1,200 offices, contingent on changes in pandemic conditions and further negotiations. Bargaining is set to conclude by March 1, which would allow 30 days to plan for the office re-entry.                                                                                                                                                                                                                                                     , “This agreement will allow all the parties to wait and see what happens with the latest wave of the pandemic,” said Rich Couture, chief negotiator for the American Federation of Government Employees, one of three unions representing the agency work force involved in the talks. “Hopefully it subsides, but if it doesn’t, we can take further action to postpone the reopening if necessary.”                                                                                                                                                                   , Social Security field offices handle benefit claims for retirement and Medicare. But they also assist with applications for Social Security Disability Insurance and Supplemental Security Income, the benefit program for low-income, disabled or older people. Since the pandemic began, nearly all public service has been available only online, and by phone and mail, and the agency work force of nearly 60,000 has operated virtually. Office visits are available only by appointment and only for a limited number of critical issues.                       , Processing of Social Security retirement benefits and Medicare claims has not been impaired during the office shutdown, agency records show. But there were sharp drops in 2020 in benefit awards for Supplemental Security Income and disability insurance.                                                                                                                                                                                                                                                                                                           , Social Security had earlier announced a tentative plan for employees to return to the offices on Jan. 3. But that date was postponed because of disagreements between the agency and unions over specifics of the plan.                                                                                                                                                                                                                                                                                                                                                , The new agreement calls for all employees and visitors to wear masks while at Social Security facilities, regardless of their vaccination status. Under the agency’s original plan, visitors who stated that they were vaccinated would have been permitted to forgo masks. The agreement also calls for negotiations between the agency and various segments of the work force over the specifics of each group’s reopening plan.                                                                                                                                     , “Our main concern is to keep employees and the visiting public safe and healthy,” Mr. Couture said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , The details on office reopenings, including hours of operation, are still being negotiated, but are expected to be announced in March. The agency also plans to continue to allow telework to varying degrees for different jobs.                                                                                                                                                                                                                                                                                                                                      , During the transition, the agency advises people to use its website wherever possible or to call its national toll-free number, 800-772-1213, as a starting point to receive assistance.                                                                                                                                                                                                                                                                                                                                                                               , By Kellen Browning                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , A group of workers at Raven Software, a studio owned by Activision Blizzard, said Friday that they were forming a union and wanted the prominent video game company to voluntarily recognize it.                                                                                                                                                                                                                                                                                                                                                                       , The new union, the Game Workers Alliance, says it includes more than 80 percent of the 34 people in the quality assurance division of Raven, the Wisconsin studio that helps create Activision’s popular Call of Duty game. More than 60 Raven employees walked out in early December, protesting the company’s ending of the contracts of a dozen temporary Raven quality assurance workers, which they said felt abrupt and unfair. Some have been on strike since then.                                                                                             , “This is just the best thing for us and our company going forward, for us to have a voice,” said Erin Hall, a Raven quality assurance worker who helped organize the union. She said she hoped that unionizing would lead to better job security, and that the Game Workers Alliance would be just “the first domino at Activision.”                                                                                                                                                                                                                                   , “I think a lot of us are motivated a lot by the fact that unionization in the games industry hasn’t really happened yet,” Ms. Hall said.                                                                                                                                                                                                                                                                                                                                                                                                                               , Now, Activision executives will have to decide whether to recognize the union voluntarily or force a vote among employees, which the National Labor Relations Board would oversee. Activision said in a statement that it was “carefully reviewing” the request.                                                                                                                                                                                                                                                                                                       , “While we believe that a direct relationship between the company and its team members delivers the strongest work force opportunities, we deeply respect the rights of all employees under the law to make their own decisions about whether or not to join a union,” the company said in the statement. Activision added that it had increased pay, time off and medical benefits for the unionizing workers in recent years.                                                                                                                                         , Activision, which Microsoft on Tuesday said it would buy for nearly $70 billion, has been dealing with months of employee unrest. Before the company incited anger by not keeping the Raven workers in December, employees had been pushing for labor organizing and better treatment since July, when a California employment agency sued Activision, accusing it of fostering a culture where women were routinely sexually harassed and discriminated against.                                                                                                      , Jessica Gonzalez, a former Activision worker and one of the organizers of ABetterABK, a group of activists that formed in the wake of the lawsuit to improve conditions at Activision and its Blizzard and King units, said she hoped the Raven union, though small, would galvanize more labor efforts at the company — which has about 10,000 employees — and at other gaming publishers.                                                                                                                                                                            , “I think it’ll have a ripple effect across the industry,” Ms. Gonzalez said. “I’m hoping the rest of ABK will join our mission and help push this movement forward.”                                                                                                                                                                                                                                                                                                                                                                                                   , In contrast to Europe, unions are rare in the North American gaming industry. American employees are often subjected to unexpected layoffs and brutal “crunch,” in which they are required to work long hours and weekends for weeks at a time to ensure games do not miss deadlines.                                                                                                                                                                                                                                                                                  , Interest in unionization has picked up in recent years, with groups like Game Workers Unite, Game Workers of Southern California and the Campaign to Organize Digital Employees, a project from the Communications Workers of America, all working to mobilize gaming employees.                                                                                                                                                                                                                                                                                       , In December, workers at the independent game developer Vodeo Games, which has about a dozen employees, became the first video game studio union in North America.                                                                                                                                                                                                                                                                                                                                                                                                      , The Raven employees’ organizing effort was shepherded by C.W.A., a prominent tech, media and communications union.                                                                                                                                                                                                                                                                                                                                                                                                                                                     , “A collective bargaining agreement will give Raven QA employees a voice at work, improving the games they produce and making the company stronger,” Sara Steffens, C.W.A.’s secretary-treasurer, said in a statement. “Voluntary recognition is the rational way forward.”                                                                                                                                                                                                                                                                                             , In a news release announcing the union, C.W.A. and the Game Workers Alliance accused Activision of using “surveillance and intimidation tactics, including hiring notorious union busters, to silence workers.”                                                                                                                                                                                                                                                                                                                                                        , Ms. Hall and C.W.A. both said the timing, given Microsoft’s blockbuster acquisition of Activision, was coincidental. Microsoft declined to comment on the union organizing.                                                                                                                                                                                                                                                                                                                                                                                            , Some workers view Microsoft’s purchase of the company, which could take a year or more to close, as a path for Activision to improve its workplace culture.                                                                                                                                                                                                                                                                                                                                                                                                            , Others see it as an easy out for the company’s embattled chief executive, Bobby Kotick, who has been under fire since last summer and is expected to step down as chief executive once the deal is complete, two people with knowledge of his plans have said.                                                                                                                                                                                                                                                                                                         , During a company livestream on Thursday with Julie Hodges, Activision’s chief people officer, Mr. Kotick told employees that he had promised Microsoft that he would “stay as long as is necessary to ensure that we have a great integration and a great transition,” according to a transcript of the conversation viewed by The New York Times.                                                                                                                                                                                                                     , Mr. Kotick also addressed Activision's culture problems, saying the Microsoft deal “reinforces” his commitment to reforming the workplace, “and we’ve certainly recognized that we have opportunities for improvement.”                                                                                                                                                                                                                                                                                                                                                , He added that Microsoft “has been on its own journey to improve its workplace, and I think that it’s a shared journey.”                                                                                                                                                                                                                                                                                                                                                                                                                                                , By Alan Rappeport                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , WASHINGTON — Treasury Secretary Janet L. Yellen described the Biden administration’s approach to managing the United States economy as “modern supply side economics” on Friday, putting a liberal twist on the Reagan-era economic philosophy of tax cuts and deregulation as the White House looks to curb rising prices and drive productivity.                                                                                                                                                                                                                     , The comments came as President Biden’s economic agenda is at a crossroads, with inflation at its highest level in decades and Democrats’ social safety net and climate spending package stalled in Congress. Ms. Yellen argued that Democrats are not merely calling for traditional policies of taxing and spending, but introducing a new model to create enduring economic growth.                                                                                                                                                                                  , “Our new approach is far more promising than the old supply side economics, which I see as having been a failed strategy for increasing growth,” Ms. Yellen said. “Significant tax cuts on capital have not achieved their promised gains.”                                                                                                                                                                                                                                                                                                                            , Ms. Yellen cast in a new light many policies the Biden administration has already been promoting: infrastructure investment, more money to combat climate change and spending on early childhood education to let more parents join the labor force. She said this version of supply side economics, rather than spurring growth by cutting taxes and loosening regulation, will make the economy more productive while reducing inequality.                                                                                                                           , “The lagging labor force participation rate is driven in large part by a combination of factors that disincentivize work, such as inadequate paid leave and high child care costs,” Ms. Yellen said.                                                                                                                                                                                                                                                                                                                                                                   , The path forward for Mr. Biden’s agenda in Congress remains uncertain. The president acknowledged this week that he would need to scale back his proposals to pass something this year.                                                                                                                                                                                                                                                                                                                                                                                , Ms. Yellen expressed optimism that inflation would “substantially” abate later this year and insisted that the Biden administration is working to alleviate supply chain congestion. Nevertheless, she acknowledged that the pandemic continues to bring significant uncertainty.                                                                                                                                                                                                                                                                                      , “Even as policymakers continue to address rising prices, our economic recovery will face significant risks until we have moved more decisively past the pandemic,” Ms. Yellen said.                                                                                                                                                                                                                                                                                                                                                                                    , By Coral Murphy Marcos                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Microsoft earnings: The tech giant is scheduled to publish its earnings report for the last three months of the year. Investors are waiting to hear more details from its chief executive, Satya Nadella, on the company’s $70 billion acquisition of Activision Blizzard, its biggest deal ever, which was announced on Tuesday.                                                                                                                                                                                                                                      , I.M.F. World Outlook: The International Monetary Fund will provide an update for its biannual report on the outlook for a global economic recovery, which was published in October. Economists are expecting to hear revised forecasts for global growth, inflation and the effects of the Omicron variant on the economy.                                                                                                                                                                                                                                             , F.O.M.C. meeting: The central bank’s Federal Open Market Committee will meet for the first time this year. Economists think Federal Reserve officials will use the meeting to signal that interest rate increases are coming in March. Some think there is even a chance that officials will slow bond buying more quickly than they previously planned.                                                                                                                                                                                                               , Boeing earnings: Investors will be looking for an update on when Boeing will resume shipping its 787 Dreamliner after quality concerns led the company to slow production and suspend deliveries. The company said last week that it sold a net 535 new planes last year after factoring in cancellations, capping its best year of sales since 2018.                                                                                                                                                                                                                  , Tesla earnings: With a major computer chip shortage slowing vehicle production for many companies, investors will want to hear more on how Tesla increased its deliveries 87 percent in 2021. The earnings report will also cover a period when Tesla’s market value exceeded $1 trillion for the first time, making it more valuable than General Motors, Ford Motor, Toyota, BMW and several other automakers combined.                                                                                                                                              , G.D.P. growth: The Commerce Department will publish data on gross domestic product growth in the United States. Some experts estimate that the global chip shortage alone knocked off a full percentage point from the U.S. G.D.P. last year, and they estimate an overall annual growth of 5 to 6 percent.                                                                                                                                                                                                                                                            , Southwest earnings: Investors will want to learn more about how the Omicron variant of the coronavirus upended Southwest Airlines during the busy holiday season, as well as the company’s forecast for the year. A series of winter storms, coupled with staff shortages as employees called in sick, prompted a wave of flight cancellations by several airlines at the end of 2021.                                                                                                                                                                                 , Apple earnings: Analysts expect the company to share more about the effects of an update that allows Apple users to choose not to be tracked across apps and websites, which has disrupted companies that used that information to target ads. Shareholders will also want to learn more about the demand for the iPhone 13 over the holidays.                                                                                                                                                                                                                         , McDonald’s earnings: With fast food prices rising at their fastest pace in more than 20 years, economists are looking for insight into how much longer the American chain will keep passing on the higher costs of ingredients to consumers.                                                                                                                                                                                                                                                                                                                           , Chevron earnings: The oil giant will report its earnings for the end of the year, giving investors more details on new drilling strategies and its profits as oil and natural gas prices rose throughout 2021. The report will cover a time when Chevron pledged to slash operational emissions to net zero by 2050.                                                                                                                                                                                                                                                   , By Stanley Reed                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , TotalEnergies, the French oil giant, and Chevron said Friday that they would begin taking steps to withdraw from an offshore natural gas field in Myanmar that is a critical source of energy for both the host country and neighboring Thailand.                                                                                                                                                                                                                                                                                                                      , TotalEnergies said it was responding to a deterioration of the human rights situation and the “rule of law” in Myanmar since the military coup in February.                                                                                                                                                                                                                                                                                                                                                                                                            , The situation had reached a point, the company said, where it could no longer “make a sufficiently positive contribution in the country.” Since the coup, the military regime has waged a brutal crackdown on protests. Soldiers and the police have killed at least 1,488 civilians, according to the Assistance Association for Political Prisoners.                                                                                                                                                                                                                 , Chevron and TotalEnergies argued in the past that their presence was beneficial to the people of Myanmar and that shutting off the flow of gas would increase hardship. Chevron says the gas from the Yadana field generates electric power for roughly half the population of Yangon, Myanmar’s largest city, as well as supplying Thailand.                                                                                                                                                                                                                          , “Effectively turning off the power to half of Yangon’s homes, schools and hospitals — in the middle of a state of emergency and a pandemic — risks creating even more hardship,” Chevron said in a briefing note published in May on the company’s website.                                                                                                                                                                                                                                                                                                            , Last year, Chevron waged a vigorous lobbying campaign in Washington to prevent the White House from imposing sanctions in Myanmar that could disrupt the gas operations at the Yadana field and worsen the crisis for people who rely on the power.                                                                                                                                                                                                                                                                                                                    , The companies, though, have evidently decided that they have no choice but to yield to pressure from human rights groups and others to prepare to abandon a project that provides financial sustenance for Myanmar’s military.                                                                                                                                                                                                                                                                                                                                         , Total, which is the operator or manager of Yadana, said it would withdraw after six months without compensation. Chevron said it was reviewing its interest in the project to “enable a planned and orderly transition that will lead to an exit from the country.”                                                                                                                                                                                                                                                                                                    , The departures are not likely to be a major financial hit for either company. Chevron obtains only about 1.5 percent of its global gas output from Myanmar. TotalEnergies owns about 31 percent of the project, which dates to the 1990s, while the rest is owned by Chevron (28 percent); a subsidiary of Thailand’s energy company, PTT (26 percent); and the Myanmar national oil company (15 percent).                                                                                                                                                             , On the other hand, a stoppage of gas exports to Thailand, a major consumer, could have an impact on the already heated market for the fuel.                                                                                                                                                                                                                                                                                                                                                                                                                            , “Any disruption would further tighten an international gas market where there is already considerable supply anxiety,” said Neil Beveridge, an analyst at Bernstein, a research firm.                                                                                                                                                                                                                                                                                                                                                                                  , Still, it is not clear that the exit of Total and Chevron would lead to an end to the flows of gas or of funds to the military regime. Thailand’s PTT could take over operating the project. And TotalEnergies said in its news release that stopping revenue going to the Myanmar government from Yadana was “materially impossible” because the Thai company made most of the payments from gas sales from the project.                                                                                                                                              , By Steve Lohr                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , IBM is selling its Watson Health data and analytics business, the final step in the company’s retreat from what it once called a “moonshot” venture to improve health care, helping save lives and trim medical costs.                                                                                                                                                                                                                                                                                                                                                 , The business is being sold for an undisclosed price to Francisco Partners, a private investment firm, the companies announced on Friday.                                                                                                                                                                                                                                                                                                                                                                                                                               , Watson Health was set up as a separate business in 2015. IBM then spent more than $4 billion to acquire companies with medical data, billing records and diagnostic images on hundreds of millions of patients.                                                                                                                                                                                                                                                                                                                                                        , IBM has been trying to find buyers for the Watson Health business for more than a year. And it was seeking a sale price of about $1 billion, The Wall Street Journal reported last year.                                                                                                                                                                                                                                                                                                                                                                               , IBM had been winding down the business. In 2020, the company discontinued two products designed for cancer diagnosis — Watson for Genomics and Watson for Oncology, developed with another early collaborator, the Memorial Sloan Kettering Cancer Center.                                                                                                                                                                                                                                                                                                             , Since Arvind Krishna became chief executive in 2020, IBM has been tightening the focus of its business and shedding operations.                                                                                                                                                                                                                                                                                                                                                                                                                                        , Last November, IBM spun out its big back-office technology support and services business, which has yearly revenue of $19 billion. That business, called Kyndryl, has had lower profit margins and growth prospects than areas that are IBM’s current focus, cloud computing and artificial intelligence. IBM retained a stake of just under 20 percent in Kyndryl.                                                                                                                                                                                                    , IBM executives described the sale of the Watson Health assets as part of that broader strategy. Tom Rosamilia, senior vice president in charge of IBM’s software business, said the move was “a clear next step as IBM becomes even more focused on our platform-based hybrid cloud and AI strategy.”                                                                                                                                                                                                                                                                  , An earlier version of this article misstated the year that IBM discontinued Watson for Genomics and Watson for Oncology and that Arvind Krishna became chief executive. It was 2020, not 2000.                                                                                                                                                                                                                                                                                                                                                                         , The path of the pandemic is uncertain, but investors may have already made up their minds about the prospects for companies that had prospered months earlier. Netflix and Peloton plunged late in the day on Friday on signs that “stay at home” stocks, which were already under pressure, could take a turn for the worse as people begin to venture out again.                                                                                                                                                                                                     , Netflix reported its fourth-quarter earnings after the market closed, and warned that subscriber growth was about to slow. This sent the streaming giant’s stock down 20 percent, erasing more than $40 billion in market cap. The report suggests that the company is more vulnerable to competition than its investors are comfortable with.                                                                                                                                                                                                                         , Rivals are eating into Netflix’s business. The company, which now has 222 million subscribers, forecast that it would gain only 2.5 million customers in the current quarter, far from analysts’ average estimate of just over six million. Competition from the likes of Disney+, Amazon Prime Video, HBO Max and others “has only intensified over the last 24 months,” Netflix said.                                                                                                                                                                                , Other streamers have some advantages. Those services are attached to big studios, so they already own a ton of content. (Amazon is about to own a studio, if regulators approve its deal to buy MGM.) That gives them license to market their streaming efforts outside the United States, where all the growth is. Netflix can’t do the same as easily. In order to compensate, Netflix last week announced a price increase for U.S. subscribers.                                                                                                                    , Investors may reconsider the heady valuation of Netflix’s stock. Until the expected decline in growth announced on Thursday, investors were essentially paying double for each dollar of expected profit at Netflix, versus tech giants like Meta and Alphabet. But are Netflix’s growth prospects really that good? The answer, at least for now, is no.                                                                                                                                                                                                              , Peloton is similarly struggling, as the at-home exercise equipment maker grapples with waning demand for its bikes and treadmills. Its shares closed 24 percent lower Thursday — and are down some 80 percent over the past six months.                                                                                                                                                                                                                                                                                                                                , The company said it was weighing layoffs. “We now need to evaluate our organization structure and size of our team,” John Foley, Peloton’s chief executive, wrote in an open letter to customers and employees.                                                                                                                                                                                                                                                                                                                                                        , Peloton expects to have lost as much as $270 million last quarter, it said ahead of its scheduled earnings report next month.                                                                                                                                                                                                                                                                                                                                                                                                                                          , The company denied that it would temporarily halt all production because of a glut in inventory, pushing back on a CNBC report that had sent its shares plunging. That said, Mr. Foley wrote that “we are resetting our production levels for sustainable growth.                                                                                                                                                                                                                                                                                                      , By Melissa Eddy                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , BERLIN — Employees at Tesla’s new assembly plant outside Berlin will elect a works council next month, the latest indication that the factory could soon begin operation after months of setbacks and delays.                                                                                                                                                                                                                                                                                                                                                          , Elon Musk, Tesla’s chief executive, had hoped the facility, the company’s first assembly plant in Europe, would have been completed by the end of last year. But Germany’s cumbersome bureaucracy, combined with a flurry of lawsuits from local environmental groups, has pushed back the opening by several months.                                                                                                                                                                                                                                                  , Birgit Dietze, the regional leader for the IG Metall union, which represents autoworkers in Germany, said on Thursday that a vote for 19 representatives to serve on the works council had been scheduled for Feb. 28.                                                                                                                                                                                                                                                                                                                                                 , Works councils, committees that represent employees in helping to set factory policies, are standard in German companies. Although union members can serve on the councils, the bodies are not organized by or directly affiliated with the unions.                                                                                                                                                                                                                                                                                                                    , Members of the state government in Brandenburg, which has not yet granted final approval for the $7 billion plant, said this month that all of the necessary paperwork had been received in late December and that the process was in its final stages. They also indicated that settlement of a pending lawsuit over water use would not affect the timeline.                                                                                                                                                                                                         , “We are on what we hope are the last steps as far as the whole issue of permits for the factory,” Jörg Steinbach, Brandenburg’s minister for the economy, said last week. But he declined to speculate exactly when the plant would receive its final approval to begin production.                                                                                                                                                                                                                                                                                    , IG Metall said it was concerned that the works council vote had been scheduled even though roughly only one in six of the estimated 12,000 people who are expected to work at the plant had been hired so far. Most companies hire managers and engineers first, before filling in the lower ranks of blue-collar workers, who will make up the majority of the workers, Ms. Dietze said. That raises the prospect that a works council vote in February may not represent the work force when full production begins.                                                 , “With a works council, the work force is given a voice and can bring in and assert its interests,” Ms. Dietze said on Thursday. “In order to play this role, however, it is a prerequisite that a works council actually represents the work force, and that’s where it’s important to look closely at Tesla.”                                                                                                                                                                                                                                                         , Although Tesla has opposed unions at its plants in the United States, Germany has a strong tradition of unionization, and IG Metall recently opened an office near the plant and has been answering questions from workers and those applying for jobs. Ms. Dietze declined to say how many union members were already working at the facility, or whether they were among those running for positions on the works council.                                                                                                                                           , In Germany, individual workers join unions and, if enough of them do so, use their leverage to get employers to agree to a union contract, which is negotiated between workers and management for entire industries.                                                                                                                                                                                                                                                                                                                                                   , The plant, where Tesla expects to eventually produce 500,000 Model Y sport utility vehicles a year, has begun turning out cars, but they are prototypes that cannot be sold. Pending approval of the final steps, the Brandenburg authorities granted the company the right to produce an additional 2,000 prototypes of its Model Y cars, after Tesla said its initial run of 250 of the electric vehicles revealed points in the production that needed additional fine-tuning.                                                                                      , Still, speculation in Germany about a possible opening date has been fueled by reports of the prototype vehicles, optimism from government officials that a final approval is nearing and word from Mr. Musk that he would be making his way to Germany.                                                                                                                                                                                                                                                                                                               , Mr. Musk told his followers on social media this week that he will be headed to Berlin in “mid Feb.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , An earlier version of this article mistated the cost of a Tesla plant being built outside of Berlin. It is $7 billion, not $7 million.                                                                                                                                                                                                                                                                                                                                                                                                                                 , By Mike Isaac and Kate Conger                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , SAN FRANCISCO — Twitter shook up the top ranks of its security team this week with the termination of the head of security and the exit of the chief information security officer, the company told employees on Wednesday, as its new chief executive reorganizes the social media service.                                                                                                                                                                                                                                                                           , Peiter Zatko, the head of security, who is better known within the security community as Mudge, is no longer at the company, Twitter confirmed. Rinki Sethi, the chief information security officer, will depart in the coming weeks.                                                                                                                                                                                                                                                                                                                                  , The changes followed “an assessment of how the organization was being led and the impact on top priority work,” according to a memo from Parag Agrawal, Twitter’s chief executive, that was sent to employees on Wednesday and obtained by The New York Times. Mr. Agrawal said the “nature of this situation” limited what he was allowed to share with employees.                                                                                                                                                                                                    , Ms. Sethi and Mr. Zatko did not immediately respond to requests for comment.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Mr. Agrawal, who was appointed Twitter’s chief executive in November, has shuffled the company’s executives since taking over from Jack Dorsey, a founder. In December, Mr. Agrawal reorganized the leadership team and dismissed Dantley Davis, the chief design officer, and Michael Montano, the head of engineering.                                                                                                                                                                                                                                               , Mr. Zatko joined Twitter in late 2020. He is a well-known hacker and has had a long career in government and private industry. Before taking on his role at Twitter, he held roles at DARPA, Google and Stripe. He began his cybersecurity career in the 1990s, when he was a member of the hacking group Cult of the Dead Cow. Twitter recruited him after teenagers compromised the company’s systems in July 2020 and took over the accounts of prominent users.                                                                                                    , Ms. Sethi also joined Twitter after the hack and, alongside Mr. Zatko, was charged with improving the company’s security and protecting its user data. She was previously a vice president of information security at IBM and had worked in security at Intuit and Walmart.                                                                                                                                                                                                                                                                                            , Lea Kissner, Twitter’s head of privacy engineering, will become the company’s interim chief information security officer, according to current and former employees. They previously held security and privacy leadership roles at Google and Apple.                                                                                                                                                                                                                                                                                                                   , Two years into the pandemic, rundown bungalows command bidding wars, buyers keep snatching up places they’ve never seen, and homebuilders can’t find enough hardware. The median price for an American home is up nearly 20 percent in a year. The for-sale inventory is at a new low. And the hopeful buyers left on the sidelines have helped drive up rents instead.                                                                                                                                                                                                , There’s probably no quick reprieve coming, no rollback in stratospheric home prices if you can just wait a little longer to jump in, Emily Badger reports for The New York Times.                                                                                                                                                                                                                                                                                                                                                                                      , “It’s not a bubble, it really is about the fundamentals,” said Jenny Schuetz, a housing researcher at the Brookings Institution. “It really is about supply and demand — not enough houses, and huge numbers of people wanting homes.”                                                                                                                                                                                                                                                                                                                                 , Today, first-time home buyers in once-affordable markets have competition that didn’t exist a generation ago: global capital, all-cash “iBuyers” that size up homes by algorithm, institutional investors renting single-family homes and smaller-scale investors running Airbnbs.                                                                                                                                                                                                                                                                                     , “It’s really hard for an owner-occupier to compete with the amount of money that’s flowing into this region,” said Dan Immergluck, a professor at Georgia State in Atlanta.                                                                                                                                                                                                                                                                                                                                                                                            , None of this is rooted in the kind of risky borrowing that inflated the housing bubble. Instead, new forces are at play:                                                                                                                                                                                                                                                                                                                                                                                                                                               , Home buyers flush with pandemic savings and strong credit have been taking out conventional loans (if they’re taking out loans at all).                                                                                                                                                                                                                                                                                                                                                                                                                                , The rental market has experienced a rise in higher-income households, too, at a time when new household formation has also surged with young adults who began the pandemic by moving back home.                                                                                                                                                                                                                                                                                                                                                                        , Local governments have further stymied new housing supply with zoning and building restrictions that will remain a problem even when home-building supply chain kinks resolve                                                                                                                                                                                                                                                                                                                                                                                          , Intel has will build a new $20 billion chip manufacturing complex in Ohio, ramping up an effort to increase U.S. production of computer chips as users grapple with a lingering shortage of the vital components. Intel said Friday that the new site near Columbus would initially have two chip factories and would directly employ 3,000 people while creating additional jobs in construction and at nearby businesses                                                                                                                                             , Netflix said it had added 8.3 million subscribers in the fourth quarter, but was expecting growth to slow this year, prompting its stock to drop in after-hours trading on Thursday. The streaming giant now has 222 million subscribers worldwide. Netflix said that one reason for its depressed first-quarter forecast was that many new releases were scheduled for the end of the period.                                                                                                                                                                         , Mustafa Suleyman, a pioneer in the field of artificial intelligence, is leaving Google after a rocky tenure to join the venture capital firm Greylock Partners. Mr. Suleyman, who was Google’s vice president of product management and policy for artificial intelligence, joined Google in 2014 when the search giant acquired DeepMind, a cutting-edge artificial intelligence research lab.                                                                                                                                                                        , JPMorgan Chase gave its chief executive, Jamie Dimon, a raise of almost 10 percent days after he said the bank had to spend more to retain top performers. Mr. Dimon’s 2021 compensation was $34.5 million, the company said in a filing on Thursday. That’s $3 million more than a year earlier, when he received no raise — but did get a midyear bonus in the form of stock options he can exercise in 2026.                                                                                                                                                        , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/paraguay/interest-rate </td>
   <td style="text-align:left;"> 2022-01-22 06:14:26 </td>
   <td style="text-align:left;"> Paraguay Hikes Interest Rate to 5.5% </td>
   <td style="text-align:left;"> The central bank of Paraguay raised its benchmark interest rate by 25 bps to 5.5% on January 21st, 2022, it was the sixth consecutive hike since the monetary authority started the normalization process in August. Policymakers noted the resurge of pandemics internationally boosted by the new variant Omicron, however, it is important to note that the duration of the wave of contagious and the death rate are way lower when compared to other variants. Domestically, the economic recovery has maintained a favorable dynamic in the short term, while the spike in Covid-19 cases represents a downward risk for the economic recovery along of 2022. Still, the inflation rate remained above the target regime and it is expected to gradually ease during 2022. The annual inflation rate in Paraguay increased 6.8 percent in December of 2021 easing further from an over 10-year of 7.6 percent hit in October. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-21/blackrock-plans-blockchain-and-tech-etf-amid-crypto-meltdown?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-22 06:07:19 </td>
   <td style="text-align:left;"> BlackRock Plans ‘Blockchain and Tech’ ETF Amid Crypto Meltdown </td>
   <td style="text-align:left;"> Katherine Greifeld                                                                                                                                                                                                                                                                                                                        , BlackRock Inc. is stepping into the arena of cryptocurrency-flavored exchange-traded funds in the midst of a $1 trillion wipeout.                                                                                                                                                                                                         , The iShares Blockchain and Tech ETF would invest in companies involved in the “development, innovation, and utilization of blockchain and crypto technologies,” according to a Friday filing with the U.S. Securities and Exchange Commission. If launched, it would be the first crypto-adjacent fund in the largest ETF issuer’s lineup. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60057281?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-22 06:00:14 </td>
   <td style="text-align:left;"> First-time buyer: 'I couldn't keep paying so much rent' </td>
   <td style="text-align:left;"> Jake Olenick, 24, used to spend almost two-thirds of his take-home pay renting a London flat before he managed to get on the property ladder last year.                                                                                            , A new job, rigorous saving and "lucky family circumstances" enabled him to buy a share of a flat in Kilburn.                                                                                                                                       , Jake is not alone in managing to get a foot on the housing ladder in 2021.                                                                                                                                                                         , Figures from mortgage lender Halifax suggest there were a record number of first-time buyers last year, despite rising house prices and falling affordability.                                                                                     , Jake, who is originally from New York, graduated from Oxford University and got a job in Oxford working as a games developer in 2019.                                                                                                              , Six months ago, he landed a software development job in London and moved into a West Hampstead flat with his girlfriend.                                                                                                                           , That relationship broke down in October and Jake started to pay all of the rent, which worked out at about 60% of his take-home pay.                                                                                                               , "I couldn't keep paying that much in rent and I already knew that it's almost always much better to buy," he said.                                                                                                                                 , So he started the ball rolling on buying 40% of a flat in Kilburn, sharing ownership with a housing association. In total, he'll be paying 35% of his salary on rent, mortgage and service charge when he moves in.                                , He said one of the main reasons he was able to do this was "extremely lucky family circumstances".                                                                                                                                                 , His parents had been saving for him to go to a US university, which was much more expensive than a UK one, and they were able to cover his fees at Oxford.                                                                                         , So when he left, he had no student loans, which helped him when viewing properties.                                                                                                                                                                , He also managed to put aside money from his job and has been saving birthday and Christmas money his whole life.                                                                                                                                   , Jake is really looking forward to moving into his new flat.                                                                                                                                                                                        , "I'm very excited!" he says. "I'll be able to put up posters, make repairs, the oven door will close, I'll be able to sleep because the windows are insulated, triple-glazed even!                                                                 , "I'll be able to afford a weekend away, maybe I'll be able to afford a keyboard so I can play piano again. All sorts of things!"                                                                                                                   , There were more than 400,000 people buying their first home in 2021, up 35% from the previous year, the Halifax said. That rate dropped by 13% in 2020, when the number of Halifax buyers was about 300,000.                                       , A stamp duty holiday that started in 2020 saw house buyers rush to pick up properties - although first-time buyers were not part of this stampede.                                                                                                 , However, this meant a number of so-called "first-rung" homes came on to the market, which first-time buyers took advantage of in 2021, despite hikes in property prices.                                                                           , Esther Dijkstra, mortgage director at Halifax, said: "There were a number of factors influencing home-buying decisions in 2021.                                                                                                                    , "While working from home and the 'race for space' was key for many, particularly movers, it's clear that the stamp duty holiday increased the availability of first-rung homes as others moved up the ladder."                                     , The average age of first-time buyers rose to 32, up from 29 in 2011. Ms Dijkstra said that this rise in average age was mostly due to "the need to save a significant deposit to get on the housing ladder".                                       , The average buyer used a £53,935 deposit on a first property costing £264,140.                                                                                                                                                                     , Because of difficulties raising a deposit, the gap between the purchase price and the deposit widened in every region in the UK, Ms Dijkstra added.                                                                                                , It's only in three local authority areas in Scotland that homes are either more affordable - in Clackmannanshire and Moray - or as affordable - in East Ayrshire, since 2011.                                                                      , Houses in the rest of the UK have become less affordable since then, Halifax said.                                                                                                                                                                 , On average, properties now cost nearly seven times the annual salary of first-time buyers.                                                                                                                                                         , The limit for affordability is considered to be four times the average income.                                                                                                                                                                     , In some areas, affordability has dropped very sharply since 2011.                                                                                                                                                                                  , In one London borough, Merton, affordability has halved, with similar drops, albeit not as pronounced, in Reigate and Banstead, South Kesteven, Westminster and Ashford.                                                                           , Anya Martin, director of campaign group PricedOut, which pushes for more affordable housing, said: "House prices and rents have been pushed out of reach by decades of failure to build enough homes.                                              , "First-time buyer schemes may help a few, but ultimately they are designed to help people stretch to high prices, rather than dealing with the cause of those high prices."                                                                        , Many first-time buyers get help from their parents to be able to afford a home, but some use a mortgage firm that was itself set up by frustrated first-time buyers.                                                                               , Retail worker Chae Sarjant is buying a home with her partner, who works for the NHS, on the same road where she grew up in East Finchley.                                                                                                          , They got a mortgage through a company called Generation Home. Chae says: "To be honest, we couldn't have done it without them."                                                                                                                    , Her mum "is only able to give us as much as she is because it's a loan protected by Generation Home, so she can get it back when we move and use it in retirement" and her stepfather has also taken a stake in the property, Chae says.           , "We're buying about two minutes walk from them in East Finchley," she says. "It's the same road I grew up on and it means my son gets to go to the same schools I went to.                                                                         , "We're all thrilled, although we're currently in conveyancing hell," she says. "It's a long and very annoying process."                                                                                                                            , The family are hoping to move in February and "we're really looking forward to settling down".                                                                                                                                                     , They have rented for the past four years, "which has meant moving a lot, and I know my son is looking forward to that being over!" she adds.                                                                                                       , She said they "never really took the idea of buying our own place that seriously, to be honest".                                                                                                                                                   , "Our salary has been eaten up by rent every month, so we have very little savings of our own and our income means most mortgage companies were giving us way less than we needed to afford anything even remotely close to our families," she said., Flats in East Finchley typically cost between £350,000 and £550,000, she said.                                                                                                                                                                     , "Having my mum loan us the money makes us all a lot more comfortable," Chae adds. "She's able to get the money back in the future and I'm a lot less stressed about affecting her retirement."                                                     , Eating with My Ex is back with even more drama!                                                                                                                                                                                                    , What is it really like to live in Dubai?                                                                                                                                                                                                           , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/goldman-jpmorgan-award-bumper-bonuses-top-bankers </td>
   <td style="text-align:left;"> 2022-01-22 05:59:40 </td>
   <td style="text-align:left;"> Goldman, JPMorgan award bumper bonuses to top bankers </td>
   <td style="text-align:left;"> JPMorgan Chase CEO Jamie Dimon acknowledges that risk increases when doing business with China, noting there are 'complex issues' and the bank is going to 'have to navigate around that.'                                                                                   , Goldman Sachs and JPMorgan Chase, Wall Street's premier investment banks, this week informed staff of bumper bonuses for 2021, following a record-breaking year for Wall Street deal-making.                                                                                 , Goldman Sachs increased its annual bonus pool for top-performing investment bankers by 40% to 50%, people with direct knowledge of the matter said.                                                                                                                          , JPMorgan Chase, the largest U.S. bank, increased its annual bonus pool for top-performing investment bankers by 30% to 40%, sources with direct knowledge of the matter said.                                                                                                , JP Morgan Chase was one of the companies targeted by Andrei Tyurin. (iStock / iStock)                                                                                                                                                                                        , Goldman Sachs and JPMorgan declined to comment.                                                                                                                                                                                                                              , Record levels of deal-making and trading activities have driven profit at investment banks this year as economic stimulus measures helped propel stock markets globally to all-time highs.                                                                                   , Top performers in M&amp;A advisory and equity capital markets enjoyed some of the biggest bonuses at both Goldman and JPMorgan, the people said.                                                                                                                                 , Bankers in Goldman's M&amp;A advisory and ECM divisions were handed an average 40% increase in bonuses with the very best performers seeing rises of 50% or more.                                                                                                                , Headquarters building of Goldman Sachs Group Inc. stands at 200 West Street in New York, U.S. (Photographer: Ramin Talaie/Bloomberg via Getty Images) (Getty Images)                                                                                                         , GOLDMAN SACHS' PROFIT DECLINES BY 13% IN FOURTH QUARTER                                                                                                                                                                                                                      , The bank's partners were handed special stock bonuses, some of which amounted to multimillion-dollar packages, the sources said. Bankers who worked on some of the biggest deals of the year were among those who received the most generous awards, one of the sources said., Wall Street's biggest banks are facing cutthroat competition to hire and are paying more to recruit and retain top talent. But that comes at a price.                                                                                                                        , In the latest quarter, non-interest expenses at the nation's biggest banks ballooned by tens of billions of dollars, hurting profit growth, earnings disclosures showed.                                                                                                     , The cost of retaining talent put a dampener on record 2021 earnings from both Goldman and JPMorgan.                                                                                                                                                                          , JPMorgan Chase reported last week that its non-interest expenses jumped 11% in the fourth quarter last year, largely due to higher staff compensation. Goldman reported a 33% rise in compensation expenses last year.                                                       , JPMORGAN'S FOURTH-QUARTER PROFIT DROPS 14%                                                                                                                                                                                                                                   , JPMorgan boss Jamie Dimon said the bank would pay what it takes to retain the bank's top talent.                                                                                                                                                                             , JP Morgan CEO Jamie Dimon looks on during the inauguration of the new French headquarters of US' JP Morgan bank on June 29, 2021 in Paris. (Photo by MICHEL EULER/POOL/AFP via Getty Images / Getty Images)                                                                  , "We will be competitive and pay and if that squeezes margin a little bit for shareholders, so be it," he told analysts.                                                                                                                                                      , Top executives at Goldman Sachs echoed those statements on Tuesday.                                                                                                                                                                                                          , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                  , "Our philosophy remains to pay for performance, and we are committed to rewarding top talent in a competitive labor environment," Chief Financial Officer Denis Coleman told analysts.                                                                                       , Morgan Stanley raised its annual bonus for top-performing staff by more than 20%, Reuters reported last week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/kraft-heinz-appoints-new-cfo/story.aspx?guid={84CB6B53-28E3-4270-9C26-6B881726A9E5}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-22 05:56:05 </td>
   <td style="text-align:left;"> Kraft Heinz appoints new CFO - MarketWatch </td>
   <td style="text-align:left;"> Kraft Heinz Co. said late Friday it has appointed Andre Maciel as its chief financial officer, effective March 2. Maciel will succeed Paulo Basilio, who will step down on March 1, the company said. Basilio will remain with the company as a strategic adviser through August. Shares of Kraft Heinz were off around 0.1% in the extended session Friday after ending the regular trading day down 0.2%. , After being poor, rich—then poor again—she now helps people avoid costly money mistakes.                                                                                                                                                                                                                                                                                                                    , Claudia Assis is a San Francisco-based reporter for MarketWatch. Follow her on Twitter @ClaudiaAssisMW. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-21/unrelenting-plunges-in-the-nasdaq-ring-a-dot-com-bust-alarm-bell?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-22 05:40:18 </td>
   <td style="text-align:left;"> Nasdaq 100’s Unrelenting Declines Ring a Dot-Com Bust Alarm Bell </td>
   <td style="text-align:left;"> Lu Wang                                                                                                                                                                                                                                                                                       , Bulls should be glad there were only four days this week instead of five.                                                                                                                                                                                                                     , To wit, the Nasdaq 100 just did something it hasn’t done since the aftermath of the internet bubble: fall more than 1% in every session of a week. It doesn’t count as a superlative because Monday was a holiday. But for investors caught up in the selloff, it felt like something shifted. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-21/where-s-that-fed-put-scorched-dip-buyers-confront-new-reality </td>
   <td style="text-align:left;"> 2022-01-22 05:20:31 </td>
   <td style="text-align:left;"> Where’s That ‘Fed Put’? Scorched Dip Buyers Confront the Market’s New Reality </td>
   <td style="text-align:left;"> Monitors display stock market information at the Nasdaq MarketSite in New York, on Jan. 21.                                                                                                                                                                                                                                                                        , Jess Menton                                                                                                                                                                                                                                                                                                                                                        ,  and Joanna Ossinger                                                                                                                                                                                                                                                                                                                                               , When stocks plunged in 2018, Jerome Powell was there, buoying sentiment. Two years later as shares careened into the fastest bear market ever, he stepped up again, flooding the system with support.                                                                                                                                                              , After the Nasdaq 100’s worst week since March 2020, investors are wondering what it would take for the Federal Reserve chairman to reprise his unofficial role as market savior. But the bar is now clearly higher, with the economy running hot, consumer prices surging the most four decades and President Joe Biden saying it’s Powell’s job to tamp them down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-01-22 05:15:00 </td>
   <td style="text-align:left;"> Canada Stocks Plunge to 1-Month Low </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, plunged 2.1% to close at 20,608 on Friday, extending losses for a 4th straight session to the lowest in over a month, and in line with its international peers, as weaker crude futures pressured heavyweight energy stocks 3.4% lower. Also, investors weighed the implications of a tighter monetary policy by the Federal Reserve dragging tech stocks 3.3% lower, while disappointing US earnings raised concerns over economic recovery. On the data front, retail sales in Canada fell 2.1% over a month earlier in December, according to preliminary estimates, while final data showed the rise in November came short of expectations. On corporate updates, Canadian Imperial Bank of Commerce analysts cut the target of food processing firm George Weston Ltd to C$171 from a prior C$175 per share. On a weekly basis, the index plunged 3.4%, its worst performance in a year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-01-22 05:12:05 </td>
   <td style="text-align:left;"> Brazilian Equities Snap 3-Day Rally </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Bovespa, fell 0.1% to close at 109,014, snapping a 3-day rally that had pushed the index to a near 3-month high during the last session, as investors weigh the implications of a tighter monetary policy by the Federal Reserve, while disappointing US earnings raised concerns over economic recovery. Domestically, traders continued to monitor Brazil's fiscal scenario, with the Federal Government's initiative to reduce fuel and electricity prices adding to the pressure of civil servants for salary adjustments. President Jair Bolsonaro is expected to sign the 2022 Budget today, as the deadline expires. On the political front, a new poll showed Former leftist President Luiz Inacio Lula da Silva is pulling ahead of his likely rival, far-right President Jair Bolsonaro, and could win outright in the first round of Brazil's October election. Still, the index extended gains for 2nd straight week, after jumping 1.9%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/21/business/economy/stock-markets-down-inflation.html </td>
   <td style="text-align:left;"> 2022-01-22 05:09:56 </td>
   <td style="text-align:left;"> Stock Markets Off to Worst Start Since 2016 as Fed Fights Inflation - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Stocks are off to their worst start of a year since 2016 as the central bank pulls back the enormous stimulus programs it began in the early months of the pandemic.                                                                                                                                                                                                                                                                                                                                        , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                                                                              , Source: Sentieo                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , By The New York Times                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , By Jeff Sommer                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , After falling for a fourth day in a row on Friday, the stock market suffered its worst week in nearly two years, and so far in January the S&amp;P 500 is off to its worst start since 2016. Technology stocks have been hit especially hard, with the Nasdaq Composite Index dropping more than 10 percent from its most recent high, which qualifies as a correction in Wall Street talk.                                                                                                                     , That’s not all. The bond market is also in disarray, with rates rising sharply and bond prices, which move in the opposite direction, falling. Inflation is red hot, and supply chain disruptions continue.                                                                                                                                                                                                                                                                                                 , Until now, the markets looked past such issues during the pandemic, which brought big increases in the value of all kinds of assets.                                                                                                                                                                                                                                                                                                                                                                        , Yet a crucial factor has changed, which gives some market watchers reason to worry that the recent decline may be consequential. That element is the Federal Reserve.                                                                                                                                                                                                                                                                                                                                       , As the worst economic ravages of the pandemic appear to be waning, at least for now, the Fed is ushering in a return to higher interest rates. It is also beginning to withdraw some of the other forms of support that have kept stocks flying since it intervened to save desperately wounded financial markets back in early 2020.                                                                                                                                                                       , This could be a good thing if it beats back inflation without derailing the economic recovery. But removing this support also inevitably cools the markets as investors move money around, searching for assets that perform better when interest rates are high.                                                                                                                                                                                                                                           , “The Fed’s policies basically got the current bull market started,” said Edward Yardeni, an independent Wall Street economist. “I don’t think they are going to end it all now, but the environment is changing and the Fed is responsible for a lot of this.”                                                                                                                                                                                                                                              , The central bank is tightening monetary policy partly because it has worked. It helped stimulate economic growth by holding short-term interest rates near zero and pumping trillions of dollars into the economy.                                                                                                                                                                                                                                                                                          , This flood of easy money also contributed to the rapid rise in prices of commodities, like food and energy, and financial assets, like stocks, bonds, homes and even cryptocurrency.                                                                                                                                                                                                                                                                                                                        , What happens next comes from an established playbook. As William McChesney Martin, a former Fed chairman, said in 1955, the central bank finds itself acting as the adult in the room, “who has ordered the punch bowl removed just when the party was really warming up.”                                                                                                                                                                                                                                  , The mood of the markets shifted on Jan. 5, Mr. Yardeni said, when Fed officials released the minutes of their December policymaking meeting, revealing that they were on the verge of embracing a much tighter monetary policy. A week later, new data showed inflation climbing to its highest level in 40 years.                                                                                                                                                                                          , Putting the two together, it seemed, the Fed would have no choice but to react to curb rapidly rising prices. Stocks began a disorderly decline.                                                                                                                                                                                                                                                                                                                                                            , Financial markets now expect the Fed to raise its key interest rate at least three times this year and to start to shrink its balance sheet as soon as this spring. It has reduced the level of its bond buying already. Fed policymakers will meet next week to decide on their next steps, and market strategists will be watching.                                                                                                                                                                       , Low interest rates made certain sectors especially appealing, foremost among them tech stocks. The S&amp;P 500 information technology sector, which includes Apple and Microsoft, has risen 54 percent on an annualized basis since the market’s pandemic-induced trough in March 2020. One reason for this is that low interest rates amplify the value of the expected future returns of growth-oriented companies like these. If rates rise, this calculus can change abruptly.                              , What is inflation? Inflation is a loss of purchasing power over time, meaning your dollar will not go as far tomorrow as it did today. It is typically expressed as the annual change in prices for everyday goods and services such as food, furniture, apparel, transportation costs and toys.                                                                                                                                                                                                            , What causes inflation? It can be the result of rising consumer demand. But inflation can also rise and fall based on developments that have little to do with economic conditions, such as limited oil production and supply chain problems.                                                                                                                                                                                                                                                                , Where is inflation headed? Officials say they do not yet see evidence that rapid inflation is turning into a permanent feature of the economic landscape, even as prices rise very quickly. There are plenty of reasons to believe the price burst will fade, but some concerning signs suggest it could last.                                                                                                                                                                                              , Is inflation bad? It depends on the circumstances. Fast price increases spell trouble, but moderate price gains could also lead to higher wages and job growth.                                                                                                                                                                                                                                                                                                                                             , How does inflation affect the poor? Inflation can be especially hard to shoulder for poor households because they spend a bigger chunk of their budgets on necessities — food, housing and especially gas.                                                                                                                                                                                                                                                                                                  , Can inflation affect the stock market? Rapid inflation typically spells trouble for stocks. Financial assets in general have historically fared badly during inflation booms, while tangible assets like houses have held their value better.                                                                                                                                                                                                                                                               , The very prospect of higher interest rates has made technology the worst-performing sector in the S&amp;P 500 this year. Since its peak in late December, it has fallen more than 11 percent.                                                                                                                                                                                                                                                                                                                   , The S&amp;P’s three best-performing sectors in the early days of 2022, on the other hand, are energy, financial services and consumer staples.                                                                                                                                                                                                                                                                                                                                                                  , The energy index is dominated by fossil fuel companies, like Exxon Mobil and Halliburton, whose fortunes have risen along with oil and gas prices. Financial companies can charge more for loans when interest rates are high. Big banks like Wells Fargo have reported bumper earnings over the past week. Consumer companies like Kraft Heinz and Campbell Soup lagged the explosive share price growth of tech stocks earlier in the pandemic, but they have been gaining ground in this new environment., The stock market, overall, has also lost some of its buoyancy for reasons other than monetary policy. “Stay at home” stocks that flourished during pandemic restrictions, like Netflix and Peloton, have begun to flag as people venture out more.                                                                                                                                                                                                                                                          , Some astute market analysts foresee bigger problems. Jeremy Grantham, one of the founders of GMO, an asset manager, predicts a catastrophic end to what he calls a “superbubble.”                                                                                                                                                                                                                                                                                                                           , But the current losses could be beneficial if they let a little air out of a potential bubble, without bursting investor portfolios. This year’s declines erase only a small share of the market’s gains in recent years: The S&amp;P 500 rose nearly 27 percent last year, more than 16 percent in 2020 and nearly 29 percent in 2019.                                                                                                                                                                         , And the prospects for corporate earnings remain good. Once the Fed starts to act, and the effects are better understood, the stock market party could continue — at a less giddy pace.                                                                                                                                                                                                                                                                                                                      , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bloomberg.com/news/articles/2022-01-21/morgan-stanley-rates-trading-flop-shows-wall-street-s-fed-risk?srnd=markets-vp </td>
   <td style="text-align:left;"> 2022-01-22 05:07:45 </td>
   <td style="text-align:left;"> Morgan Stanley Rates Trading Flop Shows Wall Street’s Fed Risk </td>
   <td style="text-align:left;"> Morgan Stanley headquarters in New York.                                                                                                                                                                                                                                                                                                                        , Donal Griffin                                                                                                                                                                                                                                                                                                                                                   , Morgan Stanley saw a plunge of more than 60% in its U.S. rates trading business last year, fueled by a fourth-quarter flop in one of its most complex desks, as uncertainty about how the Federal Reserve would combat inflation wreaked havoc across Wall Street.                                                                                              , The firm’s U.S. structured rates book suffered about $50 million of losses in the last three months of the year, leaving that area in the red for 2021, according to people with direct knowledge of the performance. The rates performance was a blemish on a set of results otherwise cheered by investors for delivering record profit and revenue last year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/us-stocks-end-lower-friday/story.aspx?guid={618678B3-4566-4BB5-9326-E8D81C04ECCF}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-22 05:02:23 </td>
   <td style="text-align:left;"> U.S. stocks end lower Friday, Nasdaq books worst week since March 2020 - MarketWatch </td>
   <td style="text-align:left;"> U.S. stock indexes closed lower Friday, capping another punishing week for growth and technology stocks as investors await a Federal Reserve update next week on how aggressively interest rates may rise and financial conditions tighten to tame inflation. The Nasdaq Composite Index 
        COMP,
        -2.72%
       led the three stock benchmarks lower Friday, ending down 2.7%, but off 7.6% for the week, which was its worst weekly decline since March 2020, according to Dow Jones Market Data. The Nasdaq also entered correction territory mid-week, commonly measured as at least a 10% decline from its recent record close, and recorded its worst start to a year through Friday since the 2008 global financial crisis. Rising 10-year Treasury yields, up about 25 basis points near 1.74% this year, also have pressured speculative stocks and total returns of riskier assets. The S&amp;P 500 index 
        SPX,
        -1.89%
       tumbled 1.9% Friday and 5.7% for the week, while the Dow Jones Industrial Average fell 1.3% for the session and 4.6% for the week, pulled lower in part by jitters about pinched margins as major banks kicked off fourth-quarter earnings.  , Investors have taken things to a whole new level and many still haven't learned their lesson.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , Joy Wiltermuth is a news editor and senior markets reporter based in San Francisco. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-01-22 05:01:47 </td>
   <td style="text-align:left;"> Wall Steet Tumbles </td>
   <td style="text-align:left;"> The US stocks closed sharply lower on Friday amid disappointing earnings results from companies that soared in the pandemic and as investors anticipate a tighter monetary policy. The Dow Jones lost as much as 450 points, the S&amp;P dropped 1.9% and the tech-heavy Nasdaq Composite plunged 2.7%. Netflix was the main drag falling 23% after the company's subscriber outlook missed estimates due to the rise in streaming competition, also hitting its competitors with Disney+ streaming falling 7%. On the other hand, Peloton shares jumped 10%, rebounding from a 23.9% fall yesterday. On the week, the Nasdaq Composite posted its worst performance since October 2020, after dropping 7.6%. Also, both the Dow and the S&amp;P 500 extended losses for a 3rd straight week, with a fall of 4.6% and 5.7%, respectively. Next week, the focus remains on the Fed monetary policy decision and further earnings reports from big tech companies which investors fear could disappoint. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-01-22 04:30:04 </td>
   <td style="text-align:left;"> The Dow Jones Index falling 1.31% </td>
   <td style="text-align:left;"> United States Stock Market is dropping 454 points. Leading the losses are Walt Disney (-4.16%), Boeing (-1.24%) and GS (-1.20%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/oil-prices-tally-fifth-consecutive/story.aspx?guid={A8891D93-1594-42B3-AAEA-3DC0B71CE45B}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-22 03:59:04 </td>
   <td style="text-align:left;"> Oil prices tally a fifth consecutive week of gains - MarketWatch </td>
   <td style="text-align:left;"> Oil prices finished lower on Friday, but scored a fifth consecutive weekly rise. "Crude prices may not have a one-way ticket to $100 oil, but the supply-side fundamentals certainly support that could happen by the summer," said Edward Moya, senior market analyst at OANDA. "The next few trading sessions could be difficult for energy traders as oil prices may move more so on investor positioning ahead of Wednesday's FOMC policy decision and over a handful of brewing geopolitical risks, that include Russia-Ukraine tensions, Iran nuclear talks, and developments with global handling over North Korea." March West Texas Intermediate crude 
        CLH22,
        -0.84%
       fell 41 cents, or 0.5%, to settle at $85.14 a barrel on the New York Mercantile Exchange. The U.S. benchmark, based on the front-month contract, rose 2.2% for the week, according to Dow Jones Market Data., Stocks had their worst week since the early days of the pandemic, as a disappointing earnings report from Netflix spooked tech investors. That's just one worry on a laundry list of concerns for the stock market.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/gold-futures-fall-session-post/story.aspx?guid={7263388B-E843-4FF4-A57C-BCE08DC13178}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-22 02:49:06 </td>
   <td style="text-align:left;"> Gold futures fall for the session, but post a second straight week gain - MarketWatch </td>
   <td style="text-align:left;"> Gold futures fell on Friday amid declines in most asset classes, but still tallied a gain for a second straight week after settling Wednesday at their highest in two months. "While the precious metal markets are likely overbought from significant gains earlier this week, and due some corrective action, we blame big picture risk off psychology," analyst at Zaner wrote in a daily report Friday. "Not only has the tensions between Russia and the rest of the world undermined sentiment, but U.S. corporate earnings seem to have lost their ability to lift equities and highflying crude oil prices have corrected sharply." February gold 
        GCG22,
        -0.35%
       fell $10.80, or 0.6%, to settle at $1,831.80 an ounce. For the week, however, most-active gold futures rose 0.8%, up a second week in a row, according to FactSet data., Cryptocurrency prices tumbled Thursday night, with bitcoin hitting its lowest price since last August.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Myra P. Saefong, assistant global markets editor, has covered the commodities sector for MarketWatch for 20 years. She has spent the bulk of her years at the company writing the daily Futures Movers and Metals Stocks columns and has been writing the weekly Commodities Corner column since 2005. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/money/covid-relief-money-scams </td>
   <td style="text-align:left;"> 2022-01-22 02:48:50 </td>
   <td style="text-align:left;"> Olympic medalist accused of stealing millions in COVID-19 relief money </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.
                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , When the COVID-19 pandemic began nearly two years ago, scammers immediately began siphoning off money from the trillions in federal relief money that Congress approved.                                                                                                                                                                                                                                                                                                                                                  , COMPANIES RETURNED $30B IN VIRUS RELIEF LOANS FROM PPP                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Authorities say those fraudsters include Allison Baver, a former Olympic speedskater who has been charged with eight counts of making a false statement to a bank and one count of money laundering, according to the U.S. Attorney's General Office in Utah.                                                                                                                                                                                                                                                             , Allison Baver competes in the ladies 1,000 meter time trial during the U.S. Olympic Short Track Trials at the Utah Olympic Oval on Jan. 2, 2014 in Salt Lake City, Utah.  (Matthew Stockman/Getty Images / Getty Images)                                                                                                                                                                                                                                                                                                  , The 41-year-old won a bronze medal for the women's 3000m relay in the 2010 Olympics in Vancouver, nearly one year after she shattered her ankle and broke her leg in multiple places during a competition in Bulgaria.                                                                                                                                                                                                                                                                                                    , After her Olympic victory, Baver launched Allison Baver Entertainment, a company that describes itself as the "engine behind stories that move the needle. We are purpose-driven across film, television, and lifestyle endeavors."                                                                                                                                                                                                                                                                                       , Now, authorities say that Baver lied on loan applications to fraudulently receive $10 million from the Paycheck Protection Program – some of which she invested in a movie about the serial killer Ted Bundy, prosecutors say.                                                                                                                                                                                                                                                                                            , Baver allegedly claimed in some applications for PPP funding that her company had an average monthly payroll of $4 million and 105 employees, according to the indictment. In others, she said she had 430 workers. But the indictment alleges that Baver actually had no employees or monthly payroll.                                                                                                                                                                                                                   , Allison Baver falls in the women's 1000m first race semifinals at the Short Track US Single Distance Championships on Aug. 25, 2013 at the Olympic Oval in Kearns, Utah.  (George Frey/Getty Images / Getty Images)                                                                                                                                                                                                                                                                                                       , In May 2020, one of the banks, Meridian, approved a $10 million loan for Allison Baver Entertainment; two months later, the indictment says, Baver transferred $150,000 to another production company behind the movie "No Man of God," which stars Elijah Wood as serial killer Ted Bundy.                                                                                                                                                                                                                               , Federal prosecutors want Baver to forfeit roughly $9.7 million of the money, according to local station KTSU. She also faces up to 40 years if convicted on all counts.                                                                                                                                                                                                                                                                                                                                                   , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , The Secret Service estimated last month that roughly $100 billion has been stolen from COVID-19 relief funds, a figure that's based on Secret Service cases as well as data from the Labor Department and the Small Business Administration. It does not include COVID-19 fraud cases prosecuted by the Justice Department. In all, at least 3% of the total $3.4 trillion in federal pandemic aid has been stolen by scammers, showing the "sheer size of the pot is enticing to the criminals," the Secret Service said., Allison Baver attends the 25th Annual Race To Erase MS Gala at The Beverly Hilton Hotel on April 20, 2018 in Beverly Hills, California.  (Jon Kopaloff/Getty Images / Getty Images)                                                                                                                                                                                                                                                                                                                                       , "Every state has been hit, some harder than others," said Roy Dotson, assistant special agent in charge. "The Secret Service is hitting the ground running, trying to recover everything we can, including funds stolen from both federal and state programs." </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/01/21/politics/trump-giuliani-january-6-2020/index.html </td>
   <td style="text-align:left;"> 2022-01-22 02:41:25 </td>
   <td style="text-align:left;"> Donald Trump's hands are all over the coup attempt - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)With each passing day, it seems, new revelations come to light that suggest how intimately involved then-President Donald Trump and his advisers were in the coup attempt leading up to the events of January 6, 2021.                                                                                                                                                                                                                                                                                                                                          , The latest bombshell came Thursday night when CNN reported that Trump lawyer and confidant Rudy Giuliani, as well as other Trump campaign aides, spearheaded the efforts to gather alternate electors in seven swing states in an attempt to overturn Joe Biden's Electoral College victory.                                                                                                                                                                                                                                                                          , As CNN's Marshall Cohen, Zachary Cohen and Dan Merica write:                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , "Giuliani and his allies coordinated the nuts-and-bolts of the process on a state-by-state level, the sources told CNN. One source said there were multiple planning calls between Trump campaign officials and GOP state operatives, and that Giuliani participated in at least one call. The source also said the Trump campaign lined up supporters to fill elector slots, secured meeting rooms in statehouses for the fake electors to meet on December 14, 2020, and circulated drafts of fake certificates that were ultimately sent to the National Archives.", The goal of these efforts? To have Vice President Mike Pence declare a dispute about which electors to seat from those seven key states, throwing the matter to the House where a Republican majority of state delegations would vote to recognize the pro-Trump electors rather than the rightful electors.                                                                                                                                                                                                                                                          , That plot was laid out in a two-page memo by John Eastman, a conservative lawyer working for Trump in the aftermath of the 2020 election. As CNN wrote of the Eastman memo late last year:                                                                                                                                                                                                                                                                                                                                                                            , "The Eastman memo laid out a six-step plan for Pence to overturn the election for Trump, which included throwing out the results in seven states because they allegedly had competing electors. In fact, no state had actually put forward an alternate slate of electors -- there were merely Trump allies claiming without any authority to be electors."                                                                                                                                                                                                           , As all of that was going on, Trump himself was actively pressuring Pence to throw the election back to the House despite there being no constitutional backing for such a move. On January 5, just hours before the Electoral College certification, Trump and Pence met at the White House. Here's how CNN described that meeting:                                                                                                                                                                                                                                   , "Pence came under intense pressure from Trump to toss out the election results during a meeting that lasted hours in the Oval Office. The vice president's chief of staff, Marc Short, was banned by Trump from entering the West Wing, the source said, as the President repeatedly warned with 'thinly veiled threats' to Pence that he would suffer major political consequences if he refused to cooperate."                                                                                                                                                      , The picture of all this reporting makes clear: Publicly and privately, Trump and those close to him were actively working to not only undermine public confidence in the 2020 election, but also to put in motion a plan to overturn a free and fair election.                                                                                                                                                                                                                                                                                                        , It's damning stuff. And, if the past few months have taught us anything, it's the more of this picture we see, the worse things look for Trump. His role in the scatter-shot, legally suspect effort only seems to grow larger with each passing week. While the report from the January 6 House select committee will be the definitive word on all of this, we can already see just how big a role Trump and those closest to him played in the attempted coup.                                                                                                     , What's even scarier than a sitting president actively trying to bend laws for his own personal gain? The fact that he is the current frontrunner to be the Republican Party's nominee in 2024.                                                                                                                                                                                                                                                                                                                                                                        , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/google-asks-federal-court-dismiss/story.aspx?guid={49376FE1-83E6-44CF-9492-88DCEE0F417E}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-22 02:30:58 </td>
   <td style="text-align:left;"> Google asks federal court to dismiss ad tech lawsuit - MarketWatch </td>
   <td style="text-align:left;"> Google parent Alphabet Inc. 
        GOOGL,
        -2.22%
        GOOG,
        -2.56%
       filed a motion in federal court in New York Friday asking the court to dismiss Texas Attorney General Ken Paxton's antitrust lawsuit over Google's ad tech products. "This lawsuit has now been rewritten three times. With each version, AG Paxton follows the same pattern: make inaccurate and inflammatory allegations, publicize them widely, and repeat. This playbook may generate attention, but it doesn't make for a credible antitrust lawsuit," Google said in a blog post., Stocks had their worst week since the early days of the pandemic, as a disappointing earnings report from Netflix spooked tech investors. That's just one worry on a laundry list of concerns for the stock market.                                                                                                                                                                                                                                                                                                                                                                        , Jon Swartz is a senior reporter for MarketWatch in San Francisco, covering many of the biggest players in tech, including Netflix, Facebook and Google. Jon has covered technology for more than 20 years, and previously worked for Barron's and USA Today. Follow him on Twitter @jswartz. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2022-01-22 02:10:00 </td>
   <td style="text-align:left;"> US Natural Gas Rebounds Sharply </td>
   <td style="text-align:left;"> US natural gas futures jumped towards $4 per million British thermal units after hitting an over two-week low of $3.78 on January 20th, underpinned by expectations of record demand and tight supplies. Weather forecasts showed colder temperatures for the fortnight ahead, which is expected to cause domestic inventories to stand below the 5-year average for the first time since mid-December, as utilities draw larger-than-normal amounts of gas from storage. Meanwhile, a cold snap in Texas and other producing states has frozen wells and other equipment, curtailing output levels to their lowest in four months. Production in the lower 48 states averaged 95.3 bcfd so far this month, down from a record 97.6 bcfd in December. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60087798?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-22 01:52:43 </td>
   <td style="text-align:left;"> Firms call for urgent help with energy bills </td>
   <td style="text-align:left;"> Five business groups have written to Chancellor Rishi Sunak urging support for businesses and consumers as energy costs soar.                                                                                                                                                        , The groups, representing small and large businesses, bosses and manufacturers, said price rises on the horizon could push millions of people into fuel poverty.                                                                                                                      , They said businesses had also been hit by steep rises in bills.                                                                                                                                                                                                                      , The Treasury said it was helping families with £12bn support.                                                                                                                                                                                                                        , The five groups - the British Chambers of Commerce, the Confederation of British Industry, the Federation of Small Businesses, the Institute of Directors and Make UK - said businesses were likely to be faced with further costs as existing fixed tariff contracts come to an end., "The scale of the crisis has left companies with little protection while they face dealing with soaring wage, shipping and tax costs," the groups said.                                                                                                                              , "Small and medium-sized businesses are the most at risk. Many companies will be left with little other choice than to pass costs on to their customers, adding further inflationary pressure."                                                                                       , They said that the government should focus on "supporting firms across the economy as they strive to manage these costs and protect cashflows".                                                                                                                                      , Energy-intensive industries such as steel, ceramics and glass makers also needed support to be competitive internationally, the groups said.                                                                                                                                         , Rising energy costs are putting pressure on families.                                                                                                                                                                                                                                , Inflation is running at its fastest rate for 30 years, pushed up by surging food costs and the energy bill crisis.                                                                                                                                                                   , A government spokesperson said: "We understand the pressures people are facing with the cost of living and are providing support worth around £12bn over two years to help families.                                                                                                 , "Support is being targeted towards the lowest paid, and we are specifically helping households with their energy bills.                                                                                                                                                              , "In addition, the energy price cap is currently insulating millions of consumers from high global gas prices and we'll continue to listen to consumers and businesses on how to manage the costs of energy."                                                                         , Eating with My Ex is back with even more drama!                                                                                                                                                                                                                                      , What is it really like to live in Dubai?                                                                                                                                                                                                                                             , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/netflix-stock-worst-day-10-years </td>
   <td style="text-align:left;"> 2022-01-22 01:50:19 </td>
   <td style="text-align:left;"> Netflix stock has worst day since 2012 </td>
   <td style="text-align:left;"> Wedbush Securities managing director Michael Pachter previews the streaming giant's earnings on 'The Claman Countdown.'                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Netflix shares got nailed on Friday in the worst one-day percentage drop since 2012.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , The stock lost 21.7%, the largest percent drop since July 25, 2012 when shares fell 25%, as tracked by Dow Jones Market Data Group. Shares have fallen 33% this year, with added pressure as investors rotate out of technology names.                                                                                                                                                                                                                                                                                                                                                                                  , MEAT LOAF BECAME 'BAT OF HELL' ON TRUMP'S 'THE APPRENTICE'                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , The streaming giant added 8.3 million subscribers in the fourth quarter, just shy of the 8.5 million estimate. Forecasts for the current quarter also disappointed with plans to add 2.5 million vs. 4 million in the year-ago period.                                                                                                                                                                                                                                                                                                                                                                                  , Still, total subscribers, globally, hit 222 million.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , "Overall, the business was healthy. Retention was strong. Churn was down. Viewing was up. But on the margin, we just -- we didn't grow acquisition quite as fast as we would have liked to see" said chief financial officer Spencer Neumann on the earnings call.                                                                                                                                                                                                                                                                                                                                                      , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , In this Feb. 28, 2017, file photo, Netflix Founder and CEO Reed Hastings smiles during an interview in Barcelona, Spain. (AP Photo/Manu Fernandez, File) (Associated Press)                                                                                                                                                                                                                                                                                                                                                                                                                                             , Why the slowdown? CEO Reed Hastings said he and his team are trying to figure that out.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , "There's a number of potential explanations with COVID, but then we worry about hanging too much on that. There's more competition than there's ever been. But we've had Hulu and Amazon for 14 years. So it doesn't feel like any qualitative change there. And overall, confidence in streaming becomes all of entertainment. Linear dissipates over the next 10 to 20 years. Very high confidence in that thesis because everyone's coming into streaming. So like market size, very large. Our execution is steady and getting better. So for now, we're just like staying calm and trying to figure out," he said. , Coming up, Season 2 of Bridgerton and The Adam Project will debut in March.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/google-epic-games-agree-trial/story.aspx?guid={DE37E3EA-3954-41CB-AB0A-77DAD8DE7477}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-22 01:47:00 </td>
   <td style="text-align:left;"> Google, Epic Games agree to trial in early 2023 - MarketWatch </td>
   <td style="text-align:left;"> Google parent Alphabet Inc. 
        GOOGL,
        -2.22%
        GOOG,
        -2.56%
       and Epic Games Inc. have agreed to start their antitrust lawsuit in late January 2023, according to a filing in federal court in Northern California last week. Epic, the maker of the popular Fortnite game, is suing Google over alleged antitrust violations after Fortnite was dropped from the both the Google Play Store and Apple Inc.'s 
        AAPL,
        -1.28%
       App Store in August 2020. Epic and Apple went to court last year, a split decision of sorts that has been appealed by both companies., Netflix Inc. brought in more than 8 million new subscribers in the holiday quarter, but executives predicted that growth would suffer much more than expected at the beginning of 2022, sending shares screaming lower in after-hours trading.                                                                                                                                                                                                                                                                                                                                                                                   , Jon Swartz is a senior reporter for MarketWatch in San Francisco, covering many of the biggest players in tech, including Netflix, Facebook and Google. Jon has covered technology for more than 20 years, and previously worked for Barron's and USA Today. Follow him on Twitter @jswartz. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/21/stocks-making-the-biggest-moves-midday-netflix-peloton-disney-and-more.html </td>
   <td style="text-align:left;"> 2022-01-22 01:38:18 </td>
   <td style="text-align:left;"> Stocks making the biggest moves midday: Netflix, Peloton, Disney and more </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Check out the companies making headlines in midday trading.                                                                                                                                                                                                                                                                                                                                                                                                                            , Netflix – Shares of the streaming giant tanked 21.7%, on pace for their worst day since July 2012. The steep sell-off came after Netflix admitted that streaming competition was eating into its own growth in its fourth-quarter earnings release Thursday. Other media companies with streaming services also saw shares fall after Netflix issued lower-than-expected subscriber guidance. Disney shares fell 5.6%, while ViacomCBS dropped about 6%, and Discovery lost roughly 4%., Peloton – Shares of the at-home fitness company saw an 11.7% bounce on Friday after a major wipeout Thursday, when investors sold shares following a CNBC report that the company is halting production of its bikes and treadmills. Peloton then said Friday that it's reviewing production levels and considering layoffs.                                                                                                                                                           , Schlumberger – The oilfield services stock fell 1.8% on Friday despite a better-than-expected fourth-quarter report for Schlumberger. The company reported adjusted earnings per share of 41 cents per share, while analysts surveyed by Refinitiv were looking for 39 cents. Revenue also topped estimates. Schlumberger reported shrinking margins in its production systems unit.                                                                                                   , CSX – CSX shares dipped 3.2% even after the railroad operator beat earnings expectations for the fourth quarter. The company posted a profit of 42 cents per share, beating the StreetAccount consensus estimate by 1 cent. However, CSX reported volume fell from the previous year.                                                                                                                                                                                                  , Intuitive Surgical – Intuitive Surgical shares sunk 7.9% despite the company's quarterly earnings report beating expectations. Management said procedures using its DaVinci surgical system will be down significantly in the current quarter due to Covid surges.                                                                                                                                                                                                                     , PPG Industries – PPG's shares slipped 3% even after beating analysts' earnings expectations in its quarterly report. The paint and coatings maker said heightened supply and Covid-related disruptions from the fourth quarter are expected to continue in the current quarter.                                                                                                                                                                                                        , Intel – Intel's stock rose nearly 1% midday but closed flat, after the company announced plans to invest at least $20 billion in new manufacturing facilities outside Columbus, Ohio. The plants come as chipmakers work to accelerate supply to meet demand.                                                                                                                                                                                                                          , Rio Tinto – Rio Tinto shares retreated about 2.2% after Serbia revoked the mining company's lithium exploration licenses. Government leaders said the decision came after opposition from environmental groups. Rio had aimed to become one of the top producers of lithium, a key component in batteries.                                                                                                                                                                             , Under Armour – The apparel stock rose 1.4% after Citi upgraded Under Armour to buy from neutral. The firm said in a note to clients that the industry shift to online and direct-to-consumer shopping would Under Armour improve its profit margins.                                                                                                                                                                                                                                   , — CNBC's Tanaya Macheel, Jesse Pound and Yun Li contributed reporting                                                                                                                                                                                                                                                                                                                                                                                                                  , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                                                                                                                 , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                                                                                                                 , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                                                                                                                       , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                                                                                                                       , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                                                                                                                     , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-22 01:20:00 </td>
   <td style="text-align:left;"> Brazil 10Y Bond Yield Eases From Near 7-Week High </td>
   <td style="text-align:left;"> Brazil's 10-year government bond yield traded around 11% in January, easing from near a 7-week high of 11.595% hit on January January 18th, tracking a fall in global yields on falling risk sentiment. Domestically, President Bolsonaro is expected to sign the 2022 budget, which would remove a point of uncertainty. Still, Brazil's economic outlook remains clouded by high inflation and the prospect of rising rates, elevated unemployment, as well as fiscal and political concerns ahead of presidential elections in October. While neither candidate has formally declared his candidacy, former President Lula is leading the pools, and despite he suggesting he could name Geraldo Alckimin as a running mate if he is elected a worsening in Brazil’s budget deficit is on the radar. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/markets/oil-prices-russia-putin-ukraine-war </td>
   <td style="text-align:left;"> 2022-01-22 00:59:56 </td>
   <td style="text-align:left;"> Oil risks price rise as Putin inches into Ukraine </td>
   <td style="text-align:left;"> Mike Waltz, R-Fla., weighs in on Biden's cancellation of American pipelines and growing tensions at the Russia-Ukraine border.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , As Russian President Vladimir Putin inches closer to Ukraine, the world energy markets are facing a potentially seismic event threatening a global economic recession.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , With global oil supplies below normal and the International Energy Agency (IEA) reportedly admitting that it has been overstating global supplies, the loss of Russian oil and gas could be next to impossible to replace. In Europe, we have already seen natural gas prices surge to record highs as the continent feels the impact of being over-reliant on Russia for that product. On the petroleum side, Russia is currently the world's second-largest producer, and if it chooses to cut off supply or if supplies were disrupted because of an active war, the void in the global market would be massive.                                                                                 , THE STOCK MARKET IN BIDEN'S FIRST YEAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , President Biden said that he expects that Russia will move into Ukraine and suggested that the country could do what is called a "minor incursion" that might cause less severe sanctions. That seemed to invite Putin to cross some lines and an open invitation to invade. The administration had to walk back those comments. Ukraine also snapped back that there is no such thing as a minor incursion. The president still did warn Russia of "disaster" if it invades Ukraine, and that word could extend to the global energy space.                                                                                                                                                        , THE ECONOMY DURING BIDEN'S FIRST YEAR                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Former CIA officer Mike Baker reacts to Biden's Ukraine comments on 'Kennedy.'                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Biden and some leaders from the West are assuming that Russia is more than likely to not use oil and gas as a political weapon because the Russian economy is so dependent on oil and gas money. Yet, Putin suggests that he feels that the West is closing in on him, so desperate times might call for desperate measures.                                                                                                                                                                                                                                                                                                                                                                        , NORD 2 PIPELINE DEAL WILL HAND RUSSIA’S PUTIN KEYS TO EUROPE                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , Just recently, the Biden administration tried to stop Congress from putting new sanctions on Russia's crown jewel pipeline, the Nord Stream 2, so that the president could use that as leverage, taking a carrot-and-stick approach to try keeping him from invading Ukraine. The Nordstrom 2 pipeline is that controversial pipeline that Germany wanted over the objections of both President Trump and Biden that moves gas from Russia to Germany. The pipeline leaves not only Germany but also other parts of Europe more dependent on Russia for gas supply. Ukraine for its part knows very well the risk of getting gas from Russia, as Russia cut off its supply in 2006 and 2009.        , Biden did lift sanctions on the pipeline to allow its completion as a gesture to Germany, who now probable regrets working with Russia. Russia has already played hardball this cold European winter, moving supplies slowly over existing pipelines, and some European politicians and others have accused Russia of holding back gas supplies to Europe to use its influence to speed up the certification of Nord Stream 2.  Senate Democrats blocked legislation by Republicans to sanction the pipeline.                                                                                                                                                                                       , Pipeline networks are a big deal in this dispute, as Ukraine is a major part of the pipeline network that helps spread the natural gas supply throughout Europe. Russia is the gas producer, Ukraine is the transporter. Russia provides over 25% of the natural gas consumed in the European Union, and 80% of that moves through Ukrainian pipelines.                                                                                                                                                                                                                                                                                                                                             , 23,950 million natural gas pipelines                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , 13,770 miles of trunk lines                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , 10,180 miles of branch pipelines                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , 72 compressor stations, with 702 compressors and push supply                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , After Russia cut off the supply in 2009 to Ukraine, it was reported that 18 European countries saw major drops in or complete cutoffs of their gas supplies transported through Ukraine from Russia.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , That brings us back to oil. It is not good when the world's second-largest oil producer that produced 10.1 million barrels of oil and condensate last month goes to war.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , In years past, fear of war in and of itself would drive oil prices higher in what became known as a geopolitical risk premium. In recent years, that risk premium was lower because of the U.S. shale revolution that gave the world a buffer of supply. Yet the US oil industry has been held back by trying to remain profitable after some bad years, especially after COVID-19, and held back by the Biden administration that has created an unfriendly investment environment for fossil fuels. Without that U.S. buffer, the supply situation globally looks tight, and based on recent news tighter than a major world agency thought.                                                      , The International Energy Agency reported that the global inventory of oil fell by an astounding 600 million barrels last year, more than the 400 million that was expected.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Preliminary data for December show OECD industry stocks falling by another 45 MB while volumes of oil on the water rose.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , That means that the global oil supply is much tighter than they thought and makes us even more at risk of upside price shocks if a Russian war in Ukraine cuts off more oil supply.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , READ MORE ON FOX BUSINESS BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , Phil Flynn is senior energy analyst at The PRICE Futures Group and a Fox Business Network contributor. He is one of the world's leading market analysts, providing individual investors, professional traders, and institutions with up-to-the-minute investment and risk management insight into global petroleum, gasoline, and energy markets. His precise and timely forecasts have come to be in great demand by industry and media worldwide and his impressive career goes back almost three decades, gaining attention with his market calls and energetic personality as writer of The Energy Report. You can contact Phil by phone at (888) 264-5665 or by email at pflynn@pricegroup.com. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/biden-presses-congress-pass-chips/story.aspx?guid={FDABB4F4-66CF-4E97-9470-5664091F85BE}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-22 00:59:14 </td>
   <td style="text-align:left;"> Biden presses Congress to pass chips funding as he hails Intel's plan for new site - MarketWatch </td>
   <td style="text-align:left;"> President Joe Biden on Friday pressed lawmakers to pass what's known as the CHIPS Act, which would provide $52 billion to boost U.S. semiconductor production. Speaking at the White House alongside Intel 
        INTC,
        
       CEO Pat Gelsinger, Biden hailed the company's plans to invest more than $20 billion to build the world’s largest chip-manufacturing site in Ohio. Biden, however, said the U.S. produces barely 10% of computer chips and that Friday's announcement is "just the beginning."     

, President Joe Biden is signaling that monthly payouts for an expanded child tax credit probably won't make a comeback, even as he aims to get Congress to pass other parts of his social-spending and climate package.                                                                                                                                                                                                                                                                                                             ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Robert Schroeder is the Washington bureau chief for MarketWatch. Follow him on Twitter @mktwrobs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-01-22 00:57:00 </td>
   <td style="text-align:left;"> London Stocks Extend Losses For 2nd Session </td>
   <td style="text-align:left;"> The FTSE 100 dropped 1.3% to close at 7,494 on Friday, the lowest since January 10th, in line with its European peers, and extending losses for 2nd straight session as investors remained concerned about the impact of rising inflation and tighter monetary policy by major central banks on the slowing economic recovery. At the same time, tensions between the US and Russia continued to weigh on sentiment, while energy shares were hit by a decline in crude prices. On the economic data front, British retail sales slumped 3.7% in December, a far bigger hit than the 0.6% fall forecast by markets and the biggest decrease since last January. On the week, the index snapped four consecutive weeks with gains after falling 0.7%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/south-africa/stock-market </td>
   <td style="text-align:left;"> 2022-01-22 00:56:36 </td>
   <td style="text-align:left;"> South African Stocks Close at Over 1-Week Low </td>
   <td style="text-align:left;"> The FTSE/JSE All Share Index fell 1.8% to close at 74,835 on Friday, its lowest since January 11th, pulled down by miners and tech stocks, as worse-than-expected US corporate earnings and the prospect of tighter US Federal Reserve monetary policy weighed on sentiment. At the same time, investors bet that the South African Reserve Bank will lift its repo rate by another 25bps to 4% during its first monetary policy committee meeting of the year next week, with the decision due on January 27th. Meanwhile, the World Bank has approved South Africa's request for a $750 million loan, aiming to help protect the poor and support economic recovery from the pandemic. The low-interest loan “will contribute towards addressing the financing gap stemming from additional spending in response to the Covid-19 crisis,” Treasury Director-General Dondo Mogajane said. For the week, the JSE lost about 0.4%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-01-22 00:48:00 </td>
   <td style="text-align:left;"> Italian Shares at 4-Week Lows </td>
   <td style="text-align:left;"> The FTSE MIB Index closed 1.8% lower at 27,061 on Friday, the lowest in over four weeks, tracking a sell-off in global equities around jitters of high inflation and tighter monetary policy by the Federal Reserve. Healthcare shares fell 2.6%, led by Amplifon (-4.1%) and DiaSorin (-2.8%), while tech shares lost over 2%, driven by STMicroelectronics (1.9%). At the same time, industrials dropped 2.2%, led by Prysmian (-3.8%) and Tenaris (-3.7%), the latter due to a global sell-off in steel pipe manufacturers. On the economic data front, the Bank of Italy lowered its projections of Italy’s GDP for this year to 3.8% from 4%, as the current surge in coronavirus cases clouded the economy’s outlook. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-01-22 00:47:00 </td>
   <td style="text-align:left;"> European Stocks End 2% Lower </td>
   <td style="text-align:left;"> European equity markets closed deeply in the red on Friday, with Frankfurt’s DAX and the pan-European Stoxx 600 shedding about 2% each, dragged down by automakers and banks stocks. Energy stocks were also under pressure as crude prices fell from recent seven-year highs. Among single stocks, wind turbine manufacturer Siemens Gamesa slipped more than 10% after cutting its revenue guidance for 2022, and its owner Siemens Energy plunged 16%. On the economic data front, Britain's retail sales slumped 3.7% in December, the largest decline since last January and compared with forecasts of a 0.6% drop. For the week, European shares dropped 1.5% as the prospect of tighter monetary policy across the globe this year and tensions between the US and Russia weighed on sentiment. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/france/stock-market </td>
   <td style="text-align:left;"> 2022-01-22 00:46:00 </td>
   <td style="text-align:left;"> French Shares Close at 4-Week Lows </td>
   <td style="text-align:left;"> The CAC 40 Index fell 1.8% to close at 7,067 on Friday, the lowest in four weeks and the second consecutive weekly decline, as expectations of tighter monetary policy by the Federal Reserve pressured technology stocks and risk sentiment. The tech sector traded over 2% lower, in line with its global counterparts, dragged by STMicroelectronics (-1.9%) and Dassault Systemes (-2.4%), while the energy sector lost 2.2% as oil prices fell from seven-year highs. In the meantime, ArcelorMittal (-7.3%) and Valourec (-6.6%) both plunged, in line with the steel pipe manufacturers amid a sector wide sell-off as investors took profits from the industry's recent rally. Lastly, Stellantis shares fell 3.6% after the Chinese group Dongfeng Motor sold-off 1.2% of the French firm’s capital at a price of 18.3 euros per share, in line with current prices. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/stock-market </td>
   <td style="text-align:left;"> 2022-01-22 00:45:14 </td>
   <td style="text-align:left;"> The FTSE 100 Index dropped 1.27% </td>
   <td style="text-align:left;"> United Kingdom Stock Market fell 96 points. Leading the losses are Carnival (-5.45%), Entain PLC (-4.87%) and TUI (-4.76%). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-22 00:37:27 </td>
   <td style="text-align:left;"> Canada 10Y Bond Yield Eases From Near 3-Year High </td>
   <td style="text-align:left;"> The yield on the Canadian 10-year government bond traded below 1.80%, after hitting a near 3-year high of 1.89% on January 18th, tracking lower US Treasury yields as investors turned more cautious amid falling equities and political tensions between the US and Russia over Ukraine. At the same time, a tighter Fed policy this year seems to be priced in and investors now bet on a bigger than 25 basis points hike in the fed funds rate by March. Also, domestically, weaker-than-expected retail sales data prompted investors to question if the BoC should start hike already in its next monetary policy decision, 75% of analysts see that the Canadian central bank will maintain the borrowing costs unchanged, while 25% see a 25 bps hike. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ivory-coast/inflation-cpi </td>
   <td style="text-align:left;"> 2022-01-22 00:37:00 </td>
   <td style="text-align:left;"> Ivory Coast December Inflation Rate Highest since 2011 </td>
   <td style="text-align:left;"> The annual inflation rate in the Ivory Coast rose to 5.6 percent in December of 2021 from 5.5 percent in the previous month. it was the steepest inflation rate since May of 2011, mainly pushed by prices of food &amp; non-alcoholic beverages (12.3 percent vs 11.4 percent in November), in particular fresh vegetables (31.6 percent), fish (15.6 percent) and meat (12.3 percent); and housing &amp; utilities (5.6 percent vs 4.8 percent). On a monthly basis, consumer prices inched up by 1.2 percent, the most in ten months, after a 0.7 percent increase in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/switzerland/currency </td>
   <td style="text-align:left;"> 2022-01-22 00:32:00 </td>
   <td style="text-align:left;"> Swiss Franc Rebounds on Lower Risk Mood </td>
   <td style="text-align:left;"> The Swiss franc strengthened to 0.91 per USD, not far from the two-month high of 0.909 touched on January 13th, as concerns over economic recovery, rising inflation, and potential of geopolitical unrest send investors to safer haven assets. The data showed consumer prices in the Euro Area increased at a record pace during December. Also, talks between NATO members and Russia failed to de-escalate growing tensions on the Ukrainian border. Meanwhile, the OECD stated that the Swiss National Bank should not alter its expansive monetary course until the country’s post-pandemic recovery fund is established, as domestic inflation is expected to remain moderate when compared to the rest of Europe and the United States. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/nickel </td>
   <td style="text-align:left;"> 2022-01-22 00:26:00 </td>
   <td style="text-align:left;"> Nickel Prices at Over Decade High </td>
   <td style="text-align:left;"> Benchmark nickel futures on the London Metal Exchanged traded above $24,000 a tonne in January, the highest since July 2011, amid rising demand and low inventories. On-warrant nickel stocks were at their lowest since December 2019 at 48,846 tonnes and nickel stocks in Shanghai Futures Exchange warehouses are close to record lows at 4,859 tonnes. Meanwhile, the demand from the battery sector remains firm as electric vehicles sales are rising and economic growth in China is set to pick up again amid further stimulus. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/currency </td>
   <td style="text-align:left;"> 2022-01-22 00:19:00 </td>
   <td style="text-align:left;"> Canadian Dollar Falls From Near 10-Week High </td>
   <td style="text-align:left;"> The Canadian dollar traded above $1.25 on Friday, the lowest since January 14th as investors are moving away from risky assets. Weaker-than-expected results from companies that soared in the pandemic started to weigh on the US stock market while tensions between Russia and NATO over Ukraine are boosting demand for safe-haven. Domestically, in November, retail sales increased only 0.7 percent over a month earlier and missing preliminary estimates of a 1.2 percent increase while preliminary estimates showed sales in December fell 2.1 percent. Also, the recent fall in oil prices from a 7-year high weight on the loonie. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/modernas-stock-has-tumbled-enough/story.aspx?guid={45A9210A-1424-4BE5-8DFE-9DD5D9323A52}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-22 00:12:22 </td>
   <td style="text-align:left;"> Moderna's stock has tumbled enough for a long-time bear to say stop selling - MarketWatch </td>
   <td style="text-align:left;"> Shares of Moderna Inc. 
        MRNA,
        -4.45%
       slumped 2.3% toward an eight-month low in morning trading Friday, and have tumbled 26.5% amid a six-day losing streak, enough for formerly bearish BofA Securities analyst Geoff Meacham to say investors should stop selling the biotechnology company. Meacham raised his rating to neutral from underperform, and lifted his stock price target to $180 from $135. Meacham said he has been bearish on Moderna for some time because of "overly optimistic" Wall Street assumptions on COVID-19 boosters, but has valuation has compressed in recent months and as the pandemic starts moving toward endemic status, he is now focusing more on the beyond-"Spikevax" pipeline. "Bulls previously called Moderna the 'Tesla of Biotech,' which meant that the stock narrative overruled valuation assumptions but now, the latter looks more reasonable," Meacham wrote in a note to clients. "As a results, we think the risk/reward in [Moderna] shares is more favorable, considering Moderna's leadership position in mRNA technology." The stock, which has now lost nearly two-thirds of its value from the August 2021 peak, has shed 35.5% so far this year, while the S&amp;P 500 
        SPX,
        -1.89%
       has declined 5.9%., Peloton Interactive Inc. shares bounced back in after-hours trading Thursday, after Chief Executive John Foley combatted media reports claiming a production halt and layoffs.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Tomi Kilgore is MarketWatch's deputy investing and corporate news editor and is based in New York. You can follow him on Twitter @TomiKilgore. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/21/business/quitting-contagious.html </td>
   <td style="text-align:left;"> 2022-01-22 00:00:08 </td>
   <td style="text-align:left;"> You Quit. I Quit. We All Quit. And It’s Not a Coincidence. - The New York Times </td>
   <td style="text-align:left;"> The Great Read                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Why the decision to leave a job can become contagious.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Cat Del Carmen, left, and Erika Cruz are not exactly mourning having left their jobs.Credit...Michelle Groskopf for The New York Times                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , By Emma Goldberg                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Something infectious is spreading through the work force. Its symptoms present in a spate of two-week notices. Its transmission is visible in real time. And few bosses seem to know how to inoculate their staff against this quitagion.                                                                                                                                                                                                                                                                                                                                                                                                    , It catches quickly. “There’s a shock when you see multiple people leaving — it’s like, oh, is there something I’m not seeing?” said Tiff Cheng, 27, who left her job in digital marketing in July, along with five of her close friends at the 40-person agency. “Is it my time to leave as well?”                                                                                                                                                                                                                                                                                                                                           , Quitting rates were high in August, September and October. Then, according to Labor Department data, they climbed even further: More than 4.5 million people left their jobs voluntarily in November, a record high in two decades of tracking.                                                                                                                                                                                                                                                                                                                                                                                              , Economists explained the numbers by noting that competition for workers led to better pay and benefits, driving some to seek out new opportunities. Psychologists have an additional explanation: Quitting is contagious.                                                                                                                                                                                                                                                                                                                                                                                                                    , When workers weigh whether to jump jobs, they don’t just assess their own pay, benefits and career development. They look around and take note of how friends feel about the team culture. When one employee leaves, the departure signals to others that it might be time to take stock of their options, what researchers call “turnover contagion.”                                                                                                                                                                                                                                                                                       , So quitting begets more quitting, a challenge that employers can’t always solve with raises or perks. Even a single resignation notice can breed a “hot spot,” said Will Felps, who teaches management at the University of New South Wales and was an author of a study of turnover contagion.                                                                                                                                                                                                                                                                                                                                              , Mr. Felps and his team studied staffing at a hospitality company and a selection of bank branches, all in the United States, and found that one worker’s decision to leave is especially likely to inspire others who don’t feel strongly embedded at the company. In a recent poll of more than 21,000 LinkedIn members, 59 percent said a colleague’s departure had led them to consider quitting as well.                                                                                                                                                                                                                                 , The office has long been a petri dish for infectious behavior. Lying, cheating and job satisfaction all tend to spread from desk to desk. Financial advisers, for example, are 37 percent more likely to commit misconduct if they encounter teammates who have done so, what researchers refer to as “peer effects,” noting that one case of misconduct results on average in an additional 0.59 cases. Employees also mimic the nutritional patterns of people they sit with in the cafeteria. Teammates are suggestible to one another in far subtler ways than they realize.                                                             , But when it comes to heading for the exit, peer effects are particularly potent.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , “When you walk by a restaurant and it’s full of people, it’s a clue this restaurant is pretty good,” Mr. Felps said. “Similarly, when the people you know, like and respect are leaving a job, you think maybe the grass is greener somewhere else.”                                                                                                                                                                                                                                                                                                                                                                                         , Here are more fascinating tales you can’t help but read all the way to the end.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Ms. Cheng saw her inbox begin to fill with resignation notes last summer. Every other week she got an email from a colleague who was quitting her company, where hours were long and career advancement options seemed limited. She decided to turn full time to her own coaching business, which she now runs from Vancouver, British Columbia.                                                                                                                                                                                                                                                                                             , “It’s always really scary to make a decision to leave your job, and it was nice to be able to see other people were doing it,” Ms. Cheng said. “It didn’t feel as lonely, or like I was an outsider.”                                                                                                                                                                                                                                                                                                                                                                                                                                        , A sense of workplace disaffection and restlessness started growing for many Americans in the early stages of the pandemic. For some, social media became a therapy couch, a space to vent those employment frustrations.                                                                                                                                                                                                                                                                                                                                                                                                                     , Back in March 2020, Erika Cruz, 31, was working at a Silicon Valley start-up, where she had grown disgruntled with the hallmarks of work life: “meetings that could have been an email” and lack of control over her schedule.                                                                                                                                                                                                                                                                                                                                                                                                               , She got the motivation she needed to leave that summer when she watched a friend she had met on Instagram ditch a cushy tech job to open a coaching firm. Then Ms. Cruz, who had about six months of living expenses saved up, moved back to her parents’ home in the Bay Area and put in her one month’s notice at work. She sought advice from social media about how to start a business. Ms. Cruz realized, though, that there was no one-size-fits-all approach to upending a career.                                                                                                                                                   , “If you Google banana breads, there’s over a million recipes online, and they’re all going to be good but they’re all slightly different,” she said. “You have to choose your own recipe.”                                                                                                                                                                                                                                                                                                                                                                                                                                                   , It’s the story of the pandemic: When people posted their banana bread photos, they influenced their friends to start baking as well. But like quitting, it was something no two people did the same way.                                                                                                                                                                                                                                                                                                                                                                                                                                     , The friend who inspired Ms. Cruz’s resignation, Cat Del Carmen, 34, agreed that it was important to develop her own quitting strategy. Ms. Del Carmen was able to leave a job at Adobe by cutting back spending on restaurant meals, vacations and TJ Maxx splurges. The six months after she left her job were high pressure financially. Ms. Del Carmen drew comfort from her correspondence with friends on social media who were also navigating the post-paycheck territory.                                                                                                                                                            , That bond forged by resignation, as people look to one another for inspiration and affirmation, is a phenomenon that predates the pandemic.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , “It’s a huge decision,” said Anthony Klotz, an organizational psychologist at Texas A&amp;M University. “If you Google how to resign from your job, there’s lots of conflicting guidance. Those answers are not in a company handbook. It makes sense people reach out for sounding boards from trusted others.”                                                                                                                                                                                                                                                                                                                                 , Aimee Wells, 53, who works in public relations, had her own quitagion experience years ago. She had been working at a global marketing firm in San Francisco, where she bristled at the time constraints of corporate life. She was never able to drop off her son at kindergarten. She remembered watching the 1996 movie “One Fine Day,” in which Michelle Pfeiffer plays an architect who decides to make her family a priority over high-powered work. It left Ms. Wells grappling with how to reset the balance between her own corporate job and personal life (far as it was from the realities of Ms. Pfeiffer and George Clooney’s)., One evening, on the train coming home from work at 6, she ran into a neighbor carrying shopping bags full of files, office supplies and photographs. The neighbor told Ms. Wells that she had just quit the role that was burning her out.                                                                                                                                                                                                                                                                                                                                                                                                   , “I went home and starting thinking about it a lot more seriously,” Ms. Wells said. One month later, she put in her own resignation notice, catalyzed by the run-in with her neighbor. “She was like my hero.”                                                                                                                                                                                                                                                                                                                                                                                                                                , The payoffs for some pandemic quitters have been significant. Nikissa Granados, 26, was weighing whether to leave her job at an Orange County, Calif., school in 2020 to do freelance social media marketing. She made the leap after seeing two of her teammates resign.                                                                                                                                                                                                                                                                                                                                                                    , Ms. Granados went from making $2,100 a month, spending days on her feet setting up cots for nap time and begging children to wear their masks, to making as much as $8,000 monthly while dictating her own schedule, she said. She realized something now viscerally clear to many child care providers: In her work at the school, the mismatch between strain and pay had been stark.                                                                                                                                                                                                                                                      , For employers, replacing just one quitter is a straightforward task. But replacing several, or even dozens, is far more challenging, and the interim period tends to leave existing staff with a heavier load, while recruiters field awkward questions about what’s fueling all the departures. With quitting rates soaring, some executives are wondering how to lift morale.                                                                                                                                                                                                                                                              , Seth Besmertnik, chief executive of the marketing software company Conductor, had seen his company’s turnover rates hover in the low single digits for years. He even worried that his retention was too strong, making it hard to scout new talent.                                                                                                                                                                                                                                                                                                                                                                                         , Over the last two years, though, turnover rose into the double digits. Mr. Besmertnik had to get creative in his tactics to keep workers content, including adding new holidays and bringing Broadway actors from “Hamilton” and “Dear Evan Hansen” to sing “Burn” and “Waving Through a Window” (respectively) for staff during all-company video meetings.                                                                                                                                                                                                                                                                                 , Career coaches, meanwhile, worry that some people are being too easily influenced by the behaviors of their roaming colleagues. Kathryn Minshew, chief executive of the Muse, a job search site, warns clients that a single employee’s desire to leave a company shouldn’t have too much bearing on the decisions that friends make.                                                                                                                                                                                                                                                                                                        , “When one person announces their resignation, there are usually some questions from their colleagues and workplace friends,” she said. “‘Where are you going? Why are you leaving?’”                                                                                                                                                                                                                                                                                                                                                                                                                                                         , That Pied Piper trail won’t always lead people to better options, and Ms. Minshew advises workers to assess their companies with the hyper-individualized approach they might take to building relationships.                                                                                                                                                                                                                                                                                                                                                                                                                                , “The idea that somebody would publish a list of the 50 best people to marry in New York City is silly,” she continued. “Similarly, I think the best companies to work for is a bit of a silly idea.”                                                                                                                                                                                                                                                                                                                                                                                                                                         , But logical career advice can’t always prevent the contagion from catching.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , “There’s a little bit of a ‘take this job and shove it’ feeling,” Ms. Wells said. “If you’re in a company where people all start leaving, you’re like, ‘Why am I the last one sitting here?’”                                                                                                                                                                                                                                                                                                                                                                                                                                                , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/01/21/middleeast/yemen-detention-strike-internet-outage-intl/index.html </td>
   <td style="text-align:left;"> 2022-01-21 23:58:32 </td>
   <td style="text-align:left;"> Yemen: Airstrikes kill 70 people and knock out internet - CNN </td>
   <td style="text-align:left;"> (CNN)At least 70 people were killed and more than 130 injured when an airstrike hit a detention center in Yemen on Friday, Doctors Without Borders (MSF) said, as the Saudi-led coalition continued to ramp up its deadly offensive on rebels in the war-torn nation.                                                              , Another airstrike early Friday hit a telecommunications building in the strategic port city of Hodeidah, causing a nationwide internet blackout, according to NetBlocks, an organization that tracks network disruptions. At least three children were killed in that attack, Save the Children said.                               , The Norwegian Refugee Council said the internet blackout, which was still ongoing as of Friday evening, would affect aid delivery.                                                                                                                                                                                                  , The Iran-back Houthi rebels, who control much of Yemen, blamed the Saudi-led coalition for the strikes. CNN has reached out to the coalition for comment.                                                                                                                                                                           , A coalition led by Saudi Arabia and the United Arab Emirates launched an offensive in 2015 to restore Yemen's internationally recognized government, after it was ousted by the Houthis. The coalition has intensified its attacks in the wake of a Houthi missile and drone strike in the UAE capital Abu Dhabi earlier this week. ,                                                                                                                                                                                                                                                                                                                                     , The Houthi-run media outlet Al Masirah showed graphic video of people under rubble in the aftermath of Friday's detention center strike in the northern Yemeni city of Sa'ada. The Red Cross said it had sent emergency medical supplies to two hospitals that had received a "very high" number of casualties.                     , "From what I hear from my colleague in Sa'ada there are many bodies still at the scene of the airstrike, many missing people," said Ahmad Mahat, head of the MSF mission in Yemen. "It is impossible to know how many people have been killed. It seems to have been a horrific act of violence."                                   , An MSF-supported hospital in Sa'ada has been overwhelmed by an influx of wounded people and cannot receive more, Mahat said. Two other hospitals in the city have also received large numbers of casualties, according to MSF.                                                                                                      , International aid groups have been struggling to gather details about the strike because of the internet blackout, multiple aid workers told CNN.                                                                                                                                                                                   , The Saudi-led coalition did not comment on the the strikes on the telecommunications building or the detention center, but said Friday that it had hit the port of Hodeidah, taking down "one of the [Houthis'] dens of maritime piracy and organized crime."                                                                       , The coalition also said it attacked "military targets" in the capital Sanaa on Friday, claiming to have conducted the operation "in response to the threat of hostile attacks," Saudi state-owned SPA said.                                                                                                                         , "The ICRC is deeply concerned about the intensification of hostilities over recent days, including attacks against cities across Yemen, in Saudi Arabia and in the United Arab Emirates, and deplores the human toll this escalation has caused," the International Committee of the Red Cross said Friday.                         , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/politics/biden-minimum-wage-hike-federal-agencies </td>
   <td style="text-align:left;"> 2022-01-21 23:56:00 </td>
   <td style="text-align:left;"> Biden's $15 minimum wage hike for federal agencies goes into effect </td>
   <td style="text-align:left;"> Many businesses are worried President Biden's economic plan to raise taxes and minimum wage could hurt their companies. FOX Business' Grady Trimble with more.                                                                                                                                                                                                 , Federal agencies are being directed to raise the minimum wage for government employees to $15 an hour, according to new guidance from the Office of Personnel Management.                                                                                                                                                                                      , The directive will affect nearly 70,000 federal workers, most of whom work at the Departments of Defense, Agriculture and Veteran Affairs, OPM said in a statement on Friday. The new minimum wage applies to all executive branch agencies, except the U.S. Postal Service and Postal Regulatory Commission.                                                  , WHERE ARE SURGING CONSUMER PRICES HITTING AMERICANS THE HARDEST?                                                                                                                                                                                                                                                                                               , Agencies are expected to implement the higher wage by Jan. 30. There are 2.2 million federal workers, a majority of whom already earn $15 an hour. There are 2.2 million federal workers, the largest share – 56,000 – who don't yet earn $15 an hour work at the Department of Defense, according to the memo.                                                , NEW YORK, NEW YORK - SEPTEMBER 21: U.S. President Joe Biden addresses the 76th Session of the U.N. General Assembly on September 21, 2021 at U.N. headquarters in New York City. ((Photo by Timothy A. Clary-Pool/Getty Images) / Getty Images)                                                                                                                , "Raising pay rates across the federal government to a minimum of $15 per hour reflects our appreciation for the federal workforce and our values as a nation," Kiran Ahuja, director of the Office of Personnel Management, said in the statement.                                                                                                             , The rule comes after President Biden signed an executive order in April raising the minimum wage for federal contractors from $10.95 an hour. The minimum wage will continue to be indexed to inflation in the coming years so that the pay reflects changes in the cost of living.                                                                            , Biden's executive order also eliminated the tipped minimum wage for federal contractors by 2024, requiring those workers to earn the same $15 minimum wage as other employees.                                                                                                                                                                                 , "Raising the minimum wage enhances worker productivity and generates higher-quality work by boosting workers’ health, morale, and effort; reducing absenteeism and turnover; and lowering supervisory and training costs," the White Houses said in April.                                                                                                     , Activists appeal for a $15 minimum wage near the Capitol in Washington, Thursday, Feb. 25, 2021. ((AP Photo/J. Scott Applewhite))                                                                                                                                                                                                                              , Democrats have pushed for legislation that would raise the federal minimum wage to $15 per hour by 2025, but have failed to move it through Congress.                                                                                                                                                                                                          , A recent analysis published by the Congressional Budget Office, a nonpartisan agency, found that as many as 3.7 million workers could lose their jobs as a result of the minimum wage increase. At the same time, the CBO projects that some 17 million workers would receive a pay boost.                                                                     , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                        , The federal minimum wage has not increased in more than a decade, although a growing number of states have voted to adopt their own wage increases. There are 29 states with wages above the federal minimum wage, according to the National Conference of State Legislatures. At $15 an hour, California currently has the highest minimum wage in the nation. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/slovenia/producer-prices-change </td>
   <td style="text-align:left;"> 2022-01-21 23:43:56 </td>
   <td style="text-align:left;"> Slovenia Producer Inflation at New All-Time High </td>
   <td style="text-align:left;"> Producer prices in Slovenia jumped 10.6 percent year-on-year in December of 2021, quickening from a 9.9 percent rise in the previous month. It was the highest producer price inflation since records began, mainly driven by prices in manufacturing industries (10.9 percent vs 10.2 percent in November), mining &amp; quarrying (7.1 percent vs 6.7 percent), and to a lesser extent, water supply (4.8 percent vs 3.0 percent). In contrast, inflation remained steady for prices of utilities (2.7 percent). On a monthly basis, producer prices rose by 0.6 percent, easing from a 0.9 percent rise in November. On a yearly basis, producer inflation climbed to 5.5 percent, compared with 5.1 percent in 2020. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/real-estate/real-estate-expert-predicts-commercial-bloodbath </td>
   <td style="text-align:left;"> 2022-01-21 23:30:36 </td>
   <td style="text-align:left;"> Real estate expert warns of commercial 'bloodbath' </td>
   <td style="text-align:left;"> The Commercial Academy J. Scott Scheel discusses the massive defaults that will hit the commercial real estate industry.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , During an interview on "Varney &amp; Co" real estate expert J. Scott Schell predicted a commercial real estate "bloodbath" due to disruptions in the industry from the COVID-19 pandemic.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , HOME SALES HIT 16-YEAR HIGH                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , J. SCOTT SCHEEL: What we're dealing with is a lot of pent-up forces that are all coming into play right now. The Central Business District Office has been devastated by stay-at-home pandemic restrictions. You know, all of the disruptions that we've seen there has caused all of those assets to really be in non-covenant compliance. Same thing with Class A retail that didn't get absorbed in the last cycle. And then certainly all of your hospitality has been devastated throughout this pandemic and over the course of last couple of years that in and of itself is going to cause massive defaults.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , The good news is, is that there's opportunities for these things to turn around for investors. But the bad news is that through the Troubled Asset Deferral Program, which is part of the CARES Act, nobody has reported on these for 18 months. We have 18 months of defaults that are all going to start hitting now. That happened, that program terminated as of January 1, 2022, and they've got 60 days to report it. So by the second quarter of this year, those things are going to start to come out and banks are going to have to deal with that. So that's going to be a huge crisis in and of itself. And then obviously, we know that the banks, when they start to take on defaulted assets, they're not really in a position to make loans. And so, so many of those assets that did stabilize but have now been hurt are going to be hamstrung by their balance sheets because 3 years of historic operating statements won't really be there to support new debt with values plummeting. There's going to be a lot of blood in the streets and a lot of folks who are going to be looking for safe haven. , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , WATCH THE FULL INTERVIEW HERE:                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , The Commercial Academy J. Scott Scheel discusses the hit the commercial real estate industry has taken due to the COVID-19 pandemic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/stock-market </td>
   <td style="text-align:left;"> 2022-01-21 23:22:25 </td>
   <td style="text-align:left;"> Canada Stocks at 1-Month Low </td>
   <td style="text-align:left;"> Canada’s main stock index, the S&amp;P/TSX, extended losses for a fourth straight session on Friday, sliding to one-month lows as weaker crude futures pressured heavyweight energy stocks. On the data front, retail sales in Canada fell 2.1% over a month earlier in December, according to preliminary estimates, while final data showed the rise in November came short of expectations. On corporate updates, Canadian Imperial Bank of Commerce analysts cut the target of food processing firm George Weston Ltd to C$171 from a prior C$175 per share. On a weekly basis, the index is on track to drop 2.5%, its worst performance in a year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/slovenia/unemployment-rate </td>
   <td style="text-align:left;"> 2022-01-21 23:21:54 </td>
   <td style="text-align:left;"> Slovenia Jobless Rate Lowest since 2008 </td>
   <td style="text-align:left;"> Slovenia’s unemployment rate fell to 6.7 percent in November of 2021, the lowest since November of 2008, from 8.6 percent in the same month of the previous year. The number of unemployed declined by 18,760 to 65,379 while the number of employed rose by 23,662 to 913,420. In October, the jobless rate was slightly higher at 6.8 percent. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/euro-area/consumer-confidence </td>
   <td style="text-align:left;"> 2022-01-21 23:09:48 </td>
   <td style="text-align:left;"> Eurozone Consumer Morale Weakest in 10 Months </td>
   <td style="text-align:left;"> The consumer confidence indicator in the Euro Area was little-changed at -8.5 in January 2022, the lowest level since March 2021 and compared with market expectations of -9.0, a preliminary estimate showed. In the European Union as a whole, consumer sentiment fell by 0.4 points to -10.0. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/natural-gas </td>
   <td style="text-align:left;"> 2022-01-21 23:09:00 </td>
   <td style="text-align:left;"> US Natural Gas Makes a Slight Comeback </td>
   <td style="text-align:left;"> US natural gas futures saw an uptick towards $3.9 per million British thermal units after hitting an over two-week low of $3.78 on January 20th, underpinned by expectations of record demand and tight supplies. Weather forecasts showed colder temperatures for the fortnight ahead, which is expected to cause domestic inventories to stand below the 5-year average for the first time since mid-December, as utilities draw larger-than-normal amounts of gas from storage. Meanwhile, a cold snap in Texas and other producing states has frozen wells and other equipment, curtailing output levels to their lowest in four months. Production in the lower 48 states averaged 95.3 bcfd so far this month, down from a record 97.6 bcfd in December. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/germany/stock-market </td>
   <td style="text-align:left;"> 2022-01-21 23:08:02 </td>
   <td style="text-align:left;"> DAX below 15500 </td>
   <td style="text-align:left;"> DAX decreased below 15500 points. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/21/banks-close-record-number-of-branches-in-2021-led-by-wells-fargo.html </td>
   <td style="text-align:left;"> 2022-01-21 23:05:16 </td>
   <td style="text-align:left;"> U.S. banks close record number of retail branches in 2021, Wells Fargo shutters most </td>
   <td style="text-align:left;"> , U.S. banks closed a record number of retail branches in 2021 as customers increasingly turn to digital banking and the industry consolidates.                                                                                                                , On net, U.S. banks shuttered 2,927 branches last year, according to S&amp;P Global Market Intelligence data. Banks closed nearly 4,000 branches and opened more than 1,000 branches, the analysis found.                                                         , Another record year for bank closures comes after 2020 had set the previous high as the Covid pandemic accelerated digital adoption.                                                                                                                         , "We anticipate that the downward trend in branches will continue for a number of years ... as more of the transaction-orientated aspects of banking are done digitally," Gerard Cassidy, head of U.S. bank equity strategy at RBC Capital Markets, told CNBC., The branch closures also come as banks consolidate, with merger and acquisition deals in the sector topping $77 billion in 2021, the highest level since 2006, according to S&amp;P Global.                                                                      , "As consolidation continues and there are overlapping branches when deals are approved, there's no need to have two branches on Main Street," Cassidy said.                                                                                                  , Wells Fargo was the top branch closer in 2021, closing on net 267 retail locations last year, according to S&amp;P Global Market Intelligence.                                                                                                                   , While JPMorgan Chase was the sixth-biggest net branch closer last year, the company opened the most branches in 2021 with 169 new locations as it expands into new markets.                                                                                  , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                       , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                       , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                             , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                             , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                           , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/brazil/stock-market </td>
   <td style="text-align:left;"> 2022-01-21 22:49:00 </td>
   <td style="text-align:left;"> Brazilian Equities Lack Direction </td>
   <td style="text-align:left;"> The main Sao Paulo stock index, Bovespa, swung between small gains and losses on Friday, as investors weigh the implications of a tighter monetary policy by the Federal Reserve, while disappointing US earnings raised concerns over economic recovery. Domestically, traders continued to monitor Brazil's fiscal scenario, with the Federal Government's initiative to reduce fuel and electricity prices adding to the pressure of civil servants for salary adjustments. President Jair Bolsonaro is expected to sign the 2022 Budget today, as the deadline expires. On the political front, a new poll showed Former leftist President Luiz Inacio Lula da Silva is pulling ahead of his likely rival, far-right President Jair Bolsonaro, and could win outright in the first-round of Brazil's October election. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/latvia/producer-prices-change </td>
   <td style="text-align:left;"> 2022-01-21 22:44:42 </td>
   <td style="text-align:left;"> Latvia Producer Inflation Hits Fresh Record </td>
   <td style="text-align:left;"> Producer prices in Latvia climbed to an all-time high of 25.1 percent year-on-year in December of 2021 from 23.4 percent in the previous month, driven by prices of domestically sold goods (31.4 percent vs 26.7 percent in November). On the other hand, charges for Latvian exports went up at a slower rate (19.6 percent vs 20.5 percent). Across different industries, prices of utilities jumped (62.9 percent vs 49.8 percent) and those of mining and quarrying rose slightly (13.8 percent vs 13.1 percent). Meanwhile, inflation slowed for manufacturing (18.7 percent vs 19 percent); and water supply, sewerage, and waste management (18.5 percent vs 18.7 percent). On a monthly basis, producer prices surged 1.6 percent, accelerating from a 1.2 percent rise in November. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/economy/bank-of-america-ceo-us-economy-will-normalize-in-2023 </td>
   <td style="text-align:left;"> 2022-01-21 22:38:01 </td>
   <td style="text-align:left;"> Bank of America CEO: US economy will normalize in 2023 </td>
   <td style="text-align:left;"> Bank of America chairman and CEO Brian Moynihan on when the U.S. economy will fully recover from the COVID pandemic.                                                                                   , In an exclusive interview on "Mornings with Maria" Friday, Bank of America Chairman and CEO Brian Moynihan discussed when he believes the economy will normalize following the COVID pandemic recovery., "Our experts have it [the economy] growing at 4% in 2022, but it starts to normalize in 2023," Moynihan told FOX Business’ Maria Bartiromo.                                                            , He believes that it’s up to the Federal Reserve to bring the economy back to pre-pandemic levels.                                                                                                      , "That's the job, to get the economy back to normal after its recovery from the pandemic, that the Fed has to do now," he pointed out.                                                                  , BANK OF AMERICA SLASHES ITS OVERDRAFT FEES                                                                                                                                                             , Improving unemployment numbers signal to the Fed it’s time for interest rate hikes, he said.                                                                                                           , "Unemployment’s down below 4%," he said. "Those numbers mean that the economy's fully recovered. That means the Fed has to normalize it."                                                              , He went on to say that Bank of America experts agree with the Fed’s four proposed rate hikes over 2022, helping the underlying economy get back to a normal growth rate.                               , "For the U.S. economy for next year, that's normalizing the activity, which is important to stop this potential speculative aspects and things that go on when money is too loose," he noted.          , Bank of America CEO Brian Moynihan speaks with Secretary John Kerry on June 10, 2021.  (Chris Jackson - WPA Pool/Getty Images)                                                                         , Amid looming policy changes, Moynihan said banks will serve as a "source of strength" for clients.                                                                                                     , "We'll be around. The story changes, regulations change," Moynihan explained. "We adapt to them. It's what we in the industry have to do."                                                             , "I think people have to remember, no matter what the debate is about incremental changes and things like that, the core banking system of the United States is a pillar of strength," he continued.    , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                            , Bank of America Chairman and CEO Brian Moynihan, in a wide-ranging interview with Maria Bartiromo, discusses company earnings, the state of the economy and the Federal Reserve.                       , After Bank of America’s earnings topped profit estimates for Q4, the CEO expects the market to be up in 2022.                                                                                          , "And as the Fed slows it down and the economy slows down, by design, back to more normalized conditions, of course, the market's going to reflect that."                                               , READ MORE FROM FOX BUSINESS </td>
  </tr>
  <tr>
   <td style="text-align:left;"> http://www.marketwatch.com/news/story/stocks-open-mostly-lower-netflix/story.aspx?guid={1E47A5A2-EA83-4F45-85B7-484ED540B97B}&amp;siteid=rss </td>
   <td style="text-align:left;"> 2022-01-21 22:37:51 </td>
   <td style="text-align:left;"> Stocks open mostly lower as Netflix drags down Nasdaq - MarketWatch </td>
   <td style="text-align:left;"> Stocks opened mostly lower Friday, on track for a hefty weekly loss as the Nasdaq Composite pushes deeper into correction territory. The Dow Jones Industrial Average 
        DJIA,
        -1.30%
       rose 56 points, or 0.2%, to 34,772, while the S&amp;P 500 
        SPX,
        -1.89%
       was off 0.1% at 4,477. The Nasdaq was down 0.2% at 14,126, bringing it down more than 5% for the week. The Nasdaq earlier this week entered correction territory, falling more than 10% from its record high set in November. Shares of Netflix Inc. 
        NFLX,
        -21.79%
       helped weigh on the Nasdaq in Friday's session, slumping 20% after delivering a disappointing quarterly report., After being poor, rich—then poor again—she now helps people avoid costly money mistakes.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , William Watts is MarketWatch’s senior markets writer. Based in New York, Watts writes about stocks, bonds, currencies and commodities, including oil. He also writes about global macro issues and trading strategies. Before moving to New York, he reported for MarketWatch from Frankfurt, London and Washington, D.C. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/21/goldman-partners-mint-15-million-pay-packages-as-boom-times-return-to-wall-street.html </td>
   <td style="text-align:left;"> 2022-01-21 22:36:13 </td>
   <td style="text-align:left;"> Boom times are back on Wall Street as some Goldman partners mint $15 million pay packages </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                               , Bonus season has arrived on Wall Street, and the bankers who produced record revenue last year for firms including Goldman Sachs are reaping the rewards.                                                                                                                                                                                                                                     , Goldman and JPMorgan Chase informed investment bankers and traders of their pay packages this week, part of an annual ritual that can leave workers elated — or deflated — as they learn how much their 2021 efforts were valued.                                                                                                                                                             , The compensation pool for Goldman's investment bankers jumped 40% to 50%, according to people with knowledge of the situation. At rival JPMorgan, the bonus pool for that category rose 30% to 40%, other people with knowledge said, confirming a Bloomberg report.                                                                                                                          , "I know bankers who are exceptionally happy, they generally did the best this year as opposed to traders," said David McCormack, head of finance recruitment firm DMC Partners. "This is the highest compensation many people have seen in the last decade."                                                                                                                                  , Pay is up everywhere you look on Wall Street, from first-year bankers to partners and top executives, after a two-year boom in mergers and markets activity sparked by the Federal Reserve's response to the coronavirus pandemic. Wage inflation was a key theme this past week as banks disclosed fourth-quarter results, with analysts fretting that rising expenses will eat into profits., The rise in bank's bonus pools tracks their results for 2021. For instance, at Goldman, investment banking revenue jumped 58% from the previous year to $14.9 billion on high levels of completed mergers and initial public offerings. JPMorgan said last week that its 2021 investment banking fees climbed 39% to $13.2 billion.                                                           , The rise in compensation pools doesn't tell the full story. Managers use the pools to dole out bonuses to individual employees, and their incentives are determined by how much they contributed to team results. Rainmakers who source and close billion-dollar deals are paid the most.                                                                                                     , Goldman partners in areas that did particularly well like technology and health-care investment banking made between $12 million and $15 million last year, McCormack said. Senior partners running divisions made even more, he said.                                                                                                                                                        , Top-performing managing directors, who are one level down from partners, brought in $5 million to $7 million, he said.                                                                                                                                                                                                                                                                        , And the Goldman figures don't include special one-time awards for partners which can amount to multimillion-dollar sweeteners, according to the people familiar with the situation. The bonuses were dubbed PPA, or Partnership Performance Awards, by the bank, according to a source.                                                                                                       , "We wanted to remind partners how valuable they are and express how exceptional this year was," one person said.                                                                                                                                                                                                                                                                              , At Goldman, the rise in banker pay mirrored the advance in overall compensation for the firm's 43,900 workers. Pay and benefits expenses jumped 33% to $17.7 billion, which amounts to $403,621 per person, compared with $329,000 in 2020.                                                                                                                                                   , At JPMorgan's corporate and investment bank, compensation costs rose 13% to $13.1 billion, or $193,882 for each of the division's 67,546 workers.                                                                                                                                                                                                                                             , "There's a lot more compensation for top bankers and traders and managers who I should say did an extraordinary job in the last couple years," JPMorgan CEO Jamie Dimon said last week in a conference call.  "We will be competitive in pay. If that squeezes margins a little bit for shareholders, so be it."                                                                              , Wage inflation reached all corners of the investment bank. Dimon himself earned a 10% raise to $34.5 million last year, the bank said Thursday in a filing.                                                                                                                                                                                                                                   , Pressure to retain workers amid fierce competition for talent even filtered down to recent college graduates. JPMorgan recently boosted base salaries for first-year investment banking analysts to $110,000, matching the rate that Goldman set last year, according to sources who confirmed a Financial News report.                                                                       , But for every banker who is celebrating a windfall, there are many others who are or will be deeply disappointed after learning their number. Michael Sloyer, a former Goldman trader who is now a leadership development coach, shared his own realizations about the intensity of banking culture.                                                                                          , "At times, the money became a proxy for my value as a person," said Sloyer, who spent 11 years climbing the ranks at Goldman, ultimately reaching managing director. "As the number grew larger over the years, the comparisons only grew to the people around me. It could feel like a never-ending treadmill."                                                                              , Read more: Wage inflation has arrived in a big way and Jamie Dimon says CEOs ‘shouldn’t be crybabies about it’                                                                                                                                                                                                                                                                                , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                        , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                        , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                              , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                              , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                            , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-states/stock-market </td>
   <td style="text-align:left;"> 2022-01-21 22:35:00 </td>
   <td style="text-align:left;"> US Stocks Waver, Netflix Disappoints </td>
   <td style="text-align:left;"> The Dow Jones was shifting between gains and losses after opening slightly higher, and the S&amp;P 500 and the Nasdaq remained into negative territory on Friday amid disappointing earnings results and as investors anticipate a tighter monetary policy. Netflix was the main drag falling 22% after the company's subscriber outlook missed estimates due to the rise in streaming competition. Focus now turns to the Fed monetary policy decision next week and further earnings reports from big tech companies which investors fear could disappoint. The Nasdaq is on track for its worst week since October 2020 and both the Dow and the S&amp;P 500 are likely to book a 3rd straight week of losses. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/baltic </td>
   <td style="text-align:left;"> 2022-01-21 22:25:00 </td>
   <td style="text-align:left;"> Baltic Exchange Dry Index Falls for 11th Day </td>
   <td style="text-align:left;"> The Baltic Exchange Dry Index fell 4% to 1,415 on Friday, its lowest since mid-February 2021, extending losses for the eleventh straight session, amid weaker seasonal demand across all vessel segments. The capesize index, which tracks iron ore and coal cargos of 150,000-tonnes, plunged 13.6% to 891, its lowest since June 2020; and the panamax index which tracks cargoes of about 60,000 to 70,000 tonnes of coal and grains, decreased 0.7%, to its lowest since mid-April 2021 at 2,010. Among smaller vessels, the supramax index shed 24 points to its lowest since end-February 2021 at 1,749. The Baltic Dry Index has lost nearly 19.8% in the third week of January, its second consecutive weekly decline. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/lithium </td>
   <td style="text-align:left;"> 2022-01-21 22:19:00 </td>
   <td style="text-align:left;"> Lithium Carbonate Extends Rally </td>
   <td style="text-align:left;"> Lithium carbonate prices in China rose to 348,500 yuan/tonne in the second half of January, amid high global demand and difficulty of securing supplies. Prices have surged over 25% this year from continuously increasing demand from lithium battery manufacturers, especially for electric vehicles. Global electric vehicle sales are estimated to have increased by 160% during 2021, while deliveries in China are expected to double in 2022 to over 5 million sales. Meanwhile, battery manufacturers race to secure long-term supply contracts due to mineral scarcity and environmental concerns with mining. On January 20th, the Serbian government revoked mining giant Rio Tinto’s exploration licenses following extensive protests of environmental concerns. The now-defunct project would have been worth USD 2.4 billion and was estimated to produce enough lithium for 1 million electric vehicle batteries. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/21/your-money/cable-streaming-bill.html </td>
   <td style="text-align:left;"> 2022-01-21 22:00:08 </td>
   <td style="text-align:left;"> How I Cut My Family’s Cable and Streaming Bill by $170 - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , your money adviser                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , After I realized we were paying more than $400 a month, I knew I had to do something. Here’s what I learned.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , By Ann Carrns                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , It was another fat cable bill that finally spurred me to act. For my New Year’s resolution, I would cut the cord and watch streaming services instead.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , And I’ve done it — or at least a modified version of it (more of a “fraying” of the cord, let’s say). Here’s what I did, and why. But note: Things are moving at lightning pace in the world of television and streaming services, so details may change at any time.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Over the last two years, hunkered down during the pandemic, my family had gradually added a host of new internet subscription services. “Ted Lasso,” for our soccer-loving teenagers (Apple TV+). “Picard,” for my “Star Trek”-fan husband (Paramount+.) And for me? The debut of the film version of “Hamilton” (Disney+). We also had Netflix, which we’ve used since it began renting DVDs by mail and appreciate now for series like “The Queen’s Gambit.”                                                                                                                                                                                                                                                                                              , We weren’t alone: As of last summer, viewers who streamed had increased their subscriptions to an average of 4.5, up from 3.9 in December 2020, according to research from J.D. Power, and the average monthly costs increased to $55 from $47.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , “It comes up in cash-flow conversations,” said Kenny Senour, a fee-only financial planner at Millennial Wealth Management near Denver.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , The catch is that each “plus” added to our streaming costs, atop our already hefty cable bill. Most came with free trials — but those eventually expire. Yet I couldn’t muster the will to do the necessary research to cut the cord. So many options! So much jargon to parse! What were a few extra dollars a month, when we weren’t doing much else anyway?                                                                                                                                                                                                                                                                                                                                                                                              , Then I received our December cable bill, which had grown to $382. A quick review of my credit card statements confirmed what I suspected: When I added the cost of our separate streaming subscriptions to the cable bill, we were easily paying more than $400 a month for on-screen entertainment. Ouch!                                                                                                                                                                                                                                                                                                                                                                                                                                                  , True, the amount reflected a cable bundle that included the base cost of reliable internet service, crucial for working at home. But it also included a telephone line we no longer used. (I had kept it as a backup, when my children were small. Why did I still have it?) And there were a bunch of channels we never watched.                                                                                                                                                                                                                                                                                                                                                                                                                           , My plan was to drop cable television and the dormant phone line and switch to a “cable replacement” streaming service, like YouTubeTV or Hulu + Live TV, that also includes access to broadcast television stations, as cable does, for news and live sports.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , I contacted my cable company via its chat option — often quicker than waiting to speak on the phone — to say I wanted to keep internet service but drop everything else. I was paying $75 a month before taxes and fees for the internet, but the rate was part of a package. Stand-alone internet would cost more than $100 a month. Still, that was a big savings, so I decided to do it.                                                                                                                                                                                                                                                                                                                                                                 , Note: Don’t attempt this when you are short of time. It took me several hours, when I added it all up, to figure out what to do.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , While I was sorting things out, I tested YouTube TV, recommended by friends. (I watched it via a Roku device, which lets you watch internet services on your television.) I liked that it offered access to local PBS stations, unlike some other cable-replacement options. But I found its menu a bit challenging to navigate. I knew I would eventually become familiar with the format, but I also knew others in my family would be less patient.                                                                                                                                                                                                                                                                                                      , Watching television shouldn’t be this hard.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , “It’s become quite complicated,” said Jim Willcox, senior electronics editor with Consumer Reports.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , I was about out of steam. So instead of testing other cable-replacement options, I returned for another go-round with the cable company. Maybe I had been too hasty.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , After I had submitted my initial cancellation notice, the cable company sent me an email offering more “flexibility” if I gave it another try. After another chat session, the company offered internet service and a leaner television option (no premium channels) for about $185 a month, including taxes and fees.                                                                                                                                                                                                                                                                                                                                                                                                                                      , The deal is good for two years and can be changed at any time. And we can always choose later to pull the plug entirely. That was a lot better than what I had been paying.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Next came deciding what streaming services to keep.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Mr. Willcox suggests making a list of the shows you and your family want to watch and then matching them with the appropriate streaming service. Set a limit on what you want to spend. “It’s a lot more work than it used to be,” he said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , To keep the total cost under a target of $250 a month (a savings of at least $150 from my current bill), I had $65 left.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , I prefer advertising-free viewing, so I’m planning on paying a bit more than I would for ad-supported streaming options. Even so, my savings should cover the cost of monthly subscriptions to Netflix (currently $13.99 for a standard plan), Paramount+ ($9.99 for premium) and Amazon Prime video ($8.99; if you pay for a full Prime membership, video is included). I learned that we can keep Disney+ bundled with two more services free — Hulu (shows include “Only Murders in the Building,” with Steve Martin) and ESPN+ — as part of a promotion from Verizon, our mobile phone company. The Hulu option in the deal has ads, but I’ll take them — for now. Finally, we can add HBO Max ($11.99) and watch acclaimed shows like “Station Eleven.”, (Our Apple TV+ subscription is free for six more months; we’ll re-evaluate it when the promotion expires.)                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Grand total for streaming and cable: $230.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , With the overall savings (about $170 a month), maybe we can even buy other things (hopefully, more books).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , Still, that’s a lot of television — and it’s probably unnecessary to pay for all of those subscriptions year round, Mr. Willcox said. You could instead pay for a month here and there because most streaming services currently allow customers to join and cancel at will. (Just remember to cancel.)                                                                                                                                                                                                                                                                                                                                                                                                                                                     , For instance, if you don’t care about watching a new show right away, he said, you can simply wait. When an entire season of a show that you want to watch becomes available, you can join the appropriate streaming service, watch it for a month, then cancel — and sign up again later if something else catches your fancy. (Some people even binge watch their selections during free trials.) It takes some planning but can save you money.                                                                                                                                                                                                                                                                                                          , Another option, if you don’t mind watching some ads: free streaming services, like IMDb TV, now part of Amazon, and the basic tier of NBCUniversal’s Peacock.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , You could also go old school and buy an antenna, available at most big box stores. That will give you access to local broadcast stations so you can cut out cable and rely solely on streaming services.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , Here are some questions and answers about managing cable and streaming bills:                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Try to subscribe to all of your streaming services on a single credit card. That makes it easier to find the monthly (or annual) charges without having to hunt through several statements.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , In the early days of streaming, it was easy to cut the cord and see huge savings. That’s getting harder as streaming services increase subscription fees to help pay for all that stellar content, Mr. Willcox said. You’ll need to look closely at a specific service’s offerings to see if you can get what you want at a lower price.                                                                                                                                                                                                                                                                                                                                                                                                                    , Free trials are still common but are getting shorter. Apple TV+, for instance, once offered a yearlong free trial with the purchase of an Apple device, but has shortened it to three months.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , One way to think about a reasonable cost of services is to consider streaming as part of your entertainment spending, which should take up no more than 5 to 10 percent of your overall budget, said Mr. Senour, the financial planner. (If you net $5,000 a month after taxes, the median household income, your entertainment spending, including streaming, should be no more than $500.)                                                                                                                                                                                                                                                                                                                                                                , The explosion of new services and intricate licensing deals has made it difficult to know where to find your preferred show. Mr. Willcox suggests trying Reelgood.com, which lets you search for any show to find where it’s available. Or you could try subscribing to a newsletter like The New York Times’s “Watching” to help you wade through the entertainment options.                                                                                                                                                                                                                                                                                                                                                                               , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/21/business/retirement-stocks-vanguard.html </td>
   <td style="text-align:left;"> 2022-01-21 22:00:08 </td>
   <td style="text-align:left;"> Stock Investing in Retirement for Those Able to Bear the Risk - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Strategies                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Stocks and bonds are core investments. Now, Vanguard is suggesting that retirees willing and able to bear the risk may want a stock target of 50 percent.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , By Jeff Sommer                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , The stock market can provide eye-popping returns but can also be counted on to produce big losses. High-quality bonds, on the other hand, typically generate modest returns but are better for income and relative stability.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , So buy stocks for the long run, but as you age and get closer to the moment when you will need to rely on your nest egg, shift gradually into bonds and hold less stock.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , These may seem to be truisms, and they are embedded in the design of target-date funds, the diversified stock-and-bond portfolios that received government approval to be the default offering in corporate retirement plans in 2007 and have quietly become central all-in-one pillars of investment for many Americans. While the ideas reflected in these funds may seem obvious, they are not settled doctrine in academic finance, and they certainly don’t hold true for all people all of the time.                                                                                                                                                                                                               , Still, with the demise of most traditional pensions — known as defined-benefit plans — and the limited, though crucial, capacity of Social Security to ensure a comfortable retirement, people need to invest for themselves. With the blessing of the U.S. government, target-date funds and trusts have become an enormously important way of doing so. Once you choose a fund, you can “set it and forget it.” The fund company does the rest for you.                                                                                                                                                                                                                                                                , About $3.1 trillion was invested in them through October, according to data from the Investment Company Institute, a trade group for the mutual fund industry, and Morningstar, a financial research company.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , In a shift that is just beginning to be offered to workplace retirement plans, Vanguard, which has dominated the target-date fund market, has begun to acknowledge the need for variations in its standard portfolios for retirees.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , It now says that some investors who have already entered retirement may be better off if they keep their stock holdings fairly high, retaining a 50 percent allocation to equities. The 50 percent stock retirement portfolio will be a new option available to companies with Vanguard target-date retirement funds in their plans. That is a big increase over the current allocation: just 30 percent stocks and 70 percent bonds.                                                                                                                                                                                                                                                                                    , “People will need to evaluate this at a household level,” Roger Aliaga-Diaz, chief economist for the Americas and head of portfolio construction at Vanguard, said in an interview. “This greater allocation to stocks would be for people with more willingness to take on more risk, who are more comfortable with an inherently more volatile portfolio and who are wealthy enough to have the ability to take on more risk without endangering their retirement.”                                                                                                                                                                                                                                                    , Like the target-date funds of other leading companies, including Fidelity, BlackRock, T. Rowe Price, and JPMorgan, Vanguard’s offerings have kept things simple for investors until now.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 , Look under the hood, though, and you’ll find that Vanguard’s target-date funds are actually a collection of low-cost, broad-based index funds, with holdings in a variety of domestic and international stocks and bonds. For large workplace plans, these investments are not mutual funds but, technically, collective index trusts, which are generally cheaper than mutual funds, with pricing negotiated with individual companies. (For example, the standard Vanguard Target Retirement 2030 Fund has an expense ratio of 0.14 percent, which Vanguard will lower to about 0.08 percent in February. That compares with 0.065 percent in expenses for the equivalent offering in The New York Times 401(k) plans.), Until now, you could disregard the strategies powering the funds. All you had to do was decide which target-date fund most closely matched your likely retirement date — they are categorized in five-year increments, ranging, at the moment, from 2015 to 2065, with the 2070 fund emerging shortly — and Vanguard would make adjustments for you gradually as you approached retirement. The Vanguard Target Retirement 2065 Fund, for example, contains more than 90 percent stock and less than 10 percent bonds.                                                                                                                                                                                                   , The funds attain a 50 percent stock allocation at the designated target date, say 2030, and for seven years, the allocation declines until it reaches 30 percent in the Vanguard Target Retirement Income Fund for retired investors. That’s the current setup, which will continue to be the default in workplace plans.                                                                                                                                                                                                                                                                                                                                                                                                , But this year, Vanguard is introducing a new fund, the Vanguard Target Retirement Income and Growth Trust. At the target date, a retiree’s investments would flow into that fund, which will never drop its equity proportion below 50 percent, Nathan Zahm, head of goal-based investing research at Vanguard, said in an interview. “This fund is right for some people, those who can handle more risk and can afford to do so,” he said. “But people will need to think carefully about it.”                                                                                                                                                                                                                         , The company’s research shows how the two different equity allocations would have affected a retiree with a portfolio of $1 million from 1990 to 2020, based on the performance of the markets tracked by the indexes represented in Vanguard’s current array of funds. The 50 percent stock fund would have had annualized returns of 7.3 percent versus 6.6 percent for the 30 percent stock fund. That amounts to $7,000 extra each year for the fund with more stock, which the retiree could have spent or salted away.                                                                                                                                                                                              , But the greater risks associated with stock investing were also apparent. The biggest loss in any 12-month period for the fund with more stock was 28 percent, compared with 17 percent for the traditional income fund. If those declines occurred in the first year of investing, the $1 million portfolio would have had a whopping loss of $280,000 compared with a $170,000 decline for the bond-heavy fund. Clearly, unless you are capable of withstanding the greater loss, you should not risk the 50 percent stock fund.                                                                                                                                                                                       , It’s easy to contemplate hefty stock investments when the market has risen for years. But if you need to stop working just as the stock market falls — which happened to many people in 2008, when the S&amp;P 500 dropped more than 38 percent — target-retirement funds will generate painful losses with either allocation.                                                                                                                                                                                                                                                                                                                                                                                               , That’s why some finance experts are skeptical about trusting such a big part of the nation’s retirement to target-date funds. Zvi Bodie, professor emeritus in finance at Boston University, and the author of numerous books on investing, said in an interview that target-date funds fail to perform a crucial task: ensuring that people who save their money will have a secure retirement.                                                                                                                                                                                                                                                                                                                         , “The risk of owning stock never goes away,” he said. “It’s an illusion to think it will.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , For a core investment, he recommends buying U.S. government inflation bonds, or I bonds, which are now paying an interest rate of more than 7 percent. And he favors purchasing lifetime insurance contracts, also known as annuities, which, he says, “are unpopular but will guarantee that you have enough to live on.”                                                                                                                                                                                                                                                                                                                                                                                               , Adding stock to a retiree’s portfolio may be fine if, for example, you have a pension that you can count on or have other sources of income. Otherwise, he said, “It’s not what I’d suggest.”                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            , I’ve been investing in target-date funds for years and appreciate their virtues of simplicity and automatic rebalancing.  But I’d have to think carefully before putting extra money into stocks. If market history tells us anything, it is that there will almost certainly be big shocks down the road.                                                                                                                                                                                                                                                                                                                                                                                                               , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/videos/world/2022/01/21/lavrov-presser-blinken-meeting-ukraine-sot-intl-vpx.cnn </td>
   <td style="text-align:left;"> 2022-01-21 21:55:33 </td>
   <td style="text-align:left;"> Russian FM after meeting Blinken: The West is in 'hysterics' over Ukraine - CNN Video </td>
   <td style="text-align:left;">  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/lifestyle/dhs-requires-non-us-travelers-fully-vaccinated </td>
   <td style="text-align:left;"> 2022-01-21 21:42:59 </td>
   <td style="text-align:left;"> DHS requires non-US travelers to be fully vaccinated </td>
   <td style="text-align:left;"> Check out what's clicking on FoxBusiness.com.
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , The Department of Homeland Security (DHS) said that beginning Saturday it will require non-U.S. individuals hoping to enter the U.S. via land ports of entry and ferry terminals at the U.S.-Mexico and U.S.-Canada borders to be fully vaccinated against COVID-19.                                                                                                                                                                                                                                                                                                                                     , The individuals will need to provide related proof of vaccination and the restrictions will apply to both those traveling for essential and nonessential reasons.                                                                                                                                                                                                                                                                                                                                                                                                                                        , CDC ADDS 22 MORE DESTINATIONS TO COVID-19 'HIGH RISK' TRAVEL LIST                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , The changes were first announced in October 2021 and were made in consultation with the Biden administration and several federal agencies, including the Centers for Disease Control and Prevention (CDC).                                                                                                                                                                                                                                                                                                                                                                                               , In a news release, the department noted that this action will "align public health measures that govern land travel with those that govern incoming international air travel."                                                                                                                                                                                                                                                                                                                                                                                                                           , "Starting on January 22, 2022, the Department of Homeland Security will require that non-U.S. individuals entering the United States via land ports of entry or ferry terminals along our northern and southern borders be fully vaccinated against COVID-19 and be prepared to show related proof of vaccination," Homeland Security Secretary Alejandro Mayorkas said in a statement. "These updated travel requirements reflect the Biden-Harris Administration’s commitment to protecting public health while safely facilitating the cross-border trade and travel that is critical to our economy.", The non-U.S. travelers must also present a Western Hemisphere Travel Initiative (WHTI)-compliant document, like a valid passport, Trusted Traveler Program card or Enhanced Tribal Card.                                                                                                                                                                                                                                                                                                                                                                                                                 , To reduce wait times, the DHS said travelers can take advantage of the CBP One mobile app and facial biometrics.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , CLICK HERE TO READ MORE ON FOX BUSINESS                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  , They should also be prepared to present any other relevant documents requested by a U.S. Customs and Border Protection (CBP) officer during a border inspection.                                                                                                                                                                                                                                                                                                                                                                                                                                         , The agency added that any non-U.S. individuals attempting to enter the U.S. irregularly – either illegally or without the proper documentation – will "continue to be expelled pursuant to CDC’s Title 42 public health order."                                                                                                                                                                                                                                                                                                                                                                          , COVID-19 testing is not required for entry via a land port of entry or ferry terminal.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , FOX Business' Ashley Webster speaks with Canaveral Port Authority CEO Captain John Murray regarding the CDC's warning to Americans looking to travel via cruise ship.                                                                                                                                                                                                                                                                                                                                                                                                                                    , Conversely, air travelers ages 2 and older – regardless of nationality or vaccination status – are required to show documentation of a negative viral test result taken within one day of the flight’s departure to the U.S. before boarding.                                                                                                                                                                                                                                                                                                                                                            , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              , Those who recently recovered from the virus may instead travel with documentation of recovery, like a positive COVID-19 viral test result on a sample taken no more than 90 days before the flight's departure from a foreign country and a letter from a licensed health care provider or a public health official stating they are cleared to travel.                                                                                                                                                                                                                                                  , Exemptions will be considered on an extremely limited basis.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , The CDC recommends that people do not travel internationally until they are fully vaccinated. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/canada/retail-sales </td>
   <td style="text-align:left;"> 2022-01-21 21:38:00 </td>
   <td style="text-align:left;"> Canada Retail Sales Rise Less than Anticipated </td>
   <td style="text-align:left;"> Retail sales in Canada likely fell 2.1 percent month-over-month in December of 2021, preliminary estimates showed. Considering November, retail sales increased 0.7 percent over a month earlier, easing from a downwardly revised 1.5 percent in October and missing preliminary estimates of a 1.2 percent increase. Sales rose in 6 out of 11 sub-sectors, with overall growth driven by increased retail in gasoline stations (4.9 percent), building material, garden equipment and supplies (3 percent), and food and beverage stores (1 percent). Across major Canadian provinces, gains took place Quebec (1.2 percent), Ontario (0.5 percent), and British Columbia (0.8 percent), despite intense flooding during November. On an annual basis, retail trade hiked 4.4 percent in November, easing from an upwardly revised 5.5 percent in October. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/heating-oil </td>
   <td style="text-align:left;"> 2022-01-21 21:23:41 </td>
   <td style="text-align:left;"> Heating Oil Futures Ease from 7-Year High </td>
   <td style="text-align:left;"> Heating oil futures moderated to $2.6 per gallon after touching an over seven-year high of $2.73 on January 19th amid a broad pullback in futures of crude and oil derivatives, as traders monitored changes in domestic inventories. Oil inventory stocks unexpectedly rose in the second week of the month, after being on a downward trend for seven weeks, while heating oil inventories increased for the first time in four weeks. Still, storage levels remained near their lowest since 2014 following a freezing start of the year in the US Northeast, which provided upward momentum. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/united-kingdom/government-bond-yield </td>
   <td style="text-align:left;"> 2022-01-21 21:18:21 </td>
   <td style="text-align:left;"> UK 10Y Bond Yield Eases from Near 3-Year High </td>
   <td style="text-align:left;"> The yield on the UK 10-year government bond fell back below 1.2%, as tensions between the US and Russia and a fall in equity markets boosted demand for safe-haven assets. Washington said it was prepared to impose significant sanctions on Moscow if it invades Ukraine, while Russia said there are currently no plans to launch an attack while making several demands to the West, including that Ukraine be stopped from joining Nato. The UK yield has recently touched a near three-year high of 1.3%, amid prospects of faster monetary policy tightening due to stubbornly high inflation. Data showed Britain's consumer prices rose 5.4% in December, the largest increase since March 1992. The CPI numbers, combined with stronger November activity data and better jobs data, pointed to a possibility of a 25bps rate hike by the Bank of England on February 3rd, which is expected to be followed by multiple rate rises this year. Elsewhere, the US Fed is also seen raising rates in March. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.foxbusiness.com/features/investing-in-blackrock-a-clear-conflict-of-interest-hurts-west-virginians-treasurer-says </td>
   <td style="text-align:left;"> 2022-01-21 21:01:16 </td>
   <td style="text-align:left;"> Investing in BlackRock 'a clear conflict of interest,' hurts West Virginians, treasurer says </td>
   <td style="text-align:left;"> West Virginia Treasurer pulls banking contracts from BlackRock over anti-energy concerns.                                                                                                                                                                                           , Investing in BlackRock would be "a clear conflict of interest" since the firm aims to cut the greenhouse gas emissions of its portfolio to net-zero, West Virginia Treasurer Riley Moore told Fox News.                                                                             , The West Virginia Board of Treasury Investments will no longer use BlackRock for banking transactions, Moore announced Monday. He said the decision was made since BlackRock "has urged companies to embrace ‘net zero’ investment strategies," which he said hurts West Virginians., "There's a clear conflict of interest here to hand over tax dollars generated from coal and gas to a financial institution that wants to destroy those very industries in which they're reaping dollars from," Moore told Fox News.                                                 , BlackRock, the world's largest asset manager with nearly $10 trillion under its management, announced in 2021 that it is "committed to supporting the goal of net zero greenhouse gas emissions by 2050 or sooner."                                                                 , WATCH NOW:                                                                                                                                                                                                                                                                          , West Virginia Treasurer pulls banking contracts from BlackRock over anti-energy concerns.                                                                                                                                                                                           , WEST VIRGINIA DUMPS BLACKROCK FUND OVER ANTI-ENERGY STANCE                                                                                                                                                                                                                          , "What does that mean? That means no fossil fuels," Moore told Fox News.                                                                                                                                                                                                             , "So why are we going to hand those dollars over to the same people that want to destroy our industries? That doesn't make sense," Moore continued. "We're not going to pay for our own destruction."                                                                                , In a Jan. 17 letter to investors, BlackRock CEO Larry Fink said the firm "does not pursue divestment from oil and gas companies as a policy."                                                                                                                                       , Coal and energy production are the lifelines of the Mountain State's economy, Charleston residents told Fox News.                                                                                                                                                                   , "All you have to do is go in your yard and go down a foot, you're going to find coal," one West Virginia resident, Anthony, told Fox News, "Coal is West Virginia's bread and butter."                                                                                              , A West Virginia woman told Fox News: "A lot of our stuff that we have here runs on coal."                                                                                                                                                                                           , Paul speaks with Fox News Originals.                                                                                                                                                                                                                                                , Another resident, Paul, said: "Coal is definitely important. It's almost cultural … It's hard to take that away."                                                                                                                                                                   , "There's not a lot of other job opportunities that supply that type of salary and living wage," he continued.                                                                                                                                                                       , CONSUMER WATCHDOG BASHES BLACKROCK FOR 'GOING WOKE' WHILE INVESTING IN CHINA                                                                                                                                                                                                        , Moore called West Virginia an "energy state," noting its coal mining and gas production.                                                                                                                                                                                            , "As BlackRock looks to push people out of investing in those types of industries, it hurts us," the treasurer said.                                                                                                                                                                 , "Your energy costs, your bills are going to increase if there is no coal and gas in this country, you're going to pay the price," Moore added.                                                                                                                                      , West Virginia Treasurer Riley Moore gives Fox News Originals a tour of the treasury vault.                                                                                                                                                                                          , The coal and oil industries provide great paying jobs and furnish significant tax revenue, Moore told Fox News. He said $1.5 billion annually flows through the BlackRock fund he's withdrawing from.                                                                               , He also criticized firm's investments in China, bemoaning how the world's most populated country is building dozens of coal-fired power plants. The BlackRock China Fund, which BlackRock uses to invest in Chinese holdings, is valued at around $1.5 billion.                     , "So coal is apparently OK in China, not OK in America, which I think is absolutely wrong and an opportunity where we certainly need to put America first," Moore said.                                                                                                              , GET FOX BUSINESS ON THE GO BY CLICKING HERE                                                                                                                                                                                                                                         , Anthony agreed: "Investing in China? No, we need to invest here."                                                                                                                                                                                                                   , Financial firms, including British insurer Prudential, lenders Citi and HSBC and BlackRock Real Assets are devising plans to speed the closure of Asia’s coal-fired power plants in order to lower the biggest source of carbon emissions, five people wit                          , Moore told Fox News: "We are certainly continuing to grow and diversify our economy. But part of that is cheap and abundant energy that we're going to be able to supply new manufacturers, new businesses here in the state of West Virginia."                                     , "We want to do business with companies that want to do business with us," Moore added.  </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/21/stocks-making-the-biggest-moves-premarket-schlumberger-netflix-csx-and-others.html </td>
   <td style="text-align:left;"> 2022-01-21 20:47:15 </td>
   <td style="text-align:left;"> Stocks making the biggest moves premarket: Schlumberger, Netflix, CSX and others </td>
   <td style="text-align:left;"> , In this article                                                                                                                                                                                                                                                                                                                                                                        , Check out the companies making headlines before the bell:                                                                                                                                                                                                                                                                                                                              , Schlumberger (SLB) – The oilfield services company's stock rose 1% in the premarket after it beat top and bottom-line estimates for the fourth quarter. Schlumberger earned an adjusted 41 cents per share, 2 cents above estimates, as higher oil prices spurred demand for drilling services.                                                                                        , Netflix (NFLX) – Netflix plunged 19.4% in premarket trading, after predicting slower subscriber growth for this quarter than analysts were anticipating. The streaming service cited growing competition among the factors hitting its growth numbers. Netflix did report a better-than-expected profit and revenue for its latest quarter.                                            , Peloton (PTON) – Peloton said it is reviewing its production levels as well as the size of its workforce in response to a CNBC report that it was temporarily halting production of bikes and treadmills to deal with waning demand. Peloton bounced back 6.1% in premarket action after plunging 24% Thursday.                                                                        , CSX (CSX) – CSX beat estimates by 1 cent with a quarterly profit of 42 cents per share, and the railroad operator's revenue also beat Street forecasts. CSX said sales grew across all of its business lines as customers sought to deal with supply chain challenges. However, the stock fell 1.4% in the premarket as the company noted a surge in expenses.                         , Intuitive Surgical (ISRG) – Intuitive Surgical reported adjusted quarterly earnings of $1.30 per share, 2 cents above estimates, with the surgical equipment maker's revenue topping estimates as well. However, the stock is being pressured after the company noted a decline in procedures using its Da Vinci surgical system. Intuitive Surgical slumped 6.4% in premarket trading., PPG Industries (PPG) – PPG is seeing its shares fall in premarket trading despite beating Wall Street forecasts on the top and bottom lines for its latest quarter. The paint and coatings maker is seeing demand take a hit from declining airplanes and automobiles production. The stock lost 2.9% in the premarket.                                                                , Intel (INTC) – Intel announced plans to invest $20 billion in new manufacturing facilities outside Columbus, Ohio. The plants will produce advanced semiconductors, as chipmakers accelerate efforts to meet growing demand.                                                                                                                                                           , Rio Tinto (RIO) – Rio Tinto shares lost 1.6% in premarket trading after Serbia revoked the mining company's lithium exploration licenses, citing environmental concerns. Rio had aimed to become one of the top producers of lithium, a key component in batteries.                                                                                                                    , Under Armour (UAA) – The athletic apparel maker's stock rose 1.4% in the premarket after Citi upgraded the stock to "buy" from "neutral," saying Under Armour is emerging from the pandemic in a very strong position in North America.                                                                                                                                                , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                                                                                 , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                                                                                 , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                                                                       , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                                                                       , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                                                                     , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/info:us </td>
   <td style="text-align:left;"> 2022-01-21 20:32:14 </td>
   <td style="text-align:left;"> IHS Markit Ltd earnings above expectations at 0.85 USD </td>
   <td style="text-align:left;"> IHS Markit Ltd (INFO) released earnings per share at 0.85 USD, compared to market expectations of 0.83 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/world-europe-60081853?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-21 20:31:12 </td>
   <td style="text-align:left;"> Serbia revokes Rio Tinto lithium mine permits following protests </td>
   <td style="text-align:left;"> Serbia has withdrawn the exploration licences of Anglo-Australian mining company Rio Tinto following weeks of protests over plans for a lithium mine.                                                                                                                                 , "All permits were annulled... we put an end to Rio Tinto in Serbia," Prime Minister Ana Brnabic said on Thursday.                                                                                                                                                                     , The decision comes just weeks ahead of Serbia's general election in April.                                                                                                                                                                                                            , Relations between Belgrade and Canberra have also soured recently over Australia's treatment and deportation of Serbian tennis star Novak Djokovic.                                                                                                                                   , Djokovic, the world's number one men's tennis player who was unable to compete in the Australian Open, has supported the protests against the controversial mine.                                                                                                                     , In December, he posted images on social media of demonstrators and green landscapes along with comments written in Serbian such as "clean air and water are the keys to health" and "nature is our mother".                                                                           , Thousands of demonstrators have been taking to the streets in recent months, blocking main roads in several cities, including the capital Belgrade and the country's second-largest city Novi Sad.                                                                                    , They say the development of a large mine near the town of Loznica in the western Jadar Valley could cause irreparable damage to the landscape and contaminate the region's water supplies.                                                                                            , Rio Tinto had previously said that any mining development in the country would meet both domestic and European Union environmental standards.                                                                                                                                         , Speaking at a news conference in Belgrade on Thursday, Ms Brnabic - Serbia's first woman and first openly gay prime minister - said the decision to abandon the $2.4bn (£1.8bn; A$3.3bn) Jadar lithium mine was made in response to requests from environmental groups.               , The project had been due to start production in 2027.                                                                                                                                                                                                                                 , Rio Tinto's shares tumbled in Australia following the news, and were down more than 4% after markets opened in London.                                                                                                                                                                , It is undoubtedly tempting to look for a link between Australia's treatment of Novak Djokovic and Serbia's cancellation of Rio Tinto's mining project.                                                                                                                                , After all, it does have headquarters in Melbourne as well as London. And Serbia's prime minister, Ana Brnabic, announced the demise of the much-trumpeted lithium extraction operation just days after her counterpart in Australia cheered the deportation of Serbia's sporting icon., The cancelled project is more likely a victim of Serbia's domestic politics, rather than a bizarre diplomatic tit-for-tat. Novak Djokovic is important to Serbia - but not as important as the $2.4bn which the mining giant had promised to invest.                                  , In fact, pulling the plug is a reaction to months of protests. The movement has surprised Serbia's authorities with its organisation, unity and broad support going well beyond the usual coalition of opposition activists.                                                          , The government does not want to go into April's elections against a backdrop of blocked roads and accusations about favouring foreign investors over local interests.                                                                                                                 , But the environmentalists say they will continue protesting until the authorities issue a permanent ban on lithium mining.                                                                                                                                                            , In December, local authorities in western Serbia scrapped a plan to allocate land for a lithium mine in the region.                                                                                                                                                                   , President Aleksandar Vucic had said that the opening of such a mine would require approval following an environmental study and a referendum.                                                                                                                                         , In a statement to Reuters news agency, the Australian government said it regretted Serbia's decision: "We note the strong economic benefits of the significant investment by Rio Tinto in Serbia," it said.                                                                           , Lithium is the main component of the batteries used in electric vehicles and demand for the element is increasing.                                                                                                                                                                    , The World Bank estimates that globally the production of lithium will need to increase by 500% by 2050.                                                                                                                                                                               , This video can not be played                                                                                                                                                                                                                                                          , Eating with My Ex is back with even more drama!                                                                                                                                                                                                                                       , What is it really like to live in Dubai?                                                                                                                                                                                                                                              , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnbc.com/2022/01/21/ecbs-lagarde-and-imfs-georgieva-discuss-the-global-economic-outlook.html </td>
   <td style="text-align:left;"> 2022-01-21 20:14:55 </td>
   <td style="text-align:left;"> Watch ECB's Lagarde and IMF chief Georgieva discuss the global economic outlook </td>
   <td style="text-align:left;"> , [The stream is slated to start at 7:30 a.m. ET. Please refresh the page if you do not see a player above at that time.]                                                                                                                                                                                                           , The Covid-19 pandemic sent the global economy into one of its worst recessions ever. And last year saw supply bottlenecks, surging inflation and new variants weigh further on the recovery.                                                                                                                                      , With that in mind, CNBC's Geoff Cutmore explores the global economic outlook for 2022 at the Davos Agenda with ECB President Christine Lagarde, Bank of Japan Governor Haruhiko Kuroda, IMF Managing Director Kristalina Georgieva, Brazilian Economy Minister Paulo Guedes and Indonesian Finance Minister Sri Mulyani Indrawati., Subscribe to CNBC on YouTube.                                                                                                                                                                                                                                                                                                     , Got a confidential news tip? We want to hear from you.                                                                                                                                                                                                                                                                            , Sign up for free newsletters and get more CNBC delivered to your inbox                                                                                                                                                                                                                                                            , Get this delivered to your inbox, and more info about our products and services.                                                                                                                                                                                                                                                  , © 2022 CNBC LLC. All Rights Reserved. A Division of NBCUniversal                                                                                                                                                                                                                                                                  , Data is a real-time snapshot *Data is delayed at least 15 minutes. Global Business and Financial News, Stock Quotes, and Market Data and Analysis.                                                                                                                                                                                , Data also provided by </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.cnn.com/2022/01/21/politics/kevin-mccarthy-speaker-gop-conference/index.html </td>
   <td style="text-align:left;"> 2022-01-21 20:07:43 </td>
   <td style="text-align:left;"> Kevin McCarthy's path to speakership enters final but treacherous leg - CNNPolitics </td>
   <td style="text-align:left;"> (CNN)Kevin McCarthy was done being nice. The House Republican leader cast off his typically sunny demeanor during a December 8 meeting of the GOP conference to deliver a stern warning to his most raucous members: Quit trying to hold your vote for speaker over my head.                                                                                                                                                                                                                                                                                                                 , "He said, 'If any of you come to me and tell me that you're not going to vote for me unless I do something, I'm going to do exactly the opposite, even if I agree with you,'" said Rep. Tom Cole of Oklahoma, who was there at the time. A second Republican member told CNN McCarthy punctuated his threat with, "I mean it."                                                                                                                                                                                                                                                                , Further driving home his point was an edgy warning that the House GOP steering committee -- which determines committee assignments -- will take into consideration those fomenting internal dissent and attacking their fellow Republicans.                                                                                                                                                                                                                                                                                                                                                   , McCarthy's tough talk has taken some by surprise. The eight-term California Republican built a reputation in House leadership not as an arm-twister or dictator but as a friendly backslapper increasingly tolerant of his party's most hardline members. Now, with less than a year before the 2022 elections and the expectation that Republicans could win back the House, McCarthy is feeling the heat and laying down the law.                                                                                                                                                           , It all goes to illustrate the narrow path McCarthy is walking as he strives to knit together the warring factions of the GOP in his quest to win back the majority, and with it, the coveted speaker's gavel -- a mission that has been years in the making. The 56-year-old is perhaps closer than ever to fulfilling his lifelong dream, armed with a massive war chest, a favorable political environment and valuable lessons from his previous missteps. But the final leg of McCarthy's journey to the pinnacle of power could prove to be the most treacherous.                        , He must balance the desires of a populist and emboldened right-flank with the needs of moderate and swing-district Republicans to build a majority coalition -- an increasingly tough task, as exemplified by the recent retirement announcement of centrist Rep. John Katko of New York. He must ensure Republican infighting doesn't distract from a struggling Biden presidency. And he must parry with the House select committee investigating the January 6 attack, which just last week requested to speak with McCarthy about his knowledge. (McCarthy quickly and publicly refused.) , Hanging over all of McCarthy's moves is former President Donald Trump, the undisputed leader of the Republican Party to whom much of the House conference remains fiercely devoted and whose opinions of people can turn on a dime. And while no one has said they would challenge McCarthy for speaker -- and few in the conference believe anyone could pose a serious threat -- there is no shortage of ambitious politicians waiting in the wings should McCarthy stumble.                                                                                                                , So McCarthy is getting serious, starting, for anyone who had previously missed it, with that pre-Christmas meeting.                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , "He shifted from friendly mode to 'stop f***ing around and hurting the conference' mode," said the second GOP House member.                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , CNN spoke with more than two dozen Republicans, including current and former House members, Capitol Hill aides and political figures from California. From those conversations, a picture emerges of McCarthy as a hard-working political animal, dedicated to the members he oversees but sometimes struggling to lead a vocal right wing that has grown increasingly extreme.                                                                                                                                                                                                               , The shift in the balance of power within the House GOP conference -- from institutionalists like John Boehner to conservative rabble-rousers like Jim Jordan -- is reflected in McCarthy's own evolution from young establishment Republican to dedicated Trump ally.                                                                                                                                                                                                                                                                                                                         , What has remained consistent is McCarthy's willingness to be what House Republicans want him to be -- one of his greatest strengths, yet a trait that could also prove to be a weakness threatening his ascent to the speaker's podium.                                                                                                                                                                                                                                                                                                                                                       ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , The House conference McCarthy built                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , McCarthy has been preparing for this moment for quite some time. Even as minority leader in the California State Assembly back in the early 2000s, the Bakersfield native was known for his popularity with colleagues.                                                                                                                                                                                                                                                                                                                                                                       , "He spent the evenings in Sacramento socializing with his members," said Rob Stutzman, a Republican political strategist who was a top aide to then-Gov. Arnold Schwarzenegger.                                                                                                                                                                                                                                                                                                                                                                                                               , "Nobody didn't like Kevin," said Jim Brulte, the former Republican leader in the state senate.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , But McCarthy was an ambitious strategist, too, and it showed after he was elected to Congress and teamed up with Reps. Eric Cantor of Virginia, then the chief majority whip, and Paul Ryan of Wisconsin, the ranking GOP member on the Budget Committee. McCarthy's role in the group -- the "Young Guns," as people started calling them -- was to focus on recruiting candidates and expanding the map of winnable seats. He was tireless even when his peers were feeling down, as friends recall it.                                                                                     , Stutzman remembers running into McCarthy in an airport lounge in Denver not long after Barack Obama was first elected to the White House and the Republican Party was at its lowest point in decades.                                                                                                                                                                                                                                                                                                                                                                                         , "He's got folder after folder of districts that he thinks can be pickups, and he's already out looking for candidates to run," Stutzman said.                                                                                                                                                                                                                                                                                                                                                                                                                                                 , It was in this strategic role that McCarthy emerged as an early champion of a novel idea for regular Republicans -- co-opting the burgeoning tea party movement and bringing them under the GOP tent. He recognized the movement's political power and how its followers' supposed commitment to reining in government spending dovetailed with the vision he and the Young Guns had for the GOP.                                                                                                                                                                                             , "He brought in that energy, he brought in that creativity, he brought in that willingness to say, 'Hey, let's start something,'" Cantor said.                                                                                                                                                                                                                                                                                                                                                                                                                                                 , It worked, at least in terms of statistical analysis. The strategy has helped bring McCarthy and his Republicans just a handful of seats shy of the majority, in a conference that he can legitimately claim to have built himself. Nearly 85% of sitting House Republicans came into Congress after McCarthy, and many of those were recruited to run by him. He has been a dogged fundraiser for members across the party. That's generated a great deal of personal loyalty to McCarthy among the rank-and-file.                                                                           , "He'll know your dog's name, your kids name, their birthday," Cole said. "His attention to detail of building a personal relationship is really quite exceptional."                                                                                                                                                                                                                                                                                                                                                                                                                           , Allies praise him as a consensus-builder with a keen awareness for where the team wants to go.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                , "He's very congenial and tries to take in everybody's opinions and ideas to come to consensus, and I think that's good leadership," said Rep. Vicky Hartzler of Missouri.                                                                                                                                                                                                                                                                                                                                                                                                                     , "I'd take a bullet for the guy," said Rep. Markwayne Mullin of Oklahoma.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , Rep. Dave Joyce, a moderate Ohio Republican, said McCarthy made for a "sh*tty" whip when he served in the House majority because he was too "nice" to always play the role of enforcer.                                                                                                                                                                                                                                                                                                                                                                                                       , "I think he's much better at where he's at now, being able to be Big Picture, get people to consensus," Joyce said. "He does a tremendous job of bringing everybody to the table."                                                                                                                                                                                                                                                                                                                                                                                                            , But to critics, McCarthy seems more like a weathervane, shifting with his most vocal members and operating without a core philosophy.                                                                                                                                                                                                                                                                                                                                                                                                                                                         , One example that critics point to is how McCarthy -- once a champion for Silicon Valley -- has made battling major tech firms a top priority if Republicans win the House, echoing a prominent rallying cry on the right.                                                                                                                                                                                                                                                                                                                                                                     , Mark Bednar, a spokesman for McCarthy, told CNN the leader hasn't changed but that Big Tech firms need real accountability for "deplatforming conservatives and censoring ideas the left and media didn't agree with."                                                                                                                                                                                                                                                                                                                                                                        , A second example is how McCarthy went from condemning Trump for being responsible for the January 6 riot to cozying up with the former President weeks later.                                                                                                                                                                                                                                                                                                                                                                                                                                 , And in another sign of his evolving attitudes, McCarthy once praised Rep. Adam Kinzinger of Illinois as the future of the party. But after Kinzinger voted to impeach Trump and agreed to serve on the select committee investigating the Capitol riot, McCarthy now derides the Illinois lawmaker as a "Pelosi Republican."                                                                                                                                                                                                                                                                  , "The inmates are running the asylum now, and he just constantly looks scared," said one former House Republican leadership aide, echoing the views of multiple former top aides familiar with the dynamics of the GOP conference.                                                                                                                                                                                                                                                                                                                                                             , The tea party element McCarthy coopted has now evolved into a powerful and contrary faction within his conference. And that is partly what brings the would-be speaker to his current set of challenges.                                                                                                                                                                                                                                                                                                                                                                                      ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Hurdles on the track to becoming speaker                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , As House Republicans have become more conservative, more populist and more committed to Trump's vision for the party, McCarthy's leadership has reflected the shifting priorities of the conference.                                                                                                                                                                                                                                                                                                                                                                                          , Frequently, that has meant acceding to the influence of the Freedom Caucus, the far-right faction of around 44 pro-Trump Republicans that includes Reps. Paul Gosar of Arizona, Lauren Boebert of Colorado and Marjorie Taylor Greene of Georgia.                                                                                                                                                                                                                                                                                                                                             , As they have done for years, the Freedom Caucus' members stir up confrontation with outrageous rhetoric designed more for driving engagement online and in cable news than for any legislative purpose. But their loud megaphones within conservative media and their support, both implicit and explicit, from Trump give them a significant sway.                                                                                                                                                                                                                                           , Despite countless controversies with the group's most extreme members using violent or bigoted language, frequently toward their own colleagues, McCarthy has largely resisted calls from both inside and outside the conference to exert discipline on Freedom Caucus members.                                                                                                                                                                                                                                                                                                               , "I think he's been careful to court the right of his conference," said Charlie Dent, a former Republican congressman from Pennsylvania. "And part of the reason he's not gone after the Taylor Greenes and the Boeberts and the Gosars is because he's concerned about his flank."                                                                                                                                                                                                                                                                                                            , People familiar with the dynamics of the House GOP conference say McCarthy derives much of his own power from staying in the favor of the Freedom Caucus and its founder and spiritual leader, Jim Jordan.                                                                                                                                                                                                                                                                                                                                                                                    , Jordan unsuccessfully challenged McCarthy in 2018 for minority leader. Instead of ex-communicating Jordan into the political wilderness, where McCarthy would have less control over him, McCarthy made a strategic decision to push the Ohio Republican for a coveted top spot on the House Oversight and Reform Committee.                                                                                                                                                                                                                                                                  , "When picking Jim for Oversight, I thought he was crazy. I told him that," Joyce said. "But he said, 'Bring people in.' "                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , When asked whether he thought the risky move paid off for McCarthy, Joyce didn't hesitate: "Oh yes. Jim has been a tremendous team player."                                                                                                                                                                                                                                                                                                                                                                                                                                                   , But maintaining support across the conference also requires McCarthy to placate the smaller and less vocal wing of moderates and institutionalists, who have sometimes privately expressed frustration with McCarthy's deference to the party's hardliners and warned that trying to please too many different people can backfire.                                                                                                                                                                                                                                                           , The balancing act has put him in difficult positions, leading him in May to withdraw his support from the anti-Trump Rep. Liz Cheney as conference chairwoman just months after reasserting his confidence in her. Ousting the Wyoming Republican pleased the Freedom Caucus, but his decision to back as her successor Rep. Elise Stefanik of New York, once an ideological moderate, typified why many on the right remain suspicious of McCarthy.                                                                                                                                          , "He gets beat up from time to time. In fact, he gets beat up a lot," said Rep. Randy Weber of Texas, a member of the Freedom Caucus. "There's some concessions you have to make up here, that's just the nature of the beast. It's not easy."                                                                                                                                                                                                                                                                                                                                                 , But others in the conference have instead sought to test the boundaries of what McCarthy will accept from his members, leaving him with the difficult task of keeping his troops in line while staying in their good graces.                                                                                                                                                                                                                                                                                                                                                                  , Greene, for instance, spent much of her first year in office making incendiary statements and engaging in conspiracy theories, not stopping even after the Democratic majority voted to strip her of her committee assignments in February. McCarthy has condemned Greene's most outrageous comments, including her comparison of the House's masking rules to Nazi Germany. But he also objected to Greene's removal from committees and has promised to restore her assignments if Republicans win the majority.                                                                            , Weber recalled how he was in the car with McCarthy when the GOP leader got into a heated phone call with House Majority Leader Steny Hoyer over Greene's committee assignments, and threatened to return the fire on Democrats if he's in charge of the House next Congress.                                                                                                                                                                                                                                                                                                                  , "I said to (McCarthy), 'I've never heard you cuss before. I'm disappointed. What took you so long?' " Weber said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , But despite McCarthy's defense of Greene, in November, she joined Rep. Matt Gaetz's podcast to say that McCarthy did not have "the full support to be speaker" and started laying out a list of demands in exchange for her vote for speaker.                                                                                                                                                                                                                                                                                                                                                 , Her statement echoed sentiments from Freedom Caucus members in 2015 who helped sink McCarthy's previous bid for speaker following Boehner's resignation. Despite being next in line, McCarthy quickly discovered he did not have enough support from the conference's most conservative members. He withdrew at the last minute, paving the way for Ryan to ascend to the speakership. But the episode also taught McCarthy a valuable lesson.                                                                                                                                                , The day after Greene's Thanksgiving appearance on Gaetz's show last fall, McCarthy called up the Georgia congresswoman in part to smooth things over but also to rein her in.                                                                                                                                                                                                                                                                                                                                                                                                                 , Yet just as quickly as McCarthy put one fire out, another emerged. Days later, Greene and Rep. Nancy Mace of South Carolina engaged in a high-profile and personal spat over social media. This time, McCarthy hauled each congresswoman in his office for separate meetings to tell them each to "stop it."                                                                                                                                                                                                                                                                                  , The talking-to didn't seem to work. After her meeting, Greene told CNN that both she and Trump may back a primary challenge to Mace in 2022. Following her own meeting with McCarthy, Mace had this to say when asked about Greene's threat: "All I can say about Marjorie Taylor Greene is bless her f***ing heart."                                                                                                                                                                                                                                                                         ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , Balancing hardliners and 'majority makers'                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    , As the midterms approach, McCarthy will face pressure not just to curb the infighting but to cave to the right wing's demands for a harder line should Republicans win a majority. Greene, Gaetz and their cohorts in the conference have been pushing for a GOP majority to commit to investigating the 2020 election and launch impeaching proceedings into Biden. There are also persistent calls from that wing to boot anti-Trump Republicans Cheney and Kinzinger from the conference.                                                                                                  , McCarthy was able to quell those calls for now, asking the group to hold off on their effort so the GOP doesn't distract from its messaging around the one-year anniversary of Biden's inauguration. But the issue is almost certain to bubble back up.                                                                                                                                                                                                                                                                                                                                       , In the meantime, McCarthy risks being outflanked on the issue. Rep. Jim Banks of Indiana, the head of the conservative Republican Study Committee who is said to have future leadership ambitions, recently came out in support of removing Cheney and Kinzinger from the conference.                                                                                                                                                                                                                                                                                                         , Appeasing his right wing could run hard up against McCarthy's other mission for 2022: keeping the "majority makers" in swing districts happy and putting moderate incumbents and candidates in position to win in districts where Trump is not popular.                                                                                                                                                                                                                                                                                                                                       , Katko's retirement typifies the struggle McCarthy faces. Hailing from a Democratic-leaning district around Syracuse, Katko had defied expectations for several elections. But his vote to impeach Trump last year, plus his work to find a compromise on investigating January 6 and his vote for the White House's infrastructure bill, drew the ire of Trump and the conference's right wing.                                                                                                                                                                                               , McCarthy declined to heed conservative calls to boot Katko from his top committee spot, but he didn't vocally defend Katko, either. McCarthy also opposed the bipartisan commission on January 6 even though he had deputized Katko to strike a deal on the proposal, which surprised and upset the New York Republican, according to sources familiar with his thinking.                                                                                                                                                                                                                     ,                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               , "He didn't have a whole lot of choices there," said Mullin, recalling McCarthy's handling of the situation. "I don't know if there is such a thing as a win or a right solution in that circumstance. And he handled it the best way that the conference needed."                                                                                                                                                                                                                                                                                                                             , The encroachment of the January 6 committee on McCarthy raises even more potential problems for him on his journey to be speaker. Even if the GOP leader is not subpoenaed, any details in the final report from the committee on McCarthy's conversations with Trump could be damaging and distracting as the party tries to make its case against Biden in the midterm elections.                                                                                                                                                                                                           , But McCarthy's swift dismissal of the committee's interest reveals how he sees no advantages in cooperating. In fact, a standoff with the committee could strengthen McCarthy's position within the conference and, just as importantly, with Trump.                                                                                                                                                                                                                                                                                                                                          , "I think if you remember what Kevin's job is, it's to lead the members in the conference," said Cantor. "There are an overwhelming majority of the members of the conference who have constituents that are very loyal and look to Donald Trump as a leader."                                                                                                                                                                                                                                                                                                                                 , "Kevin is someone who leads by understanding the needs of his members," Cantor added. "The key to being a successful leader is understanding the fabric of the conference."                                                                                                                                                                                                                                                                                                                                                                                                                   , </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/eu-natural-gas </td>
   <td style="text-align:left;"> 2022-01-21 20:06:55 </td>
   <td style="text-align:left;"> TTF Gas is up by 5.05% </td>
   <td style="text-align:left;"> Natural Gas EU Dutch TTF increased 5.05% to 79 EUR </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/ireland/producer-prices-change </td>
   <td style="text-align:left;"> 2022-01-21 20:02:21 </td>
   <td style="text-align:left;"> Irish Wholesale Prices Rise the Most in 4 Years </td>
   <td style="text-align:left;"> Ireland’s wholesale prices rose by 4.5 percent from a year earlier in December of 2021, accelerating from a 0.2 percent increase in the previous month. It was the second increase in wholesale prices since April of 2019 and the highest since May of 2017, as prices rebounded for export sales (4.3 percent vs -0.1 percent in November) and rose faster for domestic sales (5.9 percent vs 5 percent). On a monthly basis, wholesale prices remained unchanged for the second consecutive month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/slb:us </td>
   <td style="text-align:left;"> 2022-01-21 20:00:01 </td>
   <td style="text-align:left;"> Schlumberger earnings above expectations at 0.41 USD </td>
   <td style="text-align:left;"> Schlumberger (SLB) released earnings per share at 0.41 USD, compared to market expectations of 0.39 USD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/uk-natural-gas </td>
   <td style="text-align:left;"> 2022-01-21 19:56:06 </td>
   <td style="text-align:left;"> UK Gas is up by 5.23% </td>
   <td style="text-align:left;"> Natural Gas UK GBP increased 5.23% to 188.5 GBp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.bbc.co.uk/news/business-60066436?at_medium=RSS&amp;at_campaign=KARANGA </td>
   <td style="text-align:left;"> 2022-01-21 19:07:03 </td>
   <td style="text-align:left;"> Ex-Credit Suisse chief also broke Covid rules going to Euros final </td>
   <td style="text-align:left;"> Banker António Horta-Osório, who quit as Credit Suisse boss for breaking Covid isolation rules, also went to the Euros football final, it has emerged.                                                                                , He resigned last weekend, with reports saying he had lost the confidence of other directors for going to the Wimbledon tennis finals last summer.                                                                                     , But the former Lloyds Bank boss also attended the football at Wembley on the same day, sources have confirmed.                                                                                                                        , News of the Euros visit was first reported by the Financial Times.                                                                                                                                                                    , The Swiss bank had organised corporate hospitality at both events, but Mr Horta-Osório took family members to both events after other guests were unable to use the tickets, the Financial Times said.                                , The Portuguese executive attended Wimbledon and the final of the European Championship in July at a time when the UK's Covid-19 restrictions required him to be in quarantine.                                                        , Mr Horta-Osório also breached Swiss Covid restrictions when, according to Reuters, he flew into the country on 28 November but left on 1 December. Swiss rules meant he should have quarantined for 10 days upon his arrival.         , He joined Credit Suisse in April last year following a series of scandals at the bank, including allegations of spying on employees, and had vowed to change the culture at the firm.                                                 , In his resignation statement earlier this week, Mr Horta-Osório said: "I regret that a number of my personal actions have led to difficulties for the bank and compromised my ability to represent the bank internally and externally., "I therefore believe that my resignation is in the interest of the bank and its stakeholders at this crucial time," he added.                                                                                                         , The England-Italy Wembley final was later declared a Covid superspreader event by public health officials, with more than 2,000 people said to have attended while "likely to be infectious".                                         , Eating with My Ex is back with even more drama!                                                                                                                                                                                       , What is it really like to live in Dubai?                                                                                                                                                                                              , © 2022 BBC. The BBC is not responsible for the content of external sites. Read about our approach to external linking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/macau/inflation-cpi </td>
   <td style="text-align:left;"> 2022-01-21 19:03:16 </td>
   <td style="text-align:left;"> Macau Annual Inflation Eases to 1% in December </td>
   <td style="text-align:left;"> Consumer prices in Macau rose by 1 percent year-on-year in December of 2021, slowing from a 1.21 percent increase in the previous month as prices eased for food and non-alcoholic beverages (1.01 percent vs 1.2 percent in November) due to retreating prices of pork; transport (6.85 percent vs 8.59 percent) and miscellaneous goods and services (0.7 percent vs 0.88 percent). Also, prices declined further for housing and utilities (-0.46 percent vs -0.22 percent) underpinned by lower rentals for dwellings; and clothing and footwear (-1.41 percent vs -1.35 percent). Meanwhile, inflation remained steady for education (at 1.4 percent) whereas accelerated for health (1.34 percent vs 1.19 percent); and household furnishings and services (7.78 percent vs 6.67 percent). On a monthly basis, consumer prices edged up 0.01 percent, slowing from a 0.21 percent rise in November. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/belgium/consumer-confidence </td>
   <td style="text-align:left;"> 2022-01-21 18:46:19 </td>
   <td style="text-align:left;"> Belgium Consumer Morale Rebounds in January </td>
   <td style="text-align:left;"> The consumer confidence indicator in Belgium edged higher to -2 in January of 2022 from -4 in the previous month. Remaining above the long-term average, it was the first increase in the headline index since September of 2021, as Belgian consumers appeared more optimistic about their economic situation in the next twelve months, while fears of increased unemployment have waned. Contrarily, expectations on the personal front have deteriorated in regard to both households’ financial situation and households’ savings intentions. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/poland/producer-prices-change </td>
   <td style="text-align:left;"> 2022-01-21 18:37:43 </td>
   <td style="text-align:left;"> Polish Producer Inflation Close to 26-Year High </td>
   <td style="text-align:left;"> The producer price inflation in Poland jumped to 14.2 percent year-on-year in December of 2021, quickening from an upwardly revised 13.6 percent in the previous month and faster than market expectations of 13.5 percent. It was the steepest increase in producer prices since April of 1996, as costs increased at a faster pace in electricity, gas, steam &amp; air conditioning supply (16.2 percent vs 10.4 percent). Meanwhile, inflation remained steady for manufacturing (at 13.7 percent) whereas eased for mining and quarrying (22.5 percent vs 26.1 percent); and water supply, sewerage, waste management &amp; remediation activities (4 percent vs 4.3 percent). On a monthly basis, producer prices inched up 0.8 percent, accelerating from an upwardly revised 1.4 percent rise in November. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/india/stock-market </td>
   <td style="text-align:left;"> 2022-01-21 18:30:00 </td>
   <td style="text-align:left;"> BSE Sensex Falls to 3-Week Low, Loses 3.6 % in a Week </td>
   <td style="text-align:left;"> The BSE Sensex ended 427.44 points or 0.72% lower to close at 59,037.18 on Friday, its weakest value since the beginning of 2022 amid continued selling pressure from foreign institutional investors due to persistent inflationary worries and mixed earnings results. Banks and technology were the main draggers. 22 out of 30 stocks ended in red. Among the individual stocks, Asian Paints slumped 1% as its Q3 net profit declined 18% year-on-year (YoY), missing estimates whereas consumer-giant Hindustan Unilever jumped 2.68% and Housing Development Finance Corporation surged 1.02% amid their strong December quarter earnings. Bajaj Financial Service (-5.37%), Tech Mahindra (-4.44%), Tata Steel (-3.18 %), Bharti Airtel (-2.83%), IndusInd Bank (-2.77%) and Larsen and Toubro (-2.38%) were the top SENSEX losers. On the week, the BSE booked an almost 3.6% loss. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/slovenia/consumer-confidence </td>
   <td style="text-align:left;"> 2022-01-21 18:12:39 </td>
   <td style="text-align:left;"> Slovenia Consumer Confidence Remains Unchanged in January </td>
   <td style="text-align:left;"> The consumer confidence in Slovenia remained steady at -24 in January of 2022, the same as in the previous month. Expectations over the next 12 months improved for the general economic situation in the country (-33 vs -40 in December) whereas sentiment deteriorated for savings (-8 vs -6); financial situation of the household (-21 vs -17); and major purchases (-31 vs -28). Also, consumers were slightly more downbeat about unemployment (63 vs 62). Last year, the indicator was at a higher -19. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/rubber </td>
   <td style="text-align:left;"> 2022-01-21 18:06:00 </td>
   <td style="text-align:left;"> Rubber Futures Fall from 29-Week High </td>
   <td style="text-align:left;"> Osaka rubber futures traded around 230 yen per kg level, after hitting a 29-week high of 238.5 yen on January 19th amid weaker oil prices and concerns over slow automobile output due to the spreading pandemic. Toyota Motor Corp is slowing production at as many as 11 plants in Japan because of rising COVID-19 infections among its workers and those at parts suppliers. There are also fears that supply may get tight as coronavirus curbs by rubber-producing countries in Southeast Asia would cause labor shortages at rubber farms. Still, imports from China are expected to pick ahead of the week-long holiday for the Lunar New Year, which begins at the end of the month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/morocco/inflation-cpi </td>
   <td style="text-align:left;"> 2022-01-21 18:03:00 </td>
   <td style="text-align:left;"> Morocco December Inflation Rate Highest since 2009 </td>
   <td style="text-align:left;"> The annual inflation in Morocco quickened for the fourth straight month to 3.2% in December of 2021, up from 2.6% in the previous month. That was the highest rate since February of 2009, mainly driven by prices of transport (6.2% vs 7.1% in November); food &amp; non-alcoholic beverages (4.5% vs 2.9%); miscellaneous goods &amp; services (4.3% vs 4.2%) and clothing &amp; footwear (3% vs 3.1%). On a monthly basis, consumer prices were up 0.1%, following a 0.2% increase in the previous month. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/italy/stock-market </td>
   <td style="text-align:left;"> 2022-01-21 18:00:58 </td>
   <td style="text-align:left;"> Italian Shares at 3-Week Lows </td>
   <td style="text-align:left;"> The FTSE MIB Index fell 1.3% to hover around the 27,200 level on Friday, the lowest in over three weeks, tracking a sell-off in global equities around jitters of tighter monetary policy by the Federal Reserve. Tech shares lost 2.5%, led by STMicroelectronics (-3%), while consumer discretionary goods fell 2.2% led by Ferrari (-2.5%) and Moncler (-0.5%). Meanwhile, Stellantis shares dropped 3% after the Chinese group Dongfeng Motor sold-off its 1.2% stake of the car manufacturer at a price of 18.3 euros per share, in line with current prices. Also, Tenaris dropped 2.5%, in line with other suppliers of steel pipes worldwide, after having gained more than 60% this year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/21/business/hong-kong-covid-supply-chain.html </td>
   <td style="text-align:left;"> 2022-01-21 18:00:32 </td>
   <td style="text-align:left;"> Zero-Covid Policy Shakes Hong Kong’s Economy and Its ‘Soul’ - The New York Times </td>
   <td style="text-align:left;"> , Businesses that held on through several outbreaks are now trembling as the highflying metropolitan hub struggles with supply chain issues and a relentless approach to the pandemic.                                                                                                                                                                                                   , Shuttered restaurants in Hong Kong, where several rounds of bar closures have dimmed the city’s vibrant nightlife.Credit...Billy H.C. Kwok for The New York Times                                                                                                                                                                                                                      , Supported by                                                                                                                                                                                                                                                                                                                                                                           , By Alexandra Stevenson                                                                                                                                                                                                                                                                                                                                                                 , HONG KONG — Perry Lam felt confident that his business had weathered the worst of the pandemic. Several rounds of bar closures in Hong Kong had dimmed the city’s vibrant nightlife, threatening to destroy his brewery. But things seemed better late last year.                                                                                                                      , After the government’s relentless effort to stamp out the virus, there were no local infections, bars began ordering kegs of his lager again and money was coming in. “You saw the silver lining,” said Mr. Lam, 34.                                                                                                                                                                   , That changed this month when Omicron started spreading, and officials returned to the trusted zero-Covid playbook that Hong Kong shares with mainland China. Restaurants were forced to shut down by 6 p.m. Small animals were culled. Flights from eight countries were suspended. Imports came to a standstill.                                                                      , Hong Kong is chasing the same dogged virus strategy as China, hoping this will strengthen ties to Beijing and allow it to declare victory over Covid-19. But in the process, a place once known as “Asia’s World City” has cut itself off from the outside world, crushing an economy reliant on international trade at a time when the global supply chain is already deeply strained., Now, local businesses that held on through several outbreaks are trembling as their highflying metropolitan hub transforms into what feels more like another isolated Chinese city.                                                                                                                                                                                                    , Hong Kong has reported around 300 cases of Omicron, most detected from overseas visitors during their quarantine. In recent days, however, local infections have jumped and emerged from unexpected origins, putting health officials on edge. In all, it has recorded 13,096 virus cases and 213 deaths since the start of the pandemic.                                              , These low numbers have been too much for Beijing’s zero-tolerance line, a seeming prerequisite for Hong Kong to reopen its border with China — a top priority for local officials who are under pressure to make the former British colony more like the mainland.                                                                                                                     , The fallout for local business has been staggering. Economists at Wall Street banks have lowered their estimates of the city’s economic growth for the year. Fitch, the ratings agency, warned that the ban on foreign travel would severely threaten Hong Kong’s economic future.                                                                                                     , In the days after the city announced its latest virus measures, several small businesses, including a rotisserie chicken chain, a popular wine bar, a craft beer shop and a gastro pub, said that they would close. Mr. Lam said he is determined that H.K. Lovecraft, his brewery, is not next.                                                                                       , “I’ve tried to hold out as long as possible,” he said, “but we are losing money.”                                                                                                                                                                                                                                                                                                      , Just a few years ago when he was studying to become a brewmaster in Germany, Mr. Lam had much bigger dreams: “I wanted to have something that belongs to Hong Kong, that is locally made,” he said.                                                                                                                                                                                    , He returned to the city and with his own money built a brewery with special equipment shipped from Germany. If he had known what was to come, he might have waited, he said. “It seems like it’s not getting any better and there have been times when I have been pondering how we should proceed.”                                                                                   , Even before the latest round of virus measures in Hong Kong, the cost of shipping malts and hops had become a challenge for many brewers. When the pandemic put pressure on the global supply chain, prices soared.                                                                                                                                                                    , Ships stuffed with raw materials remain stuck at sea. There are more delivery trucks than there are drivers.                                                                                                                                                                                                                                                                           , Ian Jebbitt, who started a Hong Kong brewery called Gweilo Beer in 2015 with his wife and a friend, said before the pandemic he used to pay around €2,000 for a container of hops. “I just agreed to pay €15,500,” he said, or more than $17,500.                                                                                                                                      , The rising costs of goods, rent and labor, as well as the lockdown measures, have made Hong Kong one of the hardest markets to operate in, said Mr. Jebbitt, who has expanded his business to other markets, including Britain and Australia. “I am surprised there haven’t been more casualties.”                                                                                     , The Hong Kong Association of Freight Forwarding and Logistics said the city’s 21-day quarantine and the effort to stamp out Omicron have created a deficit of aircrew that will most likely cause prices to go up by 30 to 40 percent in the coming weeks.                                                                                                                             , Carrie Lam, the city’s chief executive, has acknowledged the problem and warned that the cost will be felt by everyone. “We almost have no goods entering via cargo flight,” she said last week.                                                                                                                                                                                       , Motorino, a popular pizzeria with two locations in the city, is running out of tomato sauce.                                                                                                                                                                                                                                                                                           , A pallet of the sauce left Naples, Italy several months ago, but has been delayed four times, said Syed Asim Hussain, a co-founder of Black Sheep Restaurants, the group that owns Motorino and 28 other restaurants.                                                                                                                                                                  , The number of diners is dwindling, too.                                                                                                                                                                                                                                                                                                                                                , When he calculated his daily revenue across all restaurants after the new pandemic restrictions were announced, Mr. Hussain said it was less than what one of his restaurants brought in at lunchtime just a month ago.                                                                                                                                                                , The pandemic sparked the problem. The highly intricate and interconnected global supply chain is in upheaval. Much of the crisis can be traced to the outbreak of Covid-19, which triggered an economic slowdown, mass layoffs and a halt to production. Here’s what happened next:                                                                                                    , A reduction in shipping. With fewer goods being made and fewer people with paychecks to spend at the start of the pandemic, manufacturers and shipping companies assumed that demand would drop sharply. But that proved to be a mistake, as demand for some items would surge.                                                                                                        , Demand for protective gear spiked. In early 2020, the entire planet suddenly needed surgical masks and gowns. Most of these goods were made in China. As Chinese factories ramped up production, cargo vessels began delivering gear around the globe.                                                                                                                                 , Then, a shipping container shortage. Shipping containers piled up in many parts of the world after they were emptied. The result was a shortage of containers in the one country that needed them the most: China, where factories would begin pumping out goods in record volumes                                                                                                     , Demand for durable goods increased. The pandemic shifted Americans’ spending from eating out and attending events to office furniture, electronics and kitchen appliances – mostly purchased online. The spending was also encouraged by government stimulus programs.                                                                                                                 , Strained supply chains. Factory goods swiftly overwhelmed U.S. ports. Swelling orders further outstripped the availability of shipping containers, and the cost of shipping a container from Shanghai to Los Angeles skyrocketed tenfold.                                                                                                                                              , Labor shortages. Businesses across the economy, meanwhile, struggled to hire workers, including the truck drivers needed to haul cargo to warehouses. Even as employers resorted to lifting wages, labor shortages persisted, worsening the scarcity of goods.                                                                                                                         , Component shortages. Shortages of one thing turned into shortages of others. A dearth of computer chips, for example, forced major automakers to slash production, while even delaying the manufacture of medical devices.                                                                                                                                                             , A lasting problem. Businesses and consumers reacted to shortages by ordering earlier and extra, especially ahead of the holidays, but that has placed more strain on the system. These issues are a key factor in rising inflation and are likely to last for months — if not longer.                                                                                                  , In the background, Hong Kong is still navigating the aftermath of the 2019 pro-democracy protests that divided the city and his 1,000 employees.                                                                                                                                                                                                                                       , At Carbone, another one of Mr. Hussain’s Italian restaurants, December was punctuated by farewell dinners for people leaving the city, rather than raucous holiday parties. “No one in business school teaches you how to deal with two black swan events like this,” he said.                                                                                                         , Another obstacle to relaxing Covid-19 restrictions is the city’s vaccination rate, which is low compared with many developed countries. Only 70 percent of residents are fully vaccinated, with many saying they are suspicious of the government.                                                                                                                                     ,                                                                                                                                                                                                                                                                                                                                                                                        , The estimated loss for the current virus measures, which are expected to last for several more weeks, is at least $1.2 billion over a four-week period, according to Tommy Cheung, a legislative councilor who represents the catering sector in Hong Kong.                                                                                                                            , “This isn’t going away like SARS,” he said, referring to the coronavirus that devastated Hong Kong in 2003 and helped shape the city’s response to Covid-19. “This is one tunnel where I don’t see the light at the end. All these restaurants that ask me to their ribbon cutting, I keep saying that, ‘You guys are too damn brave.’”                                                , Mrs. Lam last week announced a $500 million pandemic relief fund for restaurants, retailers and travel agencies, but many businesses say it won’t be enough.                                                                                                                                                                                                                           , Rob Cooper, who owns four restaurants under the Enoteca Group, said he received four rounds of government support between November 2020 and May 2021, but managed to break even in this year only because of generous landlords and some savings.                                                                                                                                      , Now that fewer chefs and other restaurant workers are willing to move to Hong Kong and brave the quarantine, he’s unsure he’ll be able to survive another outbreak under the zero-Covid policy.                                                                                                                                                                                        , “We’ll never open up,” Mr. Cooper said. “The next variant is around the corner. That’s just science, isn’t it? How do you open up an economy if everything is imported? The rest of the world is riddled with Omicron.”                                                                                                                                                                , For Mr. Hussain, a fifth-generation Hong Konger, losing the small mom-and-pop restaurants, diners and outdoor eateries that make his home so vibrant will irrevocably change the city.                                                                                                                                                                                                 , “The old-timers assure me that we are going to be OK. But I worry as a restaurateur, as an entrepreneur,” he said. “I worry about the soul of the city.”                                                                                                                                                                                                                               , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/21/business/fast-food-prices-inflation.html </td>
   <td style="text-align:left;"> 2022-01-21 18:00:21 </td>
   <td style="text-align:left;"> Inflation Hits the Fast Food Counter  - The New York Times </td>
   <td style="text-align:left;"> , The pandemic has led to the largest price spikes at fast-food restaurants in two decades.                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , Fast food like Shake Shack hamburgers, Wingstop chicken wings and Chipotle burritos has increased in price this past year.Credit...Amy Lombard for The New York Times                                                                                                                                                                                                                                                                                                                                                                                                 , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          , By Julie Creswell                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     , On a chilly Tuesday afternoon this month, James Marsh stopped by a Chipotle near his suburban Chicago home to grab something to eat.                                                                                                                                                                                                                                                                                                                                                                                                                                  , It had been a while since Mr. Marsh had been to Chipotle — he estimated he goes five times a year — and he stopped cold when he saw the prices.                                                                                                                                                                                                                                                                                                                                                                                                                       , “I had been getting my usual, a steak burrito, which had been maybe in the mid-$8 range,” said Mr. Marsh, who trades stock options at his home in Hinsdale, Ill. “Now it was more than $9.”                                                                                                                                                                                                                                                                                                                                                                           , He walked out.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , “I figured I’d find something at home,” he said.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , The pandemic has led to price spikes in everything from pizza slices in Manhattan to sides of beef in Colorado. And it has led to more expensive items on the menus at fast-food chains, traditionally establishments where people are used to grabbing a quick bite that doesn’t hurt their wallet.                                                                                                                                                                                                                                                                  , At a Chipotle in Costa Mesa, Calif., the price of a chicken burrito — nothing fancy, hold the guacamole — about a year ago was $7.25. These days, that same burrito costs around $7.95, according to price data collected by analysts. In Ann Arbor, Mich., a ShackBurger at Shake Shack used to cost $5.69; now it’s $6.09. And in Oklahoma City, an order of 50 bone-in wings from Wingstop that cost $41.99 early last year is now $47.49, a 13 percent increase.                                                                                                  , Last year, the price of menu items at fast-food restaurants rose 8 percent, its biggest jump in more than 20 years, according to government data. And, in some cases, portions have shrunk.                                                                                                                                                                                                                                                                                                                                                                           , “In recent years, most fast-food restaurants had, maybe, raised prices in the low single digits each year,” said Matthew Goodman, an analyst at M Science, an alternative data research and analytics firm. “What we’ve seen over the last six-plus months are restaurants being aggressive in pushing through prices.”                                                                                                                                                                                                                                               , This comes at a time when the hypercompetitive fast-food market is booming.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , Chains like McDonald’s, Chipotle and Wingstop were big winners of the pandemic as consumers, stuck at home working and tired of cooking multiple meals for their families, increasingly turned to them for convenient solutions. But in the past year, as the cost of ingredients rose and the average hourly wage increased 16 percent to $16.10 in November from a year earlier, according to government data, restaurants began to quietly bump up prices.                                                                                                         , But making customers pay more for a burger or a burrito is a tricky art. For many restaurants, it involves complex algorithms and test markets. They need to walk a fine line between raising prices enough to cover expenses while not scaring away customers. Moreover, there isn’t a one-size-fits-all approach. Chains that are operated by franchisees typically allow individual owners to decide pricing. And national chains, like Chipotle and Shake Shack, charge different prices in various parts of the country.                                         , When Carrols Restaurant Group, which operates more than 1,000 Burger Kings, raised prices in the second half of last year, the number of customers actually improved from the third to the fourth quarter. “Over time, we generally have not seen a whole lot of pushback from consumers” on the higher prices, Carrols’ chief executive, Daniel T. Accordino, told analysts at a conference in early January.                                                                                                                                                        , Menu prices are likely to continue to climb this year. Many restaurants say they are still paying higher wages to attract employees and expect food prices to rise.                                                                                                                                                                                                                                                                                                                                                                                                   , “We expect unprecedented increases in our food basket costs versus 2021,” Ritch Allison, the chief executive of Domino’s Pizza, told Wall Street analysts at a conference this month. While Domino’s hasn’t raised prices, it is altering its promotions — offering the $7.99 pizza deal only to customers ordering online and shrinking the number of chicken wings in certain promotions to eight from 10 — in an effort to maintain profit margins.                                                                                                                , Despite the higher food and labor costs, some restaurants are seeing sales and profits rebound past prepandemic levels.                                                                                                                                                                                                                                                                                                                                                                                                                                               , When McDonald’s reports earnings this month, Wall Street analysts expect that its revenues will have hit a five-year high of more than $23 billion, a $2 billion increase from 2019. Net income is predicted to top $7 billion, up from $6 billion in 2019. Other chains like Cracker Barrel and Darden Restaurants, which owns Olive Garden and Longhorn Steakhouse, have resumed dividend payments or cash buybacks of stock after suspending those activities early in the pandemic to conserve cash.                                                              , And next month, when Chipotle reports results for 2021, analysts expect revenues to top $7.5 billion, a 34 percent jump from 2019. Net income is expected to almost double from prepandemic levels. In the third quarter, the company repurchased nearly $100 million of its stock. Chipotle declined to make an executive available for an interview, citing the quiet period ahead of its earnings release.                                                                                                                                                         , While Chipotle executives blamed higher labor costs for a 4 percent price increase in menu items this summer, the company has been looking for ways to boost its profitability.                                                                                                                                                                                                                                                                                                                                                                                       , One way was to charge higher prices for delivery. Delivery orders through vendors like DoorDash and Uber Eats exploded for Chipotle and other fast-food chains during the pandemic. But so did the commission fees that Chipotle paid the vendors. So in the fall of 2020, it began running tests to see what would happen if it raised the prices of burritos and guacamole and chips that customers ordered for delivery, executives told Wall Street analysts in an earnings call. It essentially meant the customer covered Chipotle’s side of the delivery costs., The company discovered customers were willing to pay for the convenience of delivery. Now, customers ordering Chipotle for delivery pay about 21 percent more than if they had ordered and picked the food up in the stores, according to an analysis by Jeff Farmer, an analyst at Gordon Haskett Research Advisors.                                                                                                                                                                                                                                                 , “I would say that our ultimate goal, so this would be over the long term, maybe the medium term, is to fully protect our margins,” said Jack Hartung, the chief financial officer of Chipotle, on a call with Wall Street analysts last fall. “When you look at our pricing versus other restaurant companies’ for the quality of the food, the quantity of the food, and the quality and convenience of the experience, we offer great value. So we believe we have room to fully protect the margin.”                                                               , That doesn’t mean customers are thrilled about the extra costs.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , This month, Jacob Herlin, a data scientist in Lakewood, Colo., placed an order: a steak-and-guacamole burrito for $11.95, a Coca-Cola for $3, and chips and guacamole, which were free with a birthday coupon. The total was $14.95, before tax.                                                                                                                                                                                                                                                                                                                      , But when he clicked to have the food delivered, the price for the burrito jumped to $14.45 and the soda climbed to $3.65, bringing the total to $18.10 before tax, 21 percent more than if he had picked the food up himself.                                                                                                                                                                                                                                                                                                                                         , There was more. Mr. Herlin was charged a delivery fee of $1 and another “service fee” of $2.32, bringing the total for the delivered meal to $23.20. He tipped the driver an additional $3.                                                                                                                                                                                                                                                                                                                                                                           , Mr. Herlin said he did not mind paying for delivery and wanted drivers to be paid a decent wage. But he felt that Chipotle wasn’t being upfront with customers about the added costs.                                                                                                                                                                                                                                                                                                                                                                                 , “They’re basically hiding the fees two different ways, through that base price increase and through the hidden ‘service fee,’” Mr. Herlin said in an email. “I would very much prefer if they had the same pricing and were just honest about a $5 delivery fee.”                                                                                                                                                                                                                                                                                                     , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://www.nytimes.com/2022/01/21/us/politics/us-mint-racial-turmoil.html </td>
   <td style="text-align:left;"> 2022-01-21 18:00:12 </td>
   <td style="text-align:left;"> Racial Turmoil Mars Signs of Progress at the U.S. Mint - The New York Times </td>
   <td style="text-align:left;"> Advertisement                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       , Supported by                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        , A new internal report found that Black employees felt marginalized at the Treasury agency that produces the nation’s coins.                                                                                                                                                                                                                                                                                                                                                                                                                                                                         , Send any friend a story                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             , As a subscriber, you have 10 gift articles to give each month. Anyone can read what you share.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      , By Alan Rappeport                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   , WASHINGTON — The United States Mint celebrated a milestone this month when it announced the first shipment of a new batch of quarters bearing the image of the writer and poet Maya Angelou, the first Black woman to be depicted on the 25-cent coin.                                                                                                                                                                                                                                                                                                                                              , The announcement came weeks after President Biden said he would nominate Ventris C. Gibson to lead the Mint, where, if confirmed, she would serve as its first Black director.                                                                                                                                                                                                                                                                                                                                                                                                                      , But beneath the public signs of social progress is an agency that has struggled for years with racial tension, with Black employees saying they feel threatened, marginalized and professionally disadvantaged. While instances of racism at the Mint have surfaced in previous years, a new internal report that was reviewed by The New York Times depicts an institution rife with tumult over allegations of racist behavior.                                                                                                                                                                   , A draft of the report, which was commissioned by the Mint last year and produced by an independent human resources consulting firm, determined that the agency, which is part of the Treasury Department, had a “culture problem” and that staff members felt a “lack of psychological safety.” The report described a workplace with “implicit bias” and “microaggressions” toward people of color.                                                                                                                                                                                                , Participants in a survey conducted by the consulting firm, which included more than 200 staff members, senior managers and executives, said race was a divisive issue at the Mint. Many people at the agency expressed concerns that hiring and promotions for people of color were not handled fairly and said they feared reprisal for making formal complaints.                                                                                                                                                                                                                                  , In interviews with the firm that were quoted in the report, some managers at the Mint appeared dismissive of the racial concerns. Comments made by managers included saying that “we need a model minority” and that “if we put a minority as a U.S. Mint assistant director, the minorities will see we are not racist or sexist.”                                                                                                                                                                                                                                                                 , The firm, TI Verbatim Consulting, said in the report that its findings “point to potential root causes for the racial divide” at the Mint. The report cited outdated policies, cliques, ambiguous promotion practices and the perception of favoritism. Although some members of the Mint’s work force described a positive environment, others said there had been a noticeable “downward spiral” in recent years amid growing racial tension and as acts of overt discrimination surfaced.                                                                                                        , “The work force does not feel that the organization lives up to its values,” said the report, which surveyed a mix of white employees and people of color.                                                                                                                                                                                                                                                                                                                                                                                                                                          , Concerns about a culture of discrimination at the Mint garnered national attention in 2017 after a white worker at a facility in Philadelphia tied a rope used for sealing coin bags into a noose and left it on the workstation of a Black colleague. In a letter in 2020 to Steven Mnuchin, who was the Treasury secretary, staff members at the Mint said that another noose had surfaced and that the N-word had been written across walls in restrooms. They also said a white Mint official had referred to a Black leader at the agency as a “zoo keeper” in an instant message conversation., The allegations were referred to the Treasury Department’s inspector general, Richard K. Delmar. He found no evidence of racial animus surrounding the Philadelphia noose incident, but his inquiry into other allegations continues. Mr. Delmar declined to comment on the review that is underway.                                                                                                                                                                                                                                                                                                , The day after the noose was found, the employee in question was removed from his job. He challenged his removal before the U.S. Merit Systems Protection Board, which reviews cases of government employees who are contesting their termination, and said his job involved tying knots. The Mint later agreed to a settlement with the employee after the Justice Department declined to take any action; a Mint spokesman said the settlement had been made in an effort to end the dispute and ensure that the employee would not be reinstated.                                                 , The revelations of racial turmoil come as the Mint is at a potential turning point. Mr. Biden has made racial equity a centerpiece of his agenda, and he announced in December that he would nominate Ms. Gibson to be the agency’s director. She is the Mint’s deputy director and has been leading the agency on an acting basis.                                                                                                                                                                                                                                                                 , Ms. Gibson, who needs to be confirmed by the Senate, has vowed to improve the Mint’s culture. Last month, she led a diversity briefing during a senior managers’ meeting, and she is planning to create new career development programs to help make the promotion process more transparent.                                                                                                                                                                                                                                                                                                        , “Our work force comes from diverse backgrounds, and I am committed to ensuring that we respect, honor and leverage that diversity,” Ms. Gibson said in a statement. “We must ensure that there are no barriers to the success and advancement of any employee at the Mint.”                                                                                                                                                                                                                                                                                                                         , She added, “We at the senior leadership level must make concerted efforts to always treat our employees with fairness and integrity, and to restore faith in those basic tenets of good leadership and exemplify genuine care for the work force.”                                                                                                                                                                                                                                                                                                                                                  , But there are lingering concerns within the Mint’s staff about her commitment and ability to bring change to an organization where cultural problems have festered for so long.                                                                                                                                                                                                                                                                                                                                                                                                                     , Staff members inside the Mint are fearful that symbols of change may not necessarily lead to tangible cultural change at the 1,600-person agency, which was established by the Coinage Act of 1792. That includes the decision to put Ms. Angelou on the quarter.                                                                                                                                                                                                                                                                                                                                   , “It’s a distraction,” said Rhonda Sapp, the president of the Mint workers’ union, who questioned the value of putting Ms. Angelou on a coin “when you mistreat the people, some of whom are people of color, who are making the coins.”                                                                                                                                                                                                                                                                                                                                                             , Ms. Sapp, who said she had not seen the consulting firm’s report, said shifting the agency’s culture would require more sweeping changes among the Mint’s leadership.                                                                                                                                                                                                                                                                                                                                                                                                                               , “What good is it to have the first Black female director, if she is confirmed, when you have all of these people who have these behaviors and mind-sets undermining her at every turn?” Ms. Sapp asked.                                                                                                                                                                                                                                                                                                                                                                                             , Others are more optimistic that Ms. Gibson will be able to foster a culture of inclusion.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           , “Ventris brings years of human resources experience at large organizations,” said Rosie Rios, who served as treasurer of the United States during the Obama administration. “I’m sure she will do a fine job with the Mint.”                                                                                                                                                                                                                                                                                                                                                                        , The report credited the Mint’s leadership for commissioning the assessment of its culture and allowing respondents to speak freely about the agency. It said that “tremendous opportunity exists for real change.”                                                                                                                                                                                                                                                                                                                                                                                  , Before Mr. Biden announced her nomination to lead the Mint, Ms. Gibson was appointed in October as the agency’s deputy director. At the time, Wally Adeyemo, the deputy Treasury secretary, hailed her selection as a sign of progress.                                                                                                                                                                                                                                                                                                                                                             , “Her historic appointment reflects our ongoing commitment to building a qualified, diverse work force at Treasury and its bureaus that will serve the American people well,” he said.                                                                                                                                                                                                                                                                                                                                                                                                               , The Mint historically was a place that pioneered diversity but did not always prioritize healthy working conditions. In 1795, it became the first federal agency to employ women when it began hiring them to work in the so-called adjusting room, a poorly ventilated space where they would weigh and file down blank coins.                                                                                                                                                                                                                                                                     , The agency has facilities in Philadelphia; Denver; San Francisco; West Point, N.Y.; and Fort Knox, Ky. Through the 1960s, the staff around the country was largely white and working class, but in recent decades it became more diverse. At the Mint’s administrative headquarters in Washington, where around 300 people work, those in leadership and higher-paying roles are mostly white, while employees on the lower end of the pay scale are mostly people of color, according to the report.                                                                                               , In recent years, bringing diversity to the imagery on America’s coins has been a priority for the Mint. The bipartisan Circulating Collectible Coin Redesign Act of 2020, which President Donald J. Trump signed into law the week before he left office, initiated the addition of notable women, such as Ms. Angelou, on quarters through 2025.                                                                                                                                                                                                                                                   , The findings of the report have yet to be released publicly. They are expected to be shared more widely within the Mint’s staff this month, Ms. Gibson said in her statement.                                                                                                                                                                                                                                                                                                                                                                                                                       , Advertisement </td>
  </tr>
  <tr>
   <td style="text-align:left;"> https://tradingeconomics.com/commodity/gasoline </td>
   <td style="text-align:left;"> 2022-01-21 17:57:05 </td>
   <td style="text-align:left;"> Gasoline Rally Falters after Storage Buildup </td>
   <td style="text-align:left;"> US gasoline futures eased to $2.4 per gallon after touching a three month high of $2.48 a gallon on January 20th, as domestic inventories increased. US crude inventories unexpectedly rose for the first time in eight weeks, while gasoline stocks expanded by 5.87 million barrels, compared with estimates of a 2.63 million barrel build. Earlier, the bullish momentum stemmed from rising tensions in the Middle East, which had exacerbated supply woes, and from EIA data that showed gasoline storage levels were well below the long-term usual. Looking ahead, the government agency sees the recent reduction in retail gasoline prices to extend through 2022 and 2023 due to slower demand growth and increasing crude oil production. </td>
  </tr>
</tbody>
</table></div>

---


### Stock Tweets Scraping

#### Extraction of latest stock comments and tweets from [StockTwits](https://stocktwits.com/), a real-time social media platform for sharing of ideas between market participants.

[Brief Illustration of Function](/Output-of-getStockTwits.md)



Last Updated: 2022-01-22 09:42:23 UTC +8

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
   <td style="text-align:left;"> 2022-01-22 09:41:38 </td>
   <td style="text-align:left;"> $SPY added small lotto for next Wednesday $440 c </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:41:26 </td>
   <td style="text-align:left;"> $SPY bro the whole board is bears now.. 🐻  they&amp;#39;re really trying make it seem like it&amp;#39;s the end of the world. I bought calls before closing for next week because why not. Call em &amp;quot;Lotto tickets&amp;quot; Things don&amp;#39;t go straight up or straight down. Even a dead cat bounce should print for me. Buying millions of dollars in puts when this has corrected almost 10% is straight up retarded. Those who bought from 470s did their hw but now it&amp;#39;s just greed and those MMs don&amp;#39;t give out free candy... well except for today&amp;#39;s trillions in puts. But still yall get the point!  👈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:41:05 </td>
   <td style="text-align:left;"> $SPY will it stop at 390 or going below 390 ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:41:02 </td>
   <td style="text-align:left;"> $SPY read through a few messages on various tickers… I get the sense BTFD isn’t dead yet lmao… unbelievable </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:40:59 </td>
   <td style="text-align:left;"> $SPY i dont forget. Ill be back kenny g. When you least expect it. I will be there when you die to piss on your mausoleum </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:40:47 </td>
   <td style="text-align:left;"> The only way to hedge against Stocks &amp;amp; Crypto it&amp;#39;s with NFTs $SPY $ETH.X $QQQ $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:40:47 </td>
   <td style="text-align:left;"> $SPY Why Was Jim Cramer Stressed tonight. ? Anybody have a Guess? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:39:58 </td>
   <td style="text-align:left;"> $SPY   Looks like 10 points pullback  will reset mark to 19x 2022 expected earnings.  May be appropriate  level.  Drop to 19x may be reflective of FED expected action.  Drop 4X in multiple from 23X to 19X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:39:47 </td>
   <td style="text-align:left;"> $DAVE Wtf is this shit.   meanwhile americas top 500 companies bkeeding out the ass. Way to go dave. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:39:44 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:39:38 </td>
   <td style="text-align:left;"> $SPY dont forget the election was stolen through voter fraud by Marxists in swing states. Biden didn’t get close to 81M votes. He’s the worst president in history. Those responsible should be tried and punished for treason. 

Let’s go Brandon! Need a good president again, so the market can bounce back. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:39:05 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:38:58 </td>
   <td style="text-align:left;"> $SPY if u want to have nightmares tonight look at the the monthly MACD.  Stay safe y’all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:38:40 </td>
   <td style="text-align:left;"> $SPY while most are shaking a short term bounce is overdo. Just you watch the algos. Earnings, fed meeting, 200 day moving average and more </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:38:38 </td>
   <td style="text-align:left;"> $SPY Let&amp;#39;s play a game of pick the bottom.

I say 420.

Name your price. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:38:13 </td>
   <td style="text-align:left;"> $SPY WHATS GOING ON IN HERE?🧐 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:38:06 </td>
   <td style="text-align:left;"> $SPY 
Ight I&amp;#39;ll admit. 

I got stock market addiction. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:38:05 </td>
   <td style="text-align:left;"> $LCID $SPY $DJIA $QQQ $NASDAQ - it absolutely blows my mind that two weeks ago everyone was “diamond hands”, “apes”, “buying lambos”, etc… yet now, because the news and our joke of a White House administration tells you otherwise, people are running for the hills screaming Armageddon, Recession, Depression. Hell.. I even heard people talking about Russia invading Ukraine and we barely do sh*t with either of those countries. This is the whole reason that senile, clown got elected in the first place… because people take any and everything they hear from the media as gospel and don’t think for themselves. Has your life so substantially changed in the last 2-3 weeks that it makes sense to devalue your assets 10-20%?!?! The answer is no… these clowns are propagating fear to profit at your expense based on ignorance, just as they do in politics!!!l </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:37:37 </td>
   <td style="text-align:left;"> $SPY only 2% drop. Can&amp;#39;t wait for the 20% break!!! Oh wait government will have breakers at 5% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:37:23 </td>
   <td style="text-align:left;"> $SPY $SPX $ES_F  I called this drop / gap-fill in the first week of December last year. A healthy/needed correction for SPY. Now, upward and onward </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:37:18 </td>
   <td style="text-align:left;"> $SPY $QQQ $UUP $TLT
Weekend Market Recap for Friday1/21/2022 for #Stocks #Bitcoin #Gold and #Silver
https://youtu.be/0XbfeD1bKu4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:36:59 </td>
   <td style="text-align:left;"> $SPY 2018 or 2008 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:36:42 </td>
   <td style="text-align:left;"> $SPY My most degenerate weekend position. Anybody else got something better? I’m open to calls and puts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:36:37 </td>
   <td style="text-align:left;"> $SPY this build back better... does he mean does this feel better? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:36:13 </td>
   <td style="text-align:left;"> $SPY If you have dementia is it better to be 1. president of the USA
2. Playing bingo in a nursing home </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:35:40 </td>
   <td style="text-align:left;"> $SPY short whatever Cramer says buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:34:54 </td>
   <td style="text-align:left;"> $SPY only another new variant that shuts  down everything will save the mkts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:34:43 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:34:36 </td>
   <td style="text-align:left;"> $SPY everything is fake , you know it, I know it, everybody knows it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:34:32 </td>
   <td style="text-align:left;"> $SPY I bought a 440$ call before close and looks like I&amp;#39;m screwed. I will take break even if possible </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:34:20 </td>
   <td style="text-align:left;"> $SPY IM STILL WATCHING SCREAM 5 with someone NO ONE SPOIL IT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:34:18 </td>
   <td style="text-align:left;"> $SPY trading rule #1: don’t blame others for your losses. You placed the trade. You own the decision. You own the outcome. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:34:04 </td>
   <td style="text-align:left;"> $SPY vote for the swamp you get the swamp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:33:19 </td>
   <td style="text-align:left;"> $SPY I understand y’all. For the past year we’ve been able to buy calls on every daily low and make EASY money, but those times are officially over… for now.

This stock is utterly bearish… It’s about to crash whether you accept it or not. 

Bearish confirmation happened today. Monday will be bloodbath 100% confidence. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:33:11 </td>
   <td style="text-align:left;"> $SPY McClellan Oscillator a reliable tool for judging overbought and over sold mkts.  We are near the lowest level in 2 yrs. Only time lower was Covid crash and Dec 2018 correction. Monday or Tuesday could be the turn around days.. atleast the Breadth picking up. $DIA $TSLA $QQQ $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:33:11 </td>
   <td style="text-align:left;"> $SPY What a shellacking!!! Despite the bearishness, I’m going to continue to buy. The downtrend can’t last forever. The market has gone up with elevated rates in the past. Earnings are still expected to grow and be great. Omicron is starting to fade as well. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:32:52 </td>
   <td style="text-align:left;"> $SPY msft went from deep red in after hours to slightly green. They were loading it in Ah. You know what that means for Monday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:32:45 </td>
   <td style="text-align:left;"> $SPY stable markets is one of the Fed&amp;#39;s mandates. we&amp;#39;ve been down this road in &amp;#39;18. JP will most likely take a relatively dovish tone. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:32:30 </td>
   <td style="text-align:left;"> $SPY Volatility is great again. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:32:22 </td>
   <td style="text-align:left;"> $SPY FAANG IS NOW FAAG </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:32:00 </td>
   <td style="text-align:left;"> $SPY I&amp;#39;m losing my shit! It&amp;#39;s all Biden&amp;#39;s fault!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:31:58 </td>
   <td style="text-align:left;"> $SPY remember the 69 million the ceos sold in December? I do </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:31:50 </td>
   <td style="text-align:left;"> $SPY the mother of all short squeezes is approaching. Pigs get slaughtered!

4510, BELOW THAT 4410, BELOW THAT 4300+/-10 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:31:20 </td>
   <td style="text-align:left;"> $SPY okay so major question, are we pricing in a January rate hike with this recent correction?  Or is this merely a reaction to us entering the future of curbing inflation which entails multiple periodic rate hikes? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:31:02 </td>
   <td style="text-align:left;"> $SPY Were darkpools buyers or sellers today? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:30:59 </td>
   <td style="text-align:left;"> $SPY Powell will save the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:30:54 </td>
   <td style="text-align:left;"> $SPY spy Monday 445 open followed by the biggest squeeze of lemons ever to hit 451, 455 gap up and close at 458 on Tuesday Wednesday we see some dump shit chop close at 460, Thursday we fade into fomc ending, with an initial dip at 230 followed by a green candle up our asses to 462 for the close. Friday probably flatter then your wife’s tits after your kids sucked the meat out of them. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:30:16 </td>
   <td style="text-align:left;"> Ditch the Sub-Services! How To Make Your Own Winning Trading System!

$SPY $QQQ $IWM $ES_F $DIA

https://www.chartlearning.com/2021/12/how-to-create-a-stock-trading-system.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:30:05 </td>
   <td style="text-align:left;"> $SPY I have the best information around that converts liberals. Debate my info if you can. Biden remorse is growing all over America and the markets are not happy🤦‍♂️🤦‍♂️🤦‍♂️🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸🇺🇸✅✅✅ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:30:01 </td>
   <td style="text-align:left;"> $SPY never understood how you degens play with margin.  this is fun to watch and im not even worried. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:29:52 </td>
   <td style="text-align:left;"> $SPY IM WATCHING SCREAM 5, NO ONE SPOIL IT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:29:37 </td>
   <td style="text-align:left;"> $SPY need Trump 😔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:27:41 </td>
   <td style="text-align:left;"> $SPY mis important this week 

https://www.cnbc.com/2022/01/21/markets-are-expected-to-remain-on-edge-as-the-fed-meets-in-the-week-ahead.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:27:31 </td>
   <td style="text-align:left;"> $SPY So let me get this straight due to the vaccine mandates truck drivers are required to be vaccinated as of the 22nd? Currently only 50% of truckers are vaccinated😳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:27:22 </td>
   <td style="text-align:left;"> $SPY for real though the young people narrative... 50 to 60 year old control everything currently..... Y&amp;#39;all fucked this up don&amp;#39;t blame young ones you were the ones that could raise 3 kids as a mailman. Gtfo. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:26:16 </td>
   <td style="text-align:left;"> $QQQ $SPY all I have to say is election’s will be all republicans democrats set themselves up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:25:42 </td>
   <td style="text-align:left;"> $SPY Today&amp;#39;s dip buying effort according to the option flow study option flows.  Track flows using thinkorswim natively, built in thinkscript. stonkmetrics.ca/chainsentiment </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:25:11 </td>
   <td style="text-align:left;"> $SPY there are gazillion lines of algo code that executes every hour. If past occurrence is repeatable , there wouldn’t be any mkts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:25:10 </td>
   <td style="text-align:left;"> $SPY $QQQ pawn shop and payday loans booming today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:25:01 </td>
   <td style="text-align:left;"> $SPY  blacking out tonight </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:24:52 </td>
   <td style="text-align:left;"> $SPY  
 
DD 
 
https://youtu.be/yaKVgsjfDi0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:24:39 </td>
   <td style="text-align:left;"> $SPY I beat the market. I know what’s happening! Listen! It’s bearish fasho!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:24:11 </td>
   <td style="text-align:left;"> $SPY deep red day Monday when we hit 427, and then bounce Tuesday then drop rest of week to 400 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:24:04 </td>
   <td style="text-align:left;"> $SPY what would happen if 98% of everyone just bought puts on this? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:23:53 </td>
   <td style="text-align:left;"> $SPY Big Red Dildo candles coming boy!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:23:36 </td>
   <td style="text-align:left;"> $SPY How you rate yourself: A-

How the market rates you: F

Completely delusional. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:22:58 </td>
   <td style="text-align:left;"> $IWM $QQQ $SPY 

Bang 💥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:22:16 </td>
   <td style="text-align:left;"> $SPY ngl this looks exactly like march 2020 and dropped 2-3% per day triggerin circuit breakers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:21:37 </td>
   <td style="text-align:left;"> $SPY $QQQ people aren&amp;#39;t even going to work anymore 
The ones that have jobs complain if they have to physically be there lol
This generation is pathetic
Economy is pathetic and stock market has been a smartphone slot machine for teens!
This online casino will end like reddit ponzi games </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:21:37 </td>
   <td style="text-align:left;"> $QQQ $SPY $VIX   
 
This is a pretty good one:))) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:21:21 </td>
   <td style="text-align:left;"> $SPY if i learned one thing after getting fucked by the market in the ass without lube multiple times is to do and expect the unexpected. Monday seems to obvious to be red which means is going to be super Green. Watch it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:21:10 </td>
   <td style="text-align:left;"> The Stock Markets wont bounce back they way they did in 2020, specially with the FED shrinking their Balance sheet and raising rates -- Normalize this $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:20:48 </td>
   <td style="text-align:left;"> $SPY $PFE $MRNA let’s go Brandon bringing equality to the masses </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:20:37 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:20:19 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
A sucessful president does not drag his country into war.  
  
He takes care of his own house before worrying about others!  
  
Fuck Joe Biden and his &amp;quot;war with Russia&amp;quot; rhetoric! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:20:15 </td>
   <td style="text-align:left;"> $SPY continue bleeding until FOMC! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:19:59 </td>
   <td style="text-align:left;"> $SPY getting clapped </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:19:57 </td>
   <td style="text-align:left;"> $SPY GD drama queens.  Make your shopping list Bulls.  I&amp;#39;m excited won&amp;#39;t be asleep all weekend 🍺 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:19:55 </td>
   <td style="text-align:left;"> $QQQ $Spy $NASDAQ 
Here’s to all the D F’s who worship the God Fauci and the CDC . 

https://newspunch.com/cdc-finally-admits-natural-immunity-far-superior-to-jabbed-immunity-alone/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:19:43 </td>
   <td style="text-align:left;"> $SPY How are you doing Cathie Woods? “ How the hell do you think I’m doing?” “I need another shot of Tequila!” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:19:39 </td>
   <td style="text-align:left;"> $KLXE should be pretty clear where this is heading, kept it’s ground despite the red in $SPY $XLE and $IWM. Thanks to @da224 for pointing out this gold mine and to all others for extensive DD. Big pay day coming in next few months </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:19:17 </td>
   <td style="text-align:left;"> $SPY please watch and share https://youtu.be/6ecxrCRET5Y </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:18:47 </td>
   <td style="text-align:left;"> $SPY I don&amp;#39;t think Russia will do the new world war model. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:18:40 </td>
   <td style="text-align:left;"> $SPY it can still go Wayyyyy lower (but I cannot stop buying 🥴) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:18:15 </td>
   <td style="text-align:left;"> $SPY $433, $427, then plummeting sub $400 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:17:53 </td>
   <td style="text-align:left;"> $SPY simple equation russia starts war and we tank.. russia does not do anything we have a dead cat bounce on Monday.. let’s see </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:17:50 </td>
   <td style="text-align:left;"> $SPY $BTC $ALGO.X $FARM.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:17:32 </td>
   <td style="text-align:left;"> $SPY 

I hate to say it but this thing will pass down to $300. I actually feel bad for the bulls. Good grief! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:17:17 </td>
   <td style="text-align:left;"> $SPY $QQQ Biden should be wearing an oxygen mask instead of a N95 maybe he can think better </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:17:10 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:17:01 </td>
   <td style="text-align:left;"> $SPY funny how the bears are out right before the weekend. happens every time 😂 monday we go up. i’m estimating $444+. throwing some angel numbers out there. yeah, we’re seeing some red but in every dump is a pump. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:17:00 </td>
   <td style="text-align:left;"> $SPY told yea to buy puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:16:52 </td>
   <td style="text-align:left;"> $BABYDOGE.X $BTC $SPY Looking better with every trim. I&amp;#39;ll keep adding every chance I get. Let&amp;#39;s get this last dip on BTC to 15 - 20k then 200k please. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:16:46 </td>
   <td style="text-align:left;"> $SPY Holy shix this almost as brutal as bulls getting slaughtered today  👀 

https://mobile.twitter.com/CBSLA/status/1484279564423483395?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1484279564423483395%7Ctwgr%5E%7Ctwcon%5Es1_&amp;amp;ref_url=https%3A%2F%2Fcitizenfreepress.com%2Fbreaking%2Fmotorcyclist-killed-in-high-speed-crash-live-on-air%2F </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:16:44 </td>
   <td style="text-align:left;"> $SPY Still 10 more days of January and more Fed news next week. Not over yet! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:16:16 </td>
   <td style="text-align:left;"> $SPY $QQQ $ARKK I have been chart reading for the last two hours and I have come to this conclusion on this massacre. I would like honest second opinions: SPY broke the neckline of a HS pattern at $450. The bottom of that pattern plays out at $430. I am looking to SPY to lead us out of this so that is why I am focusing on SPY chart more than QQQ.  The $430 bottom of HS pattern for SPY also happens to be long term support going back to July AND is also SPY 50 DMA on WEEKLY. So, if on Monday morning SPY goes down another 1.5% and hits around $430, completing HS bottom pattern AND hits 50 DMA on WEEKLY, I am buying and taking my damn chances. That makes sense to me. I will buy Apple at $157 and maybe a few QQQ. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:16:15 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA $BTC.X 
 
Poor Millennials 
 
They were once again take advantage off as JPOW leveraged the world-wide pandemic to intentionally inflate asset prices so Boomers could hand off bags at all time highs and valuations just as they were retiring en masse. 
 
Boomers know the stock market game and took the opportunity to lock in lifetime gains and hand off their bags to Millennials at OBVIOUSLY overvalued levels. 
 
So who are Millennials going to convince to take their bags when they are ready to retire? GenZ? Good luck!...they just went through the same scam with you. 
 
Boomers are relentless in taking advantage of the world around them for their own personal gain. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:15:55 </td>
   <td style="text-align:left;"> $SPY We dropped from avg PE of 66 in mid 2021 now down to 36.

The average P/E of all the stocks in the _____ database is 36.7..

*By the way, FEB 2020 before COVID Crash, avg PE was 40.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:15:41 </td>
   <td style="text-align:left;"> $SPY $RTY_F $GLD $BTC.X 
Friday night quotes: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:15:39 </td>
   <td style="text-align:left;"> $SPY I think I picked the last day you could to sell my portfolio and buy puts lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:15:25 </td>
   <td style="text-align:left;"> $SPY $QQQ January Effect reminding me of that time I bought a nice vacation home and, instead of moving in, burned it straight to the ground. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:15:10 </td>
   <td style="text-align:left;"> At this pace market is pricing in doomsday 👀😂 $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:15:05 </td>
   <td style="text-align:left;"> $SPY Biden’s build back better plan is dead which means no tax hikes. How does he fix that? Have Powell and Fed crush investors and wall street. Payback </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:14:49 </td>
   <td style="text-align:left;"> $SPY  was it 480 eom or 500? I forget..... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:14:27 </td>
   <td style="text-align:left;"> $SPY at least the market hit the breaks. Crypto is going to bleed all weekend 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:14:21 </td>
   <td style="text-align:left;"> $SPY $QQQ Do y’all remember when that happened? Good times. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:14:07 </td>
   <td style="text-align:left;"> $SPY Everyone sees Netflix post-percent, -22?

Now, take tech stocks ERs and subtract 10-20% from share price of the 26% of stocks in the Nasdaq.... $NDX

Love that song: You Ain&amp;#39;t Seen Nothing Yet

Here&amp;#39;s something, you won&amp;#39;t forget. BABY! You ain&amp;#39;t seen nothing yet. You ain&amp;#39;t...

God bless your trades.

Do own DD

$QQQ $SOXX $XLK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:14:05 </td>
   <td style="text-align:left;"> $SPY Hope everyone has a great weekend. This month has been incredible for my port. Remember if you lose money learn from your mistakes, find what trading strategies work for you, and improve. The goal is long term wealth building, don&amp;#39;t lose it all on leveraged short term gambling. If the market continues to crash(my targets are 3500 and 2500) spend the bear cycle years adding shares in strong companies that give a dividend and keep reinvesting them. Just don&amp;#39;t forget to diversify into other asset classes that are more recession proof as well. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:13:57 </td>
   <td style="text-align:left;"> $SPY  I don&amp;#39;t hate inflation anymore. $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:13:56 </td>
   <td style="text-align:left;"> $SPY $BTC.X $ETH.X no where else to go: </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:13:51 </td>
   <td style="text-align:left;"> $SPY After Ukraine...Taiwan..? With Biden the world is an oyster </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:13:47 </td>
   <td style="text-align:left;"> $SPY $NAIL $BLDR Buy BLDR @ $60 All you can, this will be tremendous opportunity </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:13:42 </td>
   <td style="text-align:left;"> $SPY Monday big dump day </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:13:27 </td>
   <td style="text-align:left;"> $rhe $blin $SPY $CEI 

How does a trader with 5k account turn into multi million fortune In few years. This is something immense that will be talked about, very soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:13:22 </td>
   <td style="text-align:left;"> $SPY 500 by valentine&amp;#39;s day. ♥ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:13:06 </td>
   <td style="text-align:left;"> $BTC.X $SPY guess we will know how Monday opens😂😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:13:04 </td>
   <td style="text-align:left;"> $SPY Biden is so out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:12:59 </td>
   <td style="text-align:left;"> $SPY Icing on the cake for Bears will be if Russia invades Ukraine this week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:12:58 </td>
   <td style="text-align:left;"> $SPY inverse the chart. Hello volatility. 
 https://www.reddit.com/r/Epic_Economics/comments/s9qcdk/its_time_to_hold_uvxy_volatility_is_here_to_stay/?utm_source=share&amp;amp;utm_medium=ios_app&amp;amp;utm_name=iossmf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:12:58 </td>
   <td style="text-align:left;"> $SPY can we see $200 possible next week? I am all in sqqq💪☀️🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:12:49 </td>
   <td style="text-align:left;"> $SPY congrats to whoever is the republican presidential candidate in 2024 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:12:06 </td>
   <td style="text-align:left;"> $DWAC $SPY BTC.X 
Two New York City police officers were struck in a shooting in Harlem Friday night, days after a 16-year-old boy allegedly shot another officer in the Bronx, according to authorities. 
 
An NYPD spokesperson confirmed that two officers had been shot near 119 West 135th Street in the NYPD’s 32nd Precinct but said their conditions were not immediately available. They were rushed to Harlem Hospital. 
 
Both officers are dead. 
 
Democrat Utopia pushing police hate. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:12:00 </td>
   <td style="text-align:left;"> $SPY  -2.5% gap down :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:11:58 </td>
   <td style="text-align:left;"> $SPY watch everyone be wrong, no crash no crazy V recovery just nasty indecision </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:11:57 </td>
   <td style="text-align:left;"> $SPY admit it. Biden make Powell fuck us </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:11:28 </td>
   <td style="text-align:left;"> $SPY Joe hiden after this market crash </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:11:19 </td>
   <td style="text-align:left;"> $SPY @sonicmerlin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:11:03 </td>
   <td style="text-align:left;"> $AAPL The Fed is your friend until it isn’t. Which is now! Rug pull! $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:10:58 </td>
   <td style="text-align:left;"> $SPY Here goes another boring weekend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:10:40 </td>
   <td style="text-align:left;"> $SPY Enjoy your weekend and remember those you saw here today who were not afraid to post on a volatile day. Only the strong and valiant fly their colors at Battle Zero. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:10:30 </td>
   <td style="text-align:left;"> $SPY

Downward target: $390 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:10:28 </td>
   <td style="text-align:left;"> $SPY  
If the real estate market crashes, will many have paid their first round of property taxes based on the inflated selling price... 
 
Buy puts on the local tax assessors stress level </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:10:20 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:10:18 </td>
   <td style="text-align:left;"> $SPY Monday morning it’s 4 am and futures have just done something unheard of and you’re 6 to 12 you open up Yahoo finance to see an article post saying the market is in a bubble and it’s about to burst. You scroll down to your watchlist and all you see is what colour? You quickly roll over to your wife and say sorry hun I need to tell you something. What do you say? You then turn back to your phone and see things haven’t changed. You’re now rich or broke? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:09:59 </td>
   <td style="text-align:left;"> $SPY who voted for Dementia? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:09:56 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $SPX 
War on drugs, war on terrorism, war on other countries. 

Maybe a war on homelessness should be tried. Ahh wait. No money in that never-mind. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:09:55 </td>
   <td style="text-align:left;"> $SPY back to 400 we go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:09:51 </td>
   <td style="text-align:left;"> $SPY I won’t buy one spy share until it’s under 400 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:09:35 </td>
   <td style="text-align:left;"> $SPY At least...Putin is there to not let it get too out of hand...He may not want a nuclear war.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:09:30 </td>
   <td style="text-align:left;"> $SPY such a slow gentle crash, calling bottom: 420.69 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:09:23 </td>
   <td style="text-align:left;"> $SPY been super bearish for these past two weeks and closed my put positions around 2pm today but I grabbed some calls at close bc this shit always rips when everyone is bearish. Excited to sell these for the eventual bull trap Monday morning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:09:23 </td>
   <td style="text-align:left;"> $SPY I have my tuition on a 4$ bounce Monday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:09:09 </td>
   <td style="text-align:left;"> $SPY $AAPL $AMZN $TSLA $PLTR 
Officially entered to 🐻 market today from correction 🧙‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:09:06 </td>
   <td style="text-align:left;"> $NVDA The Bear 🐻 likes to eat dead cat bounces. Not hibernating anymore. Don’t fight the Fed. $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:08:37 </td>
   <td style="text-align:left;"> $QQQ $SPY I’ll be honest, I expected a pullback but not the way it’s been happening since the new year. Somewhere I read that Nasdaq sentiment is lower than March 2020 and that’s why every pop is sold. I’m not sure if I should begin shopping/buying the dip now or wait a few more weeks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:08:27 </td>
   <td style="text-align:left;"> $SPY sentiment too bearish, that means we rally Monday :) 
I went share shopping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:08:21 </td>
   <td style="text-align:left;"> $SPY Bitcoin could be under 10k by Monday at this rate. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:08:16 </td>
   <td style="text-align:left;"> $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:08:08 </td>
   <td style="text-align:left;"> $SPY RIDIN WITH BIDEN

Eeeeeeee doggie </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:08:07 </td>
   <td style="text-align:left;"> $SPY $QQQ date dinner for apes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:08:04 </td>
   <td style="text-align:left;"> $SPY this all reminds me of the ‘18 taper tantrum. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:07:52 </td>
   <td style="text-align:left;"> $SPY Gonna throw it out there. Could be wrong. I expected to fill the gap during market, but came after hours. Expecting a relief fall next week. Not sure it sustains, but I didn’t hold outs over the weekend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:07:50 </td>
   <td style="text-align:left;"> $SPY $QQQ 
Have a good weekend everyone. Except for you Bulls. Go fuck yourself &amp;amp; your delionsial conviction that stocks only goes up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:07:31 </td>
   <td style="text-align:left;"> $SPY All bears tonight👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:07:28 </td>
   <td style="text-align:left;"> $SPY How is BTD strategy working out since 2022 started? I don’t like quicksand either. Lol 😝 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:07:23 </td>
   <td style="text-align:left;"> $SPY Everything is tanking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:07:07 </td>
   <td style="text-align:left;"> $SPY $QQQ 
I gotta know right now
Do you love me?
Will you love me forever?
Do you need me?
Will you never leave me?
Will you make me so happy for the rest of my life?
Will you take me away and will you make me your wife?
I gotta know right now!
Before we go any further
Do you love me?
And will you love me forever?

Let me sleep on it
Baby, baby let me sleep on it
Let me sleep on it
And I&amp;#39;ll give you an answer in the morning.

R.I.P. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:07:07 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $SPX 
Being Gods dream is pretty cool. Who woulda thought every possibility would be explored and every thought would be just as valid as any other given enough time to inevitably come to be in another dream. 

Pretty awesome how everything I do to another conscious being I’m actually doing to another version of myself up or down the chain. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:07:05 </td>
   <td style="text-align:left;"> $SPY At least another month or two selling to bring some equilibrium back into the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:06:39 </td>
   <td style="text-align:left;"> $SPY $SOFI $MSFT $TSLA Welcome to the Biden market folks! Get use to red. You wanted Trump gone and he’s gone. You got want you wanted. Enjoy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:06:32 </td>
   <td style="text-align:left;"> $SPY $VOO Just putting this out there to see if im correct later on but my guess is that we test and hold the October low early next week, have a short rally, then roll over to lower lows </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:06:28 </td>
   <td style="text-align:left;"> $SPY f**** off bears!!!!! I’m a buyer…get it down to 300 I have so much cash I can f*** u all! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:06:08 </td>
   <td style="text-align:left;"> $SPY see ya at 380 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:06:07 </td>
   <td style="text-align:left;"> $BBIG shorts didn’t even cover before the weekend because they know the market is fucked $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:05:48 </td>
   <td style="text-align:left;"> $SPY $QQQ Can’t wait for the P/E compression to really kick in after 8 rate hikes in 2022 😂🤣🤣

Get ready for those annual reviews boys and girls. America is about to get a big fucking raise </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:05:42 </td>
   <td style="text-align:left;"> $SPY  $btc.x Not a bitty hater but I like funny. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:05:30 </td>
   <td style="text-align:left;"> $SPY So much of this lately </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:05:21 </td>
   <td style="text-align:left;"> $SPY Obama Tried to Warn Us: ‘Don’t Underestimate Joe’s Ability to F— Things Up’ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:05:17 </td>
   <td style="text-align:left;"> $SPY Damn Joe who made us all buy those SPACs, IPOs and stay-at-home stocks! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:05:17 </td>
   <td style="text-align:left;"> $SPY thank you my hero </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:04:56 </td>
   <td style="text-align:left;"> $SPY 435-436 will get hit on Monday to close that gap. Reversal starts there. Prob will see 450 at one point next week… then down more. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:04:50 </td>
   <td style="text-align:left;"> $SPY Good lord, that double top on Tesla. 👀🔥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:04:44 </td>
   <td style="text-align:left;"> $SPY Every one in America is confident our President will handle a major war with Russia successfully... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:04:42 </td>
   <td style="text-align:left;"> $SPY wow! 420—&amp;gt; 380 next week! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:04:39 </td>
   <td style="text-align:left;"> $SPY $QQQ thought ive seen it all. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:04:30 </td>
   <td style="text-align:left;"> $SPY Inflation has consequences! Wealth destruction </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:04:24 </td>
   <td style="text-align:left;"> $SPY $QQQ oversold conditions - expect a multi-day ripper </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:04:23 </td>
   <td style="text-align:left;"> $SPY Trump will get re-elected if you continue!!  wake up Joe!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:04:14 </td>
   <td style="text-align:left;"> $SPY $QQQ $DWAC It is clear as day: November, when the Republicans will take the House and Senate in a landslide,  cannot come soon enough. 

We can then either impeach Dementia Joe and/or invoke the 25th Amendment, jail Komrade Kamala and Nasty Nancy for treason, and reinstate President Trump to his rightful spot in the oval office. 

Our great country cannot afford to have a dementia patient who is controlled by the Deep State in office. We need President Trump, the greatest since Washington back to save our country and the stock market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:04:00 </td>
   <td style="text-align:left;"> $SPY  
 
Our government is incompetent...always...hard to argue.   
 
On a positive, we&amp;#39;ve never gone full El Salvadorian as a country </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:03:52 </td>
   <td style="text-align:left;"> $SPY Hookers and blow for bears this weekend. We are going up on Monday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:03:40 </td>
   <td style="text-align:left;"> $SPY Beautiful Market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:03:33 </td>
   <td style="text-align:left;"> $SPY all those home buyers buying shit up like its daddys free money. hopefully did not buy on ARM&amp;#39;s. otherwise with 6-8 rate hikes we will have another 2008 in addition to bear markets... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:03:32 </td>
   <td style="text-align:left;"> $SPY You know how these idiot analysts are coming up with their numbers. They are multiplying the S&amp;amp;P earnings by 15 and then 17.  Then they short and spread FUD. They don’t believe their own numbers but it sounds good, regardless of how sophomoric. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:03:24 </td>
   <td style="text-align:left;"> Victory will be ours $SPY 500 EOM. 🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:03:07 </td>
   <td style="text-align:left;"> $SPY Russia Covid Netflix pick one. Hopefully next week we see a bull run after this blood bath </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:03:02 </td>
   <td style="text-align:left;"> $SPY vix keeps going up. This keeps going down in AH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:02:57 </td>
   <td style="text-align:left;"> $SPY Bull logic- “It went down too much so it will to go back up. I better buy yolo calls for Monday!”🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:02:55 </td>
   <td style="text-align:left;"> $SPY perma bears that have been calling for a crash every single day since the stock exchange opened </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:02:34 </td>
   <td style="text-align:left;"> $SPY nowadays got a side chick on side chick
They keep hacking my iPhone
About to get a sidekick @PurpleReign8 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:02:03 </td>
   <td style="text-align:left;"> $SPY $QQQ $VIX $TSLA $AAPL  
 
What a day (and week) in the markets! 
 
- $ 973 Billion traded today alone in US Equities ( $ 690 B was the daily average this week). 
 
- $ 45 Billion traded today alone in US Options ( $ 22 B was the daily average this week). 
 
-------- </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:02:01 </td>
   <td style="text-align:left;"> $SPY Like in any other bear market the bear rallies are some of the best! We have a massive clear cut “Bearish Engulfing” on the WEEKLY chart. I should fill a decent chunk of it next week :) still more downside but we’re ready for the long scalp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:01:56 </td>
   <td style="text-align:left;"> $SPY $NFLX $TSLA $BA $COIN

GREAT DAY BEARS! CLAP IT UP!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:01:49 </td>
   <td style="text-align:left;"> $SPY $450 Monday? Or $442 before going lower? I think definitely will be a pump before going lower </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:01:31 </td>
   <td style="text-align:left;"> $SPY $QQQ this is the very beginning will be a turd for weeks into late February 
No magic V bounce this time
Get out while you can </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:01:12 </td>
   <td style="text-align:left;"> $NFLX $SPY  I’ve been a bear for a very long time but at this price Netflix is a buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:01:05 </td>
   <td style="text-align:left;"> $BTC.X $SPY Who&amp;#39;s gonna be fucked worse in the coming weeks, Ukrainians or Hodlers? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:00:53 </td>
   <td style="text-align:left;"> $SPY Everyone with atleast half a brain knows the asset bubble created by years of quantitative easing, stimulus, and free money is popping. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:00:51 </td>
   <td style="text-align:left;"> $SPY the only issue with looking at historical data and trying to figure out tomorrow and the future.... Is what is going on now is unprecedented. The fed has never been this reckless with rates and their unlimited printer. So you can look at data and try to say well its in a correction but data shows to always buy them ... But data has never had the fed or a bubble of this magnitude. So I think data at this point is useless. 
Goodluck trading and investing all. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:00:50 </td>
   <td style="text-align:left;"> $MRNA who’s the real expert 1 is clearly $SPY the other one gates a psychopath </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:00:38 </td>
   <td style="text-align:left;"> $IWM $SPY $QQQ Oh hey, out of curiosity, where is Aunt Cathy W and Tommy F’ing Lee !!! Paid pumpers….  SMH.  Bye bye for now…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:00:22 </td>
   <td style="text-align:left;"> $SPY When it&amp;#39;s p00t season </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 09:00:21 </td>
   <td style="text-align:left;"> $LINK.X every dump i am reminded of this
$ETH.X $BTC.X $qqq $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:59:55 </td>
   <td style="text-align:left;"> $SPY   We aren’t even close to done.  This turd is still moist.  3 more weeks.  Start averaging in at 385 down to 365 for the bounce. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:59:47 </td>
   <td style="text-align:left;"> $SPY if this doesn’t bounce next week might as well just take it down 90% and start a new bull run all over again. I’d consider selling my kidney to invest if that happened. Probably would load up the 3x levered stuff with it all to. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:59:40 </td>
   <td style="text-align:left;"> $SPY gonna get laid on Monday mean paid. Lol 
444 put. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:59:02 </td>
   <td style="text-align:left;"> $NVDA this is next tesla and zoom and amon and apple of  decade ... 
$385 in no time  
 
$dwac $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:58:41 </td>
   <td style="text-align:left;"> $SPY 442 then lower towards 425 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:58:27 </td>
   <td style="text-align:left;"> $SPY anyone recall furniture.com in 2000? shit started rolling with that and eventually bubble burst. Peleton is that canary. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:57:31 </td>
   <td style="text-align:left;"> $SPY big bounce Monday most likely </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:57:23 </td>
   <td style="text-align:left;"> $SPY Bull traps SET!! $433, then $427, then trap bulls all the way down to $380!!

All support is broken!! First time since Feb 2020 COVID breakout!!

ITS BEARISH FOR SURE!! PUT CITY!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:57:16 </td>
   <td style="text-align:left;"> $SPY How do you solve a labor shortage? 

Crash the crypto market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:57:07 </td>
   <td style="text-align:left;"> $SPY how likely we get a fake rally into FOMC note released then an even bigger rug pull? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:57:07 </td>
   <td style="text-align:left;"> $SPY what a brutal AH… no mercy shown 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:56:23 </td>
   <td style="text-align:left;"> $SPY am I going to see crash of 2022 caused by over leveraged investors?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:56:15 </td>
   <td style="text-align:left;"> $SPY bulls catching the piano </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:56:06 </td>
   <td style="text-align:left;"> latex5e8941ad52b63277540e071597d82749QQQ

$IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:56:05 </td>
   <td style="text-align:left;"> $SPY Momentum stocks after today 

$QQQ $XLK $SOXX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:55:59 </td>
   <td style="text-align:left;"> $SPY just trade what the charts say and shut up about the politics… you pushed the buy button </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:55:55 </td>
   <td style="text-align:left;"> $SPY midterms are coming..I wonder who will win the house and senate this year if market keeps crashing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:55:55 </td>
   <td style="text-align:left;"> $SPY $QQQ ARKK needs to return +26% for a year to be at 0. And today is only January 21st…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:55:48 </td>
   <td style="text-align:left;"> $SPY didnt break lower keltner on weekly for SPX.  Should hit a bottom around here or 4369 ish. Good luck to all. This week was brutal. FUCK JB! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:55:39 </td>
   <td style="text-align:left;"> $SPY wait until Apple and Microsoft fall </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:55:30 </td>
   <td style="text-align:left;"> $SPY stop blaming others👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:55:24 </td>
   <td style="text-align:left;"> $SPY With FOMC Wednesday and the Russia/Ukraine affair, it is risk off next week, till likely after Powell pumps markets. I don&amp;#39;t think he has a choice at this point. Guessing speculative buying starts Wednesday morning. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:55:08 </td>
   <td style="text-align:left;"> $SPY GAP DOWN MONDAY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:55:06 </td>
   <td style="text-align:left;"> $SPY rip market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:55:02 </td>
   <td style="text-align:left;"> $SRNE $SPY $XBI 

Hello ?? We can fix this 👇👇👇

Mount Sinai back up our Nasal Antibodies 

Covid Shield but now one give 2 fcks right?
Our antibodies are not a pill, they can be use in children. No needles </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:54:59 </td>
   <td style="text-align:left;"> $SPY for long term investment( year or two) airlines, service industry and banking looks good. For short term, short everything that fucking moves. I won’t repeat this. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:54:56 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMZN $TSLA how to measure this correction. Take the whole market cap minus 8T powell giveaways. Minus another 10% of clearance. Then watch for bargains accordingly. By then bankruptcies will be looming and banks will be struggling regardless of high rates. MM wants you to believe Banks make money of interest rates. Wrong. They make money by trading a fixed market. GS are so greedy they short their own stock. This is true. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:54:53 </td>
   <td style="text-align:left;"> $SPY oversold, bounce to 452$ Monday then fade </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:54:30 </td>
   <td style="text-align:left;"> $SPY brutal bitches. Any bulls left? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:54:18 </td>
   <td style="text-align:left;"> $BTC.X $SPY $QQQ  Russia declares war, buys the dip, then says “I was kidding uwu” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:54:08 </td>
   <td style="text-align:left;"> $SPY we still bitching? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:54:04 </td>
   <td style="text-align:left;"> $SPY see you all at 460 next week right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:53:56 </td>
   <td style="text-align:left;"> $SPY $tlt $gld I&amp;#39;m cALINg It Now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:53:34 </td>
   <td style="text-align:left;"> $SPY Fauci you motherfucker you’ll pay for this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:53:21 </td>
   <td style="text-align:left;"> $SPY &amp;quot;If your portfolio either tanks or moons depending on the words of one man (JP)... you might have bought a bubble.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:53:21 </td>
   <td style="text-align:left;"> $SPY I usually like to be wined and dined before I get fucked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:53:18 </td>
   <td style="text-align:left;"> $QQQ $SPY The AMC/GME/Crypto craze was a huge indication that the markets were about to crash. 
 
There was too much easy money to be made and it couldn&amp;#39;t last forever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:53:12 </td>
   <td style="text-align:left;"> $SPY billionaires are gonna be richer
Retails are going to get screwed again

Rinse and repeat </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:53:04 </td>
   <td style="text-align:left;"> $SPY no wonder $NFLX sank. Watching the Gabby Petito&amp;#39;s documentary and this rivals anything Netflix has ever produced. Competition is real. That won&amp;#39;t ever regain the amount of market share it had imo </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:52:44 </td>
   <td style="text-align:left;"> $SRNE is an interesting story for sure… 
 $SPY  $XBI </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:52:38 </td>
   <td style="text-align:left;"> $SPY $QQQ still going Down???
Wow

LOLLLL

NOTHING GROWS TO THE SKY.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:52:24 </td>
   <td style="text-align:left;"> $SPY God fucking damn you Fauci my kids have fevers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:52:01 </td>
   <td style="text-align:left;"> $SPY Are we staying above 436 for the weekend? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:50:50 </td>
   <td style="text-align:left;"> $XLF $QQQ $SPY This really isn’t all that bad.. very controlled downtrend IMO. Still sitting on my pile of dry powder but will be looking to make some large buys next week if we see further downside. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:50:33 </td>
   <td style="text-align:left;"> $SPY I imagine this will continue to sink for a while. This is where you get rich folks. Buy as it goes down, buy the bottom, buy the fear. If youre investing, not trading, the next cycle will make you rich. No one gets rich overnight. It takes years. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:50:29 </td>
   <td style="text-align:left;"> $SPY Waiting for Jpow to chillax the market come Wednesday. Relief rally to high 450s after a week or so then the full plunge into February with China &amp;amp; Russia winning in life and the U.S. floundering with the unelected vegetable in office 🤷🏽‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:50:26 </td>
   <td style="text-align:left;"> $AMZN $NFLX $SPY $DIS Amazing callouts by our team this week. Follow for more! Here&amp;#39;s our
Top 3 this week:
AMZN 3050 PUT $5.25 to $190 3751%
DIS 149 PUT $.41 to $10.50 +2460%
NFLX 460 PUT $2.62 to $60.25 2199% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:50:24 </td>
   <td style="text-align:left;"> $SPY $QQQ my account is now all cash. It has $1.53 left </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:50:14 </td>
   <td style="text-align:left;"> $SPY $XBI $SPY 

Ohh nooo panic began ? 👇 we have the Nadal antibodies that can fix this by the way . Covid Drop Sorrento </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:49:51 </td>
   <td style="text-align:left;"> $SPY STOP SELLING! I&amp;#39;M NOT GOING TO STOP UNTIL I FK EVERY BEAR IN HERE </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:49:41 </td>
   <td style="text-align:left;"> $SPY The CIA won&amp;#39;t let the markets dip too much. BULLISH. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:49:36 </td>
   <td style="text-align:left;"> Green Monday?

$SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:49:33 </td>
   <td style="text-align:left;"> $AMZN $NFLX $SPY $DIS Amazing callouts by our team this week. Make sure to follow Here&amp;#39;s our
Top 3:
AMZN 3050 PUT $5.25 to $190 3751%
DIS 149 PUT $.41 to $10.50 +2460%
NFLX 460 PUT $2.62 to $60.25 2199% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:49:31 </td>
   <td style="text-align:left;"> $SPY don’t buy into the fud. Look at this gem published in June 2020 when the SPY was $300. These talking heads are clueless </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:48:39 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM Young Warren Buffet 1962 Interview | Stock Market Crash
https://youtu.be/DnhhR-LxNYg $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:48:37 </td>
   <td style="text-align:left;"> $SPY asshole Powell has been saying &amp;quot;transitory inflation&amp;quot; since February 2020. In November he says well we cant use the word transitory anymore. WTF asshole you have every inch of data and you&amp;#39;re pumping shit like a politician. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:48:12 </td>
   <td style="text-align:left;"> $SPY $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:48:09 </td>
   <td style="text-align:left;"> $AMZN $NFLX $SPY $DIS Amazing callouts by our team this week. Here&amp;#39;s our
Top 3:
AMZN 3050 PUT $5.25 to $190 3751%
DIS 149 PUT $.41 to $10.50 +2460%
NFLX 460 PUT $2.62 to $60.25 2199% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:47:48 </td>
   <td style="text-align:left;"> $SPY One downfall of working from home for 2 years. I just looked at my fingernails lol. Gross!!!

Just been trading, skiing &amp;amp; being a Dad &amp;amp; husband.  Notice I didn’t include work.  This is a permanent vacation for the workaholics out there.  Realized what life is all about. 

Cheers 🍻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:47:47 </td>
   <td style="text-align:left;"> $SPY I think this will have the mother of all melt-ups in the next few weeks. 600 on its way imo. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:47:39 </td>
   <td style="text-align:left;"> $SPY so the mkt ran up more than 50% from COVID lows and everyone freaking out over a 9% pullback..hahahahaha…amateurs. Anyone trading for more than a few years knows how this goes….it’s called efficient markets </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:47:38 </td>
   <td style="text-align:left;"> $SPY let’s agree on one rule, don’t complain about 401k if you are never employed and trading on robinhood. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:47:29 </td>
   <td style="text-align:left;"> $SPY too many who missed 2020 still looking for a deep correction/crash. they probably won’t get it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:47:17 </td>
   <td style="text-align:left;"> $SPY
The next catalyst for the markets should be and probably will be announcement Of  all US companies bring their employees back to work 
Starting with a mask mandates and everything else that came with it we could do it. Oh one more thing Never bet against United States </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:47:07 </td>
   <td style="text-align:left;"> $SPY dont keep throwing your money away... it&amp;#39;s not getting better anytime soon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:46:57 </td>
   <td style="text-align:left;"> $SPY Where&amp;#39;s all the 2 year bulls saying stocks only go up?

Did you blow your account up in 1 week? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:46:50 </td>
   <td style="text-align:left;"> $SPY everyone on Stocktwits bitching like their stock or crypto is the only one down. The whole fucking market and world is down right now stfu </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:46:38 </td>
   <td style="text-align:left;"> $SPY Good job democrats, lovely country your creating here. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:46:27 </td>
   <td style="text-align:left;"> $SPY im pretty pumped to buy dips w this put money. Get that AMD and NVDA. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:46:11 </td>
   <td style="text-align:left;"> $SPY Today I decided to cut my losers and let my winners run. I’m now 100% cash. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:46:10 </td>
   <td style="text-align:left;"> $SPY $QQQ its simple when fed is dovish you buy.. when they are hawkish you sit in cash or buy lotto puts. We might get oversold bounces but ultimately market isn’t going anywhere in 2022.. too many issues that are unfixable </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:45:53 </td>
   <td style="text-align:left;"> $SPY 

They will give you a green Monday and maybe Tuesday too to make you forget about this week. And you will forget because bulls are just large size gold fish. But then, the real punishment will be delivered without mercy. There’s a retracement level in the chart, but I don’t want you to disrespect the bears and celebrate too much. We own you for the next 2-3 years! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:45:47 </td>
   <td style="text-align:left;"> $SPY Any dips are temporary. 🐂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:45:30 </td>
   <td style="text-align:left;"> $SPY Vote Camacho for president, 2024. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:45:01 </td>
   <td style="text-align:left;"> The end is coming for FAANG valuations - wow just brutal annihilating $amzn $googl $NFLX  
 
$spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:44:42 </td>
   <td style="text-align:left;"> $SPY BULL Market next week? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:43:51 </td>
   <td style="text-align:left;"> $SPY BIDEN KILLED IT </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:43:39 </td>
   <td style="text-align:left;"> $SPY bear markets really bring the community together though.  Most sarcastic generations of all time and you think they won’t shrug this off, watch Gen z and Millenial investors buy every single dip the entire way down.  Then Diamond hands to victory in 3-5 years. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:43:33 </td>
   <td style="text-align:left;"> $SHOP Unreal the SEC ever let some of these get as out of control as they did. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:43:13 </td>
   <td style="text-align:left;"> $SPY Snugged the 200 SMA. Expecting a powerful retest towards previous highs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:43:08 </td>
   <td style="text-align:left;"> $SPY unless you started working and contributing to 401k from two days ago,.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:42:39 </td>
   <td style="text-align:left;"> $SPY forget the dip y’all should be buying ammo 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:42:34 </td>
   <td style="text-align:left;"> $SPY bulls mindset </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:42:34 </td>
   <td style="text-align:left;"> $SPY nice close bulltards lol 😆 😂 😄 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:42:10 </td>
   <td style="text-align:left;"> $SPY $QQQ cnbc is funny.. at 390-400 they were all saying buy .. “aapl going to 200” now they all saying sell lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:41:55 </td>
   <td style="text-align:left;"> $SPY remember when we went to all time high 70 times during a fake president and during a “pandemic” so year we are heading down to 2020 feb lows </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:41:51 </td>
   <td style="text-align:left;"> $SPY If only democrats cared about the sovereignty of the United States as much as they cared about the sovereignty of Ukraine.  🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:41:30 </td>
   <td style="text-align:left;"> $SPY bye retirement $ nice knowing u </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:41:26 </td>
   <td style="text-align:left;"> $NRZ Every time the market corrects and this dips, people freak out. Go look at the chart and then look at the posts on this site 12-16 to 12-20. This is about to set up exactly as last time.  When I look at the $SPY this week on 4 hour chart.....I am just glad NRZ didnt get to $10, lmao.....yet!! 
 
On another note. My daughter died 12-15-21 at about 9am...I was looking at the chart on a 4 hour time frame, and I had a tear in my eye when I seen the 9am candle on the 4hr for 12-15. God is good...  🙏🙏🙏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:41:06 </td>
   <td style="text-align:left;"> $SPY new president next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:40:59 </td>
   <td style="text-align:left;"> $SPY losing my mind right now 😳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:40:54 </td>
   <td style="text-align:left;"> $SPY that bastard Powell is going to speak next week to try to pump the markets. thats not supposed to be his job. feds are not here to pump the markets. asshole. dont buy this shit. market veterans are calling 40% drop. this is bear market. covid was a panic crash. this is a thoughtful systemic problem.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:40:40 </td>
   <td style="text-align:left;"> $SPY The biggest Double top in History and the biggest scam in history? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:40:36 </td>
   <td style="text-align:left;"> This is the month to buy $SPY $ETH.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:39:44 </td>
   <td style="text-align:left;"> $SPY GO JOE!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:39:34 </td>
   <td style="text-align:left;"> $SPY rally next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> SPY </td>
   <td style="text-align:left;"> 2022-01-22 08:39:25 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $BTC.X $ETH.X Joe Biden: making 0.02% savings accounts GREAT AGAIN!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:40:47 </td>
   <td style="text-align:left;"> The only way to hedge against Stocks &amp;amp; Crypto it&amp;#39;s with NFTs $SPY $ETH.X $QQQ $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:38:05 </td>
   <td style="text-align:left;"> $LCID $SPY $DJIA $QQQ $NASDAQ - it absolutely blows my mind that two weeks ago everyone was “diamond hands”, “apes”, “buying lambos”, etc… yet now, because the news and our joke of a White House administration tells you otherwise, people are running for the hills screaming Armageddon, Recession, Depression. Hell.. I even heard people talking about Russia invading Ukraine and we barely do sh*t with either of those countries. This is the whole reason that senile, clown got elected in the first place… because people take any and everything they hear from the media as gospel and don’t think for themselves. Has your life so substantially changed in the last 2-3 weeks that it makes sense to devalue your assets 10-20%?!?! The answer is no… these clowns are propagating fear to profit at your expense based on ignorance, just as they do in politics!!!l </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:37:18 </td>
   <td style="text-align:left;"> $SPY $QQQ $UUP $TLT
Weekend Market Recap for Friday1/21/2022 for #Stocks #Bitcoin #Gold and #Silver
https://youtu.be/0XbfeD1bKu4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:36:43 </td>
   <td style="text-align:left;"> $QQQ is correction done ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:33:11 </td>
   <td style="text-align:left;"> $SPY McClellan Oscillator a reliable tool for judging overbought and over sold mkts.  We are near the lowest level in 2 yrs. Only time lower was Covid crash and Dec 2018 correction. Monday or Tuesday could be the turn around days.. atleast the Breadth picking up. $DIA $TSLA $QQQ $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:30:16 </td>
   <td style="text-align:left;"> Ditch the Sub-Services! How To Make Your Own Winning Trading System!

$SPY $QQQ $IWM $ES_F $DIA

https://www.chartlearning.com/2021/12/how-to-create-a-stock-trading-system.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:26:16 </td>
   <td style="text-align:left;"> $QQQ $SPY all I have to say is election’s will be all republicans democrats set themselves up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:25:10 </td>
   <td style="text-align:left;"> $SPY $QQQ pawn shop and payday loans booming today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:23:40 </td>
   <td style="text-align:left;"> $QQQ we need one more bubble to make back these losses </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:22:58 </td>
   <td style="text-align:left;"> $IWM $QQQ $SPY 

Bang 💥 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:21:37 </td>
   <td style="text-align:left;"> $SPY $QQQ people aren&amp;#39;t even going to work anymore 
The ones that have jobs complain if they have to physically be there lol
This generation is pathetic
Economy is pathetic and stock market has been a smartphone slot machine for teens!
This online casino will end like reddit ponzi games </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:21:37 </td>
   <td style="text-align:left;"> $QQQ $SPY $VIX   
 
This is a pretty good one:))) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:21:35 </td>
   <td style="text-align:left;"> $QQQ $UVXY https://youtu.be/Ia5Uh-kj3C0 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:21:13 </td>
   <td style="text-align:left;"> $CFLT we can only look at past data and have to extrapolate…this week has been one of the worst in like 2 decades….be greedy when other are afraid $QQQ $VGT $HOOD $AMPL 

$MOB </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:21:10 </td>
   <td style="text-align:left;"> The Stock Markets wont bounce back they way they did in 2020, specially with the FED shrinking their Balance sheet and raising rates -- Normalize this $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:21:05 </td>
   <td style="text-align:left;"> $QQQ   Where I short lambo? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:20:25 </td>
   <td style="text-align:left;"> $QQQ Isn’t they wanna shake out before Earning season and Fed meeting? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:20:19 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
A sucessful president does not drag his country into war.  
  
He takes care of his own house before worrying about others!  
  
Fuck Joe Biden and his &amp;quot;war with Russia&amp;quot; rhetoric! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:19:55 </td>
   <td style="text-align:left;"> $QQQ $Spy $NASDAQ 
Here’s to all the D F’s who worship the God Fauci and the CDC . 

https://newspunch.com/cdc-finally-admits-natural-immunity-far-superior-to-jabbed-immunity-alone/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:17:55 </td>
   <td style="text-align:left;"> $QQQ mark this post, feds will say, not rasing rates for a few more months bc covid has hit it&amp;#39;s peak and will dissipate. This will cause labor shortage to pick up stem, causing supply issues to decrease. Once this happens, inflation will retreat and we will reevaluate raising rates. 

JK JK jk...I have no idea what&amp;#39;s going to happen bc whales control the market and we just play by their rules. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:17:34 </td>
   <td style="text-align:left;"> $QQQ got a feeling it pops monday like 5% and then drops again during fed meeting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:17:17 </td>
   <td style="text-align:left;"> $SPY $QQQ Biden should be wearing an oxygen mask instead of a N95 maybe he can think better </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:16:16 </td>
   <td style="text-align:left;"> $SPY $QQQ $ARKK I have been chart reading for the last two hours and I have come to this conclusion on this massacre. I would like honest second opinions: SPY broke the neckline of a HS pattern at $450. The bottom of that pattern plays out at $430. I am looking to SPY to lead us out of this so that is why I am focusing on SPY chart more than QQQ.  The $430 bottom of HS pattern for SPY also happens to be long term support going back to July AND is also SPY 50 DMA on WEEKLY. So, if on Monday morning SPY goes down another 1.5% and hits around $430, completing HS bottom pattern AND hits 50 DMA on WEEKLY, I am buying and taking my damn chances. That makes sense to me. I will buy Apple at $157 and maybe a few QQQ. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:16:15 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA $BTC.X 
 
Poor Millennials 
 
They were once again take advantage off as JPOW leveraged the world-wide pandemic to intentionally inflate asset prices so Boomers could hand off bags at all time highs and valuations just as they were retiring en masse. 
 
Boomers know the stock market game and took the opportunity to lock in lifetime gains and hand off their bags to Millennials at OBVIOUSLY overvalued levels. 
 
So who are Millennials going to convince to take their bags when they are ready to retire? GenZ? Good luck!...they just went through the same scam with you. 
 
Boomers are relentless in taking advantage of the world around them for their own personal gain. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:15:56 </td>
   <td style="text-align:left;"> $QQQ Let us remember... besides this shit show, that Democracy and Freedom are in the balance. A fascistic coup was prevented last Jan 6th and the forces of fascism are gathering to dismantle anything Democratic comes 2024.
Europe is now mostly and proudly atheistic i.e secular and social democratic... that is the basic needs of Maslow&amp;#39;s hierarchy of needs like shelter, safety and food as well as basic healthcare are provided, and way more efficiently than the redundant and inefficient oligarchy and special interest controlled &amp;quot;Capitalism&amp;quot; in America. The later is now nothing more than Corporations vs. The People. Not Corporations fighting among themselves to bring the best products and services to the people. Regulatory capture is everywhere: The scams of Ed and Med where higher education and healthcare are a disgrace of elitism and profit making on the misery of others. Front Line Assembly put it nicely... let the American Dream not be the world&amp;#39;s nightmare.

https://www.youtube.com/watch?v=FSJ0FNFTaz4 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:15:28 </td>
   <td style="text-align:left;"> $QQQ Even the Dot Com crash bounced on the 50 EMA, meanwhile this market just slices right through. This is going to be really painful for bulls. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:15:25 </td>
   <td style="text-align:left;"> $SPY $QQQ January Effect reminding me of that time I bought a nice vacation home and, instead of moving in, burned it straight to the ground. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:15:10 </td>
   <td style="text-align:left;"> At this pace market is pricing in doomsday 👀😂 $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:14:21 </td>
   <td style="text-align:left;"> $SPY $QQQ Do y’all remember when that happened? Good times. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:14:16 </td>
   <td style="text-align:left;"> $QQQ do yourself a favor don’t buy anything until earning season is over and we get a lay at the land. It’s better to join the party late than losing money. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:14:07 </td>
   <td style="text-align:left;"> $SPY Everyone sees Netflix post-percent, -22?

Now, take tech stocks ERs and subtract 10-20% from share price of the 26% of stocks in the Nasdaq.... $NDX

Love that song: You Ain&amp;#39;t Seen Nothing Yet

Here&amp;#39;s something, you won&amp;#39;t forget. BABY! You ain&amp;#39;t seen nothing yet. You ain&amp;#39;t...

God bless your trades.

Do own DD

$QQQ $SOXX $XLK </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:12:01 </td>
   <td style="text-align:left;"> $QQQ possible $100 qqq nex week? I am all in sqqq now! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:11:03 </td>
   <td style="text-align:left;"> $AAPL The Fed is your friend until it isn’t. Which is now! Rug pull! $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:09:56 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $SPX 
War on drugs, war on terrorism, war on other countries. 

Maybe a war on homelessness should be tried. Ahh wait. No money in that never-mind. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:09:06 </td>
   <td style="text-align:left;"> $NVDA The Bear 🐻 likes to eat dead cat bounces. Not hibernating anymore. Don’t fight the Fed. $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:08:37 </td>
   <td style="text-align:left;"> $QQQ $SPY I’ll be honest, I expected a pullback but not the way it’s been happening since the new year. Somewhere I read that Nasdaq sentiment is lower than March 2020 and that’s why every pop is sold. I’m not sure if I should begin shopping/buying the dip now or wait a few more weeks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:08:07 </td>
   <td style="text-align:left;"> $SPY $QQQ date dinner for apes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:07:50 </td>
   <td style="text-align:left;"> $SPY $QQQ 
Have a good weekend everyone. Except for you Bulls. Go fuck yourself &amp;amp; your delionsial conviction that stocks only goes up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:07:07 </td>
   <td style="text-align:left;"> $SPY $QQQ 
I gotta know right now
Do you love me?
Will you love me forever?
Do you need me?
Will you never leave me?
Will you make me so happy for the rest of my life?
Will you take me away and will you make me your wife?
I gotta know right now!
Before we go any further
Do you love me?
And will you love me forever?

Let me sleep on it
Baby, baby let me sleep on it
Let me sleep on it
And I&amp;#39;ll give you an answer in the morning.

R.I.P. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:07:07 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $SPX 
Being Gods dream is pretty cool. Who woulda thought every possibility would be explored and every thought would be just as valid as any other given enough time to inevitably come to be in another dream. 

Pretty awesome how everything I do to another conscious being I’m actually doing to another version of myself up or down the chain. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:05:48 </td>
   <td style="text-align:left;"> $SPY $QQQ Can’t wait for the P/E compression to really kick in after 8 rate hikes in 2022 😂🤣🤣

Get ready for those annual reviews boys and girls. America is about to get a big fucking raise </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:04:39 </td>
   <td style="text-align:left;"> $SPY $QQQ thought ive seen it all. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:04:24 </td>
   <td style="text-align:left;"> $SPY $QQQ oversold conditions - expect a multi-day ripper </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:04:14 </td>
   <td style="text-align:left;"> $SPY $QQQ $DWAC It is clear as day: November, when the Republicans will take the House and Senate in a landslide,  cannot come soon enough. 

We can then either impeach Dementia Joe and/or invoke the 25th Amendment, jail Komrade Kamala and Nasty Nancy for treason, and reinstate President Trump to his rightful spot in the oval office. 

Our great country cannot afford to have a dementia patient who is controlled by the Deep State in office. We need President Trump, the greatest since Washington back to save our country and the stock market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:02:40 </td>
   <td style="text-align:left;"> $QQQ yes I agree with everybody it&amp;#39;s oversold, but why it will go up?  
when the fed screws the market with higher interest rate. it&amp;#39;s done. and yes I miss Trump. This silly guy (Biden) doesn&amp;#39;t care and maybe he&amp;#39;s sleeping like a kid now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:02:10 </td>
   <td style="text-align:left;"> $QQQ short qqq is real gem </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:02:05 </td>
   <td style="text-align:left;"> $QQQ Simulated Weekly $352.0 CALLS for Monday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:02:03 </td>
   <td style="text-align:left;"> $SPY $QQQ $VIX $TSLA $AAPL  
 
What a day (and week) in the markets! 
 
- $ 973 Billion traded today alone in US Equities ( $ 690 B was the daily average this week). 
 
- $ 45 Billion traded today alone in US Options ( $ 22 B was the daily average this week). 
 
-------- </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:01:31 </td>
   <td style="text-align:left;"> $SPY $QQQ this is the very beginning will be a turd for weeks into late February 
No magic V bounce this time
Get out while you can </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:00:41 </td>
   <td style="text-align:left;"> $QQQ LMAO they close it at the very low. Savages </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:00:38 </td>
   <td style="text-align:left;"> $IWM $SPY $QQQ Oh hey, out of curiosity, where is Aunt Cathy W and Tommy F’ing Lee !!! Paid pumpers….  SMH.  Bye bye for now…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:00:32 </td>
   <td style="text-align:left;"> $QQQ Monday is going to be so green </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 09:00:21 </td>
   <td style="text-align:left;"> $LINK.X every dump i am reminded of this
$ETH.X $BTC.X $qqq $spy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:59:43 </td>
   <td style="text-align:left;"> $NVDA Unusual Option Activity is loaded $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:59:22 </td>
   <td style="text-align:left;"> $QQQ I’ve been on both sides of the $QQQ train but this time I’m glad I called it right. 

Next time might not be so lucky. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:58:43 </td>
   <td style="text-align:left;"> $QQQ it&amp;#39;s been very accurate so far. Crypto crashes, short Nasdaq and vice versa. Don&amp;#39;t tell me they are not related. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:56:06 </td>
   <td style="text-align:left;"> latex5e8941ad52b63277540e071597d82749QQQ

$IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:56:05 </td>
   <td style="text-align:left;"> $SPY Momentum stocks after today 

$QQQ $XLK $SOXX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:55:55 </td>
   <td style="text-align:left;"> $SPY $QQQ ARKK needs to return +26% for a year to be at 0. And today is only January 21st…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:54:56 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMZN $TSLA how to measure this correction. Take the whole market cap minus 8T powell giveaways. Minus another 10% of clearance. Then watch for bargains accordingly. By then bankruptcies will be looming and banks will be struggling regardless of high rates. MM wants you to believe Banks make money of interest rates. Wrong. They make money by trading a fixed market. GS are so greedy they short their own stock. This is true. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:54:18 </td>
   <td style="text-align:left;"> $BTC.X $SPY $QQQ  Russia declares war, buys the dip, then says “I was kidding uwu” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:54:13 </td>
   <td style="text-align:left;"> $QQQ I don’t typically buy after hours but buying some for a swing trade on Monday. It’s hilarious that it’s down AH, rsi says bounce coming Monday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:53:28 </td>
   <td style="text-align:left;"> $QQQ i feel bad for anyone that sold or had short term calls. Next week we kick off the recovery turnaround. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:53:18 </td>
   <td style="text-align:left;"> $QQQ $SPY The AMC/GME/Crypto craze was a huge indication that the markets were about to crash. 
 
There was too much easy money to be made and it couldn&amp;#39;t last forever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:52:38 </td>
   <td style="text-align:left;"> $SPY $QQQ still going Down???
Wow

LOLLLL

NOTHING GROWS TO THE SKY.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:50:50 </td>
   <td style="text-align:left;"> $XLF $QQQ $SPY This really isn’t all that bad.. very controlled downtrend IMO. Still sitting on my pile of dry powder but will be looking to make some large buys next week if we see further downside. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:50:24 </td>
   <td style="text-align:left;"> $SPY $QQQ my account is now all cash. It has $1.53 left </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:50:23 </td>
   <td style="text-align:left;"> $QQQ 50% correction coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:50:09 </td>
   <td style="text-align:left;"> $QQQ markets are crashing </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:50:07 </td>
   <td style="text-align:left;"> $QQQ its over guys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:49:50 </td>
   <td style="text-align:left;"> $QQQ 

340 bounce
Bull trap 
320 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:49:06 </td>
   <td style="text-align:left;"> $DIA $QQQ Watching that $350 level closely on Nasdaq and 200 day MA on Dow like a hawk 👁️👁️🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:48:39 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM Young Warren Buffet 1962 Interview | Stock Market Crash
https://youtu.be/DnhhR-LxNYg $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:47:58 </td>
   <td style="text-align:left;"> $SQQQ selling my SQQQ  into the AH melt up. Expecting a market rally next week after today&amp;#39;s high volume capitulation, but ready to buy back on Monday if the $QQQ breaks the 350 level. But hard to argue with a quick 22%. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:46:10 </td>
   <td style="text-align:left;"> $SPY $QQQ its simple when fed is dovish you buy.. when they are hawkish you sit in cash or buy lotto puts. We might get oversold bounces but ultimately market isn’t going anywhere in 2022.. too many issues that are unfixable </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:45:41 </td>
   <td style="text-align:left;"> $QQQ Blaming Biden for stock market crash is insane he did not get this Country in Debt The Orange do Nothing Trump did </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:45:28 </td>
   <td style="text-align:left;"> $QQQ ✅ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:43:23 </td>
   <td style="text-align:left;"> $QQQ OVER 3% ON A DAY ... now imagine a few days on the row like that ... can you handle it ... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:43:10 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:42:10 </td>
   <td style="text-align:left;"> $SPY $QQQ cnbc is funny.. at 390-400 they were all saying buy .. “aapl going to 200” now they all saying sell lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:39:29 </td>
   <td style="text-align:left;"> $QQQ The high for this month was $402.  Just starting to rollover so strap in folks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:39:25 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $BTC.X $ETH.X Joe Biden: making 0.02% savings accounts GREAT AGAIN!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:38:16 </td>
   <td style="text-align:left;"> $SPY $SPX $QQQ 

Papa Powell will save this market on Wednesday. Huge freaking rally on Thursday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:37:09 </td>
   <td style="text-align:left;"> $SPY $QQQ $PTON PTON (Peloton) Stock SELL OFF! JIM CRAMER SAID BUY!
https://youtu.be/2jddO1K57io </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:36:09 </td>
   <td style="text-align:left;"> $QQQ 

Bears  posting are hilarious 🤣🤣🤣

Oh ……SUDDENLY they FOUND a few bucks to short </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:35:56 </td>
   <td style="text-align:left;"> $SPY $QQQ down another dollar after hours </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:35:48 </td>
   <td style="text-align:left;"> $PLTR Getting clocked for sure. Yet I wonder if all the negatives around the number of large government contracts and &amp;quot;lack of&amp;quot; smaller commercial contracts is ultimately a floor. Long term stable mega contracts may ultimately be salvation in vol environment as companies rethink business. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:35:30 </td>
   <td style="text-align:left;"> $SPY $QQQ 
RIP to the big man.
https://youtu.be/C11MzbEcHlw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:35:12 </td>
   <td style="text-align:left;"> $QQQ I&amp;#39;m sorry to say but this isn&amp;#39;t no normal dip I&amp;#39;m a bull and this is iffy I think we will bottom in the 310 range imho </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:34:16 </td>
   <td style="text-align:left;"> $BTC.X $SPY $QQQ $PBF.X  when the dark comes crashing through, when you need a friend to carry you, and when you broken on the ground hedge funds will sell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:34:00 </td>
   <td style="text-align:left;"> $QQQ heading for $225 boys </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:32:18 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:32:06 </td>
   <td style="text-align:left;"> $SPY $QQQ hate to say it but this man was right!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:31:07 </td>
   <td style="text-align:left;"> $BTC.X $DJIA $QQQ https://www.yahoo.com/news/dam-syria-no-strike-list-131742146.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:28:41 </td>
   <td style="text-align:left;"> $SPY biggest bull trap of the year setting up at 456-457 level next week. 

You survive that and next 2 weeks and you will be fine for the year. 

Buckle up!

$NDX $VIX $QQQ $IWM </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:28:03 </td>
   <td style="text-align:left;"> $BTC.X $SPY $QQQ $DIA 

$6 Trillion in Stimulus and the bull market is over in one year???????

Normally bullmarkers run for 5 to 8 years. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:27:43 </td>
   <td style="text-align:left;"> $BTC.X $SPY $QQQ $DIA 
 
Actor and superyacht enthusiast Leonardo DiCaprio told Deadline planet Earth has “literally” nine years left on its “ticking clock,” and that “we should not have any elected leaders, on a state level, on a city level, or a national level that don’t listen to science.” 
 
 
I love how his Carbon footprint is probably that of 100 people </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:26:04 </td>
   <td style="text-align:left;"> Close the after hour market already! $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:21:57 </td>
   <td style="text-align:left;"> $QQQ My prediction for Monday is the market either goes up or it goes down. Hope that helps </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:21:00 </td>
   <td style="text-align:left;"> $QQQ Russia invades - Red Monday. If not - Green

*A minor incursion is an invasion </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:20:25 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA you get what you voted for. Let&amp;#39;s go Brandon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:18:18 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM Monetary Policy you say? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:17:57 </td>
   <td style="text-align:left;"> $QQQ $SPY $BTC.X 

Letting go gives us freedom, and freedom is the only condition for happiness. If, in our heart, we still cling to anything - anger, anxiety, or possessions - we cannot be free.

Thich Nhat Hanh </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:17:55 </td>
   <td style="text-align:left;"> $QQQ this is way too funny </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:17:49 </td>
   <td style="text-align:left;"> $BTC.X $ETH.X $QQQ $PLTN 

BRANDON  and Dems economy enjoy the pain!!

Cheers 🥂 

Where’s no mask 😷 DeSantis </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:17:32 </td>
   <td style="text-align:left;"> $QQQ bottom predictions? Let’s hear em </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:16:55 </td>
   <td style="text-align:left;"> $QQQ Ever wondered how Millennials could survive the Great Depression? Well, wonder no more, it&amp;#39;s about to be reality. Too entitled to do hard labor, but at least they can use their worthless diplomas as toilet paper. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:15:23 </td>
   <td style="text-align:left;"> $BTC.X $SPY $QQQ  everything is down… stocks, crypto, self esteem, my d! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:15:18 </td>
   <td style="text-align:left;"> $SPY $AIKI $UAMY $QQQ $DATS What fucking day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:14:41 </td>
   <td style="text-align:left;"> $QQQ don&amp;#39;t worry we&amp;#39;ll reach a new high in about 10 years. Just hold. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:14:13 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $AAPL $TSLA  
 
Boomers doing what Boomers do when the market starts to crash. 
 
Find a war! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:13:49 </td>
   <td style="text-align:left;"> $SHOP $SPY $QQQ $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:12:55 </td>
   <td style="text-align:left;"> $QQQ at this point this is all on Joe Biden </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:12:16 </td>
   <td style="text-align:left;"> $QQQ $SPY $DJIA $BTC.X 
I am a Muslim, but I want Trump back in the office. All the gains in the past two years are officially gone. One more red day and I will start losing money </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:11:34 </td>
   <td style="text-align:left;"> $QQQ Bulls still in denial. The selloff isn&amp;#39;t even close to being over </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:11:15 </td>
   <td style="text-align:left;"> $QQQ $SPY 

These ❄️UNFUCKED INSECTS are STILL selling INDEXES like qqq under 351 right now 

Thought THEY SOLD THEIR CLIENTS MONEY AT THE ABSOLUTE LOWS/CLOSE👍🏼
running out to their mistress 💋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:10:35 </td>
   <td style="text-align:left;"> $QQQ $SPY we are due for a bounce next week for a bit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:10:08 </td>
   <td style="text-align:left;"> $QQQ 

SERIOUSLY 

These ❄️UNFUCKED INSECTS are STILL selling INDEXES like qqq under 351 right now 

Thought THEY SOLD THEIR CLIENTS MONEY AT THE ABSOLUTE LOWS/CLOSE👍🏼
running out to their mistress 💋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:09:08 </td>
   <td style="text-align:left;"> $AMC $SPY $QQQ 

🦧 🍌🪤 🦧 🍌🪤 🦧 🍌🪤 🦧 🍌🪤

“APE TRAP” COMING TO THEATRES 

SOON....

🦧 🍌🪤 🦧 🍌🪤 🦧 🍌🪤 🦧 🍌🪤 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:08:58 </td>
   <td style="text-align:left;"> $QQQ  Anyone sorry for voting sleepy in the last election. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:08:07 </td>
   <td style="text-align:left;"> $SPY $QQQ $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:07:41 </td>
   <td style="text-align:left;"> $SPY $QQQ Not a great week but next week should be much better, let&amp;#39;s enjoy the weekend and we will probably see some green when we log onto our brokerage account next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:07:09 </td>
   <td style="text-align:left;"> $QQQ Biden Variant destroying the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:06:47 </td>
   <td style="text-align:left;"> $SPY  sank much more than we thought and we lost some $$$ as it was left on the table.  $QQQ too. 
 
Panic selling and forced selling was the picture today.  Fear of loss was rampant but why would we be so inclined to exit at near lows? Ah, because some did not have any control over it. Others sold their stocks wholesale. 
 It is painful with the losses but that pain allows others flush with cash to cherry pick there fave profitable cos. Patience does pay on the buy side. 
 
Many $$$ mgrs got out of the markets back in November and since then many stocks were eroding seemingly for no reason but there was a reason.  The froth was obvious and many just ignored it. It would have been better to exit at highs, not lows but that is what Retail and others do! 
 
The future is in limbo?  Maybe not. We are very resilient where markets are concerned. Plenty of stealth accumulation took place all the way down. Fear is deadly. 
 
I will be mopping the Blood from the Streets tonite! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:05:27 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
I&amp;#39;m really liking the 4200 and 4000 levels 
 
I&amp;#39;m a buyer there. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:04:59 </td>
   <td style="text-align:left;"> $SPY $QQQ  $TNX  kind of funny that the talk of rate hikes has pushed rates up almost .25% In January. Still near record lows... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:03:24 </td>
   <td style="text-align:left;"> $SOFI Holding 12000 shares here 💪 $TSLA $LCID $NIO $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:02:57 </td>
   <td style="text-align:left;"> $Open lmao .. #throwback $arkk $spy $iwm $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:02:43 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ  
Not the worst close for Tesla.  We completely filled an important gap, reached the critical support line, and there&amp;#39;s a massive inverse head &amp;amp; shoulders forming on the 4 hour.. deliveries are up 70% from last year, and earnings report will be 🔥.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:01:52 </td>
   <td style="text-align:left;"> $BTC.X $QQQ $SPY How am I supposed to enjoy the playoffs with all of this BS going on? 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:01:15 </td>
   <td style="text-align:left;"> $QQQ $SPY bulls saying &amp;quot;if $BTC.X can survive, they we can.&amp;quot; What a thesis. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:00:55 </td>
   <td style="text-align:left;"> $QQQ $SPY  Donald Stonks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:00:41 </td>
   <td style="text-align:left;"> $QQQ who else feels like puking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 08:00:04 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA real investors know we’re in for a 10-15% correction here. Back to pre covid baby! Lets grow organically this time </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:59:51 </td>
   <td style="text-align:left;"> $QQQ Bulls every day this week: &amp;quot;It&amp;#39;s going to bounce.&amp;quot; </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:58:20 </td>
   <td style="text-align:left;"> $QQQ the end of Biden and the Democrats , the biggest driver of inflation will be rate hikes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:57:45 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $NASDAQ https://youtu.be/Qhi7cwW1_Es </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:57:39 </td>
   <td style="text-align:left;"> $SPY $QQQ these don&amp;#39;t follow latexafad79a548276426b29dbb33a0dd8d4bAA
UPS
$SOXS (calls) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:57:12 </td>
   <td style="text-align:left;"> $QQQ What do we think is the next suport level? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:56:57 </td>
   <td style="text-align:left;"> $TLT $QQQ 20 week correlation which can be predictor of corrections. observed last year and maybe it was delayed? interpret how you will </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:55:58 </td>
   <td style="text-align:left;"> $SPY To charts to ponder this week end
Weekly Ichimoku.  Tgt 420. $DIA $QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:55:33 </td>
   <td style="text-align:left;"> $SPY $BTC.X $QQQ  is the Santa Rally over? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:55:21 </td>
   <td style="text-align:left;"> $QQQ latexdc69415a84b72ce68e55632a28e87840QQQ down 11.7%
$DJIND down 5.7% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:52:15 </td>
   <td style="text-align:left;"> $QQQ Nasdaq tumbles 2% Friday, notches worst week since 2020 and falls deeper into correction territory

https://www.cnbc.com/2022/01/20/stock-market-futures-open-to-close-news.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:51:56 </td>
   <td style="text-align:left;"> $SPY $QQQ — Roots flippin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:51:55 </td>
   <td style="text-align:left;"> $QQQ $SPY WAWW Bears still saying gap down 😂 dumb greedy bears will be trap … Reversal coming soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:51:49 </td>
   <td style="text-align:left;"> 2 Technical Indicators That Show The Stock Market Could Be In Store For More Pain

$QQQ $SPY  

https://m.benzinga.com/article/25168718 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:51:30 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:50:55 </td>
   <td style="text-align:left;"> $qqq $NDX smart sounding folks (who I presume sniff their own farts) often say that oversold things can always get more oversold. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:50:25 </td>
   <td style="text-align:left;"> $QQQ $SPY  Gap down after Russia levels Ukraine this weekend then rockets before more 🩸 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:49:39 </td>
   <td style="text-align:left;"> Watch $QQQ stock analysis  after today&amp;#39;s  meltdown 

https://youtu.be/yXMoTMd9U9k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:49:27 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ  asking for a friend, he looking for that flavor. Where can he buy? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:46:59 </td>
   <td style="text-align:left;"> $HOOD $FUBO $SPY $QQQ $HPIL  

I bought the dip.. AGAIN. 

I guess I just love pain. 

F*** the bears and the shorts at this point. 
Greed goes BOTH ways you know </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:46:57 </td>
   <td style="text-align:left;"> $QQQ calls monday🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:46:55 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
Bears finally seeing green in their account...lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:46:52 </td>
   <td style="text-align:left;"> $QQQ 
Until market gets detached from the FAANG(T) meaning crash these fuckers, we’re fucked </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:46:43 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ I’m not selling and you can’t make me. Poor people sell low. I’d rather buy low, thx. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:46:00 </td>
   <td style="text-align:left;"> $SPY $QQQ  Any educated guesses on how we are looking next week? 
Will it turn around or do we continue to bleed? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:45:35 </td>
   <td style="text-align:left;"> $SPY $QQQ I&amp;#39;m going to need another 10% drop to be satisfied. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:45:28 </td>
   <td style="text-align:left;"> $MSFT $QQQ $AMZN Microsoft ER on Tuesday. Our next hope to stop the bleeding. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:43:58 </td>
   <td style="text-align:left;"> $QQQ given how oversold everything is, the high volume today, and where we stopped, this is my current working theory. Ready to throw it out the window on Monday of course haha. 
 
But if we get a relief rally, moving up to that right shoulder position is a move of 9.5%. 
 
$ENPH </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:43:43 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWN Don&amp;#39;t ever believe the words that rates where &amp;quot;build in&amp;quot; to the prices </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:43:39 </td>
   <td style="text-align:left;"> $SPY $QQQ   Crypto Money moving to quality stocks very soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:43:03 </td>
   <td style="text-align:left;"> $QQQ what happens if MSFT, AMZN, AAPL and TSLA all go down 10-20%🙈 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:42:44 </td>
   <td style="text-align:left;"> $QQQ Hmmmm lets see ....... 
 
Shortie beartard bozos celebrating a 10%drop after a 200% rise ... 
 
Yup, makes total sense ... LMFAO 
 
Still in cash </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:41:52 </td>
   <td style="text-align:left;"> $QQQ if $MSFT reports great earnings next tuesday, will they still sell into the rally? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:41:24 </td>
   <td style="text-align:left;"> $QQQ $SPY lots of selling for a Friday AH…. $BTC.X $ETH.X probably not helping. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:41:11 </td>
   <td style="text-align:left;"> $XBI $QQQ it’s funny that you all work with your charts and history … that does not work 🤦🏼‍♂️😂😂😂 here are criminal individuals in full control …. They give a shit on your charts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:39:09 </td>
   <td style="text-align:left;"> $QQQ pos machines! Nothing and i mean nothing has changed in the marker between now and the start of this month. Fed at most will raise rates .25% or might not raise at all. This pull back is BS. Oversold!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:36:16 </td>
   <td style="text-align:left;"> Where is the 1987 crash talk? There isn’t any….the set up is there and I’ll be a buyer.  $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:36:03 </td>
   <td style="text-align:left;"> $QQQ $XBI the big difference is … US increase Rates in 2022 … China cuts rates 🤔😵‍💫

China loves their economy….FED/US obviously hates their economy and it seems they want to destroy all the success of the last years … I don’t get it … if the FED will do wrong moves next week, this ends in a Desaster 4 the US Stockmarket

Oh boy, I miss him so much 😒 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:34:29 </td>
   <td style="text-align:left;"> $SPY $QQQ Lets get some news about aliens or something this weekend and call it a wrap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:33:05 </td>
   <td style="text-align:left;"> $QQQ just be patient </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:32:42 </td>
   <td style="text-align:left;"> $SPY $QQQ this is the toughest market to trade I have ever seen in my 6,5 months trading it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:31:51 </td>
   <td style="text-align:left;"> $QQQ GREAT NEWS! We&amp;#39;re over halfway there! Only ~10-12% left! Or if you look at a log chart, like... 7%! HOT DAMN! 
 
Hold me. $ENPH $SQQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:31:39 </td>
   <td style="text-align:left;"> $NFLX $SPY $QQQ $V  i got fkd so hard 🍆today is unbelievable </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:30:13 </td>
   <td style="text-align:left;"> $QQQ Investment bankers got the word, J Powell will raise on Wednesday, 25 bps

That’s what’s spoiling the market

May be a buying opportunity after the hike </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:29:53 </td>
   <td style="text-align:left;"> $SPY $QQQ — jk got $SQQQ calls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:28:23 </td>
   <td style="text-align:left;"> $QQQ so what happens when Powell ends QE and initiates QT? that markets havent seen this type of reversal since the 2007 disaster! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:28:11 </td>
   <td style="text-align:left;"> $UPST $AMZN $IWM $SPY $QQQ Young Warren Buffet 1962 Interview | Stock Market Has Been Selling Off
https://youtu.be/DnhhR-LxNYg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:27:56 </td>
   <td style="text-align:left;"> DJIA Weekly Close. This {Wave 5} bull market blowoff top has now subdivided into it&amp;#39;s own 5 wave fractal structure which is standard policy in terminal fazes of raging bull markets. Target for {Wave 5} was 36k so the bull market top could be hammered in. $DIA $QQQ $IWM $TSLA $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:27:34 </td>
   <td style="text-align:left;"> $QQQ let&amp;#39;s go Brandon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:26:41 </td>
   <td style="text-align:left;"> $QQQ 

I analyzed everything. Had to go short again. Heavily. We aren’t done yet. Sorry </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:26:12 </td>
   <td style="text-align:left;"> $QQQ :Too much selling !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:25:42 </td>
   <td style="text-align:left;"> $QQQ IMO no bottom till AAPL drops below 150 and the VIX goes &amp;gt; 40. Of all the FAANG names, AAPL has yet to drop 20%. It&amp;#39;s the last shoe to drop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:23:00 </td>
   <td style="text-align:left;"> $SPY $AAPL $QQQ this was a huge reversal indicator. In addition to the different macro environment. This isnt 2020-2021. Many individual names are in a bear market beneath the underlying indices. Big tech lagged and is now bringing the market down. They are essentially the heaviest weighted, especially apple. Which seems to be lagging on the correction </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:22:36 </td>
   <td style="text-align:left;"> $QQQ  At Marketwatch.com: ‘Godfather’ of technical analysis says the stock market could fall 20% or more, but don’t panic: ‘This market really, really did unbelievable’ for 18 months </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:22:13 </td>
   <td style="text-align:left;"> Hope you guys loved the session great to have 100s of you on it live asking QnA! SEE MY BIO if you missed it.. If you have been following me or is this week, it was pretty crazy on the downside. We NAILED tons of puts on $SHOP $QQQ $SPY $TSLA $PTON. No one said you can’t make $$ in a down market. Let’s stay focused and crush it volatility. HAVE A SPLENDID WEEKEND!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:21:50 </td>
   <td style="text-align:left;"> $QQQ bigs money stealing all your money. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:21:39 </td>
   <td style="text-align:left;"> $SPY $QQQ Man, can’t lie as I’m frustrated. I’ve never been stopped more on trades then I’ve been so far this year. I’m not being patient. Stupid. I need to be better. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:21:04 </td>
   <td style="text-align:left;"> $QQQ good time to pick up some ETH for the long time crypto investor. 2500 today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:20:55 </td>
   <td style="text-align:left;"> $QQQ IBM better report good earnings monday or else... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:20:33 </td>
   <td style="text-align:left;"> $BTC.X $SPY $TSLA $QQQ 

And just like that El Salvador just became that much more poor... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:19:58 </td>
   <td style="text-align:left;"> $BTC.X fuck wallst blackrock citadel cnbc phonies  $SPY $QQQ no amount of pumping will save this bs market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:19:33 </td>
   <td style="text-align:left;"> $QQQ $SPY  Let&amp;#39;s talk stocks! 
https://youtu.be/Bd1KfZbHf-s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:18:52 </td>
   <td style="text-align:left;"> $QQQ Nasdaq 13k here we cometh!!! But you know they always overshoot that load... so... Nasdaq 12,600 is more like it...Buckle up tech geeks... Your party has been invaded Bulls.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:18:32 </td>
   <td style="text-align:left;"> $NFLX In time we will all be saying, &amp;quot;damn, I should&amp;#39;ve bought more&amp;quot;. $SPY $QQQ $PYPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:18:04 </td>
   <td style="text-align:left;"> $QQQ this was a huge reversal indicator. In addition to a completely different macro environment.  This isnt 2020-2021...could see this at 330 by mid feb </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:17:27 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ  
 
If markets keep dropping Jimmy gonna lose his shit again! 
 
&amp;quot;They Know Nothing!&amp;quot; 
 
lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:17:17 </td>
   <td style="text-align:left;"> $QQQ Cramer thinks market drop today is due to imminent russian invasion of ukraine, nothing to do with $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:17:15 </td>
   <td style="text-align:left;"> $BTC.X $SPY $QQQ nobody wants to catch the falling knife. Until big money steps in, the knife keeps falling. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:17:06 </td>
   <td style="text-align:left;"> $SPY $QQQ The put/call ratio for SPY contracts expiring next Friday is 2/1 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:15:38 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:15:00 </td>
   <td style="text-align:left;"> The technical rating of $QQQ is bad and it also does not present a quality setup at the moment. https://www.chartmill.com/stock/analyzer/stock/QQQ?key=d8dac8fb-a874-4422-96db-185a5752c108&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=QQQ&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:13:22 </td>
   <td style="text-align:left;"> $SPY $QQQ So market just told us Russia is taking over this weekend 🇷🇺 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:13:16 </td>
   <td style="text-align:left;"> $QQQ 99.99% will not CRASH this week…. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:12:32 </td>
   <td style="text-align:left;"> $SOFI $PLTR $IWM $QQQ next week will be the mother of all weeks, at least for the past year. We moon or we bust. It doesn’t matter even much what we own. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:10:47 </td>
   <td style="text-align:left;"> $QQQ 

Sh!t is going to pop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:09:42 </td>
   <td style="text-align:left;"> $QQQ QQQ 2022-01-21 Daily Forecast Video: 
https://www.youtube.com/watch?v=yOtCpTOh-CU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:08:33 </td>
   <td style="text-align:left;"> $SPY it took $qqq 5 months to go from 350 to 400. Lost those gains in 21 days. Lmao! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:07:50 </td>
   <td style="text-align:left;"> $QQQ $SPY god help tech if $350 breaks. 😳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:07:28 </td>
   <td style="text-align:left;"> $MTTR  I’m done with individual stocks after this one recovers, too many games by hedge funds. $SPY or $QQQ for my 90% of my holding, hedgefunds are just gutting retail investors. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:07:07 </td>
   <td style="text-align:left;"> $QQQ cnn website isnt even mentioning the complete crash of the stock and crypto market, typical anything to protect their swamp rats </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:07:03 </td>
   <td style="text-align:left;"> $SPY $QQQ no way more then 1 rate raise this year..economy still in the shitter and now everyone has lost a lot of money In the market.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:06:18 </td>
   <td style="text-align:left;"> $SPY $QQQ Next week the market should bounce. We will get more clarity from the FED on rate hikes and the market can finally fully pricing into how many rate hikes the FED will do this year. When the rate hikes are fully priced in then this market should be able to resume going up very quickly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:05:25 </td>
   <td style="text-align:left;"> $QQQ this is falling like the fraudulent senile pedophile they installed in the white house. If you still support him, please get off the planet like now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:03:20 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:01:09 </td>
   <td style="text-align:left;"> $QQQ Ah closed. We good. Till Monday everyone. $SPY $ROKU </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 07:00:12 </td>
   <td style="text-align:left;"> $SPY $QQQ $DJIA Fed meets on Wednesday so until then we can see a significant drop in the averages </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:59:09 </td>
   <td style="text-align:left;"> $QQQ $SPY my call positions! Bought a little early. Sometimes the pros make a mistake or two as well ;-) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:58:42 </td>
   <td style="text-align:left;"> $QCOM I am dumbfounded right now. People of Stocktwits bought put options instead of call options today? $SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:58:41 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:58:24 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:57:26 </td>
   <td style="text-align:left;"> $QQQ during pandemic it dropped 30%+ $234’s upper $160’s before rising.  We are about 13.5% off highs.  It would be $285’s if did the same before rising but I don’t different scenario here but interesting nonetheless </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:56:56 </td>
   <td style="text-align:left;"> $QQQ time to buy is now bitcoin dump will probably help give up another couple of percent here for fear i wouldnt bet on it though </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:56:49 </td>
   <td style="text-align:left;"> $SPY $QQQ $DIA gap down Monday and possible intraday rally that might last into the following day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:56:37 </td>
   <td style="text-align:left;"> $SPY #GEX is still negative at -1.7B and #DIX didnt fall much (still at 43.2) after today&amp;#39;s massacre. Not sure what it means. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:56:34 </td>
   <td style="text-align:left;"> $BTC.X $QQQ $SPY $GLD almight Jerome, I will never doubt you again, I’m forever your bitty. Call me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:56:11 </td>
   <td style="text-align:left;"> $QQQ $SPY got some good news for bulls. As your money in your account shrinks the 3% drops get smaller dollar wise 🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:56:07 </td>
   <td style="text-align:left;"> $BTC.X Russia Russia Russia 

Get your money while you can man and lady 

  $spy $DIA $DJIA $QQQ  👊🏻🧞‍♂️       🕶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:55:44 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $ARKK $BTC.X 
 
Poor Millennial and GenZ retail trader. They gonna have some serious PTSD as the FED pulls more liquidity from the markets. 
 
Will they ever invest with such optimism again? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:55:20 </td>
   <td style="text-align:left;"> Retail investors were net sellers of equities over the last 2 days, marking the 6th time since COVID that retail sold over 2 consecutive sessions. Tremendous change from earlier in the wk when rolling 1-wk average daily retail flow hit an ATH pace of $2.8B/day. - MS 
 
$SPY $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:55:17 </td>
   <td style="text-align:left;"> $QQQ how predictable is  RSI ?? When was last time the market went up 6.3 % in a week and 11.3 % in month ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:55:07 </td>
   <td style="text-align:left;"> $QQQ Anyone peep that monthly candle 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:55:05 </td>
   <td style="text-align:left;"> $QQQ Most everything completely wrecked. RSi on everything in the toilet. This should be close to the bottom. That plus volume and big Capitulation on multiple names. Of course the bears will say we are going to zero but history and charts say otherwise. Time to get a recovery going. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:55:03 </td>
   <td style="text-align:left;"> $QQQ how much more pain Nasdaq ? I am exhausted </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:54:35 </td>
   <td style="text-align:left;"> $QQQ bears thinking rsi doesn’t matter apparently 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:54:34 </td>
   <td style="text-align:left;"> $DIA300 $SPY350 $QQQ  (30000, 3500, Nasdaq13000) buy levels </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:54:26 </td>
   <td style="text-align:left;"> $BTC.X $ONE.X $QQQ  
If bitcoin, NA bitcoin miners and Harmony don&amp;#39;t make some sort of new all time high after the next halving then i will concede to the bears. Learning fast to stay humble.  
Brutal 👇The revenant 
https://www.youtube.com/watch?v=uSXmzoqpkHA 
https://www.youtube.com/watch?v=7hnmqsiOzXA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:53:36 </td>
   <td style="text-align:left;"> $QQQ loading today </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:52:32 </td>
   <td style="text-align:left;"> $SPY $QQQ the dump continues after hrs. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:52:21 </td>
   <td style="text-align:left;"> $QQQ when split? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:51:11 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM  
 
While we are long term bearish, but be careful here shorts, a big bounce may be coming:  
 
QQQ RSI = 27 
SPY RSI = 27 
IWM = 24 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:51:03 </td>
   <td style="text-align:left;"> $AVCT March 2020 all over again! Next week FED has a meeting! Jeremy Powell will probably pump the market until March. Almost every stock that I am watching is oversold. We are due for reversal! $QQQ $SPY! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:50:46 </td>
   <td style="text-align:left;"> $BTC.X Bruno’s Diaz    $SPY $SPX $QQQ 🧞‍♂️

👊🏻🧞‍♂️🤣🤣🤣🤣🤣🤣🤣🤣🤣    🕶 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:50:38 </td>
   <td style="text-align:left;"> $QQQ you think Sloppy Joe  is not run by hedge funds the only thing driving the housing market is the stock market this will clean up quickly no chart necessary </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:49:50 </td>
   <td style="text-align:left;"> This week&amp;#39;s stock market analysis video has been published! 
 
📽️ https://www.youtube.com/watch?v=B811T5arxeo 
 
☑️Worst S&amp;amp;P500 weekly decline since 2020 
☑️Long-term equity trends under pressure 
☑️VIX term structure enters backwardation 
 
Have a great weekend! 
 
$SPY $IWM $QQQ $VIX $GLD #stocks #trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:49:21 </td>
   <td style="text-align:left;"> $QQQ FYI, 
 $408.71(All Time High) on 11-22-21 
-10% = $367.839 
-15% = $347.4035 
-20% = $326.968 
-25% = $306.5325 
GLTA. (Good Luck To All) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:49:15 </td>
   <td style="text-align:left;"> $QQQ we’re going up on Monday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:48:34 </td>
   <td style="text-align:left;"> $SPY I still think $QQQ offers the best short setup after it gets a dead cat bounce. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:48:26 </td>
   <td style="text-align:left;"> $QQQ Seems like she wants $343 back to that breakout 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:47:57 </td>
   <td style="text-align:left;"> $SPY $QQQ Biden and Powell tag teaming for an economic crisis </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:47:18 </td>
   <td style="text-align:left;"> $QQQ to many people bitching about market crashing haha, watch the market be green next week and all shorts burn and loose all the money they made on puts this week, market does opposite of what you think and to many people are screaming crash for it to crash. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:46:53 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $DIA $NDX … me 👇🏻… buying the “dip” today 🤬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:46:21 </td>
   <td style="text-align:left;"> $QQQ $SPY  $AAPL $TSLA  Any bounce will be sold off as so much damage has been done  some hedge funds r blowing up soon Margin calls r killing retails </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:45:59 </td>
   <td style="text-align:left;"> $SPY $IWM $DJIA $QQQ I don’t think anyone understands how much power the Fed has unleashed into the markets.  Go look at the DJIA in 1918 when their pandemic happened then what happened after it recovered to the previous high…Let me know what you find. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:44:55 </td>
   <td style="text-align:left;"> $QQQ all the big shorts deserve to be dead with omicron fk them </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:44:47 </td>
   <td style="text-align:left;"> $QQQ where is Tom Lee and risk on SPX 4000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:43:05 </td>
   <td style="text-align:left;"> $QQQ market is preparing for a good month in feb, i expect one big shitstorm next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:42:57 </td>
   <td style="text-align:left;"> $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:42:13 </td>
   <td style="text-align:left;"> I could show you a bunch of backtests and stats but basically coordinated &amp;amp; steep sell offs in many markets / sectors like now have very good risk/reward ratios going forward except for the crash like or steep bear markets like 2008. Do you think believe we are in crash / bear market scenario? $SPY $IWM $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:39:57 </td>
   <td style="text-align:left;"> $QQQ , $AMC, $SQQQ   Best metaphor on what is going on with the stock market I have seen, and funny despite the pain. https://www.youtube.com/watch?v=hNMsoRtRKew </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:39:35 </td>
   <td style="text-align:left;"> $BTC.X $QQQ $SPY looks like everyone compounded backwards in 2022💩 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:39:09 </td>
   <td style="text-align:left;"> $QQQ this is Bidenomics baby. I bought $380 puts last year. Trump policies are now wiped out. We are on Joe&amp;#39;s court now. That means another 50% down baby! I pulled put all my money at end of last year. Dabbled in some puts, and ohh lawd! I am loving this!! I&amp;#39;ll put my money back in plus the put profits once this thing bottoms out...around campaign season when Republican hope and fiscal policy is restored. Until then. Destroy this market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:38:03 </td>
   <td style="text-align:left;"> $QQQ Will this ever bounce, man? Nervous here </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:37:57 </td>
   <td style="text-align:left;"> $BTC.X $SPY $QQQ this Year they take back all the money you made last year lol 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:37:46 </td>
   <td style="text-align:left;"> $QQQ a lot of bozos are pricing things right now based on current earnings. Don’t forget once the earnings evaporate there won’t be a floor under the stock anymore and it’ll be free fall </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:36:48 </td>
   <td style="text-align:left;"> $QQQ Volume peak today, several tech companies massively oversold, incl. blue chips like Amazon, Alphabet and  QQQ sitting on the $350 support. Everything alligned for a great bounce from here imho </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:35:59 </td>
   <td style="text-align:left;"> $QQQ market is only down 14% what’s wrong with you guys..? $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:35:48 </td>
   <td style="text-align:left;"> $QQQ  
I compared the YTD performance QQQ, to two popular Large Growth mutual funds: 
 
The Fidelity Blue Chip Growth Fund FBGRX, and the Vanguard U.S. Growth Fund VWUAX ... and QQQ has outperformed YTD. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:35:34 </td>
   <td style="text-align:left;"> $QQQ $SPY $IWM $DIA This week was the worst week since 1969. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:35:20 </td>
   <td style="text-align:left;"> $QQQ beautiful </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:35:00 </td>
   <td style="text-align:left;"> $QQQ $SPY its a big illusion folks. Those star companies that can’t do any wrong. Once the narrative changes they’ll show every crack in every beloved company and get every % point drop out of it </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:33:59 </td>
   <td style="text-align:left;"> $QQQ $SPY selling FAANG! On the next highs I guess </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:33:15 </td>
   <td style="text-align:left;"> $QQQ i see low 300s before a bounce </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:31:39 </td>
   <td style="text-align:left;"> $QQQ think about all those bullshit companies that went up like crazy and already have been cut by 60-70%. People will jump in thinking it’s value and they will go down 95% or more when it’s all said and done </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:31:08 </td>
   <td style="text-align:left;"> $SPY $QQQ are y’all really listening to those idiots on cnbc? 😹 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:31:07 </td>
   <td style="text-align:left;"> $QQQ $SPY We’re used to free money by Fed. After years of massive gains in stocks this pullback was expected. It amazes me people buying into grossly overpriced stocks and then blame Biden  or others for their loss. Do your DD, diversify your portfolio and hold cash to buy in days like today. GL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:31:00 </td>
   <td style="text-align:left;"> Big call buying in $NVDA for Jan 28th expire $smh $qqq https://www.cnbc.com/video/2022/01/21/big-call-buying-in-this-semiconductor-name.html?__source=iosappshare%7Ccom.stocktwits.StockTwits.STShareExtension </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:30:17 </td>
   <td style="text-align:left;"> $SPY I remember that mr pro guy saying clearly this was coming and to buy all inverse etf like $SQQQ and $SPXS etc. He said all the people that just started last year will get crushed by buying the dip over and over because they don’t realize it was the fed that was causing the V back to green and the fed is gone. Wow was he ever right. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:29:18 </td>
   <td style="text-align:left;"> $QQQ  Can we all just stop pretending we don&amp;#39;t see it. $SQQQ $$UVXY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:28:59 </td>
   <td style="text-align:left;"> $QQQ $VIX $SPY $SPX $IWM  
 
now we are all relegated to listening to Moo talk about his fake trading account for the weekend. 
 
This is the definition of hell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:28:46 </td>
   <td style="text-align:left;"> $QQQ Look out below </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:28:18 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $NASDAQ I think what is happening is big guys selling covid19 stocks like PTON NFLX etc crypto included. hold it in cash and then buy other sectors at a discount during the bloody market. I guess post pandemic stocks, financial etc. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:28:13 </td>
   <td style="text-align:left;"> $BTC.X wish I had more cash to buy more bitty. 
 
$SPY $QQQ $TSLA $AAPL fuck the old system </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:28:06 </td>
   <td style="text-align:left;"> $SPY as I said folks don’t go yolo into calls for next week. With certainty this heads into the 420,s minimum as the earnings next week are all from companies that already stated bad forward guidance last earnings call on supply chain issues and inflation and Covid employment concerns. Then u have the fed late week. This isn’t going anywhere but down until at bare minimum after fed but by then it will be in the 420,s so wait until then before buying calls. $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:28:05 </td>
   <td style="text-align:left;"> $QQQ $SPY way too easy 🤣🔻🔻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:27:34 </td>
   <td style="text-align:left;"> $QQQ 6.2% fall just off yesterday highs 👀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:27:19 </td>
   <td style="text-align:left;"> $QQQ $SPY don’t be surprised to see a big dead cat bounce soon maybe even days of green. Once everyone is back in it will resume dumping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:25:56 </td>
   <td style="text-align:left;"> $QQQ $SPY right on schedule folks 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:25:27 </td>
   <td style="text-align:left;"> $SPY $QQQ $IWM $DIA so government spending for chip manufacturing 😁😁😁😁😁😁 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:25:24 </td>
   <td style="text-align:left;"> $SPY $qqq and crap day. January gains and more gone. Annoying. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:25:08 </td>
   <td style="text-align:left;"> $SPY $QQQ I don&amp;#39;t think I&amp;#39;ve ever seen anything tank as much as Cathie Wood&amp;#39;s flagship ARK Innovation Fund 
 
This is a clinic on what happens to a high-beta, ultra-high P/E multiple portfolio of non-diversified stock positions during a crashy bear market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:24:52 </td>
   <td style="text-align:left;"> $QQQ the big short </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:24:44 </td>
   <td style="text-align:left;"> $QQQ $SPY like taking candy from a baby 🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:23:51 </td>
   <td style="text-align:left;"> $TQQQ loaded up heavy today - risk to reward is incredible at these levels for a longer hold 

$SPY $IWM $VIX $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:23:10 </td>
   <td style="text-align:left;"> $QQQ monster volume today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:23:00 </td>
   <td style="text-align:left;"> $QQQ $SPY $BTC.X $ETH.X what you’re seeing is a massive confidence game being exposed. if the hidden hand of the Fed doesn’t wave it’s wand soon, it’s going to be 2x worse than March ‘20. Idk what to say I’m usually Uber bullish but if this regime is dead set on letting things fail then it is what it is. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> QQQ </td>
   <td style="text-align:left;"> 2022-01-22 06:22:49 </td>
   <td style="text-align:left;"> $SPY $DIA $QQQ 
Not buying this dip until $SPY 3500, and $DIA30000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 09:41:45 </td>
   <td style="text-align:left;"> $AAPL 👁❤️🍏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 09:40:23 </td>
   <td style="text-align:left;"> $AAPL those iOS updates will be coming more often now that there is slow down. Might want to switch to Nokia for more transparency and cheaper phones. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 09:33:36 </td>
   <td style="text-align:left;"> $AAPL taking a big position here for earnings, we will see $90! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 09:25:26 </td>
   <td style="text-align:left;"> $AAPL blame the feds.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 09:21:49 </td>
   <td style="text-align:left;"> $AAPL gona be at 80 bucks in march. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 09:16:15 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA $BTC.X 
 
Poor Millennials 
 
They were once again take advantage off as JPOW leveraged the world-wide pandemic to intentionally inflate asset prices so Boomers could hand off bags at all time highs and valuations just as they were retiring en masse. 
 
Boomers know the stock market game and took the opportunity to lock in lifetime gains and hand off their bags to Millennials at OBVIOUSLY overvalued levels. 
 
So who are Millennials going to convince to take their bags when they are ready to retire? GenZ? Good luck!...they just went through the same scam with you. 
 
Boomers are relentless in taking advantage of the world around them for their own personal gain. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 09:11:03 </td>
   <td style="text-align:left;"> $AAPL The Fed is your friend until it isn’t. Which is now! Rug pull! $QQQ $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 09:10:15 </td>
   <td style="text-align:left;"> $AAPL when I said 153 weeks ago they laughed at me. Ah. Here. We go. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 09:10:10 </td>
   <td style="text-align:left;"> $AAPL mostly bounce at 155$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 09:09:09 </td>
   <td style="text-align:left;"> $SPY $AAPL $AMZN $TSLA $PLTR 
Officially entered to 🐻 market today from correction 🧙‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 09:05:20 </td>
   <td style="text-align:left;"> $AAPL Tom Cruise is in..👍 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 09:02:22 </td>
   <td style="text-align:left;"> $AAPL Simulated Weekly $162.5 CALLS for Monday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 09:02:03 </td>
   <td style="text-align:left;"> $SPY $QQQ $VIX $TSLA $AAPL  
 
What a day (and week) in the markets! 
 
- $ 973 Billion traded today alone in US Equities ( $ 690 B was the daily average this week). 
 
- $ 45 Billion traded today alone in US Options ( $ 22 B was the daily average this week). 
 
-------- </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 09:01:09 </td>
   <td style="text-align:left;"> $AAPL if Netflix dump, Amazon dump, and this over priced crap cell phone company valued at 2.5 trillion doesn’t go down, then I don’t understand physics 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 09:00:27 </td>
   <td style="text-align:left;"> $AAPL bring back blackberry </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 08:57:34 </td>
   <td style="text-align:left;"> $AAPL. It is trading below 9 and 50 EMA. If broke below $160.5 which happened to be the 100 EMA, it will break the downtrend channel (in orange) and gap down to $157, then $150. If the market is red on Monday then hitting $150 is just matter of time. For bullish reversal, it must cross above the green trend line. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 08:55:28 </td>
   <td style="text-align:left;"> $AAPL 29 bucks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 08:55:27 </td>
   <td style="text-align:left;"> $AAPL  if the market wont bounce back next week then there&amp;#39;s a cyber issue going on..goodluck. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 08:53:28 </td>
   <td style="text-align:left;"> $AAPL r
This is one of the only stocks I&amp;#39;d buy rn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 08:51:13 </td>
   <td style="text-align:left;"> $AAPL IF BUY THE DIP WAS A GUY IT WOULD B ME👨🏽‍💻🖨💵 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 08:51:06 </td>
   <td style="text-align:left;"> $AAPL hope you took profit, gonna be brutal couple of months. Still a great company 👌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 08:41:37 </td>
   <td style="text-align:left;"> $AAPL Silly bears having fun before 🍏🚀🤑. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 08:39:03 </td>
   <td style="text-align:left;"> $FB the funny thing is they put a price target (much higher than what&amp;#39;s now), people jumped in and then boom, they start shorting it, one after one, $FB, $AAPL, $NIO and so on... those are criminals. Last year they were crying because they got caught with $AMC and $GME, now we are paying the price. GL all </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 08:38:42 </td>
   <td style="text-align:left;"> The Stock Market Has 3 Problems. 2 Aren’t Going Away.  $PTON $NFLX $AAPL $TSLA 

https://newsfilter.io/a/6652442d66cba49abc81e35b6e99a9ec </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 08:36:14 </td>
   <td style="text-align:left;"> $AAPL great ER coming, new AR glasses news will out. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 08:29:22 </td>
   <td style="text-align:left;"> $AAPL hard to believe that people who don’t own anything are making more money in this market than people who invest their own money, this is a market for the shorties right now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 08:29:06 </td>
   <td style="text-align:left;"> $AAPL $116 march 2021 low. Was at a 30+ PE. 
$180 would be 30 PE now. 116 today would be a 19 pe. 
If you bought in 2019, @ $41, and are holding, you also have a 2% dividend yield. While it was 0.5% then. 
New verticals yet to come to this stock lol. AR , VR, Car, healthcare, better silicon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 08:20:32 </td>
   <td style="text-align:left;"> $SPY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 08:18:43 </td>
   <td style="text-align:left;"> $AAPL I’m buying this dip, it’ll go back the other way </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 08:17:32 </td>
   <td style="text-align:left;"> $PLTR $AMZN $AAPL $NFLX $GOOG What is the best site to get up-to-date earnings , p/s earning ratios? they all carry depending on site, which is bullshit </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 08:15:06 </td>
   <td style="text-align:left;"> $AAPL BEARS ate like KINGS this week. Let&amp;#39;s see them fold when the SQUEEZE cancel their Free Meal tickets 🎟 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 08:14:33 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 08:14:13 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $AAPL $TSLA  
 
Boomers doing what Boomers do when the market starts to crash. 
 
Find a war! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 08:14:03 </td>
   <td style="text-align:left;"> $AAPL this is just crazy.  apple plants money 💰 and grows money.   this really should never go down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 08:12:50 </td>
   <td style="text-align:left;"> $AAPL 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 08:07:26 </td>
   <td style="text-align:left;"> $AAPL I bought a little in after hours for Monday pop. Have a great weekend. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 08:05:46 </td>
   <td style="text-align:left;"> $AAPL who bought at $183 😂😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 08:05:06 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-01-21 Technical Analysis Video: 
https://www.youtube.com/watch?v=MTKVrEGEz38 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 08:04:03 </td>
   <td style="text-align:left;"> $AAPL hit this price because of anticipation of apple car. There is no such thing ,so this will dive hard this week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 08:03:45 </td>
   <td style="text-align:left;"> $BTC.X buying some $AAPL  take advantage of the red days </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 08:03:40 </td>
   <td style="text-align:left;"> $AAPL this may bey well go below 100 soon with the war </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:56:12 </td>
   <td style="text-align:left;"> $AAPL $TSLA $NIO 

Wearable Health Solutions Inc. Announces &amp;quot;Worldwide Business | WHSI Stock News https://www.stocktitan.net/news/WHSI/wearable-health-solutions-inc-announces-worldwide-business-with-n7xlrpshqskl.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:55:58 </td>
   <td style="text-align:left;"> $SPY To charts to ponder this week end
Weekly Ichimoku.  Tgt 420. $DIA $QQQ $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:55:27 </td>
   <td style="text-align:left;"> $AAPL - when Russia invades the Ukrane this weekend, I wonder what the price of $AAPL will be Monday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:55:14 </td>
   <td style="text-align:left;"> $AAPL buy at any price and hold </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:54:16 </td>
   <td style="text-align:left;"> $AAPL Anyone who says this is going up are down &amp;amp; don’t provide facts please don’t post , or say it’s just a guess . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:52:47 </td>
   <td style="text-align:left;"> $AAPL  tomorrow worst day for AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:52:37 </td>
   <td style="text-align:left;"> $AAPL This years  earnings I will be buying p long puts for simple fact 2021 what gave them the 100 billions earnings  was due to stimulus checks and work from home.  Now what happens this year or next when people are back in the office and no stimulus?  Those same people who bought new macs last year will they want new macs? No. Apple will probably make around 59 to 75 billions in earnings so taking long puts on apple because it’s 3x earnings pre pandemic.  So my guess we see $120 ish this year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:51:52 </td>
   <td style="text-align:left;"> Sweep Options Activity: $AAPL is the #1 ticker with sweep activity where institutions are trading options urgently with 99.5K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:49:27 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ  asking for a friend, he looking for that flavor. Where can he buy? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:48:52 </td>
   <td style="text-align:left;"> $AAPL I wonder if Hollywood will make a movie about the stock market crash of 2022? Lol. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:47:44 </td>
   <td style="text-align:left;"> $AAPL still holding up </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:47:11 </td>
   <td style="text-align:left;"> $MSFT $AAPL $TSLA  no matter what Earnings they report these r going down all priced in market adjusting to new world with high interest rates </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:41:38 </td>
   <td style="text-align:left;"> 3 Things to Know About the Q4 #Earnings Season $GE $JNJ $MCD $AAPL https://talkmarkets.com/content/stocks--equities/3-things-to-know-about-the-q4-earnings-season?post=342052 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:38:04 </td>
   <td style="text-align:left;"> $AMD $SPY $AAPL $MSFT $FB

markets are like this. If you have stocks don’t worry average down when you get chance. Don’t invest the amount you afford to lose. Invest in reliable and strong fundamental company so even if it goes some amount down ultimately it will go above. 
Prices always goes up and down. You should follow the trend. Don’t marry to a stock, move your money with the market trend. 😌
Correction in market is very common and it happens almost 4 times in a year. I know this correction is a lot bigger but still it’s not crash, it will come back sooner then you expect. 
There is a life outside of this ridiculous market also, enjoy your time with your family and friends, don’t get depressed everything will be ok. Just be patient and follow the trend. 
Have a wonderful weekend. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:37:30 </td>
   <td style="text-align:left;"> $MSFT $SPY $AAPL $FB

markets are like this. If you have stocks don’t worry average down when you get chance. Don’t invest the amount you afford to lose. Invest in reliable and strong fundamental company so even if it goes some amount down ultimately it will go above. 
Prices always goes up and down. You should follow the trend. Don’t marry to a stock, move your money with the market trend. 
Correction in market is very common and it happens almost 4 times in a year. I know this correction is a lot bigger but still it’s not crash, it will come back sooner then you expect. 
There is a life outside of this ridiculous market also, enjoy your time with your family and friends, don’t get depressed everything will be ok. Just be patient and follow the trend. 
Have a wonderful weekend.😎 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:35:11 </td>
   <td style="text-align:left;"> $AAPL it&amp;#39;s obviously gonna come down a bit but it&amp;#39;s undoubtedly the best inflation hedge this year. Fact that no one wants to sell says a lot too </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:32:18 </td>
   <td style="text-align:left;"> $AAPL had to cancel all my recurring subscriptions in the App Store, overcharged me 70 bucks ☠️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:31:26 </td>
   <td style="text-align:left;"> $AAPL Can&amp;#39;t believe Apple is acting like a 5th Wheel?  The Hedges didn&amp;#39;t see  todays upgrades.. Something is rotten in Denmark. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:30:38 </td>
   <td style="text-align:left;"> $AAPL earnings will beat top and bottom load up those $180 calls in cheap price </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:26:18 </td>
   <td style="text-align:left;"> $AAPl any thoughts on earnings? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:25:37 </td>
   <td style="text-align:left;"> $AAPL gme is green haha, the only green ticker on my list. What kind of world do we live in. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:24:33 </td>
   <td style="text-align:left;"> $AAPL $200 automatic </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:23:00 </td>
   <td style="text-align:left;"> $SPY $AAPL $QQQ this was a huge reversal indicator. In addition to the different macro environment. This isnt 2020-2021. Many individual names are in a bear market beneath the underlying indices. Big tech lagged and is now bringing the market down. They are essentially the heaviest weighted, especially apple. Which seems to be lagging on the correction </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:22:08 </td>
   <td style="text-align:left;"> Unusual Options Activity: $AAPL is the #22 ticker with unusual activity from institutional traders with an average of 24% out of the money, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:21:46 </td>
   <td style="text-align:left;"> $AAPL 85 bucks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:21:26 </td>
   <td style="text-align:left;"> $AAPL WOW, look at all the bears coming out of hibernation. Same people who thought March April 2022 was the beginning of the end. Keep shorting this at your own peril. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:18:54 </td>
   <td style="text-align:left;"> $AAPL $AMZN  Joe shit-his-pants Biden has done it again. LGB!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:18:38 </td>
   <td style="text-align:left;"> $AAPL might start position at $125 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:17:30 </td>
   <td style="text-align:left;"> $AAPL trending on StockTwits right now in top 20 - saw a significant increase in number of impressions the last 24hrs - should see some strong support. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:15:52 </td>
   <td style="text-align:left;"> $AAPL heading for the 50MA on the weekly at 158-159 next week. Prob bounce from there. Seems to be lagging as i stated, only down 11% from ATH. All the other big tech is 15-20%+ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:12:40 </td>
   <td style="text-align:left;"> $AAPL can see 158-160 before reversal </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:11:09 </td>
   <td style="text-align:left;"> $AAPL We will see a temp rally dont get screwed thinking its over! There is more pain coming sorry its the truth dow needs to come to 30k area sp500 broke below 200 movn average right not good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:10:33 </td>
   <td style="text-align:left;"> $AAPL I doubt people will stop buying a new iPhone every year. Plus Apple Watch or machook or EarPods and other Apple stuff. 

Accumulate! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:08:18 </td>
   <td style="text-align:left;"> $AAPL 145$ not too far </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:05:43 </td>
   <td style="text-align:left;"> $AAPL this is due one mighty correction.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:03:16 </td>
   <td style="text-align:left;"> $AAPL now Cramer is saying to not listen to show!!! Hahahahahaahahahahahahahahahahahahahahahhahahahaaaahahahahahahahahahahahhahahahahahahahahahhaahahahahahahahahahahahahahahahahaaahhaajaahajajajajajajajajajaaajajhahahahaahahhahahahahahahaaahhahaahahahahahahahahahahahahahahahahahaahahahahahahahahahhahahaahahahhaahaahhhaahahahahahaahahahahahahahahahahahahaahhaahahahahahahahahahahahahahahaahahhahahahaahhaahhaahhahaahahahahhaahaj </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:02:30 </td>
   <td style="text-align:left;"> $AAPL what do you all think about earnings next week? bearish or bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:01:40 </td>
   <td style="text-align:left;"> $MSFT loaded up on $AAPL  and $MSFT today. There will soon be a rally. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 07:00:22 </td>
   <td style="text-align:left;"> $AAPL anyone else load up on shares? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 06:59:38 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 06:56:49 </td>
   <td style="text-align:left;"> $NFLX $SPY $SHIB.X $AAPL $NVDA 
5k to 60k in 1 day we made </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 06:56:03 </td>
   <td style="text-align:left;"> $AAPL AAPL Controls the market. Peridot!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 06:52:29 </td>
   <td style="text-align:left;"> $AAPL The Afterhours dumping has started ... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 06:52:08 </td>
   <td style="text-align:left;"> $AAPL why are they crashing so much </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 06:52:00 </td>
   <td style="text-align:left;"> $AAPL has an average volume of 100093000. This is a good sign as it is always nice to have a liquid stock. https://www.chartmill.com/stock/analyzer/stock/AAPL?key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=TA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 06:47:15 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $AMZN 

My thoughts on the stock mkt today ... 

I sent an email alert out to subscribers early this morning as we pressed the 440 level, mentioning that it felt panicky and I was buying QQQ for a trade. A bit later, after an almost 70 handle bounce, I sent another alert out saying it was time to take the trade (SEE BELOW). 

I&amp;#39;ve been on record since the start of 2022 suggesting we are headed for a correction. And I&amp;#39;ve posted this on ST. This is what one feels like.

For those who have only known the &amp;quot;buy the dip&amp;quot;  market, this has been an absolute disaster I am sure. For those who have subscribed to my site, this is exactly the type of action I have been expecting since the start of 2022. 

Question now is, where are we heading? My Game Plan on  Sunday will cover this very topic. If interested in receiving, mail me at

 jessielivermore1929@gmail.com 

Will they finally break TSLA and AAPL? Does AMZN continue its free fall? 

Thank you to all who have subscribed! ✌️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 06:47:13 </td>
   <td style="text-align:left;"> $AAPL NEW ARTICLE : You can see the impact of the congressional antitrust fight on tech stocks, says Strategas&amp;#39; Clifton https://www.stck.pro/news/AAPL/21721093 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 06:46:36 </td>
   <td style="text-align:left;"> $AAPL now apple can go down rug pull to 140 or green dildo to 200 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 06:46:21 </td>
   <td style="text-align:left;"> $QQQ $SPY  $AAPL $TSLA  Any bounce will be sold off as so much damage has been done  some hedge funds r blowing up soon Margin calls r killing retails </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 06:46:20 </td>
   <td style="text-align:left;"> $SPY $UVXY $AAPL 

I love to see it, you little bitches 📉 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 06:45:43 </td>
   <td style="text-align:left;"> $AAPL this will get destroyed after earnings. you heard it here first </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 06:43:02 </td>
   <td style="text-align:left;"> $ISPC fuck what a shit show with this stock.. I am loosing my ass on this and $lgvn.. shoukd have taken profit at day after thanksgiving or on Christmas Eve .. now it’s all shit show.. if fed makes good decision next week and market recovers I will go all in on $aapl or $tsla or best $baba.. will take my losses on $ispc and $lgvn.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 06:42:35 </td>
   <td style="text-align:left;"> $AAPL $100 soon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 06:37:55 </td>
   <td style="text-align:left;"> $AAPL 140 next area </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 06:31:15 </td>
   <td style="text-align:left;"> $SPY  Wisdom after some Selling 
 
$bb $amzn $aapl $jpm </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 06:30:45 </td>
   <td style="text-align:left;"> $AAPL What stock do we think falls like Netflix next?. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 06:30:07 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-01-21 Largest Trades Data: 
https://www.youtube.com/watch?v=C0JE78k2Z6Q </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 06:28:13 </td>
   <td style="text-align:left;"> $BTC.X wish I had more cash to buy more bitty. 
 
$SPY $QQQ $TSLA $AAPL fuck the old system </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 06:22:16 </td>
   <td style="text-align:left;"> $DJIA $SPY $NFLX $AAPL 
So if you look at the data, an insane amount of money was dumped from Goldman, Chase and BoA. It was dumped in coordination 2 days ago. Possible theory… The dystopian Biden regime has brought nothing but crime, division, racial hatred, record inflation and well over 2.4 million illegal border crossers since Jan 2021. The most ever recorded. Logic, history and human behavior tells you that when tyrants or ruling parties begin to fail they need to foster a diversion. Based on the financial data, it is possible they may be preparing to start a war or allow for their media monoply to broadcast and propagandize the precipice of one? The next 2 weeks will be interesting… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 06:21:10 </td>
   <td style="text-align:left;"> $MSFT $AAPL $LCID $COIN $NET 

Anyone else find themselves becoming an avid day drinker </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 06:18:56 </td>
   <td style="text-align:left;"> $AAPL  Monday Bounce $SPY  #WhosKnow??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 06:15:46 </td>
   <td style="text-align:left;"> $AAPL 200+ million in volume 😳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 06:14:10 </td>
   <td style="text-align:left;"> $F $TSLA $MSFT $AAPL I sold half my stocks in November and then all of the rest this past week. I see the market falling so much more very soon. Tesla might hit $750 soon, and I&amp;#39;m just happy locking in profits. The pandemic stock market dream is over when Powell Hour comes </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 06:12:02 </td>
   <td style="text-align:left;"> The magic question on many people’s minds is.. 

BUY

$MSFT @ $270

OR

$AAPL @ $125

“Both” answers don’t count :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 06:11:51 </td>
   <td style="text-align:left;"> $AAPL Time to buy soon 👍🏼 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 06:10:56 </td>
   <td style="text-align:left;"> $AAPL EXPECT losses on open Monday and Tuesday Apple will go into the lower 158 to 161 range. Called 165 and 162 hope people made money on puts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 06:10:55 </td>
   <td style="text-align:left;"> $AAPL If you liked it at 175 then you’ve got to love it at 162. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 06:09:46 </td>
   <td style="text-align:left;"> $AAPL 🍏💪 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 06:09:30 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $AAPL latex509e7c81af61a4ce2923ed21d790514cTSLA Wednesday 
$AAPL Thursday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 06:00:25 </td>
   <td style="text-align:left;"> $AAPL 155P Exp:28-Jan-22 --  🔥🔥 Total(Day): $139,474 
#UnusualActivity 
 
 
Sign-up free for beta ver.:https://app.jarvisalerts.com 
charts: courtesy of finviz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 06:00:22 </td>
   <td style="text-align:left;"> $AAPL 150P Exp:17-Jun-22 ↑  🔥🔥 Total(Day): $74,165 
$AAPL 155P Exp:18-Nov-22 ↓↓  🔥 Total(Day): $44,160 
$AAPL 155P Exp:16-Sep-22 ↑  🔥 Total(Day): $98,355 
#UnusualActivity 
 
 
Sign-up free for beta ver.:https://app.jarvisalerts.com 
charts: courtesy of finviz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 06:00:18 </td>
   <td style="text-align:left;"> $AAPL 145P Exp:18-Mar-22 ↑↑  🔥🔥 &amp;lt;R&amp;gt; Total(Day): $128,023 
$AAPL 150P Exp:18-Feb-22 ↑  🔥🔥 &amp;lt;R&amp;gt; Total(Day): $101,812 
$AAPL 150P Exp:19-Jan-24 ↓  🔥 &amp;lt;R&amp;gt; Total(Day): $221,607 
#UnusualActivity 
 
 
Sign-up free for beta ver.:https://app.jarvisalerts.com 
charts: courtesy of finviz </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:58:24 </td>
   <td style="text-align:left;"> $SPY best case scenario... Putin invades and the fed raises interest rates same week. Just rip the fkn band aid off. That simple 😬
$QQQ $AAPL $TSLA $AMZN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:53:13 </td>
   <td style="text-align:left;"> $NVDA $AAPL these two will not be spared in the correction underway </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:53:02 </td>
   <td style="text-align:left;"> $AMZN $AAPL $LCID $FSR $NFLX 
We miss you! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:52:18 </td>
   <td style="text-align:left;"> Wow this is a big change! $AAPL&amp;#39;s price moved below its 50-day Moving Average on January 19, 2022. View odds for this and other indicators: https://srnk.us/go/3344739 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:50:55 </td>
   <td style="text-align:left;"> $BABA  I dont care how much good news is out there Sentiment &amp;amp; group think can not stop a stock from taking a hit on a day like this. 
 
Don&amp;#39;t take it personally, its not   
$jd $bb $amzn $aapl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:50:00 </td>
   <td style="text-align:left;"> $AAPL  
 
AAPl Happy Friday everyone - take a step back, relax and enjoy the weekend. I know it&amp;#39;s been a rough trading week but have to keep things in perspective.  
 
Still seeing a strong trend across social - good momentum. Going to keep and eye on the &amp;quot;whale&amp;quot; accounts. You can check out teh trend for the last 24 and 72 hrs. Should be interesting to see over the weekend.  
 
https://utradea.com/social-dashboard?utm_source=stocktwits&amp;amp;utm_medium=ssd-stocktwits&amp;amp;utm_campaign=sm_20220121 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:49:52 </td>
   <td style="text-align:left;"> $AAPL  just keep holding </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:48:04 </td>
   <td style="text-align:left;"> $SHOP $TSLA $AMZN $AAPL 

Waiting for the FED rate increase — 
It will shave another 10-15% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:47:53 </td>
   <td style="text-align:left;"> $AAPL Dan Niles FYI Apple isn’t only smartphones, Have u tried to use a Macbook Pro or Imac?? Or Ipad or Apple watch , Airpods?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:47:33 </td>
   <td style="text-align:left;"> $AAPL not your beloved Apple </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:46:12 </td>
   <td style="text-align:left;"> $SPY $BTC.X $tsla $aapl who has been here trading or doing business like me, back in 2008-2010? I’ve learned one thing on a crisis- cash is king. Nothing else. Have a cash pillow. Now that all will go bk, I’ll buy their businesses for pennies on the dollar. Current generation of tik tok btd traders has never seen a crisis.. and well.. most won’t make it out. I didn’t become rich but I stayed afloat which is better than 85% of traders. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:42:56 </td>
   <td style="text-align:left;"> $AAPL  🍏 Shock:  CNBC:  Dan Niles, says Technicals led him to consider that Today may have been the Mkt Bottom. And, he bought “some” Today.  Also, says he Closed some of his Shorts this Week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:42:46 </td>
   <td style="text-align:left;"> $AAPL Apple hater on CNBC, boy he looks like a CROOK! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:41:12 </td>
   <td style="text-align:left;"> $SPY Next week it will be $AAPL $MSFT and $GOOG pulling down the market . This week it was NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:40:23 </td>
   <td style="text-align:left;"> $SPY Last year I was discussing often about the problem w/  
$BTC.X &amp;amp; how if it fell it was going to affect the Market just from Margin Calls, it has. $AAPL held up today ok considering the BTC drop.  
  
We knew Jan was going to be ugly, we knew tax loss deferment was why 2021 ended the way it did &amp;amp; why we have selling now so the Market move does make sense.  
  
Sometimes its just using common sense w/out the need to get into the weeds. When $NFLX came out saying they would raise fees a week before their ER how could anyone think that was a good sign going into Earnings? yet some were still buying &amp;amp; got upset when I posted this  
 
$qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:40:13 </td>
   <td style="text-align:left;"> $AAPL if you haven&amp;#39;t bought during this ULTRA fear, your loss babies x </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:38:18 </td>
   <td style="text-align:left;"> $AAPL how does who voted for joe like the... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:38:09 </td>
   <td style="text-align:left;"> latexc90bdf9d3fb6c72a49a3d5dcc501e105NVDA 1.070m (55% call/45% put)
$F 942k (55% call/45% put)

Lynk in bayo for option trading ideas 💡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:31:07 </td>
   <td style="text-align:left;"> $AAPL huh how come it isnt puking after hours by another $2 ? Oh right, Buffoon isnt talking. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:28:34 </td>
   <td style="text-align:left;"> Bought $VOO $AAPL &amp;amp; $TSLA Today in the ROTH IRA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:28:10 </td>
   <td style="text-align:left;"> $AAPL this gunna be the next bubble to burst? Asking for a friend </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:26:50 </td>
   <td style="text-align:left;"> $AAPL buy the dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:25:05 </td>
   <td style="text-align:left;"> $AAPL $165 MONDAY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:25:05 </td>
   <td style="text-align:left;"> $AAPL $DIS dont Worry folks, with the the sell offs. Game stop was green today. Market is filled with trash 🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:24:35 </td>
   <td style="text-align:left;"> $AAPL Longs you had a great day  ... compared to other FANG stocks AMZN/TSLA down almost 6% each.  This should have been down $6-$7.  So congrats on a great day, be happy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:24:00 </td>
   <td style="text-align:left;"> $AAPL 165 Monday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:23:15 </td>
   <td style="text-align:left;"> $TSLA $AMD $AAPL $NVDA $NASDAQ  
https://www.marketwatch.com/story/nasdaq-composite-has-logged-65-corrections-since-1971-and-as-it-heads-for-66-heres-how-the-stock-index-tends-to-perform-afterward-11642623639?siteid=yhoof2 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:21:03 </td>
   <td style="text-align:left;"> $SPY Wait to $AMZN and $AAPL get crushed, recession looming.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:19:40 </td>
   <td style="text-align:left;"> $NVDA hope you sold youre puts $QQQ $AAPL $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:17:25 </td>
   <td style="text-align:left;"> $AAPL   🍏 CNBC:  Coming up:  Leave it to Sara Eisen, to have as her Guest, Dan Niles…Short-Sjde Money Manager &amp;amp; AAPL Bear.  Remember, he is not an Analyst.  This is typical Sara Eisen…aka, “Market in Turmoil” Witch. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:17:20 </td>
   <td style="text-align:left;"> $MSTR lovely banking heavy. 💰💰🤞🧸

$AAPL $BTC.X $ETH.X $MARA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:15:56 </td>
   <td style="text-align:left;"> $AAPL  
 
Below $160 for sure! likely hits $150  
 
Got puts at $166 for April, let´s collect money! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:14:35 </td>
   <td style="text-align:left;"> $AAPL this has dropped more than 10% from its recent 52 week high </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:14:20 </td>
   <td style="text-align:left;"> $AAPL 130 after ER </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:13:47 </td>
   <td style="text-align:left;"> $AAPL Volume was again 20% above average. When weak hands sell, ask yourself who is buying. Wallstreet and all the other Gangsters are doing this every year around January or February. The only difference is the &amp;quot;reason&amp;quot; for the drop. CNBC has every year a new reason. They are certainly &amp;quot;creative&amp;quot; but still do not have a clue. This year it is the &amp;quot;inflation&amp;quot; and actions of FED. Well, this explains a negative index in Europe and Japan? Clueless... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:13:44 </td>
   <td style="text-align:left;"> $AAPL/$QQQ: love apple. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:13:35 </td>
   <td style="text-align:left;"> $AAPL least apple is holding strong compare to other stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:12:45 </td>
   <td style="text-align:left;"> $AAPL $$$$$$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:12:37 </td>
   <td style="text-align:left;"> Investors Are Giving Up on Netflix. That Makes It a Good Time to Buy the Stock.  $NFLX $DIS $AAPL $ROKU $VIAC 

https://newsfilter.io/a/3977bee48a96983717c6935ad8cec09e </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:12:00 </td>
   <td style="text-align:left;"> $AAPL  🍏CNBC:  Tony Dwyer, says:  “We are due for Bounce”.  “Interest Rates, retraced during the week”.  “The Mkt will look to MegaCap to Bounce first, and lead Mkt higher”. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:11:59 </td>
   <td style="text-align:left;"> $AAPL not a bad day at all considering another terrible day in the market </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:09:12 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:07:53 </td>
   <td style="text-align:left;"> $U $AAPL $AMZN $ANKR.X 

The tide will turn, selling pressure will exhaust as earnings come into play. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:07:35 </td>
   <td style="text-align:left;"> $AAPL finishes down 1.28% to $162.41 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:06:32 </td>
   <td style="text-align:left;"> $AAPL the pullback from the peak can reach $162.10- $152.80 area lower where buyers should be waiting to appear again #elliottwave #trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:05:29 </td>
   <td style="text-align:left;"> We have identified an unusual $AAPL block that expires on February 18, 2022 with a strike price of $150.00.

9,628 PUT contracts with a price of $2.58 (Mid-Market) were purchased at a $2,484,024 premium. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:04:53 </td>
   <td style="text-align:left;"> $AAPL monday more drop, careful a lot bad news and market not steady </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:04:44 </td>
   <td style="text-align:left;"> +$580 trading latex302603cb8c289030f690d5ca62274370NFLX was on radar but no day trade setups available.  I did start a nugget sized starter for a swing as I see major areas of support at latex1be010beb95f9277dd2260814022064cAAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:04:10 </td>
   <td style="text-align:left;"> latexac6f0c2161b3bac7df6c02e74bed2bf0PTON + latex45afdcb40a78c86416a6e9357806ebdeMSTR - SEC Rejects BTC accounting
$NVDA + Raises EU Prices

Live Breaking trading news
www.openoutcrier.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:03:58 </td>
   <td style="text-align:left;"> $AAPL right side is bullish on higher time frames. We only like to buy it in 3, 7 or 11 swing at the blue boxes. We still favor lower to take place before the blue box equal leg is hit, which can play a part in dragging world indices lower in the sessions to come. #Elliottwave #Trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:03:54 </td>
   <td style="text-align:left;"> $PLUG $FCEL $ENPH $AAPL $AMZN  
OVERDONE. 💪💪🦬 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:03:41 </td>
   <td style="text-align:left;"> $AAPL Sweet dump at the close. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:03:09 </td>
   <td style="text-align:left;"> $AAPL AAPL 2022-01-21 Technical Analysis Video: 
https://www.youtube.com/watch?v=MTKVrEGEz38 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:02:22 </td>
   <td style="text-align:left;"> $AAPL 170C expiring 1/28 😳 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:02:18 </td>
   <td style="text-align:left;"> Re-adding /VX short 27.40

$SPY $BTC.X $TQQQ $UVXY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:01:38 </td>
   <td style="text-align:left;"> Bears Grab Ahold Of Amazon Stock As Market Falls Into Turmoil: What&amp;#39;s Next?  $AMZN $SPY $AAPL $MSFT 

https://newsfilter.io/a/c4845b0609b1e724b40cd28690eb7bbc </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:01:36 </td>
   <td style="text-align:left;"> $SPY Tony on CNBC, watch him! 
 
$aapl $baba $jd $amzn </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:01:29 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

SOLID WORK TODAY BEAR BROTHERS

🐻 HAVE 💎 🙌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:01:07 </td>
   <td style="text-align:left;"> $AAPL drop to $130 for a slingshot? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 05:00:11 </td>
   <td style="text-align:left;"> $AAPL 1hr view from 1/14 Pre-Market update presented to members at elliottwave-forecast.com/ #elliottwave #trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:59:16 </td>
   <td style="text-align:left;"> $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:59:12 </td>
   <td style="text-align:left;"> $AAPL The algos got the bears eating good AF.. inflationGate. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:59:10 </td>
   <td style="text-align:left;"> $AAPL Who voted for Sleepy Jose.. hahahha. Sh I t. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:58:53 </td>
   <td style="text-align:left;"> GOLDEN SWEEP OPTION ALERT: $AAPL $167.5 CALLS Expiring on 01/28/22; Premium: $1.2M; 🟢BULLISH More details at https://marketaction.live/cyber-monday-sale/ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:58:21 </td>
   <td style="text-align:left;"> $AMZN $nflx $pton $DWAC $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:58:16 </td>
   <td style="text-align:left;"> $AAPL 🩸🩸🩸
$149* </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:58:11 </td>
   <td style="text-align:left;"> $AMZN $NFLX $AAPL   COVID booming companies going to take a huge punch to the face... netflix now, amazon and apple soon.  COVID suffering stocks going to boom this year, $WYNN $UAL double you up. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:56:49 </td>
   <td style="text-align:left;"> $AAPL #Apple video from 12 January looking at the #Elliottwave path https://www.youtube.com/watch?v=q1xLRP7d8LA  #trading </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:56:24 </td>
   <td style="text-align:left;"> $AAPL ok lets close above 163 lmao i know we can! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:56:20 </td>
   <td style="text-align:left;"> Mid-morning push on $AAPL was looking strong... until it ran into the prior day&amp;#39;s VWAP. 
 
Reversed from there and faded alongside the broader market into the afternoon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:55:45 </td>
   <td style="text-align:left;"> $SPY so this is what the fed tampering leads to? Everything destroyed accept $aapl and $tsla ? 😂 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:55:22 </td>
   <td style="text-align:left;"> $QQQ $AAPL $GOOG $AMZN $FB 

This has happened before the last few tech earnings , huge sell offs but nothing as big as this sell off -  makes me believe they are going to beat huge on earnings and allow for huge runs back up . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:54:18 </td>
   <td style="text-align:left;"> $AAPL loaded apple yolo calls for next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:54:12 </td>
   <td style="text-align:left;"> $aapl Fill it! $170 call lol. no ones selling! oh it just filled hehe for 2. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:54:08 </td>
   <td style="text-align:left;"> $AAPL  🍏 Remember, $Trillions in OpEx, expire Today.  Today, is one of the largest “Mkt Wide” Monthly Options Expirations in History. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:53:50 </td>
   <td style="text-align:left;"> $AAPL BUY AAPL A HEDGE AGAINST BIDENFLATION !!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:53:44 </td>
   <td style="text-align:left;"> $AAPL Buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:53:40 </td>
   <td style="text-align:left;"> $AAPL my commons look gross but DAMN the Puts day trade was amazing today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:53:26 </td>
   <td style="text-align:left;"> $SPY $DJIA $AAPL Bulls... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:53:02 </td>
   <td style="text-align:left;"> $AAPL Who see a green closing.👍👍👇 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:52:20 </td>
   <td style="text-align:left;"> $AAPL caught that dip!! I actually bid 1.42 because i wanted to close it bad. was slapping the ask. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:51:52 </td>
   <td style="text-align:left;"> $AAPL Chart of The Day 12 January: #Apple can see further downside https://elliottwave-forecast.com/stock-market/elliott-wave-view-apple/  #elliottwave #trading #stocks </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:51:23 </td>
   <td style="text-align:left;"> $MSFT barely red. Hmm. $AAPL as well. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:50:46 </td>
   <td style="text-align:left;"> $AAPL SELL SELL SELL !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:49:36 </td>
   <td style="text-align:left;"> Where to Find Stock Bargains Amid the Tech Wreckage  $AAPL $GOOG $MSFT $FB $ZM 

https://newsfilter.io/a/a5efdea96a00bf25535e5cd86f6a8a9b </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:48:50 </td>
   <td style="text-align:left;"> $AAPL no Bidenflation =  we need Kevin Durant back KD !!   we need Kevin durant back KD !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:47:39 </td>
   <td style="text-align:left;"> $FUBO would $AAPL buy FUBO 🤔
With Netflix returning to earth, can streaming rivals make gains? https://seekingalpha.com/news/3790387-with-netflix-returning-to-earth-can-streaming-rivals-make-gains?source=copyToPasteboard </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:47:15 </td>
   <td style="text-align:left;"> LOL. Well this doesn&amp;#39;t look good.  
 
$AAPL $MSFT   
 
Not to worry. Just temporary. Buy the dip. Just like inflation this selling is &amp;quot;transitory&amp;quot; LOL. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:47:11 </td>
   <td style="text-align:left;"> $AAPL  . Earnings . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:46:12 </td>
   <td style="text-align:left;"> $SPY $TSLA $AMZN $AAPL dinner is served </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:46:04 </td>
   <td style="text-align:left;"> $AAPL    🍏 Look Traders!  The OpEx Derivative Players, can Short the price on no Volume…but, WallSt, Tutes, &amp;amp; Sovereigns, are Buying like crazy at the Dipped Prices.  Massive accumulation all Day. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:45:53 </td>
   <td style="text-align:left;"> $AAPL is holding so well over this market correction. Time to buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:45:36 </td>
   <td style="text-align:left;"> $AMD 
Shake the paper hands out $AAPL $MSFT $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:45:17 </td>
   <td style="text-align:left;"> $AAPL 

These shorts are holding all stocks as hostage.

We need to fk them out! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:45:00 </td>
   <td style="text-align:left;"> $AAPL has a Return On Equity of 150.07%. This is amongst the best returns in the industry. https://www.chartmill.com/stock/analyzer/stock/AAPL?view=fundamental-analysis&amp;amp;key=bb853040-a4ac-41c6-b549-d218d2f21b32&amp;amp;utm_source=stocktwits&amp;amp;utm_medium=FA&amp;amp;utm_content=AAPL&amp;amp;utm_campaign=social_tracking </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:44:02 </td>
   <td style="text-align:left;"> $RBLX #Shortsqueeze into close. M&amp;amp;A in gaming heating up. $FB $AAPL or $AMZN all would love to buyout $RBLX.  $100 a share sounds about right. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:44:01 </td>
   <td style="text-align:left;"> $AAPL thank lets go brandon for the entry point </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:43:33 </td>
   <td style="text-align:left;"> $AAPL $MSFT What do you think about next week’s ER? 📈 or 📉? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:43:22 </td>
   <td style="text-align:left;"> $AMD Yes today’s last hour what matters. This hour tells if they buying the dip or want way more down. Nasdaq Spy bottom is around us. $SPY $AMZN $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:43:16 </td>
   <td style="text-align:left;"> $AAPL WHO CARES? 

If you are long you just have to sit back and laugh. 

We are all the way back to November levels?  Nope.   December. 

On December 3rd AAPL closed just over 161.  

So I’m just sitting here watching the world burn knowing 200 is that much closer now. We been waiting for the 10% pullback for months. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:42:19 </td>
   <td style="text-align:left;"> $AAPL 

101 million traded hand we are still at war to stop the fall! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:41:22 </td>
   <td style="text-align:left;"> The scary thing about $QQQ is that $AAPL $TSLA are still not at bottom yet. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:39:25 </td>
   <td style="text-align:left;"> $AMZN war in Russia guys.... damp everything!!! $AAPL $SKY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:38:56 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL 

LOL!!! cnbc is still tryna pump this 
market!!!! 🤣🤣🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:38:25 </td>
   <td style="text-align:left;"> $AAPL - Pay good attention to the technicals.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:37:59 </td>
   <td style="text-align:left;"> $AAPL HEY TIMMY IT&amp;#39;S TIME to speak to the masses.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:36:32 </td>
   <td style="text-align:left;"> $FB $MSFT $AAPL  $AMZN Should I buy puts for all of them as YOLO earnings selloff? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:35:52 </td>
   <td style="text-align:left;"> $NIO $AAPL $AMD $VORB you go red you go red everybody go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:34:40 </td>
   <td style="text-align:left;"> $AAPL 

Unbelievable.. they are letting the red to continue until next week .. when we have no control to stop and fix that VIX … with many short attacks ..

It makes no sense at all..

It ignores many strong news for AAPL. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:34:17 </td>
   <td style="text-align:left;"> $NASDAQ $AAPL $TSLA $NIO
This market will not bounce back until all mid-cap stocks becomes penny stocks 🤣. What heck is going on? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:33:42 </td>
   <td style="text-align:left;"> $AAPL if you can’t see that this is a easy ride to $180 plus as soon as they stop scaring the retail investors out. My target price is a layup at $200! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:33:22 </td>
   <td style="text-align:left;"> Unusual Option Alert on $AAPL $858,381 call sweep traded with $160.0 strike expiring on 2022-02-18. Via: https://www.stockgrid.io/optionsflowcumulativestats/AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:33:14 </td>
   <td style="text-align:left;"> $AAPL Long @ 162.78 Target @ 165.26 Stop Loss 159.00 will sell spot on 163.65 No time to update sorry guys just follow my lead </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:33:02 </td>
   <td style="text-align:left;"> $AAPL bullish af for next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:32:26 </td>
   <td style="text-align:left;"> $QQQ $SPY $PLTR $AAPL $FB 

Blamed it all on the 10 year ? It’s dropped quite a bit and crickets ? What’s the game here . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:32:22 </td>
   <td style="text-align:left;"> $AAPL it no longer power hour. it’s just power half hour haha </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:32:11 </td>
   <td style="text-align:left;"> $AAPL just sold all 25 puts of 165 for $2.40 a piece. I. Ought each for .25. Lotto! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:31:52 </td>
   <td style="text-align:left;"> $TSLA bears really don’t know what’s at stake … if $AAPL and $TSLA fall it will cause a recession and they’ll lose their McDonald’s jobs </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:31:48 </td>
   <td style="text-align:left;"> $AAPL $MSFT $TSLA Sentiment has shifted. Next week, earnings and Powell Hour will likely bring the market down even further. We&amp;#39;re clearly in a falling knife </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:31:20 </td>
   <td style="text-align:left;"> $AAPL needs to fall more for market correction....looking for the bottom around $145-150. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:30:53 </td>
   <td style="text-align:left;"> $AAPL 1% Jesus come on! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:30:14 </td>
   <td style="text-align:left;"> $AAPL There is a fine line between correction and manipulation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:30:03 </td>
   <td style="text-align:left;"> $AAPL buy all you can </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:30:01 </td>
   <td style="text-align:left;"> $SPY anyone grabbing $AAPL puts? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:29:55 </td>
   <td style="text-align:left;"> $AAPL ✅
Next support level! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:29:40 </td>
   <td style="text-align:left;"> $AAPL devastating month so far in the stock , down over 10%.  any sign of a rebound? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:28:17 </td>
   <td style="text-align:left;"> $RBLX will wait for it to test the $60 level which is also its all time low .  No point being a hero.  The really sell-off will probably end when $aapl and $msft fall 20% </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:28:09 </td>
   <td style="text-align:left;"> $AAPL Where did he place his bet? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:25:29 </td>
   <td style="text-align:left;"> $QQQ $SPY $AMD $AAPL $SHOP  
Who is bahhhhing the dip here? Buy when there is blood in the streets! It always works, until it doesn’t. I’m ready for a 🐑 in turmoil special on CNBC… just wait and see! Err can you even see? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:25:18 </td>
   <td style="text-align:left;"> $AAPL this is the shorts/bears one last hoorah for a while… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:25:02 </td>
   <td style="text-align:left;"> $AAPL options gamblers desperate blaming Brandon for this mkt correction 🤦🏼 and Brandon doesn’t even acknowledge that the mkt exists. 😂. The fact is that Brandon inherited the Powell printer and now P is turning it off. Mkt corrections are normal, as it always happens, it will come back up. $SPY </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:24:39 </td>
   <td style="text-align:left;"> $AAPL 

It is what it is !! It’s already down $20 from ATH …

I think algo is really bullshit .. no question..  they are trying to erase other investors gain from Santa rally! 

This is really pure manipulation! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:23:56 </td>
   <td style="text-align:left;"> $AAPL $SPY $QQQ is VIX Going to hit 35 next week, maybe 50? Nothing looks good. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:22:40 </td>
   <td style="text-align:left;"> $AAPL Buyers bought AAPL @ 180 as a hedge against Bidenflation !!! oops </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:21:58 </td>
   <td style="text-align:left;"> $ARKK $AMZN $AAPL $NFLX Adding today right thru the panic. Not all in, just a slow add everyday as people panic. I have no doubt the Hedgies yelling about a 50% crash are also adding today.  

My strategy is to add a little on red days thru March.  This is not cOvid but a speculation that inflation “may” continue to rise and Powell “may” do 7 rate hikes. 

Cathy and I think not and are adding but staying away from the Margin. 

Have a nice weekend and take it easy man </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:20:55 </td>
   <td style="text-align:left;"> $AAPL safest stock ever </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:20:41 </td>
   <td style="text-align:left;"> $SPY Still not sure how we close, waiting for after  3:40 for the real Tell. 
 
Just saw a lot of MOC Orders come through but trusting WS is like,.. trusting WS :o)  
 
Its Chess folks so there&amp;#39;s a lot of game left to play today 
 
$baba $bb $aapl $nflx </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:20:40 </td>
   <td style="text-align:left;"> $AAPL 
The crown jewel 💎 should not be touched to the moon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:20:16 </td>
   <td style="text-align:left;"> $AMD $NVDA $AMZN $AAPL $SPY 
As I mentioned earlier, today’s final hour is kinda telling after this much of shit show . We gonna see if JP morgan goldman and hedge funds who asked us to buy the dip weeks ago are buying the dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:19:48 </td>
   <td style="text-align:left;"> Covered half /VX short +0.50 points

$SPY $BTC.X $TQQQ $UVXY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:19:25 </td>
   <td style="text-align:left;"> $AAPL heading to 150s. Put your puts in sell off is not done. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:18:57 </td>
   <td style="text-align:left;"> $AAPL Apple needs to be beat down ... this is BS ... TSLA down 5%, AMZN down 6% ... it&amp;#39;s coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:18:51 </td>
   <td style="text-align:left;"> $AAPL nearly two weeks of red..hanks democrats for the inflation. Markets down to worst week since Covid 19 hit originally. Fucking idiots </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:18:41 </td>
   <td style="text-align:left;"> $AAPL wait for ppl to throw towel. 160 coming your way. Matter of time. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:18:35 </td>
   <td style="text-align:left;"> $SPY $BTC.X $AAPL $TSLA $QQQ Remember liberals, you voted for this absolute fraud </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:18:30 </td>
   <td style="text-align:left;"> $AAPL smh was hoping to close short calls.. hopefully theta rips them apart by close. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:18:26 </td>
   <td style="text-align:left;"> $AAPL surprised this is holding. Market is a bloodbath </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:17:47 </td>
   <td style="text-align:left;"> $AAPL BRANDON BEAR MARKET FOR THE NEXT YEAR LIKE IN THE 70&amp;#39;S !!!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:16:46 </td>
   <td style="text-align:left;"> $AAPL Hey GME up 3%, PTON up 12% such valuable companies to go up like that, give me a break CROOKS! SEC, look into the algos of the CROOKS! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:16:43 </td>
   <td style="text-align:left;"> $AAPL you can thank biden/harris. They care more about BLM than the american ppl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:16:36 </td>
   <td style="text-align:left;"> $AAPL WHO AGREES FOR FIRING OF FED POWELL FOR CAUSING UNWARRANTED PANIC AND CARNAGE IN MARKETS? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:16:35 </td>
   <td style="text-align:left;"> Netflix Needed a Big Beat—All We Got Was More Questions  $NFLX $DIS $AAPL $ROKU $VIAC 

https://newsfilter.io/a/062017791c0fe932f7d1124707326648 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:16:27 </td>
   <td style="text-align:left;"> MOVES HAPPENING NOW (3:16pm)

⦿ $AAPL is down 0.2% in the last 5 mins. 

⦿ There are 8 stocks that are up more than 3% in the last 5 mins. 

⦿ The top gainer is up 6.9% in the last 5 mins. 

 See the stocks that are moving the most right now via link in bio (wallstreetodds .com). </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:16:13 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ $AAPL

Add to your short positions bear 

brothers!!! 

🐻 have 💎 🙌 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:16:10 </td>
   <td style="text-align:left;"> $AAPL 157 next? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:15:56 </td>
   <td style="text-align:left;"> $AAPL LETS GO BRANDON !!! LGB !! AAPL !! NFLX !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:15:05 </td>
   <td style="text-align:left;"> $AAPL trading beautifully off the 30mn / 290 ma </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:14:29 </td>
   <td style="text-align:left;"> $QQQ $SPY $AAPL $MSFT massive dumping late into the day. Put sweeps rolling in for next week. Earnings will be amazing can’t wait. Great end to another volatile week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:14:19 </td>
   <td style="text-align:left;"> $AAPL $150 next Friday puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:14:10 </td>
   <td style="text-align:left;"> $spy Tony Dwyer will be on CNBC today, there are very few reason to ever put the sound on w/ CNBC is on but Tony is one of the smartest Analyst on WS, I read his note everyday. 
 
He was on CNBC a few weeks ago when the Market was up saying to expect this drop &amp;amp; Scott Wapner (that idiot) gave him a hard time. 
 
If you listen to anyone on WS listen to Tony, hes the real deal 
 
$aapl $baba $amzn $qqq </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:14:09 </td>
   <td style="text-align:left;"> $AAPL     🍏 Massive Shorting, to Dip “Price for Bearish OpEx”.  No Volume with the Dips.  This is not “Selling”.  This is “Targeted Shorting”.  AAPL, is still under “Accumulation”…look at technicals. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:14:09 </td>
   <td style="text-align:left;"> $QQQ This is down with only one of the FANNG stocks going bust. The next two weeks will see more ERs from the big guns in the index. If $AAPL or $MSFT even gives a hint of bearishness the Qs will see 340 or lower. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:14:07 </td>
   <td style="text-align:left;"> $AAPL  today AAPL will be at least 20 % down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:13:57 </td>
   <td style="text-align:left;"> $AAPL 150 to 155 puts for next week market will be red. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:13:57 </td>
   <td style="text-align:left;"> $AAPL 
Thanks Joe. Heck of a job you’re doing with the economy. Keep up the good work. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:13:50 </td>
   <td style="text-align:left;"> $AAPL loaded big calls 162.5 / 165 calls for next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:13:33 </td>
   <td style="text-align:left;"> AAPL Aggressive Elevated Risk: Apple Inc $AAPL triggered at $163.00 on 21-Jan-22 EST http://dlvr.it/SHZ6tf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:13:20 </td>
   <td style="text-align:left;"> $AAPL apple headed to 150s range. Next week will be red. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:13:18 </td>
   <td style="text-align:left;"> $AAPL Biden&amp;#39;s Market Bear market - Lets Go Brandon !!! LGB !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:12:52 </td>
   <td style="text-align:left;"> $AMZN $SPY OMG 😰
$TSLA &amp;amp; $AAPL next dump for overvaluation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:12:32 </td>
   <td style="text-align:left;"> $AAPL oh god i just hope it doesnt go below 160 by next weeks close lmao. Shorted HELLA puts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:12:11 </td>
   <td style="text-align:left;"> $AAPL sold my puts and bought call here. should go up next week into earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:12:00 </td>
   <td style="text-align:left;"> $AAPL about to get clapped next week, on the road to $130. Gonna miss earnings too! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:11:57 </td>
   <td style="text-align:left;"> $AAPL 150 puts still looking good </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:11:07 </td>
   <td style="text-align:left;"> $AAPL last time Daily RSI was this low was when it saw 120 close post 116 intraday... Soo more or less, should be fine soon </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:10:33 </td>
   <td style="text-align:left;"> $AMD guys... this price action in the last month for tech... is the fear of war Russia Ukrain.... get out now!!! war is imminent... they do not want to colapse it by anounce it ...yet!!! $SPY $AAPL </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:10:28 </td>
   <td style="text-align:left;"> $AAPL when will you learn I said a reversal was inbound. I said stock went to 165 and would go to 162. Puts make profit too. There is more loss on apple it might head to 150s territory next weak. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:10:17 </td>
   <td style="text-align:left;"> $AAPL swung puts for a small profit. It was a roller coaster. Not doing it again lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:10:12 </td>
   <td style="text-align:left;"> If $AAPL made a play on scooping $PTON for the low that&amp;#39;d be all time but I don&amp;#39;t think Cook has it in him </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:10:04 </td>
   <td style="text-align:left;"> $AAPL they are going to give extreme max pain .. that’s what they wanted !! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:09:59 </td>
   <td style="text-align:left;"> $AAPL Brutal ... Dip buyers have been crushed over the last couple weeks. Resist and wait for 150&amp;#39;s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> AAPL </td>
   <td style="text-align:left;"> 2022-01-22 04:09:52 </td>
   <td style="text-align:left;"> $AAPL Like an iron boot to the balls. This entire week was bloody </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:42:04 </td>
   <td style="text-align:left;"> $TSLA I’ll wait for you…meet me where I am </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:41:25 </td>
   <td style="text-align:left;"> $TSLA fine! take your time :) </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:41:00 </td>
   <td style="text-align:left;"> $TSLA earnings will be bad. Like q4 of 2020 save the red for end of year </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:39:35 </td>
   <td style="text-align:left;"> $TSLA tHiS stoNk iZ woRTh 3o00$! buY DIp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:37:59 </td>
   <td style="text-align:left;"> $TSLA Black Monday 2.0 or what? Shame that you were so willing to be robbed like this. I will never understand you. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:37:32 </td>
   <td style="text-align:left;"> $TSLA I get it. Bulls bought this for cheap and are in love with the stock. The same bulls would never buy a Tesla car. Probably follow Elon on twitter and like all his posts, even if they make no sense. This company should be worth $ 10 trillion. Scratch that. $ 20 trillion. Undervalued af. Electric cars are amazing. Maybe they will fly one day...so add another 20 trillion USD. Fair value therefore should be $ 40 trillion + 5 trillion extra for the unfunny memes. $ 45 trillion. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:36:53 </td>
   <td style="text-align:left;"> $TSLA ThIs iS gOiNg To SkY rOcKeT aFtEr ErNiNgS 🤡 your calls are worthless. Thanks for your money you bozos. To the moooooooooon 🤣🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:35:08 </td>
   <td style="text-align:left;"> $TSLA 
1/24 - $960
1/25 - $990
1/26 - $1,015
1/26 AH - $1,080
1/27 - $1,090
1/28 - 1,075
1/31 - 1,115
2/1 - $1,130
2/2 - $1,110
2/3 - $1,140
2/4 - $1,130
2/7 - 1,160
2/8 - 1,210
2/9 - 1,240
2/10 - 1,250
2/11 - 1,230 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:35:00 </td>
   <td style="text-align:left;"> $TSLA this is going to skyrocket after earnings 🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:33:11 </td>
   <td style="text-align:left;"> $SPY McClellan Oscillator a reliable tool for judging overbought and over sold mkts.  We are near the lowest level in 2 yrs. Only time lower was Covid crash and Dec 2018 correction. Monday or Tuesday could be the turn around days.. atleast the Breadth picking up. $DIA $TSLA $QQQ $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:32:37 </td>
   <td style="text-align:left;"> $TSLA Nikola Tesla want his name back from the fraudster. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:32:24 </td>
   <td style="text-align:left;"> $TSLA Hope some if you took some lottos 👻👻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:32:15 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-21 Options Analysis Video: 
https://www.youtube.com/watch?v=8shs44RSodk </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:32:09 </td>
   <td style="text-align:left;"> $TSLA continues to drop after ER </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:29:30 </td>
   <td style="text-align:left;"> $TSLA Buy the dip </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:25:46 </td>
   <td style="text-align:left;"> $TSLA when you see amazon at 2800 what do you think is going to happen to this overpriced, overhyped car company. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:24:43 </td>
   <td style="text-align:left;"> $TSLA Monday 700 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:24:28 </td>
   <td style="text-align:left;"> $TSLA Tesla Stock Vs. BYD Stock: Tesla Growing Fast, But EV Rival Is Catching Up… https://www.investors.com/news/tesla-stock-vs-byd-stock-comparing-ev-stocks-tsla-byddf/?src=A00220 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:24:27 </td>
   <td style="text-align:left;"> $TSLA up down up down down downs down down ground </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:24:24 </td>
   <td style="text-align:left;"> $NFLX it’s good to be back baby 😉 $PTON $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:24:11 </td>
   <td style="text-align:left;"> $TSLA filled the gap at 938.53 in the AH. THOUGHTS FOR MONDAY GUYS? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:24:09 </td>
   <td style="text-align:left;"> $TSLA I guess the 930 gap is filled? or not? anyone? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:23:53 </td>
   <td style="text-align:left;"> $TSLA One bull just told me that Tesla will hit 1.8k at the end of the year, and another said 3k?  3 fkn k in this economic climate?! surpassing Apple and Amazon. Man, this pig needs to be shorted for real. People are bare cocky and deluded here. 3 mfkn k? 3 k?! wtf are you all smoking?! 3k!! short this pig. cheers. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:22:47 </td>
   <td style="text-align:left;"> $TSLA where’s that kunt cathie lee now?  she’s been quiet for days now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:22:41 </td>
   <td style="text-align:left;"> $TSLA on  Monday it will bounce back. Over sold for no reason. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:21:33 </td>
   <td style="text-align:left;"> $TSLA all these after hours sellers should be rounded up and face a public. whipping </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:20:16 </td>
   <td style="text-align:left;"> $TSLA Tesla Option Alert: Fri $850 Calls Sweep (19) below Bid!: 204 @ $20.06 vs 6239 OI; Earnings 1/27 After Close Ref=$836.9999🐂 |🥇 Learn more and get details on  ➡️ SweepCast.com </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:18:17 </td>
   <td style="text-align:left;"> $TSLA where all the braindead TSLA to $1300 bulls at by er at now 😂 to the mooooooooon right 🤣🚀🚀 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:17:48 </td>
   <td style="text-align:left;"> $SE $SHOP $TSLA $SQ take your pic ladies and gentlemen who’s your front runner On this dip? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:16:31 </td>
   <td style="text-align:left;"> $TSLA good stock but overvalued asf 
800 incoming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:16:15 </td>
   <td style="text-align:left;"> $SPY $QQQ $AAPL $TSLA $BTC.X 
 
Poor Millennials 
 
They were once again take advantage off as JPOW leveraged the world-wide pandemic to intentionally inflate asset prices so Boomers could hand off bags at all time highs and valuations just as they were retiring en masse. 
 
Boomers know the stock market game and took the opportunity to lock in lifetime gains and hand off their bags to Millennials at OBVIOUSLY overvalued levels. 
 
So who are Millennials going to convince to take their bags when they are ready to retire? GenZ? Good luck!...they just went through the same scam with you. 
 
Boomers are relentless in taking advantage of the world around them for their own personal gain. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:15:11 </td>
   <td style="text-align:left;"> $TSLA no price target upgrades this week by Dan Ives of Wedbush? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:14:57 </td>
   <td style="text-align:left;"> $TSLA Should partner with Palantir
Help me share </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:11:51 </td>
   <td style="text-align:left;"> $TSLA 
what is a good put in this? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:10:40 </td>
   <td style="text-align:left;"> $TSLA  Im buying INV crypto token on coinbase , it is up and moving to hit 45% up today. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:10:20 </td>
   <td style="text-align:left;"> $ALGO.X in case you haven’t yet, this is my daily reminder to do your DD and stop panicking. $BTC.X $ETH.X $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:09:09 </td>
   <td style="text-align:left;"> $SPY $AAPL $AMZN $TSLA $PLTR 
Officially entered to 🐻 market today from correction 🧙‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:08:56 </td>
   <td style="text-align:left;"> $TSLA Fed members all bought the puts before their last meeting. Corrupted </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:07:38 </td>
   <td style="text-align:left;"> $TSLA that’s it. Closed all the gaps and way over sold. Should have rebound rally on Monday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:07:01 </td>
   <td style="text-align:left;"> $TSLA Tweet something, Elon! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:06:39 </td>
   <td style="text-align:left;"> $SPY $SOFI $MSFT $TSLA Welcome to the Biden market folks! Get use to red. You wanted Trump gone and he’s gone. You got want you wanted. Enjoy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:06:14 </td>
   <td style="text-align:left;"> $TSLA 

See here’s where I’m having fit :

It’s not like they don’t want to own the stock so therefore they’re selling .. it is not !! They’re selling shares they never owned and that where @elonmusk n myself n many  heavy duty bulls will f**  them up soon 🔜 mark my words !! 

🙏🏻🐉🦅 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:05:43 </td>
   <td style="text-align:left;"> $TSLA no matter how good the earnings are still will fall </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:05:41 </td>
   <td style="text-align:left;"> $TSLA Will it be a buy in a few weeks/months if tesla stock touches $420 in spring ??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:04:46 </td>
   <td style="text-align:left;"> $TSLA with everything going on this is still holding strong wth... give us $500 and ill sell everything for a loss and buy into this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:04:03 </td>
   <td style="text-align:left;"> $TSLA This is what Elontards are hoping to see while all growth stocks are getting decimated, and while NFLX, SHOP and everyone else is getting hammered. Doesn&amp;#39;t look like a bubble at all. Especially with the blue addition. All organic and natural. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:02:52 </td>
   <td style="text-align:left;"> $TSLA Gap filled completely, Monday should be $110 up let’s go </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:02:52 </td>
   <td style="text-align:left;"> $TSLA Following the logic of the sell off on growth stocks. TSLA is in for a major correction! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:02:50 </td>
   <td style="text-align:left;"> $TSLA more people are going to lose money with lottos on calls during short rebounds than now </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:02:33 </td>
   <td style="text-align:left;"> $TSLA clown company.  

Clown valuation </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:02:30 </td>
   <td style="text-align:left;"> $TSLA today’s sentiment </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:02:20 </td>
   <td style="text-align:left;"> $TSLA realistic 1150 back before earnings unless markets controls 🦾🦾🦾 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:02:03 </td>
   <td style="text-align:left;"> $SPY $QQQ $VIX $TSLA $AAPL  
 
What a day (and week) in the markets! 
 
- $ 973 Billion traded today alone in US Equities ( $ 690 B was the daily average this week). 
 
- $ 45 Billion traded today alone in US Options ( $ 22 B was the daily average this week). 
 
-------- </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:01:56 </td>
   <td style="text-align:left;"> $SPY $NFLX $TSLA $BA $COIN

GREAT DAY BEARS! CLAP IT UP!!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:01:46 </td>
   <td style="text-align:left;"> $TSLA we going back to over 1k next week. Don’t sweat it. Get a goodnight sleep and enjoy your weekend folks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:01:36 </td>
   <td style="text-align:left;"> $TSLA Simulated Weekly $945.0 CALLS for Monday&amp;#39;s open on StockOrbit. 
 https://apps.apple.com/us/app/stockorbit/id1541560646 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:01:29 </td>
   <td style="text-align:left;"> $TSLA shit stock </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:00:41 </td>
   <td style="text-align:left;"> $TSLA all bears will cry on Monday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 09:00:04 </td>
   <td style="text-align:left;"> $TSLA I am keeping some cash handy on Wed to buy PUT options but only if we get a solid (and most likely short lived) pop AFTER earnings. its all about playing the fade that will follow </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:56:52 </td>
   <td style="text-align:left;"> $TSLA Looks like will revisit $800’s again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:56:36 </td>
   <td style="text-align:left;"> $TSLA I expect NQ futures to eventually drop down to 8k over the next 16 months. The bleeding will not stop. Furthermore, a stock drops quicker than the time it takes to climb upward. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:56:25 </td>
   <td style="text-align:left;"> $SQ $APPL $MSFT $PYPL $TSLA buy and hold is dead or should be dead. You don’t even hear pundits say it anymore. Because it sounds very stupid. Years of gains can evaporate in less than a week. The market takes the escalator on the way up but the elevator on the way south. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:56:20 </td>
   <td style="text-align:left;"> $TSLA levels in previous post are approximately as follows:

Mon-Wed Close: +7% to $1,008
AH Wed - Friday: +7% to $1,080 
Following 2 weeks: +12% to ~ $1,210

Goes to show we EASILY get back above $1,200. Especially if JPow gets dovish before ER Wednesday morning. Which is likely due to market turmoil. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:55:48 </td>
   <td style="text-align:left;"> $TSLA Reasonable price after ER is $ 1800 🤡 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:55:15 </td>
   <td style="text-align:left;"> $TSLA raise your hand if you think your a know it all? But started investing a year ago? LMAO </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:54:56 </td>
   <td style="text-align:left;"> $SPY $QQQ $AMZN $TSLA how to measure this correction. Take the whole market cap minus 8T powell giveaways. Minus another 10% of clearance. Then watch for bargains accordingly. By then bankruptcies will be looming and banks will be struggling regardless of high rates. MM wants you to believe Banks make money of interest rates. Wrong. They make money by trading a fixed market. GS are so greedy they short their own stock. This is true. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:54:24 </td>
   <td style="text-align:left;"> $TSLA Upcoming week according to the bulls, earnings are priced in 😁. The main thing that&amp;#39;s going to move the markets and crypto, if they announce the initial rate hike of 50bp or higher Lookout below. The US10Y didn&amp;#39;t move much from yesterday. Bulls these are just the jitters, can&amp;#39;t wait for the panic. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:53:14 </td>
   <td style="text-align:left;"> $TSLA made some good money the last couple of weeks with options on the swings. Threw some money at $1050 calls next week. If it doesn’t work out, take it as a loss but if it works out will be pretty happy 🤷🏻‍♂️ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:53:09 </td>
   <td style="text-align:left;"> $TSLA $2000 next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:52:16 </td>
   <td style="text-align:left;"> $TSLA $800 puts are primed, Elon Musk got rich on the back of poor and then wanna pretend to be a Massiah, thanks to Elon and his cult, I am in the money now, love to Hate Amazon, Tesla, Google and Microsoft, they bankrupted so many small businesses across US and across the world and then never paid their fair share of taxes also </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:52:12 </td>
   <td style="text-align:left;"> $DAVE $AMZN $ARKK $TSLA $BTC.X Forget Bitcorn and  Amazon, Dave is Running. 

All in on $DAVE ! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:52:07 </td>
   <td style="text-align:left;"> $TSLA Tesla Fanboys still believe that this stock will continue to trade as it used to. You guys are about to learn a hard lesson regarding Central Monetary Policy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:52:00 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:51:17 </td>
   <td style="text-align:left;"> $TSLA these Are the type of comments you see at a bottom. Have no fear. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:51:11 </td>
   <td style="text-align:left;"> $TSLA Waiting for max pain….yum yum yum yum yum yum </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:50:45 </td>
   <td style="text-align:left;"> $TSLA for WallStreet to survive retail investors have to lose so you have to be smarter than them to survive. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:50:36 </td>
   <td style="text-align:left;"> $TSLA Party is over, TSLA  still overvalued. Will follow the same pattern as other tech companies crashing, still a bit late in the game until the « denial » syndrome is over. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:50:22 </td>
   <td style="text-align:left;"> $TSLA $800 puts are primed, Elon Musk got rich on the back of poor and then wanna pretend to be a Massiah, thanks to Elon and his cult, I am in the money now, love to Hate Amazon, Tesla, Google and Microsoft, they bankrupted so many small businesses across US and across the world and then never paid their fair share of taxes also. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:50:06 </td>
   <td style="text-align:left;"> $TSLA this is why it’s not far fetched for us to see new ATH in the next 2-3 weeks. If you have been watching Tesla for ANY amount of time, you should know we could easily outperform this projection. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:48:23 </td>
   <td style="text-align:left;"> $TSLA Biden wants your shares  don’t sell </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:48:05 </td>
   <td style="text-align:left;"> $TSLA Bulls&amp;#39; logic. If Tesla drops, all other stocks will drop. Can&amp;#39;t afford that. Wait a second...So you&amp;#39;d rather Tesla keep going up to like 2k...3k and then let the pop shit on everyone after the market recovers ? Makes no sense. Short it now. Pop this egregious bubble. Even if this drags other stocks down. Better to get a good purge and flush now. Let the market rebalance...Money needs to trickle in the right stocks. Not be concentrated in the hands of a meme lord who has cult following. No confidence in the market as long as Tesla stays at this level. It needs to go down. Shot up way too fast. The growth was unjustified. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:47:36 </td>
   <td style="text-align:left;"> $TSLA 23.6% broke today. We could see $886 next. Then a big bounce into ER </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:47:19 </td>
   <td style="text-align:left;"> $PIXY - garbage stock can&amp;#39;t even get to $100 - better off buying $TSLA OR $RIVN </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:45:41 </td>
   <td style="text-align:left;"> $TSLA I doubt that Powell is American. He alone is responsible for 20% drop in all the tech stocks from the beginning of the year 2022. Even IMF chief said that Fed is not clearly communicating its policy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:45:31 </td>
   <td style="text-align:left;"> shorts are winning - garbage stock can&amp;#39;t even get to $100 - better to buy $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:44:41 </td>
   <td style="text-align:left;"> $TSLA the market isn’t going to reverse unless jay pow ends up lowering interest rates instead of raising them but that will result in hyperinflation. It’s lose lose for us stocks. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:43:45 </td>
   <td style="text-align:left;"> $TSLA 970+ open on Monday. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:43:09 </td>
   <td style="text-align:left;"> $TSLA Xinjiang expansion criticized by US lawmakers saying it empowers chinese 🇨🇳 government but US lawmakers not ready to do anything about it other than sitting in their offices and criticizing the move ??? does that make sense to anyone </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:42:51 </td>
   <td style="text-align:left;"> $TSLA no more Tesla options for me.  I keep doing this and I am writing help remind myself not do this.  Buying a ATM Tesla option at 2pm for a 2 hour trade on a friday where the options are the cheapest but I keep losing.  Last week I bought a put when Tsla was at 1040 for $670 or something and then it only went up only for 5 minutes.  Today I saw tsla&amp;#39;s graph starting to move and so I bought a call at 965 for $550 and then it goes down more.  Both of these times did I have about a 50% gain in the beginning and I said to myself ok if it going to go in my favor then I am going to try hard and hold it longer.  Then it goes the other way and then I can&amp;#39;t close it for a loss and then watch the option go to 0. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:42:51 </td>
   <td style="text-align:left;"> $TSLA called this to a tee in the morning. Follow my twitter for more free plays. https://twitter.com/OrdinaryInvest3 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:42:29 </td>
   <td style="text-align:left;"> $TSLA This grew 1000+% since early Covid.  Pricing in 5 years forward. They have to execute perfectly. Already seen some bumps. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:42:16 </td>
   <td style="text-align:left;"> Wage inflation has leveled off. I know this as a stone cold fact. And it was the last bullish hope the market had. 

Consumer discretionary will bleed, EVs bleed most $TSLA $RIVN $LCID $F 🚨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:41:52 </td>
   <td style="text-align:left;"> $TSLA 
I guaranteed its bad earnings. Buying YOLO put options for easy money. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:41:36 </td>
   <td style="text-align:left;"> $TSLA there’s levels to this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:41:30 </td>
   <td style="text-align:left;"> $TSLA 700 post ER? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:40:14 </td>
   <td style="text-align:left;"> $TSLA 900 will fill the gap. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:40:00 </td>
   <td style="text-align:left;"> $TSLA algo target around 930 &amp;amp; fed meeting Jan 25-26? I wonder if they release some news monday as indices are reaching 1.618 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:39:14 </td>
   <td style="text-align:left;"> $TSLA Going to $800?, I will buy. Going to $50?, I will buy. Got nothing but the the time. And this will eventually be $5,000 stock [again]. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:38:42 </td>
   <td style="text-align:left;"> The Stock Market Has 3 Problems. 2 Aren’t Going Away.  $PTON $NFLX $AAPL $TSLA 

https://newsfilter.io/a/6652442d66cba49abc81e35b6e99a9ec </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:38:40 </td>
   <td style="text-align:left;"> $TSLA As long as this garbage has an unjustified value of around 1 trillion, there is no confidence in this scam market. Everyone should short this pig to restore order. Irrational af to support this stock at this level. Elon fanboys need to see the truth. short it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:38:33 </td>
   <td style="text-align:left;"> $TSLA What could go wrong withba 300 p/e stock right? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:38:20 </td>
   <td style="text-align:left;"> $TSLA This week was like a mini market crash. All they are doing to make FED realize that what can happen to tech stocks after int rate rise. Hope Fed realizes soon next week and Powell want to save his job and will not raise the interest rate in March and we rally on Tuesday.  😇Mainly, It was the worst idea of Biden to re-elect Powell as Fed Chairman. Even Trump wanted to fire him a couple of times. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:37:23 </td>
   <td style="text-align:left;"> $TSLA This bubble has not even began to pop </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:35:45 </td>
   <td style="text-align:left;"> $AMZN 1500 soon
$TSLA 500 soon and I won&amp;#39;t be buying either of these </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:35:37 </td>
   <td style="text-align:left;"> @ThePropDesk The analysis here is incorrect megatechs took a beating and have sold off quite a bit. Market is still pricing in 4 rate hikes and by how much with the last one in December being 50/50 as of now. It will all depend on January numbers reporting in February for $SPY $TSLA $NVDA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:35:32 </td>
   <td style="text-align:left;"> $TSLA stock market might become a bit more normal once this one loses a few $100 billion in market cap </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:35:18 </td>
   <td style="text-align:left;"> $TSLA bonds are getting rekt. That&amp;#39;s decent </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:34:13 </td>
   <td style="text-align:left;"> $TSLA I would still hold it. what if cars started flying? I am all for the future. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:32:45 </td>
   <td style="text-align:left;"> The mighty $TSLA  is falling next week. Bulls think that the stock is invincible. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:32:15 </td>
   <td style="text-align:left;"> $TSLA time to get some more? 🧐 😋 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:31:49 </td>
   <td style="text-align:left;"> $TSLA Does Cathy wood own any Tesla stock in her $ARKK $ARKW $ARKF funds anymore or did she wash her hands off of it at the TOP before the fall?? does anyone know?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:31:04 </td>
   <td style="text-align:left;"> $TSLA all time highs after ER? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:29:57 </td>
   <td style="text-align:left;"> $TSLA Deja vu April 2000 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:29:13 </td>
   <td style="text-align:left;"> $TSLA Dear piece of junk, please crash EVEN HARDER </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:28:34 </td>
   <td style="text-align:left;"> $TSLA going under 900 Monday .. maybe low 800s weds </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:28:28 </td>
   <td style="text-align:left;"> $TSLA Well, so how long before elon casually come on twitter and say , oh yeah .. we sold all out $BTC.X ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:27:18 </td>
   <td style="text-align:left;"> $TSLA I think we are better off buying a hummer at this point? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:27:03 </td>
   <td style="text-align:left;"> $SPY $TSLA 
Big thank you to the Bulls for selling me these put options and giving me free money. Keep buying the dip yall. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:24:15 </td>
   <td style="text-align:left;"> $ARKK This has always been the “Tell” for me with ARK and $TSLA . When they trade precisely in tandem, they start buying shares. Way before Tesla was big, their early big scores were Amazon, PayPal and Netflix 2014-2018. Similar sells, then buys. Same thing as they were top 3 holdings. Their selling is radically over-analyzed . They genuinely have a 5 year plan and Tesla is a huge part of it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:23:15 </td>
   <td style="text-align:left;"> $TSLA fair value 94$ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:22:24 </td>
   <td style="text-align:left;"> $TSLA Where is all the money going from the tech stocks? Not good for economy. They are buying all the energy companies’ stock. $40 oil is selling at $90. What a joke. That’s how inflation going up. Stupid Fed. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:22:07 </td>
   <td style="text-align:left;"> $TSLA Whoever needs to hear it- I&amp;#39;ve considered selling Tesla MANY times throughout the years. Never did &amp;amp; today, a $15,000 investment is nearly half a million dollars. If I&amp;#39;d sold anywhere along the way, I wouldn&amp;#39;t have reached this point. Even as bad as the 2020 crash was, I was buying &amp;amp; not selling. Don&amp;#39;t let turbulence scare you away. 👊 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:21:55 </td>
   <td style="text-align:left;"> $TSLA This is setting up for a $200 move this Wednesday, no rate hike with a dovish language from the Fed after the 2 day meeting, also phenomenal earnings with bullish guidance. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:21:14 </td>
   <td style="text-align:left;"> $TSLA If you are one of the idiots that voted for this moron and think you made a wise decision with your portfolio… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:20:43 </td>
   <td style="text-align:left;"> $TSLA don’t worry guys having a P/E of anywhere between 10x - 40x more than any other automaker in the world is fine. It’s up from here. 😂😂 Most overvalued stock EVER </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:20:27 </td>
   <td style="text-align:left;"> $TSLA Solid support here or is it headed to 200ma? 🤔 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:20:22 </td>
   <td style="text-align:left;"> $TSLA Isn’t this the plot of the Terminator?  
The machines are causing havoc. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:19:58 </td>
   <td style="text-align:left;"> $TSLA I dare Elon to say something bad next week. Just try it in this market. This will tank 20%+ just like that other extremely overpriced stonk  $NFLX </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:19:10 </td>
   <td style="text-align:left;"> $BTC.X Elon started pumping Bitcoin looks what happens! $TSLA who bought one with $DOGE.X ? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:18:12 </td>
   <td style="text-align:left;"> $TSLA $891 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:17:44 </td>
   <td style="text-align:left;"> $TSLA nearly all the large cap growth stocks I follow are eiether just below 200ma or nearly there.  Spy closed below 200ma today. 

ER will be sell the news unless they announce something unexpected. a test of the 200ma (around 810$) seems likely imo.

Don&amp;#39;t see a change in market sentiment till the first rate rise is announced in March. Untill then retail buy the dippers will get raped.

Retail buy &amp;quot;dips&amp;quot; and hedgies sell the ripp </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:16:30 </td>
   <td style="text-align:left;"> $TSLA Just in case Tesla stonk drops -25% or -20% after earnings like $NFLX crashed after its ER, do we buy in AH on ER day after the crash or do we wait until the next day to get an even lower price mid day to load up ??? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:15:54 </td>
   <td style="text-align:left;"> $TSLA up 13,000 percent and you all think 15 percent is a correction lol </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:14:18 </td>
   <td style="text-align:left;"> $TSLA Expectations are running high ahead of Tesla, Inc.&amp;#39;s (TSLA) earnings next week. The company is on strong footing for its fourth quarter 2021 earnings call on Jan. 26. It weathered the pandemic successfully by pivoting its production capabilities to overcome the automobile industry&amp;#39;s chip shortage. The carmaker also opened two new factories and reported record deliveries for its electric vehicles. To top it all off, Tesla was the best-selling electric vehicle (EV) brand in Europe in 2021.1 
 
 Appropriately enough, analysts are predicting a great performance next week. 
 
https://www.investopedia.com/analysts-bullish-ahead-of-tesla-earnings-5216610 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:14:13 </td>
   <td style="text-align:left;"> $SPY $DJIA $QQQ $AAPL $TSLA  
 
Boomers doing what Boomers do when the market starts to crash. 
 
Find a war! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:14:01 </td>
   <td style="text-align:left;"> $TSLA Cathie out of cash so lots of selling about to commence </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:14:00 </td>
   <td style="text-align:left;"> $TSLA $PLTR $HOOD $SOFI  down 9.5% for the week… 12% for the month… It hurts but I kept buying… Gotta be able to get through these days to enjoy the correction. 

Enjoy your weekend everyone. Do not let this get to you. Those numbers will change for the better soon. 
Go spend time with your family and friends… </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:13:54 </td>
   <td style="text-align:left;"> $TSLA PLEASE GOD don&amp;#39;t let the EV bubble POP.
This can see $200s </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:13:48 </td>
   <td style="text-align:left;"> $TSLA Netflix type drop next week </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:13:26 </td>
   <td style="text-align:left;"> $TSLA Elon sold. 

What do you all fucking expect? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:12:50 </td>
   <td style="text-align:left;"> $TSLA regardless of how great they will be, this thing will crater after earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:12:33 </td>
   <td style="text-align:left;"> $BTC.X I think Elon will be among the first to publicly dump Bitcoin. $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:12:01 </td>
   <td style="text-align:left;"> $TSLA this is what’s gonna happen… they gonna raise rates till the market gets donked further… then reverse course… party continues… how you gonna raise rates when global debt to gdp numbers 256%+ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:11:34 </td>
   <td style="text-align:left;"> $TSLA been short for a month now. Balls of steel </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:11:05 </td>
   <td style="text-align:left;"> $TSLA $NKLA Nikola Tesla was a great inventor. His name was hijacked by 2 fraudster. Nikola went down before Tesla. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:10:35 </td>
   <td style="text-align:left;"> $TSLA $NIO Will sell NIO if this goes below $900 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:10:12 </td>
   <td style="text-align:left;"> $TSLA 10k in a week no lube </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:10:05 </td>
   <td style="text-align:left;"> $TSLA bagholding a useless coin </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:07:41 </td>
   <td style="text-align:left;"> $TSLA At least we got a super smart CEO. He sold at the TOP or close to top of the roller coaster 🎢 when we were all blindly cheering 📣 , not knowing that a crash was coming. But he caught the pulse and knew what to do. cha ching... hit the register Musk baby </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:06:49 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:06:05 </td>
   <td style="text-align:left;"> $TSLA it’s fully self driving with your hands on. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:05:25 </td>
   <td style="text-align:left;"> $TSLA TSLA 2022-01-21 Technical Analysis Video: 
https://www.youtube.com/watch?v=v8Omlw9dVxw </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:05:01 </td>
   <td style="text-align:left;"> $TSLA Biden better fix this over the weekend.  This guy is hanging on a thin thread.  Very thin. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:05:00 </td>
   <td style="text-align:left;"> $TSLA wasn&amp;#39;t today the main options expiration day ?? so all those $$$ folks invested in call options, did it all go poof into thin air overnight?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:04:44 </td>
   <td style="text-align:left;"> $TSLA Elon and aunt Cathie sold at a good price. But we are vigilantes, let’s hold the responsibilities. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:04:03 </td>
   <td style="text-align:left;"> $TSLA thanks biden … </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:03:56 </td>
   <td style="text-align:left;"> $TSLA I think the market will be in the mood for some positive relief next week.  Great weak to report tesla earnings. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:03:24 </td>
   <td style="text-align:left;"> $SOFI Holding 12000 shares here 💪 $TSLA $LCID $NIO $QQQ </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:03:20 </td>
   <td style="text-align:left;"> $TSLA Elon warned you a recession is coming </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:02:43 </td>
   <td style="text-align:left;"> $TSLA $SPY $QQQ  
Not the worst close for Tesla.  We completely filled an important gap, reached the critical support line, and there&amp;#39;s a massive inverse head &amp;amp; shoulders forming on the 4 hour.. deliveries are up 70% from last year, and earnings report will be 🔥.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:01:06 </td>
   <td style="text-align:left;"> $TSLA can we see green on Monday?? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:00:45 </td>
   <td style="text-align:left;"> $TSLA 

Over 150M shares now are shorted / underweight between actual short selling and options play !! 

I can assure y’all now it won’t take much to get you past $1243 ! 

A BREAKING NEWS INBOUND!! 

🙏🏻🐉🙏🏻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 08:00:15 </td>
   <td style="text-align:left;"> $TSLA this time papa is not around to save you! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:59:15 </td>
   <td style="text-align:left;"> $TSLA ok another it is. Did I say buy the dip yet?! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:59:08 </td>
   <td style="text-align:left;"> $TSLA Patience motherfuckers. Patience. The world will turn. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:57:29 </td>
   <td style="text-align:left;"> $TSLA that’s a shitty week.  It can’t happin again.  All shitty priced in. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:57:05 </td>
   <td style="text-align:left;"> $TSLA ok market this bottle was full 2 hours ago. My liver does not thank you but I do feel a little better. All you fuckers buy the dip! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:56:12 </td>
   <td style="text-align:left;"> $AAPL $TSLA $NIO 

Wearable Health Solutions Inc. Announces &amp;quot;Worldwide Business | WHSI Stock News https://www.stocktitan.net/news/WHSI/wearable-health-solutions-inc-announces-worldwide-business-with-n7xlrpshqskl.html </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:55:36 </td>
   <td style="text-align:left;"> Sweep Options Activity: $TSLA is the #2 ticker with sweep activity where institutions are trading options urgently with 43.2K sweep contracts, a leading indicator of market movement.

Market analysis and options contracts included in screenshot of dashboard from http://insiderfinance.io. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:55:33 </td>
   <td style="text-align:left;"> $SOFI Gimme 12 again and I will go all in with my entire family and pets!! $TSLA $LCID $BTC.X $ETH.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:54:50 </td>
   <td style="text-align:left;"> $TSLA You know it&amp;#39;s bad when some of the originals of your generation don&amp;#39;t even want to associate themselves with you. I go with GenX so I am not automatically labeled a simpleton. Thanks for that. Wise up. Please? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:54:14 </td>
   <td style="text-align:left;"> $TSLA The only stock split happening here is the halving from the top when it hits mid 600&amp;#39;s next week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:53:51 </td>
   <td style="text-align:left;"> $TSLA Elon is changing his mind on doge and now says pulsechain.com is the future of Defi . </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:51:46 </td>
   <td style="text-align:left;"> $TSLA 50 dollar down day and bears celebrating like they won the Superbowl.   Gap now filled and held.    What happened after the 1,200 gap was filled?  Reverse of that now. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:51:37 </td>
   <td style="text-align:left;"> $TSLA Elon doesn’t like letting down his share holders.  I expect something mind blowing cool positive that excites the market. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:51:11 </td>
   <td style="text-align:left;"> $TSLA All you people be like OK Boomer. News flash. Cathy Wood is a Boomer. I however am a millennial. One of the first ones actually. Not very proud to say that but it is true. The rest of you makes us all look bad. OK Boomer and you follow one to your doom. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:50:35 </td>
   <td style="text-align:left;"> $TSLA stock split I’m out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:49:50 </td>
   <td style="text-align:left;"> $TSLA it would be super funny if after all this fear.  Next week tesla goes up after earnings.  Because Tesla is not Netflix </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:48:56 </td>
   <td style="text-align:left;"> $TSLA Stock split announcement is not priced in yet. Once traders get the leaked news next week that there is a possibility of stock split announcement on earnings report, then stock will jump to $1200 before earnings. Same happened with Amazon before earnings. 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:48:47 </td>
   <td style="text-align:left;"> EXCLUSIVE: Plug Power&amp;#39;s CEO On Stock Price, Competitive Advantages, &amp;#39;Green Hydrogen&amp;#39; Strategy

$TSLA $PLUG  

https://www.benzinga.com/trading-ideas/long-ideas/22/01/25166804/exclusive-plug-powers-ceo-on-stock-price-competitive-advantages-green-hydrogen-strategy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:48:36 </td>
   <td style="text-align:left;"> $TSLA Realty is sinking in virus not important anymore government printed money running out folks cashing in on their abnormal gains from stock market during virus that’s why market is  plumeting </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:48:26 </td>
   <td style="text-align:left;"> $TSLA large buy </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:48:24 </td>
   <td style="text-align:left;"> $TSLA 
Anyone know how’s it trading in Frankfurt? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:47:11 </td>
   <td style="text-align:left;"> $MSFT $AAPL $TSLA  no matter what Earnings they report these r going down all priced in market adjusting to new world with high interest rates </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:46:51 </td>
   <td style="text-align:left;"> $MMAT I’m bullish that Cathy Woooooood never showed up here $TSLA $ARKF </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:46:23 </td>
   <td style="text-align:left;"> $XPEV $NIO $TSLA  
 
Very soon, your bank savings accounts start to pay 10% interest,   people will move out of stocks into saving accounts. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:45:54 </td>
   <td style="text-align:left;"> $TSLA Cathy Wood stole information then went on CNBC like it was her own words. She was an Echo with $2400 in 2025 back in 2019 when they said $10. She pays dearly for that now and will continue to do. She had one pick and that was all. Look below though. What a joke she is. Also don&amp;#39;t like Morgan Stanley but who does? They should be targeted but why bother. She is cooked like Tesla&amp;#39;s books. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:44:50 </td>
   <td style="text-align:left;"> $TSLA  does bitcoins price drop gonna effect their ER report </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:44:37 </td>
   <td style="text-align:left;"> $SHOP reminds me of $tsla shakeout will run again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:44:30 </td>
   <td style="text-align:left;"> $TSLA calm seas don’t make a strong sailor. I feel bad for the shorts who covered over 1k to now see 930 a couple months later 😆 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:43:49 </td>
   <td style="text-align:left;"> $TSLA every thing is going down, sell sell sell. buy rice wheat oil and frozen meat. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:43:39 </td>
   <td style="text-align:left;"> $ARKK Cathie Woodshed just fucked everyone $BTC.X $ETH.X $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:42:04 </td>
   <td style="text-align:left;"> $TSLA so many whiny little bitches on here!!! Blame Biden, blame Cathy, blame the next-door neighbors cat. If you can&amp;#39;t deal market volatility for god sake invest somewhere else! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:41:44 </td>
   <td style="text-align:left;"> $TSLA AAII survey reports every Thursday . It’s a contrarian indicator over bearish is extremely bullish and vice versa . This is the biggest bearish report in over 20 years!!!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:41:39 </td>
   <td style="text-align:left;"> $LCID $RIVN $TSLA $NIO $XPEV 
Pivots for Mon 1/24, next week &amp;amp; this month </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:41:38 </td>
   <td style="text-align:left;"> $TSLA $BTC.X holding will be a big blow to Tesla stock next week…. 
RIP Tesla Investors </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:40:50 </td>
   <td style="text-align:left;"> $TSLA 99.99% sure about stock split announcement on January 26. Mark it on ur calendar. 😆🚀🌙Thats why Elon said, “To the moon”, “Roaring 20s”, , and “Believe in future”. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:40:32 </td>
   <td style="text-align:left;"> $TSLA cybertruck delay will be a big blow to Tesla stock next week….
RIP Tesla Investors 🪦 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:40:27 </td>
   <td style="text-align:left;"> $TSLA still more room to fall. No run up to ER. If ur not in puts, not too late. Target 935-885 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:39:56 </td>
   <td style="text-align:left;"> $TSLA Surprised we haven&amp;#39;t heard a thing from Gordon Johnson yet 🤪🤪.... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:39:39 </td>
   <td style="text-align:left;"> $TSLA $BTC.X  $36500 it&amp;#39;s going to come down to $800 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:39:31 </td>
   <td style="text-align:left;"> $TSLA </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:39:24 </td>
   <td style="text-align:left;"> $TSLA so many bears all over . As a long term investor . You know what that tells me ? Bullish </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:38:18 </td>
   <td style="text-align:left;"> $TSLA too the moon. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:38:01 </td>
   <td style="text-align:left;"> $TSLA Cathy is done here. This is more her fault than EVEN Elon&amp;#39;s as far as I am concerned. She been done since I came back. If you didn&amp;#39;t notice. Targeted since March. They even destroy my own picks because of her. ACHR is a prime example. She will leave with nothing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:37:56 </td>
   <td style="text-align:left;"> $TSLA Maybe Musk will start focusing on his main business for a change </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:37:38 </td>
   <td style="text-align:left;"> $TSLA you bears are playing with fire </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:37:12 </td>
   <td style="text-align:left;"> $TSLA 

do you think tesla day there is going to be some big news that will make this stock rise alot?! i keep hearing about tesla becoming a worldwide utility company for electricity... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:37:07 </td>
   <td style="text-align:left;"> $TSLA is where it was a month ago. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:35:33 </td>
   <td style="text-align:left;"> $TSLA did jerome tell y’all the stock market is inflated asf </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:35:24 </td>
   <td style="text-align:left;"> Just wait for $TSLA  to correct and these funds will be liquidated  $ARKF $ARKW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:35:09 </td>
   <td style="text-align:left;"> $TSLA what price are you scaling back in at? $600 for me probably. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:33:28 </td>
   <td style="text-align:left;"> $TSLA To average cost down deep red holdings, Cathie has no choice but liquidate Tesla holdings, which is about the only holding that is green. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:33:04 </td>
   <td style="text-align:left;"> $TSLA “500-700 PT, say it to me again! Go ahead…” </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:31:42 </td>
   <td style="text-align:left;"> $TSLA Strange, normally when you post something sensible here about Tesla price going down, you get a load of abusive replies from bulls. Nothing today. That is disappointing. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:31:19 </td>
   <td style="text-align:left;"> $TSLA this is not good.. at least short and make i lite buck before the the 2008 x 5 starting.. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:31:13 </td>
   <td style="text-align:left;"> $TSLA wait till extreme fear 🤑 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:31:06 </td>
   <td style="text-align:left;"> $TSLA well.. earnings is on Wednesday, Jan 26 end of day. A lot of factors need to be positive to make sure this doesn’t rank after earnings. Let’s see how Monday and Tuesday do.. stop losses on smaller bumps is probably a good idea if need cash in the short term. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:31:05 </td>
   <td style="text-align:left;"> $TSLA how can

This be down the same day Meat Loaf dies.  Double whammy. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:30:21 </td>
   <td style="text-align:left;"> $TSLA dont sell as there are no buyers </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:29:55 </td>
   <td style="text-align:left;"> $TSLA WHO SELLS AH AND ON FRIDAY . DIDNT THEY GET THE TIME BEFORE 4pm . Shitty Ppl </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:29:54 </td>
   <td style="text-align:left;"> $TSLA 600s will be here before you know it. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:29:17 </td>
   <td style="text-align:left;"> $TSLA with BTC dropping the way it has, this is about to slaughtered on Monday. Ouch... ouch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:28:12 </td>
   <td style="text-align:left;"> $TSLA Damn.  Looks like headed to 500 and quick.  Wow.  Calling it like I see it.  Nothing is getting spared now.  Especially with PEs that are astronomical. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:27:59 </td>
   <td style="text-align:left;"> $TSLA When Tesla Bubble Pops... Cathie is done

Tesla $369
Arkk $41 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:27:56 </td>
   <td style="text-align:left;"> DJIA Weekly Close. This {Wave 5} bull market blowoff top has now subdivided into it&amp;#39;s own 5 wave fractal structure which is standard policy in terminal fazes of raging bull markets. Target for {Wave 5} was 36k so the bull market top could be hammered in. $DIA $QQQ $IWM $TSLA $BTC.X </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:27:53 </td>
   <td style="text-align:left;"> $TSLA what the heck, this was supposed to happen during market hours not after </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:26:45 </td>
   <td style="text-align:left;"> $TSLA Guys, I&amp;#39;m not gonna lie. I am a bit scared. Anyone have any news that can cheer me up for next week? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:26:43 </td>
   <td style="text-align:left;"> $TSLA and here are my estimated numbers. 17.65B rev 2.07B ER  will see if I was close on Wednesday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:26:35 </td>
   <td style="text-align:left;"> $TSLA Ok Tesla should be a flight to safety. Earnings next week and there guidance is historically good. We will be $1200 next week, should just be buying the dip, don’t sell to cover your other losses and just hold and sell after $1200 cause you’ll be kicking yourself in a week otherwise </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:26:17 </td>
   <td style="text-align:left;"> $TSLA breaking down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:26:17 </td>
   <td style="text-align:left;"> $TSLA remember they just delivered a record 308,600 cars in Q4 alone, which means without 2 new factories coming online any day now, they are at a 1.23 million vehicle/year run rate.   Berlin also vastly improves logistics as Giga Shanghai can focus on meeting Asian demand.  Insurance now in 5 states, FSD v. 10.9 blowing people’s minds, Tesla compact design on the way out of China, 4680 cells, credit upgrade, record beat on earnings expected Jan 26 - Tesla share price strong on fundamentals. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:25:12 </td>
   <td style="text-align:left;"> $TSLA Serious kumo break-out DOWN. This could be in synch with looming SPY/QQQ crash later in the year. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:24:48 </td>
   <td style="text-align:left;"> $tsla 510 next week .10 last size was 100 contracts </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:24:44 </td>
   <td style="text-align:left;"> $TSLA sub 500 by March </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:23:51 </td>
   <td style="text-align:left;"> $TSLA only going to get worse. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:23:20 </td>
   <td style="text-align:left;"> $TSLA ouch got bit on entry </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:22:58 </td>
   <td style="text-align:left;"> $TSLA $1100 before earnings and $1500 after. Miracle will definitely happen for the good. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:22:51 </td>
   <td style="text-align:left;"> $TSLA I don’t know fam, probabuy out after earnings.  This shit ain’t looking swell. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:22:23 </td>
   <td style="text-align:left;"> $TSLA much love. I am retired! 🍻 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:22:13 </td>
   <td style="text-align:left;"> Hope you guys loved the session great to have 100s of you on it live asking QnA! SEE MY BIO if you missed it.. If you have been following me or is this week, it was pretty crazy on the downside. We NAILED tons of puts on $SHOP $QQQ $SPY $TSLA $PTON. No one said you can’t make $$ in a down market. Let’s stay focused and crush it volatility. HAVE A SPLENDID WEEKEND!! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:20:59 </td>
   <td style="text-align:left;"> $TSLA welcome to the 2022 
market crash. Don‘t throw away 2 years of gains pretending it’s still bull season. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:20:33 </td>
   <td style="text-align:left;"> $BTC.X $SPY $TSLA $QQQ 

And just like that El Salvador just became that much more poor... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:20:07 </td>
   <td style="text-align:left;"> $TSLA the complete opposite of a Value investment. Just retardly dangerous </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:20:05 </td>
   <td style="text-align:left;"> $tsla 936 AH wow hit 1040 + yesterday </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:20:03 </td>
   <td style="text-align:left;"> $SHOP $TSLA biden the worst president </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:19:52 </td>
   <td style="text-align:left;"> $TSLA trending on Twitter right now in top 4 - saw a significant increase in number of impressions the last 24hrs - should see some strong support. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:19:51 </td>
   <td style="text-align:left;"> $TSLA According to fintel Jan 20 Insider Kirkhorn Zachary reports selling 1,250 shares of $TSLA / Tesla Motors, Inc. at a total cost of $1,283,437.50 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:19:27 </td>
   <td style="text-align:left;"> $TSLA Even with earnings general market is at a sell off. Hard to think that good earnings would do anything at this time other than another pop and drop. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:18:08 </td>
   <td style="text-align:left;"> $TSLA could it be possible someone leaked the earnings </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:17:59 </td>
   <td style="text-align:left;"> $TSLA painful truth </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:17:56 </td>
   <td style="text-align:left;"> $TSLA technicals say this should break 900 next week. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:17:37 </td>
   <td style="text-align:left;"> $TSLA is this shorting or longs existing? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:17:28 </td>
   <td style="text-align:left;"> $TSLA MMs are going to drop this bitch down to upper 800s leading into er. It&amp;#39;s predictable.  If you have puts, be careful with the next week. The Fed knows the markets are tanking so they will offer some reassurance. It will be certainly a tricky play on Wednesday.  Long term, however, this stock will go into the shitter. No way a automaker will maintain a trillion dollar market cap, which is silly. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:16:49 </td>
   <td style="text-align:left;"> $TSLA I don’t have position here but I was wondering. What is going on? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:16:45 </td>
   <td style="text-align:left;"> $TSLA will tesla beat earnings? </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:16:44 </td>
   <td style="text-align:left;"> $TSLA Jan 7 Insider Taneja Vaibhav reports selling 5,900 shares of $TSLA / Tesla Motors, Inc. at a total cost of $6,674,423.74 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:16:39 </td>
   <td style="text-align:left;"> $TSLA PT: $800. $NFLX  we will finally get some realistic earnings reactions. Love Tesla but I been waiting on a mega short opportunity for a good time on this </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:15:54 </td>
   <td style="text-align:left;"> $TSLA At this rate 15 days TSLA could be at$0.00! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:15:13 </td>
   <td style="text-align:left;"> $TSLA Have to see $830 here so we can bottom out </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:13:46 </td>
   <td style="text-align:left;"> $TSLA trending on StockTwits right now in top 6 - saw a significant increase in number of impressions the last 24hrs - should see some strong support. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:13:00 </td>
   <td style="text-align:left;"> $TSLA PUTS AH 🖨🖨🖨 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:12:51 </td>
   <td style="text-align:left;"> $TSLA well I lost my whole portfolio. What also sucks is I should have stuck with my gut and kept my put. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:12:36 </td>
   <td style="text-align:left;"> $TSLA you can still sell and this is still near the top. This is a trillion dollar car company just saying. Before bulls tweet nonsense at me for calling it a car company, just know 93% of their revenue comes from selling cars. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:12:11 </td>
   <td style="text-align:left;"> $TSLA lets get a 40% crash, black monday lfg </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:11:58 </td>
   <td style="text-align:left;"> $TSLA there is only a small portion of stock shorted, who are you going to squeeze? Not too much short to cover. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:11:54 </td>
   <td style="text-align:left;"> $TSLA I’m all in…at 650 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:11:41 </td>
   <td style="text-align:left;"> $TSLA 😓 ouch </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:10:18 </td>
   <td style="text-align:left;"> $TSLA Tesla Fanboys.... look at this as a major opportunity.  You rode this sucker up. Now, ride it down. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:08:21 </td>
   <td style="text-align:left;"> $TSLA today&amp;#39;s volume was 34M average 27M. Selling just started. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:08:08 </td>
   <td style="text-align:left;"> $TSLA 
You can almost see it in the future history books,
“the Carnival Barker‘s”
🤣Donald Trump
🤣Elon musk
🤣😂the ‘Apes’

Bye-bye Bitty!!!!!
🐾🦁🐾 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:08:03 </td>
   <td style="text-align:left;"> $TSLA well on a positive note it’s actually over $4700 had it not split! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:07:52 </td>
   <td style="text-align:left;"> $TSLA guys it’s a dip chill out. 90% of ya’ll should be pulling the trigger like you said you would last time. We 140 upside days on the regular </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:07:30 </td>
   <td style="text-align:left;"> $ARKK  This feels like 00’01  but only for inflated tech like ARKK except $TSLA I remember 00’01 this feels similar but this selling is a lot fasterrr </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:07:22 </td>
   <td style="text-align:left;"> $TSLA 
 
Why are these weak hands cashing out in AH on Friday!!!!!!!!!!!!!!!!!!! 
We have a 308K delivery stat for Q4-21;  
 
and I am pouring myself another glass of wine after Bell!! 
 
Scew Macro -Economics and Earnings misses!! 
 
This Stock, Tesla , is going to the Moon with Giga Berlin, &amp;amp; Austin Factory  openings; and Cybertruck and $25K sports car pending in 2023!!  
 
------------------------------------------------------- 
 
 The tech selloff continued Friday, dragging down a lot of stocks, including shares of Tesla .  https://www.barrons.com/articles/tesla-stock-technical-analysis-tsla-51642776116 via @BarronsOnline </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:07:19 </td>
   <td style="text-align:left;"> $TSLA this is going to 750 after ER </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:06:34 </td>
   <td style="text-align:left;"> $TSLA what a joke. People calling this a value here with a 300x P/E. This is going to 60 bucks and might not even hold that </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:06:18 </td>
   <td style="text-align:left;"> $TSLA becoming a trillionaire in Joe Biden&amp;#39;s administration is an abomination 🤣 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:06:16 </td>
   <td style="text-align:left;"> $TSLA called $930s today and $600-$700 in March. Tell me I’m wrong! Dumb cuck bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:05:57 </td>
   <td style="text-align:left;"> $TSLA 935.5 nibble </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:05:47 </td>
   <td style="text-align:left;"> $TSLA The decline in Tesla hasn’t even started yet </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:05:09 </td>
   <td style="text-align:left;"> $TSLA How easily did we loss 6% today on no news? Well done market with ur fking manipulation 👏 </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:04:38 </td>
   <td style="text-align:left;"> $TSLA Bears, don&amp;#39;t get slaughtered like pigs! Not much upside left for you. You&amp;#39;ve entered oversold territory with ER looming. Doesn&amp;#39;t take much to trigger a squeeze. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:04:32 </td>
   <td style="text-align:left;"> $TSLA I&amp;#39;m a  bull long term, I have massive position but I think she&amp;#39;s going down to 800 so keep hedging bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:04:21 </td>
   <td style="text-align:left;"> $TSLA You bulls better pump this for ER!  I closed my puts today just for you! </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:03:54 </td>
   <td style="text-align:left;"> $TSLA what if btc falls to 30k by  Monday 

Fuckerty fuck fuck bulls </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:03:22 </td>
   <td style="text-align:left;"> $TSLA Bulls…$600 can trade next week.  Don’t think it can’t. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:02:39 </td>
   <td style="text-align:left;"> $TSLA if you tell them to be realistic, they say attack. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:02:05 </td>
   <td style="text-align:left;"> $TSLA $200 buy order </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:01:52 </td>
   <td style="text-align:left;"> $TSLA I’m heavily invested in Tesla, but i’m worried about this up coming earnings with the plummet of Bitcoin. Hopefully Bitcoin reverses to atleast $40000 by then </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:01:24 </td>
   <td style="text-align:left;"> $TSLA started a wave here, crypto doesn&amp;#39;t close, everything connected to the markets now with Trading apps... </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:01:11 </td>
   <td style="text-align:left;"> $TSLA wow btc lol cathie said 100k </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:01:02 </td>
   <td style="text-align:left;"> $TSLA Near to rebound. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:00:59 </td>
   <td style="text-align:left;"> $TSLA https://www.businessinsider.com/tesla-may-start-selling-audio-products-like-headphones-trademark-application-2022-1?international=true&amp;amp;r=US&amp;amp;IR=T </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:00:57 </td>
   <td style="text-align:left;"> $TSLA To make money on TSLA it’s very easy. Just hold for long. If you think you are smart, and plan to buy and sell at the “perfect” time, you will either miss the bus at low or sell too early at high. Just look at the chart. </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:00:53 </td>
   <td style="text-align:left;"> $TSLA what goes up must come down , what goes down always doesn’t just stay down </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:00:32 </td>
   <td style="text-align:left;"> $TSLA CATHY &amp;amp; OTHERS ARE COMING. JUST WATCH NOW </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:00:28 </td>
   <td style="text-align:left;"> $TSLA you will see pre pandemic prices again </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 07:00:26 </td>
   <td style="text-align:left;"> $TSLA Shoutout to all the bulls that blocked me </td>
  </tr>
  <tr>
   <td style="text-align:left;"> TSLA </td>
   <td style="text-align:left;"> 2022-01-22 06:59:38 </td>
   <td style="text-align:left;"> $SPY $TSLA $AAPL $AMZN </td>
  </tr>
</tbody>
</table></div>

---
